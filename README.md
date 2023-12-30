<img src="./images/scyfin-full.svg" alt="scyfin logo" width="200"/>

---

Custom CSS theme for Jellyfin (plus a backdrops supported version)

---

## Table of contents

- [Installation](#installation)
- [Themes](#themes)
  - [Complete theme](#complete-theme)
  - [Complete theme + without static drawer](#complete-theme-without-static-drawer-and-with-backdrop)
  - [Complete theme + without static drawer + with backdrop](#complete-theme-without-static-drawer)

## Installation
1. Click on ``Settings`` in the navigation bar
2. Click on ``Dashboard`` below ``Administration``
3. Click on ``General`` below ``Server``.
4. Scroll to the bottom of the page and enter the custom CSS code of your desired theme.
5. Click ``Save``
6. Press ``CTRL`` + ``F5``

> [!WARNING]  
> Only add 1 version of the theme, do not add both the normal Scyfin theme and the backdrops supported version together

## Themes
### Complete theme

```css
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/scyfin-theme.css');
```

<img src="./images/scyfin/scyfin1.png" alt="scyfin1" width="80%"/>
<img src="./images/scyfin/scyfin2.png" alt="scyfin2" width="80%"/>
<img src="./images/scyfin/scyfin3.jpg" alt="scyfin3" width="80%"/>
<img src="./images/scyfin/scyfin4.png" alt="scyfin4" width="80%"/>
<img src="./images/scyfin/scyfin5.png" alt="scyfin5" width="80%"/>

### Complete theme without static drawer and with backdrop

```css
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/disable-static-drawer.css');
```

### Complete theme without static drawer

```css
@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.10/CSS/css-scyfin/disable-static-drawer-backdrop.css');
```

> [!NOTE]  
> Backdrops need to be enabled in Jellyfin (`Settings` > `Display` > `Backdrop`) for backdrop supported version to display properly


<img src="./images/scyfin/scyfin-backdrop1.jpg" alt="scyfin-backdrop1" width="80%"/>
<img src="./images/scyfin/scyfin-backdrop2.png" alt="scyfin-backdrop2" width="80%"/>
<img src="./images/scyfin/scyfin-backdrop3.jpg" alt="scyfin-backdrop3" width="80%"/>


