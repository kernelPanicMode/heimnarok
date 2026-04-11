### *Valhalla Certified™ – For Mortal Homes*

> *"Even the All-Father needs to keep track of the mjød budget."*

Heimnarok™ is a privacy-first, self-hosted household management app for the modern Viking family. Track budgets, receipts, meals, shopping, tasks, vehicles, and more — all on your own server, with zero subscriptions and zero cloud dependencies.

**No tracking. No cloud. No nonsense. Odin approved. ⚡**

🔗 **[Try the live demo](https://kernelPanicMode.github.io/heimnarok/demo/)** — Norse-themed demo data included. PIN: `1234`

---

## The Heimnarok™ Series

Heimnarok™ is a single-file SPA platform. All apps in the series share the same visual identity, theme system, i18n engine, and component library — built from a common base template.

| App | Purpose | Status |
|-----|---------|--------|
| **Heimnarok™** | Full household management | ✅ Released |
| **Cashnarok** | Budget-only, lightweight sibling | ✅ Released |
| *(new apps)* | Built from `heimnarok-template.html` | 🔨 In development |

`heimnarok-template.html` in this repository is the official starting point for new apps in the series — includes all CSS tokens, component styles, the full 11-language i18n engine, theme controls, module navigation, modal system, and localStorage-based persistence. Ready to fork and build.

---

## Heimnarok™ vs. Cashnarok

| | Cashnarok ⚔️ | Heimnarok™ 🛡️ |
|---|---|---|
| **Spirit** | The younger brother — light, fast, and deadly focused | The older, wiser one who also remembered to eat |
| **Budget tracking** | ✅ | ✅ |
| **Statistics** | ✅ | ✅ |
| **Receipts** | ✅ | ✅ |
| **Savings goals** | ❌ | ✅ |
| **Meal planner** | ❌ | ✅ |
| **Shopping lists** | ❌ | ✅ |
| **Task list** | ❌ | ✅ |
| **Information vault** | ❌ | ✅ |
| **Vehicle management** | ❌ | ✅ |
| **Freezer inventory** | ❌ | ✅ |
| **Multi-language** | ❌ | ✅ 11 languages |
| **User accounts** | ❌ | ✅ |
| **File attachments** | ❌ | ✅ |

Think of Cashnarok as Mjølner — compact and devastating. Heimnarok™ is the entire Asgard armory.

---

## Features

### 💰 Household Budget
Monthly budget sheets with income and expense tracking. Compare budgeted vs. actual amounts, toggle payment status, assign expenses to household members, and use a reusable template (MAL) so you only have to set up your recurring expenses once. Like Odin's ravens — set it up once and let it fly.

- Budgeted vs. actual with automatic variance column
- Expense types: Fixed, Variable, Estimated, Temporary
- Per-member assignment and owner filter
- Monthly notes + permanent sticky note
- Savings goal widget on the budget page
- Vehicle reminder widget (upcoming EU inspection / service) with colour-coded urgency

### 📊 Statistics
Because even Thor wants to know why the lightning bolt bill keeps going up.

- Period selector: 3M / 6M / 1Y / 2Y / 5Y / 10Y / All
- Summary cards: average income, expenses, savings, and savings rate
- Five charts: income/expenses over time, monthly balance, by expense type, by owner, cumulative savings

### 🧾 Receipts
Store receipts with vendor, amount, payment method, tags, and file attachments (images and PDFs up to 20 MB). Live search and tag filtering. Because "Loke made me do it" is not a valid tax deduction.

### 📋 Savings Goals (Formålsbudsjett)
Track savings goals and purpose-specific budgets separately from the monthly budget. Monitor progress with a visual breakdown — whether you're saving for a Mjølner upgrade or a bathroom renovation.

### 🍽️ Meal Planner
Plan meals like a Valkyrie manages the feast hall — efficiently and without casualties.

- Recipe database with ingredients, quantities, calories, and estimated cost
- Ingredient catalogue with cross-recipe search and rename
- Weekly meal plan — navigate weeks, copy from previous week
- Push the week's ingredients directly to the shopping list
- Favourite recipes, usage counter, and last used date

### 🛒 Shopping Lists
Multiple named lists with drag-to-reorder. Check items off, clear checked items in one tap. The meal planner auto-fills an "Ukesmeny" list with that week's ingredients.

### ✅ Task List
Tasks with title, description, due date, and colour label. Filter by status and owner. Searchable via global search (Ctrl+K). Unlike Loke's promises, these actually get done.

### 🔐 Information Vault
Secure local storage for sensitive household information — passwords, insurance policy numbers, activation codes, WiFi credentials. Category sidebar with entry count badges. Accordion view. Searchable. No cloud. Only Odin can see it (and he's got one eye on it at all times).

### 🚗 Vehicles
The most thorough vehicle module you'll find outside of Statens Vegvesen. Supports cars, motorcycles, ATVs, snowmobiles, trailers, and anything else with wheels (or hooves).

**11-tab detail view per vehicle:**

| Tab | Contents |
|-----|----------|
| 🔧 Technical | Reg. number, brand, model, year, fuel, colour, engine, VIN, weight, purchase date, tank size |
| 📋 Custom fields | Add your own key/value fields |
| 📝 Notes | Freetext note with auto-save |
| 🔩 Repairs | Log with date, odometer, description, cost + yearly cost chart |
| 🛠 Service | Service log + cost report with chart + next service date tracking |
| ⛽ Fuel | Fill-up log with L/100km calculation, stat cards, three chart types, period filter |
| ✅ EU Inspection | Inspection log with next due date |
| 🔵 Tyres | Summer/winter tyre sets, tyre pressure, tyre inventory with age tracking, change log, rotation log |
| 📄 Documents | Upload and view documents and images |
| 🔔 Reminders | Toggle EU and service reminders per vehicle |
| 💰 Economy | Total ownership cost estimation — forward-looking stacked bar chart |

**Summary strip** — colour-coded status for next EU inspection, next/last service, last fill-up, last tyre change, and last tyre rotation.

**Cost reports** (Repairs & Service): total, average per year, average per event, highest single entry — bar chart by calendar year with a dashed average line. Period filter: 1Y / 3Y / 6Y / 8Y / 10Y / All.

**Fuel statistics**: average per month (highlighted), average L/100km, kr/km, total cost, total litres, estimated range, fill-up percentage. Efficiency chart with green/red colouring against average. Three chart modes: monthly cost, monthly litres, L/100km trend. Period filter: 1Y / 3Y / 6Y / 8Y / 10Y / All.

**Economy tab**: fixed monthly costs (loan, insurance, toll, parking, custom) with optional end dates — cost disappears from the chart automatically when the end date passes. Fuel and repair/service costs estimated from actual log data with the exact calculation shown. Forward-looking stacked bar chart (6M / 1Y / 2Y … 10Y / All) breaks costs into colour-coded categories. EV support: home charging estimated from km × kWh × price, plus separate fast-charging / subscription field. Tyre rotation and next service tracking integrated.

### 🧊 Freezer Inventory
Log frozen items with storage date, best-before date, and notes. Freshness indicators (green / yellow warning / red expired). Configurable thresholds per household. Because nobody wants to discover Loke's mystery meat from 2024.

### ⛽ Fuel Quick-Log (FAB)
An optional floating action button for rapid fuel fill-up logging. Assign a default vehicle in settings, tap the button anywhere in the app, and log in seconds.

### 🔍 Global Search (Ctrl+K)
Search across budget entries, receipts, tasks, vault, vehicles, meal recipes, and shopping lists — from anywhere in the app.

---

## Interface

- **11 languages** — Norwegian (Bokmål), Nynorsk, English, German, Spanish, French, Danish, Swedish, Viking (Old Norse), Kebabnorsk, and Trumpese
- **Dark / Light mode** — saved per user
- **High contrast mode** — for accessibility
- **Currency selector** — NOK, SEK, DKK, ISK, EUR, USD, GBP, CHF
- **Module toggle** — enable/disable individual modules in settings
- **Per-user settings** — language, theme, currency, and modules saved per account (user mode)
- **Responsive** — works on desktop and mobile

---

## Authentication

| Mode | Use case |
|------|----------|
| **PIN** | Shared 4-digit PIN — suitable for private home network or VPN |
| **Username + password** | bcrypt-hashed accounts — suitable for public-facing servers |
| **Role-based access** | Admin manages users and global settings; regular users control only their own preferences |

---

## Tech Stack

No Yggdrasil required. Just a basic LAMP server.

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML / CSS / JavaScript — no frameworks (~13 500 lines) |
| Charts | Custom SVG + Chart.js 4 (statistics module) |
| Backend | PHP 8 — single `api.php` REST endpoint |
| Database | MariaDB via PDO |
| Server | Apache2 with `mod_rewrite` |
| Auth | PHP sessions — PIN or bcrypt user accounts |
| Hosting | Proxmox LXC — Debian 12 (recommended) |

All database tables are created automatically on first use. No manual migrations. Ever. Ragnarok may come, but you won't have to run `ALTER TABLE`.

---

## Installation — Debian 12 / Proxmox LXC

A detailed guide with troubleshooting is available in `server/howto.html`.

### 1. Create a Debian 12 LXC in Proxmox

| Setting | Recommended |
|---------|-------------|
| Template | `debian-12-standard` |
| Disk | 8 GB |
| RAM | 256 MB |
| Network | DHCP, bridge `vmbr0` |

### 2. Copy files to the container

```powershell
# From Windows PowerShell inside the server/ folder
scp index.html api.php install.php .htaccess install.sh howto.html `
    root@<CONTAINER-IP>:/root/budsjett/
```

> **Important:** Always SCP files before running `install.sh`. The script copies from `/root/budsjett/` to `/var/www/html/`.

### 3. Run the installer

```bash
cd /root/budsjett
chmod +x install.sh
bash install.sh
```

This automatically installs Apache2, PHP 8, and MariaDB, creates the `budsjett` database with a randomly generated password, and configures everything.

### 4. Run the web installer

```
http://<CONTAINER-IP>/install.php
```

### 5. Open the app

```
http://<CONTAINER-IP>/
```

---

## Deploying Updates

```powershell
# From Windows PowerShell inside the server/ folder
scp index.html api.php root@<IP>:/root/budsjett/
ssh root@<IP> "cp /root/budsjett/index.html /root/budsjett/api.php /var/www/html/ && chown www-data:www-data /var/www/html/index.html /var/www/html/api.php"
```

Or create a `/root/deploy.sh` on the server:

```bash
#!/bin/bash
cp /root/budsjett/*.html /root/budsjett/*.php /var/www/html/
chown www-data:www-data /var/www/html/*.html /var/www/html/*.php
echo "Deployed. Skål!"
```

> **Note:** New database tables and columns are created automatically on the first API call after deploy — no SQL migration needed.

---

## Setting Up User Accounts (for public servers)

1. Log in with the PIN
2. Open **Settings** (⚙ in the header)
3. Scroll to **Authentication → Users**
4. Add at least one user with the **Admin** role
5. Click **Switch to user accounts** and confirm

> **Recommendation:** Enable HTTPS with Let's Encrypt if exposing the app to the internet:
> ```bash
> apt install certbot python3-certbot-apache -y
> certbot --apache
> ```

---

## Remote Access via Tailscale VPN

Don't open ports to the internet. Bifrost is a better solution.

```bash
curl -fsSL https://tailscale.com/install.sh | sh
tailscale up
tailscale ip -4
```

Install Tailscale on your phone or laptop, log in with the same account — the app is accessible from anywhere over WireGuard, no port forwarding required.

---

## Security

| Topic | Detail |
|-------|--------|
| `db.php` | Excluded from git — contains the database password generated by `install.sh` |
| `.htaccess` | Blocks direct HTTP access to `db.php`, `install.php.done`, and `uploads/` |
| File uploads | Stored outside web root, served only through authenticated API calls |
| PIN | Stored in plaintext — only for private networks / VPN |
| Passwords | bcrypt via PHP `password_hash()` — safe for public use |
| Recommended setup | Private home network or Tailscale VPN for PIN mode; HTTPS + user accounts for public servers |

---

## Known Issues

| Symptom | Cause | Fix |
|---------|-------|-----|
| `install.php` returns HTTP 500 | PHP parse error (old file) | Use the latest `install.php` from this repo |
| 403 Forbidden after deploy | Files owned by `root` instead of `www-data` | Run `chown www-data:www-data /var/www/html/index.html` |
| File upload fails | `uploads/receipts/` missing or wrong owner | Run `mkdir -p /var/www/html/uploads/receipts && chown -R www-data:www-data /var/www/html/uploads` |

---

## Repository Structure

```
.
├── README.md
├── CHANGELOG.md
├── heimnarok-template.html    # Series base template — start here for new apps
└── server/
    ├── index.html             # The entire frontend (~13 500 lines of vanilla JS)
    ├── demo/
    │   └── index.html         # Standalone demo with Norse-themed mock data
    ├── api.php                # REST API — all data and file operations
    ├── db.php                 # Database connection (⚠ generated by install.sh, never committed)
    ├── install.php            # Web installer for first-time setup
    ├── install.sh             # Automated setup script for Debian 12 LXC
    ├── .htaccess              # Apache: SPA routing + security rules
    └── howto.html             # Installation guide with troubleshooting
```

---

## Database Schema

All tables are created automatically. No migration scripts. No drama. Odin has spoken.

```
settings              (key PK, value)
user_settings         (user_id, key) — per-user preferences
sheets                (key PK, notes)
income                (id, sheet_key → sheets, name, budgeted, actual, sort_order)
expenses              (id, sheet_key → sheets, name, budgeted, actual, type, status, owner, note, sort_order)
users                 (id, username UNIQUE, password_hash, role, created_at)
receipts              (id, name, vendor, description, purchase_date, amount, payment_method, tags)
receipt_files         (id, receipt_id → receipts, filename, original_name, mime_type, file_size)
meal_recipes          (id, name, portions, calories, price, instructions, use_count, is_favorite)
meal_ingredients      (id, recipe_id → meal_recipes, name, amount, unit, sort_order)
ingredient_catalogue  (id, name UNIQUE)
meal_plan             (id, week_start, day_index, recipe_id → meal_recipes)
shopping_lists        (id, name, sort_order)
shopping_items        (id, list_id → shopping_lists, name, checked, sort_order)
tasks                 (id, title, description, due_date, color, done, created_at)
vault_categories      (id, name, icon, sort_order)
vault_entries         (id, category_id → vault_categories, title, value, note)
vehicles              (id, reg_nr, brand, model, year, fuel, color, motor, vin,
                       purchase_date, tyre_summer_front, tyre_summer_rear,
                       tyre_winter_front, tyre_winter_rear, tyre_pressure_front,
                       tyre_pressure_rear, remind_service, remind_eu,
                       next_service_date, archived, archived_at)
vehicle_service       (id, vehicle_id → vehicles, service_date, km_stand, description, cost, next_service_date)
vehicle_repairs       (id, vehicle_id → vehicles, repair_date, km_stand, description, cost)
vehicle_eu            (id, vehicle_id → vehicles, inspection_date, result, next_due, notes)
vehicle_fuel          (id, vehicle_id → vehicles, fuel_date, km_stand, liters, total_cost)
vehicle_tyres         (id, vehicle_id → vehicles, brand, model_name, size, season, quantity, purchase_date)
vehicle_tyre_log      (id, vehicle_id → vehicles, change_date, km_stand, tyre_id, season, notes)
vehicle_tyre_rotation (id, vehicle_id → vehicles, rotation_date, km_stand, notes)
vehicle_custom_fields (id, vehicle_id → vehicles, label, value, sort_order)
vehicle_documents     (id, vehicle_id → vehicles, filename, original_name, mime_type, uploaded_at)
vehicle_economy       (id, vehicle_id → vehicles, monthly_payment, monthly_insurance, monthly_toll,
                       monthly_parking, payment_end_date, insurance_end_date, toll_end_date,
                       parking_end_date, monthly_km_ev, avg_consumption_ev, electricity_price_ev,
                       monthly_fuel_override, monthly_maint_override, monthly_charging_ev,
                       custom_costs JSON, updated_at)
freezer_storages      (id, name, capacity_note)
freezer_items         (id, storage_id → freezer_storages, name, quantity, date_frozen, best_before, notes)
sbudgets              (id, name, description, category, is_goal, goal_amount, created_at)
sbudget_expenses      (id, sbudget_id → sbudgets, name, budgeted, actual, type, status, owner)
```

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the full release history.

---

## License

Personal use.

© 2026 Roger Johannesen — Made in Norway 🇳🇴  
Heimnarok™ — *Valhalla Certified™ – For Mortal Homes*

> *May your budgets be balanced, your freezer well-stocked, and your Bifrost always operational.*
