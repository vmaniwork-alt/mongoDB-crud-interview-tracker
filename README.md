This project is a simple MongoDB-based application that demonstrates basic database operations using a real-world use case – tracking failed interview experiences.

The system stores interview details such as company name, role, reason for failure, rounds cleared, and retry status.  
It helps analyze common weaknesses and improve future interview preparation.
# mongoDB-crud-interview-tracker
# MongoDB Interview Experience Tracker
---

## 🛠 Technologies Used
- MongoDB
- MongoDB Shell (mongosh)

---

## 📂 Database Structure

*Database Name:* interviewDB  
*Collection Name:* interviews

### Sample Document:
```js
{
  company: "Zoho",
  role: "Frontend Developer",
  reason: "Low JavaScript Knowledge",

🔄 Operations Covered

✅ Create

insertOne()

insertMany()


📖 Read

find()

Filters & Query Operators ($gt, $exists, etc.)


🔁 Update

updateOne()

updateMany()

$set, $inc


❌ Delete

deleteOne()

deleteMany()

drop() (collection & database)
  roundCleared: 2,
  retry: true
}
