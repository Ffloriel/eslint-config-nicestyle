# NiceStyle - Eslint config

A proposal of style and rules for javascript. This config is midly strict and you
can overwrite or add rule if you want.

## Install

```bash
npm install eslint-config-nicestyle
```

## Usage
In your eslintrc.js:
```js
{
    extends: "nicestyle",
    rules: {
        // you can overwrite rules here
    }
}
```
The package contains a `.eslintrc.json` file with all the rules so you can also
modify it to create your own eslint configuration.

## Config

### Possible Errors

| Rule                      | Error     | Options           |
| ------------------------- |:---------:| ----------------- |
| no-cond-assign            | error     | always            |
| no-console                | error     |                   |
| no-constant-condition     | error     |                   |
| no-control-regex          | error     |                   |
| no-debugger               | warn      |                   |
| no-dupe-args              | error     |                   |
| no-dupe-keys              | error     |                   |
| no-duplicate-case         | error     |                   |
| no-empty                  | error     |                   |
| no-empty-character-class  | error     |                   |
| no-ex-assign              | error     |                   |
| no-extra-boolean-cast     | error     |                   |
| no-extra-parens           | error     |                   |
| no-extra-semi             | error     |                   |
| no-func-assign            | error     |                   |
| no-inner-declarations     | error     |                   |
| no-invalid-regexp         | error     |                   |
| no-irregular-whitespace   | error     |                   |
| no-negated-in-lhs         | error     |                   |
| no-obj-calls              | error     |                   |
| no-prototype-builtins     | error     |                   |
| no-regex-spaces           | error     |                   |
| no-sparse-arrays          | error     |                   |
| no-unexpected-multiline   | error     |                   |
| no-unreachable            | error     |                   |
| no-unsafe-finally         | error     |                   |
| use-isnan                 | error     |                   |
| valid-jsdoc               | off       |                   |
| valid-typeof              | error     |                   |

### Best Practices

| Rule                          | Error     | Options           |
| -------------------------     |:---------:| ----------------- |
| accessor-pairs                | error     |                   |
| array-callback-return         | error     |                   |
| block-scoped-var              | error     |                   |
| complexity                    | error     | 30                |
| consistent-return             | error     |                   |
| curly                         | error     | all               |
| default-case                  | error     |                   |
| dot-location                  | off       |                   |
| dot-notation                  | error     |                   |
| eqeqeq                        | error     | always            |
| guard-for-in                  | warn      |                   |
| no-alert                      | error     |                   |
| no-caller                     | error     |                   |
| no-case-declarations          | error     |                   |
| no-div-regex                  | error     |                   |
| no-else-return                | error     |                   |
| no-empty-function             | error     |                   |
| no-empty-pattern              | error     |                   |
| no-eq-null                    | error     |                   |
| no-eval                       | error     |                   |
| no-extend-native              | error     |                   |
| no-extra-bind                 | error     |                   |
| no-extra-label                | error     |                   |
| no-fallthrough                | error     |                   |
| no-floating-decimal           | error     |                   |
| no-implicit-coercion          | error     |                   |
| no-implicit-globals           | error     |                   |
| no-implied-eval               | error     |                   |
| no-invalid-this               | error     |                   |
| no-iterator                   | error     |                   |
| no-labels                     | error     |                   |
| no-lone-blocks                | error     |                   |
| no-loop-func                  | error     |                   |
| no-magic-numbers              | off       |                   |
| no-multi-spaces               | error     |                   |
| no-multi-str                  | error     |                   |
| no-native-reassign            | error     |                   |
| no-new                        | error     |                   |
| no-new-func                   | error     |                   |
| no-new-wrappers               | error     |                   |
| no-octal                      | error     |                   |
| no-octal-escape               | error     |                   |
| no-param-reassign             | error     |                   |
| no-proto                      | error     |                   |
| no-redeclare                  | error     |                   |
| no-return-assign              | error     |                   |
| no-script-url                 | error     |                   |
| no-self-assign                | error     |                   |
| no-self-compare               | error     |                   |
| no-sequences                  | error     |                   |
| no-throw-literal              | error     |                   |
| no-unmodified-loop-condition  | error     |                   |
| no-unused-expressions         | error     |                   |
| no-unused-labels              | error     |                   |
| no-useless-call               | error     |                   |
| no-useless-concat             | error     |                   |
| no-useless-escape             | error     |                   |
| no-void                       | error     |                   |
| no-warning-comments           | warn      |                   |
| no-with                       | error     |                   |
| radix                         | error     |                   |
| vars-on-top                   | error     |                   |
| wrap-iife                     | error     |                   |
| yoda                          | error     | never             |

### Strict
| Rule                      | Error     | Options           |
| ------------------------- |:---------:| ----------------- |
| strict                    | off       | safe              |

### Variables

| Rule                      | Error     | Options           |
| ------------------------- |:---------:| ----------------- |
| init-declarations         | off       | never             |
| no-catch-shadow           | error     |                   |
| no-delete-var             | error     |                   |
| no-label-var              | error     |                   |
| no-restricted-globals     | error     |                   |
| no-shadow                 | error     |                   |
| no-shadow-restricted-names| error     |                   |
| no-undef                  | error     |                   |
| no-undef-init             | error     |                   |
| no-undefined              | error     |                   |
| no-unused-vars            | error     |                   |
| no-use-before-define      | error     |                   |

