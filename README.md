# Awesome Flake8 Extensions with stars

> A curated list of awesome flake8 extensions.

Inspired after reading a [post](https://web.archive.org/web/20230322220629/https://julien.danjou.info/the-best-flake8-extensions/).

## Contents

* [All-in-one](#all-in-one)
* [Bugs](#bugs)
* [Clean code](#clean-code)
* [Limitations](#limitations)
* [Naming](#naming)
* [Complexity](#complexity)
* [Comments](#comments)
* [Docstrings](#docstrings)
* [Tools](#tools)
* [Imports](#imports)
* [Testing](#testing)
* [Type annotations](#type-annotations)
* [Library-specific checks](#library-specific-checks)
* [Integrations](#integrations)
* [Wrappers](#wrappers)
* [Formatters](#formatters)

## All-in-one

Extensions with more than 20 rules inside.

* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) ⭐ 2,892 | 🐛 13 | 🌐 Python | 📅 2026-08-24 - The strictest and most opinionated Python linter ever.
* [flake8-bugbear](https://github.com/PyCQA/flake8-bugbear) ⭐ 1,116 | 🐛 60 | 🌐 Python | 📅 2026-08-22 - Finding likely bugs and design problems in your program.
* [hacking](https://github.com/openstack/hacking) ⭐ 244 | 🐛 0 | 🌐 Python | 📅 2026-06-11 - Set of flake8 plugins that test and enforce the [OpenStack StyleGuide](https://docs.openstack.org/hacking/latest/user/hacking.html#styleguide).
* [flake8-simplify](https://github.com/MartinThoma/flake8-simplify) ⭐ 193 | 🐛 57 | 🌐 Python | 📅 2026-07-21 - Plugin that helps you to simplify code.
* [dlint](https://github.com/dlint-py/dlint) ⭐ 178 | 🐛 23 | 🌐 Python | 📅 2026-01-07 - Tool for encouraging best coding practices and helping ensure Python code is secure.
* [flake8-pie](https://github.com/sbdchd/flake8-pie) ⚠️ Archived - Extension that implements misc. lints.
* [flake8-tergeo](https://github.com/SAP/flake8-tergeo) ⭐ 6 | 🐛 4 | 🌐 Python | 📅 2026-08-24 - Adds many new rules to improve your code quality and brings a curated and actively maintained list of other plugins including flake8-bugbear.

## Bugs

Extensions for finding possible bugs.

* [flake8-2020](https://github.com/asottile/flake8-2020) ⚠️ Archived - Plugin which checks for misuse of `sys.version` or `sys.version_info`.
* [flake8-mutable](https://github.com/ebeweber/flake8-mutable) ⭐ 44 | 🐛 15 | 🌐 Python | 📅 2026-04-13 - Detect usage of mutable objects as default values for arguments.
* [flake8-alfred](https://github.com/datatheorem/flake8-alfred) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2026-02-09 - Alfred is a flake8 plugin to warn on unsafe/obsolete symbols.
* [flake8-requirements](https://github.com/Arkq/flake8-requirements) ⭐ 37 | 🐛 13 | 🌐 Python | 📅 2025-12-01 - Package requirements checker.
* [flake8-unused-arguments](https://github.com/nhoad/flake8-unused-arguments) ⭐ 32 | 🐛 3 | 🌐 Python | 📅 2025-10-27 - Warn against unused arguments in functions.
* [flake8-string-format](https://github.com/xZise/flake8-string-format) ⭐ 20 | 🐛 14 | 🌐 Python | 📅 2026-08-01 - Check that indexed parameters are used in strings.
* [flake8-warnings](https://github.com/orsinium-labs/flake8-warnings) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-09-28 - Detect usage of deprecated modules, classes, and functions.
* [flake8-async](https://github.com/cooperlees/flake8-async) ⚠️ Archived - A flake8 plugin that checks for bad async / asyncio practices.
* [flake8-dunder-all](https://github.com/python-formate/flake8-dunder-all) ⭐ 8 | 🐛 4 | 🌐 Python | 📅 2026-07-10 - Ensures that modules have defined `__all__`.
* [flake8-encodings](https://github.com/python-formate/flake8-encodings) ⭐ 7 | 🐛 3 | 🌐 Python | 📅 2026-04-07 - Identify incorrect use of encodings.
* [flake8-secure-coding-standard](https://github.com/Takishima/flake8-secure-coding-standard) ⭐ 5 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Enforce some secure coding standards for Python. <!-- TODO(@orsinium): move into 'All-in-one' when grows -->
* [flake8-slots](https://github.com/python-formate/flake8-slots) ⭐ 4 | 🐛 4 | 🌐 Python | 📅 2026-04-07 - Require `__slots__` to be defined for subclasses of immutable types.
* [flake8-useless-assert](https://github.com/decorator-factory/flake8-useless-assert) ⭐ 4 | 🐛 2 | 🌐 Python | 📅 2023-01-31 - Detect useless `assert` statements.
* [flake8-timeout](https://github.com/jkittner/flake8-timeout) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-08-03 - Checks for missing timeout parameters in network calls.
* [flake8-strftime](https://github.com/python-formate/flake8_strftime) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2026-04-07 - Checks for use of platform-specific strftime codes.
* [flake8-qt-tr](https://github.com/ostr00000/flake8-qt-tr) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-06 - Detect incorrectly wrapped Qt translation text.

## Clean code

Extensions for finding stylistic issues and enforcing consistent codestyle.

* [flake8-comprehensions](https://github.com/adamchainz/flake8-comprehensions) ⭐ 465 | 🐛 8 | 🌐 Python | 📅 2026-08-18 - Helps you write better list/set/dict comprehensions.
* [flake8-commas](https://github.com/PyCQA/flake8-commas) ⭐ 134 | 🐛 3 | 🌐 Python | 📅 2026-01-05 - Enforcing trailing commas in Python.
* [flake8-class-attributes-order](https://github.com/best-doctor/flake8-class-attributes-order) ⭐ 60 | 🐛 8 | 🌐 Python | 📅 2025-03-20 - Checks classes attributes order.
* [flake8-datetimez](https://github.com/pjknkda/flake8-datetimez) ⭐ 40 | 🐛 0 | 🌐 Python | 📅 2026-08-12 - A plugin for flake8 to ban the usage of unsafe naive datetime class.
* [flake8-implicit-str-concat](https://github.com/flake8-implicit-str-concat/flake8-implicit-str-concat) ⭐ 34 | 🐛 5 | 🌐 Python | 📅 2026-07-24 - Plugin to encourage correct string literal concatenation.
* [flake8-obey-import-goat](https://github.com/Melevir/flake8-obey-import-goat) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-05-17 - Allows to forbid specific imports.
* [flake8-multiline-containers](https://github.com/jsfehler/flake8-multiline-containers) ⭐ 14 | 🐛 12 | 🌐 Python | 📅 2026-06-19 - Plugin to ensure a consistent format for multiline containers.
* [flake8-newspaper-style](https://github.com/mobility-university/flake8-newspaper-style) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2022-10-16 - Ensures the function definition goes below its usage.
* [flake8-literal](https://github.com/plinss/flake8-literal) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-06-28 - Enforces consistent styling of string literals.
* [flake8-clean-block](https://github.com/cyyc1/flake8-clean-block) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-10-08 - Plugin to enforce a blank line after if/for/while/with/try blocks.
* [flake8-datetime-utcnow-plugin](https://github.com/expobrain/flake8-datetime-utcnow-plugin) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2026-01-01 -  Plugin to warn the developer of the usage of `datetime.utcnow()`.
* [flake8-indent-in-def](https://github.com/cyyc1/flake8-indent-in-def) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2022-10-08 - Plugin to enforce 8-space indentation in function and class definitions.
* [flake8-all-not-strings](https://github.com/ggupta2005/flake8-all-not-strings) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-02-27 - Checks that if modules under `__all__` are defined as strings.

<!--lint ignore awesome-spell-check-->

* [tryceratops](https://github.com/guilatrova/tryceratops) ⭐ 446 | 🐛 10 | 🌐 Python | 📅 2024-10-30 - Prevent exception handling antipatterns.
* [flake8-quotes](https://github.com/zheller/flake8-quotes) ⭐ 181 | 🐛 12 | 🌐 Python | 📅 2024-03-23 - Extension for checking quotes in Python.
* [flake8-return](https://github.com/afonasev/flake8-return) ⭐ 60 | 🐛 14 | 🌐 Python | 📅 2025-10-08 - Plugin that checks return values.
* [flake8-sql](https://github.com/pgjones/flake8-sql) ⭐ 26 | 🐛 6 | 🌐 Python | 📅 2022-06-15 - Plugin that checks SQL code against opinionated style rules.
* [flake8-strict](https://github.com/smarkets/flake8-strict) ⭐ 10 | 🐛 4 | 🌐 Python | 📅 2018-05-30 - Checks Python code against a set of opinionated style rules.
* [flake8-picky-parentheses](https://github.com/robsdedude/flake8-picky-parentheses) ⭐ 9 | 🐛 4 | 🌐 Python | 📅 2026-08-11 - Checks for redundant parentheses and alignment of parentheses and brackets.
* [flake8-scream](https://github.com/MartinThoma/flake8-scream) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2022-11-19 - Rules which do have known false-positives but might still be useful for a one-time run.
* [flake8-too-many](https://github.com/queensferryme/flake8-too-many) ⭐ 4 | 🐛 2 | 🌐 Python | 📅 2026-08-24 - Plugin that prevents you from writing 'too many' bad codes.

## Limitations

Extensions banning specific Python features.

* [flake8-logging-format](https://github.com/globality-corp/flake8-logging-format) ⭐ 137 | 🐛 32 | 🌐 Python | 📅 2026-04-12 - Report string formatting inside logging.
* [flake8-print](https://github.com/JBKahn/flake8-print) ⭐ 121 | 🐛 4 | 🌐 Python | 📅 2023-07-16 - Report `print` statement.
* [flake8-broken-line](https://github.com/wemake-services/flake8-broken-line) ⭐ 111 | 🐛 14 | 🌐 Python | 📅 2025-01-03 - Report line break with backslash (`\`).
* [flake8-logging](https://github.com/adamchainz/flake8-logging) ⭐ 86 | 🐛 16 | 🌐 Python | 📅 2026-08-18 - Reports issues in using the standard library logging module.
* [flake8-use-fstring](https://github.com/MichaelKim0407/flake8-use-fstring) ⭐ 50 | 🐛 4 | 🌐 Python | 📅 2023-11-07 - Report `%`-formatting and `str.format`.
* [flake8-walrus](https://github.com/asottile/flake8-walrus) ⚠️ Archived - Report walrus operator (`:=`).
* [flake8-debugger](https://github.com/JBKahn/flake8-debugger) ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2022-04-30 - Report debug statements (`pdb`, `ipdb`).
* [flake8-no-pep420](https://github.com/adamchainz/flake8-no-pep420) ⭐ 29 | 🐛 2 | 🌐 Python | 📅 2026-08-18 - Report implicit namespace packages.
* [flake8-match](https://github.com/asottile/flake8-match) ⚠️ Archived - Report `match` statement.
* [flake8-no-implicit-concat](https://github.com/10sr/flake8-no-implicit-concat) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2026-06-29 - Report implicit string concatenation.
* [flake8-pep3101](https://github.com/gforcada/flake8-pep3101) ⭐ 14 | 🐛 3 | 🌐 Python | 📅 2025-10-25 - Report `%`-formatting.
* [flake8-printf-formatting](https://github.com/atugushev/flake8-printf-formatting) ⭐ 11 | 🐛 4 | 🌐 Python | 📅 2021-10-12 - Report `%`-formatting.
* [flake8-forbidden-func](https://github.com/tripcher/flake8-forbidden-func) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2022-11-09 - Forbid some functions in some modules.
* [flake8-use-pathlib](https://gitlab.com/RoPP/flake8-use-pathlib) - Report `os.path`.

## Naming

Extensions for checking names of variables, functions, etc.

* [pep8-naming](https://github.com/PyCQA/pep8-naming) ⭐ 530 | 🐛 21 | 🌐 Python | 📅 2025-05-06 - Check the PEP-8 naming conventions.
* [flake8-builtins](https://github.com/gforcada/flake8-builtins) ⭐ 118 | 🐛 3 | 🌐 Python | 📅 2025-10-25 - Check for Python builtins being used as variables or parameters.
* [flake8-variables-names](https://github.com/best-doctor/flake8-variables-names) ⭐ 53 | 🐛 5 | 🌐 Python | 📅 2024-06-28 - Extension that helps to make more readable variables names.
* [flake8-functions-names](https://github.com/Melevir/flake8-functions-names) ⭐ 27 | 🐛 9 | 🌐 Python | 📅 2023-03-13 - Validate functions names, decomposition and conformity with annotations.
* [flake8-test-name](https://github.com/bagerard/flake8-test-name) ⭐ 5 | 🐛 3 | 🌐 Python | 📅 2026-07-24 - Checks that test functions names follow a given convention.

## Complexity

Extensions for ensuring low code complexity.

* [cohesion](https://github.com/mschwager/cohesion#flake8-support) ⭐ 278 | 🐛 8 | 🌐 Python | 📅 2024-12-09 - Extension for measuring Python class cohesion.
* [flake8-cognitive-complexity](https://github.com/Melevir/flake8-cognitive-complexity) ⭐ 71 | 🐛 6 | 🌐 Python | 📅 2021-02-24 - Extension for flake8 that validates cognitive functions complexity.
* [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) ⭐ 50 | 🐛 3 | 🌐 Python | 📅 2026-08-14 - Plugin to validate annotations complexity.
* [flake8-functions](https://github.com/best-doctor/flake8-functions) ⭐ 50 | 🐛 7 | 🌐 Python | 📅 2026-08-14 - Plugin for validation of function parameters (length, complexity, etc).
* [flake8-expression-complexity](https://github.com/best-doctor/flake8-expression-complexity) ⭐ 33 | 🐛 6 | 🌐 Python | 📅 2026-08-14 - Plugin to validate expressions complexity.
* [flake8-length](https://github.com/orsinium-labs/flake8-length) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2022-10-30 - Smart line length validation.

## Comments

Extensions for checking comments.

* [flake8-eradicate](https://github.com/wemake-services/flake8-eradicate) ⭐ 315 | 🐛 11 | 🌐 Python | 📅 2025-03-14 - Plugin to find commented out or dead code.
* [flake8-noqa](https://github.com/plinss/flake8-noqa) ⭐ 39 | 🐛 9 | 🌐 Python | 📅 2026-02-07 - Validate `# noqa` comments.
* [flake8-todo](https://github.com/schlamar/flake8-todo) ⭐ 30 | 🐛 3 | 🌐 Python | 📅 2019-03-07 - Check for TODO notes.
* [flake8-todos](https://github.com/orsinium-labs/flake8-todos) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2024-02-09 - Lint TODO comments to be consistent and have an issue linked.
* [flake8-executable](https://github.com/xuhdev/flake8-executable) ⭐ 20 | 🐛 18 | 🌐 Python | 📅 2026-08-06 - Plugin for checking executable permissions and shebangs.
* [flake8-fixme](https://github.com/tommilligan/flake8-fixme) ⭐ 20 | 🐛 4 | 🌐 Python | 📅 2023-02-08 - Check for FIXME, TODO and other temporary developer notes.
* [flake8-copyright](https://github.com/savoirfairelinux/flake8-copyright) ⭐ 18 | 🐛 9 | 🌐 Python | 📅 2023-09-18 - Adds copyright checks to flake8.
* [flake8-coding](https://github.com/tk0miya/flake8-coding) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2019-06-16 - Adds coding magic comment checks (coding:) to flake8.
* [flake8-comments](https://github.com/orsinium-labs/flake8-comments) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2021-06-08 - Reports redundant comments.
* [flake8-ado](https://github.com/DanielKusyDev/flake8-ado) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-12-01 - Check that all Azure DevOps IDs mentioned in the comments are in the correct format and have the corresponding ADO item.
* [flake8-jira-todo-checker](https://github.com/simonstjg/flake8-jira-todo-checker) ⭐ 7 | 🐛 3 | 🌐 Python | 📅 2024-07-06 - Check that every TODO comment has a valid JIRA issue ID next to it.
* [flake8-ownership](https://github.com/decafjoe/flake8-ownership) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2019-07-15 - Checker for assuring that author, copyright, and license are specified in source files.
* [flake8-author](https://github.com/jparise/flake8-author) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-07-25 - Checks Python modules for `__author__` attributes.

## Docstrings

Extensions for checking docstrings.

* [pydoclint](https://github.com/jsh9/pydoclint) ⭐ 221 | 🐛 30 | 🌐 Python | 📅 2026-07-03 - A Python docstring linter that checks arguments, returns, yields, and raises sections.
* [flake8-docstrings](https://github.com/pycqa/flake8-docstrings) ⭐ 159 | 🐛 3 | 🌐 Python | 📅 2026-07-13 - Include checks provided by pep257.
* [flake8-spellcheck](https://github.com/MichaelAquilina/flake8-spellcheck) ⭐ 76 | 🐛 25 | 🌐 Python | 📅 2024-08-27 - Spellcheck variables, classnames, comments, docstrings etc.
* [flake8-rst-docstrings](https://github.com/peterjc/flake8-rst-docstrings) ⭐ 58 | 🐛 5 | 🌐 Python | 📅 2026-08-03 - Validate Python docstrings as reStructuredText (RST).
* [flake8-docstrings-complete](https://github.com/jdkandersson/flake8-docstrings-complete) ⭐ 12 | 🐛 15 | 🌐 Python | 📅 2024-11-07 - Linter that checks docstrings of functions, methods and classes.
* [flake8-sphinx-links](https://github.com/python-formate/flake8-sphinx-links) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-04-07 - Check docstrings for double backticked strings which should be links to the Python documentation.
* [flake8-docstring-checker](https://gitlab.com/JakobDev/flake8-docstring-checker) - Checks if everything has a docstring.

## Tools

Tools empowering flake8.

* [nitpick](https://github.com/andreoliwa/nitpick) ⭐ 413 | 🐛 57 | 🌐 Python | 📅 2026-08-24 - Enforce the same lint configuration (flake8, isort, mypy, pylint) across multiple Python projects.
* [yesqa](https://github.com/asottile/yesqa) ⭐ 264 | 🐛 0 | 🌐 Python | 📅 2026-08-17 - A tool to automatically remove unnecessary `# noqa` comments.
* [flake8-pyproject](https://github.com/john-hen/Flake8-pyproject) ⭐ 245 | 🐛 2 | 🌐 Python | 📅 2026-07-20 - Flake8 plug-in loading the configuration from pyproject.toml.
* [flakehell](https://github.com/flakehell/flakehell) ⭐ 88 | 🐛 21 | 🌐 Python | 📅 2025-08-20 - Wrapper to make it nice, legacy-friendly, and configurable.
* [flake8-codes](https://github.com/orsinium-labs/flake8-codes) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2022-05-23 - CLI tool to introspect flake8 plugins and their codes.
* [flake8-ruler](https://github.com/orsinium-labs/flake8-ruler) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2022-01-28 - More powerful configs for flake8.
* [flake8-in-file-ignores](https://github.com/bagerard/flake8-in-file-ignores) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-10-09 - Allow in file ignore e.g. `# flake8-in-file-ignores: noqa: E731`.
* [wps-playground](https://github.com/orsinium-labs/wps-playground) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-01-09 - Online playground for wemake-python-styleguide.
* [flake8-pyprojecttoml](https://gitlab.com/durko/flake8-pyprojecttoml) - Adds support for reading flake8 config from pyproject.toml.
* [flakes](https://flakes.orsinium.dev/) - Web list of flake8 plugins and their codes, a wrapper around flake8-codes.

## Imports

Extensions for checking import statements.

* [flake8-import-order](https://github.com/PyCQA/flake8-import-order) ⭐ 281 | 🐛 14 | 🌐 Python | 📅 2026-08-18 - Include checks import order against various Python Style Guides.
* [flake8-type-checking](https://github.com/snok/flake8-type-checking) ⭐ 128 | 🐛 4 | 🌐 Python | 📅 2026-02-18 - Plugin lets you know which imports to move in or out of type-checking blocks.
* [flake8-tidy-imports](https://github.com/adamchainz/flake8-tidy-imports) ⭐ 75 | 🐛 5 | 🌐 Python | 📅 2026-08-18 - Extension that helps you write tidier imports.
* [flake8-lazy](https://github.com/henryiii/flake8-lazy) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-08-17 - Detect modules that can be lazy imported in Python 3.15+.
* [flake8-future-import](https://github.com/xZise/flake8-future-import) ⭐ 18 | 🐛 6 | 🌐 Python | 📅 2022-10-18 - Extension to check imports.
* [flake8-alphabetize](https://github.com/tlocke/flake8-alphabetize) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2023-05-23 - Checking the order of `import` statements and the `__all__` list.
* [flake8-import-order-spoqa](https://github.com/spoqa/flake8-import-order-spoqa) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2018-08-30 - Spoqa's import order style for flake8-import-order.
* [flake8-absolute-import](https://github.com/bskinn/flake8-absolute-import) ⭐ 13 | 🐛 4 | 🌐 Python | 📅 2025-11-29 - Plugin to require absolute imports.
* [flake8-datetime-import](https://github.com/marcgibbons/flake8-datetime-import) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Enforce importing `datetime as dt` and `time as tm`.
* [flake8-import-conventions](https://github.com/joaopalmeiro/flake8-import-conventions) ⭐ 11 | 🐛 17 | 🌐 Python | 📅 2023-10-14 - How certain packages should be imported or aliased.
* [flake8-import-style](https://github.com/sfstpala/flake8-import-style) ⭐ 3 | 🐛 2 | 🌐 Python | 📅 2022-03-27 - Plugin to ensure explicit module imports.
* [flake8-internal-name-import](https://github.com/rows-s/flake8_internal_name_import) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2023-08-25 - Plugin that reports imports of protected names.

## Testing

Extensions for testing.

* [flake8-pytest-style](https://github.com/m-burst/flake8-pytest-style) ⭐ 240 | 🐛 34 | 🌐 Python | 📅 2026-08-20 - Checks for common style issues or inconsistencies with pytest-based tests.
* [flake8-aaa](https://github.com/jamescooke/flake8-aaa) ⭐ 73 | 🐛 11 | 🌐 Python | 📅 2025-10-25 - Lints tests against the Arrange Act Assert pattern.
* [flake8-assertive](https://github.com/jparise/flake8-assertive) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2026-07-27 - Unittest assert method checker.
* [flake8-mock](https://github.com/zupo/flake8-mock) ⭐ 17 | 🐛 4 | 🌐 Python | 📅 2023-07-07 - Provides checking mock non-existent methods.
* [flake8-pytest](https://github.com/vikingco/flake8-pytest) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-04-09 - Enforces to use `pytest`-style assertions.
* [flake8-pytestrail](https://github.com/and-semakin/flake8-pytestrail) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2022-01-04 - Checks TestRail test case IDs.
* [flake8-mock-spec](https://github.com/jdkandersson/flake8-mock-spec) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2023-10-01 - Enforce the use of the spec argument on mocks ensuring that your use of mocks is compliant with the interface of the object being mocked.

## Type annotations

Extensions for type annotations.

* [flake8-annotations](https://github.com/sco1/flake8-annotations) ⭐ 165 | 🐛 0 | 🌐 Python | 📅 2026-07-10 - Plugin for flake8 to check for presence of type annotations in function definitions.
* [flake8-typing-imports](https://github.com/asottile/flake8-typing-imports) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2026-08-17 - Plugin which checks that typing imports are properly guarded.
* [flake8-annotations-coverage](https://github.com/best-doctor/flake8-annotations-coverage) ⭐ 34 | 🐛 3 | 🌐 Python | 📅 2022-02-24 - Plugin to validate annotations coverage.
* [flake8-pep585](https://github.com/decorator-factory/flake8-pep585) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2023-02-28 - Enforce new style annotations from [PEP585](https://peps.python.org/pep-0585/) such as `list[int]` instead of `typing.List[int]`.
* [flake8-future-annotations](https://github.com/tyleryep/flake8-future-annotations) ⭐ 15 | 🐛 4 | 🌐 Python | 📅 2026-08-24 - Verifies Python 3.7+ files use `from __future__ import annotations`.
* [flake8-new-union-types](https://github.com/xome4ok/flake8-new-union-types) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-05-07 - Plugin to enforce new Union/Optional syntax `Foo | Bar | None` defined in [PEP 604][pep604].
* [flake8-pep604](https://gitlab.com/matthewhughes/flake-pep604) - Forbids use of `typing.Union` (in favour of `|`), per [PEP 604][pep604].

## Library-specific checks

Extensions for linting usage of specific libraries.

* [flake8-django](https://github.com/rocioar/flake8-django) ⭐ 180 | 🐛 29 | 🌐 Python | 📅 2024-02-09 - Plugin for Django projects.
* [pandas-vet](https://github.com/deppen8/pandas-vet) ⭐ 170 | 🐛 13 | 🌐 Python | 📅 2023-08-11 - Plugin that provides opinionated linting for Pandas code.
* [TorchFix](https://github.com/pytorch-labs/torchfix) ⚠️ Archived - Plugin for code that uses PyTorch.
* [flake8-fastapi](https://github.com/Kludex/flake8-fastapi) ⭐ 46 | 🐛 3 | 🌐 Python | 📅 2023-01-29 - Checks FastAPI code against opinionated style rules.
* [flake8-scrapy](https://github.com/stummjr/flake8-scrapy) ⭐ 22 | 🐛 98 | 🌐 Python | 📅 2026-07-07 - Plugin to catch common issues on Scrapy spiders.
* [flake8-django-migrations](https://github.com/browniebroke/flake8-django-migrations) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Plugin to lint for backwards incompatible database migrations in Django.
* [flake8-numba](https://github.com/mflova/flake8-numba) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2023-07-23 - Plugin that facilitates code development with `numba` package.

## Integrations

Extensions for running flake8 not only on Python files.

* [jupyterlab-flake8](https://github.com/mlshapiro/jupyterlab-flake8) ⭐ 112 | 🐛 8 | 🌐 TypeScript | 📅 2021-09-16 - Jupyterlab Python linter for notebooks and text files using flake8.
* [flake8-pyi](https://github.com/PyCQA/flake8-pyi) ⭐ 83 | 🐛 23 | 🌐 Python | 📅 2026-07-24 - Plugin for Flake8 that provides specializations for type hinting stub files.
* [flake8-nb](https://github.com/s-weigand/flake8-nb) ⭐ 29 | 🐛 11 | 🌐 Python | 📅 2024-11-18 - Runs flake8 on `*.ipynb` (Jupyter Notebook) files.
* [flake8-markdown](https://github.com/johnfraney/flake8-markdown) ⭐ 26 | 🐛 1 | 🌐 Python | 📅 2025-01-09 - Lints Python code blocks in Markdown files using flake8.
* [flake8-rst](https://github.com/flake8-docs/flake8-rst) ⭐ 22 | 🐛 13 | 🌐 Python | 📅 2021-02-26 - Checks on code in `*.rst` files or in docstrings.

## Wrappers

Wrappers around other tools making it possible to use them with flake8.

* [flake8-isort](https://github.com/gforcada/flake8-isort) ⭐ 186 | 🐛 1 | 🌐 Python | 📅 2025-10-25 - Wrapper around [isort](https://github.com/PyCQA/isort) ⭐ 6,948 | 🐛 87 | 🌐 Python | 📅 2026-08-18.
* [flake8-black](https://github.com/peterjc/flake8-black) ⭐ 167 | 🐛 4 | 🌐 Python | 📅 2026-08-03 - Wrapper around [black](https://github.com/psf/black) ⭐ 41,814 | 🐛 303 | 🌐 Python | 📅 2026-08-20.
* [flake8-bandit](https://github.com/tylerwince/flake8-bandit) ⭐ 116 | 🐛 13 | 🌐 Python | 📅 2023-09-13 - Wrapper around [bandit](https://github.com/PyCQA/bandit) ⭐ 8,237 | 🐛 260 | 🌐 Python | 📅 2026-08-24.
* [flake8-pylint](https://github.com/orsinium-labs/flake8-pylint) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2023-10-07 - Wrapper around [pylint](https://github.com/pylint-dev/pylint) ⭐ 5,714 | 🐛 1,091 | 🌐 Python | 📅 2026-08-24.

## Formatters

Extensions for formatting flake8 output.

* [flake8-html](https://github.com/lordmauve/flake8-html) ⭐ 50 | 🐛 11 | 🌐 Python | 📅 2024-11-26 - Generates an HTML report.
* [flake8-gl-codeclimate](https://github.com/awelzel/flake8-gl-codeclimate) ⭐ 25 | 🐛 3 | 🌐 Python | 📅 2026-04-06 - Generates GitLab Code Quality artifacts.
* [flake8-dashboard](https://github.com/aperezhortal/flake8-dashboard) ⭐ 16 | 🐛 1 | 🌐 CSS | 📅 2024-01-05 - Generates an HTML dashboard.
* [flake8-json](https://github.com/PyCQA/flake8-json) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2026-07-13 - Generates JSON output.
* [flake8-github](https://github.com/maxkrivich/flake8-github) ⭐ 5 | 🐛 7 | 🌐 Python | 📅 2026-07-06 - Generates GitHub annotation for PR's.
* [flake8-for-pycharm](https://gitlab.com/ramast/flake8-for-pycharm) - Generates pylint-style JSON output.

[pep604]: https://peps.python.org/pep-0604/ "PEP 604"

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
