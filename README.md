#🔍 Wikipedia Search App
A sleek, minimalist Wikipedia search interface built using HTML, CSS, and Vanilla JavaScript. Powered by the ccbp.in Wikipedia search API, this app delivers real-time search results with a responsive UI and loading indicator.

🚀 Features
🔎 Search Wikipedia articles via keyword input

⏳ Real-time loading spinner during API fetch

📄 Display title, URL, and description of each result

💡 Opens links in a new tab

🎯 Fully responsive with Bootstrap 4

📁 Project Structure
bash
Copy
Edit
/wiki-search-app/
│
├── index.html       # UI structure and logic (inlined CSS + JS)
For scalability, consider modularizing CSS and JS into separate files.

🛠️ Tech Stack
HTML5

CSS3 (with Bootstrap 4.5)

JavaScript (ES6+)

Wikipedia Search API via ccbp.in

▶️ How to Use
Open the HTML file in any modern browser.

Type a search term in the input field.

Press Enter to fetch and view results.

⚙️ API Used
Endpoint: https://apis.ccbp.in/wiki-search?search=<your_query>

Response Format:

json
Copy
Edit
{
  "search_results": [
    {
      "title": "Example Title",
      "link": "https://en.wikipedia.org/wiki/Example",
      "description": "A short summary of the article."
    }
  ]
}
🧪 Future Enhancements
 Infinite scroll

 Debounced search

 Mobile-first refinements

 Autocomplete suggestions
