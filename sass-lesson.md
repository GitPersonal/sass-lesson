# Sass

1. open terminal or hyper.
2. cd into projects folder
3. type `mmkdir` and `project_name`
4. type `mmkdir` and `dist`
5. cd into `dist` folder
6. type `touch` and `file_name`
7. next, type `code .` to open in VS code.
8. for the first time install `Live Sass Compiler` extension.
9. Click the settings gear bottom left corner
10. Search sass
11. Click `Live Sass Compile` under `Autoprefix` section click on `Edit in settings.json`
12. type the following in between the `{}`

```javascript
"liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/dist/css"
    }
  ],
  "liveSassCompile.settings.generateMap": false,
```

13. Go to the Sass file and at the bottom bar click `Watch Sass` and then test the sass file.
14. run `Live Server`
15. Option use `fontawesome.com` and select `start using free`
