# stylelint-plugin-styled-components

A [Stylelint] plugin for the styled-components Library

## Installation

```sh
npm install --save-dev stylelint-plugin-styled-components 
```

## Configuration

```json
{
  "plugins": [""]
}
```

And then, in the rules:

```json
{
  "rules": {
    }
}
```

## Usage



## Configuration



## Purpose of Rules 

### plugin/styled-components-enforce-ampersand
- when updating the styled-components from v5 to v6 there are a breaking changes.

![image](https://github.com/ArkadiK94/stylelint-plugin-styled-components/assets/76536506/d27aa215-3d19-433d-aa95-a15669b2594d)
Source: https://styled-components.com/docs/faqs#what-do-i-need-to-do-to-migrate-to-v6

The problem is that you will not notice any error on the console when updating to v6. However, the styles will not work as you expected.

This rule helps to find all pseudo elements and toast an error in console if this pseudo element does't have ampersand.



LICENSE - [MIT]

[stylelint]: https://github.com/stylelint/stylelint/

