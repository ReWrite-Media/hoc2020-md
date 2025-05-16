### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# احمِ البنجر

## الخطوة الأولى
يبدو أن شيئا ما يدخل الحديقة ويأخذ البنجر. اجعل الروبوت يبني سياجا حول المزرعة لحماية الشمندر.

#### ~ tutorialhint 
استخدم الكتلة ``||hoc2020:وضع القضبان الحديدية للأسفل||`` ليتمكن الروبوت من و ضع القضبان الحديدية. استخدم الكتلة ``||hoc2020:تحريك الروبوت||`` ليتحرك الروبوت في الاتجاه الذي تحدده استخدم الكتلة ``||hoc2020:تدوير الروبوت||`` ليستدير الروبوت إما إلى اليمين أو لليسار استخدم الكتلة ``||hoc2020Different:تكرار||`` لتكرار مجموعة من الكتل عدة مرات


```ghost
    hoc2020.placeFence()
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.turnAgent(TurnDirection.Left)  
    hoc2020Different.customRepeatLoop(0, () => {})
```
```template
//
```
```package
hoc2020-ts-ar=github:rewrite-media/hoc2020-ts-ar
```