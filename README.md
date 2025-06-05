# AI-Powered Resume Builder

This application helps users create professional resumes using AI assistance. The app provides an intuitive interface to input your professional information and generates a well-formatted resume using Llama's language model.

## Features
- Interactive web interface using Streamlit
- AI-powered content suggestions
- Export to DOCX format
- Professional resume templates

## Security Notice ⚠️
This application requires a Llama API endpoint. For security:
- Never commit your `.env` file to version control
- Never share your API endpoint publicly
- Use the provided `.env.example` as a template
- Each user needs to set up their own API access

## Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/resume-builder.git
cd resume-builder
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up your environment:
```bash
cp .env.example .env
```
Then edit `.env` and add your Llama API endpoint.

5. Run the application:
```bash
streamlit run app.py
```

## Usage
1. Fill in your personal and professional information in the web interface
2. Get AI suggestions for improving your content
3. Generate and download your resume in DOCX format

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Security Best Practices
- Keep your API endpoint private
- Don't commit the `.env` file
- Use environment variables for sensitive data
- Regularly update dependencies
- Review code for security issues before merging

## License
This project is licensed under the MIT License - see the LICENSE file for details. 