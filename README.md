# atom-quick-reference

An abridged list of atom hotkeys. The list includes those keys I find to be the:

1. hardest to remember
2. biggest time savers
3. most interesting

Obvious and unhelpful combos are not in this reference. The full list of shortcuts for the core and all your packages is in Settings > Keybindings.

## Dartlang

Keystroke     | Command                         | Source
------------- | ------------------------------- | --------
alt-enter     | dartlang:quick-fix              | Dartlang
f1            | dartlang:show-dartdoc           | Dartlang
f4            | dartlang:type-hierarchy         | Dartlang
alt-shift-I   | dartlang:refactor-inline-local  | Dartlang
alt-shift-L   | dartlang:refactor-extract-local | Dartlang
alt-shift-R   | dartlang:refactor-rename        | Dartlang
cmd-f4        | dartlang:find-references        | Dartlang
alt-cmd-b     | dartlang:dart-format            | Dartlang
alt-cmd-o     | dartlang:organize-directives    | Dartlang
alt-cmd-enter | dartlang:jump-to-declaration    | Dartlang
shift-cmd-T   | dartlang:find-type              | Dartlang

## Core

Keystroke          | Command                                    | Source
------------------ | ------------------------------------------ | ------
alt-b              | editor:move-to-beginning-of-word           | Core
alt-cmd-[          | editor:fold-current-row                    | Core
alt-cmd-]          | editor:unfold-current-row                  | Core
alt-cmd-h          | application:hide-other-applications        | Core
alt-cmd-i          | window:toggle-dev-tools                    | Core
alt-cmd-s          | window:save-all                            | Core
alt-cmd-{          | editor:fold-all                            | Core
alt-cmd-}          | editor:unfold-all                          | Core
alt-d              | editor:delete-to-end-of-word               | Core
alt-f              | editor:move-to-end-of-word                 | Core
alt-h              | editor:delete-to-beginning-of-word         | Core
cmd-shift-         | editor:scroll-to-cursor                    | Core
cmd-[              | editor:outdent-selected-rows               | Core
cmd-]              | editor:indent-selected-rows                | Core
cmd-enter          | editor:newline-below                       | Core
cmd-j              | editor:join-lines                          | Core
cmd-k alt-cmd-w    | pane:close-other-items                     | Core
cmd-k cmd-0        | editor:unfold-all                          | Core
cmd-k cmd-1        | editor:fold-at-indent-level-1              | Core
cmd-k cmd-2        | editor:fold-at-indent-level-2              | Core
cmd-k cmd-3        | editor:fold-at-indent-level-3              | Core
cmd-k cmd-4        | editor:fold-at-indent-level-4              | Core
cmd-k cmd-5        | editor:fold-at-indent-level-5              | Core
cmd-k cmd-6        | editor:fold-at-indent-level-6              | Core
cmd-k cmd-7        | editor:fold-at-indent-level-7              | Core
cmd-k cmd-8        | editor:fold-at-indent-level-8              | Core
cmd-k cmd-9        | editor:fold-at-indent-level-9              | Core
cmd-k cmd-down     | window:focus-pane-below                    | Core
cmd-k cmd-l        | editor:lower-case                          | Core
cmd-k cmd-left     | window:focus-pane-on-left                  | Core
cmd-k cmd-n        | window:focus-next-pane                     | Core
cmd-k cmd-p        | window:focus-previous-pane                 | Core
cmd-k cmd-right    | window:focus-pane-on-right                 | Core
cmd-k cmd-u        | editor:upper-case                          | Core
cmd-k cmd-up       | window:focus-pane-above                    | Core
cmd-k cmd-w        | pane:close                                 | Core
cmd-k down         | pane:split-down-and-copy-active-item       | Core
cmd-k left         | pane:split-left-and-copy-active-item       | Core
cmd-k right        | pane:split-right-and-copy-active-item      | Core
cmd-k up           | pane:split-up-and-copy-active-item         | Core
cmd-l              | editor:select-line                         | Core
cmd-{              | pane:show-previous-item                    | Core
cmd-}              | pane:show-next-item                        | Core
ctrl-a             | editor:move-to-first-character-of-line     | Core
ctrl-alt-b         | editor:move-to-previous-subword-boundary   | Core
ctrl-alt-backspace | editor:delete-to-beginning-of-subword      | Core
ctrl-alt-cmd-f     | editor:fold-selection                      | Core
ctrl-alt-f         | editor:move-to-next-subword-boundary       | Core
ctrl-alt-h         | editor:delete-to-beginning-of-subword      | Core
ctrl-alt-shift-B   | editor:select-to-previous-subword-boundary | Core
ctrl-alt-shift-F   | editor:select-to-next-subword-boundary     | Core
ctrl-b             | core:move-left                             | Core
ctrl-cmd-down      | editor:move-line-down                      | Core
ctrl-cmd-f         | window:toggle-full-screen                  | Core
ctrl-cmd-left      | editor:move-selection-left                 | Core
ctrl-cmd-right     | editor:move-selection-right                | Core
ctrl-cmd-up        | editor:move-line-up                        | Core
ctrl-d             | core:delete                                | Core
ctrl-e             | editor:move-to-end-of-line                 | Core
ctrl-f             | core:move-right                            | Core
ctrl-h             | core:backspace                             | Core
ctrl-k             | editor:cut-to-end-of-line                  | Core
ctrl-n             | core:move-down                             | Core
ctrl-p             | core:move-up                               | Core
ctrl-shift-A       | editor:select-to-first-character-of-line   | Core
ctrl-shift-C       | editor:copy-path                           | Core
ctrl-shift-K       | editor:delete-line                         | Core
ctrl-shift-W       | editor:select-word                         | Core
ctrl-shift-down    | editor:add-selection-below                 | Core
ctrl-shift-tab     | pane:show-previous-recently-used-item      | Core
ctrl-t             | editor:transpose                           | Core
ctrl-tab           | pane:show-next-recently-used-item          | Core
shift-cmd-D        | editor:duplicate-lines                     | Core
shift-cmd-L        | editor:split-selections-into-lines         | Core
shift-cmd-T        | pane:reopen-closed-item                    | Core
shift-cmd-enter    | editor:newline-above                       | Core

