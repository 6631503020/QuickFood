# QuickFood
Thanakit Chupviroj_6631503020

ชื่อ - นามสกุล (Full Name): Thanakit Chupviroj

รหัสนักศึกษา (Student ID): 6631503020

ชื่อแอป (App Name): QuickFood

Framework ที่ใช้ (Framework Used): Flutter / React Native / อื่น ๆ

ลิงก์ GitHub Repository: [ใส่ลิงก์ที่นี่ | Insert link here] //////

ลิงก์ไฟล์ติดตั้ง (APK/IPA): https://expo.dev/accounts/thanakitchupviroj/projects/QuickFood/builds/08b5fd58-0005-4257-bc0a-478316b22991


----------------------------------------------------------------

# 1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)
1.1 ผู้ใช้งานเป้าหมาย | User Personas

Persona 1:  
- ชื่อ: นุ่น  
- อายุ: 20 ปี  
- อาชีพ: นักศึกษาปี 2  
- ความต้องการ: ต้องการสั่งอาหารผ่าน Application Delivery ง่ายและ Ui ที่เป็นมิตรดูง่ายสั่งสะดวก

Persona 2:  
- ชื่อ: น็อต  
- อายุ: 24 ปี  
- อาชีพ: นักศึกษาฝึกงาน  
- ความต้องการ: ต้องการหา Application Delivery Food ที่สะดวกและใช้งานง่าย
1.2 เป้าหมายของแอป | App Goals

- ช่วยทำให้ผู้ใช้ใช้งานสะดวก
- มี Ui ที่เรียบง่ายและสบายตาสำหรับผู้ใช้
- มีร้านอาหารที่หลากหลาย
  
1.3 โครงร่างหน้าจอ / Mockup
ใส่รูปภาพ หรือคำอธิบายแต่ละหน้าหลัก 3 หน้า | Attach image or describe 3 main pages

1.4 การไหลของผู้ใช้งาน | User Flow

เปิดแอป > เข้าหน้าหลัก > สมัครสมาชิก > เลือก "ร้านอาหาร" > กดดู "เมนู" > เลือกเมนู "ใส่ตะกร้า" > จ่ายเงิน

----------------------------------------------------------------

# 2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
2.1 รายละเอียดการพัฒนา | Development Details
เครื่องมือที่ใช้ / Tools used:

- React Native
- Expo
- Package: Provider, SharedPreferences, React-Navigation, react-native-safe-area-context, react-native-screens, react-native-vector-icons
2.2 ฟังก์ชันที่พัฒนา | Features Implemented
Checklist:

- [x] เพิ่ม / ลบ อาหารได้
- [x] มีรีวิวดาวไว้ให้ผู้ใช้งานดู
- [x] สแกนจ่ายเงิน
- [ ] ซิงก์กับ Google Map
2.3 ภาพหน้าจอแอป | App Screenshots
แนบภาพหรือ URL (Attach images or image links):
- ![image](https://github.com/user-attachments/assets/a5a0b5d9-1ba5-4556-8fd9-c2fe18f0351a)
- ![image](https://github.com/user-attachments/assets/d36655c8-6713-411a-8758-accbb5f22499)
- ![image](https://github.com/user-attachments/assets/619d28d5-2184-4c37-a5b7-2add7f98af12)

----------------------------------------------------------------

# 3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)
3.1 ประเภท Build | Build Type
[x] Debug
[ ] Release
3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested
[x] Android
[ ] iOS
3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide
แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps

1. ดาวน์โหลดไฟล์ .apk
2. เปิดในอุปกรณ์ Android
3. ติดตั้งผ่าน File Manager
----------------------------------------------------------------

# 4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)

- พบปัญหาเวลาใช้ setState ใน async function แล้วค่าที่เปลี่ยนไม่ทันแสดงผล
- เจอ error เรื่อง Cannot redeclare block-scoped variable 'styles' จากการประกาศซ้ำในหลายไฟล์
- ยังไม่เข้าใจการจัดโฟลเดอร์ src/screens, components, navigation ในช่วงแรก ต้องใช้เวลาเรียนรู้
- หากมีเวลาเพิ่ม อยากทำระบบ Login และเชื่อม Firebase เพื่อบันทึกข้อมูลคำสั่งซื้อ

----------------------------------------------------------------

# 5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)
5.1 ใช้ AI ช่วยคิดไอเดีย | Idea Generation

Prompt ที่ใช้:  
"ช่วยคิดไอเดียแอพสั่งอาหารสำหรับร้านแถวมหาวิทยาลัยแม่ฟ้าหลวง"
ผลลัพธ์:
ได้แนวคิดแอพชื่อ QuickFood สำหรับรวมร้านอาหารในพื้นที่และมีระบบตะกร้าสั่งอาหาร

5.2 ใช้ AI ช่วยออกแบบ UI | UI Layout Prompt
Prompt ที่ใช้:
"ช่วยออกแบบ layout แอพสั่งอาหารแบบมีหน้า Home, Cart, Signup"
ผลลัพธ์:
ได้ไอเดียการจัดหน้าแอพแบบแยกหน้าชัดเจน พร้อมแถบ navigation ด้านล่าง (Bottom Tabs)

5.3 ใช้ AI ช่วยเขียนโค้ด | Code Writing Prompt
Prompt ที่ใช้:
"เขียน React Native ด้วย Expo ให้มี navigation bar และหน้าแสดงร้านอาหาร"
ผลลัพธ์:
ได้โครงสร้างโฟลเดอร์ src/screens, components, navigation พร้อม code สำหรับ Bottom Tab Navigation และรายการอาหาร

5.4 ใช้ AI ช่วย debug | Debug Prompt

Prompt ที่ใช้:

"Cannot redeclare block-scoped variable 'styles'"

ผลลัพธ์:

AI อธิบายสาเหตุว่าเกิดจากการประกาศ const styles ซ้ำ และแนะนำให้ใช้ชื่อเฉพาะในแต่ละไฟล์ เช่น homeStyles, cartStyles

5.5 ใช้ AI ช่วย Deploy | Deployment Prompt

Prompt ที่ใช้:

"ทำยังไงให้รันApp บน Android ได้"

ผลลัพธ์:

ได้คำแนะนำให้ใช้คำสั่ง 
eas login
eas build:configure
eas build -p android --profile preview
เพื่อทดสอบแอพได้ทันที
