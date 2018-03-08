#### 1.1.1. 注解 {#_comments}

##### 单行注解 {#_single_line_comment}

Single line comments start with `//` and can be found at any position in the line. The characters following `//`, till the end of the line, are considered part of the comment.

```java
// a standalone single line comment
println "hello" // a comment till the end of the line
```

##### Multiline comment {#_multiline_comment}

A multiline comment starts with `/*` and can be found at any position in the line. The characters following `/*` will be considered part of the comment, including new line characters, up to the first `*/` closing the comment. Multiline comments can thus be put at the end of a statement, or even inside a statement.

