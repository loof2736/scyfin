<img src="./images/scyfin-full.svg" alt="scyfin logo" width="200"/>

---

Custom CSS theme for Jellyfin (plus a backdrops supported version)

---

Scyfin Complete Theme

<img src="./images/scyfin/scyfin1.png" alt="scyfin1" width="80%"/>
<img src="./images/scyfin/scyfin2.png" alt="scyfin2" width="80%"/>
<img src="./images/scyfin/scyfin3.jpg" alt="scyfin3" width="80%"/>
<img src="./images/scyfin/scyfin4.png" alt="scyfin4" width="80%"/>
<img src="./images/scyfin/scyfin5.png" alt="scyfin5" width="80%"/>

@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.7/CSS/css-scyfin/scyfin-theme.css');

Note: If you use the Jellyfin Media Player desktop app, you need to add this CSS bit (navigate to Settings>Display>Custom CSS Code if you only want it to apply to one client, ie the desktop app) or else the content will be covered by the sidebar:

```
/* Scyfin Media Player fix */
.layout-desktop .libraryPage:not(#editItemMetadataPage) {margin-left: 250px !important;}
```

---

Scyfin Complete Theme - Backdrops Supported

Note - 

 Only add 1 version of the theme, do not add both the normal Scyfin theme and the backdrops supported version together
 
 Backdrops need to be enabled in Jellyfin (Settings > Display > Backdrops) for backdrop supported version to display properly

<img src="./images/scyfin/scyfin-backdrop1.jpg" alt="scyfin-backdrop1" width="80%"/>
<img src="./images/scyfin/scyfin-backdrop2.png" alt="scyfin-backdrop2" width="80%"/>
<img src="./images/scyfin/scyfin-backdrop3.jpg" alt="scyfin-backdrop3" width="80%"/>

@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@v1.0.7/CSS/css-scyfin/scyfin-theme-backdrop.css');

Note - If you use the Jellyfin Media Player desktop app, you need to add this CSS bit (navigate to Settings>Display>Custom CSS Code if you only want it to apply to one client, ie the desktop app) or else the content will be covered by the sidebar:

```
/* Scyfin Media Player fix */
.layout-desktop .libraryPage:not(#editItemMetadataPage) {margin-left: 250px !important;}
```
