## Spicetify Colorful Theme

A vibrant and customizable Spicetify theme that lets you inject personality into your Spotify experience.

### Features

- **Variety of Schemes:** Explore multiple color schemes to suit your mood or style:

  - `base` (default)
  - `beach-sunset`
  - `biscuit`
  - `blue-dark`
  - `blue-light`
  - `catppuccin-frappe`
  - `catppuccin-latte`
  - `catppuccin-macchiato`
  - `catppuccin-mocha`
  - `dark`
  - `dracula`
  - `gray-dark`
  - `gray-light`
  - `green-dark`
  - `green-light`
  - `greenland`
  - `gruvbox`
  - `gruvbox-material-dark`
  - `lunar`
  - `midnight-catppuccin`
  - `nord-dark`
  - `nord-light`
  - `orange-dark`
  - `orange-light`
  - `purple`
  - `purple-dark`
  - `purple-light`
  - `red-dark`
  - `red-light`
  - `rose-pine`
  - `rose-pine-dawn`
  - `rose-pine-moon`
  - `samurai`
  - `tokyo-night`
  - `white`

- **Easy Installation:** Install via scripts or the Spicetify Marketplace.
- **Community Support:** Report issues on GitHub.

### Installation

#### Manual installation using Scripts (recommended):

**Windows (Powershell)**

```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
iex "& { $(iwr -useb 'https://sanoojes.github.io/spicetify-colorful/install/install.ps1') }"
```

**Linux/macOS (Bash)**

```bash
curl -fsSL https://raw.githubusercontent.com/sanoojes/spicetify-colorful/main/install/install.sh | sh
```

#### Using Spicetify Marketplace (simpler installation):

1. Install the `spicetify-marketplace` extension following its instructions: [https://github.com/spicetify/spicetify-themes](https://github.com/spicetify/spicetify-themes).
2. Search for "colorful" in the Spicetify Marketplace and click "Install."

#### Advanced Manual Installation:

1. **Download the repository:** Visit the Colorful GitHub repository: [https://github.com/sanoojes/spicetify-colorful](https://github.com/sanoojes/spicetify-colorful) and download the code as a ZIP archive.
2. **Locate Spicetify's Themes directory:** Use the command `spicetify path userdata` in your terminal/command prompt to find the path.
3. **Create the theme folder:** Inside the Themes directory, create a new folder named `colorful`.
4. **Extract theme files:** Extract the downloaded ZIP archive and move all files from the `src` subfolder to the `colorful` folder you created.
5. **Apply the theme:** Open your terminal/command prompt and run these commands (replace `<color_scheme>` with your desired scheme):

   ```bash
   spicetify config current_theme colorful
   spicetify config color_scheme <color_scheme>  # Example: dark, white, etc.
   spicetify config inject_css 1 replace_colors 1 overwrite_assets 1 inject_theme_js 1
   spicetify apply
   ```

### Customization

### Colors List

`base`, `white`, `dark`, `dracula`, `nord-light`, `nord-dark`, `purple`, `samurai`, `beach-sunset`, `gruvbox`, `gruvbox-material-dark`, `rosepine`, `lunar`, `catppuccin-latte`, `catppuccin-frappe`, `catppuccin-macchiato`, `catppuccin-mocha`, `blue-dark`, `blue-light`, `gray-dark`, `gray-light`, `green-dark`, `green-light`, `orange-dark`, `orange-light`, `purple-dark`, `purple-light`, `red-dark`, `red-light`, `rose-pine`, `rose-pine-moon`, `rose-pine-dawn`, `tokyo-night`

### Color scheme:

- The default scheme is `base`. You can change it using the command:

  ```bash
  spicetify config color_scheme <color_scheme>
  spicetify apply
  ```

- If you installed via Marketplace, the color scheme can be changed directly in the theme options.

### Community Support

- **GitHub Issues:** [https://github.com/sanoojes/spicetify-colorful/issues](https://github.com/sanoojes/spicetify-colorful/issues)

### License

[MIT License](LICENSE); colors are taken from different spicetify themes. All rights reserved to their original owners.

<details> 
  <summary></summary> 
  Readme is ai generated
</details>

