# Eslint and Styleguide configuration
  - `npm install eslint@4.x babel-eslint@8 eslint-plugin-react --save-dev`
  - `eslint --init`
  - Configuration: 
```js
// eslintrc.json
{
  "parser": "babel-eslint",
  "extends": ["eslint:recommended", "plugin:react/recommended"]
}
```
  - This [plugin](https://www.npmjs.com/package/eslint-plugin-react) exports a `recommended` configuration that enforces React good practices. 
  - See [ESLint documentation](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) for more information about extending configuration files.

The rules enabled in this configuration are:

* [react/display-name](docs/rules/display-name.md)
* [react/jsx-key](docs/rules/jsx-key.md)
* [react/jsx-no-comment-textnodes](docs/rules/jsx-no-comment-textnodes.md)
* [react/jsx-no-duplicate-props](docs/rules/jsx-no-duplicate-props.md)
* [react/jsx-no-target-blank](docs/rules/jsx-no-target-blank.md)
* [react/jsx-no-undef](docs/rules/jsx-no-undef.md)
* [react/jsx-uses-react](docs/rules/jsx-uses-react.md)
* [react/jsx-uses-vars](docs/rules/jsx-uses-vars.md)
* [react/no-children-prop](docs/rules/no-children-prop.md)
* [react/no-danger-with-children](docs/rules/no-danger-with-children.md)
* [react/no-deprecated](docs/rules/no-deprecated.md)
* [react/no-direct-mutation-state](docs/rules/no-direct-mutation-state.md)
* [react/no-find-dom-node](docs/rules/no-find-dom-node.md)
* [react/no-is-mounted](docs/rules/no-is-mounted.md)
* [react/no-render-return-value](docs/rules/no-render-return-value.md)
* [react/no-string-refs](docs/rules/no-string-refs.md)
* [react/no-unescaped-entities](docs/rules/no-unescaped-entities.md)
* [react/no-unknown-property](docs/rules/no-unknown-property.md)
* [react/prop-types](docs/rules/prop-types.md)
* [react/react-in-jsx-scope](docs/rules/react-in-jsx-scope.md)
* [react/require-render-return](docs/rules/require-render-return.md)
