# Nuxt3 Electron Template
A complete and ready to use template for Nuxt3 and Electron.

The template includes the following features and technologies, all ready to use:
- [TailwindCss](https://tailwindcss.com/)
- [vueuse](https://vueuse.org/nuxt/README.html)
- Packing with [Electron Builder](https://www.electron.build/)
- [Nuxt3](https://v3.nuxtjs.org/)
- [Electron](https://www.electronjs.org/)
- [Vue3](https://v3.vuejs.org/)
- Custom App icon
- Auto updater
- Build on Github actions



## How to use


### Build and pack
```bash
npm install

# for development
npm run dev

#build and pack app
#For windows users: run as administrator
npm run build
```

### Customize
- Change the app icon: replace the `icon.png` file in the `ressources` folder.
- Replace `appId` in `electron-builder.json5` file
- Change the app name in `package.json` file
- Replace repository url in `package.json` file to your private or public repository 
(You can create a private repository on Github just for the releases)
- Create a github new token with repo permission and export as `GH_TOKEN` in your environment variables
