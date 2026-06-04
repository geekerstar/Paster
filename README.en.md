<div align="center">
  <img src="https://gitee.com/aiexporter/paster/raw/master/image/logo.png" alt="Paster Logo" width="128" height="128"/>
  <h1>Paster - Clipboard Manager</h1>
  <p><strong>Lightweight · Efficient · Privacy-First · Completely Free</strong></p>
  <p>
    <a href="#-features">Features</a> ·
    <a href="#-download--install">Download</a> ·
    <a href="#-hotkeys">Hotkeys</a> ·
    <a href="#-changelog">Changelog</a> ·
    <a href="#-privacy">Privacy</a>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Platform-Windows-blue?style=flat-square"/>
    <img src="https://img.shields.io/badge/Version-1.1.3-green?style=flat-square"/>
    <img src="https://img.shields.io/badge/License-GPLv3-orange?style=flat-square"/>
  </p>
</div>

<div align="center" style="background-color:#fff3cd;border:1px solid #ffc107;border-radius:6px;padding:10px 16px;margin:12px 0;">
  <strong>🔥 v1.1.3 Released: Quick Insert overhaul (search/image preview/type filter) / Backup now includes sticky notes / Image Save As / First-time empty state guide / Enhanced keyboard interaction — Download Now!</strong>
</div>

<div align="center" style="background:#fffbe6;border:1px solid #ffe58f;border-radius:8px;padding:16px 20px;margin:16px 0;">
  <p><strong>🎉 This software is completely free and forever — built with love, updated with passion! 🎉</strong></p>
  <p><strong>If you find it useful, don't forget to ⭐ Star the repo!</strong></p>
  <p><strong>Scan to follow our WeChat official account for the latest updates, tutorials & more desktop productivity tools.</strong></p>
  <p><strong>Bug reports & feature requests are always welcome — let's make the best clipboard tool together!</strong></p>
</div>

---

## 📋 Features

### 🗂️ Clipboard History
Automatically saves all copied text, images, files, links, and code, sorted in reverse chronological order — never lose anything again.

**Usage:** After copying anything (Ctrl+C), open the Paster main window to see your history. Supports text, images (PNG/JPG), file paths, hyperlinks, code snippets, and more. History limit is configurable in Settings → General (100–1000 items).

### 🔍 Search & Filter
Real-time search with keyword highlighting. Filter by content type or folder.

**Usage:** Type keywords into the search bar at the top of the main window. Results are filtered in real-time with highlighted matches. Supports type filter (All/Text/Link/Code/Image/Files) and folder-based filtering.

### ⌨️ Keyboard Navigation
Navigate between clipboard cards using keyboard shortcuts — no mouse needed.

**Usage:** In the main window card area, use the following keyboard controls:
- ←/↑ — Select previous card
- →/↓ — Select next card
- Enter — Single-click behavior (text/code → copy, link → open, image → preview, file → open)
- Quick double Enter — Double-click behavior (text/link/code → paste at cursor, others → copy)
- Space — Preview/close selected card content

The selected card is highlighted with a blue border for easy identification.

### ❤️ Favorites & Pinning
Pin important items to keep them always on top, safe from being cleared.

**Usage:** Click the 「❤️」 icon on any card to pin/unpin. Pinned items stay at the top of the list and are preserved when clearing history.

### 📷 Screenshot Tool
Full-screen capture with rich annotation tools: rectangle, ellipse, arrow, brush, text, mosaic, highlighter, eraser, crop, and more — plus undo/redo and color picker.

**Usage:**
- **Method 1:** Press global hotkey `Ctrl + 2` (customizable in settings)
- **Method 2:** Click the camera button in the toolbar

After capture, use the toolbar to annotate, supporting:
- ▸ Rectangle/Ellipse  ▸ Arrow  ▸ Freehand brush  ▸ Text
- ▸ Mosaic  ▸ Highlighter  ▸ Eraser  ▸ Line tool
- ▸ Crop  ▸ Resize  ▸ Watermark  ▸ Bubble annotation
- ▸ Step numbering  ▸ Layer management  ▸ Color picker
- ▸ Image adjustments: brightness/contrast/grayscale/sepia/invert/opacity
- ▸ Undo/Redo

Choose from: Copy to clipboard, Save to file, or Pin to desktop.

### 👁️ OCR Text Recognition
Recognize text from screenshots or images. Supports Chinese and English.

