🐦 X.Arko

A minimal microblogging / tweet-feed web app built with Vanilla JavaScript.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📌 Overview

X by Arko is a lightweight Twitter-style microblog clone built using HTML, CSS, and JavaScript (ES6+).
It features tweet posting, like toggles, reply threads, dynamic rendering, and clean UI updates — all powered with modular JS and DOM manipulation.

This project was built to strengthen concepts like:

Dynamic rendering using template literals

Event delegation

Arrays of objects

Toggling UI states (classList.toggle)

Data-driven UI updates

Modular code structure


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🚀 Features

📝 Create new posts

❤️ Like & Unlike tweets

💬 Add and view replies

🔽 Expand/Collapse reply threads

🔄 Auto-rendering feed

📱 Responsive & clean UI

🧩 Modular JS architecture

⚡ Live reload support with VS Code Live Server


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🧠 Tech Stack

JavaScript (ES6 Modules)

HTML5

CSS3 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📁 Project Structure

/x-arko
│
├── index.html
├── index.js
├── data.js
├── styles.css
└── images/
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ How to Run X.Arko Locally

1️⃣ Clone the repository
git clone https://github.com/Arko101/X.Arko.git

then:

cd x-arko

2️⃣ Open the project in VS Code

code .

3️⃣ Install the “Live Server” extension

VS Code → Extensions

Search Live Server

Install it

4️⃣ Start the app

Right-click on index.html → "Open with Live Server"
or click the "Go Live" button in VS Code’s status bar.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🧩 How X.Arko Works Internally
✔ 1. Data Layer (data.js)

All posts, likes, and replies are represented as objects inside arrays.

✔ 2. Rendering Engine (index.js)

The feed is built dynamically using template literals:

document.getElementById('feed').innerHTML = getFeedHtml();

✔ 3. Event Delegation

A single global click listener handles:

likes

replies

posting

toggling reply threads

✔ 4. Toggle Mechanics

Reply threads are shown/hidden using:

classList.toggle('hidden');


.hidden class:

.hidden {
  display: none;
}

✔ 5. Dynamic IDs

Reply sections use IDs like:

replies-42


Built using:

`replies-${replyId}`


Simple, scalable, and modular.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Concepts Demonstrated

ES6 Modules (import { data } from './data.js')

Template literal HTML generation

Event delegation for cleaner JS

Using .closest() and .dataset for UI actions

Array operations: .map(), .filter(), .forEach(), .push()

Boolean toggling:

isLiked = !isLiked;


DOM class manipulation via classList

State-driven UI updates

This is exactly how modern Twitter-style feeds work under the hood.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🧑‍💻 Author

Arkopratim Chakraborty 📍 Software Test Engineer | Siemens Technology & Services Pvt. Ltd. 
🔗 LinkedIN - https://www.linkedin.com/in/arkopratim-chakraborty/  | 💻 GitHub - https://github.com/Arko101
