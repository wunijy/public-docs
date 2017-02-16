#### 场景二：某电商平台的支付转化率的分析

提升购买率的第一步在于刺激用户购买的欲望，而第二步则是确保用户能够成功完成订单的支付，为企业产生盈利。还是以某电商为例子，通过对于购买流程的数据分析发现，用户从提交订单到完成订单的支付的平均转化率仅为10%左右。基于这个事实，我们可以提问：用户为什么在这一步中流失？如何流失的？

此时我们先通过用户分群，筛选出在支付流程中流失的所有用户，再通过“用户细查”来观察用户在支付流程中的交互行为。

通过查看一些用户的访问轨迹，我们发现了一个常见的行为模式。下图为一个典型用户的行为轨迹，该用户提交完订单之后进入支付选择页面，用户首先选择支付宝的支付方式后，进入支付宝二维码的扫码页面后，平台提示用户使用支付宝支付方式会扣除1%的手续费，于是用户退出该支付方式，同样，选择微信支付也是一样，到最后用户选择银联支付，先是进入银联支付的个人信息和身份证的信息填写页面后，这部分用户停留时间比较长，而且有两次用户打开这个页面之后直接跳出，到第三次的时候才填写该银行的支付信息，点击下一步准备进入银行的手机验证码页面，经过冗长的流程之后才完成的订单支付。如此反复三次，并且每次在产品页面产生的事件内容都有差异。而用户在这个过程中花费很多时间。

结合这个电商平台的产品形态，我们可以进一步分析该用户的行为。支付选择页面上，免手续费的需要用户选择支付方式、填写银行卡信息、验证手机号码等，而快捷支付方式（微信和支付宝）要收1%手续费。该用户在支付选择页面反复访问，最后才决定在银联页面填写个人银行卡的信息，并且填写的时间很长，由此我们可以猜测：用户在进入支付选择的页面后，想要选择便捷的支付方式，但便捷的支付方式需要收1%的手续费，于是用户放弃两种便捷的支付方式，转而去选择流程冗长的银联支付方式，经过较长的一段时间操作之后，才完成订单的支付。在这个过程中用户是非常有耐心，但我们看到绝大部分用户是没有耐心的，最终没有完成支付就离开了。

由此，建议在后续产品的优化中，在支付选择页面上免除快捷支付的手续费，同时简化银联支付的流程，优化产品体验，从而提高最终的购买转化率。