# sing-box-builder

This repository contains GitHub Actions workflows to automate the building of [sing-box](https://github.com/sagernet/sing-box) for **Linux** and **Windows**. It supports multiple build configurations, including:

- **Default builds**: Built with the default feature set (default tags).
- **All builds**: Built with all features enabled (all tags).
- **CGO builds**: Built with CGO either enabled or disabled.

## How to Use

1. **Fork this repository**: Click the "Fork" button at the top-right to create your own copy.
2. **Navigate to the Actions tab**: In your forked repo, go to the "Actions" tab.
3. **Select the workflow**: Choose **"Build and Release sing-box"**.
4. **Run the workflow**:
   - Click **"Run workflow"**.
   - Enter the desired `sing-box` version (e.g., `v1.11.4`) in the input field.
   - Click the green **"Run workflow"** button to start the build.
5. **Download the binaries**: Once the workflow completes, find the built binaries in the **"Releases"** section of your forked repository.

You can also download pre-built binaries directly from the [Releases](https://github.com/bI4ckb34rd/sing-box-builder/releases) section of this repository.

## Contributing

Have an idea to make this better? Feel free to:
- Open a **Pull Request (PR)** with your improvements.
- Share feedback or report issues in the **Issues** tab.

## Support This Project

If you find this tool helpful, consider supporting it with a donation!  
<a href="https://github.com/bI4ckb34rd/donate/blob/main/README.md" alt="Donate shield">  
  <img src="https://img.shields.io/badge/-Donate-red?logo=undertale" />  
</a>

---
*Note*: This repo was crafted with a little help from AI to make it clear and user-friendly!

Happy building!
