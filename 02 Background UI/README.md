# Background UI

วิธีสร้าง Relative Background ให้ กับ  ด้านหลังของ GameObject  โดยใช้กล้องสองตัว

## วิธีทำ

### GUI Background Layer

เป็นส่วนที่จะแสดงผลเป็น Background

1.	Object > UI > Canvas ตั้งชื่อว่า Background
2.	ตรง Layer ให้คลิกที่ Drop down list แล้ว Add layer
3.	เพิ่ม Layer ชื่อ background
4.	คลิกที่ Hierarchy > Background ตั้งค่าตามนี้

![](https://raw.githubusercontent.com/indevizible/Unity-Knowledge/master/photo-75269.gif "วิธีตั้งค่า Background Camera")

ตรง Camera ปล่อยเป็น None ไว้ก่อน


### Camera

*	ทำ Background Camera ได้โดยการ Duplicate Main Camera ขึ้นมา พร้อมกับตั้งค่า Camera ดังนี้

![](https://raw.githubusercontent.com/indevizible/Unity-Knowledge/master/photo-75269.gif "วิธีตั้งค่า Background Camera")

*	ปรับค่า Culling Mask โดยเลือกที่ Nothing แล้วเลือกที่ Background อีกรอบ ให้แน่ใจตรง Drop list เขียนไว้ว่า Background

*	ปรับ Main camera ดังนี้

![](https://raw.githubusercontent.com/indevizible/Unity-Knowledge/master/photo-75269.gif "วิธีตั้งค่า Background Camera")

*	ปรับค่า Culling Mask โดยคลิกเลือกที่ Background ตรง drop list จะขึ้นคำว่า Mixed...

*	เสร็จแล้วให้กลับไปที่ Background แล้วลาก Background Cam ใส่ในช่องที่ว่างไว้

## Refference 

*	http://answers.unity3d.com/questions/9729/how-can-i-display-a-flat-background-2d-image-not-a.html


## Keyword
*	unity make static background [1]

Create by [Nattawut Singhchai](wut@2bsimple.com)
