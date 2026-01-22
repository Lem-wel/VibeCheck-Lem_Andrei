# VibeCheck-Lem_Andrei

Description:
This is a simple front-end web page that lets users click buttons to fetch and display data (like fortunes, jokes, moods, or secrets) from a Node.js API. The HTML handles the layout, CSS adds a clean dark UI, and app.js manages button events and API requests, showing responses in the output area.

How to run:

Make sure you have a Node.js backend running (your API server).

Place this HTML file and app.js in the same folder.

Start your Node.js server (node server.js or npm start).

Open the HTML file in a browser (or serve it via a local server).

Click the buttons to see the API responses appear in the output box.

Endpoints

GET /api/fortune -> returns { fortune: "..." } - tell a random fortune message

GET /api/joke -> returns { joke: "..." } - tell a one liner joke

GET /api/vibe?mood=happy|tired|stressed -> returns { mood, emoji, message } - gives mood randomly

POST /api/smash -> increases a counter and returns { smashes: number } - increases smash counter by 1

GET /api/smashes -> returns { smashes: number } - show number of smashes

GET /api/secret?code=411L - secret
