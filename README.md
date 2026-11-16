# 73072 PRINTS

Local catalog for handmade 3D prints in Norman, OK. Cash on pickup. No cart processor.

Live: https://tomford200167-a11y.github.io/73072-prints/

## Door-to-door

1. Open `cards.html`
2. Print actual size on thick stock (Avery 8371 for the wallet cards)
3. Hand the 3.75×5 leave-behind. Do **not** put it in a mailbox (federal)

QR points at the live shop.

## Your number

In `index.html`, set:

```js
const PHONE = "4055551212";
```

Digits only. Then “Send this order” opens SMS with the ticket filled in. Until that is set, it copies the order to the clipboard.

## Photos later

Cards are type-first on purpose — no fake product shots. Drop real photos in when the canary print is done and we can swap the SKU letter for a picture.
