## Table of Contents
- [Introduction](#Setup JUnit)
- [Installation](#Debuger)


## Setup JUnit

ให้ทำตามในนี้เลย

[Link Text] https://www.jetbrains.com/help/idea/junit.html#intellij
(ในห้องผมอาาจะกดบางอย่างพลาดไปต้องขออภัยด้วยครับ แต่ว่าทำตาม link นี้ก็ชัวร์สุดแล้ว)

หากว่ามี Project อยู่แล้ว และอยากจะเพิ่ม Test ก็สามารถทำได้เลย 
โดย
  1. ต้องดูก่อนว่าสร้างโปรเจคมาด้วยอะไร Gradle, Maven, INtellij build tool
  2. อ่านตามลิงก์ที่ผมให้ไป และต้องเลือกอ่านให้ถูกอันด้วย

---

## Annotation

[Link Text] https://junit.org/junit5/docs/current/api/org.junit.jupiter.api/org/junit/jupiter/api/package-summary.html

ผมต้องขอโทษด้วยเรื่องที่ผม อธิบายเรื่องลำดับของ Before After ผิดไป

คือ ความจริงแล้ว หากว่าเราไม่ใส่เลขมันจะเป็นอันที่มาก่อน อันที่มีเลข ไม่ใช่ว่า มันไม่อ่าน 

อย่างเช่น

  AfterAllTest

  AfterAllTest0

  ในกรณีนี้ AfterAllTest จะทำงานก่อน AfterAllTest0

---

## Asserion

[Link Text] https://junit.org/junit5/docs/5.0.1/api/org/junit/jupiter/api/Assertions.html

ผมได้เตรียมไฟล์ไว้ให้ลองเล่น 2 ตัวแล้วนะครับ (ที่ชื่อยาวๆ ลองเล่นได้เลยครับ)

---

## Debuger

ผมและ TA Chin ได้เตรียมให้เล่น 3 ตัวอย่างครับ
[Go to Introduction] (#Find_length)
[Go to Introduction] (#Factorial)
[Go to Introduction] (#Palindrome)
 
---

## Find_length

ตัวนี้ผมไม่ได้เตรียม Junit Test มาให้แต่ว่าผมเตรียม Main มาให้ครับ คือ Main_find_length.java
(จริงๆ linkedlist ที่เตรียมไว้ให้มันก็มีช่องให้เล่นเยอะอยู่ จะเล่นหับอันนั้นแทนก็ได้ครับ เพราะผม ลืมเช็คไปหลายเคสเหมือนกัน)

---

## Factorial

อันนี้ TA Chin ได้เตรียม Test มาให้ครับ สามารถใช้ ตัวนั้นแทน Main ได้เลยครับ

---

## Palindrome

อันนี้อันที่ชื่อ Correct คืออันที่ถูกครับ ที่เหลือคืออันที่ ผิด เลือก version ที่ชอบและลองเล่นได้เลยครับ

---