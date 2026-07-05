# DP Tech Blog

A minimalist, static technology blog built with [Hugo](https://gohugo.io/) and the [Risotto](https://github.com/joeroe/risotto) theme. This repository contains the raw Markdown content and configuration for the site, which focuses on Phones, PCs/Laptops, Hardware/Softwarem, Photography anf tech overall.

The site is automatically compiled and deployed to GitHub Pages via continuous integration (CI/CD) using GitHub Actions.

## 🛠 Tech Stack
*   **Engine:** Hugo (Extended Version)
*   **Theme:** Risotto (base16-dark palette)
*   **Hosting:** GitHub Pages
*   **CI/CD:** GitHub Actions (`hugo.yaml`)
*   **Formatting:** Markdown (Content) & TOML (Configuration/Front Matter)

## 📦 Prerequisites
To run this project locally on macOS, you will need to install Git and the extended version of Hugo via Homebrew.

```bash
# Install Git and GitHub CLI
brew install git gh

# Install Hugo Extended (required for compiling certain theme assets)
brew install hugo
