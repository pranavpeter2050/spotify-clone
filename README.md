# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).


## Commands

```bash
npm create vite@latest spotify-clone -- --template vue
```

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

```bash
npm install pinia-plugin-persistedstate uniqolor vue-material-design-icons
```

[Pinia](https://youtu.be/ZzuqwqP1wAQ?t=1855) is used to manage state so that the Library page and the Music player are always synchronised.

## Known Bugs

- The Total time of Song is not display on the right side of Track-seeker when a song is loaded for the first time.
- The Volume resets to 80% when song is changed, although the Volume-slider shows the same level in volume (eg. 40%)
- When clicking towards end of the song through the song-seeker, shows error like below in console.
    ```console
    Uncaught TypeError: Failed to set the 'currentTime' property on 'HTMLMediaElement': The provided double value is non-finite.
    at HTMLInputElement.<anonymous> (MusicPlayer.vue:35:28)
    ```

## References

- [Vite JS Guide](https://vitejs.dev/guide/#scaffolding-your-first-vite-project)
- [Install Tailwind CSS with Vite](https://tailwindcss.com/docs/guides/vite#vue)
- [Pinia Installation](https://pinia.vuejs.org/getting-started.html)
- [pinia-plugin-persistedstate](https://www.npmjs.com/package/pinia-plugin-persistedstate)