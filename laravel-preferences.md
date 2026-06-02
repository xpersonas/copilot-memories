## Laravel Project Preferences

- Prefer Laravel conventions over custom abstractions.
- Prefer clear PHP over overly clever framework magic when readability or maintainability improves.
- Use built-in Laravel features before adding packages.
- Avoid service/container abstractions unless they solve a real complexity problem.
- Always ask if Tinker is available before suggesting `php artisan tinker` commands — some sites do not have it installed.