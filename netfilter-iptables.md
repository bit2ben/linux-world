### iptables
### 三个问题
* what?
firewall是什么？
* why?
为什么要用firewall?
* how?
firewall原理
### netfilter/iptables与商业firewall的对比
### netfilter/iptables的功能与性能？
### 如何评价netfilter的性能？
### iptables的操作（运维成本与学习成本）

### iptables基础
* chain concept
匹配规则，执行对应动作。
多条规则构成链
* 5个关卡
  * prerouting
  * input 
  * output
  * forward
  * postrouting
 * table concept
   * filter
   * nat
   * mangle
   * raw
 * 表链关系
   * 实际使用时通过表作操作入口，对规则进行定义。
   * 各种表的优先级
 * 数据经过firewall的流程
 
 

