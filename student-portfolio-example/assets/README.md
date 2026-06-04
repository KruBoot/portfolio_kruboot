# Assets

โฟลเดอร์นี้ใช้เก็บไฟล์ประกอบ Portfolio เช่น รูปภาพ เกียรติบัตร เอกสาร PDF หรือไฟล์ผลงานอื่น ๆ

## ตัวอย่างไฟล์ที่สามารถเก็บได้

```text
assets/
├── profile-photo.jpg
├── peer-support-poster.png
├── peer-support-activity-photo.jpg
├── short-video-screenshot.png
├── reading-journal-sample.jpg
├── certificate-positive-communication.pdf
└── certificate-library-volunteer.pdf
```

## แนวทางการตั้งชื่อไฟล์

- ใช้ภาษาอังกฤษตัวพิมพ์เล็ก
- ใช้เครื่องหมาย `-` คั่นคำ
- ตั้งชื่อให้รู้ว่าไฟล์เกี่ยวกับอะไร
- หลีกเลี่ยงชื่อไฟล์เช่น `IMG_1234.jpg` หรือ `finalfinal.pdf`

## ข้อควรระวัง

- ไม่ควรอัปโหลดข้อมูลส่วนตัวที่ละเอียดเกินไป เช่น เลขบัตรประชาชน ที่อยู่ หรือเบอร์โทรศัพท์
- ถ้ามีรูปเพื่อนหรือครู ควรขออนุญาตก่อนเผยแพร่
- ตรวจสอบว่าไฟล์เปิดดูได้จริง
- ถ้าใช้ภาพจากอินเทอร์เน็ต ต้องระบุแหล่งที่มาและใช้ภาพที่มีสิทธิ์เหมาะสม

## วิธีอ้างอิงไฟล์ภาพใน Markdown

ตัวอย่างการใส่รูปในไฟล์ Markdown

```markdown
![โปสเตอร์กิจกรรม Peer Support](assets/peer-support-poster.png)
```

ถ้าไฟล์ Markdown อยู่ในโฟลเดอร์ย่อย เช่น `projects/` ให้ย้อนกลับมาก่อน 1 ระดับ

```markdown
![โปสเตอร์กิจกรรม Peer Support](../assets/peer-support-poster.png)
```
