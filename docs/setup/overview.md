# Overview

<figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2F3drS2ZSkiOfzxHXMDEzK%2FLogo.png?alt=media&#x26;token=dbe1945e-a876-48cd-a5c1-e957bbcb4c59" alt="" width="188"><figcaption></figcaption></figure>

{% hint style="info" %}
Material Components for Home Assistant is the result of my personal effort: countless hours of development, testing, and improvements designed to make your Home Assistant experience smoother and more functional. There’s no team behind it just me, driven by the passion to create something genuinely useful for users like you.

Maintaining this project takes time and resources. Without support, I might have to stop updates or new features, and the project could come to a halt.

Donating isn’t just a financial gesture it’s a way to say, “This project is worth keeping alive.”&#x20;

Even a small contribution helps ensure Material Components remains available and continues to improve.

If this component has been useful to you or you enjoy using it, your support can make a real difference.

Thank you sincerely for helping me keep this work going
{% endhint %}

<p align="center"><a href="https://www.buymeacoffee.com/giovannilamarmora"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&#x26;emoji=%E2%98%95&#x26;slug=giovannilamarmora&#x26;button_colour=5F7FFF&#x26;font_colour=ffffff&#x26;font_family=Poppins&#x26;outline_colour=000000&#x26;coffee_colour=FFDD00" alt="Buy me a coffee"></a></p>

