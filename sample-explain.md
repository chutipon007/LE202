# Sample Explain
## Experiment 1 
![image](https://user-images.githubusercontent.com/98943400/153397439-e3f3030f-ecf4-4d7b-a5e5-20418d6a5710.png)

- ตัวโปรแกรมจะเริ่มด้วการประกาศตัวแปรตัวเลข cnt โดยเริ่มต้น 1 ครั้ง 
- จากนั้นจะเป็นลูปบวกทีละ 1 ไปเรื่อย
- โดยมีดีเลย์ 300 ms

## Experiment 2
![image](https://user-images.githubusercontent.com/98943400/153398641-2a9e946f-eea5-4927-abad-065626e3105a.png)

- ตัวโปรแกรมจะเริ่มด้วการประกาศตัวแปรตัวเลข cnt 
- จากนั้นจะทำการเซ็ต wifi ให้พร้อมทำงาน โดยมีดีเลย์ 100 ms
- แล้วจะเป็นลูปแสดงข้อความเริ่มแสกนหา wifi
- ถ้าหาไม่เจอ จะแสดงข้อความ NO NETWORK FOUND
- ถ้าหาเจอก็จะแสดงออกมาให้เราเลือกใช้

## Experiment 3 
![image](https://user-images.githubusercontent.com/98943400/153400485-c376b107-aae4-41d0-9a3e-78bfe0b01e4d.png)

- ตัวโปรแกรมจะเริ่มด้วการประกาศตัวแปรตัวเลข cnt
- จากนั้นเซ็ตอัพกำหนดหน้าที่ของขาสัญญาณ (pinMode) ให้ port 0 เป็น output
- สร้างลูปให้นับเรื่อยๆ ถ้าหากเป็นไปตามเงื่อนไข cnt%2
- แล้ว cnt เป็นเลขคู่ จะแสดงข้อความ ON และเปิด
- ถ้าหาก cnt เป็นเลขคี่ จะแสดงข้อความ OFF และปิด
- โดยแต่ละครั้งจะมีดีเลย์ 500 ms

## Experiment 4
![image](https://user-images.githubusercontent.com/98943400/153402928-ef2ab33e-3671-444a-b21e-4d6630d89ddb.png)

- เซตให้ port 0 เป็น input และ port 2 เป็น output
- ทำลูปให้อ่านข้อมูลจาก port 0 แล้วจะแสดงผลว่าอ่านได้เท่าไหร่
- ถ้าเป็น 1 จะให้ Low ไปที่ port 2 ไฟจะดับ
- ถ้าเป็น 0 จะให้ High ไปที่ port 2 ไฟจะติด
- มีดีเลย์ 100 ms

## Experiment 5
![image](https://user-images.githubusercontent.com/98943400/153401685-95416d25-a0fc-4a3d-9c63-c5215608f631.png)

- เริ่มด้วยการใส่ชื่อ ssid และ password
- จากนั้นเลือก Server
- แล้วเริ่มทำการรับสัญญาณ จะมีดีเลย์ 500 ms 
- โปรแกรมจะแสดง IP address ออกมา
- ถ้าหากเชื่อมต่อไม่สำเร็จ จะขึ้นว่า Path Not Found
- ถ้าหากสำเร็จจะแสดง Hello cnt: (cnt จะบวก 1 ด้วย)
- แล้ว HTTP server started

## Experiment 6
![image](https://user-images.githubusercontent.com/98943400/153404990-77d85cc7-8781-4bff-a864-ed49c409afc3.png)
![image](https://user-images.githubusercontent.com/98943400/153405006-59e5a9af-f531-4d26-9845-fc4173326aa1.png)

- เริ่มด้วยการกำหนด SSID และ password
- ตั้ง local ip , gateway , subnet
- เปิด web server ที่ port 80
- สร้าง access point จะมีดีเลย์ 100 ms 
- มีกรณี Path Not Found
- และถ้าเชื่อมต่อสำเร็จจะแสดง Hello cnt: 
- HTTP Server started
