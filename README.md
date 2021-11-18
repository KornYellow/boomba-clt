# Boomba

เกมนี้ชื่อว่า Boomba ได้แรงบันดาลใจมาจากเกม Zuma, Luxor ซึ่งแสดงผลบน Terminal โดยใช้ ncurses สำหรับการแสดงผล และ SDL Mixer สำหรับเสียง

เกมนี้เป็นโปรเจคปลายภาคเรียนที่ 1 ปีที่ 1 วิชา Programming Fundamental

## วิธีติดตั้งและรันตัวเกม

Dependencies ของผม :

- `ncurses` 6.2 สำหรับจัดการ Terminal
- `libsdl` และ `libsdl_mixer` 1.2 สำหรับเสียง

คำสั่งติดตั้งบน Arch Linux

``` console
$ sudo pacman -S ncurses sdl_mixer
```

คำสั่งติดตั้งบน Ubuntu

``` console
$ sudo apt-get install libsdl-mixer1.2-dev libncurses5-dev
```

คำสั่งคอมไพล์

``` console
$ make
```

คำสั่งรันตัวเกม

``` console
$ ./main
```

## วิธีเล่นเกม

การควบคุมเมนู

- <kbd>↑</kbd> และ <kbd>↓</kbd>: ในการเลือกเมนู
- <kbd>x</kbd>: ยืนยัน / ตกลง
  
การควบคุมตัวผู้เล่น

- <kbd>←</kbd> และ <kbd>→</kbd>: ในการขยับตัวผู้เล่น
- <kbd>x</kbd>: ยิงกระสุน
- <kbd>c</kbd>: สลับสีกระสุน
- <kbd>p</kbd>: หยุดเกม
- <kbd>q</kbd>: ปิดเกมทันที

