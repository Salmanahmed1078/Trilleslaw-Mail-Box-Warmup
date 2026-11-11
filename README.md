# Trilles Law mailbox warm-up

Automatic Gmail warm-up for `awais@trilleslaw.com` and `salman@trilleslaw.com`, run by GitHub Actions and triggered hourly by cron-job.org.

- Code and config: [`warmup/`](warmup/) (see `warmup/README.md`)
- Schedule: `.github/workflows/warmup.yml`
- How the whole system works: [`GMAIL_WARMUP_PLAYBOOK.md`](GMAIL_WARMUP_PLAYBOOK.md)

Status: set-up in progress. Dry-run only until `github_actions_live` is set to `true` in `warmup/config.yaml`.
