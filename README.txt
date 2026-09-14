MECHANICAL QUIZ V2
==================

Firebase project: mechanical-quiz-eec08
Admin email: ngothang90@gmail.com

FEATURES
- 500 questions
- 25 questions per test
- Employee code + full name
- Anonymous Firebase authentication for employees
- Email/password authentication for admin
- Personal attempt history by Firebase UID
- Public learning statistics via publicAttempts (no answer details)
- Public ranking, topic accuracy, and most-missed questions
- Admin dashboard with full attempts, ranking, topic analysis and history

FOLDER
index.html
questions.json
questions_500.csv
firestore.rules
static/firebase-config.js

IMPORTANT
1. Firestore must be created.
2. Authentication: Anonymous and Email/Password must be enabled.
3. Create admin user with email ngothang90@gmail.com.
4. Publish firestore.rules from this package.
5. Host index.html through a web server / Firebase Hosting. Do not open as file://.
6. publicAttempts intentionally contains only learning-statistics fields and per-question correctness, not the selected answer/correct answer/explanation.
7. This login is not identity-proofing: anonymous login means a user can technically type another employee code. For official personnel verification, later add an employee roster + stronger authentication.
