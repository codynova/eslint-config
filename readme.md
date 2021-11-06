# @novas/eslint-config

ESLint config for ES2021 and TypeScript


## Installation

Install this module and its `peerDependencies`, then extend it in your `.eslintrc`:

```jsonc
// package.json
{
	"devDependencies": {
		"@novas/eslint-config": "latest",
		// peerDependencies
		"@babel/eslint-parser": "7.16.0",
		"@babel/eslint-plugin": "7.14.5",
		"@typescript-eslint/eslint-plugin": "5.3.0",
		"@typescript-eslint/parser": "5.3.0",
		"eslint": "8.2.0",
		"eslint-config-prettier": "8.3.0",
		"eslint-plugin-react": "7.26.1",
		"eslint-plugin-react-hooks": "4.2.0",
		"typescript": ">=4.4.4"
	}
}
```

```jsonc
// .eslintrc
{
	"extends": [ "@novas/eslint-config" ]
}
```
