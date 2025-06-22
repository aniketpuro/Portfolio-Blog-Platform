## 🌐 Portfolio & Blog Platform

A full-stack personal **portfolio and blog platform** built using Django and Bootstrap. Includes a custom admin dashboard for managing content, SEO optimization, and live deployment using Docker on AWS EC2.

---

### 🚀 Features

- ✨ **Personal Portfolio Website**  
  Showcases projects, blogs, and achievements in a clean, responsive layout.

- 📝 **Blog System with Admin Dashboard**  
  Custom CMS to publish and manage blog posts easily.

- 🗄️ **PostgreSQL Database Integration**  
  Structured and scalable database management with PostgreSQL.

- 🐳 **Dockerized Deployment**  
  Entire app containerized and deployed on AWS EC2 instance.

- 📈 **SEO Optimization + Google Analytics**  
  Implements meta tags, sitemap, and integrates GA for traffic insights.

- 📬 **Contact Form with Email Notifications**  
  Secure and validated contact form that triggers email alerts on submission.

---

### ⚙️ Tech Stack

- **Frontend**: HTML5, CSS3, Bootstrap  
- **Backend**: Python, Django  
- **Database**: PostgreSQL  
- **Deployment**: Docker, AWS EC2  
- **Tools**: Git, Gunicorn, Nginx, Google Analytics

---

### 🔧 How to Run Locally

```bash
git clone https://github.com/your-username/portfolio-blog-platform.git
cd portfolio-blog-platform

# Create virtual environment
python -m venv venv
source venv/bin/activate  # on Linux/macOS
venv\Scripts\activate     # on Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver
```

---

### 📦 Docker Deployment

```bash
docker build -t my-portfolio-blog .
docker run -d -p 8000:8000 my-portfolio-blog
```

---

### 📮 Contact

Feel free to connect with me:

- [Hashnode Blogs](https://aniketpurohit.hashnode.dev)
- [LinkedIn](https://linkedin.com/in/aniketpurohit)
- [Email](mailto:you@example.com)
