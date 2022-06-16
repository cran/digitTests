# digitTests 0.1.2

**Minor changes**

- Resolved CRAN note `Warning: <img> attribute "align" not allowed for HTML5`.

# digitTests 0.1.1

**Bug fixes**

- Throw a warning in `rv.test()` when there is zero variance in either the decimal portions of the number or its integer portions.

# digitTests 0.1.0

**New features**

- This is `digitTests` version `0.1.0` with functions `distr.test()`, `distr.btest()` (test first, first two, or last digits against a reference, i.e. benford or uniform, distribution) and `rv.test()` (test if data contain an excessive amount of repeated values).