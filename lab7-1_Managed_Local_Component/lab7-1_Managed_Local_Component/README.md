# Lab 7-1: Local Component Demo

## คำอธิบาย
การทดลองนี้แสดงการใช้งาน component ที่มีอยู่ในโฟลเดอร์ `components/Sensors/` ของ project


## สรุปคำสั่งที่ใช้ และผลลัพธ์ที่ได้
1. เข้าไปในโฟลเดอร์โปรเจกต์ Lab 7-1 cd lab7-1_Managed_Local_Component
2. Export environment ของ ESP-IDF . $IDF_PATH/export.sh
3. ตั้งค่าให้ target เป็น ESP32 idf.py set-target esp32
4. Build โปรเจกต์ idf.py build 
ผลลัพธ์ที่ได้
I (7225) LAB7-1: 🚀 Lab 7-1: Local Component Demo Started
I (7225) SENSOR: 🔧 Sensor initialized from file: /project/components/Sensors/sensor.c, line: 12
I (7225) SENSOR: 📡 Sensor module ready for operation
I (7225) SENSOR: 📊 Reading sensor data from file: /project/components/Sensors/sensor.c, line: 18
I (7225) SENSOR: 🌡️  Temperature: 29.1°C
I (7235) SENSOR: 💧 Humidity: 89.0%
I (7235) SENSOR: ✅ Sensor status check from file: /project/components/Sensors/sensor.c, line: 30
I (7235) SENSOR: 📈 All sensors operating normally
I (25235) LAB7-1: ----------------------------
I (28235) SENSOR: 📊 Reading sensor data from file: /project/components/Sensors/sensor.c, line: 18
I (28235) SENSOR: 🌡️  Temperature: 32.7°C
I (28235) SENSOR: 💧 Humidity: 61.5%
I (28235) SENSOR: ✅ Sensor status check from file: /project/components/Sensors/sensor.c, line: 30
I (28235) SENSOR: 📈 All sensors operating normally

# ผลลัพธ์ display component
I (7432) LAB7-1: 🚀 Lab 7-1: Local Component Demo Started
I (7432) SENSOR: 🔧 Sensor initialized from file: /project/components/Sensors/sensor.c, line: 12
I (7432) SENSOR: 📡 Sensor module ready for operation
I (7432) SENSOR: 📊 Reading sensor data from file: /project/components/Sensors/sensor.c, line: 18
I (7442) SENSOR: 🌡️  Temperature: 28.9°C
I (7442) SENSOR: 💧 Humidity: 91.8%
I (7442) SENSOR: ✅ Sensor status check from file: /project/components/Sensors/sensor.c, line: 30
I (7442) SENSOR: 📈 All sensors operating normally
I (7442) LAB7-1: ----------------------------
I (10442) SENSOR: 📊 Reading sensor data from file: /project/components/Sensors/sensor.c, line: 18
I (10442) SENSOR: 🌡️  Temperature: 34.1°C
I (10442) SENSOR: 💧 Humidity: 81.5%
I (10442) SENSOR: ✅ Sensor status check from file: /project/components/Sensors/sensor.c, line: 30
I (10442) SENSOR: 📈 All sensors operating normally

