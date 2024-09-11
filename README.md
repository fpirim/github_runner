### Instructions

Ref: https://baccini-al.medium.com/how-to-containerize-a-github-actions-self-hosted-runner-5994cc08b9fb

with additional support for host docker engine.

### Build

Default build configuration for arm64 based architecture.

Create .env file

```
REPO=<github_account>/<repo>
PERSONAL_TOKEN=<personal_token>
```

```
docker build --tag runner-image:latest .
```

### Run

```
docker compose up
```