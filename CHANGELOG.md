## 2.0.1 (April 27th, 2023)

- [added](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/commit/769b31661d399141d0ab242485b7a33f3f513e1e) extends plugin:jsx-a11y to index configuration now that airbnb config is removed, fixing issue with missing
  rules from react-ally/aribnb config as mentioned [here](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/issues/52).

## 2.0.0 (April 25th, 2023)

- removed eslint conflig airbnb from the plugin so it is more directly aligned with eslint-plugin-jsx-a11y as requested
  [here](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/issues/18). Merged [here](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/pull/51).

## 0.1.0 (January 6th, 2023)

- added support for components defined with string syntax (`styled('div')` instead of `styled.div`) as requested
[here](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/issues/47). Added test cases for this syntax.
<!-- WE SEEM TO BE MISSING VERSION 1.0.0 and unintentionally published 0.1.0 after when it should have been 1.1.0 -->

## 0.0.40 (July 29, 2022)

- Re-added support for styled components defined within objects while fixing the
  [hang](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/issues/40). `jsx-ast-utils` needed
  to be upgraded to avoid an error with `ChainingExpressions`, but using the newer version of `jsx-ast-utils`
  may cause issues in some older environments.

## 0.0.40 (June 16, 2022)

- Reverted changes from 0.0.37, which were causing eslint to [hang](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/issues/40).

## 0.0.38, 0.0.39 (June 12, 2022)

- Changed the image links in the readme to externally hosted images so they are visible outside github on npm.

## 0.0.37 (June 2, 2022)

- Add support for styled components defined as objects. ([@pawelglosz](https://github.com/pawelglosz) in [#39](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y/pull/39))
