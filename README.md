# test
一个小小的测试，以用来学习使用GitHub  

哈哈哈早上好！  

新的提交，，，

# 信息安全的属性主要有哪几个方面？各个方面什么含义？
1. 完整性：即对抗主动攻击，保证数据的一致性，防止数据被非法用户修改和破坏。
2. 保密性：即对抗被动攻击，保证机密信息不会泄露给非法用户。
3. 可用性：保证合法用户对信息和资源的使用不会被不合理的拒绝。
4. 可控性：是对信息的传播和内容具有控制力的特性。
5. 不可否认性：所有参与者都不可能否认曾经完成的操作和承诺。   


# 掌握DES
## DES的工作模式
## DES的密钥长度
## DES中S盒的工作原理（给出输入能够手算出输出）

# 什么是凯撒密码，具体怎么加解密的（可以手算）
就是移位密码
若 k=3
明文：`a b c d e ...`
密文：`d e f g h ...`  

# 古典密码和现代密码依赖要素有何区别？

# 常见的公钥密码和对称密码体制（分别有哪些）
对称密码体制（单钥密码体制）：是指如果一个系统的加密密钥和解密密钥相同或相近，即密钥是双方共享的，则该系统所采用的就是对称密码体制。（DES算法，IDEA）

非对称密码体制（公钥密码体制）：是指一个加密系统的加密密钥和解密密钥是不同的。一个是公钥用于加密，是公开的；一个是私钥用于解密，是保密的。其中由公钥计算私钥是难解的。（RSA算法，ElGamal算法，椭圆曲线算法）

# 常见公钥密码基于的数学难题有哪些？
* 大数因子分解难解性
* 离散对数难解性
* 椭圆曲线离散对数难解性

# 什么是对称密码和非对称密码？

# 公钥密码怎么实现数字签名？数字签名的作用是什么？

# 对称密码的常见攻击分为哪几类？
* 唯密文攻击
* 已知明文攻击
* 选择明文攻击
* 选择密文攻击


# 什么是数字证书？数字证书的作用是什么？
（证明身份）
证书是证明实体所声明的身份和其公钥绑定关系的一种电子文档，是将公钥和确定属性于它的某些信息（密钥持有者的姓名，电子邮件等）相绑定的数字声明。
通过把要要传输的数字信息进行加密和签名，保证信息传输的机密性，真实性，完整性和不可否认性，从而保证信息的安全传输。

# 什么是数字签名？
数字签名是通过一个单向 Hash 函数对报文进行处理，用以认证报文来源并且核实其是否发 生变化的一个字母数字串，该串被称为消息摘要。  

# 认证的主要目的。

# 什么是PKI？它包含哪几部分？

# 什么是密钥托管？
密钥托管指的是用户向 CA 申请数据加密证书之前，必须把自己的密钥分成t份交给可信赖的t个托管人。任何一个托管人都无法通过自己存储的部分用户密钥来恢复完整的用户密码。只有所有人存储的密钥合在一起才能得到用户的完整密钥。  

# 国际标准化组织在网络安全标准 ISO7498-2 中定义了哪几种层次安全服务，包括哪些?

# 什么是访问控制？包含哪三种要素？
访问控制是指主体依据某些控制策略或权限对客体本身或其资源进行的不同授权访问。访问控制包含的三要素是主体，客体和控制策略。

# 什么是自主访问控制？
自主访问控制允许合法用户以用户或用户组的身份访问策略规定的客体，同时组织非授权用户访问客体，某些用户还可以把自己所拥有的客体访问权限授予其他用户。   

# 从安全模型所控制的对象来看，一般有两种不同的方法来建立安全模型，哪两种？

# 网络攻击的一般过程。
1. 攻击身份和位置隐藏
2. 目标系统信息收集
3. 弱点信息挖掘分析
4. 目标使用权限获取
5. 攻击行为隐藏
6. 攻击实施
7. 开辟后门
8. 攻击痕迹清除


# 什么是防火墙？具有哪些基本功能？

# 什么是拒绝服务攻击（DOS）？
直观的说就是攻击者过多的占用系统资源直到系统繁忙，超载而无法处理正常的工作，甚至导致被攻击的主机系统崩溃。攻击者的目的就是通过攻击使系统无法继续为合法用户提供服务。
# DOS破坏数据的什么安全属性？

# 什么是入侵检测？入侵检测的一般原理？
入侵检测是防火墙之后的第二道安全闸门，可以及时发现内部攻击，外部攻击和误操作，提供系统安全的实时保护。

# 按照信息源划分，入侵检测系统主要分为哪两类？
