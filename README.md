# MongoDB-PetAdoption-DBMS
A Pet Adoption Management System built using Python (Tkinter) and MongoDB Atlas.
This project allows users to manage Pets, Adopters, and Adoptions with a simple GUI and cloud database.

🚀 Features

✔ Add, Update, Delete Pets
✔ Add, Update, Delete Adopters
✔ Record Pet Adoptions
✔ Search & Filter Pets / Adopters
✔ Clean Tkinter UI
✔ Fully connected to MongoDB Atlas Cloud Database
✔ Real-time CRUD operations

🛠 Tech Stack
Component	Technology
Frontend	Tkinter (Python GUI)
Backend	Python
Database	MongoDB Atlas (Cloud NoSQL DB)
Driver	PyMongo
Version Control	Git & GitHub
📁 Project Structure
PetAdoption/
├── main.py
├── db.py
├── pets_page.py
├── adopters_page.py
├── adoptions_page.py
└── README.md

🔧 Installation & Setup Instructions

Follow these steps to run the project on your computer:

1️⃣ Clone the Repository
git clone https://github.com/vidit1920/MongoDB-PetAdoption-DBMS.git
cd MongoDB-PetAdoption-DBMS

2️⃣ Install Required Packages

Make sure you have Python installed (3.10+ recommended).
Then run:

pip install pymongo


Tkinter usually comes pre-installed with Python.
If missing (Linux only):

sudo apt-get install python3-tk

3️⃣ Configure MongoDB Atlas Connection

Open db.py and replace:

MONGO_URI = "YOUR_CONNECTION_LINK"


with your own MongoDB URI from Atlas:

Example:

MONGO_URI = "mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/?retryWrites=true&w=majority"


⚠️ Important:
Never share your actual MongoDB password publicly.

4️⃣ Run the Application

Run the main file:

python main.py

🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first.

📄 License

This project is for educational purposes (DBMS Mini Project – Python + MongoDB).

⭐ Support the Project

If you found this useful, please star the repository ⭐ on GitHub!

