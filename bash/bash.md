[[bash]] tips:

1. To use a variable in [[bash]] use dollar sign. `echo "$var"`. Need to use [[curly]] braces when expanding variables in a string e.g. `"${foo}bar"` will expand the variable `foo` as opposed to when using `"$foobar"`, which will expand a variable named `foobar`.
2. `-z` is used to test if a string is null (or empty). Returns True if the [[string]] is empty.
3. to scroll up and scroll down in bash terminal use `shift + page up` and `shift + page down`
4. Use `ctrl + r` to cycle through commands in history
5. create an [[array]] in bash of words: `array=("word1" "word2" "word3")`
6. `"${array[@]}"` this will expand each element of [[array]] into separate word. Double quotes are important. For example:
   ```
   $ x=("hello" "world" "this")
   $ echo $x
   hello
   $ echo "${x[@]}"
   hello world this
   ```
7. Reuse last argument of previous command: `echo !$` 