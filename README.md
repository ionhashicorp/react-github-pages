# react-github-pages

```console
#
# Create React template: https://vite.dev/guide/#scaffolding-your-first-vite-project
#
npm create vite@latest

#
# GitHub pages with GitHub Actions: https://vite.dev/guide/static-deploy.html#github-pages
#

#
# Examle of config.vite.js
#
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

// https://vite.dev/config/
export default defineConfig({
  ...
  base: '/react-github-pages/',
  ...
})

#
# Add homepage to package.json
#
  "homepage": "https://ionhashicorp.github.io/react-github-pages/",

#
# GitHub permissions: https://github.com/ionhashicorp/react-github-pages/settings/actions
#
Workflow permissions > Read and write permissions

#
# Add basename package.json
#
  "homepage": "https://ionhashicorp.github.io/react-github-pages/",
```