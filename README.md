# Dig Ag React App

To build the app:

```
npm run build
```

And then, to deploy:

```
firebase deploy
```

## Libraries In Use

As of now, we use a few libraries to make development easier.

[Firebase](https://firebase.google.com/docs/hosting) is used to deploy the application to our domain name https://ewb-dig-ag.org.

[React Bootstrap](https://react-bootstrap.github.io/getting-started/introduction/) provides us with some basic components to maintain consistent style.

## Suggested VSCode Extensions

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets)
- [Emmet HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

You Can add these settings to your `settings.json` to ensure the Prettier formatting and Emmet snippets work correctly:

```
"editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.formatOnSave": true,
  "emmet.includeLanguages": {
    "javascript": "html"
  }
```
