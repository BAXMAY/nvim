# Keymap

## Leader key

leader key is set to <kbd>Space</kbd>.

## Navigation

```text
Basic movement

  ^
  k
<h l>
  j
```

| Keymap           | Function                              |
|------------------|---------------------------------------|
| <kbd>H</kbd>     | Go to the first character of the line |
| <kbd>L</kbd>     | Go to the last character of the line  |
| <kbd>J</kbd>     | Go down 5 lines                       |
| <kbd>K</kbd>     | Go up 5 lines                         |
| <kbd>W</kbd>     | Go 5 words forward                    |
| <kbd>B</kbd>     | Go 5 words backward                   |
| <kbd>Up</kbd>    | Go to the window above                |
| <kbd>Down</kbd>  | Go to the window below                |
| <kbd>Right</kbd> | Go to the right window                |
| <kbd>Left</kbd>  | Go to the left window                 |

## Search

| Keymap         | Function                    |
|----------------|-----------------------------|
| <kbd>-</kbd>   | Go to the before matches    |
| <kbd>=</kbd>   | Go to the following matches |
| <kbd>ESC</kbd> | Close the search highlight  |

## Tabpages

| Keymap              | Function               |
|---------------------|------------------------|
| <kbd>Ctrl-t h</kbd> | Go to the previous tab |
| <kbd>Ctrl-t l</kbd> | Go to the next tab     |
| <kbd>Ctrl-t n</kbd> | Create new tab         |

## Copy and Paste

| Keymap            | Function                 | notes                     |
|-------------------|--------------------------|---------------------------|
| <kbd>y</kbd>      | Copy to register         |                           |
| <kbd>p</kbd>      | Paste from the register  |                           |
| <kbd>Ctrl-p</kbd> | Paste from the clipboard | In normal and insert mode |
| <kbd>Ctrl-y</kbd> | Copy to clipboard        | Only in visual mode       |

## Text move

| Keymap       | Function                 | notes                        |
|--------------|--------------------------|------------------------------|
| <kbd><</kbd> | Reduce one indent level  | In normal and selection mode |
| <kbd>></kbd> | Increse one indent level | In normal and selection mode |

## Save and Quit

| Keymap           | Function              | Notes                |
|------------------|-----------------------|----------------------|
| <kbd>; w</kbd>   | save                  |                      |
| <kbd>Alt q</kbd> | delete buffer         |                      |
| <kbd>Alt ;</kbd> | Leave the insert mode | Only in insert mode  |

## Others

| Keymap            | Function                       |
|-------------------|--------------------------------|
| <kbd>Ctrl-z</kbd> | Reverse changes                |
| <kbd>;</kbd>      | Call the command line directly |
