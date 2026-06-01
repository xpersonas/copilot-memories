# DDEV Project Preferences

## DDEV Commands
- **PHP/Artisan commands**: Always use `ddev ssh` first, then run PHP commands inside the container
  - Example: `ddev ssh` then `php artisan --version`
  - Or use: `ddev exec php artisan --version`
- **NPM commands**: Always use `ddev ssh` first, then run npm commands inside the container
- **NEVER** use `ddev ssh -c` - it never works reliably
- **NEVER** use `ddev -c` for npm commands
- Example: `ddev ssh` then `cd web/themes/custom/inf2021 && npm install`
