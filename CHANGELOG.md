# master (unreleased)

# 3.2.0 / 2017-03-24

* [CHANGE] Update `rubocop` to 0.47.1 from 0.42.0 (by [@jdickey][])
* [CHANGE] Update for Ruby 2.4.0 compatibility; update `parser` gem to 2.4.0 (by [@jdickey][])
* [CHANGE] Improve YARD documentation (by [@olleolleolle][] and [@tejasbubane][])

# 3.1.3 / 2016-12-19

* [BUGFIX] Fix crash with the usage of an unavailable color in "rainbow" gem  (by [@thedrow][])

# 3.1.2 / 2016-12-17

* [BUGFIX] Fix errors when no source-control is found (by [@tejasbubane][])
* [BUGFIX] Fix lack of the GPA chart when used with rake/rails (by [@hoshinotsuyoshi][])
* [BUGFIX] Fix code navigation links in the new UI (by [@rohitcy][])

# 3.1.1 / 2016-12-02

* [FEATURE] Implement search and filter on code and smells view (by [@rohitcy][])
* [CHANGE] Use Ruby's File instead of `wc` system command (by [@tejasbubane][])
* [CHANGE] Add MRI 2.3.3 compatibility by updating `parser` to v2.3.3.1 (by [@josephpage][])
* [BUGFIX] Fix code navigation links in the new UI (by [@rohitcy][])
* [BUGFIX] Add missing method 'head_reference' for Perforce source control (by [@Rataah][])

# 3.1.0 / 2016-11-23

* [FEATURE] Support for Perforce source control system (by [@Rataah][])
* [CHANGE] New Web UI (by [@tejasbubane][])
* [CHANGE] Significant improvements to documentation (by [@olleolleolle][])
* [CHANGE] Typo / consistency updates to features and tests (by [@olleolleolle][])
* [CHANGE] Fix test warnings and upgrade 'parser' to '2.3.1.4' (by [@tejasbubane][])
* [BUGFIX] Increase the turboThreshold of Highcharts so that it renders nicely even with lots of data (by [@victormartins][])

# 3.0.0 / 2016-11-01

* [CHANGE] Set required ruby version to 2.1 (by [@Onumis][])
* [BUGFIX] Respect the .reek configuration file (by [@mereghost][])

# 2.9.4 / 2016-09-16

* [CHANGE] Update Reek, flog, flay (by [@bglusman][])

# 2.9.3 / 2016-08-17

* [FEATURE] Save json report to file  (by [@NickTroy][])
* [CHANGE] Rename Rubycritic to RubyCritic (by [@troessner][])

# 2.9.2 / 2016-07-01

* [CHANGE] Upgrade rubocop to 0.41.1 (by [@nijikon][])
* [CHANGE] Upgrade flog to 4.4.0 (by [@nijikon][])
* [CHANGE] Upgrade flay to 2.8.0 (by [@nijikon][])
* [CHANGE] Upgrade Reek to 4.1.0 and Parser to 2.3.1.2 (by [@y-yagi][])

# 2.9.1 / 2016-05-16

* [CHANGE] Upgrade 'parser' to 2.3.1.0 (by [@y-yagi][])
* [CHANGE] Upgrade 'reek' to 4.0.2 (by [@onumis][])
* [CHANGE] Upgrade 'rubocop' to 0.40.0 (by [@onumis][])

# 2.9.0 / 2016-04-12

* [FEATURE] Add links to Flay and Flog code smells documentation (by [@ragesoss][])
* [FEATURE] Documentation updates (by [@troessner][])
* [CHANGE] Bump Rubocop to 0.39.0 (by [@nijikon][])
* [CHANGE] Bump Reek to 4.0.1 (by [@nijikon][])
* [CHANGE] Drop support for Ruby 2.0 (by [@nijikon][])

# 2.8.0 / 2016-02-29

* [FEATURE] Add link to Reek's code smells documentation (by [@danielmbarlow][])
* [FEATURE] Make RubyCritic usable as Rake Task (by [@troessner][])
* [CHANGE] Bump Rubocop to 0.37.2 (by [@nijikon][])
* [CHANGE] Bump Flay to 2.7.0 (by [@nijikon][])
* [CHANGE] Bump Reek to 3.11 (by [@nijikon][])
* [CHANGE] Add explicit runtime dependency on ruby_parser ('~> 3.8') (by [@Onumis][])

# 2.7.1 / 2016-02-09

* [CHANGE] Bump Reek to 3.10.1 (by [@nijikon][])
* [BUGFIX] Analyse only the files whose paths are specified in the CLI (by [@Onumis][])

