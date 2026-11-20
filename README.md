# Blood Donor Finder — Dhaka (RoktoKhoj)

Find compatible blood donors in Dhaka by recipient blood group and area, with an animated heartbeat hero and instant donor registration.

Live demo: https://nafiz-xd.github.io/blood-donor-finder/

## Features
- Donor directory with 18 realistic sample donors (Bangladeshi names, Dhaka areas, phone, last donation date)
- Compatibility-aware filtering — pick the patient's (recipient) group and only donors who can safely donate to that group are shown (full standard compatibility map, O− universal donor, AB+ universal recipient)
- Area search (Mirpur, Uttara, Dhanmondi, etc.) and "Available now only" filter
- "URGENT • Available Now" pulse badge on available donors, eligibility note based on last donation date (90-day gap)
- Register-as-donor form saved to localStorage — new donors appear in the list instantly
- Donor avatars are initials in coloured circles (no fake photos), animated ECG heartbeat line in the hero
- Fully responsive, works offline from `file://` — no build step, no accounts

## Tech Used
- HTML5, CSS3 (crimson medical theme, ECG / pulse animations)
- Vanilla JavaScript (compatibility map, filtering, localStorage)
- Hero photo: "Bloedafname Sanquin" by MartinD via Wikimedia Commons (CC BY-SA 2.5)

Built by Nafiz Bin Azad
