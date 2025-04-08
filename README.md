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

### 1. App Build
![App](Screenshots/app.py.png.png)

### 2. Index.htm
![Index](Screenshots/index.htm.png.png)

### 3. Style.css
![Style](Screenshots/style.css.png.png)

### 4. Dockerfile 
![Dockerfile](Screenshots/Dockerfile.png.png)

### 5. Docker container
![Container](Screenshots/docker_container.png.jpg.png)

### 6. Docker images
![images](Screenshots/docker_images.png.jpg.png)

### 7. Running on chrome
![Chrome](Screenshots/run_on_chrome.png.png)

  
