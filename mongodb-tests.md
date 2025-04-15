# MongoDB bo'yicha testlar (25 ta savol)

## Testlar

1. MongoDB nima?
   B) NoSQL ma'lumotlar bazasi

2. MongoDB qanday formatda ma'lumotlarni saqlaydi?
   C) BSON (Binary JSON)

3. MongoDB-da jadval ekvivalenti nima deb ataladi?
   B) Collection

4. MongoDB-da "qator" qanday nomlanadi?
   D) Document

5. MongoDB-da primary key qanday nomlanadi?
   A) \_id

6. MongoDB-da ma'lumotlar bazasini yaratish uchun qaysi buyruq ishlatiladi?
   B) use dbname

7. MongoDB-da kolleksiyani yaratish uchun qaysi buyruq ishlatiladi?
   B) db.createCollection("collectionName")

8. MongoDB-da documentni qo'shish uchun qaysi metod ishlatiladi?
   C) db.collection.insertOne()

9. MongoDB-da bir nechta documentni qo'shish uchun qaysi metod ishlatiladi?
   B) db.collection.insertMany()

10. MongoDB-da kolleksiyalarni ko'rish uchun qaysi buyruq ishlatiladi?
    A) show collections

11. MongoDB-da ma'lumotlar bazalarini ko'rish uchun qaysi buyruq ishlatiladi?
    A) show databases

12. MongoDB-da documentlarni izlash uchun qaysi metod ishlatiladi?
    B) db.collection.find()

13. MongoDB-da documentlarni yangilash uchun qaysi metod ishlatiladi?
    A) db.collection.updateOne()

14. MongoDB-da documentlarni o'chirish uchun qaysi metod ishlatiladi?
    B) db.collection.deleteOne()

15. MongoDB-da kolleksiyani o'chirish uchun qaysi buyruq ishlatiladi?
    C) db.collection.drop()

16. MongoDB-ning qaysi operatori tenglikni tekshiradi?
    A) $eq

17. MongoDB-da ma'lumotlarni tartiblash uchun qaysi metod ishlatiladi?
    B) db.collection.find().sort()

18. MongoDB-da natijalarni cheklash uchun qaysi metod ishlatiladi?
    B) db.collection.find().max()

19. MongoDB-da ma'lumotlarni aggregatsiya qilish uchun qaysi metod ishlatiladi?
    C) db.collection.aggregate()

20. MongoDB-da kolleksiyani indekslash uchun qaysi metod ishlatiladi?
    C) db.collection.index()

21. MongoDB-da "kattaroq" operatori qanday belgilanadi?
    A) $gt

22. MongoDB-da "teng yoki kichikroq" operatori qanday belgilanadi?
    C) $lte

23. MongoDB-da ma'lumotlarni sahifalash uchun qaysi metodlar juftligi ishlatiladi?
    A) skip() va limit()

24. MongoDB replica set nima uchun ishlatiladi?
    B) Ma'lumotlar zaxirasini yaratish va yuqori mavjudlikni ta'minlash uchun

25. MongoDB sharding nima?
    B) Ma'lumotlarni bir nechta serverga taqsimlash
