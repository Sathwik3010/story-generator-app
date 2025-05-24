# story-generator-app
An app that generates stories with visuals.

# 🗣️ Story Generator App with Streamlit and LangChain

This project features an interactive web application for generating stories with rich visual content, powered by large language models (LLMs) and Python. Built with Streamlit and integrated with LangChain, the app enables users to create engaging stories and visualize them seamlessly, using models provided by Together AI.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Sathwik3010/story-generator-app.git
   ```

2. **Install the required dependencies:**

   ```bash
   cd story-generator-app
   pip install -r requirements.txt
   ```

## Configuration

1. **Set up your API key:**

   - Create a `.env` file in the project directory and add the following line, replacing the placeholder with your actual Together AI API key:

     ```
     TOGETHER_API_KEY=your_together_api_key
     ```

   - **Note:** Ensure that the `.env` file is included in your `.gitignore` to prevent accidental exposure of your API key.

## Running the App

1. **Run the Streamlit app:**

   ```bash
   streamlit run app.py
   ```

2. **Open your browser and navigate to `http://localhost:8501` to access the story generator interface.**

## Usage

1. **Enter your story prompt or idea in the input field.**
2. **The app will generate a story along with relevant visuals, using Together AI’s LLMs.**
3. **Continue generating, editing, or saving your stories as desired.**

## Features

- **Interactive story generation:** Easily create stories with the help of advanced LLMs.
- **Visual content integration:** Automatically generate or fetch visuals to enhance your stories.
- **Streamlit-powered UI:** Enjoy a smooth and intuitive user experience.
- **LangChain integration:** Connect seamlessly with Together AI models for flexible story generation.

## Contributing

Contributions are welcome! If you have ideas for enhancements or encounter any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
