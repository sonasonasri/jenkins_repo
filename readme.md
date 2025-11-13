Jenkins Cloud Project 🚀

This project demonstrates the basic setup and working of Jenkins for automation and deployment in a cloud environment.
It includes a simple HTML web page integrated with Jenkins to show how Continuous Integration (CI) and Continuous Deployment (CD) pipelines can be managed efficiently.

🔧 Tools & Technologies Used

Jenkins – Automation server for CI/CD pipeline setup

GitHub – Version control and project hosting

HTML/CSS – Front-end web interface

Cloud Integration – Demonstrates automated build and deploy process

💡 Objective

To understand and implement a basic Continuous Integration and Continuous Deployment (CI/CD) workflow using Jenkins and GitHub.
This helps automate code building, testing, and deployment to the cloud.

📁 Project Structure
```
project_repo/
│
├── index.html          # Simple web page file
├── Jenkinsfile         # Jenkins pipeline script for CI/CD
├── README.md           # Project documentation
└── assets/             # Folder for images, CSS, etc.
```


⚙️ Jenkins Pipeline Workflow

Developer pushes code to the GitHub repository.

Jenkins automatically triggers the build using a webhook connection.

Jenkinsfile defines the CI/CD stages (build, test, and deploy).

Build & Test: The code is checked for syntax or logic errors.

Deploy Stage: After successful build, Jenkins deploys the HTML site to the configured cloud environment.

Notifications: Jenkins sends success/failure alerts after each run.

🧩 Key Features

Automated build and deployment with Jenkins

Git-based integration for version control

Scalable and reusable CI/CD workflow

Easy to adapt for other cloud-based web applications

📊 Output Example

After successful deployment, the index.html web page becomes accessible from the hosted cloud server, showing the deployment success message.

👩‍💻 Author

Sona Sri S R
B.E Artificial Intelligence and Data Science
📧 sonaammu07@gmail.com

🌐 GitHub Profile: github.com/sonasonasri
