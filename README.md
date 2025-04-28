📋 ระบบบันทึกกิจกรรมจิตอาสา (Volunteer Activity Logger)
ระบบสำหรับบันทึกและจัดการข้อมูลกิจกรรมจิตอาสา ด้วย Django Framework พร้อมฟอร์มบันทึกและตารางแสดงผลสวยงามด้วย Bootstrap 5

🔥 คุณสมบัติ (Features)
📄 ฟอร์มบันทึกกิจกรรม พร้อมระบบคำนวณจำนวนชั่วโมงอัตโนมัติ

🗂 แสดงตารางกิจกรรมที่เคยบันทึก

🖋 แก้ไข และลบข้อมูลกิจกรรม

📎 แนบไฟล์หลักฐาน หรือใส่ URL ได้

📱 รองรับการแสดงผลบนมือถือ (Responsive)

🛠 เทคโนโลยีที่ใช้ (Built With)
Django - Python Web Framework

Bootstrap 5 - Frontend Framework

HTML5, CSS3, JavaScript (Vanilla)

📷 ตัวอย่างหน้าจอ (Screenshots)
ฟอร์มบันทึกกิจกรรม
<img src="https://via.placeholder.com/800x400.png?text=Form+Page" alt="ฟอร์มบันทึกกิจกรรม">
ตารางกิจกรรม
<img src="https://via.placeholder.com/800x400.png?text=List+Page" alt="ตารางกิจกรรม">
(หากคุณมีภาพหน้าจอจริง สามารถแทนที่ link รูปได้เลย)

🚀 วิธีติดตั้ง (Installation)
Clone โปรเจกต์นี้

bash
คัดลอก
แก้ไข
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
สร้างและเปิดใช้งาน Virtual Environment

bash
คัดลอก
แก้ไข
python -m venv venv
source venv/bin/activate  # บน Mac/Linux
venv\Scripts\activate     # บน Windows
ติดตั้ง Dependencies

bash
คัดลอก
แก้ไข
pip install -r requirements.txt
ตั้งค่า Database และ Migrate

bash
คัดลอก
แก้ไข
python manage.py migrate
รันเซิร์ฟเวอร์

bash
คัดลอก
แก้ไข
python manage.py runserver
เปิดเบราว์เซอร์ไปที่

cpp
คัดลอก
แก้ไข
http://127.0.0.1:8000/
📁 โครงสร้างโปรเจกต์ (Project Structure)
bash
คัดลอก
แก้ไข
/score
    /core
        templates/
            form.html
            list.html
        models.py
        views.py
        urls.py
    manage.py
    requirements.txt
    README.md
