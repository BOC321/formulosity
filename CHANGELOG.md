# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

### Changed
- Updated `fly.toml` to set `sslmode=require` for the Supabase database connection.
- Created `.env.production` in the `ui` directory to set the production API URL to `https://ttasurvey.fly.dev`.
- ci: Add `lint-ui` and `test-ui` jobs to GitHub Actions workflow to lint and test the UI.
- ci:- Add caching for Go modules and npm packages to CI.
- Fix failing tests in the `parser` package.speed up CI jobs.
- ci: Add Go code coverage reporting to the CI pipeline.