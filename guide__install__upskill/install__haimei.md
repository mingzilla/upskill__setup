# Installation Guide for Haimei

## Step 1: Repository Setup

Follow the instructions in the setup guide:  
https://github.com/mingzilla/upskill/blob/prod/.install/guide__create_public_skills/README.md

- Create two repositories: `public_skills` and `private_skills`
- Share the `public_skills` repository with Ming

## Step 2: Run Installation Script

Execute the Linux haimei installation script:

```powershell
powershell -ExecutionPolicy Bypass -c "& ([scriptblock]::Create((irm https://raw.githubusercontent.com/mingzilla/upskill/prod/.install/upskill__install.ps1))) -AddressBook 'https://raw.githubusercontent.com/mingzilla/upskill__setup/main/address_books/address_book__haimei.json'"
```

## Step 3: Sharing and Receiving

Bypass permission is required
