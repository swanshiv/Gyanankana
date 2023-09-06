# Gyanankana
Proposing a Automated Assessment Generation Platform for ALL {K-12, Higher Ed, Skilling, Hiring}
# Automated Question Generation with OpenAI and Gradio

This repository contains a Python script that demonstrates how to generate questions using OpenAI's GPT-3 and provides a web-based user interface for generating questions based on a given passage.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setting Up OpenAI API Key](#setting-up-openai-api-key)
- [Usage](#usage)
  - [Generating Questions](#generating-questions)
  - [Gradio User Interface](#gradio-user-interface)
  - [Bloom's Taxonomy Levels](#blooms-taxonomy-levels)
  - [Question Types](#question-types)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Getting Started

### Prerequisites

Before running the script, you'll need to have the following prerequisites installed:

- Python 3.x
- `openai` library
- `gradio` library

You can install the required libraries using `pip`:
<pre>
  pip install openai
  pip install gradio
</pre>

### Setting Up OpenAI API Key
To use OpenAI's GPT-3, you need to set your OpenAI API key. Replace "YOUR OPEN AI API KEY" in the script with your actual API key.
<pre>
  api_key = "YOUR OPEN AI API KEY"
</pre>

## Usage

### Generating Questions
The script can generate questions based on a provided passage. To generate a question, you can call the generate_blooms_question function and specify the paragraph, Bloom's Taxonomy level, and question type as parameters. The function will return the generated question.

Example:
<pre>
  paragraph = "Your passage goes here."
  bloom_level = "remembering"  # Choose from "remembering," "understanding," "applying," "analyzing," "evaluating," or "creating."
  question_type = "Multiple Choice"  # Choose from "Multiple Choice" or "Multiple Select."

  generated_question = generate_blooms_question(paragraph, bloom_level, question_type)
  print(generated_question)
</pre>

### Gradio User Interface
The script also provides a web-based user interface using Gradio. You can interactively generate questions by running the Gradio interface. Simply run the script, and it will launch the interface.
<pre>
  python automated_question_generation.py
</pre>

### Bloom's Taxonomy Levels
The script supports the following Bloom's Taxonomy levels for question generation:

  - Remembering
  - Understanding
  - Applying
  - Analyzing
  - Evaluating
  - Creating

### Question Types
You can generate questions in two types:
  - Multiple Choice
  - Multiple Select

## Contributing
- Contributions to this project are welcome. If you have ideas for enhancements, optimizations, or adaptations, please feel free to contribute.
- If you are expert in pedagogy and/or assessments for K-12 or Higher Ed feel free to drop me an email provided in the Contact section. 

## License
- This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- This project utilizes OpenAI's GPT-3 for natural language generation.
- Gradio is used for creating the interactive user interface.

## Contact
- For any questions, suggestions, or collaborations, you can reach me at [shivranjan1689@gmail.com](mailto:shivranjan1689@gmail.com).
