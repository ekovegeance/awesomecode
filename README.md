# Awesome Coding Setup

![img](https://github.com/ekovegeance/awesomecode/blob/main/awesome.png)

_A streamlined and developer-friendly configuration for macOS, designed to enhance productivity and coding efficiency._

This project provides a comprehensive guide for setting up your terminal and VSCode on macOS with powerful tools, themes, and extensions. Whether you're a beginner or an experienced developer, this setup will make your coding experience seamless, aesthetic, and highly optimized for modern workflows.

---

## Features

### Terminal [Warp](https://www.warp.dev/)
- Fully customizable with `.zshrc` configurations.
- Themes, plugins, and aliases to boost productivity.
- Compatible with iTerm2, Warp, or the default Terminal.app.

### Code editor vscode [Cursor AI](https://www.cursor.com/)
- Preconfigured `settings.json` for a polished development environment.
- Includes essential extensions for code formatting, Git, and language support.
- Optimized settings for a clean and efficient coding experience.

---

## How to Use

### For Terminal
1. Open your terminal (iTerm2, Warp, or Terminal.app).
2. Navigate to your home directory:
   ```bash
   cd ~
   ```
3. Open (or create) the `.zshrc` file:
   ```bash
   nano .zshrc
   ```
4. Copy the `.zshrc` content provided in this repository and paste it into the file.
5. Save the file (`Ctrl + O`, then press `Enter`, and `Ctrl + X` to exit).
6. Reload the configuration:
   ```bash
   source ~/.zshrc
   ```

**Optional:** Install additional tools mentioned in `.zshrc` (e.g., Oh My Zsh, Starship, etc.) for the best experience.

---

### Code editor
1. Open VSCode.
2. Navigate to `File > Preferences > Settings` (or press `Cmd + ,`).
3. Click the **Open Settings (JSON)** icon in the top-right corner.
4. Copy the `settings.json` content from this repository and paste it into the VSCode settings file.
5. Save the file and restart VSCode to apply the changes.

---

## Recommended Tools
- **Terminal Emulator:** [iTerm2](https://iterm2.com) or [Warp](https://www.warp.dev).
- **Font:** [Fira Code](https://github.com/tonsky/FiraCode) or [JetBrains Mono](https://www.jetbrains.com/lp/mono/).
- **Plugins:** [Oh My Zsh](https://ohmyz.sh).
- **VSCode Extensions:**
  - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

---

## Contributing
Feel free to submit issues or pull requests to improve this project. Suggestions and contributions are always welcome!

---

## License
This project is open-source and available under the [MIT License](LICENSE).
