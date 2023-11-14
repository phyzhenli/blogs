1. `grep`跨行匹配 https://stackoverflow.com/questions/12652568/how-to-give-a-pattern-for-new-line-in-grep

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `grep -zoP '.*\nERROR.*'` 可以匹配包含`ERROR`的一行和上一行。
