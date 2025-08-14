# SQL Server Lab

Practical scripts for SQL Server: filegroups/partitions, index strategies, backup/restore chains, DB Mail, Agent jobs, and RPO/RTO drills.

## Getting Started
- Open `scripts/partitioning/create_partitioned_table.sql`
- Run backups from `scripts/backup/`
- Use the troubleshooting playbooks in `/docs/playbooks`

## CI
- `sqlfluff` lints T-SQL for style
- PowerShell analyzer checks scripts

## Roadmap
- [ ] Add tsqlt unit tests
- [ ] Add performance baseline collector (Python + pyodbc)
