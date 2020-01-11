# [4.1.0](https://github.com/phalcon/cphalcon/releases/tag/v4.1.0) (xxx-xx-xx)
## Added
- Added JWT (JSON Web Tokens) support under `Phalcon\Http\JWT`. Offers support for:
  - Token
  - Parser
  - Builder
  - Validator
  - Signers (None, HMAC)
  - Base64 encode/decodeUrl helper class
[#13856](https://github.com/phalcon/cphalcon/issues/13856)
- Added additional HTML helpers under `Phalcon\Html\Helper`: `Anchor`, `Base`, `Body`, `Button`, `Close`, `Element`, `Form`, `Img`, `Input\Color`, `Input\Date`, `Input\DateTime`, `Input\DateTimeLocal`, `Input\Email`, `Input\File`, `Input\Hidden`, `Input\Image`, `Input\Input`, `Input\Month`, `Input\Numeric`, `Input\Password`, `Input\Range`, `Input\Select`, `Input\Search`, `Input\Submit`, `Input\Tel`, `Input\Text`, `Input\Textarea`, `Input\Time`, `Input\Url`, `Input\Week`, `Label`, `Link`, `Meta`, `Ol`, `Script`, `Style`, `Title`, `Ul` 
[#14696](https://github.com/phalcon/cphalcon/issues/14696)

## Changed
- Added service checks for the session. Now cookies will be saved in the session only when the `session` service is defined [#11770](https://github.com/phalcon/cphalcon/issues/11770), [#14649](https://github.com/phalcon/cphalcon/pull/14649)

## Fixed
- Fixed `Phalcon\Db\Dialect\Mysql::getColumnDefinition` to recognize `size` for `DATETIME`, `TIME` and `TIMESTAMP` columns [#13297](https://github.com/phalcon/cphalcon/issues/13297)
