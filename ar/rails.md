### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# مد السكة الحديدية

## الخطوة الأولى
أنشئ وسيلة أسهل للتنقل بين البلدتين عن طريق وضع قضبان العربات داخل النفق

#### ~ tutorialhint 
استخدم الكتلة ``||hoc2020:وضع السكة للأسفل||`` لتضع سكة حديدية أسفل الروبوت استخدم الكتلة ``||hoc2020:تحريك الروبوت||`` ليتحرك الروبوت في الاتجاه الذي تحدده استخدم الكتلة ``||hoc2020Different:تكرار||`` لتكرار مجموعة من الكتل عدة مرات 

```ghost
    hoc2020.placeRails()
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020Different.customRepeatLoop(0, () => {})
```
```template
//
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts#v0.5.2
```