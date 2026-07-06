# tmux tutor

**Learn tmux interactively -- like vimtutor, but for tmux.**

28 hands-on lessons that teach you tmux by having you actually use it. No
slides, no videos -- just your terminal, a tutor script, and live verification
that checks your work after every lesson.

<p align="center">
  <img src="docs/images/lesson-detach.png" alt="Lesson 2: Detach -- side-by-side view of the lesson text and terminal" width="700">
</p>

<p align="center">
  <img src="docs/images/verify-passed.png" alt="Verification passing with green checkmark" width="700">
</p>

## Features

- **28 interactive lessons** across two modules (basics + advanced)
- **Live verification** -- the tutor inspects your tmux state and confirms you did it right
- **No install required** beyond bash and tmux -- just clone and run
- **Progress saving** -- quit any time and resume where you left off
- **HTML reference companion** covering all 28 lessons plus a quick reference card

## Quick start

```bash
git clone https://github.com/alejandroerickson/tmuxtutor.git
cd tmuxtutor
./tmuxtutor
```

When you finish the basics, continue with:

```bash
./tmuxtutor-advanced
```

## Run without installing

Try it instantly -- no clone needed:

```bash
bash <(curl -sL https://raw.githubusercontent.com/alejandroerickson/tmuxtutor/main/tmuxtutor)
```

For the advanced module:

```bash
bash <(curl -sL https://raw.githubusercontent.com/alejandroerickson/tmuxtutor/main/tmuxtutor-advanced)
```

## How it works

Open two terminal windows (or tabs). In the first, run `./tmuxtutor`. The tutor
displays a lesson and tells you what to do. In the second terminal, execute the
tmux commands it asks for. When you think you have it right, press **[v]** in the
tutor to verify -- it checks your live tmux state and tells you whether you
passed.

<p align="center">
  <img src="docs/images/lesson-detach.png" alt="Two terminals side by side: lesson text on the right, tmux commands on the left" width="700">
</p>

## HTML reference companion

A self-contained reference covering all 28 lessons and a quick reference card is
available at **[alejandroerickson.com/tmuxtutor](https://alejandroerickson.com/tmuxtutor/)**.

<p align="center">
  <img src="docs/images/html-reference.png" alt="HTML reference companion showing sidebar navigation and lesson content" width="700">
</p>

## Screenshots

<p align="center">
  <img src="docs/images/capstone-lesson.png" alt="Lesson 14: Build a Workspace" width="600"><br>
  <em>Lesson 14 -- Build a Workspace (capstone)</em>
</p>

<p align="center">
  <img src="docs/images/completion-basics.png" alt="Basics completion screen" width="600"><br>
  <em>Completing the basics module</em>
</p>

<p align="center">
  <img src="docs/images/intro-advanced.png" alt="Advanced tutor intro screen" width="600"><br>
  <em>Advanced module introduction</em>
</p>

<p align="center">
  <img src="docs/images/lesson-move-panes.png" alt="Advanced Lesson 6: Move Panes Between Windows" width="600"><br>
  <em>Advanced Lesson 6 -- Move Panes Between Windows</em>
</p>

<p align="center">
  <img src="docs/images/lesson-tmux-conf.png" alt="Advanced Lesson 9: Edit tmux.conf" width="600"><br>
  <em>Advanced Lesson 9 -- Editing tmux.conf in a split view</em>
</p>

<p align="center">
  <img src="docs/images/lesson-ssh.png" alt="Advanced Lesson 13: SSH and tmux" width="600"><br>
  <em>Advanced Lesson 13 -- SSH and tmux</em>
</p>

<p align="center">
  <img src="docs/images/completion-advanced.png" alt="Advanced completion screen" width="600"><br>
  <em>Completing all 28 lessons</em>
</p>

## Requirements

- **bash**
- **tmux**

Install tmux if you don't have it:

```bash
# Ubuntu / Debian
sudo apt install tmux

# macOS (Homebrew)
brew install tmux

# Fedora
sudo dnf install tmux

# Arch
sudo pacman -S tmux
```

## License

[MIT](LICENSE)
