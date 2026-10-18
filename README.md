# GAS 測驗題自動生成器 / GAS Quiz Generator

A free educational web tool that converts plain-text multiple-choice questions into Google Apps Script code for creating Google Forms quizzes.

## Live demo
https://formcreators.netlify.app/

## How it works
1. Paste questions and answer choices into the left panel.
2. Click **轉換為 GAS 程式碼**.
3. Copy the generated code into the Apps Script editor attached to a Google Form.
4. Review the generated quiz and settings before using it with students.

## Features
- Recognizes several common Chinese multiple-choice formats.
- Generates Google Apps Script for Google Forms quizzes.
- Includes an in-page guide for teachers.
- Runs as a static HTML page.

## Important cautions
- **Review every answer key**: in the current version, questions without a recognized answer default to choice A.
- Generated code **deletes existing form items** before adding new questions. Use a new blank form.
- Generated forms collect email, class/seat number and student name by default; review privacy settings before sharing.
- Verify scoring and questions in the actual Google Form before assigning it to students.

## Local use
Open `index.html` in a browser. Styling loads Tailwind CSS and Google Fonts from third-party CDNs.

## License
MIT — see [LICENSE](LICENSE).

## Code of Conduct
See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Author
Hung-Chi Yin (尹鴻綺), syshmusic.
