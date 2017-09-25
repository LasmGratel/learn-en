# 绪论

在开始阅读之前, 我强烈建议读者仔细阅读和思考以下几个问题, 你将会有对自己的未来和目标有更深一层的了解, 同时也会使你在学习的道路上更轻松。

## 为什么我要学习英语？

一个老生常谈的问题。你可能认为英语只不过是你在中高考中的**必选科目**而去**被迫**学习。但你现在要做的是转变思路。

> 兴趣是最好的老师。

这句话并不是一句空话。如果你现在还没有对你将来的就业有过一定考虑，或者没有明确你的目标，你最好关闭本文好好思考一下。

那么，你现在已经有了确定的方向和目标了，所以你现在应该有了学习英语的动力。

> 什么？你这不是跟没说一样吗？

如果你还没有想明白这个问题，你需要仔细分析一下。假如你学理，那么大部分的物理、化学、生物等等学科的专业论文和文献都是**英语写的**。

> 那还不简单？我直接找个翻译不就完了。

要知道文献和专著用的词汇都是大学授课英语都不一定学到的专业性词汇，很多时候你需要通过上下文来理解这些词汇的意思。

鄙人学习Java已有3, 4年历史，你可以看一看我平时接触的东西。

例如：一个类型的Javadoc(代码文档):
> public interface Map<K,V>
>
> An object that maps keys to values. A map cannot contain duplicate keys; each key can map to at most one value.
>
> This interface takes the place of the Dictionary class, which was a totally abstract class rather than an interface.
>
> The Map interface provides three collection views, which allow a map's contents to be viewed as a set of keys, collection of values, or set of key-value mappings. The order of a map is defined as the order in which the iterators on the map's collection views return their elements. Some map implementations, like the TreeMap class, make specific guarantees as to their order; others, like the HashMap class, do not.
>
> Note: great care must be exercised if mutable objects are used as map keys. The behavior of a map is not specified if the value of an object is changed in a manner that affects equals comparisons while the object is a key in the map. A special case of this prohibition is that it is not permissible for a map to contain itself as a key. While it is permissible for a map to contain itself as a value, extreme caution is advised: the equals and hashCode methods are no longer well defined on such a map.
>
> All general-purpose map implementation classes should provide two "standard" constructors: a void (no arguments) constructor which creates an empty map, and a constructor with a single argument of type Map, which creates a new map with the same key-value mappings as its argument. In effect, the latter constructor allows the user to copy any map, producing an equivalent map of the desired class. There is no way to enforce this recommendation (as interfaces cannot contain constructors) but all of the general-purpose map implementations in the JDK comply.
>
> The "destructive" methods contained in this interface, that is, the methods that modify the map on which they operate, are specified to throw UnsupportedOperationException if this map does not support the operation. If this is the case, these methods may, but are not required to, throw an UnsupportedOperationException if the invocation would have no effect on the map. For example, invoking the putAll(Map) method on an unmodifiable map may, but is not required to, throw the exception if the map whose mappings are to be "superimposed" is empty.
>
> Some map implementations have restrictions on the keys and values they may contain. For example, some implementations prohibit null keys and values, and some have restrictions on the types of their keys. Attempting to insert an ineligible key or value throws an unchecked exception, typically NullPointerException or ClassCastException. Attempting to query the presence of an ineligible key or value may throw an exception, or it may simply return false; some implementations will exhibit the former behavior and some will exhibit the latter. More generally, attempting an operation on an ineligible key or value whose completion would not result in the insertion of an ineligible element into the map may throw an exception or it may succeed, at the option of the implementation. Such exceptions are marked as "optional" in the specification for this interface.
>
> Many methods in Collections Framework interfaces are defined in terms of the equals method. For example, the specification for the containsKey(Object key) method says: "returns true if and only if this map contains a mapping for a key k such that (key==null ? k==null : key.equals(k))." This specification should not be construed to imply that invoking Map.containsKey with a non-null argument key will cause key.equals(k) to be invoked for any key k. Implementations are free to implement optimizations whereby the equals invocation is avoided, for example, by first comparing the hash codes of the two keys. (The Object.hashCode() specification guarantees that two objects with unequal hash codes cannot be equal.) More generally, implementations of the various Collections Framework interfaces are free to take advantage of the specified behavior of underlying Object methods wherever the implementor deems it appropriate.
>
> Some map operations which perform recursive traversal of the map may fail with an exception for self-referential instances where the map directly or indirectly contains itself. This includes the clone(), equals(), hashCode() and toString() methods. Implementations may optionally handle the self-referential scenario, however most current implementations do not do so.

想好了吗？这就是你将来要接触的**实战**英语，而不是简简单单给你一道两道阅读题就完事的。本教程的目标，就是**使你在不借助任何工具书和翻译的情况下**(除了Wikipedia, 用来查这些东西都是干啥的)**让你在2分钟之内了解这种长难文章的意思。**

## 既然如此，我该如何学习英语？

现在你已经有了学习英语的动力。那么我还是要说一句老生常谈的话：

> 实践出真知。

学习一门外语最好的方法，就是日常使用这门外语。每天40/45分钟的英语课对于学习语言来说真的太短，并且几乎没有锻炼你真正去使用的能力。

在这里推荐几个网站：

[Reddit - 外国的百度贴吧](https://www.reddit.com)

[Quora - 外国的知乎](https://www.quora.com)

你需要锻炼的，是**不假思索说出英文的能力，就像说中文一样**，而不是在大脑里经过中文的翻译。

举个例子，你在街上碰到一家水果摊，摆着一些苹果。

看到苹果，你的大脑会立刻给你反应两个信息：Apple和苹果，而不是先给你反应苹果，再经过翻译一下想到Apple。专业一点就叫一个反射弧的建立。

那么，你现在想询问价格。这时候你的大脑应该给你反应出：这个苹果多少钱？和How much are they?

当然，对于一个外语初学者来说做到这一点很不容易，也比较辛苦。但当你某一天突然产生了能同时说英语和中文的冲动的时候，那种喜悦是溢于言表的。

最后，学习英语没有任何捷径。如果你想躺着就能学好英语的话，

**咋不懒死你呢？**

> 书山有路勤为径，学海无涯苦作舟。

与君共勉。