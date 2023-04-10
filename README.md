# AI Assistant for PDF Summarization

This is an AI assistant that allows users to search for text in a PDF file and receive a summarized answer to their question. The assistant uses OpenAI's GPT-3.5 turbo and GPT-4 language model to provide a natural language response to the user's query.

## Setup
1. Clone the repository to your local machine.
2. Install the required Python packages by running `pip install -r requirements.txt`.
3. Create a `.env` file and add your OpenAI API key as a variable: `API_KEY=<your_api_key>`.
4. Run the script `pdf_summarizer.py` by running `python pdf_summarizer.py`.

## Usage
1. Run the `pdf_summarizer.py` script.
2. When prompted, enter the name of the PDF file you want to search.
3. Enter your search query.
4. The assistant will provide you with a summarized answer to your query.

## Features
- Supports PDF files of any length.
- Provides summarized answers to user queries using OpenAI's GPT-3.5 language model.
- Allows users to search for multiple keywords in the same query.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
