# 提纲

1. 对于一个特定的查询，搜索结果排名取决于两种信息：**网页的质量**、**查询与网页的相关程度**。PageRank被用来度量网页质量。
2. PageRank核心思想

	- 如果一个网页被很多其他网页链接到，说明这个网页比较重要，即PageRank值会相对较高；
	- 如果一个PageRank值很高的网页链接到一个其他的网页，那么被链接到的网页的PageRank值会相应地提高。
3. 简单PageRank模型会出现**终止点问题**和**陷阱问题**，解决的方式是**平滑**。
4. 上网者的行为被视为一个马尔科夫过程，所以PageRank的收敛性可以由此证明。

# 详细原理

见这篇文章[**PageRank算法简介及Map-Reduce实现**](http://blog.jobbole.com/71431/)

也可以参考[PageRank算法--从原理到实现](http://www.cnblogs.com/rubinorth/p/5799848.html)