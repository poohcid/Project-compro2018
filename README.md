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

# Source code
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

### function main
```
int main(){
    const int WindowWidth = 1280;
    const int WindowHeight = 720;
    for (int i=0; i < 10; i++)
        level[i] = 1;
    
    InitWindow(WindowWidth, WindowHeight, "Hero Never Die");
    SetTargetFPS(60);
    randomBoss();
    selectItems(1);
    selectItems(3);
    strcpy(omen, "");
    strcpy(buff_textB, "");
             /*ดึงไฟล์รุปที่ต้องใช้*/
    sword = LoadTexture("img/sword.png");
    armor = LoadTexture("img/armor.png");
    wand = LoadTexture("img/wand.png");
    shield = LoadTexture("img/shield.png");
    eye = LoadTexture("img/eye.png");
    man = LoadTexture("img/frame_player2/frameA.png");
    battle = LoadTexture("img/battle.png");
    fight_img = LoadTexture("img/fight.png");
    atk_img = LoadTexture("img/atk.png");
    def_img = LoadTexture("img/def.png");
    grave = LoadTexture("img/grave.png");
    lucifer = LoadTexture("img/lucifer.png");
    worrior = LoadTexture("img/warrior.png");
    font1 = LoadFont("font/romulus.png");
    background_start = LoadTexture("img/background_start.png");
    background_arena = LoadTexture("img/background_arena2.png");
    SetWindowIcon(GetTextureData(battle));
    while (!WindowShouldClose()){
        /*ลูปที่จะทำให้หน้าเกมรันตลอดเวลา*/
        item_change();
        if (step == 0)
            start(); // หน้าเริ่มเกม
        if (step == 1){
            home(); //หน้าร้านค้า
            eventMouseHome();
            if (step_arena == 0)
                delayAnimetion('Q');
        }
        if (step == 2){
            arena(); //หน้าต่อสู้
            eventArena();
            if (step_arena == 0)
                delayAnimetion('Q');
            if (step_arena == 1){
                delayFight();
            }
            if (step_arena == 2){
                delayBuff(2, "+ATK");
            }
            if (step_arena == 3){
                delayBuff(3, "+DEF");
            }
        }
        if (step == 3)
            resultGame(); //หน้าชนะการต่อสู้
        if (step == 4)
            lose(); //หน้าแพ้
    }
    return 0;
}
```

### function home 
- การแสดงผลหน้าร้านค้า
```
void home(){
    BeginDrawing();
    ClearBackground(RAYWHITE);
    DrawRectangle(500, 100, 100, 100, Color{rgb[0].r, rgb[0].g, rgb[0].b, 255}); //player
    DrawRectangle(500, 250, 100, 100, Color{rgb[1].r, rgb[1].g, rgb[1].b, 255});
    DrawRectangle(500, 400, 100, 100, Color{rgb[2].r, rgb[2].g, rgb[2].b, 255});
    DrawRectangle(500, 550, 100, 100, Color{rgb[3].r, rgb[3].g, rgb[3].b, 255});
    DrawRectangle(800, 550, 80, 80, Color{rgb[4].r, rgb[4].g, rgb[4].b, 255});
    DrawText(FormatText("Lv. %d", level[0]), 520, 200, 20, BLACK);
    DrawText(FormatText("Lv. %d", level[1]), 520, 350, 20, BLACK);
    DrawText(FormatText("Lv. %d", level[2]), 520, 500, 20, BLACK);
    DrawText(FormatText("Lv. %d", level[3]), 520, 650, 20, BLACK);
    DrawRectangle(900, 250, 100, 100, Color{rgb[5].r, rgb[5].g, rgb[5].b, 255});
    DrawRectangle(1050, 250, 100, 100, Color{rgb[6].r, rgb[6].g, rgb[6].b, 255});
    DrawRectangle(900, 400, 100, 100, Color{rgb[7].r, rgb[7].g, rgb[7].b, 255});
    DrawRectangle(1050, 400, 100, 100, Color{rgb[8].r, rgb[8].g, rgb[8].b, 255});
    DrawRectangle(700, 0, 30, 730, Color{0, 0, 0, 255});
    DrawText(FormatText("$ %d", price[0]), 400, 150, 30, GREEN);
    DrawText(FormatText("$ %d", price[1]), 400, 300, 30, GREEN);
    DrawText(FormatText("$ %d", price[2]), 400, 450, 30, GREEN);
    DrawText(FormatText("$ %d", price[3]), 400, 600, 30, GREEN);
    DrawText(FormatText("money: %d $", money), 10, 20, 50, GREEN);
    DrawText(FormatText("$ 100"), 750, 85, 40, GREEN);
    //DrawText(FormatText("%d %d", type_boss[0], type_boss[1]), 50, 300, 50, RED);
    DrawRectangle(880, 80, 80, 80, Color{rgb[9].r, rgb[9].g, rgb[9].b, 255});
    DrawText(FormatText("%s", omen), 980, 110, 30, RED);
    DrawTextureEx(man, Vector2{40, 130},0, 0.9, RAYWHITE);
    DrawText(FormatText("Lv. %d", lv[0]), 50, 450, 40, BLACK);
    DrawRectangle(180, 450, lv_bar, 40, GREEN);
    DrawRectangleLinesEx(Rectangle{180, 450, 200, 40}, 2, BLACK);
    DrawTexture(sword, 500, 100, RAYWHITE);
    DrawTexture(armor, 500, 250, RAYWHITE);
    DrawTexture(wand, 500, 400, RAYWHITE);
    DrawTexture(shield, 500, 550, RAYWHITE);
    DrawTexture(eye, 880, 80, RAYWHITE);
    DrawText("Select Items", 900, 200, 40, BLACK);
    DrawTexture(sword, 900, 250, RAYWHITE);
    DrawTexture(wand, 1050, 250, RAYWHITE);
    DrawTexture(armor, 900, 400, RAYWHITE);
    DrawTexture(shield, 1050, 400, RAYWHITE);
    DrawTextureEx(battle, Vector2{800, 550}, 0, 0.6, RAYWHITE);
    DrawText("Fight", 930, 580, 40, RED);
    EndDrawing();
}
```