# 2.7.0 / 2016-01-23

* [FEATURE] Open html report with browser (by [@superiorlu][])
* [CHANGE] Bump Reek to 3.9.1
* [CHANGE] Bump Rubocop to 0.36 and internal cleanup (preparing for Ruby 2.3)

# 2.6.0 / 2016-01-21

* [FEATURE] Add a minimum score option to the command line interface (by [@RobertoSchneiders][])
* [CHANGE] Display the class and module names when the file has no methods

# 2.5.0 / 2016-01-16

* [FEATURE] Add a ConsoleReport format (by [@jbodah][])

# 2.4.1 / 2015-12-27

* [CHANGE] Bump Reek to 3.8.1

# 2.4.0 / 2015-12-26

* [FEATURE] Add progress bar functionality (by [@natesholland][])

# 2.3.0 / 2015-11-30

* [FEATURE] Added global score calculation (by [@ancorgs][])
* [CHANGE] Bump Reek dependency to 3.7.1.

# 2.2.0 / 2015-11-20

* [CHANGE] Use `Reeks` default configuration loading.

# 2.1.0 / 2015-11-11

* [CHANGE] Bump flay dependency to 2.6.1.
* [CHANGE] Bump reek dependency to 3.6.0.
* [CHANGE] Bump flog dependency to 4.3.2.

# 2.0.0 / 2015-11-11

* [CHANGE] Drop support for ruby 1.9

# 1.4.0 / 2015-03-14

* [FEATURE] New report in JSON format. Available by using the new CLI option `-f`
* [FEATURE] New CLI option `--suppress-ratings` to suppress ratings (by [@halostatue][])
* [CHANGE] Improve UI, particularly the sortable tables (by [@crackofdusk][])

# 1.3.0 / 2015-02-16

* [FEATURE] New CLI option `--deduplicate-symlinks` to deduplicate symlinks (by [@LeeXGreen][])
* [CHANGE] Update to Reek 1.6.5 (from 1.6.3)
* [CHANGE] Remove ruby2ruby dependency

# 1.2.1 / 2015-01-17

* [FEATURE] Support Ruby 2.2
* [CHANGE] Update to Reek 1.6.3 (from 1.6.0)
* [CHANGE] Update to at least Parser 2.2.0 (from 2.2.0.pre.5)

# 1.2.0 / 2014-12-27

* [FEATURE] Add CI mode that only analyses the last commit
* [FEATURE] Add partial support for Mercurial
* [FEATURE] Allow using RubyCritic programatically
* [CHANGE] Update to Reek 1.6.0 (from 1.3.8)
* [BUGFIX] Fix issue #18 - Prevent encoding issues when using Git

# 1.1.1 / 2014-07-29

* [BUGFIX] Analyse only the files whose paths are specified in the CLI

# 1.1.0 / 2014-07-27

* [FEATURE] Display name of the first module found in a file instead of the file's name

# 1.0.2 / 2014-07-23

* [BUGFIX] Fix issue #8 - Solve a dependency error by requiring at least ruby2ruby 2.1.1

# 1.0.1 / 2014-07-22

* [BUGFIX] Fix issue #6 - Rescue `Parser::SyntaxError` when a file is unparsable

# 1.0.0 / 2014-07-13

* Official Release


[@LeeXGreen]: https://github.com/LeeXGreen
[@crackofdusk]: https://github.com/crackofdusk
[@halostatue]: https://github.com/halostatue
[@ancorgs]: https://github.com/ancorgs
[@natesholland]: https://github.com/natesholland
[@jbodah]: https://github.com/jbodah
[@RobertoSchneiders]: https://github.com/RobertoSchneiders
[@superiorlu]: https://github.com/superiorlu
[@Onumis]: https://github.com/Onumis
[@nijikon]: https://github.com/nijikon
[@troessner]: https://github.com/troessner
[@danielmbarlow]: https://github.com/danielmbarlow
[@ragesoss]: https://github.com/ragesoss
[@y-yagi]: https://github.com/y-yagi
[@NickTroy]: https://github.com/NickTroy
[@bglusman]: https://github.com/bglusman
[@mereghost]: https://github.com/mereghost
[@victormartins]: https://github.com/victormartins
[@tejasbubane]: https://github.com/tejasbubane
[@olleolleolle]: https://github.com/olleolleolle
[@Rataah]: https://github.com/Rataah
[@rohitcy]: https://github.com/rohitcy
[@josephpage]: https://github.com/josephpage
[@hoshinotsuyoshi]: https://github.com/hoshinotsuyoshi
[@thedrow]: https://github.com/thedrow
[@jdickey]: https://github.com/jdickey