### Node.js and CommonJS

| Rule                      | Error     | Options           |
| ------------------------- |:---------:| ----------------- |
| callback-return           | error     |                   |
| global-require            | error     |                   |
| handle-callback-err       | error     |                   |
| no-mixed-requires         | error     |                   |
| no-new-require            | error     |                   |
| no-path-concat            | error     |                   |
| no-process-env            | error     |                   |
| no-process-exit           | error     |                   |
| no-restricted-modules     | error     |                   |
| no-sync                   | error     |                   |


### Stylistic Issues

| Rule                          | Error     | Options           |
| -------------------------     |:---------:| ----------------- |
| array-bracket-spacing         | error     | never             |
| block-spacing                 | error     | never             |
| brace-style                   | error     | 1tbs              |
| camelcase                     | error     |                   |
| comma-dangle                  | error     | never             |
| comma-spacing                 | error     | `{ "before": false, "after": true }`|
| comma-style                   | error     | last              |
| computed-property-spacing     | error     | never             |
| consistent-this               | error     |                   |
| eol-last                      | error     |                   |
| func-names                    | error     | always            |
| func-style                    | error     | expression        |
| id-blacklist                  | error     | err               |
| id-length                     | error     | `{"min": 1, "max": 30}`|
| id-match                      | error     | |
| indent                        | error     | |
| jsx-quotes                    | error     | |
| key-spacing                   | error     | |
| keyword-spacing               | error     | |
| linebreak-style               | error     | |
| lines-around-comment          | error     | |
| max-depth                     | error     | |
| max-len                       | error     | |
| max-lines                     | error     | |
| max-nested-callbacks          | error     | |
| max-params                    | error     | |
| max-statements                | error     | |
| max-statements-per-line       | error     | |
| new-cap                       | error     | |
| new-parens                    | error     | |
| newline-after-var             | error     | |
| newline-before-return         | error     | |
| newline-per-chained-call      | error     | |
| no-array-constructor          | error     | |
| no-bitwise                    | error     | |
| no-continue                   | error     | |
| no-inline-comments            | error     | |
| no-lonely-if                  | error     | |
| no-mixed-operators            | error     | |
| no-mixed-spaces-and-tabs      | error     | |
| no-multiple-empty-lines       | error     | |
| no-negated-condition          | error     | |
| no-nested-ternary             | error     | |
| no-new-object                 | error     | |
| no-plusplus                   | error     | |
| no-restricted-syntax          | error     | |
| no-spaced-func                | error     | |
| no-ternary                    | error     | |
| no-trailing-spaces            | error     | |
| no-underscore-dangle          | error     | |
| no-unneeded-ternary           | error     | |
| no-whitespace-before-property | error     | |
| object-curly-newline          | error     | |
| object-curly-spacing          | error     | |
| object-property-newline       | error     | |
| one-var                       | error     | |
| one-var-declaration-per-line  | error     | |
| operator-assignment           | error     | |
| operator-linebreak            | error     | |
| padded-blocks                 | error     | |
| quote-props                   | error     | |
| quotes                        | error     | |
| require-jsdoc                 | error     | |
| semi                          | error     | |
| semi-spacing                  | error     | |
| sort-vars                     | error     | |
| space-before-blocks           | error     | |
| space-before-function-paren   | error     | |
| space-in-parens               | error     | |
| space-infix-ops               | error     | |
| space-unary-ops               | error     | |
| spaced-comment                | error     | |
| unicode-bom                   | error     | |
| wrap-regex                    | error     | |

### ECMAScript 6

| Rule                      | Error     | Options           |
| ------------------------- |:---------:| ----------------- |
| arrow-body-style          | warn      | `"as-needed", { "requireReturnForObjectLiteral": true }`|
| arrow-parens              | error     | as-needed                                 |
| arrow-spacing             | error     | `{ "before": true, "after": true }`       |
| constructor-super         | error     |                                           |
| generator-star-spacing    | error     | `{"before": true, "after": true}`         |
| no-class-assign           | error     |                                           |
| no-confusing-arrow        | error     |                                           |
| no-const-assign           | error     |                                           |
| no-dupe-class-members     | error     |                                           |
| no-duplicate-imports      | error     |                                           |
| no-new-symbol             | error     |                                           |
| no-restricted-imports     | error     |                                           |
| no-this-before-super      | error     |                                           |
| no-useless-computed-key   | error     |                                           |
| no-useless-constructor    | error     |                                           |
| no-useless-rename         | error     |                                           |
| no-var                    | error     |                                           |
| object-shorthand          | error     |                                           |
| prefer-arrow-callback     | error     |                                           |
| prefer-const              | off       |                                           |
| prefer-reflect            | error     |                                           |
| prefer-rest-params        | error     |                                           |
| prefer-spread             | error     |                                           |
| prefer-template           | error     |                                           |
| require-yield             | error     |                                           |
| rest-spread-spacing       | error     | never                                     |
| sort-imports              | error     | `{"ignoreCase": false,"ignoreMemberSort": false,"memberSyntaxSortOrder": ["none", "all", "multiple", "single"]}`              |
| template-curly-spacing    | error     |                                           |
| yield-star-spacing        | error     | `{"before": true, "after": false}`        |