### function arena
- การแสดงผลหน้าต่อสู้
```
void arena(){
    BeginDrawing();
    ClearBackground(RAYWHITE);
    DrawTexture(background_arena, 0, 110, RAYWHITE);
    DrawTexture(background_arena, 0, -150, RAYWHITE);
    DrawTextureEx(man, Vector2{posit_player, 230}, 0, 0.6, RAYWHITE);
    DrawTexture(enemy, posit_boss, 200, RAYWHITE);
    DrawTextureEx(worrior, Vector2{400, 100}, 0, 0.7, RAYWHITE);
    DrawTextureEx(lucifer, Vector2{400, 200}, 0, 0.7, RAYWHITE);
    DrawTextureEx(atk_player, Vector2{520, 100}, 0, 0.7, RAYWHITE);
    DrawTextureEx(def_player, Vector2{620, 100}, 0, 0.7, RAYWHITE);
    DrawTextureEx(atk_boss, Vector2{520, 200}, 0, 0.7, RAYWHITE);
    DrawTextureEx(def_boss, Vector2{620, 200}, 0, 0.7, RAYWHITE);
    DrawText(FormatText("%s", buff_textB), buff_posit, 150, 40, Color{rgb[10].r, rgb[10].g, rgb[10].b, 255});
    DrawRectangle(100, 450, hp_player_bar, 30, RED); //hp player
    DrawRectangle(900, 450, hp_boss_bar, 30, RED); //hp boss
    DrawText(FormatText("Lv. %d", text_boss), 900, 100, 40, BLACK);
    DrawText(FormatText("Lv. %d", lv[0]), 100, 100, 40, BLACK);
    DrawRectangleLinesEx(Rectangle{100, 450, 200, 30}, 2, BLACK); //border hp player
    DrawRectangleLinesEx(Rectangle{900, 450, 200, 30}, 2, BLACK); //border hp boss
    DrawRectangleLinesEx(Rectangle{400, 550, 100, 100}, 3, BLACK);
    DrawRectangleLinesEx(Rectangle{550, 550, 100, 100}, 3, BLACK);
    DrawRectangleLinesEx(Rectangle{700, 550, 100, 100}, 3, BLACK);
    DrawTexture(fight_img, 400, 550, RAYWHITE);
    DrawTexture(atk_img, 550, 550, RAYWHITE);
    DrawTexture(def_img, 700, 550, RAYWHITE);
    DrawText("A", 370, 500, 50, RED);
    DrawText("S", 520, 500, 50, RED);
    DrawText("D", 670, 500, 50, RED);
    EndDrawing();
}
```

