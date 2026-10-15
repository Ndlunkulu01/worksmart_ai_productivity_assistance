# WorkSmart AI – Workplace Productivity Assistant

## 1. Project Overview

WorkSmart AI is a web-based productivity assistant designed to help employees organise daily tasks, prepare professional emails, summarise meeting notes, and monitor workplace productivity.

The project demonstrates how Artificial Intelligence (AI) can support common workplace activities, reduce repetitive manual work, and improve efficiency. It combines a functional task management dashboard with carefully designed AI prompts that can be copied into ChatGPT.

## 2. Problem Statement

Employees often spend significant time managing tasks, writing emails, organising meeting notes, and tracking completed work. These activities can reduce the time available for important responsibilities.

WorkSmart AI addresses this challenge by bringing essential productivity tools together in one simple dashboard.

## 3. Project Objectives

- Automate and simplify repetitive workplace activities using AI-assisted prompts.
- Improve task organisation and prioritisation.
- Help users prepare clear, professional email responses.
- Turn meeting notes into structured summaries and action items.
- Track task completion and estimate potential time savings.
- Promote responsible, ethical, and secure use of AI.

## 4. Main Features

### Productivity Dashboard
Displays the total number of tasks, completed tasks, task completion rate, and estimated time saved.

### Task Manager
Allows users to create tasks, assign priority levels, mark tasks as completed, and delete tasks. Task information is saved in the browser using local storage.

### AI Email Assistant
Generates structured prompts to summarise emails, draft professional replies, and identify deadlines or next steps. Users can copy these prompts into ChatGPT for assistance.

### Meeting Notes Assistant
Creates prompts that instruct ChatGPT to organise meeting notes into summaries, decisions, action items, owners, deadlines, and outstanding questions.

### Productivity Report
Summarises task completion and calculates estimated time savings based on user-entered values.

### Responsible AI Guidelines
Explains privacy protection, human oversight, accuracy checks, transparency, and safe handling of workplace information.

## 5. Technologies Used

- HTML5 – provides the structure of the application.
- CSS3 – creates the layout, colours, and responsive design.
- JavaScript – powers task management, dashboard statistics, and prompt generation.
- Browser Local Storage – saves task information in the user's browser.
- ChatGPT – processes prompts for email assistance and meeting-note summaries.

## 6. Prompt Engineering Techniques

The project uses structured prompts to improve the quality and reliability of AI-generated outputs.

The prompts include:

- **Role definition:** Instructing the AI to act as a professional workplace assistant.
- **Clear instructions:** Specifying whether the AI should summarise, draft, or extract action items.
- **Context:** Providing the email or meeting notes needed to complete the task.
- **Output structure:** Requesting organised summaries, decisions, deadlines, and next steps.
- **Constraints:** Telling the AI not to invent facts, names, commitments, or deadlines.
- **Human verification:** Asking the AI to identify missing information and flag details that require review.

These techniques make AI outputs easier to understand, check, and use in professional settings.

## 7. Ethical and Responsible AI Practices

WorkSmart AI promotes responsible AI use through the following safeguards:

- **Privacy:** Users should use fictional or anonymised information and avoid entering confidential business or personal data.
- **Accuracy:** AI-generated information must be checked because AI can produce incorrect or incomplete responses.
- **Human oversight:** Users must review and approve AI-assisted emails and summaries before sharing them.
- **Transparency:** Users should follow workplace policies about disclosing AI assistance.
- **Fairness:** AI outputs should not be used alone to make important employment or customer decisions.
- **Security:** Task information is stored locally in the browser. Users should avoid sensitive information, particularly on shared computers.

## 8. Expected Productivity Benefits

WorkSmart AI is intended to reduce repetitive work, improve organisation, and make workplace information easier to process.

Potential benefits include:

- Less time spent structuring routine emails.
- Faster organisation of meeting notes.
- Better visibility of tasks and priorities.
- Easier tracking of completed work.
- More consistent and professional written communication.

Time savings shown in the dashboard are estimates entered by the user. They are not independently measured or verified results.

## 9. How to Run the Application

1. Open the GitHub repository containing this project.
2. Open the `index.html` file.
3. Download the file to your computer, or use GitHub's file view to access the source code.
4. If downloading, open `index.html` in a modern web browser.
5. Navigate through the dashboard sections.
6. Add sample tasks, change their priorities, and mark tasks as completed.
7. Test the email and meeting-note assistants using fictional examples.
8. Check the productivity report to view the calculated statistics.

An internet connection is required to use ChatGPT for the AI-assisted tasks. The dashboard's task management and prompt-generation features run in the browser.

## 10. Limitations

This version is an educational prototype. It generates prompts for ChatGPT but does not automatically send prompts to an AI API. It does
