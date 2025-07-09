# Django Document Upload Portal

This is a basic Django project that allows users to upload documents through a web interface. Each uploaded document is stored with a title, description, file, and timestamp. Uploaded files are saved in the `media/documents/` directory.

---

## Features

- Upload documents with title and description
- Stores files using Django's `FileField`
- Admin interface for managing uploaded documents
- Media file support for development

---

## Tech Stack

- Python
- Django
- SQLite (default DB)

---
### Screenshots

![image](https://github.com/user-attachments/assets/3bd771b4-8a02-4987-8d7e-97a5f8c2faac)

![image](https://github.com/user-attachments/assets/295c3663-9e61-499a-98c1-6e7d06ac37f7)



---

## ✅ Conclusion

This Django Document Upload Portal provides a simple yet effective solution for managing file uploads in a web application. With support for metadata (title, description, timestamp) and secure file storage under `media/documents/`, it serves as a solid foundation for more advanced document management systems.

Whether you're building a personal tool, an internal portal, or a component of a larger application, this project demonstrates key Django concepts including models, file handling, admin customization, and development-time media serving.

You can further extend this project by adding:
- User authentication and permissions
- Search and filter functionality
- File type and size validation
- REST API integration using Django REST Framework
- Frontend enhancements with templates or JavaScript frameworks

This project is a great starting point for learning or building real-world Django applications.
