# renovate-12334-lockfile-maintenance-pr

This repo intentionally has an outdated `bytes` version in its `Cargo.lock`
to test the `lockFileMaintenance` feature of renovate.

Note: `bytes` is a transitive dependency, this crate only depends on `tokio-test`.
