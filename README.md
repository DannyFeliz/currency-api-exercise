### Setup

```bash
git clone --single-branch --branch vue https://github.com/DannyFeliz/currency-api-exercise.git && cd currency-api-exercise && npm install && npm run serve
```

#### Create a component that consumes a currency exchange API based on a currency selected in a Dropdown.

#### Resources:

Currency Exchange API:

```js
https://v6.exchangerate-api.com/v6/72179b357c84d84fcb2c1f3d/latest/{CURRENCY_CODE}
```

<hr>

```js
// App.vue
```

- Create a dropdown with the currencies EUR, USD, BRL, PEN, and ARS (put USD by default)
- Every time the dropdown value changes, the currency exchange API should hit the API again.

<hr>

```js
// ExchangeRates.vue
```

- Fetch the exchange rates based on the given currency and display them using a list with the following format

currency_code: value

##### e.g.

```json
USD: 1.1745
CAD: 1.3331
```

- If the request is loading, you should display **"Loading..."**.
- Omit the current selected currency from the list.

<hr>

# currency-api-exercise

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```
