# Knowledge-relation
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fx-knowledge%2Fknowledge-relation%2Fmaster%2FREADME.md)
```
<details> 
<summary></summary>
custom_mark10
  digraph G {
    size ="4,4";
    main [shape=box];
    main -> parse [weight=8];
    parse -> execute;
    main -> init [style=dotted];
    main -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    main -> printf [style=bold,label="100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare;
    编程语言 -> 计算机科学
    算法 -> 计算机科学
    数据解构 -> 计算机科学
    离散数学 -> 计算机科学
    高等数学 -> 计算机科学
    线性代数 -> 计算机科学
    算法 -> 计算机科学
    算法 -> 计算机科学
    算法 -> 计算机科学
    算法 -> 计算机科学
  }
custom_mark10
</details>
```
