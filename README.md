<h1 align="center">
   <img src="https://i.imgur.com/f6XUOJQ.png">
</h1>
<h1 align="center">
<img src="https://ik.imagekit.io/l4en7xyqq3/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67_u7F4RKLkz.png">
</h1>

## 📕 About

The App can manipulate products in the cart adding/removing your quantity.

<img src="https://media3.giphy.com/media/Wod2G0KHLl0d7P2gyy/giphy.gif">

## ⚡ Techs

* [React] - JavaScript library for building user interfaces.
* [AsyncStorage] - An asynchronous, unencrypted, persistent, key-value storage system for React Native.
* [ReactNavigation] - Made up of some core utilities and those are then used by navigators. 
* [Axios] - Promise based HTTP client for the browser and node.js
* [Typescript] - typed superset of JavaScript that compiles to plain JavaScript.
* [Styled-components] - Visual primitives for the component age.
* [Yarn] - package manager that doubles down as project manager.

## 💻 Installation

### Dependency

```sh

$ yarn

```

### Server

```sh

$ yarn json-server server.json -p 3333

```

## 🚀 Running goMarketPlace

```

$ yarn android or yarn ios
$ yarn start

```
run your AVD emulator


## If you want to see the unit testing 😊


```sh

$ yarn test

or

$ yarn test "pathfile/file.spec.tsx"

```
### what it expects

```

src/__tests__/hooks/cart.spec.tsx
  Cart Context
    📌 should be able to add products to the cart
    📌 should be able to increment quantity 
    📌 should be able to decrement quantity 
    📌 should load products from AsyncStorage 
    📌 should store products in AsyncStorage while adding, incrementing and decrementing 

src/__tests__/components/FloatingCart.tsx
  Dashboard
    📌 should be able to calculate the cart total 
    📌 should be able to show the total quantity of itens in the cart 
    📌 should be able to navigate to the cart 

src/__tests__/pages/App.spec.tsx
  Dashboard
    📌 should be able to list products
    📌 should be able to add item to cart 

src/__tests__/pages/Cart.spec.tsx
  Dashboard
    📌 should be able to list products on the cart 
    📌 should be able to calculate the cart total 
    📌 should be able to calculate the cart total 
    📌 should be able to increment product quantity on the cart 
    📌 should be able to decrement product quantity on the cart 


```



[react]: <https://reactjs.org/>
[AsyncStorage]: <https://github.com/react-native-community/async-storage>
[reactNavigation]: <https://reactnavigation.org/>
[axios]: <https://www.npmjs.com/package/axios>
[typescript]: <https://www.typescriptlang.org/>
[styled-components]: <npmjs.com/package/styled-components>
[Yarn]: <https://yarnpkg.com/>
[backend]: <https://github.com/willfeliz1/Desafio-database-upload>
