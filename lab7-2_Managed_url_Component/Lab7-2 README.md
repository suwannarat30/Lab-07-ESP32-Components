# Lab 7-2: Managed Component from GitHub URL Demo

## คำอธิบาย
การทดลองนี้แสดงการใช้งาน managed component จาก GitHub Repository
ใช้ `Sensors` component จาก https://github.com/APPLICATIONS-OF-MICROCONTROLLERS/Lab7_Components

## ผลลัพธ์ที่คาดหวัง
- แสดงข้อความการเริ่มต้น sensor จาก GitHub component
- แสดงข้อมูล temperature และ humidity ทุก 4 วินาที
- แสดงสถานะการทำงานของ sensor
- แสดงแหล่งที่มาของ component (GitHub Repository)

## ความแตกต่างจาก Lab 7-1
- Lab 7-1: ใช้ local component (ในเครื่อง)
- Lab 7-2: ใช้ managed component จาก GitHub URL

## การใช้งาน
1. เข้าไปในโฟลเดอร์ lab7-2_Managed_url_Component
2. รันคำสั่ง `idf.py build` (จะดาวน์โหลด component จาก GitHub อัตโนมัติ)
3. ทดสอบด้วย QEMU
I (11565) LAB7-2: 📋 Reading #2 from GitHub Component
I (11565) SENSOR: 📊 Reading sensor data from file: ./managed_components/lab7_components/Sensors/sensor.c, line: 18
I (11565) SENSOR: 🌡️  Temperature: 33.1°C
I (11565) SENSOR: 💧 Humidity: 90.9%
I (11565) SENSOR: ✅ Sensor status check from file: ./managed_components/lab7_components/Sensors/sensor.c, line: 30
I (11565) SENSOR: 📈 All sensors operating normally
I (11565) LAB7-2: � Component Source: GitHub Repository
I (11565) LAB7-2: ==========================================
I (15565) LAB7-2: 📋 Reading #3 from GitHub Component
I (15565) SENSOR: 📊 Reading sensor data from file: ./managed_components/lab7_components/Sensors/sensor.c, line: 18
I (15565) SENSOR: 🌡️  Temperature: 28.0°C
I (15565) SENSOR: 💧 Humidity: 98.4%
I (15565) SENSOR: ✅ Sensor status check from file: ./managed_components/lab7_components/Sensors/sensor.c, line: 30
I (15565) SENSOR: 📈 All sensors operating normally
I (15565) LAB7-2: � Component Source: GitHub Repository