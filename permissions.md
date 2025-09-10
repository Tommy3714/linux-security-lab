# Linux Security Lab – File Permissions

This lab demonstrates applying restrictive permissions to secure directories and files.

## Steps
- Created secure directory: `mkdir secure_users`
- Added sensitive file: `touch users.txt`
- Applied restrictive permissions:
  - `chmod 600 users.txt` → owner-only read/write
  - `chmod 700 secure_users/` → owner-only full access
- Verified results with:
  - `ls -l users.txt`
  - `ls -ld secure_users/`

## Outcome
Only the file/directory owner has access, effectively locking down sensitive data.

## Skills Demonstrated
- Linux system hardening  
- Access control (principle of least privilege)  
- Security validation using system commands
