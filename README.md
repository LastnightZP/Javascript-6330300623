#หนูมีการดึง apiที่ใช้ในการพูดออกเสียงมาใช้ มีการสร้างออพเจคแล้วก็กำหนดรวมทั้งควบคุมข้อความที่จะพูดออกเสียง
มีการตั้งค่า event listener เมื่อเสียง (voices) เปลี่ยนในระบบ ซึ่งจะถูกเรียกเมื่อรายชื่อเสียงที่ใช้ในการพูดข้อความมีการเปลี่ยนแปลง ในบรรทัดนี้จะทำการอัปเดตรายชื่อเสียงในอาร์เรย์ voices และเลือกเสียงแรกในรายชื่อนั้นให้กับอ็อบเจ็กต์ 
แล้วก็มีการใช้ ตัวช่วยในการตรวจจับแบบ event ที่ตอนกดปุ่มเพื่อให้ทำการอ่าน text โดยทันที การรันก็คือรันผ่านไลฟ์ server ปกติค่า
