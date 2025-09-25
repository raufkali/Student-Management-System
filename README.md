# 🎓 SmartDesk — School Management System (MERN)

SmartDesk is a **role-based school management system** built with the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.  
It provides **separate dashboards** for **Admin, Teachers, and Students** with authentication and role-based access.


configure frontend:
cd frontend
npm install
npm start


configure backend:
<pre>bash
cd backend
npm install
npm start
</pre>

Configure mongodb:
<pre>
cd backend
echo "MONGO_URL = mongodb://127.0.0.1/school" > .env
</pre>
note start mongodb must
<pre>
configure frontEnd .env:
cd frontend
echo "REACT_APP_BASE_URL = http://localhost:5000" > .env
</pre>
