# Royal Cinema · Vercel static deployment

## Files

- `index.html` — customer cinema site
- `city_lite_cinema_erp_multi_counter_role_login.html` — Super Admin / Branch Manager workspace
- `city_lite_f_b_counter_pos_role_login.html` — F&B Counter POS
- `city_lite_cinema_erp_command_center_role_login.html` — Ticketing / Entry workspace
- `vercel.json` — route aliases (`/super-admin`, `/pos`, `/ticketing`)

## Deploy

Upload this folder to a Git repository and import that repository in Vercel. Choose **Other** as the framework preset, leave the build command empty, and use `.` as the output directory. `index.html` is the home page.

## Demo and live backend

When the booking API returns 404 or cannot be reached on a `*.vercel.app` preview, checkout issues a clearly marked demo ticket saved only in that browser. It does not charge money or create a shared cinema booking. For live accounts, shared bookings and real payment capture, connect the cinema backend endpoints `/api/auth/register`, `/api/auth/login`, and `/api/bookings/confirm`, plus a persistent database and payment gateway.
