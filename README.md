# Auto-Processing-of-Emails

In today's fast-paced business environment, professionals often receive an overwhelming number of emails daily. Managing these emails efficiently is critical for ensuring timely responses, prioritizing important tasks, and maintaining effective communication. However, manually sorting, categorizing, and summarizing emails can be time-consuming and prone to errors. Leveraging Natural Language Processing (NLP) and machine learning techniques to automate these tasks can significantly enhance productivity and reduce the cognitive load on individuals. This project aims to develop an intelligent email processing system that categorizes, summarizes, and prioritizes emails, enabling users to focus on what truly matters.

# Workflow

```mermaid

graph TD
    A[Data Ingestion] -->|Azure & DVS| B[Preprocessing]
    B -->|Azure Pipelines| C[Data Versioning]
    C -->|DVS + Azure Blob Storage| D[Model Training]
    D -->|OLA Krutrim Cloud| E[Model Versioning]
    E -->|OLA Krutrim Cloud| F[Model Evaluation]
    F -->|OLA Krutrim Cloud| G[Model Deployment]
    G -->|Docker + OLA Krutrim API| H[Flask Backend]
    H -->|Python-based API| I[Add-in Deployment]
    I -->|Yeoman + Azure Static Files| J[Outlook Add-in]
    G -->|OLA Krutrim Cloud| K[Monitoring & Logging]
    K -->|OLA Krutrim Cloud| L[CI/CD Pipelines]




```
