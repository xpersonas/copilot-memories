# GitHub Copilot Memory Files

Personal preferences and rules for GitHub Copilot across all workspaces and conversations.

## What is this?

These files are part of GitHub Copilot's persistent memory system. They teach Copilot my coding preferences, common workflows, and learned patterns. The first 200 lines are automatically loaded into Copilot's context.

## Files

- **css-preferences.md** - CSS/styling conventions and preferences
- **ddev-preferences.md** - DDEV local development environment practices
- **drupal-preferences.md** - Drupal-specific development rules
- **justin-preference.md** - General personal coding preferences
- **laravel-preferences.md** - Laravel framework conventions
- **wordpress-preferences.md** - WordPress development practices

## Usage

These files live in:
```
~/Library/Application Support/Code/User/globalStorage/github.copilot-chat/memory-tool/memories/
```

Copilot automatically reads these files when providing assistance. Update them as you learn new patterns or encounter recurring issues.

## Best Practices

- Keep entries concise (brief bullets, not prose)
- Record lessons learned from mistakes
- Document tool-specific quirks and workarounds
- Update or remove outdated information
- Organize by topic/technology in separate files
