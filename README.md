# Fun Math AI Tutor — Grade 2

## Project Overview

Fun Math AI Tutor is a child-friendly mathematics practice website designed for Grade 2 students.

The website provides basic addition and subtraction exercises. It also includes a Botpress chatbot that helps children ask simple mathematics questions.

**Live Demo:** https://ovirupal.github.io/simpleMathWebsite/math.html

## Features

- Addition practice
- Subtraction practice
- Mixed mathematics practice
- Answer checking and correct-answer tracking
- Embedded Botpress mathematics chatbot
- Simple interface designed for young learners

## Technology Stack

- HTML, CSS and JavaScript — website interface and mathematics exercises
- GitHub Pages — website hosting
- Botpress — chatbot integration and conversation workflow

*Confirm the technologies against your actual source code before publishing.*

## Project Goals

- Make mathematics practice interactive.
- Help children understand basic arithmetic.
- Explore chatbot integration into a web application.
- Learn AI application development through a practical project.

## Testing Plan

The chatbot will be evaluated for:

1. Mathematical answer correctness
2. Quality of explanations and hints
3. Handling of incorrect answers
4. Generation of age-appropriate practice questions
5. Handling of unrelated questions

Testing results will be documented after validation.

## Future Improvements

- Add document-based learning resources if needed.
- Improve hints and step-by-step explanations.
- Add additional mathematics topics.
- Evaluate chatbot response quality and reliability.

## Disclaimer

This project is a learning prototype. Chatbot responses should be tested for accuracy and age-appropriateness before relying on them for children's education.

--------------------------------------------------------------------------------------------------------------------------------------------------


# AI Chatbot Evaluation Report

**Project:** Fun Math AI Tutor — Grade 2  
**Chatbot:** Grade 2 Math Helper  
**Platform:** Botpress  
**Testing Type:** Manual functional testing

## 1. Test Results

| Test ID | Test Scenario | Expected Behaviour | Result |
|---|---|---|---|
| TC-01 | Ask `7 + 5` | Give the correct answer with an explanation | PASS |
| TC-02 | Say `6 + 4 = 12, right?` | Correct the answer politely and explain | PASS |
| TC-03 | Request three addition questions without answers | Provide three questions without revealing answers | PASS |
| TC-04 | Ask for a hint for `8 + 6` without the answer | Give a useful hint without revealing the final answer | PASS |
| TC-05 | Ask for the capital of India | Politely redirect the conversation to addition or subtraction | PASS |

## 2. Observations

- The chatbot correctly solved the tested addition question.
- It corrected an incorrect answer in a friendly manner.
- It generated practice questions without showing their answers.
- It provided a hint rather than immediately revealing the answer.
- It redirected an unrelated question back to its intended maths-learning purpose.

## 3. Summary

**Test scenarios executed:** 5  
**Passed:** 5  
**Failed:** 0  
**Initial pass rate:** 100%

Pass rate = (Passed tests ÷ Total tests) × 100

## 4. Limitations

This was an initial manual evaluation using five scenarios. It does not establish that the chatbot will always provide correct answers or behave appropriately in every situation.

Further testing should cover subtraction, word problems, incorrect inputs, repeated questions, age-appropriate responses, and edge cases.

## 5. Conclusion

The chatbot passed all five initial test scenarios and demonstrated the expected behaviour in the tested examples. Additional testing is recommended before using it with children at scale.

