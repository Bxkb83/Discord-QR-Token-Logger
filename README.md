# Discord QR Token Logger

![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)
![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)
![author](https://svgshare.com/i/mg6.svg)

![GitHub](https://img.shields.io/github/license/9P9/Discord-QR-Token-Logger)
![GitHub contributors](https://img.shields.io/github/contributors/9P9/Discord-QR-Token-Logger)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=shields)](http://makeapullrequest.com)
![GitHub issues](https://img.shields.io/github/issues/9P9/Discord-QR-Token-Logger)
![GitHub pull requests](https://img.shields.io/github/issues-pr/9P9/Discord-QR-Token-Logger)
![Maintenance](https://img.shields.io/maintenance/yes/2022)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/9P9/Discord-QR-Token-Logger)

A python script that generates a scam nitro QR code which can grab a victim's authentication token if scanned. Developed to show how social engineering is performed.

*If you're interested in knowing the powerlevel configuration to get this prompt, have a look at [this repo](https://github.com/billythegoat356/pystyle).*

![Discord QR Token Grabber](https://user-images.githubusercontent.com/38190847/187040712-92f4c796-c655-47a2-abb2-7f4519d1dab7.png)

<p align="center">
<i>Love the tool? Please consider <strong>donating</strong> 💸 to help it improve!</i>
</p>

<p align="center">
<a href='https://ko-fi.com/mouadessalim' target='_blank'><img height='30' width="115" src='https://cdn.ko-fi.com/cdn/kofi3.png?v=2' alt='Buy Coffee for mouadessalim' />
</a>
<a href="https://www.buymeacoffee.com/mouadessalim" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="30" width="115" style="border-radius:1px" />
</p>

## ❗ Disclaimer
- **For Educational Purposes Only**
- We decline any responsability in case of misuse of this code.

# 📖 Table of contents

- [Usage](#-usage)
  - [Without Discord features](#without-discord-webhook)
  - [With Discord features](#with-discord-webhook)
- [Installation](#-installation)
  - [Dependencies](#dependencies)
  - [Supported Platforms](#supported-platforms)
- [Contributing](#contributing)
  - [Authors](#authors-)
- [License](#-license)
- [Other Project](#-other-projects)

# 📈 Usage

To use the script, run `install_requirements.bat` if needed, then run `main.py`. The scam image will appear as `discord_gift.png` in the directory. However there are two ways to use this script...

## Without Discord Webhook

Without a Discord Webhook, you can only get target token. You must enter `n` when prompted.

<img src="https://user-images.githubusercontent.com/38190847/187074516-29a22055-96a0-40f9-9d79-8a69834ab039.png" width="500">

## With Discord Webhook

To use a Discord Webhook you must enter `y` when prompted.

<img src="https://user-images.githubusercontent.com/38190847/187074586-d5c0a8f5-c96b-45bb-ac96-42550c2f1ae4.png" width="500">

With a Discord Webhook, you will be able to get much more target information. The target information shown includes:

- User token informations :
  - 👑 Username
  - 🆔 User ID
  - 📧 Mail 
  - 📞 Phone 
  - 🤑 Nitro 
- Payment info :
  - 💳 Brand (Visa / Mastecard / PayPal)
  - ℹ/📩 Last 4 digits / PayPal mail
  - 📅 Expiration
- Billing adress :
  - 📛 Name
  - 🏠 1️⃣ Address Line 1
  - 🏠 2️⃣ Address Line 2
  - 🏳 Country
  - 🚩 State
  - 🏙 City
  - 📮 Postal code

# 🛠 Installation

For installation, there are a few requirements. You must follow these steps to avoid all python interpreter errors.

## Dependencies

- Chrome: **be sure to have the latest version**.
- Python 3.9+
- Python Modules (launch `install_requirements.bat`)

After installing all dependencies, you can start the script 🥳.

## Supported Platforms
- Windows 11 - `supported but not tested`
- Windows 10 - `supported and tested`
- Windows 8 - `supported but not tested`
- Windows 7 - `supported but not tested`

# ✨Contributing

Your contributions are always welcome! If you contribute we will show your account in this README! 

_Please have a look at the [contribution guidelines](CONTRIBUTING.md) first._ 🎉

## Authors ❤

<a href="https://github.com/9P9/Discord-QR-Token-Logger/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=9P9/Discord-QR-Token-Logger" />
</a>
<br>
<br>

> **Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://kcd.im/pull-request)

# 📝 License

The GNU General Public License v3.0 (GPL-3.0) 2022 - [mouadessalim](https://github.com/mouadessalim) & [9P9](https://github.com/9P9). Please have a look at the [LICENSE](LICENSE) for more details.

# 💡 Other projects

If you love this repository you may be interested in these projects:

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=mouadessalim&repo=CookedGrabber&show_owner=true)](https://github.com/mouadessalim/CookedGrabber)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=9P9&repo=Website-Token-Grabber-2&show_owner=true)](https://github.com/9P9/Website-Token-Grabber-2)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=the-cult-of-integral&repo=discord-raidkit&show_owner=true)](https://github.com/the-cult-of-integral/discord-raidkit)
