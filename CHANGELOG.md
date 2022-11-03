# Changelog

User-visible changes worth mentioning.

---

## Unreleased
- Add support for Ruby 3.0 and above
- Add support for Rails 7.0
- Drop support for Ruby below 2.0
- Drop support for Rails 4.2, 5.0, and 5.1

## 3.10.0 - 2017-09-27
- Drop support for `mysql`, just test `mysql2`
- Drop support for Rails 3.1, 3.2, 4.0, and 4.1
- Add license to gemspec - Thanks @leapingfrogs - #56

## 3.9.0 - 2017-03-16
- Add option for specifying parent class - Thanks @nathanstitt - #53

## 3.8.0 - 2017-02-07
- Always clear dependencies on `Temping.teardown` using 
  `ActiveSupport::Dependencies::Reference.clear!` - Thanks @faucct - #49
- Remove `clear_dependencies` option from `Temping.teardown`

## 3.7.1 - 2016-08-24
- Primary key fix. Properly set primary key in table when creating it.

## 3.7.0 - 2016-08-24
- Option to clear dependencies cache on `teardown` - #47, #45

## 3.6.1 - 2016-03-24
- Fixed unexpected model reflections caching - Thanks @faucct - #40

## 3.6.0 - 2016-03-23
- Add support for Rails 5 ApplicationRecord - Thanks @bryanwoods - #44

## 3.5.0 - 2016-03-23
- Add `Temping.cleanup` method - Thanks @bolshakov - #39

## 3.4.0 - 2016-03-23
- Add abiltity to override create_table options - Thanks @bolshakov - #38

## 3.3.1 - 2016-03-23
- Patch an issue when you create multiple models with Temping with the same name - Thanks @oneamtu! - #31

## 3.3.0 - 2015-05-18
- Add `Temping.teardown`. Thanks @grn! - #20