**Usage:**
- **Prerequisite:** Ensure Tesseract OCR engine is available in Settings → OCR
- **How to use:**
  - Click 「OCR」 in the screenshot toolbar after capture
  - Click 「OCR」 in the image preview window

Results appear in a popup — one-click copy. Multiple result windows can be open simultaneously, each draggable, resizable, and pinnable.

### 📌 Desktop Pin (Sticky Notes)
Pin screenshots or images to your desktop — zoom, annotate, rotate, flip. Like a sticky note.

**Usage:** Click 「📌 Pin to Desktop」 in the screenshot tool. On the pinned window:
- Drag edges to resize
- Scroll to zoom
- Right-click for rotate/flip
- Continue annotating
- Click close to remove

### 🎬 Screen Recording
Record a screen region in GIF / MP4 / WebM format, with optional audio, cursor, and hardware acceleration.

**Usage:**
- **Method 1:** Press global hotkey `Ctrl + 4` (customizable in settings)
- **Method 2:** Select 「Start Recording」 from the system tray context menu

Configure recording in Settings → Recording tab:
- ▸ Format: GIF (default) / MP4 / WebM
- ▸ FPS: 1~60 FPS (GIF: 10~15 recommended, Video: 24~30)
- ▸ Capture area: Region selection / Full screen / Active window
- ▸ Audio: None / Microphone / System sound / Both
- ▸ GIF settings: loop count, dithering algorithm, encoder, color bits
- ▸ Video settings: CRF quality, encoding preset, hardware acceleration
- ▸ Max duration, idle auto-stop

After recording, preview, copy to clipboard, or save to file. MP4/WebM requires FFmpeg — download and install it in Settings → Recording.

### 🖱️ Drag & Drop
Drag any clipboard card out of the main window to create an independent floating window — great for multitasking and comparison.

**Usage:** Press and hold any clipboard card, drag it outside the Paster window. A standalone window with full content is created, supporting always-on-top mode. Closing it won't affect your history.

### ⌨️ Quick Insert
Quickly select history items (text, links, code, images) and auto-send them to the currently focused input field.

**Usage:** Press `Ctrl + 3` to open the Quick Insert popup. The search box at the top filters entries in real-time. Use ↑↓ to navigate, Enter to confirm. Image entries display as 40×40 thumbnails; press Space for a full-size preview that closes on release. Configure visible types (text/link/code/image) in Settings → General. The popup supports drag-to-move, close button, and ESC to dismiss.

### ⌨️ Quick Phrase Input
Create custom text phrases and bind global hotkeys — press a hotkey to instantly send preset text at the cursor position.

**Usage:** Go to Settings → Quick Input tab, click 「Add」 to create a new entry. Enter the phrase text, then click the hotkey button to bind a key combination. Save and press the hotkey in any application to auto-input the phrase. Supports multiple entries, each with a different hotkey.

### 🎯 Global Hotkeys
Customizable global shortcuts to show/hide the main window, launch screenshot, quick-insert text, or start screen recording.

**Default hotkeys:**
- `Ctrl + 1` — Show/Hide Paster main window
- `Ctrl + 2` — Launch screenshot tool
- `Ctrl + 3` — Quick Insert text
- `Ctrl + 4` — Start screen recording

**Usage:** Go to Settings → Hotkeys to customize. Supports Ctrl/Alt/Shift + any key. Conflict detection is automatic.

### 🌓 Dark / Light Theme
One-click toggle between light and dark themes.

**Usage:**
- **Method 1:** Click the moon/sun icon in the toolbar
- **Method 2:** Select theme in Settings → General via radio buttons

Changes take effect instantly across the entire app, including tray menu and screenshot tool.

### 🎨 Card Customization
Adjust card size, opacity, and text alignment.

**Usage:** Go to Settings → Card:
- **Card size:** 120px / 160px / 200px / 240px
- **Card opacity:** 50% ~ 100%
- **Card alignment:** Left / Center / Center-Right / Center-Left / Center-Outward / Right

All changes take effect in real-time.

### 📍 Window Positioning
Multiple preset window positions to fit your workflow.

**Usage:** Go to Settings → General → Window Position:
- Bottom Center (default) / Top Center / Left Center / Right Center / Screen Center / Follow Mouse / Custom Position

Remembers custom position between sessions.

### ✏️ Inline Editing
Edit text, link, and code entries directly. Changes save automatically.

