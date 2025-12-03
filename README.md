# 🍊 TangyTheme

A minimal and elegant theme for Jellyfin forked from stpnwf's [ZestyTheme](https://github.com/stpnwf/ZestyTheme).

  

**My goal for this fork is to unify and enhance some styling for my own personal UI/UX preferences wherever I can.**

---

### **Screenshots:**

<img src="./images/homeTangy.jpg" alt="home" width="100%"/>
<img src="./images/movieTangy.jpg" alt="movie screen" width="100%"/>
<img src="./images/liveTangy.jpg" alt="live tv guide" width="100%"/>


---

## Installing

To add the theme to Jellyfin `v10.11+`, copy the following line to Dashboard > Branding² > Custom CSS:

```
@import url('https://cdn.jsdelivr.net/gh/jpereira99/TangyTheme@latest/theme.css');
```

Here are the additional plugins that I use in Jellyfin, please refer to each respective GitHub page for instillation instructions

 - [Home Sections](https://github.com/IAmParadox27/jellyfin-plugin-home-sections)
 - [Media Bar](https://github.com/IAmParadox27/jellyfin-plugin-media-bar)
 - [File Transformation](https://github.com/IAmParadox27/jellyfin-plugin-file-transformation)
 - [Plugin Pages](https://github.com/IAmParadox27/jellyfin-plugin-pages)
 - [Jellyfin Enhanced](https://github.com/n00bcodr/Jellyfin-Enhanced)
 - [Jellyfin Teaks](https://github.com/n00bcodr/JellyfinTweaks)

*TODO: Add a current setup page that documents all the settings I run for each plugin*

<br>

<details>
<summary>For older Jellyfin versions (v10.10), add the following line instead:</summary>

Jellyfin `v10.10.x`:
<br>
```
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@legacy/v10.10/theme.css');
```
</details>

Then, if you haven't already, enable Backdrops for _every_ device using this theme (Settings > Display > Backdrops).¹

### Notes:

 ¹ You *must* enable Backdrops on *every* device you plan to use this on, otherwise theme **WILL** look broken.

 ² On Jellyfin versions below `v10.11` the custom CSS is located at Dashboard > _General_ > Custom CSS.

 This theme looks best with background images whose content is skewed right. [As demonstrated here](./images/extras/bg-guide.jpg).

 I don't use the Live TV feature and neither Music Videos, so theme may look broken there. Not opposed to theming it, but hard to since I don't use it...

 I plan to get to theming TV mode (Settings > Display > Display Mode > TV) soon™. Looks broken right now.

---

### Disclaimers:

 Theme is still **WIP**, and may look broken in some areas. Please report any issues.

**AI Usage:**

This is a fun side-project for me and way to make my Jellyfin experience better. AI was used in the development of my changes to ZestyTheme and I tried to only use it for refactoring, code completions, and to digest and modify the existing framework built up by stpnwf rather than fully "vibe-coding" all of my updates and changes. I know it can be a controversial topic on the utilization of AI in code, but this is CSS theming and not some critical infra that agents autonomously wrote without code review. Just want to be transparent about it's usage as a tool solely intended to make my life while developing this theme easier.
