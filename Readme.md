# React Setup

1. Import `idea/watchers.xml` in `Settings/Tools/File Watchers`

```shell
yarn add prettier@latest
```

```js
{
    "scripts": {
            "format": "prettier --config .prettierrc --write 'src/**/*.js'",
        }
}
```


