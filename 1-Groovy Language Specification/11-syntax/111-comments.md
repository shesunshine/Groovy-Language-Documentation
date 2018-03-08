#### 1.1.1. 注释 {#_comments}

##### 单行注释 {#_single_line_comment}

单行注释以**`//`**开头，可以在行内的任何位置， `//` 之后直到行尾的字符都被认为是注释的一部分。

```java
// a standalone single line comment
println "hello" // a comment till the end of the line
```

##### 多行注释 {#_multiline_comment}

多行注释以`/*`开头，可以在行中的任何位置。`/*`后面的字符将被视为注释的一部分，包括换行符，直到第一个`*/`关闭注释。多行评论可以放在声明的最后，甚至放在声明之中。

```
/* a standalone multiline comment
    spanning two lines */
println "hello" /* a multiline comment starting
                   at the end of a statement */
println 1 /* one */ + 2 /* two */
```





