# 🏢 UP Dorm Finder (v2)
**แอปพลิเคชันรวบรวมและค้นหาหอพักสำหรับนิสิตมหาวิทยาลัยพะเยา** โปรเจกต์นี้สร้างขึ้นเพื่อช่วยให้นิสิตใหม่ (และรุ่นพี่) สามารถค้นหาหอพักที่ตอบโจทย์ Lifestyle ได้ง่ายขึ้น โดยเน้นข้อมูลที่ "ตรงปก" และระบบการกรองข้อมูลที่ละเอียดเหมือนแอปจองที่พักระดับโลก

---

## ✨ Features (จุดเด่นของระบบ)

- 🔍 **Advanced Search & Filter:** ค้นหาหอพักตามโซน (หน้า ม., แม่กา, ในเมือง) และช่วงราคา
- 🏷️ **Smart Tagging:** ระบบแท็กอัจฉริยะภาษาไทย (แต่เก็บข้อมูลเป็นสากล) เช่น `#ค่าไฟหลวง`, `#ใกล้รถเมล์ม่วง`, `#เลี้ยงสัตว์ได้`
- 📍 **Spatial Context:** คำนวณระยะทางจากหอพักไปยังประตูหน้า ม.พะเยา และจุดจอดรถโดยสาร
- 🛡️ **Trust & Safety:** มีระบบ Verified สำหรับหอพักที่ผ่านการตรวจสอบข้อมูลแล้ว
- 📱 **Mobile First:** ออกแบบมาให้ใช้งานได้ลื่นไหลบนสมาร์ทโฟน

---

## 🛠️ Tech Stack

- **Framework:** [Next.js 16](https://nextjs.org/) (App Router)
- **Database:** [PostgreSQL](https://www.postgresql.org/) (via Supabase / Neon)
- **ORM:** [Prisma 7](https://www.prisma.io/) (Wasm-first Architecture)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Deployment:** [Vercel](https://vercel.com/)

---

## 🚀 Getting Started (วิธีรันโปรเจกต์ในเครื่อง)

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/thammarat-ai/up_dorm_finder_v2.git](https://github.com/thammarat-ai/up_dorm_finder_v2.git)
   cd up_dorm_finder_v2

```

2. **Install dependencies:**
```bash
npm install

```


3. **Set up Environment Variables:**
สร้างไฟล์ `.env` ที่ root directory และเพิ่มค่าดังนี้:
```env
DATABASE_URL="your_database_connection_string"

```


4. **Initialize Database:**
```bash
npx prisma generate
npx prisma db push

```


5. **Run the development server:**
```bash
npm run dev

```


เปิดหน้าเว็บที่ [http://localhost:3000]
---

## 🤝 Contribution (การมีส่วนร่วม)

โปรเจกต์นี้ยินดีรับไอเดียและการพัฒนาเพิ่มเติมจากทุกคน!
หากคุณมีฟีเจอร์ที่อยากได้ หรือพบข้อผิดพลาด (Bugs):

1. **Open an Issue:** หากมีข้อเสนอแนะหรือต้องการ Request Feature ใหม่ๆ สามารถเปิด [Issue](https://www.google.com/search?q=https://github.com/thammarat-ai/up_dorm_finder_v2/issues) ไว้ได้เลยครับ
2. **Submit a Pull Request:** - Fork โปรเจกต์นี้
* สร้าง Branch ใหม่ (`git checkout -b feature/AmazingFeature`)
* Commit การเปลี่ยนแปลงของคุณ (`git commit -m 'Add some AmazingFeature'`)
* Push ไปที่ Branch (`git push origin feature/AmazingFeature`)
* เปิด Pull Request มาหาเรา



---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

**พัฒนาโดย:** [Thammarat-ai](https://github.com/thammarat-ai)

*มุ่งหวังให้การหาหอพักที่ มพ. เป็นเรื่องง่ายสำหรับทุกคน 💜💛*

```

