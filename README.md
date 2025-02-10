# zed-helix-keymap

A repo to collaborate on building a helix keymap for the zed editor.

I'd like this repo to have:

* The best helix keymap for zed so far
* A listing of helix keymap features, mirroring the offical helix docs, tracking which features are implemented so far and the eqivalent command in zed
* A listing of features needed in zed to get more complete support for helix keybindings

Feel free open a PR if you have a moment to add something!

## Resources

* [Helix Keymap documentation](https://docs.helix-editor.com/keymap.html)
* [keymap.md documentation source file](https://github.com/helix-editor/helix/blob/master/book/src/keymap.md?plain=1)

## Keymap

### Normal mode

#### Movement

| Key                   | Description                                        | Helix Command               | Zed Command |
| -----                 | -----------                                        | -------                     | ----------- |
| `h`, `Left`           | Move left                                          | `move_char_left`            | ⏳           |
| `j`, `Down`           | Move down                                          | `move_visual_line_down`     | ⏳           |
| `k`, `Up`             | Move up                                            | `move_visual_line_up`       | ⏳           |
| `l`, `Right`          | Move right                                         | `move_char_right`           | ⏳           |
| `w`                   | Move next word start                               | `move_next_word_start`      | ⏳           |
| `b`                   | Move previous word start                           | `move_prev_word_start`      | ⏳           |
| `e`                   | Move next word end                                 | `move_next_word_end`        | ⏳           |
| `W`                   | Move next WORD start                               | `move_next_long_word_start` | ⏳           |
| `B`                   | Move previous WORD start                           | `move_prev_long_word_start` | ⏳           |
| `E`                   | Move next WORD end                                 | `move_next_long_word_end`   | ⏳           |
| `t`                   | Find 'till next char                               | `find_till_char`            | ⏳           |
| `f`                   | Find next char                                     | `find_next_char`            | ⏳           |
| `T`                   | Find 'till previous char                           | `till_prev_char`            | ⏳           |
| `F`                   | Find previous char                                 | `find_prev_char`            | ⏳           |
| `G`                   | Go to line number `<n>`                            | `goto_line`                 | ⏳           |
| `Alt-.`               | Repeat last motion (`f`, `t`, `m`, `[` or `]`)     | `repeat_last_motion`        | ⏳           |
| `Home`                | Move to the start of the line                      | `goto_line_start`           | ⏳           |
| `End`                 | Move to the end of the line                        | `goto_line_end`             | ⏳           |
| `Ctrl-b`, `PageUp`    | Move page up                                       | `page_up`                   | ⏳           |
| `Ctrl-f`, `PageDown`  | Move page down                                     | `page_down`                 | ⏳           |
| `Ctrl-u`              | Move cursor and page half page up                  | `page_cursor_half_up`       | ⏳           |
| `Ctrl-d`              | Move cursor and page half page down                | `page_cursor_half_down`     | ⏳           |
| `Ctrl-i`              | Jump forward on the jumplist                       | `jump_forward`              | ⏳           |
| `Ctrl-o`              | Jump backward on the jumplist                      | `jump_backward`             | ⏳           |
| `Ctrl-s`              | Save the current selection to the jumplist         | `save_selection`            | ⏳           |

#### Changes

⏳

##### Shell

⏳

#### Selection manipulation

⏳

#### Search

⏳

#### Minor modes

⏳

##### View mode

⏳

##### Goto mode

⏳

##### Match mode

⏳

##### Window mode

⏳

##### Space mode

⏳

###### Popup

⏳

###### Completion Menu

⏳

###### Signature-help Popup

⏳

##### Unimpaired

⏳

### Insert mode

⏳

### Select / extend mode

⏳

### Picker

⏳

### Prompt

⏳
