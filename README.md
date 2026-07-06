# 🧾 AI Blog Generator

An AI-powered web application built with **Python** and **Streamlit** that generates high-quality blog posts based on user input. Users can customize the blog by selecting the topic, tone, length, and target audience.

## ✨ Features

* Generate blogs on any topic
* Choose different writing tones

  * Professional
  * Friendly
  * Technical
  * Funny
  * Motivational
* Select blog length

  * Short
  * Medium
  * Long
* Specify the target audience
* Clean and interactive Streamlit interface
* Fast AI-generated content

## 🛠️ Tech Stack

* Python
* Streamlit
* OpenAI API (or compatible LLM)
* Virtual Environment (venv)

## 📂 Project Structure

```text
AI-Blog-Generator/
│── app.py
│── blog_generator.py
│── utils.py
│── requirements.txt
│── README.md
│── .gitignore
│── .env
└── .streamlit/
```

## 🚀 Installation

1. Clone the repository.

```bash
git clone https://github.com/your-username/AI-Blog-Generator.git
```

2. Navigate to the project folder.

```bash
cd AI-Blog-Generator
```

3. Create a virtual environment.

```bash
python -m venv venv
```

4. Activate the virtual environment.

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

5. Install dependencies.

```bash
pip install -r requirements.txt
```

6. Create a `.env` file and add your API key.

```env
OPENAI_API_KEY=your_api_key_here
```

7. Run the application.

```bash
streamlit run app.py
```

## 📖 How to Use

1. Enter a blog topic.
2. Select the desired tone.
3. Choose the blog length.
4. Select the target audience.
5. Click the **Generate** button.
6. View and copy the generated blog.

## 📌 Future Improvements

* Blog title suggestions
* SEO optimization
* Export to PDF or Word
* Blog history
* Multiple language support
* AI image generation
* One-click copy and download

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository, create a new branch, and submit a pull request.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Developed as a Python and Streamlit AI project for generating customizable blog content.
