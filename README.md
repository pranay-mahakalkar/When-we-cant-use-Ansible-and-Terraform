# When-we-cant-use-Ansible-and-Terraform

Scenario: Automated File Backup

Suppose you're tasked with creating an automated file backup system for a small company's important documents. This system should periodically back up specific folders to a remote server or cloud storage for data redundancy and disaster recovery.

Using Ansible: Ansible is typically used for configuration management and automation of tasks across multiple servers. While you can use Ansible to trigger backup scripts on multiple servers, it's not designed for automating file-level backups and remote storage.

Using Terraform: Terraform is focused on infrastructure provisioning and isn't suitable for managing file backups and storage.

Using Python: Python is an ideal choice for this scenario. You can write custom Python scripts to:

Periodically scan designated folders for changes.
Compress and encrypt the changed files.
Upload the backups to a remote server or cloud storage.
Log backup activities and generate reports.
