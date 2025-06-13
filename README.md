# Awesome KOReader Patches and Plugins

A curated list of useful patches and plugins for [KOReader](https://koreader.rocks/) — organized by category.  
To use: drop any `.lua` file into your `koreader/patches/` folder and restart KOReader.  
Feel free to submit a PR if you have a patch/plugin to add!

> [!NOTE]
> Most of the patches and plugins listed here are unofficial and not maintained by the KOReader team, nor by me.  
> Use at your own risk, and always check the code before installing.

## 📊 Status & Progress Bar

### Patches

- [2-statusbar-cycle-presets.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-statusbar-cycle-presets.lua) – tap the bar to hop through your saved status-bar presets.
- [2-statusbar-better-compact.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-statusbar-better-compact.lua) – sleeker compact mode, optional battery %, smarter separators.
- [2-statusbar-thin-chapter.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-statusbar-thin-chapter.lua) – chapter ticks in the ultra-thin bar without adding height.
- [2-change-status-bar-color.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-change-status-bar-color.lua) – on-device colour picker for read/unread bar tones.
- [2-change-status-bar-color.lua](https://gist.github.com/IntrovertedMage/d759ff214f799cfb5e1f8c85daab6cae) – minimal hard-coded colour override.
- [2-reference-page-count.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-reference-page-count.lua) – fixes reference page math so "x / y" always makes sense.

## 📂 File-Manager & Library

### Patches

- [2-filemanager-titlebar.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-filemanager-titlebar.lua) – configurable title bar (clock, Wi-Fi, battery, RAM, uptime, etc.)
- [2-fm-title-info.lua](https://gist.github.com/hius07/c53bc1ed00e0490cb1a0709c5ed6e735) – lightweight version of title bar indicators.
- [2-custom_title.lua](https://gist.github.com/IntrovertedMage/ee3d0b7231e6bff98f7a815444ba4bcc) – replace "KOReader" header with custom text.
- [2-large-subtitles.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-large-subtitles.lua) – larger font size for folder subtitles.
- [2-shortcut-subtitles.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-shortcut-subtitles.lua) – show shortcut name instead of path.
- [2-mark_all_ebooks_as_favorite.lua](https://gist.github.com/dagrha/f24f74ff8c304d5d4b2af6425da99012) – recursively mark all EPUB/PDF files as favorite.
- [2-hide-latest-visited.lua](https://gist.github.com/ebanDev/ad067c912db947dc15a2e0c4a0a99240) – removes the horizontal underline beneath the "latest visited" folder in mosaic view.
- [2-foldercover.lua](https://gist.github.com/ebanDev/51a76595dd609cdacb35a5d375b97e61) – shows custom cover images for directories in the file browser mosaic view, optional filename/count display.

## 💤 Screensaver & Sleep Screen

### Patches

- [2-screensaver-cover.lua](https://gist.github.com/sebdelsol/4a274d43ec4439720ef2b89ed4c900e5) – centre book cover, fix overlays, clear widgets.
- [2-screensaver-chapter.lua](https://gist.github.com/sebdelsol/aba0d15f9f13d77a2f7a8be67278f93d) – display chapter title and % on sleep screen.
- [2-modify-exit-sleep-screen-message.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-modify-exit-sleep-screen-message.lua) – customise sleep prompt text.

## 🖋️ Highlights & Annotations

### Patches

- [2-customize-highlight-colors.lua](https://github.com/ImSoRight/KOReader.patches/blob/main/2-customize-highlight-colors.lua) – rename and recolour highlight options.

## 🖌️ UI & Fonts

### Patches

- [2-ui-font.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-ui-font.lua) – choose any installed TTF/OTF as KOReader's UI font.
- [2-menu-size.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-menu-size.lua) – makes menus scale to your screen's DPI.
- [2-disable-top-menu-zones.lua](https://github.com/sebdelsol/KOReader.patches/blob/main/2-disable-top-menu-zones.lua) – turns off accidental top-menu zone taps.

## 🛠️ System & Developer Tools

### Patches

- [2-toggle-usbnet.lua](https://gist.github.com/zwim/b0d46fa83d9dbb853324f3e0c17562b5) – adds a USBNet toggle to the network menu.
- [2-limit-crashlog-size.lua](https://gist.github.com/zwim/9896498977c8eeb679b516059e752de7) – keeps `crash.log` from bloating indefinitely.

### Plugins

- [crashlog.koplugin](https://github.com/billiam/crashlog.koplugin/tree/22255e20e831b929a47cdf4b8c8895ca35eea633) – Crash log viewer for KOReader.
- [findhistory.koplugin](https://github.com/koreader/contrib/tree/main/findhistory.koplugin) – Searches your KOReader metadata files to rebuild the history view after syncing books.

## 🔢 Utilities & Productivity

### Plugins

- [calculator.koplugin](https://github.com/zwim/calculator.koplugin) – A sophisticated calculator for KOReader.
- [clock.koplugin](https://github.com/koreader/contrib/tree/main/clock.koplugin) – Analog clock for KOReader.
- [digitalclock.koplugin](https://github.com/DucNg/digitalclock.koplugin/tree/04a9ab7423e90ae2dbb890c4a7497fbda9caa189) – A digital clock for KOReader that displays time, date and an image.
- [weather.koplugin](https://github.com/roygbyte/koweather/tree/5192c957f872700d245c72e4777e38fc7e3110e6) – Provides weather forecasts and conditions within KOReader.

## 🎯 Learning & Study

### Plugins

- [flashcard.koplugin](https://github.com/koreader/contrib/tree/main/flashcard.koplugin) – Implements spaced-repetition (SM-2) flashcards of your highlights and notes.
- [crossword.koplugin](https://github.com/roygbyte/crossword.koplugin/tree/eb4a497c8d220cfedf8d1f3b92298a9c69bff35f) – Solve crosswords on your KOReader device.

## 🌐 Translation & Dictionaries

### Patches

- [2-set-translation-language-per-document.lua](https://gist.github.com/IntrovertedMage/a10196c3ca471971d6ffd1a3c0c255d6) – stores a per-book translation language.
- [2-use-deepl-for-translation.lua](https://gist.github.com/IntrovertedMage/6f17103b14fdc77849ad111315d4ec24) – switch KOReader to use DeepL API.

### Plugins

- [dictionarymode.koplugin](https://github.com/ckilb/koreader-dictionarymode/tree/0a5b31b0f09b1d17c3671f2e5bda1530c4f605ea) – Enables dictionary mode (one-tap lookups) in KOReader.

## 🌐 Internet & Web

### Plugins

- [gemini.koplugin](https://github.com/koreader/contrib/tree/main/gemini.koplugin) – A Gemini client plugin for KOReader, with bookmarks, history, queue and offline caching.

## 📈 Reading Progress & Sync

### Plugins

- [hardcoverapp.koplugin](https://github.com/billiam/hardcoverapp.koplugin/tree/8da43eb0629a2b5b3e19438fb64cf4468252ea5d) – Updates your reading status on Hardcover.app directly from KOReader.
- [pocketbooksync.koplugin](https://github.com/ckilb/pocketbooksync.koplugin/tree/e909727c587b8b3bf1bb9ace3b0e4acc9a3bbe4b) – Syncs reading status between KOReader and PocketBook's original software.

## 📤 Export & Backup

### Plugins

- [provider-old-exporters.koplugin](https://github.com/koreader/contrib/tree/main/provider-old-exporters.koplugin) – Restores legacy export targets (e.g., memos, flomo) for the KOReader exporter plugin.
- [provider-webdav-highlights.koplugin](https://github.com/fairlygood/provider-webdav-highlights.koplugin/tree/a5bda0502324522e2797b45e9c588a180d1c2e7a) – Exports KOReader highlights to a WebDAV server.

