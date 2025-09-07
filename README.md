<html>
<head><title>สื่อการสอนภาษาซี</title></head>
<body >
<h1><B><p align=center>โครงสร้างภาษาซี</h1></p></B>
<dd><br>โครงสร้างของภาษาซี++ คือรูปแบบพื้นฐานในการเขียนโปรแกรมที่กำหนดลำดับขั้นตอนและส่วนประกอบต่างๆ</dd>
ของโค้ดเพื่อให้คอมไพล์และทำงานได้อย่างถูกต้อง โดยโปรแกรม C++ ทุกโปรแกรมจะเริ่มต้นที่ฟังก์ชัน main()
<br>ซึ่งเป็นจุดเริ่มต้นการทำงานของโปรแกรม </br>
<br><dd>โครงสร้างหลักจะประกอบด้วยส่วนการเรียกใช้ไลบรารี (#include)

</dd></br></p>
<h3> การเขียนโครงสร้างและคำอธิบาย</h3>
<dd><p><xmp>   #include <iostream>           // 1. เรียกใช้ไลบรารีสำหรับแสดงผล
   // 2. ฟังก์ชันหลักของโปรแกรม
    int main() {
    // 3. การประกาศตัวแปร
    int age = 20;             // ประกาศตัวแปรเก็บอายุ
    float score = 85.5;       // ตัวแปรทศนิยม
    char grade = 'B';         // ตัวแปรอักขระ

    // 4. แสดงผลบนหน้าจอ
    cout << "Age: " << age << endl;
    cout << "Score: " << score << endl;
    cout << "Grade: " << grade << endl;

    // 5. การรับค่าจากผู้ใช้
    cout << "Enter your age: ";
    cin >> age;
    cout << "Your new age is: " << age << endl;

    // 6. เงื่อนไข if-else
    if (age >= 18) {
        cout << "You are an adult." << endl;
    } else {
        cout << "You are a minor." << endl;
    }

    // 7. ลูป for
    for (int i = 1; i <= 5; i++) {
        cout << "Count: " << i << endl;
    }

    // 8. การเรียกใช้ฟังก์ชัน
    int result = add(5, 3);
    cout << "5 + 3 = " << result << endl;

    return 0; //9. คืนค่าจบการทำงาน
}

// 10. ฟังก์ชันภายนอก
int add(int a, int b) {
    return a + b;
}
</xmp></dd></p><

<a href=" https://onecompiler.com/c ">ลิงค์ทดลอง</a>

</body>
</html>
