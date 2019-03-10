Forked from https://github.com/ryhaberecht/MAKE-A-MERRY-TRY-AGAIN
Icon changed, otherwise same as original.

How to make and sign the add-on:

Install web-ext:

    npm install --global web-ext

    web-ext build

Sign up to be a Mozilla developer.

Create an API key.  Substitute your numbers in the following command:

    web-ext sign --api-key "user:12345678:410" --api-secret "1234567812345678123456781234567812345678123456781234567812345678"

