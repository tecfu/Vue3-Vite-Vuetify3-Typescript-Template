# Vue 3 + Typescript + Vite + Vuetify 3

Fork of https://github.com/peshanghiwa/Vue3-Vite-Vuetify3-Typescript-Template in order to demo Vuetify3 bug.

### To Reproduce:

```bash
npm install
npm run dev
```

### Reproduction Environment:

- vuetify     3.0.0-alpha.11",
- vue         3.2.6
- node        16.8.0
- npm         7.24.1
 
### Error:


```bash
error when starting dev server:
Error: The following dependencies are imported but could not be resolved:

  vuetify/lib/components (imported by myproject/src/plugins/vuetify.ts)
  vuetify/lib/directives (imported by myproject/src/plugins/vuetify.ts)

Are they installed?
    at optimizeDeps (myproject/node_modules/vite/dist/node/chunks/dep-972722fa.js:73454:15)
    at processTicksAndRejections (node:internal/process/task_queues:96:5)
    at async runOptimize (myproject/node_modules/vite/dist/node/chunks/dep-972722fa.js:74167:48)
    at async Server.httpServer.listen (myproject/node_modules/vite/dist/node/chunks/dep-972722fa.js:74183:21)
```
