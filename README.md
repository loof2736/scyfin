<img src="./images/scyfin-full.svg" alt="scyfin logo" width="200"/>

---

### **Custom CSS theme for Jellyfin (plus a backdrops supported version)**

---

### [Go to installation](#installation)

---

### **Scyfin Complete Theme**

<img src="./images/scyfin/scyfin1.png" alt="scyfin1" width="100%"/>
<img src="./images/scyfin/scyfin2.png" alt="scyfin2" width="100%"/>
<img src="./images/scyfin/scyfin3.jpg" alt="scyfin3" width="100%"/>
<img src="./images/scyfin/scyfin4.png" alt="scyfin4" width="100%"/>
<img src="./images/scyfin/scyfin5.png" alt="scyfin5" width="100%"/>

`@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/scyfin-theme.css');`

### Options (Add these below the full theme)
- Disable static left drawer 
    - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/disable-static-drawer.css');`
- Disable static left drawer (BACKDROP VERSION) 
    - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/disable-static-drawer-backdrop.css');`

---

### **Scyfin Complete Theme - Backdrops Supported**

**Note -** 
* Only install ONE version of the theme, do not install both the normal version and the backdrops supported version
* Backdrops need to be enabled in Jellyfin (Settings > Display > Backdrops) for backdrop supported version to display properly

<img src="./images/scyfin/scyfin-backdrop1.jpg" alt="scyfin-backdrop1" width="100%"/>
<img src="./images/scyfin/scyfin-backdrop2.png" alt="scyfin-backdrop2" width="100%"/>
<img src="./images/scyfin/scyfin-backdrop3.jpg" alt="scyfin-backdrop3" width="100%"/>

`@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/scyfin-theme-backdrop.css');`

### Options (Add these below the full theme)
- Disable static left drawer 
    - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/disable-static-drawer.css');`
- Disable static left drawer (BACKDROP VERSION) 
    - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/disable-static-drawer-backdrop.css');`

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
    * <img src="./images/install.png" alt="install" width="60%"/>
* Optional - Paste the `@import url` for any options you want
    * Example:
    * <img src="./images/install2.png" alt="install2" width="60%"/>
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
    * <img src="./images/install3.png" alt="install3" width="60%"/>
* Optional - Paste the `@import url` for any options you want
    * Example:
    * <img src="./images/install4.png" alt="install4" width="60%"/>
* Click "Save"