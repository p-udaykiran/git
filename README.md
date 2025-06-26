# node-ci-cd-app


# Node.js App with GitLab CI/CD & AWS EC2 Deployment

This document provides a full technical overview and deployment strategy for a Node.js application using GitLab CI/CD and AWS EC2. The project demonstrates automation from code commit to deployment with process management using PM2.

---

## 📁 Project Structure

```
node-ci-cd-app/
├── app.js               # Main Node.js server file
├── package.json         # Node.js dependencies and scripts
├── .gitlab-ci.yml       # GitLab CI/CD configuration
└── README.md            # Project documentation
```

---

## 🔧 Technologies Used

* **Node.js**: JavaScript runtime 
* **Express.js**: Web framework for Node
* **GitLab CI/CD**: Continuous Integration and Deployment
* **AWS EC2**: Cloud hosting environment
* **PM2**: Node.js process manager

---

## 🌐 Application Output

After successful deployment, your app will be accessible at:

```
http://<your-ec2-ip>:3000
```

Response:

```
Hello from GitLab CI/CD!
```

---

## 🖼️ Screenshots

### ✅ Deployed App in Browser

<p>The screenshot below shows the successful deployment of the Node.js application running on AWS EC2. The browser displays:</p>
<blockquote><strong>Hello from GitLab CI/CD!</strong></blockquote>
<img src="Screenshot%202025-06-19%20002553.png" alt="Deployed App Screenshot" style="width:80%; border: 1px solid #ccc; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin-bottom: 30px;" />

### ✅ GitLab CI/CD Pipeline

<p>This screenshot shows the GitLab pipeline stages (Build, Test, Deploy) with all jobs completed successfully.</p>
<img src="Screenshot%202025-06-19%20010229.png" alt="GitLab CI/CD Pipeline Screenshot" style="width:80%; border: 1px solid #ccc; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);" />


### Stages Defined:

1. **Build**
2. **Test**
3. **Deploy**


##
