# ระบบติดตามและคาดการผลผลิต

> ภาคเรียนที่ 2 ปีการศึกษา 2566
>
> เป็นส่วนหนึ่งของโครงงาน วิชา 90642171 TEAM-PROJECT 1

## Table of Contents

- [ระบบติดตามและคาดการผลผลิต](#ระบบติดตามและคาดการผลผลิต)
  - [Table of Contents](#table-of-contents)
  - [Links](#links)
  - [รายชื่อสมาชิก](#รายชื่อสมาชิก)
  - [อาจารย์ที่ปรึกษา](#อาจารย์ที่ปรึกษา)
  - [วัตถุประสงค์ของโครงงาน](#วัตถุประสงค์ของโครงงาน)
  - [ภาพรวมโครงงาน](#ภาพรวมโครงงาน)
  - [แนวคิด ที่มา และสิ่งที่เคยมีมา](#แนวคิด-ที่มา-และสิ่งที่เคยมีมา)
  - [Tech Stack](#tech-stack)
  - [Languages](#languages)

## Links

- [IoT](https://github.com/Team-Project-Durian/RFID_Reader)
- [Backend](https://github.com/Team-Project-Durian/backend-api)

## รายชื่อสมาชิก

- 66010086 นายโกเมศ ประกอบผล
- 66010255 นายณัฐพัชร์ เจียรยุทธศักดิ์
- 66011314 นายกฤษณ์ เกษมเทวินทร์
- 66011344 นายฐิติพันธุ์ สอนโคตร

## อาจารย์ที่ปรึกษา

- ดร.ธนวิชญ์ อนุวงศ์พินิจ

## วัตถุประสงค์ของโครงงาน

1. เพื่อติดตามการเจริญเติบโต และควบคุมคุณภาพของผลผลิต
2. เพื่อให้ผู้บริโภคมีความไว้วางใจในผลผลิต
3. เพื่อเพิ่มมูลค่าให้กับผลผลิต
4. เพื่อนำข้อมูลที่ได้ไปวางแผนและพัฒนาผลผลิตในอนาคต

## ภาพรวมโครงงาน

เป็นระบบติดตามและคาดการผลผลิตโดยใช้ 3 ระบบที่นำมาทำงานร่วมกัน

1. Radio Frequency Identification (RFID)[^1]
2. Web Applications[^2]
3. Weather Stations[^3]

[^1]: RFID เป็นระบบระบุตัวต้นไร้สาย โดยใช้เคลื่อนความถี่วิทยุในการระบุตัวตนของผลผลิตนั้นๆ
[^2]: Web Applications เป็นระบบเว็บไซน์ซึ่งรวมไปด้วย ระบบคาดการและติดตาม ฐานข้อมูล ระบบรายงานสภาพภูมิอากาศ
[^3]: Weather Stations สถานีตรวจวัดสภาพอากาศ สำหรับข้อมูลในท้องที่นั้นๆ

## แนวคิด ที่มา และสิ่งที่เคยมีมา

&emsp;&emsp;&emsp;&emsp;สังคมในอดีต ปัจจุบัน หรือแม้แต่ในอนาคตการบริโภคทุเรียนก็ยังมีแนวโน้วจะเพิ่มขึ้นเรื่อยๆเนื่องจากรสชาติที่ถูกใจหลายๆคนและประโยชน์จากการบริโภคที่ได้รับ เพื่อให้ได้คุณภาพทุเรียนที่ดีที่สุด คณะผู้จัดทำถึงได้จัดทำโครงการค้นคว้าการติดตามการเจริญเติบโตของทุเรียนขึ้นมา

&emsp;&emsp;&emsp;&emsp;เพื่อให้ทราบระยะเวลาที่เหมาะสมของทุเรียนเเต่ละลูกว่ามีอายุเหมาะแก่การเก็บเกี่ยวหรือไม่ โดยโครงการนี้จะทำให้สามารถควบคุมคุณภาพของผลผลิตได้อย่างสม่ำเสมออีกทั้งยังลดเวลาที่ต้องตรวจสอบทุเรียนด้วยวิธีการเดิมๆ และสามารถนำข้อมูลไปวิเคราะห์และใช้ประโยชน์ต่อไป ทำให้ทุเรียนของเรามีจุดขายมากขึ้น เพื่อสร้างให้ทุเรียนมีมูลค่ามากขึ้น

## Tech Stack

- [VS Code](https://code.visualstudio.com/): IDE
- [Arduino IDE](https://www.arduino.cc/en/software): IDE
- [Node.js](https://nodejs.org/en/): Javascript runtime
- [Express.js](https://expressjs.com/): Web framework for Node.js
- [Typescript](https://www.typescriptlang.org/): Strong type Javascript
- [Prisma](https://www.prisma.io/): Typescript ORM
- [PostgreSQL](https://www.postgresql.org/): Database
- [Node-RED](https://nodered.org/): Flow-based programming for IoT
- [Mosquitto](https://mosquitto.org/): MQTT broker
- [Docker](https://www.docker.com/): Containerization
- [Portainer](https://www.portainer.io/): Docker management
- [Cloudflare](https://www.cloudflare.com/): DNS, CDN, SSL
- [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/): Expose local server to the internet
- [Nginx Proxy Manager](https://nginxproxymanager.com/): Reverse proxy
- [Proxmox](https://www.proxmox.com/en/): Hypervisor
- [GitHub](https://github.com): Version control

## Languages

- [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Typescript](https://www.typescriptlang.org/)
- [C++](https://en.wikipedia.org/wiki/C%2B%2B)
