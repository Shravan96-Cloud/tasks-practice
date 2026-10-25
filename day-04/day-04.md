# Day 4 — Processes and Services Practice

**Objective:** Practice managing background processes, safely terminating applications, and inspecting system services as part of the 90-day Cloud & DevOps engineering roadmap[cite: 16].

**Repository:** `tasks-practice`

### Instructions
Complete these tasks inside your `day-04` folder.

1. **Setup Directory:** Create a directory named `day-04` and navigate inside it.
2. **Start a Background Process:** Start a process that sleeps for 3600 seconds, and ensure it runs in the background so you can keep using your terminal.
3. **Find the PID:** Search your currently running processes to find the exact Process ID (PID) of the sleep command you just started.
4. **Terminate the Process:** Safely terminate (kill) that specific sleeping process using its PID.
5. **Verify Termination:** Search your running processes again to verify the sleep command is no longer running.
6. **Check Service Health:** Check the current health/status of the `cron` service on your system.
7. **Query Service Logs:** Query the system logs to display only the last 5 log entries specifically belonging to the `cron` service.

### Completion Criteria
The background sleep process must be successfully started and completely terminated, and you must be able to view the recent logs of the `cron` service without errors.
