# 📚 IIPS Digital Learning Resource Repository

A web-based platform developed to make academic learning resources easily accessible to students and faculty members of IIPS.

The platform provides a centralized place where faculty members can upload educational materials, students can explore and download approved resources, and administrators can manage users and uploaded content.

## ✨ Features

### 👨‍🎓 Student
- Register and log in securely.
- Browse approved learning resources.
- Search resources by title, description, or uploader.
- Filter resources by categories.
- Download educational materials.
- Rate resources from 1 to 5 stars.
- Share feedback through comments.
- View recently uploaded resources on the dashboard.
- Manage profile information.

### 👩‍🏫 Faculty
- Secure faculty login.
- Upload educational resources.
- Add resource titles and descriptions.
- Organize resources into categories.
- View uploaded resources.
- Track resource approval status through the dashboard.

### 🛡️ Administrator
- Dedicated admin dashboard.
- View total registered users.
- Monitor uploaded resources.
- Track pending and approved resources.
- Approve or reject uploaded resources.
- Delete resources when required.
- Manage registered users.
- Add new resource categories.

## 📂 Supported File Formats

The platform supports uploading:

- PDF
- DOC / DOCX
- PPT / PPTX
- TXT
- JPG / JPEG
- PNG
- MP4

Maximum upload size: 50 MB.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web framework |
| SQLite | Database management |
| HTML | Web page structure |
| CSS | Styling |
| Werkzeug | Password hashing and file handling |
| Jinja2 | Dynamic HTML templates |

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Kriti2594/IIPS-digital-learning-repository.git
```

### 2. Navigate to the Project Folder

```bash
cd IIPS-digital-learning-repository
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows:**
```bash
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

### 6. Open in Browser

Visit:

```text
http://127.0.0.1:5000
```

The SQLite database and upload directory are initialized automatically when the application starts.

## 🔑 Demo Login Credentials

The application initializes the following demo accounts:

| Role | Email | Password |
|---|---|---|
| Student | student@iips.com | student123 |
| Faculty | faculty@iips.com | faculty123 |
| Admin | admin@iips.com | admin123 |

**Note:** These are demonstration credentials. Change default credentials and the application secret key before deploying publicly.

## 🗄️ Database

The project uses SQLite for storing application data.

The database contains four main tables:

- **Users:** Stores user details, login credentials, and roles.
- **Categories:** Stores learning resource categories.
- **Resources:** Stores resource information, file details, uploader information, and approval status.
- **Ratings:** Stores student ratings and feedback.

## 🔄 How the System Works

1. Students and faculty members register and log in.
2. Faculty members upload educational resources.
3. Uploaded resources are submitted for administrator approval.
4. Administrators review and approve or reject resources.
5. Approved resources become available to students.
6. Students can search, filter, download, and rate resources.
7. Administrators manage users, resources, and categories.

Resources uploaded by administrators are approved automatically.

## 🔮 Future Enhancements

- Cloud-based file storage.
- Email notifications for resource approvals.
- Advanced search and filtering.
- Resource bookmarking.
- Personalized learning recommendations.
- Improved mobile responsiveness.
- Deployment on a cloud hosting platform.

## 👩‍💻 Project Information

**Project Name:** IIPS Digital Learning Resource Repository

**Repository:** [GitHub - IIPS Digital Learning Repository](https://github.com/Kriti2594/IIPS-digital-learning-repository)

**Developed Using:** Python, Flask, SQLite, HTML and CSS.

Author
Kriti Choudhary 
