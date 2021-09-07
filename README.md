# getting started

Volg deze stappen om de pre launch test werkend te krijgen bij jou.

## Installation

Zorg dat je xampp/mamp aan staat.

Begin met het .sql bestand uit te voeren in een mysql database bijv. tableplus.

Zorg dat je laravel op je pc hebt staan en dat het werkt

Zorg dat je .env bestand goed is ingesteld voor jou database connectie (database name, host, wachtwoord enz.)

## Usage

ga in de folder van het project en open je terminal en voer de onderstaande stappen uit
```bash
composer install
```
nu moeten alle composer bestanden gedownload zijn.

doe nu

```bash
cp .env.example .env
php artisan key:generate
php artisan migrate:fresh
php artisan storage:link

php artisan serve
```

nu moet de server aan staan en alles werkt nu
