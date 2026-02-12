# Deploy plan

## Pre-deploy
- Run test suite and fix failures.
- Build release artifact; store in artifact store.
- Create version tag and push to repo.

## Staging
- Run deploy pipeline (CI or manual job).
- Deploy to staging environment.
- Smoke-test and run integration tests.
- Sign off before production.

## Production
- Promote build to production.
- Check health and metrics; confirm rollback procedure.
- Notify team and update release notes.

## Rollback
- Revert to previous tag or artifact; redeploy.
- Verify service and notify.
