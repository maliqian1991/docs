# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`


### anchor 移除
  // "anchors": [
  //   {
  //     "name": "Documentation",
  //     "icon": "book-open-cover",
  //     "url": "https://mintlify.com/docs"
  //   },
  //   {
  //     "name": "Community",
  //     "icon": "slack",
  //     "url": "https://mintlify.com/community"
  //   },
  //   {
  //     "name": "Blog",
  //     "icon": "newspaper",
  //     "url": "https://mintlify.com/blog"
  //   }
  // ],
multi user edit


{
  "group": "Essentials",
  "pages": [
    "essentials/markdown",
    "essentials/code",
    "essentials/images",
    "essentials/settings",
    "essentials/navigation",
    "essentials/reusable-snippets"
  ]
},