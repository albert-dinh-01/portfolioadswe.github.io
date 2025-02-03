# Disperse - Decentralized Social Networking

## **Overview**

Disperse is a **decentralized social networking platform** inspired by [Diaspora\*](https://diasporafoundation.org/) and [ActivityPub](https://www.w3.org/TR/activitypub/).  
Originally developed as a **University of Alberta group project**, the application enables users to share posts, interact with followers, and manage content in a **distributed** environment.

After the project ended, I added features to the project. And it has been significantly extended with **cloud deployment** and improved **scalability**.

## **Acknowledgements**  

This project was originally developed as **Nodenet** for the **CMPUT 404 group project** at the University of Alberta in the Fall 2023 semester with the following contributors:  

- **Albert Dinh**  
- **Dhruvraj Singh**  
- **Mobashhir Khan**  
- **Daniel Asimiakwini**  
- **Jaspreet Singh Dhami**  

While I have added features to the project post-graduation with **cloud deployment, Dockerization, and HTTPS support**, the foundational design was a collaborative effort.  

_Disperse remains inspired by the principles of decentralized social networking platforms like [diaspora*](https://diasporafoundation.org/)._  

## **Features**

### **Core Features**

✅ **Decentralized Architecture** – Users can self-host instances.  
✅ **RESTful API** – For inter-server communication.  
✅ **Public & Private Posts** – Full control over visibility.  
✅ **Friend Requests & Following System** – Bi-directional friendships.  
✅ **Comments & Likes** – Engage with posts from any server.  
✅ **Cross-Server Authentication** – Secure node-to-node trust.  
✅ **Media Hosting** – Integrated AWS S3 for file storage.

### **Admin Features**

🔹 **Manage Authors** – Create, modify, or delete accounts.  
🔹 **Moderation Controls** – API for restricting access.  
🔹 **Inbox Model** – Handle incoming social interactions securely.

### **UI Features**

🖥️ **Feed System** – View posts from friends & public authors.  
✍️ **Post Management** – Create, edit, or delete posts.  
📢 **Notification System** – Alerts for likes, comments, and requests.  
⚙️ **User Profiles** – Update display name, profile image, and settings.

## **Technology Stack**

- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS
- **Database**: PostgreSQL (AWS RDS)
- **Cloud & Deployment**:
  - AWS **EC2** (Application Hosting)
  - AWS **RDS for PostgreSQL** (Database)
  - AWS **S3** (Media Storage)
  - Docker (Containerization)
  - Nginx & Certbot (Reverse Proxy & HTTPS)
- **API Security**: HTTP Basic Auth, Token Authentication

## **Deployment Details**

### **Live Demo**

🔗 **[Visit Disperse](https://www.mydisperse.xyz/)**

### **Infrastructure**

🌐 **Web Server** – Packaged with Docker and hosted on AWS **EC2**.
💾 **Database** – Hosted on AWS **RDS for PostgreSQL**.  
📦 **Containers** – Dockerized app deployed to AWS **EC2**.  
🔐 **HTTPS Enabled** – SSL certificate issued via **Let's Encrypt**.  
🛠️ **Reverse Proxy** – Nginx manages traffic between users & the app.

### **Setup Instructions for Local Development**

1️⃣ **Clone the Repository** (Private, Source Code Not Available)

```bash
git clone git@github.com:albert-dinh-01/disperse.git
cd disperse
```
