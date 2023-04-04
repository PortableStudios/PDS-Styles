# PDS Styles

For more details see the [PDS Docs site](https://pds-docs.netlify.app/).

## To do

- [ ] Print styles
- [ ] Layouts
- [ ] Themes

## Installation

### 1. Authenticate via NPM

To ensure you can install private Portable packages, login to our GitHub repo via NPM:

(This only has to be done once per computer, skip this step if you've already done this)

```shell
npm login --registry=https://npm.pkg.github.com
```

When prompted for "Username", enter your GitHub username.

When prompted for "Password", enter a "Personal Access Token".
To generate a token follow these instructions:

- In GitHub visit Settings > Developer settings > Personal access tokens
- Press "Generate new token"
- Name the new token "portable_npm_login" or something similar
- Select the "repo", "write:packages" and "read:packages" permissions

Finally, when prompted for "Email" enter your Portable email address.

### 2. Add `pds-styles` to your project

Create an `.npmrc` file in your project root with the following contents:

```txt
@portablestudios:registry=https://npm.pkg.github.com
```

Install `pds-styles` to your `package.json`:

```shell
npm install @portablestudios/pds-styles
# or
yarn add @portablestudios/pds-styles
# or
pnpm add @portablestudios/pds-styles
```

## Development

1. Fork
2. Clone
3. `pnpm install`
4. `pnpm start`
