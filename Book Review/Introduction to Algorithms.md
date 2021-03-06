# 算法导论-读后感  [Progress](https://github.com/WindRunnerCackerChen/Coding-Game-Story  "进度") 

## 第五章  概率分析和随机算法
>2017/12/13 18：35 <b>计数与概率</b><br>


## 第二章  算法基础

>2017/12/10 14:45 <b>伪代码中的一些约定</b><br>
>*  <b>缩进表示块结构</b>：<em>缩进风格适用于  <b>For</b>循环体、<b>if-else</b>语句。采用缩进来替代常规的块结构标志，如  <b>begin</b>、<b>end</b>语句，可以大大提高代码的<b>清晰度</b></em><br>
>*  <b>具有类似解释</b>：<em>当一个  <b>For</b>循环每次迭代增加其循环计数器时，使用关键字  <b>to</b>。当一个  <b>For</b>循环每次迭代减少其循环计数器时，使用关键字  <b>downto</b>。当循环计数器以大于1的一个量改变时，该改变量跟在可选关键字  <b>by</b>之后</em><br>
>><em><b>1</b>. 符号“<b>//</b>”表示该行后面部分是个注释。<br>
>><b>2</b>. 形如 <b>i=j=e</b>的多重赋值将表达式e的值赋给变量  <b>i</b>和 <b>j</b>；它应被处理成等价于赋值  <b>j=e</b>后跟者赋值 <b>i=j</b><br>
>><b>3</b>. 变量（如  <b>i</b>、<b>j</b>和  <b>key</b>）是局部于给定过程的。若无显式说明，我们不使用全局变量<br>
>><b>4</b>. 数组元素通过“数组名  <b>[</b>下标  <b>]</b>”这样的形式来访问，“<b>..</b>”表示省略中间下标<br>
>><b>5</b>. 复合数据通常被组织成<b>对象</b>，对象又由<b>属性</b>组成，表示数组对象或对象的变量<b>等价于</b>指向数组或对象的数据的一个指针，当指针不指向任何对象，我们赋给它特殊值<b>NIL</b><br>
>><b>6</b>. <b>按值</b>把参数传递给过程，数组通过指针来传递，结果指向数组的一个指针被传递，而不是整个数组，单个数组元素的改变对调用过程是可见的<br>
>><b>7</b>. 一个<b>return</b>可以返回多个值，并立即将控制返回到调用过程的调用点<br>
>><b>8</b>. 布尔运算符 “<b>and</b>”和  “<b>or</b>”都是  <b>短路</b>的<br>
>><b>9</b>. 关键词 <b>error</b>表示因为已被调用的过程情况不对而出现的一个错误<br>
</em>

>2017/12/10 14:29 <b>循环不变式与插入排序的正确性</b>——<em>循环不变式主要用来帮助我们理解算法的正确性。关于循环不变式，我们必须证明三条性质</em><br>
>* <b>初始化</b>：循环的第一次迭代之前，它为真<br>
>* <b>保持</b>：如果循环的某次迭代之前它为真，那么下次迭代之前它仍为真<br>
>* <b>终止</b>：在循环终止时，不变式为我们提供一个有用的性质，该性质有助于证明算法是正确的<br>

## 第一章  算法在计算机中的作用

>2017/12/9 22:40 正如我们对插入排序和归并排序的比较中所看到的，正是在较大问题规模时，算法之间效率的差别才变得特别显著
