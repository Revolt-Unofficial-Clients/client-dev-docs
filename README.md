# Revolt Unofficial Clients Dev Docs

This repository is here to document standardization between unofficial clients. This includes settings keys, badges, functions, and more.

Most functions should use (or try to use) what revite uses. (for example themes, use the revite `appearance` settings key, don't make your own)

## Settings Keys

Usage:

```js
// this is just a revolt.js example, replace 'collapsed' and it's data with whatever you're using
client.syncSetSettings({ collapsed: ["01GE586H4GP9G5T97VEDQSS76B"] });
```

Aside from the default settings keys, here are additionals:

- `collapsed` - An array of (JSON-stringified) category IDs that are currently collapsed for the user. Example:
![image](https://user-images.githubusercontent.com/50887230/208010624-985329df-95a3-4472-830a-ed5204c149c3.png)
