# tutorial-git
โปรเจกต์ตัวอย่างสำหรับฝึกใช้งาน Git เพื่อใช้งานส่วนตัวและ ทำงานร่วมกับผู้อื่น

## คำอธิบาย
โฟลเดอร์นี้เก็บไฟล์เว็บไซต์แบบสเตติกสำหรับตัวอย่างการเรียนรู้และการทดลอง
โครงสร้างเรียบง่าย เหมาะสำหรับฝึกการแก้ไขไฟล์ HTML/CSS และการใช้งาน Git

## โครงสร้างไฟล์ 
- `Note.md` — เนื้อหาหรือบันทึกการเรียนรู้ 📌
- `img/` — โฟลเดอร์เก็บรูปภาพ

## แนวทางการพัฒนา (Contributing)

- สร้างสาขาใหม่สำหรับงานของคุณ: `git checkout -b feature/ชื่อ-งาน`
- ทำการแก้ไข และ `git add` + `git commit` ด้วยข้อความที่สื่อความหมาย
- ดันขึ้นรีโมทแล้วเปิด Pull Request เพื่อขอรีวิว

ตัวอย่างคำสั่งพื้นฐาน:

```powershell
git checkout -b feature/update-content
git add .
git commit -m "แก้: ปรับปรุงเนื้อหาใน learn.md"
git push origin feature/update-content
```

## อ้างอิง
[Mikelopster](https://docs.mikelopster.dev/c/basic/git/intro) 🔎
