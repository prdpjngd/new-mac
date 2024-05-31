# New Mac

> New mac, who dis

Bunch of checklists to do when setting up a new Mac. There must be a way to automate this; I just had to work on what I have to make the setting up happen.

Last update: 31 May 2024

<br/>

![new-mac-2022](https://user-images.githubusercontent.com/8143661/148209403-51d15220-c2cc-4dfe-8b12-41c29c57f331.jpg)
<p align='center' style="color: #9b9a97;">Wallpaper from Birmingham Museums Trust via <a href="https://unsplash.com/photos/RRn7VvZCbas">Unsplash</a></p>

<br />

**S E C T I O N S**

* [Tl;dr](#tldr)
* [Applications](#applications)
  * [First things first](#first-things-first)
  * [Design](#design)
  * [Productivity/Communication](#productivitycommunication)
  * [Dev](#dev)
  * [Mac specific apps](#mac-specific-apps)
  * [Menubar apps](#menubar-apps)
  * [Accessibility tools](#accessibility-tools)
  * [Misc](#misc)
* [OS Configuration](#os-configuration)
  * [Change computer name](#change-computer-name)
  * [Change user avatar](#change-user-avatar)
  * [Keyboard app shortcuts](#keyboard-app-shortcuts)
  * [Trackpad configuration](#trackpad-configuration)
  * [Mouse configuration](#mouse-configuration)
  * [Open Spotify only on the second desktop](#open-spotify-only-on-the-second-desktop)
* [Terminal Configuration](#terminal-configuration)

<br />

---

<br />

# Tl;dr
This will install apps available in [Homebrew](https://brew.sh/). See [files](https://github.com/arisacoba/new-mac/blob/main/setup.sh) to be installed

```
bash -c "`curl -L https://raw.githubusercontent.com/arisacoba/new-mac/master/setup.sh`"
```


# Applications

### **First things first**

- [ ]  [**Google Chrome**](https://www.google.com/chrome/): web browser. If don't like Chrome, get [**Firefox**](https://www.mozilla.org/en-US/firefox/new/)
    - [ ]  [**Vimium**](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb?hl=en): enables Vim key strokes in browser
    - [ ]  [**ColorZilla**](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=en): color picker
    - [ ]  [**WhatFont**](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?hl=en): font inspector ✨Highly recommended
    - [ ]  [**ImageSize Info**](https://chrome.google.com/webstore/detail/image-size-info/oihdhfbfoagfkpcncinlbhfdgpegcigf?hl=en): checks image's size, width, and height on browser
    - [ ]  [**Fireshot**](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg?hl=en): takes screenshots of your browser
    - [ ]  [**Images under cursor**](https://chrome.google.com/webstore/detail/images-under-cursor/kjfcpinmimcpiabejchhneahpajgklcj?hl=en): get the images and background under the cursor, in URL or file
- [ ] Download [iTerm2](https://iterm2.com/downloads.html)
- [ ] Open iTerm2
  - [ ] Change theme to `Minimal`
  - [ ] Import [iTerm profile](https://github.com/arisacoba/dotfiles/blob/main/iterm2/iterm-profile.json)
- [ ]  Install [Homebrew](https://brew.sh/)
- [ ]  Download [Node.js](https://nodejs.org/en/)
- [ ]  New wallpaper from [**Unsplash**](https://unsplash.com/)
- [ ]  Change user avatar


### **Design**

- [ ]  [**Figma**](https://www.figma.com/downloads/): browser-based design and prototype app, with collaboration
  - [ ]  Nudge amount: 8
  - [ ]  Enable `Use number keys for opacity`
- [ ] [**Responsively App**](https://github.com/manojVivek/responsively-app): mirrored user-interactions on various devices
- [ ] [**Confectionery browser**](https://confectioneryapp.com/): Take delicious screenshots of your websites. Cleaner version of Safari and Arc

### **Productivity/Communication**

- [ ]  [**Slack**](https://slack.com/intl/en-ph/help/articles/207677868-Download-Slack-for-Mac)
- [ ]  [**Notion**](https://www.notion.so/desktop): powerful note-taking app
- [ ]  [**Zoom**](https://zoom.us/download): video conferencing tool
- [ ]  [**Cron**](https://cron.com/) (Now, Notion Calendar): next-generation calendar for professionals and teams
- [ ]  [**CleanShot**](https://cleanshot.com/): Capture your Mac’s screen like a pro
- [ ]  [**Telegram**](https://macos.telegram.org/): instant-messaging app
- [ ]  (Optional) [**Viber**](https://www.viber.com/download/): instant-messaging app

### **Dev**

- [ ]  **iTerm2**: terminal emulator for Mac
- [ ]  [**Firefox Developer Edition**](https://www.mozilla.org/en-US/firefox/developer/): web browser with powerful dev tools
    - [ ]  [**Vimium**](https://addons.mozilla.org/en-US/firefox/addon/vimium-ff/)
    - [ ]  [**Pocket**](https://getpocket.com/firefox/)
    - [ ]  [**ColorZilla**](https://addons.mozilla.org/en-US/firefox/addon/colorzilla/)
    - [ ]  [**WhatFont**](https://addons.mozilla.org/en-US/firefox/addon/zjm-whatfont/)
    - [ ]  [**Fireshot**](https://addons.mozilla.org/en-US/firefox/addon/fireshot/)
    See extensions' descriptions in [#first-things-first](https://www.notion.so/arisacoba/New-Mac-b861fe5837544810a37ea02abb42427a#72b4e840e1464fed9b14a28e43ca319a)
- [ ] [**Responsively App**](https://github.com/manojVivek/responsively-app): mirrored user-interactions on various devices
- [ ] [**Fig**](https://fig.io/invite?code=fig_community): Terminal autocomplete (Now called CodeWhisperer)

### **Mac specific apps**

- [ ] [**Raycast**](https://raycast.com/): High productivity launcher (Spotlight/Alfred alternative) ✨Highly recommended
- [ ] [**MeetingBar**](https://github.com/leits/MeetingBar): lists your calendar meetings in menubar (Alternative: Cron calendar) ✨Highly recommended
- [ ] [**Spectacle**](https://www.spectacleapp.com/): easily resize windows in Mac
- [ ] [**Kap**](https://getkap.co/): screen recorder for Mac
- [ ] [**Aerial Screensaver**](https://aerialscreensaver.github.io/): a macOS screensaver that lets you play videos from Apple's tvOS screensaver
- [ ] [**Screen Studio**](https://www.screen.studio/): Beautiful screen recordings. Can't recommend this enough
- [ ] [**MuteKey**](https://apps.apple.com/us/app/mutekey/id1509590766?mt=12): Mute your microphone with hotkey
- [ ] [**Arc**](https://arc.net/download): Chrome alternative

### **Menubar apps**

- [ ]  [**Contrast**](https://usecontrast.com/): a WCAG 2.0 standard contrast ratio guide/picker
- [ ]  [**Dozer**](https://github.com/Mortennn/Dozer): hides icons in menubar (free)
- [ ]  [**Vanilla**](https://matthewpalmer.net/vanilla/): hides icons in menubar (with paid version)
- [ ]  [**Numi**](https://numi.app/) (with fee): minimalist and highly funcitional calculator
- [ ]  [**Rocket**](https://matthewpalmer.net/rocket/): emoji picker and shortcut
- [ ]  [**RunCat**](https://apps.apple.com/nz/app/runcat/id1429033973?mt=12): tracks CPU, disk, memory usage of your computer with running gif/symbol
- [ ]  [**Amphetamine**](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12): keeps your Mac awake
- [ ]  [**Mounty**](https://mounty.app/): re-mount write-protected NTFS volumes
- [ ]  [**HandMirror**](https://handmirror.app/): Hand mirror, for Mac ✨ Recommended
- [ ]  [**MonitorControl**](https://github.com/MonitorControl/MonitorControl): Control your display's brightness & volume on your Mac as if it was a native Apple Display
- [ ]  [**Clocker**](https://apps.apple.com/us/app/clocker/id1056643111?mt=12): Menubar world clock

### **Accessibility tools**

- [ ]  [**Sim Daltonism**](https://michelf.ca/projects/sim-daltonism/): Lets you visualize colors as they are perceived with various types of color blindness
- [ ]  [**Contrast**](https://usecontrast.com/): a WCAG 2.0 standard contrast ratio guide/picker
- [ ]  [**Color contrast analyser (CCA)**](https://www.tpgi.com/color-contrast-checker/): WCAG 2.0 compliant contrast ratio checker with more information than Contrast
- [ ]  [**Stark**](https://www.getstark.co/figma): Figma plugin for your accessibility audits
- [ ]  [**HeadingsMap**](https://chrome.google.com/webstore/detail/headingsmap/flbjommegcjonpdmenkdiocclhjacmbi): List the headings structure of any website

### **Misc**

- [ ]  [**Logitech Options**](https://www.logitech.com/en-ph/product/options): application to configure your logitech devices
- [ ]  [**Spotify**](https://www.spotify.com/ph/download/other/): only the music and podcast streaming you need
- [ ]  [**MacDown**](https://macdown.uranusjr.com/): markdown editor
- [ ]  [**Obsidian**](https://obsidian.md/): powerful markdown editor
- [ ]  [**Keycastr**](https://github.com/keycastr/keycastr): keystroke visualiser; useful with Kap ✨New

<br />



# OS Configuration

### Change computer name

System Preferences → General → About

![about@2x](https://github.com/arisacoba/new-mac/assets/8143661/8d193bb6-6cbc-4e58-8f6e-0198e7a82853)

### Change user avatar

System Preferences → User & Groups

![user-groups@2x](https://github.com/arisacoba/new-mac/assets/8143661/004f9e43-2495-4b8f-b61d-b1e1500c80ef)

### Keyboard app shortcuts

System Preferences → Keyboard

- [x] Enable "Keyboard navigation"
- [x] Add `1Password`, `Arc`, `Google Chrome`

![keyboard-shortcuts@2x](https://github.com/arisacoba/new-mac/assets/8143661/4d96955f-45d7-41dc-a84e-5f2140b587ff)

### Trackpad configuration

System Preferences → Trackpad

![point-and-click@2x](https://github.com/arisacoba/new-mac/assets/8143661/9a4cfdd8-aca2-4fa9-852f-b0bb7b93b33f)
![scroll-zoom@2x](https://github.com/arisacoba/new-mac/assets/8143661/7c21cb91-3b69-479a-831c-6734cf166fa8)
![more-gestures@2x](https://github.com/arisacoba/new-mac/assets/8143661/ba0b4df6-b948-4032-a455-b6e664038fb0)

**Three-finger-drag**
System Settings → Accessibility → Pointer Control

- [x] Enable "Use trackpad for dragging"

![three-finger-drag 2@2x](https://github.com/arisacoba/new-mac/assets/8143661/402ac122-76bb-4fe2-ac10-f1a56aedc0b4)

### Mouse configuration

System Preferences → Mouse

![mouse@2x](https://github.com/arisacoba/new-mac/assets/8143661/ea7ef5f7-b4c2-4a36-94ca-94c1e84a3bdc)

### Open Spotify only on the second desktop

<span style="color: #9b9a97">On dock → Right-click Spotify → Options → This Desktop</span>

<img width="780" alt="spotify-configuration" src="https://user-images.githubusercontent.com/8143661/72589019-01889680-3935-11ea-8d4b-88ce39985b48.jpg">

<br />

### Figma shortcuts
Using [LogiOptions+](https://www.logitech.com/en-ph/software/logi-options-plus.html)

![mxmaster3-figma-shortcuts](https://github.com/arisacoba/new-mac/assets/8143661/a1c3e1be-b321-438c-8a74-8a91b4fe4af8)



# Terminal Configuration

- [ ]  Install [**Homebrew**](https://brew.sh/)
- [ ]  Install **zsh**

        $ brew install zsh

- [ ]  Install [**oh-my-zsh**](https://github.com/ohmyzsh/ohmyzsh)
- [ ]  Configure **~/.zshrc**
- [ ]  Install [**yarn**](https://yarnpkg.com/lang/en/docs/install/#mac-stable)

        brew install yarn

- [ ]  Configure [**~/.vimrc**](https://github.com/arisacoba/setting-up-vim)

<br /><br /><br />

---

Made by **[@aris_acoba](https://arisacoba.com/)**

2024 • [aris.acoba@gmail.com](mailto:aris.acoba@gmail.com)
