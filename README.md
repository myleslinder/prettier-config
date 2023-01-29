# Prettier Config

## In Package JSON

```json
{
	"prettier": "@myleslinder/prettier-config"
}
```

## With Overrides

```ts
module.exports = {
	...require("@myleslinder/prettier-config"),
	semi: false,
};
```
