## v0.17.0
- #131: Add JSON front matter (thanks @gkjpetter)
- #42: Prevent `language-html` from marking singular ampersands as invalid (thanks @bobrocke and @joallard)
- Disabled spec for commands; failed with latest release
- Rewritten instructions in `README.md`

### v0.16.3
- #131: Fix broken column alignment delimiters when used without a leading or trailing space (thanks @tpoisot)

### v0.16.2
- Add `.spec` filetype for [Gauge](http://getgauge.io/documentation/user/current/getting_started/project_structure/)

## v0.16.0
- #126: Add support for embedded Crystal code snippet highlighting (thanks @keplersj)
- Add keybinding `~` that toggles _strike-through_ on selected text

## v0.15.0
- #121 and #123: Add generic fenced-code-blocks (thanks @heavywatal)
- #123: Add language support for `Lua` (thanks @Stanzilla)
- Mark horizontal-rule as a constant

### v0.14.1
- #117: Disallow parenthesis in link-destination (thanks @tsaiid)

## v0.14.0
- #114: Remove necessity for a whitespace character following the language-name in fenced-code-blocks (thanks @eloquently)
- #112: Re-add R to generic fenced-code-blocks (thanks @heavywatal)
- #113: Separate table-data from table-structure

## v0.13.0
- Add keybindings `_` and `*` that toggle (**strong**) _emphasis_ on selected text
- #100: Allow inline code-spans with any number of (matching) backticks (thanks @cblp)
- Add `one-o-eight-syntax` to supported syntax themes (thanks @tpoisot)
- #2: Detect Pandoc citations (in square brackets) (thanks @tpoisot)
- #106: Merge Github mentions and Pandoc citations into generic references

## v0.12.0
- #94: Upgrade lists
  - Allow ordered/numbered task-lists
  - Allow `+` and `*` as markers for task-lists
  - Allow capital `X` to mark a task as complete
- #90: Fix nested inline elements
- #97: Add support for `liquid` (thanks @fusion809)

## v0.11.0
- #82: Add **R Markdown** flavor (thanks to @pimentel)

### v0.10.1
- Fix wrong scope on keymaps preventing list-item in- and outdenting

### v0.10.0
- #79: Add specs for custom commands
- Fix: wrong scope on keymaps
- Fix: revert #76 (marking checkbox as separate token in task-lists); prevented new task-list-items from being created

## v0.9.0
- #74: Add support for AtomDoc references, such as {ClassName} and {Class::method}
- #75: Separate `gfm-blocks` from `gfm-inlines` and add the latter to `inlines-in-blocks`; makes references work inside tables again
- #76: Mark the checkbox in task-list-items as a separate token

### v0.8.1
- #70: Don't disable `language-gfm` if it is already disabled (thanks @KaiBueker)

## v0.8.0
- Remove the automatically created empty list-item after pressing <kbd>enter</kbd> if left empty (+option to disable this)
- Add fenced-code-block support for `jsx`, `sass` and `scss` (thanks to @afc163 and @afontaine)
