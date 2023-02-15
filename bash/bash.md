[[bash]] tips:

1. To use a variable in [[bash]] use dollar sign. `echo "$var"`. Need to use [[curly]] braces when expanding variables in a string e.g. `"${foo}bar"` will expand the variable `foo` as opposed to when using `"$foobar"`, which will expand a variable named `foobar`.
2. `-z` is used to test if a string is null (or empty). Returns True if the [[string]] is empty.
3. to scroll up and scroll down in bash terminal use `shift + page up` and `shift + page down`
4. Use `ctrl + r` to cycle through commands in history