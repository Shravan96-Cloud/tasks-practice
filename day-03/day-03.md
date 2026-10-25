# Day 3 — Linux Permissions and Ownership Practice

**Objective:** Practice directory management, file creation, modifying file permissions, changing ownership, and understanding user privileges as part of the 90-day Cloud & DevOps engineering roadmap[cite: 16].

**Repository:** `tasks-practice`

### Instructions
Complete these tasks inside your `day-03` folder.

1. **Setup Directory:** Create a directory named `day-03` and navigate inside it.
2. **Create Files:** Create two new files named `secure-script.sh` and `service-config.txt`.
3. **Numeric Permissions:** Using the numeric (octal) method, change the permissions of `secure-script.sh` so that the owner has full permissions (read, write, execute), but the group and others have absolutely zero permissions.
4. **Symbolic Permissions:** Using the symbolic method (letters), ensure `service-config.txt` allows the owner to read and write, while the group and others can only read.
5. **Change Ownership:** Change the ownership of `service-config.txt` so that the `root` user is the owner (you will need to borrow superuser privileges for this).
6. **Verification:** Verify your permission and ownership changes by displaying the directory contents in long format.

### Completion Criteria
All files must be in the `day-03` directory and have the exact specified permissions and ownership verifiable via terminal output.
