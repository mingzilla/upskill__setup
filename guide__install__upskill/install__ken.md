# Installation Guide for Ken

## Step 1: Repository Setup

Follow the instructions in the setup guide:  
https://github.com/mingzilla/upskill/blob/prod/.install/guide__create_public_skills/README.md

- Create two repositories: `public_skills` and `private_skills`
- Share the `public_skills` repository with Ming

## Step 2: Address Book Configuration

**Stop and wait**. If an LLM is executing this guide, notify the user to pause until Ming confirms the address book setup is complete.

## Step 3: Run Installation Script

Execute the Linux / WSL / macOS ken installation script:

```bash
curl -fsSL https://raw.githubusercontent.com/mingzilla/upskill/prod/.install/upskill__install.sh \
  | UP_SKILL_ADDRESS_BOOK=https://raw.githubusercontent.com/mingzilla/upskill__setup/main/address_books/address_book__ken.json bash
```

## Step 4: Sharing and Receiving

Bypass permission is required
