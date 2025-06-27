# Scrum Call Assistant 

## Introduction 

A RAG-enabled chatbot that helps a manager track employee updates and progress.

This project was built as the final project for the PESU I/O course 'Agentic Systems 101.'

## Problem Statement

Employees often spend hours each day on scrum calls providing work updates to managers — most of which are repetitive or irrelevant to the majority of participants. Despite being a common practice in most organizations, these calls tend to be redundant, exhausting, and ultimately a waste of employee time and company resources — time that could otherwise be spent on productive work.

## Proposed Method

To address this problem, I propose implementing a RAG (Retrieval-Augmented Generation) based chatbot integrated with a Google Sheet where employees can log their daily updates.
The chatbot enables managers to filter updates based on relevance, deadlines, or specific queries. This allows them to quickly identify employees who require further discussion — such as those facing blockers, missing deadlines, or needing clarification — and engage only with them.

## Results

The implementation of the RAG-based chatbot significantly reduces the time spent on daily scrum calls by replacing broad, repetitive meetings with a targeted, on-demand update system. Managers can now selectively engage only with employees who require attention — such as those behind on deliverables or those with unresolved queries.

## Discussion

The most significant impact of this project has to be on time management and human resource management. If a simple RAG inclusion can help filter out different employee needs, I'm sure there can be more widespread solutions to daily scrums in companies such as integrating agents for summarisation reports and more focussed tracking based on project deadlines. Additional features such as updates being logged directly onto the database (Google Sheets in this case) from meeting discussions and calls can also be implemented.

## Project Setup and Execution

Download the zip file or clone the repository 

```bash
git clone https://github.com/sudiksha-chindula/scrum-call-assistant.git
```

Connect to a kernel and run the notebook [scrum_call_assistant.project.ipynb](https://github.com/sudiksha-chindula/scrum-call-assistant/blob/main/scrum_call_assistant_project.ipynb)

## Authors

[@sudiksha-chindula](https://github.com/sudiksha-chindula)

## Contributions

Open source contributions and pull requests are welcome

## License

[MIT](https://choosealicense.com/licenses/mit/)
