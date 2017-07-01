# How to convert JSON to a JavaScript object?

JavaScript syntax is slightly different from JSON. Sometimes you need to be able to convert JSON syntax to a JavaScript syntax which you would normally write by hand. I.e. not so many double quotes and, perhaps, you want to add trailing objects.

## Alternative # 1 CLI

Install a CLI tool [json-to-js](https://www.npmjs.com/package/json-to-js) by running `npm i -g json-to-js` and use it as follows: 

```
pbpaste | json-to-js | pbcopy

```

Copy your JSON to clipboard, run this snippet, it will put the JS object to your clipboard so that you can paste it immediately.

## Alternative # 2 Browser

Go online to [https://json-to-js.com/](https://json-to-js.com/) and convert your JSON there.

