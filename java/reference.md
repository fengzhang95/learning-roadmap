## reference

java的引用类型分为四种类型

* 强
* 软
* 弱
* 虚



强引用就是正常的引用, object obj = new object();



软引用，内存不足，要发生oom的时候，会把相应的内存回收掉

弱引用，下次gc的时候，如果只有这个弱引用ref指向这个对象，就会被回收掉





最近总是被负面情绪缠身，一方面叹息自己在目前这个公司的工资估计垫底，工作内容不太喜欢，每天陷入一种想辞职的状态，想要去深造，想要去读phd，可是自己无论经济情况还是学习能力又不支持我这么做；

另一方面，作为一个转行人员，能走到这一步自己感觉也很不容易，非常矛盾。

在网上看别人的博客，总是觉得人家的技能水平很高，写作能力很强，对自己也是一种挺严重的打击。

时常在想以后该怎么办，以后的出路在哪，又会安慰自己说，路还长，慢慢找，很多人还不如你呢，可是自己的目标也不明确，