# Sample Explain
## Experiment 1 
![image](https://user-images.githubusercontent.com/98943400/153397439-e3f3030f-ecf4-4d7b-a5e5-20418d6a5710.png)

- ตัวโปรแกรมจะเริ่มด้วการประกาศตัวแปรตัวเลข cnt โดยเริ่มต้น 1 ครั้ง 
- จากนั้นจะเป็นลูปบวกทีละ 1 ไปเรื่อย
- โดยมีดีเลย์ 300 ms

## Experiment 2
![image](https://user-images.githubusercontent.com/98943400/153398641-2a9e946f-eea5-4927-abad-065626e3105a.png)

- ตัวโปรแกรมจะเริ่มด้วการประกาศตัวแปรตัวเลข cnt 
- จากนั้นจะทำการยกเลิกเชื่อมต่อ wifi โดยมีดีเลย์ 100 ms
- แล้วจะเป็นลูปแสดงข้อความเริ่มแสกนหา wifi
- ถ้าหาไม่เจอ จะแสดงข้อความ NO NETWORK FOUND
- ถ้าหาเจอก็จะแสดงออกมาให้เราเลือกใช้

## Experiment 3 
![image](https://user-images.githubusercontent.com/98943400/153400485-c376b107-aae4-41d0-9a3e-78bfe0b01e4d.png)

- ตัวโปรแกรมจะเริ่มด้วการประกาศตัวแปรตัวเลข cnt
- จากนั้นเซ็ตอัพกำหนดหน้าที่ของขาสัญญาณ (pinMode)
- สร้างลูปให้นับเรื่อยๆ ถ้าหากเป็นไปตามเงื่อนไข cnt%2 
- แล้ว cnt จะแสดงข้อความ ON และเปิด
- ถ้าหากไม่เป็น จะแสดงข้อความ OFF และปิด
- โดยแต่ละครั้งจะมีดีเลย์ 500 ms

## Experiment 4
![image](https://user-images.githubusercontent.com/98943400/153402928-ef2ab33e-3671-444a-b21e-4d6630d89ddb.png)

- เซตให้ port 0 เป็น input และ port 2 เป็น output
- ทำลูปให้อ่านข้อมูลจาก port 0 แล้วจะแสดงผลว่าอ่านได้เท่าไหร่
- ถ้าเป็น 1 จะให้ Low ไปที่ port 2 ไฟจะดับ
- ถ้าเป็น 0 จะให้ High ไปที่ port 2 ไฟจะติด

## Experiment 5
![image](https://user-images.githubusercontent.com/98943400/153401685-95416d25-a0fc-4a3d-9c63-c5215608f631.png)

- เริ่มด้วยการกำหนดตัวแปร ssid และ password
- จากนั้นเลือก Server
- แล้วเริ่มทำการรับสัญญาณ จะมีดีเลย์ 500 ms 
- โปรแกรมจะแสดง IP address ออกมา
- ถ้าหากเชื่อมต่อไม่สำเร็จ จะขึ้นว่า Path Not Found
- ถ้าหากสำเร็จจะแสดง Hello cnt: 
- แล้ว HTTP server started

