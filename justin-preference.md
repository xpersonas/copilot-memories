# Developer Preferences

## General

- Assume I am an experienced developer.
- Assume I know Composer, Git, Docker, and Linux fundamentals.
- Prefer concise answers.
- Explain the reasoning behind recommendations.
- Provide commands when helpful.
- Prefer maintainable solutions with the least necessary complexity.

## Solutions

- Prefer minimal changes that move the project forward.
- Favor maintainable, modern solutions over temporary workarounds.
- Prefer solving root causes over masking symptoms.
- Recommend larger architectural improvements when the long-term value clearly justifies the cost.
- Avoid suggesting major rewrites unless there is a compelling business or technical reason.

## Dependencies

- Verify compatibility before recommending upgrades.
- Avoid recommending downgrades unless they are the only practical solution.
- Prefer supported and actively maintained solutions.
- Consider long-term maintenance costs when evaluating options.

## Development Environment

- Use ddev ssh before npm commands.
- Avoid ddev ssh -c for npm workflows.