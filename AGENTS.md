# AGENTS.md — jquery_hide_show_password

## What this is
A lightweight jQuery plugin (jQuery 4 compatible) that toggles the visibility of password input fields, with `showPassword`/`hidePassword`/`togglePassword` methods and an optional inner toggle button.

## Stack
- JavaScript (jQuery plugin)
- jQuery 4.0+

## Run
Include `jquery_hide_show_password.min.js` (or `.js`) after jQuery, then call `$('#password').hideShowPassword(true, true)`.

## Structure
- `jquery_hide_show_password.js` — plugin source
- `jquery_hide_show_password.min.js` — minified build
- `css/`, `images/`, `pages/` — demo assets
- `index.html` — demo page
- `bower.json` / `package.json` — package metadata

## Conventions
- No comments in code unless asked.
- Verify: `npm run minify` regenerates the min file.
