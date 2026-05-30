# Drupal Project Preferences

## General Rules
- Never suggest upgrading major Drupal versions without checking module compatibility first
- Always check contributed module versions before suggesting core updates
- Prefer conservative, tested solutions for production sites

## Composer Updates
- Use `composer update -w` for updates with dependencies
- Check security advisories but consider module compatibility impact
- For Drupal 10 sites: verify all contrib modules support the target version before upgrading

## Site-Specific Notes
- Indiana Furniture site: Drupal 10, check module compatibility before any major updates
