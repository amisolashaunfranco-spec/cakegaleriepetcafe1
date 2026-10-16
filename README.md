# Cake Galerie Pet Café

A pet café reservation and ordering website built with HTML, CSS, and JavaScript.

This repository contains the browser demo for GitHub Pages.

## Features

- Browse and search the café menu.
- Add products to a shopping basket.
- Place pickup or delivery orders.
- Select delivery destinations on a map.
- View order status and manually updated rider locations.
- Reserve café seats by date, time, and guest count.
- View pet profiles and availability.
- Manage menu items, pets, orders, reservations, and user roles.
- Upload menu and pet photos from device files.
- Export management records as CSV.
- Responsive layouts and reduced-motion support.

**Pets are display-only. Customers reserve café seats without selecting or booking a pet.**

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Leaflet
- OpenStreetMap
- Nominatim
- OSRM

## Publish on GitHub Pages

1. Upload the extracted website files to the repository root.
2. Ensure `index.html` and the `assets` folder are at the top level.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose **main** and **/(root)**, then save.
6. Check **Actions** for a successful deployment.
7. Open **Visit site** from the Pages settings.

Leave the custom domain field blank when using GitHub’s default address.

## Demo Accounts

| Role | Email | Password |
|------|-------|----------|
| Administrator | admin@cakegalerie.test | Admin123! |
| Staff | staff@cakegalerie.test | Staff123! |
| Customer | guest@cakegalerie.test | Guest123! |

## Demo Limitations

Records and uploaded photos are saved in the current browser. They are not shared between devices.

Demo authentication is illustrative. Use fictional customer information.

Delivery tracking uses staff-entered coordinates rather than live GPS. Maps require internet access.

Payments are cash on delivery or at pickup.

The full Node.js and SQLite system requires separate server hosting.

## Credits

This is an independent educational project, unaffiliated with Cake Galerie or Studio Ghibli.

See [ASSET-CREDITS.md](ASSET-CREDITS.md) for image, mapping, and software credits.
