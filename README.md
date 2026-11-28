# MEGA EMPIRE TYCOON – 3D

Godot 4.3 (GDScript, GL Compatibility) business tycoon. Supermarket first, then more shops. Built to APK with GitHub Actions.

## Deploy (phone only)
1. GitHub repo: delete the old zip, upload the new zip.
2. `.github/workflows/build.yml` must be pasted into the repo manually (a zip upload does not install it).
3. Actions → Run workflow → when done, install the APK from Releases → `latest`.

## Version history
| Version | What changed |
|---|---|
| v4 | Back button no longer quits (pause menu / double-back on menu), bigger city, premium UI, lighting and heat fixes, camera fixes |
| v4b | Customers and staff hold items in their hand, staff naming (Employees → Name), real product photos on shelves |
| v6 | Tailor Shop (east plot) with services, fabric, machines, missions and sounds; Tailor menu button; build.yml permission fix |

## Features

### Supermarket
- 3D store with shelves, checkout lanes, warehouse, glass sliding door, city streets and traffic
- Customers: shopping lists, pick products, queue at checkout, pay, leave; shoplifting; litter
- Real product photos on shelves (milk, bread, apple, cola, chips, ...)
- Buy stock (Shop menu), stock shelves, set prices
- Day/night cycle, daily report, rent / maintenance / ads costs
- Ratings and reviews, customer satisfaction

### Staff
- Hire: Cashier, Stock Manager, Cleaner, Security Guard, Supervisor, Tailor
- Levels, daily salary, train and fire
- Rename any employee (Employees → Name); name shows above their head
- Staff and customers carry items in their hand

### Tailor Shop (unlock: $3,000 total revenue + $8,000 cash)
- Full 3D shop: sewing stations, cutting table, fabric wall, counter, ready rack, sofa, mannequins, fitting room, awning and sign
- Customers order, wait on the sofa, collect and pay; patience and lost-customer rules
- 8 services: alteration, shirt, trouser, kurta set, school uniform, blazer/suit, embroidery, wedding outfit
- Fabric: cotton, wool, silk (buy in Tailor menu, capacity grows with shop level)
- Upgrades: sewing machines (up to 6), shop level (up to 5, unlocks services)
- A free Master Tailor on unlock; hire more in Employees
- 8 tailor missions
- Sounds: sewing machine loop, scissors, shop bell, cloth swish, ready ding

### Progress
- Missions with cash rewards, upgrades and expansion, stats
- Auto save and load

### Controls and camera
- One-finger pan with inertia, two-finger pinch zoom and rotate, tilt
- Camera presets: Overview, Checkout, Shelves, Warehouse, Tailor
- Speed x1/x2/x3, pause menu, settings

### Performance
- 30 fps cap, quality levels, limited lights, light heating

### Audio
- Synthesized SFX, music and ambience (replace files in `audio/` with real recordings of the same name to upgrade)

## Planned
- Mechanic shop, Mobile shop (same model as the Tailor shop)
- Daily rewards, achievements, prestige, offline earnings
- Real 3D characters from your art (`.glb` into `assets/models/people/`)
- AdMob (rewarded, optional) after the core game is stable

## Known limits
- Characters are placeholder sample models (check their licences before a Play Store release)
- Sounds are synthesized, not real recordings
- Tailors stand while working (no sitting animation)
