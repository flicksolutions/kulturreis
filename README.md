- To enable syncing with the template change the Workflow permissions here: https://github.com/<gh-user>/<repo>/settings/actions
- Go live in setting the ENV-Variable PUBLIC_DEVMODE to false in this file: /.github/workflows/main.yml (That's for search-engines)

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.
