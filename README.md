## Installation
1. Node 12.4.0+ is required (you can check your version using `node -v`)
2. Run ```npm install```
3. Run ```npm run build``` (this bundles `assets/` into `dist/`)
4. Run ```node main.js``` to boot the system (may need sudo!)

(There's also ```build.sh``` and ```start.sh```, but they may not work for your OS.)

Database logging is enabled by default. You can disable it in ```config.json``` by setting ```logToDatabase``` to false.
This requires sqlite3 drivers to be installed.
