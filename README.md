# Awesome KOReader Patches and Plugins

A curated list of useful patches and plugins for [KOReader](https://koreader.rocks/) — organized by category.  
To use: drop any `.lua` file into your `koreader/patches/` folder and restart KOReader.  
Feel free to submit a PR if you have a patch/plugin to add!

> [!NOTE]
> Most of the patches and plugins listed here are unofficial and not maintained by the KOReader team, nor by me.  
> Use at your own risk, and always check the code before installing.

--

## 📊 Status & Progress Bar

- [2-statusbar-cycle-presets.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-statusbar-cycle-presets.lua) – tap the bar to hop through your saved status-bar presets.
- [2-statusbar-better-compact.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-statusbar-better-compact.lua) – sleeker compact mode, optional battery %, smarter separators.
- [2-statusbar-thin-chapter.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-statusbar-thin-chapter.lua) – chapter ticks in the ultra-thin bar without adding height.
- [2-change-status-bar-color.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-change-status-bar-color.lua) – on-device colour picker for read/unread bar tones.
- [2-change-status-bar-color.lua](https://gist.github.com/IntrovertedMage/d759ff214f799cfb5e1f8c85daab6cae) – minimal hard-coded colour override.
- [2-reference-page-count.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-reference-page-count.lua) – fixes reference page math so "x / y" always makes sense.

## 📂 File-Manager & Library

- [2-filemanager-titlebar.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-filemanager-titlebar.lua) – configurable title bar (clock, Wi-Fi, battery, RAM, uptime, etc.)
- [2-fm-title-info.lua](https://gist.github.com/hius07/c53bc1ed00e0490cb1a0709c5ed6e735) – lightweight version of title bar indicators.
- [2-custom_title.lua](https://gist.github.com/IntrovertedMage/ee3d0b7231e6bff98f7a815444ba4bcc) – replace "KOReader" header with custom text.
- [2-large-subtitles.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-large-subtitles.lua) – larger font size for folder subtitles.
- [2-shortcut-subtitles.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-shortcut-subtitles.lua) – show shortcut name instead of path.
- [2-mark_all_ebooks_as_favorite.lua](https://gist.github.com/dagrha/f24f74ff8c304d5d4b2af6425da99012) – recursively mark all EPUB/PDF files as favorite.
- [2-hide-latest-visited.lua](https://gist.github.com/ebanDev/ad067c912db947dc15a2e0c4a0a99240) – removes the horizontal underline beneath the "latest visited" folder in mosaic view.
- [2-foldercover.lua](https://gist.github.com/ebanDev/51a76595dd609cdacb35a5d375b97e61) – shows custom cover images for directories in the file browser mosaic view, optional filename/count display.

## 💤 Screensaver & Sleep Screen

- [2-screensaver-cover.lua](https://gist.github.com/sebdelsol/4a274d43ec4439720ef2b89ed4c900e5) – centre book cover, fix overlays, clear widgets.
- [2-screensaver-chapter.lua](https://gist.github.com/sebdelsol/aba0d15f9f13d77a2f7a8be67278f93d) – display chapter title and % on sleep screen.
- [2-modify-exit-sleep-screen-message.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-modify-exit-sleep-screen-message.lua) – customise sleep prompt text.

## 🖋️ Highlights & Annotations

- [2-customize-highlight-colors.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-customize-highlight-colors.lua) – rename and recolour highlight options.

## 🌐 Translation & Dictionaries

- [2-set-translation-language-per-document.lua](https://gist.github.com/IntrovertedMage/a10196c3ca471971d6ffd1a3c0c255d6) – stores a per-book translation language.
- [2-use-deepl-for-translation.lua](https://gist.github.com/IntrovertedMage/6f17103b14fdc77849ad111315d4ec24) – switch KOReader to use DeepL API.

## 🖌️ UI & Fonts

- [2-ui-font.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-ui-font.lua) – choose any installed TTF/OTF as KOReader's UI font.
- [2-menu-size.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-menu-size.lua) – makes menus scale to your screen's DPI.
- [2-disable-top-menu-zones.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-disable-top-menu-zones.lua) – turns off accidental top-menu zone taps.

## 🛠️ System & Developer Tools

- [2-toggle-usbnet.lua](https://gist.github.com/zwim/b0d46fa83d9dbb853324f3e0c17562b5) – adds a USBNet toggle to the network menu.
- [2-limit-crashlog-size.lua](https://gist.github.com/zwim/9896498977c8eeb679b516059e752de7) – keeps `crash.log` from bloating indefinitely.

