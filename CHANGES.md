# Changelog

## 0.6.1 (2013-05-07)

* Signal a usage error when an environment_variable fails validation.
* Refactor setting, defaulting and inheritance of attributes.

## 0.6.0 (2013-04-28)

* Introduce "banner" to describe a command (replacing "self.description=").
* Introduce "Clamp do ... end" syntax sugar.
* Allow parameters to be specified before a subcommand.
* Add support for :multivalued options.
* Multi valued options and parameters get an "#append_to_foo_list" method, rather than
  "#foo_list=".
* default_subcommand must be specified before any subcommands.
