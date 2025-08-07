# REST API Client (Java)

This is a super lightweight project I made to mess around with calling REST APIs using nothing but **core Java** — no fancy libraries, just `HttpURLConnection` and some DIY JSON parsing.

### 🧠 What it does:
- Sends GET requests to a public API (I used a weather API as an example)
- Parses the JSON response
- Prints out structured data using simple POJOs

### 🛠️ How it’s structured:
- `ApiService`: Makes the actual API call
- `JsonParserUtil`: Breaks down the JSON manually
- `WeatherData`: Just a plain old Java object to hold the data
- `Main`: Kicks everything off

### 🤓 Why I built this:
Honestly, I just wanted to see if I could talk to an API without using things like OkHttp or Spring RestTemplate. Sometimes it's fun (and painful) to do it the hard way.

### 🚀 Running it:
Open it in your IDE, run `Main.java`, and you’ll see the response neatly printed in your terminal.

---

If you're learning how APIs work behind the scenes, this could be a great mini-project to get your hands dirty.

