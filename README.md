<img src="./images/scyfin-full.png" alt="scyfin logo" width="200"/>

### **Modern CSS theme for Jellyfin with support for backdrops and custom accent colors**

[Go to installation](#installation)

---

### **Scyfin Base Theme**
Jellyfin 10.11.X and above
```
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/scyfin-theme.css');
```

Jellyfin 10.10.X and lower
```
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.4.17/CSS/scyfin-theme.css');
```

<img src="./images/homepage.png" alt="homepage" width="100%"/>
<img src="./images/homepage-backdrops.png" alt="homepage-backdrops" width="100%"/>
<img src="./images/details.png" alt="details" width="100%"/>
<img src="./images/details-backdrops.png" alt="details-backdrops" width="100%"/>
<img src="./images/movies.png" alt="movies" width="100%"/>
<img src="./images/login.png" alt="login" width="100%"/>

---

### **Options (Add these below the base theme)**
### Disable static left drawer 
```
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/disable-static-drawer.css');
```

---

### **Themes:**
### Seafoam
```
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-seafoam.css');
```
<img src="./images/seafoam.png" alt="seafoam-theme" width="40%"/>

### Coral
```
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-coral.css');
```
<img src="./images/coral.png" alt="coral-theme" width="40%"/>

### Snow
```
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-snow.css');
```
<img src="./images/snow.png" alt="snow-theme" width="40%"/>

### OLED
```
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-oled.css');
```
<img src="./images/homepage-oled.png" alt="homepage-oled" width="90%"/>
<img src="./images/details-oled.png" alt="details-oled" width="90%"/>

---

### **Installation:**

---

**Server-wide install:**
* Click the hamburger icon (Top left)
* Navigate to "Dashboard" (If you don't see this, make sure you are signed in to your admin account)
* Navigate to "Branding"
* Near the bottom, under "Custom CSS code", paste the `@import url` for the base Scyfin theme
    * Example:
    * <img src="./images/install-server-base.png" alt="install-server-base" width="80%"/>
* Optional - Paste the `@import url` for any options / themes you may want
    * Example:
    * <img src="./images/install-server-options.png" alt="install-server-options" width="80%"/>
* Click "Save"

---

**Single client install:**
* Click the hamburger icon (Top left)
* Navigate to "Settings"
* Navigate to "Display"
* Near the middle, under "Custom CSS code", paste the `@import url` for the base Scyfin theme
    * Note - 
        * If there is any server-wide custom CSS, you may want to enable "Disable server-provided custom CSS code", as the two themes WILL interfere with each other
    * Example:
    * <img src="./images/install-client-base.png" alt="install-client-base" width="80%"/>
* Optional - Paste the `@import url` for any options / themes you may want
    * Example:
    * <img src="./images/install-client-options.png" alt="install-client-options" width="80%"/>
* Click "Save"
