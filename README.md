# Gen Device SCB
## บริการ api generate dsig,dtag,tag,payload สำหรับผู้พัฒนาที่ต้องการ ยิงไป gen device scb ตรงผ่านธนาคารด้วยตัวเอง
payload ที่ส่งมาหาทางเราไม่ต้องส่งข้อมูลบัญชี เลขบัตรประชาชน เบอร์ pin ดังนั้นไม่ต้องห่วงว่าจะโดนดัก deviceId
## telegram : @jur13n https://t.me/jur13n
## ข้อดี
1. ทางผมไม่รู้ deviceId จริงของลูกค้า
2. ทางผมไม่รู้ข้อมูลบัญชีของลูกค้า (วันเกิด,เลขบัตรประชาชน, เบอร์โทร, pin แอพ)
3. gen คีย์ใหม่ทุก request ไม่ใช้คีย์เก่า เพื่อให้ธนาคารไม่สามารถตรวจสอบการใช้คีย์เดิม authen หลายบัญชี
##แพ็คเกจ
1. จ่ายรายครั้ง (pay per use)
2. เช่ารายสัปดาห์ (rental)
   
## สอบถามคุยรายละเอียดเพิ่มเติมได้ที่ telegram : @jur13n https://t.me/jur13n

https://fasteasy.scbeasy.com:8443/v3/login/preloadandresumecheck
https://fasteasy.scbeasy.com:8443/v1/login/getMigrationFlag
https://fasteasy.scbeasy.com:8443/v1/registration/verifyuser
https://fasteasy.scbeasy.com:8443/v1/profiles/generateOTP
https://fasteasy.scbeasy.com:8443/v2/profiles/allowadddevice
https://fasteasy.scbeasy.com:8443/isprint/soap/preAuth
https://fasteasy.scbeasy.com:8443/v1/fasteasy-login
https://fasteasy.scbeasy.com:8443/v1/profiles/devices/

#gen device scb
