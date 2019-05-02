# Computer Programming-Project
  เกมนักสู้อมตะ(Game Hero Never Die) นี้มีจุดมีประสงค์จัดทำเพื่อความบันเทิงและการฝึกทักษะการจัดการทรัพยากร เกมนักสู้อมตะเป็นเกมที่พัฒนาจากภาษา C โดยลักษณะของเกมจะมีบอสเข้ามาให้เราตีเรื่อยๆ เมื่อเราตีบอสจนชนะเราก็จะสามารถผ่านด่านนั้นไปได้และเมื่อเราชนะเราจะสามารถอัพเกรดตัวละครของเราให้แข็งแกร่งขึ้นได้โดยบอสของแต่ละด่านนั้นก็จะเพิ่มความยากขึ้นไปเรื่อยๆ ถ้าเราไม่สามารถเอาชนะบอสในด่านนั้นได้ก็จะถือว่าจบเกม
# :page_facing_up: รายละเอียดของโปรเจคเกม
## ภาษาคอมพิวเตอร์ใช้พัฒนาตัวโปรเจคเกม
[![c-plus-plus-logo.png](https://www.img.live/images/2019/05/01/c-plus-plus-logo.png)](https://www.img.live/image/7L7TJH)
## library หลักที่ใช้พัฒนาตัวโปรเจคเกม
[![raylib_logo_card.png](https://www.img.live/images/2019/05/01/raylib_logo_card.png)](https://www.img.live/image/7LOLrt)<br/>
เพิ่มเติมเกี่ยวกับ raylib https://www.raylib.com/
## :book:คู่มือการเล่น
<b>ตัวละคร</b><br>
[![player2.gif](https://www.img.live/images/2019/05/01/player2.gif)](https://www.img.live/image/7L7Loy)
#### ประเภทอาวุธ
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
โจมตีกายภาพ
[![armor.png](https://www.img.live/images/2019/05/01/armor.png)](https://www.img.live/image/7L4mNy)
ป้องกันกายภาพ
[![wand.png](https://www.img.live/images/2019/05/01/wand.png)](https://www.img.live/image/7L74M4)
โจมตีเวท
[![shield.png](https://www.img.live/images/2019/05/01/shield.png)](https://www.img.live/image/7L7SYc)
ป้องกันเวท
#### กฎของเกม
เกราะจะต้องเป็นประเภทเดียวกับอาวุธ จึงจะสามารถป้องกันได้ <br /><br/>
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
[![armor.png](https://www.img.live/images/2019/05/01/armor.png)](https://www.img.live/image/7L4mNy)
- ป้องกันได้ <br /><br/>
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
[![shield.png](https://www.img.live/images/2019/05/01/shield.png)](https://www.img.live/image/7L7SYc)
- ป้องกันไม่ได้
#### ประเภทของบอสทั้งหมด
[![boss00.png](https://www.img.live/images/2019/05/01/boss00.png)](https://www.img.live/image/7L7pTc)
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
[![armor.png](https://www.img.live/images/2019/05/01/armor.png)](https://www.img.live/image/7L4mNy)<br /><br>
[![boss01.png](https://www.img.live/images/2019/05/01/boss01.png)](https://www.img.live/image/7L7XJe)
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
[![shield.png](https://www.img.live/images/2019/05/01/shield.png)](https://www.img.live/image/7L7SYc)<br /><br>
[![boss10.png](https://www.img.live/images/2019/05/01/boss10.png)](https://www.img.live/image/7L7ZU5)
[![wand.png](https://www.img.live/images/2019/05/01/wand.png)](https://www.img.live/image/7L74M4)
[![armor.png](https://www.img.live/images/2019/05/01/armor.png)](https://www.img.live/image/7L4mNy)<br /><br>
[![boss11.png](https://www.img.live/images/2019/05/01/boss11.png)](https://www.img.live/image/7L7f59)
[![wand.png](https://www.img.live/images/2019/05/01/wand.png)](https://www.img.live/image/7L74M4)
[![shield.png](https://www.img.live/images/2019/05/01/shield.png)](https://www.img.live/image/7L7SYc)<br /><br>


## รูปแบบของเกม
<b>เกมจะแบ่งออกเป็น 5 หน้า</b> <br> 1.หน้าเริ่มต้นเกม <br> 2.หน้าร้านค้า <br> 3.หน้าเลือกอาวุธ <br> 4.หน้าผลรวมรางวัล <br> 5.หน้าจบเกม<br><br>
![messageImage_1556727451081](https://user-images.githubusercontent.com/42909745/57029203-3ea7de00-6c6b-11e9-9bf6-7032de74a0b5.jpg)
<b>หน้าเริ่มต้นเกม</b> <br><br>
![57423165_358293301474163_3994025551818915840_n](https://user-images.githubusercontent.com/42909745/57022713-24b1cf80-6c5a-11e9-8255-af09be7b5ddc.png)
<b>หน้าร้านค้าและหน้าเลือกอาวุธ</b> <br>
<b>ในส่วนของหน้าร้านค้านั้นจะมี</b><br> 1.ปุ่มอัพเกรดอาวุธของแต่ละชนิด <br>
2.ปุ่มดวงตาซื้อคำทำนายลวงหน้าว่าจะเจออาวุธประเภทอะไร <br>
3.ช่องให้เลือกว่าจะเอาอาวุธอะไรไปสู้ในรอบถัดไป <br> 4.กดต่อสู้ <br><br>
![messageImage_1556726869481](https://user-images.githubusercontent.com/42909745/57029319-99413a00-6c6b-11e9-829b-b07b44de239d.jpg)
<b>หน้าผลรวมรางวัล</b> <br>
รางวัลปกติจะได้ตามจำนวนเลเวลของบอสที่ชนะไปยิ่งมากยิ่งได้เยอะและจะมีโบนัสที่ว่าถ้าชนะบอสที่แพ้ทางมากเท่าไหร่จะได้เพิ่มพิเศษ <br><br>
![messageImage_1556727597723](https://user-images.githubusercontent.com/42909745/57029469-0785fc80-6c6c-11e9-8dfa-a8cf351e5e1c.jpg)
<b>หน้าจบเกม</b> <br><br>
### :video_game:วิธีการเล่นเกม 
![58673863_484183635652841_1955564408767774720_n (1)](https://user-images.githubusercontent.com/42909745/57024149-1796df80-6c5e-11e9-9419-be227f483e49.png)
กด A คือการตี <br> กด S คือการบัฟเพิ่มการโจมตี <br> กด D คือการบัฟเพิ่มการป้องกัน <br> <b>***เพิ่มเติม*** ถ้าเรากดตีบอสจะไม่บัพอะไรทั้งสิ้นแต่ถ้าเรากดบัฟบอสจะมีโอกาสบัฟตัวเอง </b><br><br>



# Group members
1.นายชยภัทร พันรอด 61070036 <br>
2.นายภูชิต รุ่งระวิ 61070166 <br>
3.นายโยธิน บายศรี 61070179 <br>
4.นายอนุชา เว่ย 61070257 <br>

# Assistant Teacher
รศ.ดร.กิติ์สุชาต พสุภา <br>
รศ.ดร.ปานวิทย์ ธุวะนุติ <br>
รายงาน และ ซอร์สโค้ดนี้ เป็นส่วนหนึ่งของวิชา การสร้างโปรแกรมคอมพิวเตอร์ Computer Programming (06016206)
หลักสูตรวิทยาศาสตร์บัณฑิต สาขาวิชาเทคโนโลยีสารสนเทศ
ภาคเรียนที่ 2 ปีการศึกษา 2559
คณะเทคโนโลยีสารสนเทศ
สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง

# Introduction Video
Youtube: https://www.youtube.com/watch?v=YMkT4X-sNm0&feature=youtu.be

[![forthebadge](https://forthebadge.com/images/badges/made-with-c.svg)](https://forthebadge.com)
