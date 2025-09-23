<img src="./images/scyfin-full.png" alt="scyfin logo" width="200"/>

### **A modern CSS theme for Jellyfin, featuring backdrops and customizable accent colors. Enhanced for a more elegant appearance.**

[Go to installation](#installation)

---

### **Scyfin Elegance Theme**
```css
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/scyfin-theme.css'); /* Base theme */
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/disable-static-drawer.css'); /* Disable static left drawer */

/* Elegance theme */
:root {
    --primary-background-color: rgba(0,0,0,0.9);
    --secondary-background-color: rgba(2,2,2,0.9);
    --primary-background-transparent: rgba(2,2,2,0.2);
}

/* Increase backdrop image brightness and add some blur */
.backgroundContainer.withBackdrop {
  background-color: rgba(0,0,0,0.65);
  backdrop-filter: blur(6px);
}
```

<img width="3840" height="2071" alt="492565878-c1894478-9b1e-40d9-aad8-bc6bf96a30f6" src="https://github.com/user-attachments/assets/d8f12354-5a20-4ad5-a88b-61a3611f6013" />
<img width="3840" height="2071" alt="492565951-22b1a228-3012-4633-8236-65bce2397407" src="https://github.com/user-attachments/assets/592b5697-c4c3-4d8c-96f0-9ad8e89feb0c" />
<img width="3840" height="2071" alt="492566281-2c14d90e-36e2-43b8-a1fe-49e16192a474" src="https://github.com/user-attachments/assets/f1a22a6e-f10a-422d-83eb-fdfa150ddf49" />


---

### **Installation:**

---

**Server-wide install:**
* Click the hamburger icon (Top left)
* Navigate to "Dashboard" (If you don't see this, make sure you are signed in to your admin account)
* Navigate to "General"
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
