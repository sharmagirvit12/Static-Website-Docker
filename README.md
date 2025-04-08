# Static-Website-Docker
Automated the deployment of a static website on a Docker container using a Jenkins CI/CD pipeline.
# Flask App Deployment using Jenkins, Docker & GitHub 🚀

This project demonstrates a **CI/CD pipeline** for deploying a Flask application using:
- **GitHub** for version control
- **Jenkins** for automation
- **Docker** for containerization

---

## 📂 Project Structure


---

## 🔧 Technologies Used

| Tool     | Purpose                      |
|----------|------------------------------|
| Flask    | Web application              |
| GitHub   | Source code management       |
| Jenkins  | CI/CD pipeline automation    |
| Docker   | Containerization             |
| Ubuntu   | Environment for deployment   |

---

## ⚙️ Workflow

1. **Push Code to GitHub**
   - The Flask app, Dockerfile, and requirements.txt are pushed to GitHub.
2. **Trigger Jenkins Pipeline**
   - Jenkins pulls the code from GitHub.
3. **Build Docker Image**
   - Jenkins builds the image using Dockerfile.
4. **Run the Container**
   - The Docker container is started and Flask app runs inside it.

## 📸 Project Execution Screenshots

## 📸 Project Screenshots and Workflow

### 1. App Build (app.py)
![App](Screenshots/app.py.png)

### 2. index.html
![Index](Screenshots/index.htm.png)

### 3. style.css
![Style](Screenshots/style.css.png)

### 4. Dockerfile
![Dockerfile](Screenshots/Dockerfile.jpg)

### 5. Docker Container Running
![Container](Screenshots/docker_container.png.jpg)

### 6. Docker Images
![Images](Screenshots/Docker_images.jpg)

### 7. Application Running in Chrome
![Chrome](Screenshots/run_on_chrome.png)
  
