# Sveltekit Pocketbase 

## Features
1. [Sveltekit](https://kit.svelte.dev/)
2. [UnoCSS](https://github.com/unocss/unocss)
    - With preset [DaisyUI](https://daisyui.com/) [UnoCSS-preset](https://github.com/kidonng/unocss-preset-daisy)
    - [Scoped Css](https://github.com/unocss/unocss/tree/main/examples/sveltekit-scoped)
3. [Pocketbase](https://pocketbase.io/)
    - Auth with email/username and password
    - Oauth2 with google
    - Realtime updates ([Please contact me if you face this issue](https://github.com/pocketbase/pocketbase/discussions/1515#discussioncomment-4622221))
4. Typescript, Pnpm, EsLint, Prettier

## Run frontend

```bash
pnpm install
pnpm run dev
```

## Run backend Windows

```bash
./pocketbase-w/pocketbase serve
```

## Run backend Linux
```bash
./pocketbase-l/pocketbase serve
```

Admin DB credentials 
    Email:      test@user.com
    Password:   password00


Add google Auth2 client ID and Api key in pocketbase admin ui to activate google authentication
https://developers.google.com/identity/protocols/oauth2