**Usage:** Right-click a card (or click the edit button) and select 「Edit」. Modify content in the dialog — it saves automatically. Only text, link, and code types are editable; images and files are not.

### 🔗 Links & Files
Open links in your browser, reveal files in Explorer — all with one click.

**Usage:**
- **Link type:** Click the link button or double-click to open in default browser
- **File type:** Click the folder button to open Explorer and select the file
- **Image type:** Show image source file in Explorer

### 🖼️ Image Preview
Click image cards for full-resolution preview.

**Usage:** Click the preview button on image cards. A dialog shows the original resolution image, auto-scaled to fit within 85% of screen size. Right-click an image card and select 「Save As...」 to save as PNG or JPEG; the save path is remembered from your last use.

### 🔤 Syntax Highlighting
Code snippets are automatically detected and displayed with colorful syntax highlighting.

**Usage:** When you copy code, Paster auto-detects the language (C++/Python/JavaScript/Java/C#). Code cards display with rich syntax highlighting. Standalone windows and preview popups also support highlighting. Code items are automatically categorized for type-based filtering.

### 🗃️ Folder Management
Organize clipboard history into custom folders for better categorization.

**Usage:** Click 「+」 in the toolbar to create a folder. Right-click a card → 「Copy to Folder」 or 「Move to Folder」. Use the folder dropdown in the toolbar to filter: All / Uncategorized / Specific folder. Folders are persisted locally.

### 🖼️ Grid Overview
Browse all clipboard items in a tiled grid layout for quick visual scanning.

**Usage:** Click the grid button in the toolbar. Each item is displayed as a 180×180px tile. Click to copy and auto-close. Supports Ctrl+click multi-select and batch delete. Press ESC or click × to exit.

### 📦 Batch Operations
Select multiple items at once for efficient batch deletion.

**Usage:** Hold Ctrl and click cards to multi-select. The toolbar shows 「N selected」 and 「Delete Selected」. Deleted items go to Trash for recovery. Works in both normal and grid views.

### ♻️ Trash
Deleted items go to Trash to prevent accidental loss. Supports recovery.

**Usage:** Click the trash button in the toolbar. In Trash you can: Restore single item / Restore all / Permanently delete / Empty trash. Retention period configurable in Settings → General (7/15/30 days or never expire). Expired items auto-clean.

### 🔔 Toast Notification
When the main window is hidden, new clipboard items show a brief notification in the bottom-right corner.

**Usage:** When Paster is hidden, copying new content triggers a 3-second toast with a content preview (text snippet / image thumbnail / filename). Click the notification to locate the item in history. Can be toggled on/off in Settings → General.

### 🔒 Local Storage Only
All data is stored locally — no internet connection required, no cloud upload, privacy guaranteed. You can click 「Clear All Data」 in Settings → General to wipe all records at once.

### ⏬ Auto Start
Launch Paster automatically at system startup, ready when you need it.

**Usage:** Check 「Auto Start」 in Settings → General. Auto-start is registered automatically on first launch. Paster will run in the background on every boot. Uncheck to disable without affecting saved history.

### 📥 Import & Export
Backup and restore your entire clipboard history for migration or archiving.

**Usage:** Right-click the tray icon → 「Export Backup」 to save a .pasterbak file. Right-click → 「Import Backup」 to restore. Import supports replace mode (clear existing data) or merge mode (keep existing data, dedup by ID). Backups include all history types (text, images, sticky notes, etc.). Regular backups recommended.

### 💡 Version Updates
Automatically checks for new versions to keep you up to date.

**Usage:**
- **Auto:** Silent check 3 seconds after launch
- **Manual:** Right-click tray icon → 「Check for Updates」
- **Settings:** Go to Settings → Update tab to view version info

When a new version is found, one-click to open the download page.

### 🌐 Language Switch
Supports Chinese and English interfaces.

**Usage:** Go to Settings → General → Language to select 中文 or English via radio buttons. Requires restart to take effect. All UI text, menus, tooltips, and help documentation are fully localized.

### ⏸️ Pause Monitoring
Temporarily pause clipboard monitoring to protect sensitive content.

**Usage:** Right-click the tray icon → 「Pause Monitoring」. Paster stops recording new clipboard items. Click 「Resume Monitoring」 to continue. Ideal when copying passwords or sensitive data.

### 🖥️ System Tray
Paster lives in the system tray — runs quietly in the background, one click away when needed.

**Usage:** The tray icon appears on launch. Right-click menu includes: Show/Hide, Quick Insert, Screenshot, Pause Monitoring, Toggle Theme, Clear History, Export/Import Backup, Settings, Check Updates, Help, Quit. Left-click/double-click toggles the main window. Close minimizes to tray by default (configurable in Settings).

---

## 📸 Screenshots

<div align="center">

**Light Theme**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/1%E6%B5%85%E8%89%B2%E4%B8%BB%E9%A2%98.png" width="80%" alt="Light Theme"/>

**Dark Theme**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/2%E6%B7%B1%E8%89%B2%E4%B8%BB%E9%A2%98.png" width="80%" alt="Dark Theme"/>

**Search Highlighting**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/3%E6%90%9C%E7%B4%A2%E9%AB%98%E4%BA%AE.png" width="80%" alt="Search Highlighting"/>

**Desktop Pin**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/4%E6%A1%8C%E9%9D%A2%E8%B4%B4%E5%9B%BE.png" width="80%" alt="Desktop Pin"/>

| **Image OCR** | **Screenshot OCR** |
|:---:|:---:|
| <img src="https://gitee.com/aiexporter/paster/raw/master/image/5%E5%9B%BE%E7%89%87OCR.png" width="100%" alt="Image OCR"/> | <img src="https://gitee.com/aiexporter/paster/raw/master/image/6%E6%88%AA%E5%9B%BEOCR.png" width="100%" alt="Screenshot OCR"/> |

**OCR Text Overlay on Image**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/7%E8%AF%86%E5%88%AB%E5%90%8E%E5%B0%86%E6%96%87%E5%AD%97%E6%98%BE%E7%A4%BA%E5%88%B0%E5%9B%BE%E7%89%87.png" width="80%" alt="OCR Text Overlay"/>

| **Import & Export** | **Trash** |
|:---:|:---:|
| <img src="https://gitee.com/aiexporter/paster/raw/master/image/8%E5%AF%BC%E5%85%A5%E5%AF%BC%E5%87%BA.png" width="100%" alt="Import & Export"/> | <img src="https://gitee.com/aiexporter/paster/raw/master/image/9%E5%9B%9E%E6%94%B6%E7%AB%99.png" width="100%" alt="Trash"/> |

**Grid View**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/10%E7%BD%91%E6%A0%BC%E8%A7%86%E5%9B%BE.png" width="80%" alt="Grid View"/>

**Toast Notification**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/11%E5%8F%B3%E4%B8%8B%E8%A7%92%E9%80%9A%E7%9F%A5.png" width="80%" alt="Toast Notification"/>

| **Quick Insert** | **Quick Insert** |
|:---:|:---:|
| <img src="https://gitee.com/aiexporter/paster/raw/master/image/12%E5%BF%AB%E9%80%9F%E6%8F%92%E5%85%A5%E6%96%87%E6%9C%AC1.png" width="100%" alt="Quick Insert 1"/> | <img src="https://gitee.com/aiexporter/paster/raw/master/image/13%E5%BF%AB%E9%80%9F%E6%8F%92%E5%85%A5%E6%96%87%E6%9C%AC2.png" width="100%" alt="Quick Insert 2"/> |

**Quick Phrase Input**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/14%E5%BF%AB%E6%8D%B7%E7%9F%AD%E8%AF%AD%E8%BE%93%E5%85%A5.png" width="80%" alt="Quick Phrase Input"/>

**Recording Settings**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/15%E8%A7%86%E9%A2%91%E5%BD%95%E5%88%B6%E8%AE%BE%E7%BD%AE.png" width="80%" alt="Recording Settings"/>

**Recording Interface**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/16%E8%A7%86%E9%A2%91%E5%BD%95%E5%88%B6%E7%95%8C%E9%9D%A2.png" width="80%" alt="Recording Interface"/>

**Help Manual**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/17%E5%B8%AE%E5%8A%A9%E6%89%8B%E5%86%8C.png" width="80%" alt="Help Manual"/>

</div>

---

## 📥 Download & Install

Download the latest release for your platform from [**Releases**](https://gitee.com/aiexporter/paster/releases).

| Platform | Package | Notes |
|----------|---------|-------|
| **Windows** | `Paser-Setup.exe` | Extract and run, no installation required |
| **Linux** | `Paster-x86_64.AppImage` | Set executable permission and run (see guide below) |
| **macOS** | `Paster.dmg` | Drag to Applications folder (see guide below) |

**System Requirements:**
- **Windows:** Windows 10 / Windows 11
- **Linux:** Ubuntu 24.04+ x86_64 only. ARM architecture is not currently supported — contact the author if you need an ARM build. Due to limited resources, Windows version is the primary focus
- **macOS:** Apple Silicon (M-series) only. Intel Macs are not currently supported. Due to limited resources, please contact the author if you encounter any bugs

---

## ⌨️ Hotkeys

| Hotkey | Action |
|--------|--------|
| `Ctrl + 1` | Show/Hide main window |
| `Ctrl + 2` | Launch screenshot |
| `Ctrl + 3` | Quick Insert text |
| `Ctrl + 4` | Start screen recording |
| `Esc` | Close screenshot / Close sticky note |

All hotkeys are fully customizable in Settings.

---

## 🔐 Privacy

- ✅ All data stored locally — never uploaded
- ✅ No background processes, no ad push

---

## 🐧 Linux & macOS Usage Guide

### Linux

**Run command:**
```bash
chmod +x Paster-x86_64.AppImage
./Paster-x86_64.AppImage
```

You can also double-click the file and select "Execute".

**Important Notes:**
- Global hotkeys only work under **X11** sessions (not supported on Wayland)
- If the tray icon doesn't appear, check if your desktop environment supports system trays (recommended: GNOME + AppIndicator extension, or KDE Plasma)
- OCR requires Tesseract: `sudo apt install tesseract-ocr` (Ubuntu/Debian), or one-click install in Settings
- Data storage location: `~/.local/share/Paster/`

### macOS

**Installation steps:**
1. Download `Paster.dmg`
2. Double-click to mount, drag `Paster.app` into the **Applications** folder
3. First launch: Right-click `Paster.app` → select "Open" (bypass unsigned app warning)
4. Click "Open" on the security prompt
5. Subsequent launches: double-click normally

**Important Notes:**
- First launch will request **Accessibility** and **Input Monitoring** permissions (for global hotkeys and auto-paste) — grant these in System Settings when prompted
- macOS uses the native Vision framework for OCR (no additional installation required)
- Supports both Intel and Apple Silicon (universal binary)
- Data storage location: `~/Library/Application Support/Paster/`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Qt 6** | Cross-platform GUI framework |
| **C++17** | Core programming language |
| **CMake** | Build system |
| **Tesseract OCR** | Offline text recognition (Windows/Linux) |
| **Apple Vision** | Native OCR framework (macOS) |
| **FFmpeg** | Screen recording engine |
| **Windows API** | Screenshot, global hotkeys, system interaction (Windows) |
| **X11 / XGrabKey** | Global hotkeys (Linux) |
| **Core Graphics / Accessibility** | Global hotkeys & input simulation (macOS) |

---

## 📜 Changelog

### v1.1.3 (Latest Release, Recommended)

**✨ Image Enhancements:**
- New 「Save As...」 option on image card right-click menu, supports PNG / JPEG format
- Screenshot tool and image save-as path auto-remembered for convenience

**📦 Backup & Restore:**
- Export/import now fully includes desktop sticky notes — replace mode overwrites, merge mode deduplicates by ID
- Fixed image showing as "Image Expired" after import

**⌨️ Quick Insert (Ctrl+3) Overhaul:**
- New search box at the top for real-time text filtering
- ↑↓ switches between search and list; ↑ at top returns to search; typing jumps back to search
- Image support: 40×40 thumbnails, auto-paste on confirm
- Press Space on an image entry for full-size preview — release to close, no interruption
- Centered and beautified title bar, adaptive to dark/light themes
- New 「Quick Insert Types」 checkboxes in Settings → General to customize visible types

**🎨 UI Polish:**
- Increased Settings → General page height, optimized layout
- New first-time user guidance: empty state with prompt text + visible toolbar
- Fixed double-click issue caused by scroll-to-center on focus
- Theme and language selection changed from dropdown to radio buttons for cleaner layout

**⌨️ Keyboard Interaction:**
- Enter on card = single-click behavior (text/code → copy, link → open, image → preview, file → open)
- Quick double Enter = double-click behavior (text/link/code → paste at cursor, others → copy)

---

### v1.1.2

**📝 Desktop Sticky Notes:**

- Added a rainbow color dot on the sticky note title bar — click to freely choose any color, no longer limited to presets
- Custom text color: click the 「A」 button on the formatting toolbar to pick any color for your text; color persists after reopening
- Close confirmation dialog tells you "Closing a note only hides it — your content is safe", with a "Don't show again" checkbox
- Each note now has a 「≡」 button at the bottom-right corner to view and manage all desktop notes

**🗂️ Sticky Note Management (Grid View):**
- Full-screen grid management mode — all notes displayed as cards like a photo wall
- Each card's color, text formatting, and timestamp matches the desktop version
- Ctrl+click multi-select with a blue action bar at the top for batch deletion
- Grid stays open after deletion for continued operations
- Note count and titles update in real-time

**😊 Emoji & Text Tools:**
- New 「😊」 button on the formatting toolbar — click to open an emoji picker, selected emoji inserts directly into text
- New 「···」 expand button on the toolbar containing additional text tools:
  - H1 / H2 heading formats
  - Text highlight background (highlighter effect)
  - Left / Center / Right alignment
  - Clear formatting
  - Insert hyperlink
- Frequently used tools (B I U S etc.) stay visible; less common ones are tucked into 「···」

**⌨️ Quick Insert Enhancements:**
- The Quick Insert list (Ctrl+3) now supports ↑↓ arrow keys for selection and Enter to confirm
- Selected item auto-pastes to the active input field and closes the window
- First item is selected by default on open for faster operation

**🌐 LAN Sharing & Remote Connection:**
- Two new toolbar buttons after 「New Note」: 「LAN Share」 and 「Remote Connect」
- Both use SVG icons that auto-adapt to light/dark themes

**🎨 UI Polish:**
- Toolbar buttons (theme, screenshot, recording, grid, trash, etc.) now auto-adapt their colors in light/dark themes
- Sticky note toolbar button colors automatically switch based on note background for readability
- Optimized display handling for deleted items in note grid

**🔧 Bug Fixes:**
- Fixed Quick Insert window not receiving keyboard input
- Fixed note management grid closing after batch delete (now stays open)
- Fixed formatting toolbar buttons hard to read on certain colored backgrounds
- Fixed dual-monitor screenshot not adapting correctly

---

### v1.1.1

**New Features:**
- Screen recording with region selection, outputs GIF/MP4/WebM
- FFmpeg recording engine with auto-download and install
- Rich recording settings: FPS, quality, codec, hardware acceleration, audio source
- Quick phrase input: create custom text phrases and bind global hotkeys for one-click send
- Enhanced screenshot tool: new mosaic, highlighter, eraser, crop, resize, watermark tools
- Image adjustments: brightness, contrast, grayscale, sepia, invert, opacity
- Layer management for multi-layer screenshot editing
- Step annotation tool for tutorial screenshots
- Rich text (HTML) clipboard support preserving text formatting
- New update download dialog with progress bar and one-click install

**Improvements:**
- HiDPI screenshot optimization for accurate pixel capture on high-DPI displays
- Gaussian blur shadow rendering for smoother visual effects
- Global hotkey system rewrite fixing Windows hotkey issues
- Right-click menu rewrite fixing menu display on certain platforms
- OCR download source migrated to Gitee mirror for faster downloads in China
- Default recording FPS changed to 30, default audio source changed to System sound
- Default card base opacity adjusted from 0.75 to 0.85
- Build system optimization, removed external QHotkey dependency

**Bug Fixes:**
- Fixed image/file types not copying to clipboard
- Fixed rare crash when dragging out cards
- Fixed incorrect OCR download path
- Fixed display issues in dark mode

---

### v1.1.0 (Milestone Release, Recommended)
**New Features:**
- Draggable floating toolbar for screenshot annotations
- Grid layout mode for one-screen browsing of all clipboard history
- Optimized search with keyword highlighting for faster lookup
- Card type filter dropdown for quick category-based filtering
- Custom folder management: create folders and organize clipboard items
- One-click move/copy cards to folders for better organization
- History import/export with merge or replace mode
- Ctrl+click multi-select for batch deletion
- Toast notification for new clipboard items (toggleable, clickable)
- Trash with 30-day retention to recover deleted items
- Quick Insert popup now supports drag, close button, and ESC
- Syntax highlighting for code snippets with auto language detection
- Custom window position memory across sessions
- Internationalization with Chinese/English language support

---

### v1.0.9
**New Features:**
- Settings UI style and layout improvements
- "Unlimited" option for max history items
- Right-click OCR on image cards
- OCR result popup can be pinned to desktop like cards
- Multiple OCR result windows supported simultaneously, with drag & resize
- Beautified OCR result window and drag-out card styles
- Pinned desktop images support right-click OCR
- OCR text overlay on image at recognized position (disabled by default)
- Enhanced tray icon right-click menu

---

### v1.0.8
Thanks to Xiaohongshu users for the OCR feature request — now fully integrated, fully offline.

**New Features:**
- Built-in offline OCR using local Tesseract engine, no external dependencies
- Help manual added

---

### v1.0.7
Thanks to Xiaohongshu user 【@迷彩达叔】 for the following suggestions and bug reports:

**New Features:**
- Files copied from Explorer are auto-detected as images if they are images, showing thumbnails
- Click file/image cards to open Explorer and select the file
- Image cards show a "Reveal in Explorer" button
- Text cards: single-click to copy, double-click to insert at cursor
- New window position: "Follow Mouse" — appears below cursor on wake
- Quick Insert mode: list all text history, click to insert at cursor
- File cards now show file icon + filename instead of just filename
- New card alignment options: center-right, center-left, center-outward, left, right

**Bug Fixes:**
- Fixed Win11 dark mode text rendering in settings
- Fixed some custom hotkey configurations not working
- Various UI polish improvements

---

### v1.0.6
**New Features:**
- Auto-start on boot, always ready in the background
- Automatic version update check with one-click download
- Settings UI redesign with dedicated hotkey configuration panel
- Card alignment: Left / Center / Right
- Double-click links to open in browser, double-click files to reveal

**Improvements:**
- Customizable history limit (100–1000 items)
- Window position auto-remembered between sessions
- Performance optimizations and reduced memory usage

---

### v1.0.5
**New Features:**
- Image preview, click to view full resolution
- Inline editing for text/link/code entries
- Card alignment configuration

**Improvements:**
- Color picker for screenshot annotations
- Drag-out windows support always-on-top
- Improved link and file interactions

---

### v1.0.4
**New Features:**
- One-click dark/light theme toggle
- Card size: 120px / 160px / 200px / 240px
- Card opacity: 50% ~ 100%
- Drag-out mode: cards become standalone windows

**Improvements:**
- Enhanced screenshot annotations with freehand brush and text
- Customizable global hotkeys

---

### v1.0.3
**New Features:**
- Built-in screenshot tool with full-screen and rectangular capture
- Annotations: rectangle, ellipse, arrow, brush, text
- Screenshot undo/redo
- Desktop pin for screenshots
- Global hotkeys: `Ctrl+1` show/hide, `Ctrl+2` screenshot

---

### v1.0.2
**New Features:**
- Real-time search filtering
- Favorites & pinning
- Window positioning: bottom, top, left, right, center
- System tray with always-on background mode

**Improvements:**
- Card UI with rounded corners and hover effects
- Faster history loading

---

### v1.0.1
**Initial Release:**
- Basic clipboard history — auto-save text, images, files, links, and code
- Reverse chronological order
- Local JSON + PNG storage for privacy
- Tray icon with right-click menu
- Ctrl+C auto-capture, Ctrl+V one-click paste

---

## 📢 Follow Us

<div align="center">
  <img src="https://gitee.com/aiexporter/paster/raw/master/image/weixin.png" width="240" alt="WeChat QR Code"/>
  <p><strong>Scan to follow our WeChat official account</strong></p>
  <p>Get latest release notifications, feature updates & dev news</p>
</div>

---

## ☕ Support

<div align="center" style="background:#fffbe6;border:1px solid #ffe58f;border-radius:8px;padding:16px 20px;margin:16px 0;">
  <p><strong>🎉 This software is completely free and forever — built with love, updated with passion! 🎉</strong></p>
  <p><strong>If Paster helps you, feel free to buy me a coffee ☕ — your support keeps updates coming!</strong></p>
  <p><strong>All features are completely free. Donations are voluntary. Thank you for every bit of support ❤️</strong></p>
</div>

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://gitee.com/aiexporter/paster/raw/master/image/wx.png" width="240" alt="WeChat Pay"/>
        <p><strong>WeChat Pay</strong></p>
      </td>
      <td align="center">
        <img src="https://gitee.com/aiexporter/paster/raw/master/image/zfb.png" width="240" alt="Alipay"/>
        <p><strong>Alipay</strong></p>
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <p>If Paster helps you, please ⭐ Star the repo!</p>
</div>
