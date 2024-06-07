<img src="./images/scyfin-full.png" alt="scyfin logo" width="200"/>

---

### **Custom CSS theme for Jellyfin (plus a backdrops supported version)**

---

### [Go to installation](#installation)

---

### **Scyfin Complete Theme**

<img src="./images/homepage.png" alt="homepage" width="100%"/>
<img src="./images/details.png" alt="details" width="100%"/>
<img src="./images/movies.png" alt="movies" width="100%"/>
<img src="./images/dashboard.png" alt="dashboard" width="100%"/>
<img src="./images/login.png" alt="login" width="100%"/>

`@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/scyfin-theme.css');`

### Options (Add these below the full theme)
- Disable static left drawer 
    - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/disable-static-drawer.css');`
- Themes:
    - Seafoam
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-seafoam.css');`
        - <img src="./images/seafoam.png" alt="install2" width="40%"/>
    - Coral
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-coral.css');`
        - <img src="./images/coral.png" alt="install2" width="40%"/>
    - Snow
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-snow.css');`
        - <img src="./images/snow.png" alt="install2" width="40%"/>

---

### **Scyfin Complete Theme - Backdrops Supported**

**Note -** 
* Only install ONE version of the theme, do not install both the normal version and the backdrops supported version
* Backdrops need to be enabled in Jellyfin (Settings > Display > Backdrops) for backdrop supported version to display properly

<img src="./images/homepage-backdrops.png" alt="homepage-backdrops" width="100%"/>
<img src="./images/details-backdrops.png" alt="details-backdrops" width="100%"/>

`@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/scyfin-theme-backdrop.css');`

### Options (Add these below the full theme)
- Disable static left drawer (BACKDROP VERSION) 
    - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/disable-static-drawer-backdrop.css');`
- Themes:
    - Seafoam
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-seafoam.css');`
        - <img src="./images/seafoam.png" alt="install2" width="40%"/>
    - Coral
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-coral.css');`
        - <img src="./images/coral.png" alt="install2" width="40%"/>
    - Snow
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-snow.css');`
        - <img src="./images/snow.png" alt="install2" width="40%"/>

---

### **Installation:**

---

**Server-wide install:**
* Click the hamburger icon (Top left)
* Navigate to "Dashboard" (If you don't see this, make sure you are signed in to your admin account)
* Navigate to "General"
* Near the bottom, under "Custom CSS code", paste the `@import url` for the theme you want
    * Note - 
        * Only install ONE version of the theme, do not install both the normal version and the backdrops supported version
    * Example:
    * <img src="./images/install.png" alt="install" width="80%"/>
* Optional - Paste the `@import url` for any options you want
    * Example:
    * <img src="./images/install2.png" alt="install2" width="80%"/>
* Click "Save"

---

**Single client install:**
* Click the hamburger icon (Top left)
* Navigate to "Settings"
* Navigate to "Display"
* Near the middle, under "Custom CSS code", paste the `@import url` for the theme you want
    * Note - 
        * Only install ONE version of the theme, do not install both the normal version and the backdrops supported version
        * If there is any server-wide custom CSS, you may want to enable "Disable server-provided custom CSS code", as the two themes WILL interfere with each other
    * Example:
    * <img src="./images/install3.png" alt="install3" width="80%"/>
* Optional - Paste the `@import url` for any options you want
    * Example:
    * <img src="./images/install4.png" alt="install4" width="80%"/>
* Click "Save"

---
