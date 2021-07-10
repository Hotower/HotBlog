# RDL Introduction

**RDL** is a marking language that is easier than HTML but more complex than MarkDown. For example:

```RDL
h1\Is Me Show Successfully?\a\Hotower on github\https://github.com/Hotower\p\Nice Done!
```

A RDL is consist of lists of elements. Every part is seperated by '|'. An element of RDL is start from an element class name. Most of the class name is the same as in HTML, while some is different.

| RDL       | HTML                                                                   | MarkDown     |
| --------- | ---------------------------------------------------------------------- | ------------ |
| []\\ABC   | `<p><input type="checkbox" disabled="disabled">ABC</p>`                | `- [ ] ABC`  |
| [x]\\ABC  | `<p><input type="checkbox" checked="true" disabled="disabled">ABC</p>` | `- [x] ABC`  |
| a\url\ABC | `<a href="url">ABC</a>`                                                | `[url](ABC)` |
| i\url     | `<img src="url">`                                                      | `![](url)`   |
| \         | `<br>`                                                                 |              |
| X\ABC     | `<X>ABC</X>`                                                           |              |


