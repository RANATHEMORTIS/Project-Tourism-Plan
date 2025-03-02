# **Tours Project**

## **🛠 Project Overview**
The **Tours Project** is a React-based web application that displays a list of tours with details such as name, price, description, and images. Users can remove tours by clicking the **"Not Interested"** button, and refresh the list when no tours are left.

## **🚀 Features**
- Display a list of available tours with images and details.
- Users can read more or collapse the tour description.
- Remove a tour from the list using the **"Not Interested"** button.
- Refresh the tour list when all tours are removed.
- Fully responsive design with Tailwind CSS.

## **🌍 Live Demo**
🔗 **Live Site:** [Epic Voyages](https://epicvoyages.netlify.app/)

## **📌 Technologies Used**
- **React.js** (Functional Components & Hooks)
- **useState Hook** (For state management)
- **CSS/Tailwind CSS** (For styling)

## **🛠 Installation & Setup**

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/tours-project.git
cd tours-project
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Start the Development Server**
```sh
npm run dev
```

The application will now be running at **http://localhost:5173/**.

## **📂 Project Structure**
```
📦 tours-project
├── 📂 src
│   ├── 📂 components
│   │   ├── 📄 Tours.jsx
│   │   ├── 📄 Tour.jsx
│   │   ├── 📄 Card.jsx
│   ├── 📄 App.jsx
│   ├── 📄 data.js
│   ├── 📄 index.js
├── 📄 package.json
├── 📄 README.md
```

## **📌 How It Works**
1. The app fetches tour data from **`data.js`**.
2. Tours are displayed using the **Tours** component, which maps over the array and renders individual **Tour** components.
3. Clicking **"Not Interested"** removes a tour using the `removeTour` function.
4. If no tours are left, the **"Refresh"** button restores the original list.

## **🤝 Contributing**
Feel free to submit **issues** and **pull requests** to improve this project! 😊

## **📜 License**
This project is licensed under the **MIT License**.

---
Happy Coding! 🚀

