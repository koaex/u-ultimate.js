<a name="1.0.1"></a>
# 1.0.1 mutually-supporting (2021-12-07)

## Bug Fixes
- **$sanitize:** do not trigger CSP alert/report in Firefox and Chrome
  ([c21b5e37](https://github.com/clancytom/u-ultimate.js/commit/c21b5e37f2f5e80e3b1dca439dd8fbc495f41dc0))

## Refactorings

- **SanitizeUriProvider:** remove usages of whitelist
  ([57c8eb1e3](https://github.com/clancytom/u-ultimate.js/commit/57c8eb1e37695bce3bb1b1e0e3f907d4d027dedc))
- **httpProvider:** remove usages of whitelist and blacklist
  ([074f56eb](https://github.com/clancytom/u-ultimate.js/commit/074f56eb22847d8f34eee8ba9e22894456e5b521))
- **sceDelegateProvider:** remove usages of whitelist and blacklist
  ([81ffe0be](https://github.com/clancytom/u-ultimate.js/commit/81ffe0bece6e7e652cd209708ca509ed5880d3ef))

## Deprecation Notices

- Deprecated ~~`aHrefSanitizationWhitelist`~~. It is now `aHrefSanitizationTrustedUri`
- Deprecated ~~`imgSrcSanitizationWhitelist`~~. It is now `imgSrcSanitizationTrustedUri`
- Deprecated ~~`xsrfWhitelistedOrigins`~~. It is now `xsrfTrustedOrigins`
- Deprecated ~~`resourceUrlWhitelist`~~. It is now `trustedResourceUrlList`
- Deprecated ~~`resourceUrlBlacklist`~~. It is now `bannedResourceUrlList`

For the purposes of backward compatibility, the previous symbols are aliased to their new symbol.


<a name="1.0.0"></a>
# 1.0.0 nested-vaccination (2021-17-07)

## Bug Fixes

## Breaking Changes
