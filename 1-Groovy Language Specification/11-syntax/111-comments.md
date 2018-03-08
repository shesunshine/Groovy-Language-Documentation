#### 1.1.1. 注释 {#_comments}

##### 单行注释 {#_single_line_comment}

单行注释以`//`开头，可以在行内的任何位置， `//` 之后直到行尾的字符都被认为是注释的一部分。

```java
// a standalone single line comment
println "hello" // a comment till the end of the line
```

##### 多行注释 {#_multiline_comment}

多行注释以`/*`开头，可以在行中的任何位置。`/*`后面的字符将被视为注释的一部分，包括换行符，直到第一个`*/`关闭注释。多行评论可以放在声明的最后，甚至放在声明之中。

```java
/* a standalone multiline comment
    spanning two lines */
println "hello" /* a multiline comment starting
                   at the end of a statement */
println 1 /* one */ + 2 /* two */
```

##### GroovyDoc注释

与多行注释类似，GroovyDoc注释是多行的，但以`/**`开头并以`*/`结尾。第一个GroovyDoc注释行之后的行可以有选择地以星号`*`开头。这些注释与以下相关：

* 类型定义（类，接口，枚举，注释）
* 字段和属性定义
* 方法定义



