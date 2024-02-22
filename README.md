
Custom Neovim Configuration
This repository contains my personal Neovim configuration, built on top of Astronvim. Feel free to utilize this setup to enhance your own Neovim experience.

Why Neovim?
Neovim offers a powerful editing experience, combining the efficiency of Vim with modern features and extensibility. Its key advantages include:

Efficient Editing: Vim's modal editing and keyboard-driven commands make editing fast and efficient.
Extensibility: Neovim's plugin ecosystem allows for extensive customization and enhancement of features.
Lightweight: Neovim is lightweight and can run on various platforms without significant resource usage.
While Neovim may not be suitable for everyone, its unique features and flexibility make it a compelling choice for many developers.

Requirements
Before using this configuration, ensure your system meets the following requirements:

Compiler: A compiler is needed for certain plugins and features.
Ripgrep: Recommended for fuzzy finder support.
Installation
Follow these steps to install the configuration:

Linux
bash
Copy code
git clone https://github.com/wmeints/astronvim-config ~/.config/nvim/lua/user
nvim
Windows
powershell
Copy code
git clone https://github.com/wmeints/astronvim-config $env:LOCALAPPDATA/nvim/lua/user
nvim
Additional Setup
Plugins and Features
Treesitter Configuration: Enhanced code highlighting for various languages.
Omnisharp Configuration: Support for C# development with Omnisharp.
REST Client: Test HTTP services directly from Neovim.
Copilot Plugin: AI-powered code suggestions and assistance.
Additional Language Support: Including Golang, HTML/CSS, JSON, Python, Svelte, TailwindCSS, and more.
Usage
Refer to the plugin documentation and keybindings provided in the configuration files to utilize the features effectively.

Feedback and Contributions
Feedback and contributions are welcome! Feel free to submit pull requests or open issues on the GitHub repository.
