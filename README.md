# 【处方】屏蔽个推SDK产生的交叉唤醒

阻断集成个推Push SDK的应用之间的相互唤醒，不影响应用自身的推送功能。

注：此处方演示了一个单纯按照组件的类名（不含intent-filter）跨应用匹配的例子，需要绿色守护（Greenify）3.3以上版本支持。
