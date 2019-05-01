# Project-ComPro 2018
  เกมนักสู้อมตะ(Game Hero Never Die) นี้มีจุดมีประสงค์จัดทำเพื่อความบันเทิงและการฝึกทักษะการจัดการทรัพยากร เกมนักสู้อมตะเป็นเกมที่พัฒนาจากภาษา C โดยลักษณะของเกมจะมีบอสเข้ามาให้เราตีเรื่อยๆ เมื่อเราตีบอสจนชนะเราก็จะสามารถผ่านด่านนั้นไปได้และเมื่อเราชนะเราจะสามารถอัพเกรดตัวละครของเราให้แข็งแกร่งขึ้นได้โดยบอสของแต่ละด่านนั้นก็จะเพิ่มความยากขึ้นไปเรื่อยๆ ถ้าเราไม่สามารถเอาชนะบอสในด่านนั้นได้ก็จะถือว่าจบเกม
## รายละเอียดของโปรเจคเกม
### ภาษาคอมพิวเตอร์ใช้พัฒนาตัวโปรเจคเกม
[![c-plus-plus-logo.png](https://www.img.live/images/2019/05/01/c-plus-plus-logo.png)](https://www.img.live/image/7L7TJH)
### วิธีการเล่น
[![player2.gif](https://www.img.live/images/2019/05/01/player2.gif)](https://www.img.live/image/7L7Loy)
ตัวละคร
##### ประเภทอาวุธ
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
โจมตีกายภาพ
[![armor.png](https://www.img.live/images/2019/05/01/armor.png)](https://www.img.live/image/7L4mNy)
ป้องกันกายภาพ
[![wand.png](https://www.img.live/images/2019/05/01/wand.png)](https://www.img.live/image/7L74M4)
โจมตีเวท
[![shield.png](https://www.img.live/images/2019/05/01/shield.png)](https://www.img.live/image/7L7SYc)
ป้องกันเวท
##### กฎของเกม
เกราะจะต้องเป็นประเภทเดียวกับอาวุธ จึงจะสามารถป้องกันได้ <br /><br/>
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
[![armor.png](https://www.img.live/images/2019/05/01/armor.png)](https://www.img.live/image/7L4mNy)
- ป้องกันได้ <br /><br/>
[![sword.png](https://www.img.live/images/2019/05/01/sword.png)](https://www.img.live/image/7L41Ki)
[![shield.png](https://www.img.live/images/2019/05/01/shield.png)](https://www.img.live/image/7L7SYc)
- ป้องกันไม่ได้
##### ประเภทของบอสทั้งหมด
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


# Group members
1.นายชยภัทร พันรอด 61070036 <br>
2.นายภูชิต รุ่งระวิ 61070166 <br>
3.นายโยธิน บายศรี 61070179 <br>
4.นายอนุชา เว่ย 61070257 <br>

# Introduction Video
Youtube: 

# source code
### global variable
```
int level[10];  //เลเวลของอาวุธ
int step = 0;   //ตัวบอกว่าจะไปหน้าไหน
struct color{
    int r=245, g=245, b=245;  //ตัวเก็บข้อมูลสีที่ต้องใช้ในส่วนต่างๆ
}rgb[30];
int money = 0; //เงินของตัวละคร
int type = 0;  //ค่าที่บอกประเภทของปุ่มกด
int lv[] = {1, 0, 0, 0, 0};   //index[0]คือเลวลตัวละคร
float lv_bar = 0;  //หลอดเลเวล
float hp_player_bar = 200, hp_boss_bar = 200;  //หลอดเลือดตัวละครและบอส
int hp_player = 200, hp_boss = 180;  //ค่าเลือดตัวละครและบอส
int boss[4][2] = {{35, 20}, {35, 20}, {35, 20}, {35, 20}}; //ค่าพลังโจมตี ป้องกันของบอสแต่ละตัว
int type_boss[] = {0, 0}; //ค่าที่บอกประเภทบอส 0 กายภาพ 1 เวทมนตร์
int player[] = {40, 20, 40, 20}; //ค่าพลังโจมตีและพลังป้องกันของตัวละคร
int items[] = {0, 0, 0, 0}; // กระเป๋าใส่ไอเทม index 0, 2 อาวุธกายภาพ, เวท   1, 3  ป้องกันกายภาพ, เวท   ค่าใดเป็น 1 คือเก็บอุปกรณ์นั้นๆ
int price[] = {20, 20, 20, 20};  //ราคาอาวุธ
int type_player[] = {0, 0}; //ค่าที่บอกว่าตกระเป๋าตัวละครของเราเป็นอาวุธประเภทไหน
char omen[20];  //ข้อความลางบอกเหตุ
int buff[] = {0, 0, 0, 0}; //ค่าบัฟต่างๆ
int items_fight[2][2]; //พลังอาวุธของตัวละครและบอสในด่านนั้นๆ ที่จะมาวัดพลังกัน
int step_arena=0; //ค่าที่บอกว่าจะใช้ฟังก์ชั่น delay อะไรในระหว่างการต่อสู้
int count = 1; //ตัวนับค่า delay
int text_boss; // level ของบอสที่จะต่อสู้ในการประลอง
int price_lv = 10; //ค่าที่เพิ่มเงินรางวัลตามเลเวลของบอสที่ชนะ
char buff_textB[5]; //ตัวอักษรประเภทบัฟที่โชว์บนตัวละครและบอส
int buff_posit = 100; //ตำแหน่งของตัวอักษรบัฟ
int posit_player = 130, posit_boss = 850; //ตำแหน่งของตัวละครที่จะต้องมีการเลื่อนไปมา
int mode_player = 0, mode_boss = 0; //สถานะว่าตัวละครนั้นโจมตีหรือไม่ ถ้าโจมตีจะมีค่่าเท่ากับ 1
                   /*รุปภาพต่าง*/
Texture2D sword, armor, wand, shield, eye, man, battle, enemy;
Texture2D fight_img, atk_img, def_img, grave, lucifer, worrior;
Texture2D atk_player, def_player, atk_boss, def_boss, background_start, background_arena;
Font font1;
```
