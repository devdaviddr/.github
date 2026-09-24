# .github

Default issue forms and pull request template for every public `devdaviddr` repo that
doesn't define its own in `.github/`.

## How issues are organised

Product work in each repo is a tree of issues:

- `[Pillar]` issues (label `pillar`) are the main phases of what the repo does.
- `[Capability]` issues (label `capability`) sit under a pillar and describe something users can do.
- `[Feature]` issues (label `feature`) sit under a capability, and each one covers one job a user can get done.

A capability or feature that isn't fully shipped also carries `gap`. For these, an open
issue means the thing is still missing and a closed one means it has shipped. Each
feature links to the spec that defines it and lists the PRs that shipped it.

Four kinds of issue sit outside the tree, and each has a form here:

- **Bug** (`[Bug]`, labels `bug` and `user-report`): something that exists and is broken.
- **Change request** (`[Change]`, labels `enhancement` and `user-report`): new or different behaviour.
- **Chore** (`[Chore]`, label `chore`): internal work such as refactors, dependencies, tooling, tests or docs.
- **Spike** (`[Spike]`, label `spike`): time-boxed research that ends in a decision.

Pillar, capability and feature issues are written when a repo's features are mapped,
so they don't have forms.

The work is tracked on the private project board **devdaviddr — Public repos**
(github.com/users/devdaviddr/projects/11), which has Status, Priority, Size and Target date fields.