## Misc

Keystroke    | Command                                | Source
------------ | -------------------------------------- | -------------------
alt-_        | navigation-history:forward             | Navigation History
alt--        | navigation-history:back                | Navigation History
alt-cmd-q    | autoflow:reflow-selection              | Autoflow
alt-g b      | open-on-github:blame                   | Open On GitHub
alt-g c      | open-on-github:copy-url                | Open On GitHub
alt-g g      | open-on-github:repository              | Open On GitHub
alt-g h      | open-on-github:history                 | Open On GitHub
alt-g i      | open-on-github:issues                  | Open On GitHub
alt-g o      | open-on-github:file                    | Open On GitHub
alt-g r      | open-on-github:branch-compare          | Open On GitHub
alt-left     | tree-view:recursive-collapse-directory | Tree View
cmd-.        | key-binding-resolver:toggle            | Keybinding Resolver
cmd-shift-   | tree-view:reveal-active-file           | Tree View
ctrl-alt-b   | atom-beautify:beautify-editor          | Atom Beautify
ctrl-b       | git-blame:toggle                       | Git Blame
ctrl-cmd-g   | find-and-replace:select-all            | Find And Replace
ctrl-cmd-m   | bracket-matcher:select-inside-brackets | Bracket Matcher
ctrl-m       | bracket-matcher:go-to-matching-bracket | Bracket Matcher
ctrl-shift-M | markdown-preview:toggle                | Markdown Preview
f5           | sort-lines:sort                        | Sort Lines
shift-enter  | jumpy:toggle                           | Jumpy
