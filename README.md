# shop.rsc.ee

[![Live](https://img.shields.io/badge/live-shop.rsc.ee-b25c1f)](https://shop.rsc.ee)
[![Main site](https://img.shields.io/badge/main_site-rsc.ee-1a1612)](https://rsc.ee)

Support hub and storefront for the **Robot Study Companion (RSC)** project.

## What this is

A static GitHub Pages site served at [shop.rsc.ee](https://shop.rsc.ee). Main site: [rsc.ee](https://rsc.ee).


## Structure

```
.
├── CNAME        # binds the repo to shop.rsc.ee for GitHub Pages
├── index.html   # the page
└── README.md    # you are here
```

## Local preview

```bash
git clone https://github.com/RobotStudyCompanion/shop.git
cd shop
python3 -m http.server 8000  # then open http://localhost:8000
```

## Contributing

Substantive work happens upstream, see [github.com/RobotStudyCompanion](https://github.com/RobotStudyCompanion). Issues and pull requests on this repo are welcome for shop-specific fixes (copy, layout, links).