### function resultGame 
- การแสดงผลหน้าจบเกมเมื่อชนะและการเซตค่าต่างๆและเงินรางวัล
```
void resultGame(){
    int price_lv=0;
    int sur=0;
    int total=0;
    int go=0;
    float result;
    for (int i=0; i < 4; i++)
        buff[i] = 0;
    price_lv += 40+text_boss*10;
    if (type_player[0] == type_boss[1])
        sur += text_boss*10;
    if (type_player[1] != type_boss[0])
        sur += text_boss*10;
    if (type_player[1] != type_boss[0] && type_player[0] == type_boss[1])
        sur += text_boss*10;
    total += 40+price_lv+sur;
    BeginDrawing();
    ClearBackground(RAYWHITE);
    DrawText(FormatText("Winner +%d $", 40+price_lv), 400, 100, 50, GREEN);
    DrawText(FormatText("Bonus survivor +%d $", sur), 400, 200, 50, GREEN);
    DrawText(FormatText("Total %d $", total), 400, 300, 50, GREEN);
    if (hover(400, 700, 550, 660)){
        DrawRectangle(400, 550, 300, 100, WHITE);
        DrawText("Go Home", 420, 570, 60, BLACK);
        go = 1;
    }
    else{
        DrawRectangle(400, 550, 300, 100, BLACK);
        DrawText("Go Home", 420, 570, 60, WHITE);
    }
    if (IsMouseButtonPressed(MOUSE_LEFT_BUTTON) && go == 1){
        randomBoss();
        money += total;
        result = (text_boss/(lv[0]+0.75))*200;
        lv_bar += result;
        while (lv_bar >= 200){
            lv[0]++;
            hp_player = 50+lv[0]*20;
            lv_bar -= 200;
        }
        hp_boss_bar = 200;
        hp_player_bar = 200;
        strcpy(omen, "");
        count = 1;
        step_arena = 0;
        /*
        if (type_boss[0] == 0 && type_boss[1] == 0)
            boss[0][0] = 30*lv[1], boss[0][1] = 20*lv[1];
        if (type_boss[0] == 0 && type_boss[1] == 1)
            boss[1][0] = 30*lv[2], boss[1][1] = 20*lv[2];
        if (type_boss[0] == 1 && type_boss[1] == 0)
            boss[2][0] = 30*lv[3], boss[2][1] = 20*lv[3];
        if (type_boss[0] == 1 && type_boss[1] == 1)
            boss[3][0] = 30*lv[4], boss[3][1] = 20*lv[4];
        */
        step = 1;
    }
    EndDrawing();
}
```

### function lose
- หน้าแสดงผลจบเกม เมื่อแพ้
```
void lose(){
    int check=0;
    BeginDrawing();
    ClearBackground(RAYWHITE);
    DrawText("You lose", 400, 100, 80, BLUE);
    DrawText(FormatText("Score: Lv. %d", lv[0]), 400, 200, 50, BLACK);
    DrawTextureEx(grave, Vector2{400, 300}, 0, 3, RAYWHITE);
    DrawRectangle(800, 450, 250, 100, BLACK);
    DrawText("Replay", 825, 470, 60, WHITE);
    if (hover(800, 1050, 450, 550)){
        DrawRectangle(800, 450, 250, 100, WHITE);
        DrawText("Replay", 825, 470, 60, BLACK);
        check = 1;
    }
    else
        check = 0;
    if (IsMouseButtonPressed(MOUSE_LEFT_BUTTON) && check == 1)
        step = 0;
    EndDrawing();
}
```

### function start
- หน้าเริ่มเกมและการเซตค่าเริ่มต้น
```
void start(){
    int i;
    BeginDrawing();
    ClearBackground(RAYWHITE);
    DrawTextureEx(background_start, Vector2{0, 0}, 0, 5, RAYWHITE);
    DrawTextEx(font1, "Hero Never Die", Vector2{300, 100}, 80, 10, RED);
    DrawText("press -- ENTER -- start ", 420, 250, 30, BLACK);
    if (IsKeyPressed(KEY_ENTER)){
        money = 0;
        hp_player_bar = 200, hp_boss_bar = 200;
        hp_player = 200;
        for (i=0; i < 4; i++)
            boss[i][0] = 35, boss[i][1] = 20;
        type_boss[0] = 0, type_boss[1] = 0;
        type_player[0] = 0, type_player[1] = 0;
        player[0] = 40, player[1] = 20, player[2] = 40, player[3] = 20;
        items[0] = 1, items[2] = 1;
        for (i=0; i < 4; i++)
            price[i] = 20, level[i] = 1, buff[i] = 0;
        for (i=1; i < 5; i++)
            lv[i] = 0;
        items_fight[0][0] = 40, items_fight[0][1] = 20;
        items_fight[1][0] = 35, items_fight[1][1] = 20;
        step_arena=0;
        count = 1;
        lv[1]++;
        text_boss = 1;
        hp_boss = 200+text_boss*20;
        lv[0] = 1;
        type = 0;
        lv_bar = 0;
        atk_player = LoadTexture("img/sword.png");
        def_player = LoadTexture("img/armor.png");
        atk_boss = LoadTexture("img/sword.png");
        def_boss = LoadTexture("img/armor.png");
        enemy = LoadTexture("img/boss00.png");
        step = 2;
    }
        
    EndDrawing();
}
```
