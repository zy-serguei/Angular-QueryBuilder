Angular2-QueryBuilder Changelog
===============

Version 0.3.0
-----------
- Breaking: Renamed `changeField` callback to `onChange` for `queryField` directive.
- Add `onChange` callback to `queryEntity`, `queryInput`, `queryOperator`, `queryInput` for proper reactive form validation and touched behavior on custom components
- Add proper touched behavior to reactive form usage (See #49)
- Add entity mode (See #22)
- Fix `[value]` unrecognized property binding
- Fix QueryBuilderClassNames not being exported as interface
- Fix `in` operator causing multi-select to be displayed for all types (only limited to `category`, `boolean` now)
- Minor tweaks to CSS styling of default component

Version 0.2.5
-----------
- Fix root remove ruleset button showing
- Fix default value bug where only the first character of the operator is shown
- Fix inability to override multiselect operators (is in, is not in)

Version 0.2.4
-----------
- Fix serious issue with validation causing `ngModel` value to be wrong
- New `QueryBuilderClassNames` interface
- Rewrite CSS for more extensible CSS classes
- New bootstrap 4 example

Version 0.2.3
-----------
- Fix IE11 not working (target ES5)
- Fix invalid/valid state
- New validator function on `Field` config
