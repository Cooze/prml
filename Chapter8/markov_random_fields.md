我们已经看到有向图模型表示将一组变量上的联合概率分布分解为局部条件概率分布的乘积的一种分解方式。有向图模型也定义了一组条件独立性质，根据图进行分解的任何概率分布都必须满足这些条件独立性质。我们现在考虑图模型的第二大类，使用无向图描述的图模型。与之前一样，它表示一个分解方式，也表示一组条件独立关系。     

一个马尔科夫随机场（Markov random field），也被称为马尔科夫网络（Markov network）或无向图模型（undirected graphical model）（Kindermann and Snell, 1980），包含一组结点，每个结点都对应着一个变量或一组变量。链接是无向的，即不含有箭头。在无向图的情形中，首先讨论条件独立性质是比较方便的。
