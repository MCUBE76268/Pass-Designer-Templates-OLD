# Pass Designer Sample Passes

This repository contains six sample Wallet pass templates for the macOS 27 app **Pass Designer**.

Open the files in `Templates/` from Pass Designer. The older `Samples/` folders are plain `.pass` JSON bundles for Pass Builder/signing experiments, but Pass Designer expects `.pkpasstemplate` files.

The templates are intentionally unsigned design fixtures. To turn one into a distributable `.pkpass`, add the required image assets, generate a manifest, sign it with your Pass Type ID certificate, and zip the bundle contents.

## Samples

- `Templates/BoardingPass.pkpasstemplate` - flight boarding pass
- `Templates/Coupon.pkpasstemplate` - retail discount coupon
- `Templates/Generic.pkpasstemplate` - appointment/check-in generic pass
- `Templates/StoreCard.pkpasstemplate` - loyalty store card
- `Templates/Event.pkpasstemplate` - concert/event ticket
- `Templates/PosterGeneric.pkpasstemplate` - poster-style generic media pass

## Placeholder Identifiers

Each `pass.json` uses placeholder values:

- `passTypeIdentifier`: `pass.com.passdesigner.sample`
- `teamIdentifier`: `ABCDE12345`
- `organizationName`: `Pass Designer`

Replace those values before signing or distributing real passes.

