sic File Operations
1. **`:e filename`** - Open a file.
2. **`:w`** - Save the current file.
3. **`:q`** - Quit Vim.
4. **`:wq`** - Save and exit.
5. **`:n`** - Go to the next buffer (when multiple files are open).
6. **`:N`** - Go to the previous buffer.
7. **`:b filename`** - Switch buffer (use `:ls` to list buffers).
8. **`:ls`** - List open buffers.

## Movement
9. **`h`** - Move left.
10. **`l`** - Move right.
11. **`j`** - Move down.
12. **`k`** - Move up.
13. **`O`** - Open a new line above the current line.
14. **`$`** - Move to the end of the line.
15. **`gg`** - Go to the beginning of the file.
16. **`G`** - Go to the end of the file.
17. **`Ctrl-d`** - Move half a page down.
18. **`Ctrl-u`** - Move half a page up.

## Insert Mode
19. **`i`** - Insert before the cursor.
20. **`I`** - Insert at the beginning of the line.
21. **`a`** - Insert after the cursor.
22. **`A`** - Insert at the end of the line.
23. **`o`** - Open a new line below the current line.

## Editing Text
24. **`dd`** - Delete the current line.
25. **`yy`** - Yank (copy) the current line.
26. **`p`** - Paste after the cursor.
27. **`u`** - Undo the last change.
28. **`Ctrl-r`** - Redo the undone change.
29. **`/pattern`** - Search forward for a pattern.
30. **`?pattern`** - Search backward for a pattern.
31. **`n`** - Repeat search in the same direction.
32. **`N`** - Repeat search in the opposite direction.

## Replace and Substitution
33. **`:%s/old/new/g`** - Replace all occurrences of `old` with `new`.
34. **`:3,10s/^/ /g`** - Add spaces at the beginning of lines 3 to 10.
35. **`:%s/^/hello/g`** - Add the word "hello" at the beginning of every line.
36. **`:%s/^hai/hello/g`** - Replace "hai" with "hello" at the beginning of lines.

## Miscellaneous
37. **`esc`** - Exit insert mode and return to normal mode.
38. **`vim filename`** - Open or create a file in Vim.
39. **`vim`** - Open Vim without a file.
40. **`Ctrl-v`** - Enter visual block mode.
41. **`Shift + ~`** - Toggle between lowercase and uppercase.
42. **`dw`** - Delete a word.
43. **`cw`** - Change a word (go to insert mode).
44. **`.`** - Repeat the last change.

## Line Number Operations
45. **`G`** - Go to a specific line number.
46. **`:se nu` or `:set number`** - Show line numbers.
47. **`:se nonu` or `:set nonumber`** - Hide line numbers.

## Deleting Text
48. **`x`** - Delete the character under the cursor.
49. **`X`** - Delete the character before the cursor.
50. **`D` or `d$`** - Delete from the cursor to the end of the line.
51. **`d0`** - Delete from the cursor to the beginning of the line.
52. **`dG`** - Delete from the cursor to the end of the file.
53. **`dgg`** - Delete from the cursor to the beginning of the file.
54. **`d/word`** - Delete until the next occurrence of "word".
55. **`:3,7d`** - Delete lines 3 through 7.
56. **`:1,$d`** - Delete all lines from the start to the end of the file.
