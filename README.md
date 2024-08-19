# AI Book Writer Continuation

This project is an AI-powered application designed to assist authors in generating new chapters for their novels based on provided inputs.

## Features

- Generate chapter content based on user inputs
- Select and analyze chapter structure
- Refine generated content
- Save generated chapters as Word documents

## Setup

1. Clone this repository
2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
4. Set up your OpenAI API key as an environment variable:
   ```
   export OPENAI_API_KEY='your-api-key-here'
   ```

Alternatively, you can use the setup script as well:
```
chmod +x scripts/setup.sh
./scripts/setup.sh
```

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app/main.py
   ```
2. Open your web browser and navigate to the URL provided by Streamlit
3. Use the interface to input your novel details and generate chapters

## Testing

Run the tests using pytest:
```
pytest tests/
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.