AI Chatbot Project - Complete Details
📋 Project Ki Complete Details
🎯 Project Kya Hai?
Ek simple AI chatbot website jisme:

User signup/login kar sakta hai

User AI se baat kar sakta hai (OpenAI use karega)

Chat history save nahi hogi

Simple aur clean design

🛠️ Technology Stack
Backend (Server Side):

Node.js - Server ke liye

Express.js - Web framework

MongoDB - Database

JWT - Security tokens

OpenAI API - AI ke liye

Frontend (User Side):

HTML - Page structure

CSS - Styling

JavaScript - Functionality

🔐 Security Features
Passwords encrypted honge

JWT tokens for session management

API keys secure rahenge

📱 Design Requirements
Mobile friendly

Simple aur clean look

Easy to use

⏰ Timeline
Total Time: 3-4 weeks

Week 1: Backend setup

Week 2: Frontend development

Week 3: Integration & testing

Week 4: Final touches

🎯 Success Criteria
Project successful tab mana jayega jab:

✅ User signup/login kar paye

✅ AI se properly baat kar paye

✅ Mobile par work kare

✅ No major bugs

✅ Secure hai

💰 Cost
Sab kuch FREE hai

MongoDB Atlas - FREE tier


🎓 Learning Outcomes
Har developer ko milega:

Team collaboration experience

Specific technology expertise

Project management understanding

Problem solving skills






Abdul-Saboor:

Iska kaam server.js me Express server run karna hai.
Yeh bas Express import karega, JSON middleware lagayega, aur server ko port par start karega.
Baad me yeh authRoutes.js aur chatRoutes.js ko connect karega.
Ye backend ka foundation hai (easy task).



Hammad Ali:
 Is developer ne db.js me MongoDB connection likhna hai.
User.js me User model banana hai (name, email, password).
Iska code authController.js me use hoga.
Database layer ka saara setup ye karega.






Tamoor:
eh authController.js me signup + login ka logic likhega.
Yeh User.js (M.imran ka model) use karega.
Password hashing & JWT token ye hi banayega.
Routes (authRoutes.js) iske functions ko call karegi.





Naseer nawaz:
authRoutes.js me API endpoints banayega:
POST /signup
POST /login
Yeh routes authController.js (Tamoor) ke functions ko use karegi.
Baad me ye routes server.js me attach hongi (Abdul-saboor karega).









M.imran:
eh chatController.js me AI logic likhega.
User question lega → OpenAI API ko call karega → answer return karega.
Iska code chatRoutes.js (Developer 6) me use hoga.
Backend ka AI brain ye developer banayega.





M.Arslan
chatRoutes.js me /ask endpoint banayega.
Is route me chatController.js ke functions use honge (Developer 5).
authMiddleware.js me JWT verify karega.
Last step me yeh saare routes server.js me attach karega (Developer 1 ke server code ke through).





M.Abdul-Rasheed:
Layout Banana ha or acha design select karna ha
Or sab files ka same design ho or bootstrap ko use karna ha
Is ki ilawa Testing all Project and workflow



Ali Raza:
Ya front end java script bnay ga or os ka sath html ko connect kra ga
is ka ilawa All project ka code ko manage kra ga










Developer	        File	                            Connects With

Abdul-saboor	    server.js	                        authRoutes.js & chatRoutes.js
Hammad Ali	        db.js, User.js	                    authController.js
Tamoor	            authController.js	                User.js & authRoutes.js
Naseer	            authRoutes.js	                    authController.js & server.js
M.imran	            chatController.js	                chatRoutes.js
M.Arslan	        chatRoutes.js, authMiddleware.js	chatController.js & server.js






prompt In Roman Urdu  {




Main AI Chatbot Project par kaam kar raha hoon jiski structure yeh hai:

ai-chatbot-project/
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── chat.html
│   ├── css/
│   │    └── style.css
│   └── js/
│        ├── login.js
│        ├── signup.js
│        └── chat.js
├── backend/
│   ├── config/
│   │    └── db.js
│   ├── controllers/
│   │    ├── authController.js
│   │    └── chatController.js
│   ├── models/
│   │    └── User.js
│   ├── routes/
│   │    ├── authRoutes.js
│   │    └── chatRoutes.js
│   ├── middleware/
│   │    └── authMiddleware.js
│   └── server.js

Mujhe [SPECIFIC SECTION/FILE NAME] mein help chahiye.

Kripya provide karein:
1. Us specific section ka complete code
2. Step-by-step implementation guide
3. Testing ke instructions
4. Common issues aur unke solutions
5. Dusre sections ke saath integration points

Current Technology Stack:
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- AI: OpenAI API

Note: Hum chat history store nahi kar rahe, sirf real-time AI responses.



}




english prompt{





    I am working on an AI Chatbot Project with the following structure:

ai-chatbot-project/
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── chat.html
│   ├── css/
│   │    └── style.css
│   └── js/
│        ├── login.js
│        ├── signup.js
│        └── chat.js
├── backend/
│   ├── config/
│   │    └── db.js
│   ├── controllers/
│   │    ├── authController.js
│   │    └── chatController.js
│   ├── models/
│   │    └── User.js
│   ├── routes/
│   │    ├── authRoutes.js
│   │    └── chatRoutes.js
│   ├── middleware/
│   │    └── authMiddleware.js
│   └── server.js

I need help with [SPECIFIC SECTION/FILE YOU'RE WORKING ON]. 

Please provide:
1. Complete code for that specific section
2. Step-by-step implementation guide
3. Testing instructions
4. Common issues and solutions
5. Integration points with other sections

Current Technology Stack:
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- AI: OpenAI API

Note: We are NOT storing chat history, only real-time AI responses.





}