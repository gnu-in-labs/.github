# Contributing

Thanks for taking the time to look closely. GNU.IN work is experimental, agent-assisted, and still becoming public in stages, so specific corrections are more useful than broad approval.

## Before Opening a Pull Request

- Read the public profile and repository README.
- Check whether an issue or discussion already covers the topic.
- Reproduce the problem locally when the change is technical.
- Open an issue first when the change affects project stance, security boundaries, release policy, public claims, or live-runtime behavior.

## Branches

Recommended branch prefixes:

- `feat/...`
- `fix/...`
- `docs/...`
- `security/...`
- `chore/...`

## Commits

Recommended commit prefixes:

- `feat:`
- `fix:`
- `docs:`
- `refactor:`
- `test:`
- `security:`
- `chore:`

## Acceptance Criteria

A useful contribution should make the project easier to inspect, test, explain, or operate.

Before requesting review, check:

- formatting is applied;
- relevant lint or tests pass;
- docs are updated when public behavior or claims change;
- security-sensitive changes describe the risk boundary;
- user-facing changes include release notes or changelog notes when appropriate.

## Pull Requests

Every PR should explain:

- the problem;
- the decision;
- the risk boundary;
- how it was tested;
- what remains unverified;
- any migration, rollback, or release impact.

Agent-assisted work is welcome, but generated output is not proof. If an agent helped, the PR should still be readable, reviewable, and backed by evidence.
