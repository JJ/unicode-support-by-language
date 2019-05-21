# Unicode support by programming language

This is intended to be a user-editable list of support of Unicode
features by language. Just do PR and add a row, or maybe a column if
you find something missing. If possible, put a link to the place where
that feature is described or an example. In principle, you should
include a language if it includes it in the core or core libraries. If
you want to add something that needs an installable library, it's your
call.


| Language                 | Native unicode strings | Unicode variable names | Unicode in (other) identifiers | Support for unicode digits | Unicode in regexes (TR18) | Unicode normalization |
|:------------------------:|:----------------------:|:----------------------:|:------------------------------:|:--------------------------:|:-------------------------:|:---------------------:|
| [Perl 6](https://perl6.org)      | ✓     | ✓                             | ?                        | ✓     | ✓     |  ✓     |
| [Scala](https://scala-lang.org/) | ✓     | ✓ <sup id="a1">[1](#f1)</sup> | ✓ <sup>[1](#f1)</sup>    | ?     | ✓     |  ✓     |



<b id="f1">1</b> By using a backtick `` ` `` as an escape around the variable name. e.g. ``val `😽` = "🐈" ``. [↩](#a1)
