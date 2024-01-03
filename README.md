# Degree-Validator-Knowledge-Representation-for-Course-Completion-Analysis

## Degree Completion Analyzer

## Introduction

This project provides a tool to analyze a student's degree completion status based on their academic transcript. It categorizes courses into predefined degree requirement categories and determines the remaining credits required for graduation.

## Requirements

- Python 3.x
- `spacy` library
- `en_core_web_md` model from SpaCy (required for word vectors)

To install the necessary SpaCy model, run:

```bash`
!python -m spacy download en_core_web_md

## Functionality Overview

The code provided categorizes courses, calculates credit hours, identifies failed courses, and suggests additional courses needed for degree completion.

    - **Course Categorization**: Utilizes SpaCy and numpy for natural language processing to categorize courses based on their similarity to predefined courses in specific categories.
    - **Credit Hours Calculation**: Determines completed credit hours for each category based on the provided transcript data.
    - **Identifying Failed Courses**: Detects failed courses within the transcript.
    - **Course Suggestions**: Offers suggestions for additional courses required to fulfill credit requirements.

## Contribution

Contributions that enhance functionality, improve accuracy, or optimize the categorization process are welcome. To contribute:

    - Fork the repository.
    - Create a new branch (git checkout -b feature/improvement).
    - Make changes and commit them (git commit -am 'Add new feature').
    - Push the changes to the branch (git push origin feature/improvement).
    - Create a Pull Request.

Please ensure the transcript data adheres to the expected CSV format for accurate analysis.

## Disclaimer

This tool is for demonstrative purposes only and should not replace official academic advice or degree requirement evaluations. Always consult your academic advisor or institution for accurate degree completion information.
