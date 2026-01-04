# AI Context Brain

**Project**: WordPress Simple Customise Helper
**Type**: Modular WordPress Plugin (PHP/React)
**Purpose**: General WordPress customizations (Non-WooCommerce specific).

## Architecture
- **Modular**: Feature-based modules in `includes/modules/`.
- **Hybrid**: PHP backend + React Admin UI.

## Key Structures
- `includes/class-wsch-core.php`: Plugin loader.
- `includes/admin/class-wsch-settings-page.php`: Admin Menu & React Root.
- `includes/api/class-wsch-rest-controller.php`: Settings REST API.
- `src/components/SettingsApp.js`: React App Entry.

## Workflows
- **Build**: `npm run build`
- **Lint**: `php -l <file>`

## Conventions
- **Prefix**: `WSCH_` (WordPress Simple Customise Helper).
- **Style**: React functional components, PHP snake_case.
- **UI**: Use `@wordpress/components`.
