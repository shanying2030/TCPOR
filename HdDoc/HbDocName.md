# 团队文档命名约定

文件命名看似简单，但其实这体现了**你对你的对象在当前体系中的关系/作用的理解**深度，往大了说，命名还直接反映了**你对整个资源结构的理解**。统一的命名规约对团队，尤其对团队知识管理来说非常重要。如果没有一份约定，某人按照自己的想法创建文件将大幅度增加团队成员的协作成本，导致协作体系失效。

## 一、命名原则

- 命名请不要使用汉语命名，目的：
    - 方便同一目录下顺次查找
    -  URL 干净清晰
- 命名尽量**简明**，方法：
    - [采用大驼峰式命名法](https://zh.wikipedia.org/wiki/%E9%A7%9D%E5%B3%B0%E5%BC%8F%E5%A4%A7%E5%B0%8F%E5%AF%AB)，单字之间不以空格断开（例：camel case）或连接号（-，例：camel-case）、下划线（_，例：camel_case）链接。大驼峰式命名法的每一个单字的首字母都采用大写字母，例如：`FirstName`、`LastName`、`CamelCase`。
    - 日期使用6位数字标注，默认忽略年份前两位以减少字符，比如 `151203`（2015年12月3日）。

## 二、命名规则

为便于理解缩写内容，请具体对照查看《[团队文档缩写约定](https://github.com/runwithcc/FirstOfAll/wiki/HbDocShortRule.md)》。

常规命名结构：**文档属性/类别/项目/相对日期/发布者.md**，例如：**LogQAMe0233wd2WCC.md**，表示第23期掌控每一天第四周周三晚上的答疑会记录。

- 文档属性：明确文档属性其实有助于引人思考所建设的内容的整体结构及关联性。这样命名的好处是可以在某一个目录下节省二级目录资源，例如：
    - HbDoc ~ 文档创建规约
    - HbDocName ~ 文档命名规约
    - HbMentor ~ 教练手册
    - HbPM ~ 项目经理手册
- 类别和项目在一定程度上可以进行互换；
- 根据简明原则，在某一个文件夹下，部分内容可以被省略。

## Tips

- 若刚接触这样的命名规约，难免不知所措。不必担心，根据命名猜测文档内容并验证，慢慢就轻车熟路啦。
- 文档命名规则没有对错之分，若单看某个文件名，队友就能明白其中所含内容，协作需要时能即时调取，这就是好规则。

---- 

## ChanegeLog

- 160516 增加内容 by 易仁永澄
