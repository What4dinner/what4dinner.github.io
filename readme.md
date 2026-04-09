# Red Hat Certified System Administrator (RHCSA) - EX200

> **Original project:** [https://github.com/RHCSA/RHCSA.github.io](https://github.com/RHCSA/RHCSA.github.io)  
> **Live site:** [https://RHCSA.github.io](https://RHCSA.github.io)

---

This is a local study fork of the RHCSA EX200 exam preparation guide. All study content (markdown files under `contents/`) and the exam simulator scripts are sourced from the original repository above.

## What Was Changed

The `index.html` was fully redesigned from the original three-column layout into a more study-friendly interface:

### Layout
- **Before:** Fixed left branding sidebar (20%) + fixed right tab navigation (20%) + narrow center content (60%)
- **After:** Slim top header with branding + collapsible left sidebar with full topic tree + wide main content area (up to 900px)

### New Features
| Feature | Description |
|---------|-------------|
| **Progress tracking** | Check off completed topics. Progress bar in the header shows `X / 57`. State persists via `localStorage` |
| **Mark as Complete** | Button at top and bottom of every topic page |
| **Prev / Next navigation** | Navigate between topics without returning to the sidebar |
| **Copy button on code blocks** | One-click copy for every command block |
| **Topic search** | Filter all 57 topics across all chapters by keyword |
| **Keyboard shortcuts** | `Alt+→` / `Alt+←` to move between topics |
| **Back-to-top button** | Appears when scrolling long topics |
| **Quick-start cards** | Home screen shortcuts to jump to key study areas |
| **Collapsible sidebar** | Toggle button to maximize reading space |

### Visual
- Terminal green (`#7dce82`) code text on near-black code blocks
- Per-block copy buttons on all `<pre>` elements
- Yellow accent headings for quick scanning
- Blockquotes styled as exam-question callouts
- Better table styling with highlighted headers
- Responsive — sidebar collapses on mobile

---

## Content Structure

```
contents/
├── 01- Understand and use essential tools/   (11 topics)
├── 02- Manage software/                      (4 topics)
├── 03- Create simple shell scripts/          (4 topics)
├── 04- Operate running systems/              (10 topics)
├── 05- Configure local storage/              (6 topics)
├── 06- Create and configure file systems/    (5 topics)
├── 07- Deploy, configure, and maintain systems/ (6 topics)
├── 08- Manage basic networking/              (4 topics)
├── 09- Manage users and groups/              (4 topics)
└── 10- Manage security/                      (8 topics)
```

**Total: 10 chapters · 57 topics**

---

## FREE Exam Simulator

Requirements: CentOS Stream 10, 2 NICs (Bridge mode), 20GB for `/` + 4×5GB disks

```bash
curl -sL https://raw.githubusercontent.com/RHCSA/RHCSA.github.io/main/Install_RHCSA_EX200_Exam_Simulator.sh | sudo bash
```

---

## Credits

All study content, exam simulator scripts, and original web application belong to the [RHCSA/RHCSA.github.io](https://github.com/RHCSA/RHCSA.github.io) project.
