# Backup Note

**Source:** https://github.com/ultraworkers/claw-code
**Target:** https://github.com/greycheer/claw-code
**Date:** 2026-04-02

## Files Backed Up

- README.md â€“ repository overview
- CLAW.md â€“ claw system documentation
- PARITY.md â€“ porting parity checklist
- .gitignore â€3 git ignore rules

## Manual Backup Steps
If automated backus is incomplete, run:

```sh
# Clone source
git clone https://github.com/ultraworkers/claw-code.git claw-code-backup

# Add your remote
cd claw-code-backup
git remote add myrepo https://github.com/greycheer/claw-code.git

# Push to your repo
git push myrepo main --force
```

## Repository Structure

```
../
- src/                     # Python source code
- rust/                    # Rust port
- tests/                   # Tests
- assets/                  # Images and assets
£ .github/                   GitHub workflows
```

## Note

Repository created by Claw AI - backup in progress.