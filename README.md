# Fire

Transfers files via SFTP from working directory to NFORS

Copies files to a separate working directory for ALASTAR project (This is a handoff point to applications team).

Keeps a database of what files have been transferred and copied respectively.

cron.lock files are to prevent race conditions in cron scheduled jobs.