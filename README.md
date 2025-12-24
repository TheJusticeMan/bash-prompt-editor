# Bash Prompt Editor

> Generates prompt to customize the terminal for ya

![bash-prompt-editor-1](screencap-1.gif)

![bash-prompt-editor-2](screencap-2.gif)

## 🚀 Live Demo

This application is automatically deployed to GitHub Pages. Visit the live demo at:
https://thejusticeman.github.io/bash-prompt-editor/

## Development Checklist
- [x] Store commands
- [x] Reset button
- [x] Add custom input
- [x] Colors
- [x] Complete code store 
- [x] Layouting
- [x] Add copy button
- [ ] Refactoring

## Features Checklist
- [x] insert emoji
- [ ] git
- [ ] colorize ls
- [ ] description

## 💭 Contributing
If you're interested to work in improving the points above or if you have any idea, feel free to make a pull request! 🙏

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## 📦 Deployment

This project is configured to automatically deploy to GitHub Pages when changes are pushed to the `main` or `master` branch. The deployment is handled by a GitHub Actions workflow (`.github/workflows/deploy.yml`).

### Manual Deployment

If you need to deploy manually or want to enable GitHub Pages for your fork:

1. Ensure GitHub Pages is enabled in your repository settings:
   - Go to Settings > Pages
   - Under "Build and deployment", select "GitHub Actions" as the source

2. Push to the `main` or `master` branch, or trigger the workflow manually:
   - Go to Actions tab > Deploy to GitHub Pages > Run workflow

The workflow will automatically build the project and deploy the `dist` folder to GitHub Pages.
