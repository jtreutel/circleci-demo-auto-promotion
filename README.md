# circleci-demo-auto-promotion
Demo of automatic promotion to higher environments.

## Requirements

These environment vars must be set at the project level in CircleCI:

- `AWS_REGION`
- `CIRCLE_TOKEN`

These contexts should be configured:

- `test-dev-vars`
- `test-staging-vars`
- `test-prod-vars`

and should each contain these two vars:

- `ENV_NAME`
- `S3_BUCKET`