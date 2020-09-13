Create-react-app changes address to the static files according to the "homepage" attribute in package.json
So we need to delete that.

(Here's why)[https://stackoverflow.com/questions/59271816/react-build-with-gh-pages-generates-wrong-file-path-to-static-files]
```json
  "homepage": "https://caveayurveda.github.io/deploy-react"
```

Also, We need to use HashRouter with a 'base' property instead of BrowserRouter
(Here's why)[https://medium.com/@bennirus/deploying-a-create-react-app-with-routing-to-github-pages-f386b6ce84c2]