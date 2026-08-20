# Shaiera Shera — Portfolio Website

A personal portfolio website with a retro desktop OS aesthetic, built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies.

## Features

- **Desktop UI** — windowed layout with draggable windows, a taskbar, and clickable desktop icons
- **Light/Dark mode** — toggle between themes with the sun/moon button in the taskbar
- **CRT scanlines** — optional retro scanline overlay
- **Loading screen** — animated boot sequence on page load
- **Notepad widget** — a floating scratchpad with local auto-save
- **Mini games** — playable Pong and Snake (desktop only)
- **Panels** — About Me, Resume, Projects, Portfolio (art gallery), Contact, and More
- **Responsive** — adapted layout for mobile screens; games and notepad hidden on small screens
- **Custom font** — uses `Comicoro.ttf` throughout

## File Structure

```
Portfolio Website/
├── index.html                        # Main page — all HTML, CSS, and JS in one file
├── Comicoro.ttf                      # Custom font
├── image.jpg                         # Profile photo
├── Software_Engineering_Resume.docx  # Downloadable resume
├── backgrounds/
│   ├── image.jpg                     # Light mode background
│   └── Untitled design.png           # Dark mode background
├── icons/                            # UI icons (light + dark variants)
│   ├── Profile_Icon.png / Profile_Icon_Dark.png
│   ├── Page_Icon.png / Page_Icon_Dark.png
│   ├── Book_Icon.png / Book_Icon_Dark.png
│   ├── Folder_Icon.png / Folder_Icon_Dark.png
│   ├── Message_Icon.png / Message_Icon_Dark.png
│   ├── Notepad_Icon.png / Notepad_Icon_Dark.png
│   ├── Link_Icon.png / Link_Icon_Dark.png
│   ├── CRT_Icon.png / CRT_Icon_Dark.png
│   ├── Kitty_Icon.png / Kitty_Icon_Dark.png
│   ├── Ping_Pong_Paddle_Icon.png / Pong_Paddle_dark_mode.png
│   ├── snake_icon.png.png / Snake_Icon_Dark_Mode.png.png
│   ├── Sun_Icon.png
│   └── Moon_Icon.png
└── portfolio/                        # Art and design work images
    ├── hills.png
    ├── Point_Line_Plane.png
    ├── image.png
    ├── image1.png
    ├── Jack drawings.png
    ├── Untitled_72.png
    ├── Untitled_76.png
    └── Untitled_Artwork.png
```

## Running Locally

Just open `index.html` in a browser — no build step, no server required.

```bash
# Or with a simple local server to avoid any asset path issues:
npx serve .
```

## Panels

| Icon | Panel | Description |
|------|-------|-------------|
| Profile | About Me | Bio, photo, skills |
| Page | Resume | Full resume with download link |
| Book | Projects | Coming soon |
| Folder | Portfolio | Art and design gallery |
| Message | Contact | Email, GitHub, LinkedIn |
| Kitty | More | Fun facts |
| Notepad | Notepad | Floating scratchpad (auto-saves to localStorage) |
| Paddle | Pong | Single-player pong vs CPU (desktop only) |
| Snake | Snake | Classic snake game (desktop only) |

## Games

Both games open as draggable windows and only one can be open at a time. Hidden on mobile.

**Pong**
- Left paddle is CPU-controlled
- `↑` / `↓` — move right paddle
- `Space` — start / pause

**Snake**
- Arrow keys or `WASD` — change direction
- `Space` — start / pause

## Taskbar

- **Link icon** — copies the page URL to clipboard
- **GitHub icon** — links to github.com/sshai404
- **Sun/Moon** — toggles light and dark mode
- **CRT icon** — toggles scanline overlay
- **Clock** — live time and day display

## Contact

- Email: sshaiera@gmail.com
- GitHub: [github.com/sshai404](https://github.com/sshai404)
