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
    <img src="https://img.shields.io/badge/Version-1.1.0-green?style=flat-square"/>
    <img src="https://img.shields.io/badge/License-GPLv3-orange?style=flat-square"/>
  </p>
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

### ❤️ Favorites & Pinning
Pin important items to keep them always on top, safe from being cleared.

**Usage:** Click the 「❤️」 icon on any card to pin/unpin. Pinned items stay at the top of the list and are preserved when clearing history.

### 📷 Screenshot Tool
Full-screen capture with annotations: rectangle, ellipse, arrow, brush, text, undo/redo, and color picker.

**Usage:**
- **Method 1:** Press global hotkey `Ctrl + 2` (customizable in settings)
- **Method 2:** Click the camera button in the toolbar

After capture, use the draggable floating toolbar to annotate. Choose from: Copy to clipboard, Save to file, or Pin to desktop.

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

### 🖱️ Drag & Drop
Drag any clipboard card out of the main window to create an independent floating window — great for multitasking and comparison.

**Usage:** Press and hold any clipboard card, drag it outside the Paster window. A standalone window with full content is created, supporting always-on-top mode. Closing it won't affect your history.

### ⌨️ Quick Insert
Quickly select text from history and auto-send it to the currently focused input field.

**Usage:** Press `Ctrl + 3` to open the Quick Insert list. Only text, link, and code entries are shown. Click any entry and Paster simulates keyboard input to type the content into your active window. The popup supports drag-to-move, close button, and ESC to dismiss.

### 🎯 Global Hotkeys
Customizable global shortcuts to show/hide the main window, launch screenshot, or quick-insert text.

**Default hotkeys:**
- `Ctrl + 1` — Show/Hide Paster main window
- `Ctrl + 2` — Launch screenshot tool
- `Ctrl + 3` — Quick Insert text

**Usage:** Go to Settings → Hotkeys to customize. Supports Ctrl/Alt/Shift + any key. Conflict detection is automatic.

### 🌓 Dark / Light Theme
One-click toggle between light and dark themes.

**Usage:**
- **Method 1:** Click the moon/sun icon in the toolbar
- **Method 2:** Select theme in Settings → General

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

**Usage:** Click the preview button on image cards. A dialog shows the original resolution image, auto-scaled to fit within 85% of screen size.

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

**Usage:** Check 「Auto Start」 in Settings → General. Paster will run in the background on every boot. Uncheck to disable without affecting saved history.

### 📥 Import & Export
Backup and restore your entire clipboard history for migration or archiving.

**Usage:** Right-click the tray icon → 「Export Backup」 to save a .pasterbak file. Right-click → 「Import Backup」 to restore. Import supports replace mode (clear existing data) or merge mode (keep existing). Backups include all history types (text, images, etc.). Regular backups recommended.

### 💡 Version Updates
Automatically checks for new versions to keep you up to date.

**Usage:**
- **Auto:** Silent check 3 seconds after launch
- **Manual:** Right-click tray icon → 「Check for Updates」
- **Settings:** Go to Settings → Update tab to view version info

When a new version is found, one-click to open the download page.

### 🌐 Language Switch
Supports Chinese and English interfaces.

**Usage:** Go to Settings → General → Language to select 中文 or English. Requires restart to take effect. All UI text, menus, tooltips, and help documentation are fully localized.

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

**Help Manual**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/14%E5%B8%AE%E5%8A%A9%E6%89%8B%E5%86%8C.png" width="80%" alt="Help Manual"/>

**Settings**

<img src="https://gitee.com/aiexporter/paster/raw/master/image/15%E8%AE%BE%E7%BD%AE%E8%8F%9C%E5%8D%95.png" width="80%" alt="Settings"/>

</div>

---

## 📥 Download & Install

Download the latest release from [**Releases**](https://gitee.com/aiexporter/paster/releases), extract the archive, and run. No installation required.

**System Requirements:** Windows 10 / Windows 11

---

## ⌨️ Hotkeys

| Hotkey | Action |
|--------|--------|
| `Ctrl + 1` | Show/Hide main window |
| `Ctrl + 2` | Launch screenshot |
| `Ctrl + 3` | Quick Insert text |
| `Esc` | Close screenshot / Close sticky note |

All hotkeys are fully customizable in Settings.

---

## 🔐 Privacy

- ✅ All data stored locally — never uploaded
- ✅ No background processes, no ad push

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Qt 6** | Cross-platform GUI framework |
| **C++17** | Core programming language |
| **CMake** | Build system |
| **Tesseract OCR** | Offline text recognition |
| **Windows API** | Global hotkeys & system interaction |

---

## 📜 Changelog

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
