# Bengali Machine Translation App

A web-based machine translation application that accepts questions in Bengali, translates them into English, generates a response using **Gemma 1.1-2B-IT**, and translates the final response back into Bengali.

## Features

* Bengali-to-English translation
* AI-generated responses using Gemma
* English-to-Bengali response translation
* Displays the complete translation pipeline
* Responsive and animated user interface
* Copy generated responses
* Web and application interface

## Translation Pipeline

```text
Bengali Input
     ↓
English Translation
     ↓
Gemma Response
     ↓
Bengali Translation
```

## Running the Project

Start the backend server:

```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```

Open the frontend HTML file in a browser and ensure that the backend API address is correctly configured.

## Contributors

* Ayush Kumar — 2024A7PS0560P
* Harsh Singh — 2024A7PS0573P
