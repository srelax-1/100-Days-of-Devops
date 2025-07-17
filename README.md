# 100-Days-of-Devops
## Day 1: Linux User Setup with Non-Interactive Shell
**Task:** To accommodate the backup agent tool's specifications, the system admin team at xFusionCorp Industries requires the creation of a user with a non-interactive shell. 
**Here's your task:** Create a user named jim with a non-interactive shell on App Server 3

**Solution:** I have been tasked with creating a user named `jim` on App Server 3 with a non-interactive shell. The non-interactive shell will prevent the user from logging in interactively, which is suitable for system processes or services that need to perform tasks without requiring user interaction.
What i did was to run the following command on App Server 3 after logging in:
```bash
sudo useradd -s /sbin/nologin jim
```

## Day 2: Day 2: Temporary User Setup with Expiry
**Task:** 
**Solution:**

## DDay 3: Secure Root SSH Access
**Task:** 
**Solution:**

## Day 4: Script Execution Permissions
**Task:** 
**Solution:**

## Day 5: SElinux Installation and Configuration
**Task:** 
**Solution:**

## Day 6: Create a Cron Job
**Task:** 
**Solution:**