### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# الحصول على الكرة

## الخطوة الأولى
يبدو أن الروافع عالقة في المصعد. اجعل الروبوت يستخدم قوته لقلب جميع الروافع حتى يتمكن القروي  من إنزال كرة الأطفال.


#### ~ tutorialhint 
استخدم الكتلة  ``||hoc2020:تحريك الروبوت||`` للصعود إلى **أعلى** الجدار و الكتلة ``||hoc2020:تبديل ذراع الرافعة||`` لتشغيلها

```ghost
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.flipLever()
```
```template
//
```
```package
hoc2020-ts-ar=github:rewrite-media/hoc2020-ts-ar
```
