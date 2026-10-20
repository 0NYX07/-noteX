# NoteX 📝⚡

An intelligent, AI-enhanced note-taking application designed to boost productivity and streamline workflows. Powered by React, Vite, Tailwind CSS, Appwrite, Google Gemini AI, and TensorFlow Universal Sentence Encoder for smart semantic search.

## ✨ Features

- 🤖 **AI Assistant**: Smart summarization, expansion, tone improvement, and insights powered by Google Gemini.
- 🔍 **Semantic Search**: Client-side vector similarity search with Universal Sentence Encoder.
- 🎙️ **Speech to Text & Text to Speech**: Voice-to-note capture and listen to your notes.
- ☁️ **Appwrite Backend**: Secure cloud authentication, database storage, and document synchronization.
- 🎨 **Modern UI**: Built with Tailwind CSS, Radix UI, Framer Motion, and dark/light mode support.
- 📤 **Export Capabilities**: Export notes easily to Markdown, PDF, or DOCX formats.

## 🚀 Getting Started

To get started with NoteX locally:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/0NYX07/-noteX.git
   cd -noteX
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file from `.env.example`:
   ```sh
   cp .env.example .env
   ```
   Provide your Appwrite and Google Gemini API keys:
   ```env
   VITE_APPWRITE_URL="https://example.com/v1"
   VITE_APPWRITE_PROJECT_ID="your_project_id"
   VITE_APPWRITE_DATABASE_ID="your_database_id"
   VITE_APPWRITE_COLLECTION_ID="your_collection_id"
   VITE_APPWRITE_USERS_COLLECTION_ID="your_users_collection_id"
   VITE_APPWRITE_BUCKET_ID="your_bucket_id"
   VITE_GOOGLE_AI_API_KEY="your_google_ai_api_key"
   ```

4. **Start the development server:**
   ```sh
   npm run dev
   ```

5. **Build for production:**
   ```sh
   npm run build
   ```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the issues page or submit a pull request.

## 👤 Author

- **Krishna Sahni** - [@0NYX07](https://github.com/0NYX07)

## 📄 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.
