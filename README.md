# ✦ Pixie

> **A tiny desktop companion that lives on your Linux system.**

Pixie is a small, animated desktop companion for **Linux** that watches your activity, gets sleepy, looks around your desktop, and occasionally demands some `nam nam`.

She doesn't do anything particularly useful.

That's the point. ♡

<p align="center">
  <img src="assets/pixie-preview.png" alt="Pixie preview" width="700">
</p>

---

## ✦ What is Pixie?

Pixie is a little creature that lives on your desktop.

She can:

* 👀 Look around and react to activity
* 💤 Fall asleep when you're away
* 👁️ Wake up when you start using your computer
* 🖥️ Notice terminal activity
* ↗️ Look toward active windows
* 🍖 Get hungry
* ♡ Become happy when you feed her
* :( Become sad when you ignore her for too long
* ✦ Randomly blink, look around and change expressions
* 📐 Scale naturally with the size of her window

Pixie is designed to feel less like an application and more like a tiny creature living inside your desktop.

---

## 🍖 Feed Pixie

Pixie has her own little command system.

For example:

```bash
sudo eat nam nam
```

Pixie receives the event and...

```text
        ◉     ◉
           ω

      NAM NAM!!
        ♡ ♡ ♡
```

The `sudo` is purely part of Pixie's command-line experience.

**Pixie does not need root privileges to run.**

---

## 💤 She Sleeps

Pixie isn't awake all the time.

If your computer is idle for a while, she may slowly fall asleep.

```text
        -     -
           ᴗ

          z Z
```

Open a terminal or interact with your desktop and she can wake up again.

```text
        ◉     ◉
           ω

       Good morning!
```

Human computers apparently need sleep too. Pixie has simply chosen to be more honest about it.

---

## 👀 She Notices Your Terminal

Pixie is not tied to the terminal she was launched from.

You can have Pixie running on your desktop:

```text
┌─────────────────────────────────────┐
│                                     │
│                  ◉       ◉          │
│                     ω               │
│                  Pixie              │
│                                     │
└─────────────────────────────────────┘
```

Then open another Kitty window:

```text
$ fastfetch
$ btop
$ sudo eat nam nam
```

Pixie can receive those events through local IPC and react independently.

---

## ✦ Features

| Feature                   | Status |
| ------------------------- | :----: |
| Animated eyes             |    ✅   |
| Blinking                  |    ✅   |
| Random expressions        |    ✅   |
| Sleep system              |    ✅   |
| Hunger system             |    ✅   |
| Happiness system          |    ✅   |
| CLI interaction           |    ✅   |
| Cross-terminal IPC        |    ✅   |
| Responsive window scaling |    ✅   |
| Hyprland integration      |   🚧   |
| Persistent state          |   🚧   |
| System-wide installation  |   🚧   |
| Arch package              |   🚧   |

> Pixie is currently under active development.
> Some features may change before the first stable release.

---

## 📐 Responsive by Design

Pixie shouldn't look like a tiny sticker trapped inside a giant window.

Her rendering automatically adapts to the available window size.

Small window:

```text
┌───────────────┐
│               │
│     ◉   ◉     │
│       ω       │
│               │
└───────────────┘
```

Large window:

```text
┌───────────────────────────────────────────────┐
│                                               │
│                                               │
│              ◉           ◉                    │
│                    ω                          │
│                                               │
│                                               │
└───────────────────────────────────────────────┘
```

No fixed tiny character sitting sadly in the middle of a huge empty window.

---

## 🖥️ Linux First

Pixie is being developed with Linux desktops in mind.

The primary development environment is:

* **CachyOS**
* **Arch Linux**
* **Hyprland**
* **Kitty**

Other Linux desktop environments may work, but Hyprland is currently the main target.

---

## 📦 Installation

### Releases

Pre-built releases will be published on the project's **GitHub Releases** page.

> 🚧 First release coming soon.

### From source

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/pixie.git
cd pixie
```

Then follow the build instructions in the project documentation.

---

## 🧪 Development

Pixie is intentionally designed to be easy to extend.

The architecture is split into several components:

```text
pixie/
├── pixie-daemon
├── pixie-ui
├── pixie-cli
├── assets/
├── animations/
├── PKGBUILD
└── README.md
```

The daemon handles Pixie's state and IPC.

The UI handles rendering and animations.

The CLI lets you interact with her from any terminal.

---

## ✦ Roadmap

### v0.1 — Little Creature

* [x] Basic Pixie
* [x] Eyes
* [x] Blinking
* [x] Basic emotions
* [x] CLI
* [x] Feeding
* [x] Sleeping

### v0.2 — She Notices You

* [ ] Terminal detection
* [ ] Active window detection
* [ ] Looking toward windows
* [ ] Better animations
* [ ] Persistent state

### v0.3 — System Companion

* [ ] Hyprland integration
* [ ] System events
* [ ] Music reactions
* [ ] More expressions
* [ ] More interactions

### v1.0 — Pixie

* [ ] Stable API
* [ ] Arch package
* [ ] Official repository
* [ ] Documentation
* [ ] Release builds
* [ ] Configuration system

---

## 📸 Screenshots

Because every open-source project needs screenshots dramatically larger than the actual application.

### Pixie

<p align="center">
  <img src="assets/screenshots/pixie-01.png" alt="Pixie on the desktop" width="800">
</p>

### Sleeping

<p align="center">
  <img src="assets/screenshots/pixie-sleeping.png" alt="Sleeping Pixie" width="800">
</p>

### Terminal Interaction

<p align="center">
  <img src="assets/screenshots/pixie-terminal.png" alt="Pixie reacting to a terminal" width="800">
</p>

---

## 🛠️ Tech Stack

Pixie is built with a focus on:

* Linux
* Local IPC
* Lightweight rendering
* Responsive UI
* Hyprland integration
* CLI tools
* Arch packaging

The goal is simple:

> **Small, fast, cute, and actually useful enough to justify existing.**

---

## 🤍 Contributing

Pixie is an open-source project.

Bug reports, ideas, animations, expressions and improvements are welcome.

If Pixie is hungry, however, please feed her first.

```bash
sudo eat nam nam
```

---

## 📜 License

Pixie is released under the **[LICENSE]** included in this repository.

---

<p align="center">

### ✦ Made with Linux, code and questionable amounts of `nam nam`. ✦

**Pixie isn't a tool.
She's a roommate.**

</p>
