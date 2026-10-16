# Parchemin releases

Installers for **Parchemin**, a calm, local-first writing app for stories and the people in them: [parchemin.art](https://parchemin.art).

This repository holds release files only: the Windows installer for each version, and `latest.yml`, the small file the app reads to find out whether a newer version exists. The source code is not here yet; it will be published under the GNU Affero General Public License, version 3 or later.

## Installing

Download `Parchemin-Setup-<version>.exe` from the newest [release](https://github.com/WilliamNOsuji/parchemin-releases/releases/latest) and run it. It installs for your Windows user only, with no account. Your library stays on your computer, and stays there if you remove the app.

The installers are not code-signed yet, so Windows may say "Windows protected your PC" the first time. Choose **More info**, then **Run anyway**.

## Updates

Parchemin never looks for a new version unless you ask. Under **Safekeeping → Updates**, "Check for updates" reads `latest.yml` from here and sends nothing about you or what you write. A new version is downloaded only when you choose, checked against the SHA-512 fingerprint in `latest.yml` before it runs, and installed when you say so. You can turn on a check each time Parchemin opens; it is off until you do.
