# Balancing

## Tahap 1 Testing MPU 6050 pada Arduino UNO

**Komponen:** 
1. Arduino UNO
2. MPU6050
3. Female-Male Jumper 4x

**Koneksi pada Arduino UNO R3**
1. VCC   5v
2. GND   GND
3. SCL   A5
4. SDA   A4

**Tujuan:**
1. Tes sensor MPU6050
2. Proses bacaan sensor untuk menampilkan RPY
3. Proses bacaan sensor untuk menampilkan akselerometer
4. Filtering RPY menggunakan Kalman Filter

**Libraries**
1. MPU6050: https://github.com/jarzebski/Arduino-MPU6050
2. Kalman Filter RPY: https://github.com/jarzebski/Arduino-KalmanFilter


**Hasil:**
1. Sensor bekerja
2. Mampu menampilkan RPY pada terminal
3. Mampu menampilkan percepatan pada terminal
4. Data RPY dapat terfilter dengan baik menggunakan Kalman Filter

## Tahap 2 Implementasi MPU6050 pada OpenCM 9.04

**Komponen:** 
1. OpenCM
2. MPU6050
3. Female-Female Jumper 5x

**Koneksi pada OPENCM 9.04**
1. VCC   5v
2. GND   GND
3. SCL   D24
4. SDA   D25
5. INT   A2

**Tujuan:**
1. Tes sensor MPU6050
2. Proses bacaan sensor untuk menampilkan RPY
3. Proses bacaan sensor untuk menampilkan akselerometer
4. Filtering RPY menggunakan Kalman Filter

**Libraries**
1. LIbrary OpenCM 9.04 MPU6050 with DMP https://emanual.robotis.com/docs/en/parts/controller/opencm904/#arduino-ide

**Hasil**
1. Tes sensor berhasil
2. Sensor berhasil membaca RPY
3. 
