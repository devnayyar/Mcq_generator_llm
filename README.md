# MCQ Generation from PDF using OpenAI API

Welcome to the MCQ Generation from PDF project! This project leverages the power of generative AI, specifically the OpenAI API, to automate the creation of multiple-choice questions (MCQs) from a given PDF document. This tool is designed to save educators and trainers valuable time and effort by streamlining the process of crafting assessment materials.

## Features

- **PDF Ingestion**: Seamlessly accepts a PDF document as input.
- **Content Analysis**: Uses OpenAI's text-processing capabilities to extract and analyze key concepts and factual information from the PDF content.
- **MCQ Generation**: Intelligently formulates relevant and challenging MCQs that test learners' comprehension of the PDF content. Incorporates techniques like question framing, answer choice generation, and difficulty balancing to create high-quality MCQs.
- **Answer Creation**: Automatically generates corresponding answers for each MCQ, ensuring a complete and self-contained assessment tool.
- **Excel Export**: Organizes and exports the generated MCQs and answers into a well-formatted Excel file, ready for immediate use or further customization.

## Potential Applications

- **Educators**: Reduce the time required to generate MCQs for exams, worksheets, or homework assignments.
- **Trainers**: Create engaging and effective assessments for employee onboarding or skill development programs.
- **Content Creators**: Automate MCQ creation for interactive learning modules.

## Technical Considerations

- **OpenAI API Integration**: Obtain an OpenAI API key and integrate it securely into the project.
- **Error Handling**: Implement robust error handling mechanisms to gracefully handle potential issues during PDF processing, MCQ generation, and answer creation.
- **Customization Options**: Offer options for customizing the number of MCQs, difficulty levels, answer key formatting, and Excel export styles to suit user preferences.

## Future Enhancements

- **Advanced Question Types**: Generate short answer, matching, or true/false questions in addition to MCQs.
- **Topic Identification**: Integrate topic identification capabilities to categorize MCQs by subject matter for better organization and study.
- **Answer Explanation Generation**: Generate answer explanations to provide learners with a deeper understanding.

## Ethical Considerations

- **Bias Mitigation**: Emphasize the importance of training OpenAI models on balanced and diverse datasets to minimize bias in the generated MCQs.
- **Responsible Use**: Encourage users to apply the tool responsibly, promoting genuine learning rather than rote memorization.

## Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/mcq-generator.git
   cd mcq-generator
   ```

2. **Create a Virtual Environment and Activate It**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Required Packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**
   Create a `.env` file and add your OpenAI API key:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

1. **Run the MCQ Generator**
   ```bash
   python generate_mcqs.py path/to/your/document.pdf
   ```

2. **Check the Output**
   The generated MCQs and answers will be saved in an Excel file in the output directory.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

1. **Fork the Repository**
2. **Create a New Branch**
   ```bash
   git checkout -b feature-branch
   ```
3. **Make Your Changes and Commit Them**
   ```bash
   git commit -m "Description of changes"
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature-branch
   ```
5. **Open a Pull Request**

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any inquiries or feedback, please contact:
- Name: [Dev Nayyar]
- Email: [ritanayyar1974@gmail.com]

---

Thank you for using the MCQ Generation from PDF project! We hope it helps you create high-quality assessment materials efficiently and effectively.