
# โจทย์มีดังนี้ (ส่งก่อนวันพฤหัสหน้าที่ 25 ม.ค. เวลา 12:00น.)

ทำเกมประมาณ Fall Guys
ใช้ Blueprint เป็นหลัก
Multiplayer อย่างต่ำเล่นได้ 2 คน
ไม่ต้องทำ UI เปิดมาเริ่มเกมเลย
ไม่ต้องทำ Custom 3D model ใช้ basic shape ได้เลย
ไม่มีคะแนนการออกแบบ level design
Objective ของเกมคือวิ่งไปให้ถึง goal ใครถึงก่อนก็ชนะจบเกม
----------------------------------------------------------------
## [Math Test]
ทำ Obstacles เป็น platform ที่หมุนๆได้ (ตัวอย่างในภาพในแนบไป) โดยใช้ Pure Math (Math Expression Node)
ทำ Obstacles เป็น  moving platform โดยใช้ Pure Math  (Math Expression Node)

$${\color{red}สำหรับการเขียน Blueprint Obstacles มีข้อจำกัดห้ามใช้ Node Timeline และ Delay}$$

(Optional) เขียน moving platform path โดยใช้ Bézier curve ในการกำหนด path การวิ่งของ moving platform
-----------------------------------------------------------------
## [Network Test]
Test ที่ ping 150+
Players ทั้ง server and clients ต้องเห็นตำแหน่งของกันและกัน ตรงกัน
Players ทั้ง server and clients ต้องเห็นตำแหน่งของ Obstacles ตรงกัน

# All reference
## [Obstacles]
* https://www.youtube.com/watch?v=OP-v2xQNcFc
* https://www.youtube.com/watch?v=fO6Pmrr8Pi0

## [Bézier curve]
* https://www.youtube.com/watch?v=xVF9pnarOX4
* https://github.com/shamim-akhtar/bezier-curve

## [Network Test]
* https://www.youtube.com/watch?v=4Tnbf44NjXo
* https://www.youtube.com/watch?v=ef6SeknakeU
* https://www.youtube.com/watch?v=OVeo3cVTIcU
