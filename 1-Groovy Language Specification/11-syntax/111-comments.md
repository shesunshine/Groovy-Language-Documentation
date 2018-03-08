#### 1.1.1. 注释 {#_comments}

##### 单行注释 {#_single_line_comment}

单行注释以`//`开头，可以在行内的任何位置， `//` 之后直到行尾的字符都被认为是注释的一部分。

```java
// 一个单独的单行注释
println "hello" // 注释直到行尾
```

##### 多行注释 {#_multiline_comment}

多行注释以`/*`开头，可以在行中的任何位置。`/*`后面的字符将被视为注释的一部分，包括换行符，直到第一个`*/`关闭注释。多行评论可以放在声明的最后，甚至放在声明之中。

```java
/* 一个单独的跨
    跨两行的多行注释 */
println "hello" /* 声明结尾的一个
                   多行注释 */
println 1 /* 1 */ + 2 /* 2 */
```

##### GroovyDoc注释

与多行注释类似，GroovyDoc注释是多行的，但以`/**`开头并以`*/`结尾。第一个GroovyDoc注释行之后的行可以有选择地以星号`*`开头。这些注释与以下相关：

* 类型定义（类，接口，枚举，注释）
* 字段和属性定义
* 方法定义

尽管编译器不会抱怨GroovyDoc注释与上述语言元素没有关联，您应该在其前面加上注释来预先考虑它们的构造。

```java
/**
 * A Class description
 */
class Person{
    /** the name of the person */
    String name

    /**
     * Creates a greeting method for a certain person.
     *
     * @param otherPerson the person to greet
     * @return a greeting message
     */
    String greet(String otherPerson){
        "Hello ${otherPerson}"
    }
}
```



