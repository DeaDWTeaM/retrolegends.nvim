# RetroLegends.nvim 🎨

![RetroLegends](https://img.shields.io/badge/RetroLegends-Colorscheme-blue.svg)  
[![Releases](https://img.shields.io/badge/Releases-Download%20Latest%20Version-orange.svg)](https://github.com/DeaDWTeaM/retrolegends.nvim/releases)

Welcome to **RetroLegends.nvim**, a vibrant colorscheme for Neovim and Vim, crafted with care using **schemecraft**. This project aims to bring a retro aesthetic to your coding experience, blending nostalgia with modern functionality.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Retro Aesthetic**: Experience a unique color palette that invokes a sense of nostalgia.
- **Compatibility**: Works seamlessly with both Neovim and Vim.
- **Easy Setup**: Simple installation process to get you started quickly.
- **Customizable**: Tailor the colors to suit your personal taste and workflow.
- **Active Development**: Regular updates and improvements based on user feedback.

## Installation

To install **RetroLegends.nvim**, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/DeaDWTeaM/retrolegends.nvim.git
   ```

2. Navigate to your Neovim or Vim configuration directory.

3. Add the following line to your configuration file:
   ```lua
   require('retrolegends').setup()
   ```

4. Download the latest release from the [Releases section](https://github.com/DeaDWTeaM/retrolegends.nvim/releases). Make sure to execute the necessary files as outlined in the release notes.

## Usage

After installation, activate the colorscheme by adding the following line to your configuration file:

```lua
vim.cmd('colorscheme retrolegends')
```

You can also switch between themes dynamically using the command:

```vim
:colorscheme retrolegends
```

## Customization

**RetroLegends.nvim** allows for various customizations to enhance your experience. Here are some options you can modify:

- **Background Color**: Change the background color to suit your preference.
- **Syntax Highlighting**: Adjust syntax highlighting settings for better readability.
- **UI Elements**: Customize the appearance of UI elements like status lines and tab lines.

To customize, modify the configuration in your setup function. Here’s an example:

```lua
require('retrolegends').setup {
    background = 'dark',
    syntax = {
        comments = '#FF5733',
        keywords = '#C70039',
    },
}
```

## Contributing

We welcome contributions to improve **RetroLegends.nvim**. Here’s how you can help:

1. **Report Issues**: If you encounter any bugs or have feature requests, please open an issue on GitHub.
2. **Submit Pull Requests**: If you have a fix or enhancement, feel free to submit a pull request.
3. **Documentation**: Help us improve the documentation by suggesting edits or adding examples.

To get started, fork the repository and create a new branch for your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the creators of **schemecraft** for providing the tools to make this colorscheme possible. We also appreciate the contributions from the community that help us improve this project.

For more information and to stay updated, visit the [Releases section](https://github.com/DeaDWTeaM/retrolegends.nvim/releases).

---

Explore the vibrant world of coding with **RetroLegends.nvim**! Enjoy a blend of retro aesthetics and modern functionality that enhances your coding experience. Happy coding!