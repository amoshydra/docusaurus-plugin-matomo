#  Matomo plugin for Docusaurus.

npm install --save docusaurus-plugin-matomo

## Configuration

docusaurus.config.js
```
module.exports = {
  plugins: [
    'docusaurus-plugin-matomo',
  ],
  themeConfig: {
    matomo: {
      matomoUrl: 'https://your.matomo.instance/',
      siteId: 'ID',
    },
  },
};
```

const path = require('path');

      // path.resolve(__dirname, 'plugins/docusaurus-plugin-matomo')
