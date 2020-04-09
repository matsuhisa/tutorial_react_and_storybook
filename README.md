# create-react-app と Storybook

## 手順

### 

```
npx create-react-app ./ --typescript
```

### 

```
yarn add -D @storybook/preset-create-react-app
```

### 

`./.storybook/main.js`

```javascript:./.storybook/main.js
module.exports = {
  addons: ['@storybook/preset-create-react-app'],
};
```