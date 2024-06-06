# Vite x Svelte Boilerplate
![Fleek 2024 Rebrand Svelte Boilerplate](https://github.com/fleek-tools/svelte-template/assets/74613246/1dcd52a1-1615-4f6d-abf5-6328474f8a2f)



## 🚀 Project Structure

Inside of your Svelte project, you'll see the following folders and files:

```
/
├── public/
│   └── vite.svg
├── src/
│   └── assets/
│       ├── svelte.svg
|   └── lib/
│       ├── Counter.svelte
|   ├── app.css
|   ├── App.svelte
|   ├── main.js
|   ├── vite-env.d.ts
├── index.html
├── jsconfig.json
├── package.json
├── README.md
├── svelte.config.js
└── vite.config.js
```

Any static assets, like images, can be placed in the `public/` directory.

## ⚡ How to deploy to Fleek

### 1. Create a `fleek.config.json` config file:
You can configure this site deployment using [Fleek CLI]() and running:
```
 > fleek sites init
   WARN! Fleek CLI is in beta phase, use it under your own responsibility
   ? Choose one of the existing sites or create a new one. › 
   ❯ Create a new site
```
It will prompt you for a `name`, `dist` directory location & `build command`
- `name`: How you want to name the site
- `dist`: The output directory where the site is located, for this template it's `dist`
- `build command`: Command to build your site, this will be used to deploy the latest version either by CLI or Github Actions

### 2. Deploy the site
After configuiring your `fleek.config.json` file, you can deploy the site by running

```
fleek sites deploy
```
After running it you will get an output like this:
```
 WARN! Fleek CLI is in beta, use it at your own discretion
 > Success! Deployed!
 > Site IPFS CID: QmP1nDyoHqSrRabwUSrxRV3DJqiKH7b9t1tpLcr1NTkm1M

 > You can visit through the gateway:
 > https://ipfs.io/ipfs/QmP1nDyoHqSrRabwUSrxRV3DJqiKH7b9t1tpLcr1NTkm1M
 ```
