This repository is meant to be used for the development of ebu-list-sdk.
It includes dependencies that are linked using lerna.

# Boostrapping

If `yarn` is not installed:
```
sudo npm i --global yarn
```

Bootstrap project:

```
yarn install
npx lerna bootstrap
```

# Building

```
npx lerna run build
```


# Running demos

```
npx lerna run start -- -- login --baseUrl https://list.ebu.io --username demo --password demo
```

(note the double `'--'`)