
**Flask App Dockerized | DevOps Portfolio Project**

This is a simple Flask application packaged into a Docker image.
It demonstrates containerisation, image building, and running a Python web server inside Docker.

**🚀 Features**

Python Flask web app

Dockerfile following best practices

Runs on port 5000

Lightweight image

**🛠 Tech Used**

Python 3

Flask

**Docker**
📦 Build Docker Image
docker build -t myflaskapp:1.0 .

▶️ **Run the Container**
docker run -p 5000:5000 myflaskapp:1.0


Open in browser:

_http://localhost:5000_

**🗂 3. Update .gitignore**

Make sure this is inside .gitignore:

venv/
__pycache__/
*.pyc
.env

**🧩 4. Commit Everything**
git add .
git commit -m "Add Flask app with Dockerfile and README"
git push
