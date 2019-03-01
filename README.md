# google-java-format-with-options

This is a fork of the https://github.com/google/google-java-format that allows tab and line width to be set.

Specifically, the tab width can be set as a multipler of the standard 2 spaces using a system property as follows:
```
-Dcom.google.googlejavaformat.java.JavaFormatterOptions.indentationMultiplier=2
```
That will set it to 2 times the two standard spaces, thus 4.

The line width can be overriden as follows:
```
-Dcom.google.googlejavaformat.java.JavaFormatterOptions.maxLineLength=120
```
That will set the maximum standard line width to 120 characters.

Otherwise this is trying to leave the original unmodified and follows all other rules and recommendations.
All instructions and licences from there apply here as well.
