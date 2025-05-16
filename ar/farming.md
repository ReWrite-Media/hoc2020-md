### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# بناء المزرعة

## الخطوة الأولى
عرض القرويون تعليم الأشرار كيفية الزراعة، لكنهم بحاجة إلى المساعدة في تجهيز الأرض. اجعل الروبوت يحرث أول صفين من التربة.

#### ~ tutorialhint 
استخدم الكتلة ``||hoc2020:حرث وتحريك||`` لتقوم بحرث كتلة التربة أسفل الروبوت، ثم يتحرك إلى الأمام. استخدم الكتلة ``||hoc2020:تحريك الروبوت||`` ليتحرك الروبوت في الاتجاه الذي تحدده استخدم الكتلة ``||hoc2020:تدوير الروبوت||`` ليستدير الروبوت إما إلى اليمين أو لليسار 

```ghost
    hoc2020.tillSoil(0)
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.turnAgent(TurnDirection.Left)  
```
```template
//
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts#v0.5.2
```