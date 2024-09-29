# 📄 Document Buddy App

![App Screenshot](images/app_screenshot.png)

**Document Buddy App** is a powerful Streamlit-based application designed to simplify document management. Upload your PDF documents, create embeddings for efficient retrieval, and interact with your documents through an intelligent chatbot interface. 🚀

## 🛠️ Features

- **📂 Upload Documents**: Easily upload and preview your PDF documents within the app.
- **🧠 Create Embeddings**: Generate embeddings for your documents to enable efficient search and retrieval.
- **🤖 Chatbot Interface**: Interact with your documents using a smart chatbot that leverages the created embeddings.
- **📧 Contact**: Get in touch with the developer or contribute to the project on GitHub.
- **🌟 User-Friendly Interface**: Enjoy a sleek and intuitive UI with emojis and responsive design for enhanced user experience.

## 📁 Directory Structure

```
document_buddy_app/
│
├── new.py
├── vectors.py
├── chatbot.py
├── requirements.txt

```

## 🚀 Getting Started

Follow these instructions to set up and run the Document Buddy App on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/document-buddy-app.git
cd document-buddy-app
```

### 2. Create a Virtual Environment

It's recommended to use a virtual environment to manage dependencies.

#### On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

#### On macOS and Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

Ensure you have `pip` installed. Then, install the required packages using `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Run the App

Start the Streamlit app using the following command:

```bash
streamlit run new.py
```

*Note: If your main application file is named differently, replace `new.py` with your actual file name (e.g., `app.py`).*

This command will launch the app in your default web browser. If it doesn't open automatically, navigate to the URL provided in the terminal (usually `http://localhost:8501`).

## 🖼️ App Screenshot

![App Screenshot](images/app_screenshot.png)

*Replace `images/app_screenshot.png` with the actual path to your screenshot file.*

## 📝 Usage

1. **Home**: Get an overview of the app and its functionalities.
2. **Chatbot**:
   - **Column 1**: Upload a PDF document and preview it within the app.
   - **Column 2**: Create embeddings for the uploaded document. This process enables efficient search and retrieval.
   - **Column 3**: Interact with the chatbot by asking questions related to your uploaded document. The chatbot leverages the created embeddings to provide accurate and context-aware responses.
3. **Contact**: Find the developer's contact information and contribute to the project on GitHub.

## 🤝 Contributing

Contributions are welcome! Whether it's reporting a bug, suggesting a feature, or submitting a pull request, your input is highly appreciated. Follow these steps to contribute:

1. **Fork the Repository**: Click on the "Fork" button at the top-right corner of the repository page.
2. **Clone Your Fork**:

    ```bash
    git clone https://github.com/your-username/document-buddy-app.git
    cd document-buddy-app
    ```

3. **Create a New Branch**:

    ```bash
    git checkout -b feature/YourFeatureName
    ```

4. **Make Your Changes**: Implement your feature or fix.
5. **Commit Your Changes**:

    ```bash
    git commit -m "Add Your Feature Description"
    ```

6. **Push to Your Fork**:

    ```bash
    git push origin feature/YourFeatureName
    ```

7. **Create a Pull Request**: Navigate to the original repository and create a pull request from your fork.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📝 License

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[Include the full MIT License text here.]

```

*Replace the placeholder with the full text of the MIT License if it's not already included.*

---

## 📫 Contact

- **Email**: [developer@example.com](mailto:developer@example.com) ✉️
- **GitHub**: [Contribute on GitHub](https://github.com/your-username/document-buddy-app) 🛠️

Feel free to reach out for any queries, suggestions, or contributions. Your feedback is invaluable!

---

© 2024 Document Buddy App. All rights reserved. 🛡️

---

## ⚙️ Setting Up `requirements.txt`

Ensure your `requirements.txt` includes all necessary dependencies. Here's a sample based on the provided code:

```
streamlit
langchain_community
langchain_text_splitters
qdrant-client
langchain
langchain-ollama
```

**Install Dependencies**:

```bash
pip install -r requirements.txt
```

---

## 🔗 Useful Links

- **Streamlit Documentation**: [https://docs.streamlit.io/](https://docs.streamlit.io/)
- **LangChain Documentation**: [https://langchain.readthedocs.io/](https://langchain.readthedocs.io/)
- **Qdrant Documentation**: [https://qdrant.tech/documentation/](https://qdrant.tech/documentation/)
- **ChatOllama Documentation**: [https://github.com/langchain-ai/langchain-llms#ollama](https://github.com/langchain-ai/langchain-llms#ollama)

---

## 💡 Tips

- **Environment Variables**: For sensitive configurations like Qdrant URLs or API keys, consider using environment variables instead of hardcoding them.
- **Virtual Environment**: Always use a virtual environment to manage project-specific dependencies.
- **Testing**: Regularly test your app to ensure all components work seamlessly together.
- **Documentation**: Keep your documentation up-to-date with any changes or new features added to the app.

---

Feel free to customize this README further to better fit your project's specifics. Happy coding! 🚀✨
