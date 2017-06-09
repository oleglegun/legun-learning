# React Setup

1. Import `idea/watchers.xml` in `Settings/Tools/File Watchers`

```shell
yarn add prettier@latest

yarn add -D eslint eslint-config-react-app eslint-plugin-flowtype eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```

```json
{
    "scripts": {
            "format": "prettier --config .prettierrc --write 'src/**/*.js'"
        }
}
```


