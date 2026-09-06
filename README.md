# Course Stack — Week 2 Setup Record

## Environment
- Date: September 01, 2026
- Operating system and version: macOS Tahoe 26.6.2
- Docker Desktop version: 29.7.2
- Git commit hash for this setup: b4c5c0ae47c358a2d642b6474ec75f88a94b5671

## Service verification
| Service | Endpoint or command | Result | Evidence filename or safe note |
|---|---|---|---|
| Baserow | http://localhost:8080 |  |  |
| n8n | http://localhost:5678 |  |  |
| ToolJet | http://localhost:3000 |  |  |
| labs Postgres | `docker compose exec labs-postgres psql -U student -d labs -c "SELECT version();"` |  |  |

## Local changes and troubleshooting
- Port changes made, if any: 0
- Problem encountered: 1
- Diagnostic command used: 0
- Resolution or current next step: Watch resource usage and laptop temps and fix if needed

## Security check
- `.env` is ignored and was not committed: yes / no
- Screenshots and documentation were reviewed for secrets: yes / no

