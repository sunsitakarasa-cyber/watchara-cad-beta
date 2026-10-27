# Watchara CAD Beta

**Based on FreeCAD** · Windows10/11 x64 · รุ่น0.6.0-beta.191

[ดาวน์โหลดตัวติดตั้ง Watchara CAD Beta (640 MB)](https://github.com/sunsitakarasa-cyber/watchara-cad-beta/releases/download/v0.6.0-beta.191/WatcharaCAD-Beta-Setup.exe)

[ไฟล์รุ่นนี้ ซอร์ส ใบอนุญาต และผลตรวจ](https://github.com/sunsitakarasa-cyber/watchara-cad-beta/releases/tag/v0.6.0-beta.191)

ติดตั้ง แล้วเปิด **Watchara CAD Beta** จากเมนู Start เก็บชิ้นงานใน Documents หรือ
โฟลเดอร์งานของคุณ เมื่อต้องการอัปเดต ใช้ **Help → Check for updates** ดาวน์โหลด
บันทึกงาน ปิดโปรแกรม แล้วเปิดใหม่เพื่อใช้รุ่นที่ผ่านการตรวจลายเซ็น

เมื่อพบบั๊ก ส่งหมายเลขรุ่น ขั้นตอนทำซ้ำ และภาพหน้าจอให้ผู้พัฒนาทางแชตตามปกติ
ไม่มีการส่งโมเดลหรือภาพหน้าจออัตโนมัติ

รุ่นนี้แก้การเปิดโปรแกรมจากเส้นทางภาษาไทย/ย้ายตำแหน่งที่ทำให้ Qt โหลดไม่ได้
ผ่านการทดสอบตัวติดตั้งจริง เปิด บันทึก เปิดใหม่ และถอนการติดตั้งในพื้นที่แยก
รวมทั้งตรวจไฟล์ที่ดาวน์โหลดจากช่องทางสาธารณะและหน้าต่างอัปเดตกับ worker จริง
ดูขอบเขตและข้อจำกัดใน [ผลตรวจช่องทางจริง](https://github.com/sunsitakarasa-cyber/watchara-cad-beta/releases/download/v0.6.0-beta.191/LIVE-CHANNEL191.json)

ยังเป็นเบต้า ไม่ใช่การรับรอง1.0หรือทุก Windows/GPU โปรดสำรองงานสำคัญ
ตัวติดตั้งยังไม่มี Windows Authenticode จึงอาจแสดง Unknown publisher
ลายเซ็น Ed25519 สำหรับอัปเดตเป็นคนละส่วนกัน อย่าปิดการป้องกันของ Windows

FreeCAD, Qt/PySide, Open CASCADE และส่วนประกอบอื่นใช้ใบอนุญาตของตนเอง
สิทธิ์แก้ไข/สร้างใหม่/เปลี่ยนไลบรารีตามใบอนุญาตต้นทางยังคงอยู่ กุญแจเผยแพร่
อัปเดตทางการไม่รวมในโปรแกรมผู้ทดลอง ซอร์สที่ตรงรุ่นและวิธีสร้างอยู่ใน release assets
ใช้ไฟล์ **WatcharaCAD-Beta191-Source.zip** เป็นจุดเริ่มต้น; Source ZIP อัตโนมัติ
ของ GitHub repository นี้เป็นเพียงข้อมูลช่องทางเผยแพร่

Installer SHA256: `93cbadc99da912b2438c79d19bf7fc305620d50ac32d168aab0c15b50f235e37`
