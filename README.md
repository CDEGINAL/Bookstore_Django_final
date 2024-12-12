# Bookstore

# 📚 Django Bookstore Project



An elegant and feature-rich web application for managing an online bookstore. Built with Django, it provides a seamless experience for users to browse, shop, and manage books.

---

## **✨ Features**

### For Users:

- 🔑 **Authentication**: User login, signup, and logout.
- 🔍 **Browse Books**: Explore books by genre and price.
- 🛒 **Shopping Cart**: Add, remove, and update items.
- 🛑 **Checkout**: Place orders with ease.

### For Admins:

- ✏️ **Add Books**: Easily upload new books with cover images.
- 🛑 **Delete Books**: Manage the catalog by removing items.

---

## **🔧 Tools and Technologies**

### **Languages**:

- ✨ Python (Backend)
- ✨ HTML (Templates)
- ✨ CSS (Styling)
- ✨ JavaScript (Frontend Interactivity)

### **Frameworks & Libraries**:

- ✨ Django (Backend Framework)
- ✨ Bootstrap (CSS Framework for Styling)
- ✨ Pillow (Image Handling)

### **Database**:

- ✨ SQLite (Default database in Django)

### **Version Control**:

- ✨ Git

---

## **🜄 Screenshots**


### **Home Page:**



### **Book List Page:**



### **Shopping Cart:**



---

## **🔗 Getting Started**

### **Prerequisites**

Ensure you have Python 3.8+ installed on your system.

### **Installation**

1. ⬇️ Clone the repository:

   ```bash
   git clone https://github.com/<username>/<repository>.git
   cd <repository>
   ```

2. 🔄 Create a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. ⚙️ Apply database migrations:

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. 🚀 Start the development server:

   ```bash
   python manage.py runserver
   ```

5. 🌐 Open your browser and visit:

   ```
   http://127.0.0.1:8000/
   ```

---

## **🔍 Project Structure**

```
├── bookstore_app/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
├── manage.py
└── README.md
```

- **`models.py`**: Contains database models (e.g., `Book`, `Cart`, `Order`).
- **`views.py`**: Handles business logic and links models to templates.
- **`urls.py`**: Defines routing for different pages.
- **`forms.py`**: Custom forms for user input and validation.
- **`templates/`**: HTML templates for the frontend.

---

## **🔒 Core Features Breakdown**

### **Book Management**

- 🔐 Add books with details like title, author, genre, price, and cover image.
- 🛑 Delete books directly from the admin interface.

### **Shopping Cart**

- 🛒 Add books to the cart.
- ➕ Update quantities or ❌ remove items.
- 🛒 View total price and 🛑 checkout.

### **User Authentication**

- 🔐 Signup for new accounts.
- 🔐 Login and logout functionality.

---

## **⚡ Requirements**

This project requires the following dependencies:

```plaintext
Django==4.2.5
```

Install them using:

```bash
pip install -r requirements
```

---

## **🎉 How to Contribute**

1. 🔄 Fork the repository.
2. ➕ Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. ✏️ Make your changes and commit them:
   ```bash
   git commit -m "Add a feature"
   ```
4. ⬆️ Push your changes:
   ```bash
   git push origin feature-name
   ```
5. 🎮 Submit a pull request.

---

## **📢 Contact**
- **GitHub**: [CDEGINAL](https://github.com/CDEGINAL)

