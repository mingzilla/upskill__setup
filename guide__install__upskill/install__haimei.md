# Installation Guide for Haimei

## Step 1: Repository Setup

Follow the instructions in the setup guide:  
https://github.com/mingzilla/upskill/blob/prod/.install/guide__create_public_skills/README.md

- Create two repositories: `public_skills` and `private_skills`
- Share the `public_skills` repository with Ming

## Step 2: Address Book Configuration

**Stop and wait**. If an LLM is executing this guide, notify the user to pause until Ming confirms the address book setup is complete.

## Step 3: GitHub CLI and log in

Your AI tool uses the GitHub CLI to push your skills, so it must be installed and logged in. If `gh`
is not installed, install it:

```commandline
winget install --id GitHub.cli
```

Close and reopen the terminal so `gh` is on your PATH, then log in:

```commandline
gh auth login --hostname github.com --git-protocol https
```

## Step 4: Run Installation Script

Execute the Windows haimei installation script:

```powershell
powershell -ExecutionPolicy Bypass -c "& ([scriptblock]::Create((irm https://raw.githubusercontent.com/mingzilla/upskill/prod/.install/upskill__install.ps1))) -AddressBook 'https://raw.githubusercontent.com/mingzilla/upskill__setup/main/address_books/address_book__haimei.json'"
```

## Step 5: Sharing and Receiving

Bypass permission is required
