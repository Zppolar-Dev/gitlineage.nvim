# 🎨 gitlineage.nvim - View Git History with Ease

## 📥 Download the Plugin
[![Download gitlineage.nvim](https://img.shields.io/badge/Download-gitlineage.nvim-brightgreen)](https://github.com/Zppolar-Dev/gitlineage.nvim/releases)

## 🚀 Getting Started
This guide will help you download and run the **gitlineage.nvim** plugin. This Neovim plugin allows you to view the git history of selected lines. It provides a simple way to see how code has changed through commits, enabling you to navigate between commits, copy SHAs, and open complete diffs with diffview.nvim.

## 🔗 Download & Install
To get started, you will need to download the plugin from the Releases page. 

1. Visit this page to download: [GitHub Releases for gitlineage.nvim](https://github.com/Zppolar-Dev/gitlineage.nvim/releases).
2. On the Releases page, scroll down to the latest version.
3. Look for the file that matches your system and click to download.

### 📦 Installation Steps
1. **Extract the Files:**
   After downloading, locate the zip file in your downloads folder and extract it.

2. **Move to Neovim's Plugin Directory:**
   - For Unix-based systems (Linux, macOS), move the extracted folder into `~/.config/nvim/pack/plugins/start/`.
   - For Windows, place it in `%APPDATA%/nvim/pack/plugins/start/`.

3. **Open Neovim:**
   Launch Neovim to load the plugin. The plugin will start automatically when you start using Neovim.

4. **Configure (if needed):**
   Check your Neovim configuration file (`init.vim` or `init.lua`) for any additional settings pertaining to the plugin.

### 📋 Features
- **View Git History:** Select lines in visual mode and see their history. Easily understand how your code evolved.
- **Navigate Commits:** Quickly move between different commits to track changes.
- **Yank SHAs:** Copy commit SHAs effortlessly for reference.
- **Open Full Diffs:** Optionally open complete diffs using diffview.nvim for a deeper dive.

## 🖥️ System Requirements
- **Neovim**: Version 0.5 or higher.
- **git**: Ensure that git is installed on your system to track the history effectively.
- **diffview.nvim**: If you want to view complete diffs, ensure you have diffview.nvim installed. 

## 📖 Usage Guide
1. **Selecting Lines:**
   - Enter visual mode in Neovim by pressing `v`.
   - Highlight the lines you want to inspect.

2. **Viewing History:**
   - With lines selected, invoke the plugin’s command (usually mapped to a key combination, check your configuration).
   - A window should pop up showing the commit history for the selected lines.

3. **Navigating Commits:**
   - Use the navigation controls to move through commits. Review how each commit altered the selected lines of code.

4. **Copying SHAs:**
   - If you need to reference a specific commit, you can copy the SHA directly from the plugin window.

5. **Opening Diffs:**
   - For detailed changes, click on the option to view full diffs (you may need diffview.nvim).

## ❓ Troubleshooting
If you encounter issues:
- Make sure Neovim is updated to above 0.5.
- Check if the plugin folder is correctly placed in the Neovim configuration directory.
- Verify that git is installed and accessible from the command line.

## 🌟 Additional Resources
- **Official Neovim Documentation:** Always a good place to learn more about Neovim commands and features.
- **GitHub Issues Page:** For help with the plugin or to report bugs, head to the [Issues page](https://github.com/Zppolar-Dev/gitlineage.nvim/issues).

## 📞 Support
If you have questions or need assistance, feel free to open an issue on the GitHub repository. The developer community is here to help you. 

[Download gitlineage.nvim again here](https://github.com/Zppolar-Dev/gitlineage.nvim/releases).