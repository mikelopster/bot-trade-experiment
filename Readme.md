## Project สำหรับการทดลอง Bot trade

เราพาทุกคนมาลองคิดเรื่องการทำ bot trade กัน ว่าถ้าเกิดเราได้เป็นคนทำ bot trade ขึ้นมา เราจะตั้งโจทย์แบบไหนในการทำ bot trade บ้าง สำหรับผม ผมจะลองทำ bot trade โดยการใช้ 4 ไอเดียนี้มาลองเทรด bitcoin ปี 2021 แล้วมาวัดผลไปพร้อมกันคือ
1. Technical analysis ใช้เทคนิคคอลสไตล์มาลองหาจุดซื้อจุดขาย
2. Fair price ใช้สมการสุดมหัศจรรย์ของวงการเศรษฐศาสตร์ ในการหาจุดซื้อ (call price) และ จุดขาย (put price)
3. Deep learning ใช้ Model LSTM ในการทำนายราคาและนำข้อมูลนั้นมาหาจุดซื้อและจุดขาย
4. Deep Reinforcement learning ใช้ Deep Q Reinceforcement learning ให้มันลองเทรดในสนามทดลอง ลองหาจุดซื้อจุดขาย แล้วเอามาใช้สำหรับเทรดจริง

ผลลัพธ์สามารถดูได้ตาม video และ article ฉบับเต็มด้านล่างได้เลย

### ดู video การทดลองได้ที่
[![bot-trade-python](https://img.youtube.com/vi/5mCnhS_P99E/0.jpg)](https://youtu.be/5mCnhS_P99E)

### อ่านบทความวิเคราะห์ฉบับเต็มได้ที่
https://blog.mikelopster.dev/blog-trade
