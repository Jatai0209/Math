# ch02-Groups



**associative law**

$$(x+y)+z = x+(y+z)$$

$$(xy)z=x(yz)$$

**commutation law**

$ab=ba$

The associative law is more fundamental than the commutative law,one reason for this is that composition of functions. 复合函数其实就是 结合律的 利用。



#### identity element

定义：**集合$S$中任一元素$x \in S$ ，在进行某种二元运算时，存在且唯一的一个 元素$e \in S$ 可使得 结果还是 x. e就叫做单位元。**



#### inverse element

定义: **对任意一个元素x, $\forall x \in G$，在进行某种二元运算时， 存在且唯一的一个 元素$? \in G$，使得结果等于 $e$, 则这个元素$?$ 叫做 元素$x$ 关于该二元运算的 逆元素(inverse element), 简称逆元。**



#### 01.Group

**Definition：A group is a set G together with a law of composition which is associative and has an identity element, and such that every element of G has an inverse.**



一些性质Proposition:

1. 任意一个群的单位元唯一。
2. 任意一个群的元素的逆元唯一。
3. 设$G$ 为一个群，对于任意给定的元素$a,b \in G$,有 $(ab)^{-1}=b^{-1}a^{-1}$



如果一个群 还满足 交换律-**commutative law**，就叫做 **abelian 阿尔尔群**



**symmetric group-对称群**：其中的元素是 一个集合 set{1,2, ..., n}中的 所有 置换操作。

$S_n=$ group of permutations of {1,2,...,n}.

因为 n 种元素具有 n! 种置换组合，所以 这个群 含有 n! 个元素。同时我们叫 n! 是这个群的秩-order。

对称群的 子群 是 置换群。

> 置换不能理解的话，可以看看《抽象代数-谢邦杰》第1章第5节n阶置换



#### 02.Subgroups

其他定义和群一样，只是不要求必须包含 associative law.

1. 运算封闭
2. 包含单位元
3. 任一元素都含有 逆元



每个群都含有2个很明显的子群，一个是自己，一个是 只含有 单位元的 子群。



**cyclic group 循环群**



The order of any group $G$ is the number of its elements. We will often denote the order by:

$|G| = $ number of elements of $G$.

the order may be infinite.



klein four group 克莱因四元群,最小的非循环群.

quaternion group 四元数群



#### 03.Isomorphisms 同构

isomorphic groups 同构群 的性质Proposition:

1. 从group A映射到group B, 而 group A 的 set A 和 group B 的 set B 是不同的。简单说这个映射是$setA \rightarrow  setB$, 而在一个群里面，比如 group A里，操作符对应的映射是$setA \rightarrow  setA$。
2. 映射满足如下($\circ $ 代表操作符，可能是+，*,第1个$\circ$与第2个$\circ$可以不相同)：$\varphi(a\circ b)=\varphi(a)\circ \varphi(b)$，for all $a,b \in G$
3. 同构和同态比只是多了一个双射(bijective correspondence)的要求



Two groups G and G' are called isomorphic if there exists an isomorphism $\varphi  :G\rightarrow G'$. We will sometimes indicate that two groups are isomorphic by the symbol $\approx $:

$$G \approx  G' \ means \ G \ is \ isomorphic \ to \ G'$$



**automorphism 自同构**：

 $\varphi  :G\rightarrow G$. 



**conjugate 共轭：**

Definition: 设 G 是一个群，$a,b \in G$, 如果存在 $g \in G$ 满足 $a = gbg^{-1}$, 那么 a, b共轭。

比如矩阵里面的相似矩阵



#### 04.Homomorphisms 同态

群同态

相比于群同构，同态只是: $\varphi $ is not assumbed to be bijective here.

比如：

矩阵的行列式 到 实数的映射，而实数 逆向 回去 到行列式 会有无穷种组合，这种一对多就不满足映射的定义了。





#### 05.Equivalence relations and partitions 等价关系和区分

划分的定义：

如果$S$不是一个空集并且可以写成一系列互相之间不相交的子集的并，那么我们说这些子集构成了$S$的一个划分。





#### 06.Cosets 陪集



07.restriction of a homomorphism to a subgroup 约束同态到一个子群











---

巴拿赫-塔斯基悖论