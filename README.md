## Create config

To configure Facebook, Stripe and OpenExchange create a ```server/config.json``` with the following format:
```{
  "facebookClientId": "791481230975326",
  "facebookClientSecret": "fe1275e6aa255bd31a4439474b69b78f",
  "stripeKey": "sk_test_AS3TKysspkcioahi3clmwkoq",
  "openExchangeRatesKey": "406c134e58ad47f2898d8207f9ee4a8b"
}```

## Install dependencies & setup

Run ```npm install``` on both project's root and server directories.
Also run ```gulp browserify``` on project's root directory.

## Run

Change to ```server``` directory and execute ```node index.js```.