# Requirements

[![Instagram](https://img.shields.io/badge/Instagram-%40gio_lamarmora-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/gio_lamarmora/) [![WebSite](https://img.shields.io/badge/WebSite%20-Visit-blue?style=for-the-badge&logo=Google-Chrome&logoColor=white)](https://giovannilamarmora.github.io/) [![WebSite](https://img.shields.io/badge/Home%20Assistant%20Forum-View-blue?style=for-the-badge&logo=Home-Assistant&logoColor=white)](https://community.home-assistant.io/t/introducing-the-google-components/916428) [![BuyMeACoffee](https://img.shields.io/badge/%E2%98%95_Buy_me_a_coffee-Support-orange?style=for-the-badge&logo=buymeacoffee&logoColor=white)](https://www.buymeacoffee.com/giovannilamarmora) [![Sponsor](https://img.shields.io/badge/GitHub_Sponsors-Become_a_Sponsor-pink?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/giovannilamarmora)

To use the **Material Home Component**, a few additional dependencies and integrations are required to ensure full compatibility and styling. Below are the minimum requirements:

---

### 🛠 Home Assistant Community Store (HACS) – _Required_

> 📥 Installing via HACS is strongly recommended for easy management and updates of custom components.

🔗 [How to install HACS](https://www.hacs.xyz/docs/use/configuration/basic/)

---

### 🎨 Material You Theme & Utils – [@Nerwyn](https://github.com/Nerwyn) – _Required_

> To enable **Material You** styling (dynamic colors, adaptive palettes), you’ll need a theme that supports Material You variables.

- Includes light/dark mode support
- Supports dynamic color palettes (Material You)
- Defines required CSS variables for custom cards

🔗 [Material You Theme for Home Assistant – GitHub](https://github.com/Nerwyn/material-you-theme)

🔗 [Material You Utils for Home Assistant – GitHub](https://github.com/Nerwyn/material-you-utilities)

---

### 🧷 Material Symbol Icons – [@beecho01](https://github.com/beecho01) – _Required_

> This component uses the **Material Design Icons** set for consistency with Google’s UI.

Make sure icons are enabled in your instance (enabled by default in modern HA versions).

The icons come in six distinct styles, each with its own prefix:

- Outlined: `m3o`
- Outlined and filled: `m3of`
- Rounded: `m3r`
- Rounded and filled: `m3rf`
- Sharp: `m3s`
- Sharp and filled: `m3sf`

🔗 [Material Symbol for Home Assistant – GitHub](https://github.com/beecho01/material-symbols)

---

### 🅰️ Recommended Font: **Figtree** – _(Optional, but encouraged)_

We recommend the **Figtree** font for a look very close to **Google Sans**, the font used in official Google apps. If not available, the system will fall back to **Roboto**.

To install Figtree:

1. Go to **Dashboard → Edit dashboard → Menu (⋮) → Manage Resources**
2. Click **+ Add Resource**
3. Use this URL:

   <pre data-overflow="wrap"><code>https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&#x26;display=swap
   </code></pre>

4. Select **Resource Type: Stylesheet**
5. Click **Create**
6. Hard refresh your browser (**CTRL + F5**) or clear the app cache

---

### 🧭 Required Custom Cards (For Dashboard Card)

To achieve the full Google Home UI experience, install the following cards via HACS:

**📌** [**Swipe Card**](https://github.com/bramkragten/swipe-card)

> Enables horizontal swipeable views for dashboards, similar to the Google Home app tabbed interface.

- Allows seamless swiping between different sections (e.g. Cameras, Lighting, Wi-Fi, Climate)
- Highly configurable with `parameters`, `spaceBetween`, `slidesPerView`, etc.

**📌** [**Button Card**](https://github.com/custom-cards/button-card)

> The backbone of the UI—used to build powerful, styled buttons with dynamic content.

- Fully supports entity states, custom templates, and CSS-style controls
- Each dashboard item (camera, light, climate...) uses this card with custom styling and icons
