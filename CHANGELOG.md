# CHANGELOG

## master

## 2.2.0 (2019-06-25)

* Allow testing numeric variables with regexp

## 2.1.2 (2019-06-14)

* Let `rules` in configuration be optional

## 2.1.1 (2019-06-11)

* Let `:int` variable match with `0`

## 2.1.0 (2019-06-10)

* Introduce regexp string pattern [#56](https://github.com/sider/goodcheck/pull/56)
* Introduce variable binding token pattern [#55](https://github.com/sider/goodcheck/pull/55)

## 2.0.0 (2019-06-06)

* Introduce trigger, a new pattern definition [#53](https://github.com/sider/goodcheck/pull/53)

## 1.7.1 (2019-05-29)

* Fix test command error handling
* Update strong_json

## 1.7.0 (2019-05-28)

* Support a rule without `pattern` [#52](https://github.com/sider/goodcheck/pull/52)
* Let each `pattern` have `glob` [#50](https://github.com/sider/goodcheck/pull/50)

## 1.6.0 (2019-05-08)

* Add `not` pattern rule [#49](https://github.com/sider/goodcheck/pull/49)

## 1.5.1 (2019-05-08)

* Regexp matching improvements
* Performance improvements

## 1.5.0 (2019-03-18)

* Add `exclude` option #43

## 1.4.1 (2018-10-15)

* Update StrongJSON #28

## 1.4.0 (2018-10-11)

* Exit with `2` when it find matching text #27
* Import rules from another location #26

## 1.3.1 (2018-08-16)

* Delete Gemfile.lock

## 1.3.0 (2018-08-16)

* Improved commandline option parsing #25 (@ybiquitous)
* Skip loading dot-files #24 (@calancha)
* Performance improvement on literal types #15 (@calancha)

## 1.2.0 (2018-06-29)

* `case_insensitive` option is now renamed to `case_sensitive`. #4
* Return analysis JSON object from JSON reporter. #13 (@aergonaut)

## 1.1.0 (2018-05-16)

* Support `{}` syntax in glob. #11
* Add `case_insensitive` option for `token` pattern. #10

## 1.0.0 (2018-02-22)

* Stop resolving realpath for symlinks. #6
* Revise non-ASCII characters tokenization. #5

## 0.3.0 (2017-12-27)

* `check` ignores config file unless explicitly given by commandline #2

## 0.2.0 (2017-12-26)

* Add `version` command
