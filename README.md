# 155-495 Robotics

 เนื้อหาวิชาแบ่งออกเป็น  2  ส่วนคือ  Mobile Robot  และ  Industrail Robot
 
Mobile Robot 
    เรียนเกี่ยวกับหุ่นยนต์ที่ไม่ได้ถูกยึดติดตรึงอยู่กับที่ สามารถเคลื่อนที่เปลี่ยนตำแหน่งได้ ทั้งแบบมีขา มีล้อ  เคลื่อนที่บนพื้นราบ  หรือชนิดใบพัดเคลื่อนที่ในอากาศ  หรือเคลื่อนที่ในน้ำเป็นต้น
 
เนื้อหาวิชาจะศึกษาทำความเข้าใจโครงสร้างของหุ่นยนต์ประเภท Mobile Robot และส่วนสั่งการควบคุม โดยเนื้อวิชาเน้นการเขียนโปรแกรมควบคุมสั่งการโดยใช้   ROS  ซึ่งเป็น Robot Framework

Industrail Robot 
    เรียนเกี่ยวกับหุ่นยนต์อุตสาหกรรมประเภทต่างๆ เช่น 
    
    * Gantry Robot แขนกลเคลื่อนที่ไปมาด้วย Prismatic Joint ซึ่งมีลักษณะยืดหดหรือเลื่อนไปมาเป็นเชิงเส้น ตามแนวแกน X Y Z (3P) มีพื้นที่ทำงาน (Working Space) เป็นรูปทรงสี่เหลี่ยมผืนผ้า
    * Cylindrical Robot แขนกลเคลื่อนที่หมุนรอบแกน 1 แกน และเคลือ่นที่ โดยมีข้อต่อที่เป็นการหมุนรอบแกน Rotational Joint ร่วมกับ Prismatic Joint  (R2P) มีพื้นที่ทำงาน (Working Space) เป็นรูปทรงกระบอก 
    * Spherical Robot แขนกลจะมีแกนหมุนรอบแกน 2 แกน และมี Prismatic Joint รวมด้วย (2RP) ทำให้มีพื้นที่ทำงาน (Working Space) เป็นรูปทรงครึ่งวงกลม
    * Joined Sperial Robot หรือนิยมเรียกว่า Articulated Robot แขนกลจะมีข้อต่อประเภทแกนหมุนรอบแกนตั้งแต่ 3 แกนขึ้นไป ทำให้มีความอิสระในการเข้าถึงตำแหน่งได้หลากหลายรูปแบบ นิยมใช้ในอุตสาหกรรม  มีพื้นที่ทำงาน (Working Space) เป็นทรงกลมเกือบเต็ม (คล้ายลูกบอลที่โดนเฉือนบางส่วน)
    * Delta  Robot เป็นหุ่นยนต์ที่ถูกติดตั้งไว้ส่วนบนแล้วให้แขนกลห้อยลงมาปฏิบัติงานด้านล่าง จะประกอบด้วยแกนหมุน Rotational Joint 3 แกน สำหรับใช้บังคับการเคลื่อนที่ของปลายแขน และอาจมีแกนหมุนที่ส่วนปลายแขนเพิ่มเพื่อให้หมุนหันเครื่องมือไปในด้านต้องการ  4R  หุ่นยนต์ประเภทนี้ทำงานได้รวดเร็ว แต่รับภาระน้ำหนักได้ไม่มาก นิยมใช้ในงานหยิบจับชิ้นส่วนอิเล็กทรอนิกส์ในการประกอบแผงวงจร หรืองานอื่นๆที่มีลักษณะคล้ายกัน เนื่องจากทำงานได้เร็วแม่นยำ
    
 ## การใช้งาน Industrial Robot 
 
 ในวิชานี้จะมีวัตถุประสงค์ให้เข้าใจในภาพรวมของการใช้งาน Industail Robot จึงได้เลือกเครื่องมือคือ ABB Robot Studio ซึ่งมีความสามารถในการเขียนโปรแกรมเพื่อสั่งการและจำลองการทำงานของแขนกลได้
 นักศึกษาสามารถใช้งานในแบบ FreeTrial ได้ในระยะเวลาที่กำหนด 
 
 วิธีติดตั้ง
  1 Download โปรแกรมล่าสุดได้จาก Link
  
  https://new.abb.com/products/robotics/robotstudio/downloads
 
 
