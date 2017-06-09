# React Setup

1. Prettier
Import `idea/watchers.xml` in `Settings/Tools/File Watchers`

`yarn add -D prettier@latest`

```json
{
    "scripts": {
            "format": "prettier --config .prettierrc --write 'src/**/*.js'"
        }
}
```

2. ESLint

```bash
yarn add -D eslint \
            eslint-config-react-app \
            eslint-config-prettier \
            eslint-plugin-flowtype \
            eslint-plugin-react \
            eslint-plugin-import \
            eslint-plugin-jsx-a11y \
            eslint-plugin-prettier
```