[![Instagram](https://img.shields.io/badge/Instagram-%40gio_lamarmora-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/gio_lamarmora/) [![WebSite](https://img.shields.io/badge/WebSite%20-Visit-blue?style=for-the-badge&logo=Google-Chrome&logoColor=white)](https://giovannilamarmora.github.io/) [![WebSite](https://img.shields.io/badge/Home%20Assistant%20Forum-View-blue?style=for-the-badge&logo=Home-Assistant&logoColor=white)](https://community.home-assistant.io/t/introducing-the-google-components/916428) [![BuyMeACoffee](https://img.shields.io/badge/%E2%98%95_Buy_me_a_coffee-Support-orange?style=for-the-badge&logo=buymeacoffee&logoColor=white)](https://www.buymeacoffee.com/giovannilamarmora) [![Sponsor](https://img.shields.io/badge/GitHub_Sponsors-Become_a_Sponsor-pink?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/giovannilamarmora)

> **Note**: This is an independent open-source project and **is not affiliated with or endorsed by Google**. The project name and features are intended to integrate with Home Assistant/Lovelace and do not represent an official Google product.

**Material Home Component for Home Assistant** is a suite of custom UI elements designed to bring the **look and feel of the Google Home app** directly into your Home Assistant dashboard. It leverages the latest **Material You** design system introduced with Android 12+, providing a modern, fluid, and mobile-optimized interface for smart home control.

Unlike traditional themes, this project is more than just a visual layer: it’s a fully modular system of **interactive cards**, **custom icons**, **animations**, and **dynamic layouts** built specifically for Home Assistant with a focus on responsiveness, touch-first navigation, and entity-driven customization.

> ⚠️ **Beta Notice:** This project is currently in active development. Features, UI elements, and documentation may change frequently.\
> ⚠️ **Important:** This is **not a theme**, but a collection of custom cards that integrate with Material You themes, adding buttons, sliders, dashboards, and dynamic controls to your UI.

### 🧠 Purpose

The main goal is to provide a **modern, touch-friendly, and modular interface** for Home Assistant — clean, elegant, and intuitive on both desktop and mobile devices. Whether you're managing lights, climate, cameras, or network devices, this suite offers a **fluid and visually consistent** experience.

---

### ✨ Key Features

- 🎨 **Material You Design**\
  Full support for light/dark themes, dynamic color palettes, and rounded shapes.
- 📱 **Mobile-first UX**\
  Optimized for phones and tablets with fluid swipe navigation and adaptive sizing.
- 🧩 **Custom Cards Included**\
  Ready-to-use cards for lights, climate, Wi-Fi, cameras, and more.
- 🔁 **Dynamic Behavior**\
  Entity-aware styling, animations, conditional rendering, and real-time updates.
- ⚙️ **Easy Configuration**\
  YAML-based setup with smart defaults, compatible with UI editors.
- 📦 **Flexible Installation**\
  Use it via CDN or manually install from GitHub — your choice.
- 🔄 **Easy Updates**\
  HACS compatibility for one-click updates.

---

### 🔗 Credits

This project **would not exist** without the foundational work of:

- [@Nerwyn](https://github.com/Nerwyn) – Creator of the [Material You theme](https://github.com/Nerwyn/material-you-theme) for Home Assistant.
- [@beecho01](https://github.com/beecho01) – Creator of the [Material Symbol Icons](https://github.com/beecho01/material-symbols) for Home Assistant.
- The Home Assistant frontend community.

---

### 🙌 Support the Project

If you find this card useful and would like to support its development, consider buying me a coffee or making a small donation! ☕

\
Or support me on [Buy Me a Coffe](https://revolut.me/glamarmora)

<p align="center"><a href="https://www.buymeacoffee.com/giovannilamarmora"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&#x26;emoji=%E2%98%95&#x26;slug=giovannilamarmora&#x26;button_colour=5F7FFF&#x26;font_colour=ffffff&#x26;font_family=Poppins&#x26;outline_colour=000000&#x26;coffee_colour=FFDD00" alt="Buy me a coffee"></a></p>

Your support helps keep this project active and maintained. Thank you! ❤️

---

### 🖼️ Theme Preview

#### 🎨 **Dashboard Card (Google Home Style)**

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2F9M8FRMfEZ2uu3QnAqbVZ%2FMaterial%20Dashboard%20Dark.png?alt=media&#x26;token=f03f8e97-bb23-4331-9805-4341cb181adc" alt=""><figcaption><p>Dashboard Dark (Camera, Lights, Wifi, Climate)</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FdsgoBNjTz9ghc7CXdKTs%2FMaterial%20Dashboard%20Light.png?alt=media&#x26;token=ba5ab7e9-b493-4349-b9a1-b40a19811816" alt=""><figcaption><p>Dashboard Light (Camera, Lights, Wifi, Climate)</p></figcaption></figure></div>

#### 🎛️ **Material Button Card**

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FoqMqqGVeL7guh9tPJadR%2FMaterial%20Button%20Dark.png?alt=media&#x26;token=1554c8b9-a46b-4871-bd77-58fcd5749c16" alt=""><figcaption><p>Button Dark (Climate, Switch, Scene...)</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FMxIyn71nrZnVuw07YmTr%2FMaterial%20Button%20Light.png?alt=media&#x26;token=456c4c14-a972-4ce1-9e59-f35eaa7c2a85" alt=""><figcaption><p>Button Light (Climate, Switch, Scene...)</p></figcaption></figure></div>

#### **💡 Material Slider Card**

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FwjZ5n0l5JpnykjKkOLEH%2FMaterial%20Slider%20Dark.png?alt=media&#x26;token=278a33ef-65a6-49bf-9b0e-f46121d0fac1" alt=""><figcaption><p>Button Slider Dark  (Lights, Cover)</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FSkvO52mlWL7BODPn6Xz8%2FMaterial%20Slider%20Light.png?alt=media&#x26;token=dccc2cbc-e13e-4064-a4f1-e0270a073bae" alt=""><figcaption><p>Button Slider Light (Lights, Cover)</p></figcaption></figure></div>

#### 🌡️ Material Climate Card

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FHYDsgocmj4elqtMerUOl%2FImmagine%202025-09-24%20173108.png?alt=media&#x26;token=4cefbd5b-7bec-47c6-98ed-4cc513a141ec" alt=""><figcaption><p>Climate (Dark)</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2Fu2ydcDf65j9QfyOTBmw3%2FImmagine%202025-09-24%20172935.png?alt=media&#x26;token=4a302e61-fc27-4ab4-a0ac-951e375c0563" alt=""><figcaption><p>Climate (Light)</p></figcaption></figure></div>

#### **💡 Material Lights Control**

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FSHBFl58FU8t62BqJH9RN%2FMaterial%20Light%20Dark.png?alt=media&#x26;token=3161e6e7-caf1-42d9-8936-c02a401a89ec" alt=""><figcaption><p>Light Card (Dark)</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FVke7RsSJj99GM7NcPNl2%2FMaterial%20Light%20Light.png?alt=media&#x26;token=fa783bed-1fe2-45e9-95b5-4f11f6c301e6" alt=""><figcaption><p>Light Card (Light)</p></figcaption></figure></div>

#### 🗂️ Material Control Card

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FKR5DezetiZApEU4RvhHE%2FMaterial%20Control%20Dark.png?alt=media&#x26;token=7591c778-b147-4cad-865c-f2788e6bda7d" alt=""><figcaption><p>Control Dark</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FpM8AeYNtOQEW9FCNmsNR%2FMaterial%20Control%20Light.png?alt=media&#x26;token=35f1b25b-7d05-4ef0-a6b7-502ea6db95f4" alt=""><figcaption><p>Control Light</p></figcaption></figure></div>

#### **🔊 Material Media Page**

> 🆕 Introduced in version 1.6.0

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FiSJWqraVKcD25OEug0JH%2FMaterial%20Media%20Dark.jpg?alt=media&#x26;token=d5451ba7-60ff-48c0-8e1d-f07d113dc9d6" alt="" width="188"><figcaption><p>Media Overlay Dark</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FCalLmmHWdh7EnoSh5v7y%2FMaterial%20Media%20Light.jpg?alt=media&#x26;token=17846995-2e7d-4bdd-9511-71b292686287" alt="" width="188"><figcaption><p>Media Overlay Light</p></figcaption></figure></div>

#### 🏃‍♂️ Material Dialog Page (Sensor View)

> 🆕 Introduced in version 2.0.0

<div><figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2Fma4sUl0V4UvOzslyJMzW%2FScreenshot_20251010_160137_Home%20Assistant.jpg?alt=media&#x26;token=90dad359-36b1-4c19-a08a-0198a722a79f" alt="" width="188"><figcaption><p>Dark Mode</p></figcaption></figure> <figure><img src="https://1144211266-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3ov5EClzNfEwDYkNqmsR%2Fuploads%2FEGFct0kEvR3sSeRrzopq%2FScreenshot_20251010_160124_Home%20Assistant.jpg?alt=media&#x26;token=d2f99b74-2ea6-43a7-84d6-c7d92dfa7d37" alt="" width="188"><figcaption><p>Light Mode</p></figcaption></figure></div>

{% embed url="<https://www.buymeacoffee.com/giovannilamarmora>" %}
☕ Buy me a Coffee
{% endembed %}
