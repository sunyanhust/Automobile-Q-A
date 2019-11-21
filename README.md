# Automobile-Q-A
## 汽车大师问答摘要与推理
### 根据车主与技师问答得出Report
### 例如：
- Brand：雪佛兰
- Model：科鲁兹
- Question：科鲁兹变速箱旁边漏机油
- Dialogue：
  - 技师说：具体是哪个部位呢？是发动机和变速器正中间位置吗？
  - 车主说：[图片]
  - 技师说：这个有拍的图片吗？
  - 车主说：就是中间
  - 车主说：上面的图片就是
  - 技师说：图片上已经看见了，检查机油有没有缺少的情况吧，看见好像是变速器的油。
  - 车主说：如果是变速器漏油 应该是哪里出来问题
  - 车主说：机油不少
  - 技师说：那就是变速器的油，那就要拆开检查一下这个变速器的一轴，有可能是油封出现的路由或者是里面的这个，你这个是自动变速器，自动变速器，还要检查一下这个，中间的传动机构，液压变距器是不是有漏油的情况？
  - 车主说：我这个是手动挡的
  - 车主说：1.6
  - 技师说：手动挡就是变速器的一轴油封出现了漏油。
  - 车主说：需要抬变速箱吗？ 工程量大不大
  - 技师说：这个肯定要拆变速箱才能换，液压离合器分泵，没有问题吧，都正常吧，刹车油不缺少吧
  - 车主说：都正常
  - 技师说：那就得拆变速器了，大概需要半天的时间。
  - 车主说：确定不是机油吗？ 这个是在外面修 还是4S 比较好
  - 车主说：算不算大问题
  - 车主说：紧一下旁边的螺丝有没有用
  - 技师说：机油不缺少，那就不是漏的机油，因为这个地方有两个油封一个事，发动机的曲轴后油封，这个也容易漏机油，第二个就是变速器的一轴油封这个也是容易漏油的，不管是，哪个有问题，只要是这两个问题都要拆变速箱。
  - 车主说：暂时不修有没有什么大影响|技师说：这个去外面修理厂就可以维修，手动挡的话，比较好拆卸。暂时不维修的话也可以，他只是往出渗油检查一下变速器油有没有短缺的。
  - 车主说：好的 如果拆下来方便同时把这两个隐患都修了吗|技师说：是的，拆下来看哪个损坏维修，哪个不坏的话就不需要动它。
  - 车主说：好的谢谢你|
  - 技师说：不客气！祝您用车愉快！
### 得出Report如下：
- 像这种情况的话，如果机油不缺少，应该就是变速器的一轴油封有漏油的情况，需要拆下来检查一下，把这两个油封最好都检查一下，如果出现问题直接更换就可以。