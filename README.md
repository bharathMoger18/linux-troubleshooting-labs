# Linux Troubleshooting Labs

Hands-on Linux troubleshooting labs — breaking and fixing real production scenarios exactly like a senior engineer at Google, Amazon or Microsoft.

## Structure

Each lab has 3 files:
- `break.sh` — script that breaks the system
- `fix.sh` — script that fixes it
- `notes.md` — what happened, root cause, commands used

## Phase 1 — Process & Service Troubleshooting

| Lab | Scenario | Status |
|-----|----------|--------|
| Lab 1 | Service crash — nginx fails to start | 🔄 In Progress |
| Lab 2 | Zombie process — dead but not reaped | ⏳ Pending |
| Lab 3 | CPU spike — process eating 100% CPU | ⏳ Pending |
| Lab 4 | Orphan process — parent dies, child survives | ⏳ Pending |

## Troubleshooting Methodology

Every lab follows the senior engineer approach:
1. Observe — never touch blindly
2. Gather data — logs, process state, resources
3. Isolate — narrow down the root cause
4. Fix — minimum risk solution
5. Prevent — make sure it won't happen again

## Tools Used

`systemctl` `journalctl` `ps aux` `top` `htop` `strace` `lsof` `ss` `kill` `dmesg` `/proc`
