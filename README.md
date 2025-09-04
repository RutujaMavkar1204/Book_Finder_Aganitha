# 📖 Book Finder

Book Finder is a React-based web application that allows users to search for books quickly and view details such as title, author(s), first publish year, and cover images. It uses the **Open Library Search API** to provide a smooth and responsive experience for students, readers, and researchers.

---

## 🚀 Features
- 🔍 Search books by title  
- 🖼️ Display book details (title, author, publish year, cover)  
- 🎛️ Filter by minimum and maximum publication year  
- ⚡ Responsive and fast UI with React hooks  
- 🚫 Error handling for empty queries and failed requests  

---

## 🛠️ Tech Stack
- **Frontend:** React  
- **Styling:** Tailwind CSS (or your chosen CSS framework)  
- **API:** [Open Library Search API](https://openlibrary.org/dev/docs/api/search)  

---

## 📂 Project Setup


🔗 API Example
Search books by title:

http
Copy code
GET https://openlibrary.org/search.json?title=harry+potter
📸 Screenshots
(Add your screenshots here for better presentation)

📌 Future Improvements
Add search by author, subject, or ISBN

Save favorite books locally

Show trending/popular books

Implement pagination

👤 Author
Rutuja
### 1. Clone the repository
```bash
git clone https://github.com/RutujaMavkar1204/Book_Finder_Aganitha.git
cd book-finder
2. Install dependencies
bash
Copy code
npm install
3. Run the app
bash
Copy code
npm run dev
The app will be available at:
👉 http://localhost:5173/ (Vite default) or http://localhost:3000/ (CRA)
