# Pass Designer Sample Passes

This repository contains six sample Wallet pass JSON bundles for the macOS 27 app **Pass Designer**.

The samples are intentionally unsigned design fixtures. To turn one into a distributable `.pkpass`, add the required image assets, generate a manifest, sign it with your Pass Type ID certificate, and zip the bundle contents.

## Samples

- `Samples/BoardingPass.pass` - flight boarding pass
- `Samples/Coupon.pass` - retail discount coupon
- `Samples/Generic.pass` - appointment/check-in generic pass
- `Samples/StoreCard.pass` - loyalty store card
- `Samples/Event.pass` - concert/event ticket
- `Samples/PosterGeneric.pass` - poster-style generic media pass

## Placeholder Identifiers

Each `pass.json` uses placeholder values:

- `passTypeIdentifier`: `pass.com.passdesigner.sample`
- `teamIdentifier`: `ABCDE12345`
- `organizationName`: `Pass Designer`

Replace those values before signing or distributing real passes.

