# How to install

# NPM or Yarn

```bash
npx install-peerdeps --dev eslint-config-pitops // add --yarn if using yarn
```

## Monorepo (lerna & yarn)

If you are in a monorepo then the procedure is a bit different.

```bash
npx install-peerdeps --dev eslint-config-pitops --extra-args -W // add --yarn if using yarn
```

# Usage

This package is broken down into submodules. Right now there are two sub-modules out of the box, one for **React** and one for **Node**

## Use using the following

```javascript
// .eslintrc.js

module.exports = {
    extends: [
        "pitops/react" // or "pitops/node"
    ]
}
```

# Contributions

Are always welcome.
