# LUCID

A web application that converts YouTube video transcripts into structured AI-generated notes using Google Gemini API.

---

# Features

- Fetch YouTube transcripts automatically
- Generate AI-powered notes
- Multiple note generation modes
- Responsive user interface
- Copy notes functionality
- Google Gemini AI integration
- Transcript truncation handling
- Error handling for APIs

---

# Technologies Used

## Frontend

- HTML5
- CSS3
- JavaScript (Vanilla JS)

## APIs

- Google Gemini API
- Supadata API

---

# Running the Project

Open:

```bash
index.html
```

inside your browser.

---

# How It Works

1. User pastes YouTube video URL
2. Transcript is fetched using Supadata API
3. Transcript is processed and truncated if needed
4. Prompt is generated
5. Prompt is sent to Google Gemini API
6. Gemini generates structured notes
7. Notes are displayed on UI

---

# Gemini API Integration

## Correct Model Format

Use valid Gemini model IDs:

```js
GOOGLE_MODEL: "gemini-2.5-flash"
```

Do NOT use:

```js
"Gemini 3 Flash"
```

because Gemini API requires official model IDs.

---

# Error Handling

The project includes:

- API error handling
- Empty response handling
- Invalid JSON handling
- Transcript truncation
- Missing transcript handling

---

# Future Features

Possible future upgrades:

- AI chat with transcript
- Timestamp-based notes
- Multiple language support
- Save note history
- Download notes feature

---

# Author

  UTTARA CHATURVEDI
