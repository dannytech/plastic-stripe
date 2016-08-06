# plastic-stripe

Stripe provider for PlasticJS

## Dependencies

* [plasticjs](https://github.com/dannytech/plasticjs)

## Install

```
$ npm install plastic-stripe
```

## Usage

With [Express](http://expressjs.com):

```javascript
var stripe = require("plastic-stripe").Provider;

plastic.use("stripe", stripe(options));
// Or
app.get("/stripe", stripe(options).Checkout);
```

#### Options

* `apiPublishable` - Required, Stripe Publishable Key
* `apiSecret` - Required, Stripe Secret Key