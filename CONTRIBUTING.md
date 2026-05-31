# Contributing

Thanks for considering contributing!

## Setup

```bash
git clone https://github.com/navinavi029/AI-Coding-Assistant-API.git
cd AI-Coding-Assistant-API
run.bat
```

## PR Process

1. Create a branch: `git checkout -b feat/my-feature`
2. Make changes with tests
3. Run tests: `docker-compose exec assistant mvn test`
4. Open a pull request

## Conventions

- **Commits**: Conventional Commits (`feat:`, `fix:`, `chore:`, `docs:`, etc.)
- **Java**: Google style, 4-space indent, 120-char line limit
- **Testing**: JUnit 5 + Mockito for unit tests; MockWebServer for API client tests

See [pull_request_template.md](.github/pull_request_template.md) for the PR checklist.
