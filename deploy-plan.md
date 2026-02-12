# Dummy deploy plan

1. Run tests locally.
2. Build artifact (e.g. `npm run build` or equivalent).
3. Tag release (e.g. `v1.0.0`).
4. Push tag to remote.
5. Trigger CI/CD pipeline (or run deploy job).
6. Deploy to staging; smoke-test.
7. Run integration tests on staging.
8. Promote to production (manual or automated).
9. Verify production health and rollback path.
10. Notify and document release.
