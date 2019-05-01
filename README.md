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
![57423165_358293301474163_3994025551818915840_n](https://user-images.githubusercontent.com/42909745/57022713-24b1cf80-6c5a-11e9-8255-af09be7b5ddc.png)
<b>เกมจะแบ่งออกเป็น 2 หน้า</b> <br> 1.หน้าร้านค้า <br> 2.หน้าเลือกอาวุธ <br>
<b>ในส่วนของหน้าร้านค้านั้นจะมี</b><br> 1.ปุ่มอัพเกรดอาวุธของแต่ละชนิด <br>
2.ปุ่มดวงตาซื้อคำทำนายลวงหน้าว่าจะเจออาวุธประเภทอะไร <br>
3.ช่องให้เลือกว่าจะเอาอาวุธอะไรไปสู้ในรอบถัดไป <br> 4.กดต่อสู้ <br>

## :video_game:วิธีการเล่นเกม 
![58673863_484183635652841_1955564408767774720_n (1)](https://user-images.githubusercontent.com/42909745/57024149-1796df80-6c5e-11e9-9419-be227f483e49.png)
กด A คือการตี <br> กด S คือการบัฟเพิ่มการโจมตี <br> กด D คือการบัฟเพิ่มการป้องกัน <br> <b>***เพิ่มเติม*** ถ้าเรากดตีบอสจะไม่บัพอะไรทั้งสิ้นแต่ถ้าเรากดบัฟบอสจะมีโอกาสบัฟตัวเอง </b><br>

# Group members
1.นายชยภัทร พันรอด 61070036 <br>
2.นายภูชิต รุ่งระวิ 61070166 <br>
3.นายโยธิน บายศรี 61070179 <br>
4.นายอนุชา เว่ย 61070257 <br>

# Introduction Video
Youtube: https://www.youtube.com/watch?v=YMkT4X-sNm0&feature=youtu.be

[![forthebadge](https://forthebadge.com/images/badges/made-with-c.svg)](https://forthebadge.com)
