 HR Request Simulator (Python Project)

  Overview

This is a simple HR system simulator built with Python to practice Object-Oriented Programming (OOP) basics.

It allows employees to submit requests for:

* ✈️ Vacation
* 🏖️ Leave
* ⏱️ Overtime

Only managers have the authority to approve or reject these requests. Employees cannot approve or reject requests for themselves or others.

This project focuses on enforcing **role-based rules** in a workplace-like scenario.

---

 ⚙️ Features

* 👤 Add managers and employees.
* 📝 Employees can submit vacation/leave/overtime requests.
* ✅ Managers can approve or reject requests.
* 🚫 Employees cannot approve/reject requests.
* 🔄 Tracks the status of each request (Pending → Approved/Rejected).

---

 🧰 Tech Used

Python 3
 No external libraries (built only with core Python basics).

---

 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/your-username/HR-Request-Simulator.git
   cd HR-Request-Simulator
   ```

2. Run the program:

   ```bash
   python hr_request_simulator.py
   ```

---

 📸 Example Output


Request submitted: [1] VACATION by Eve — PENDING
Unauthorized action: Employees cannot approve/reject requests.
Request 1 APPROVED by Alice (Manager).


---

🎯 Learning Goals

Through this project, I practiced:

* ✅ Building and using classes in Python
* ✅ Implementing inheritance
* ✅ Enforcing role-based restrictions
* ✅ Tracking and updating request status

---

 💡 Future Improvements

* Add attendance tracking (clock in/clock out).
* Store employee requests in a file (CSV or JSON).
* Build a Flask version for web simulation.

---

 🙌 Acknowledgements

This project is part of my Python learning journey, where I focus on building real-world inspired mini-projects to practice the basics.

---


