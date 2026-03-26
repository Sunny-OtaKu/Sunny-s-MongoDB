# Sunny-s-MongoDB
This Repository Involve basic DataBase created using basic queries of MongoDB. 
# MongoDB Shell Practice

This repository contains basic operations and queries performed using the MongoDB shell. It is intended for learning and practicing core database concepts using MongoDB.

---

##  Contents

* Database creation:<img width="1919" height="1005" alt="Screenshot 2026-03-26 135017" src="https://github.com/user-attachments/assets/a434b8ec-a8bb-4993-b42d-4932721eb1ae" />

* Collection creation: <img width="1427" height="887" alt="Screenshot 2026-03-26 134803" src="https://github.com/user-attachments/assets/ba4d5cc2-1731-456f-a86a-134b35e9ce43" />

* Insert operations: <img width="1427" height="887" alt="Screenshot 2026-03-26 134803" src="https://github.com/user-attachments/assets/97442882-a430-44a5-bc02-71ba2fcc59bd" />

* find documents:<img width="1429" height="887" alt="Screenshot 2026-03-26 134837" src="https://github.com/user-attachments/assets/fdc2673a-53b2-4964-8d82-f94d3dcbe1a3" />

* Update operations:<img width="1429" height="887" alt="Screenshot 2026-03-26 134837" src="https://github.com/user-attachments/assets/affe13e1-7cf8-4dc7-b9fa-119c13dcc375" />

* View/quiry/Show all Documents: <img width="1423" height="887" alt="Screenshot 2026-03-26 134856" src="https://github.com/user-attachments/assets/fdd57bea-df31-41e0-899d-dc811b16893f" />

* Delete operations:<img width="1428" height="885" alt="Screenshot 2026-03-26 134920" src="https://github.com/user-attachments/assets/aa906941-8376-4bda-8055-f6b4e4adbdef" />

* Drop Collection: <img width="1428" height="885" alt="Screenshot 2026-03-26 134920" src="https://github.com/user-attachments/assets/ad83c384-6ac3-4a35-9202-0825d1a19080" />



---

##  Tools Used

* MongoDB Shell (mongosh)
* MongoDB Database

---

## File Structure

```
mongodb-basic-practice/
│── mongo-commands.js
│── README.md
```


##  Sample Operations

### 1. Create Database

```
use myDatabase
```

### 2. Create Collection

```
db.createCollection("users")
```

### 3. Insert Document

```
db.users.insertOne({
  name: "John",
  age: 25,
  city: "New York"
})
```

### 4. Find Documents

```
db.users.find()
```

### 5. Update Document

```
db.users.updateOne(
  { name: "John" },
  { $set: { age: 26 } }
)
```

### 6. Delete Document

```
db.users.deleteOne({ name: "John" })
```

---

##  Purpose

This project is created for practicing MongoDB shell commands and understanding basic database operations.

---
##  Author

Your Name
Samartha S

##  License

This project is open-source and free to use.
