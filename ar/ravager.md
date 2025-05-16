### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# قدم المدمر

## الخطوة الأولى
ساعد القرويين في مقابلة المدمر  .استخدم الروبوت  لقيادة المدمر نحو كل قروي يظهر سهم فوق رأسه.

#### ~ tutorialhint 
استخدم الكتلة ``||hoc2020:توجيه المدمر||`` لجعل المدمر يتبع الروبوت إلى الأمام استخدم الكتلة ``||hoc2020:تدوير الروبوت||`` ليستدير الروبوت إما إلى اليمين أو لليسار

```ghost
    hoc2020.leadRavager(0)
    hoc2020.turnAgent(TurnDirection.Left)    
```
```template
//
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts#v0.5.2
```
