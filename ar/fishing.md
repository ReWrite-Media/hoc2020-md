### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# بناء المرسى

## الخطوة الأولى
قم ببناء الحواف الخارجية لمرسى بحري يبلغ طوله 6 كتل وعرضه 4 كتل. (تلميح: ارسم صورة للمرسى قبل أن تبدأ!)

#### ~ tutorialhint 
استخدم الكتلة ``||hoc2020:تحريك ووضع||`` ليتحرك الروبوت للأمام ثم يضع لوح خشب أسفله استخدم الكتلة ``||hoc2020:تحريك الروبوت||`` ليتحرك الروبوت في الاتجاه الذي تحدده استخدم الكتلة ``||hoc2020:تدوير الروبوت||`` ليستدير الروبوت إما إلى اليمين أو لليسار 

```ghost
    hoc2020.placePlanks(0)
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.turnAgent(TurnDirection.Left)  
```
```template
//
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts#v0.5.2
```