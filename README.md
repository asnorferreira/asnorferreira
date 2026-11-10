# Asnor Ferreira

**Software Engineer | Java Backend & Applied AI**

I'm a software engineer based in Brazil with a B.Sc. in Software Engineering, currently working as a Java backend developer. My background covers data persistence, application security, software architecture, and object-oriented design.

I work with Java and Spring Boot, and have a solid grounding in Apache Kafka, design patterns, machine learning, large language models, and fine-tuning. My projects also use Python and TypeScript, connecting backend development with text processing and model inference.

[LinkedIn](https://www.linkedin.com/in/asnor-ferreira/)

## Technical background

| Area | Knowledge and tools |
| --- | --- |
| Backend development | Java, Spring Boot, HTTP APIs, Apache Kafka, event-driven communication |
| Architecture and design | Object-oriented programming, design patterns, separation of concerns, service boundaries |
| Data and security | Data persistence, data modeling, authentication, authorization, input validation |
| AI and machine learning | LLMs, fine-tuning, natural language processing, embeddings, semantic similarity, model evaluation |
| Implementation and validation | Python, TypeScript, MongoDB, PyTorch, Docker Compose, GitHub Actions, automated testing |

## Selected work

### [hybrid-text-similarity](https://github.com/asnorferreira/hybrid-text-similarity)

A local application for comparing Brazilian Portuguese documents at the sentence level. It combines lexical similarity using TF-IDF with semantic similarity using multilingual Sentence-BERT, and shows the sentence matches behind the comparison.

The application accepts text-based PDF, DOCX, TXT, and pasted text. Users can save comparisons, review their history, and print reports. It brings document ingestion, model inference, persistence, and authenticated access into one application.

The implementation includes:

- A Python/Flask comparison service and a TypeScript/Next.js web application connected through versioned HTTP contracts. The comparison core separates domain logic, application services, and infrastructure adapters.
- MongoDB persistence with user-scoped access, session authentication, input validation, and comparison limits.
- Core tests with pytest and Hypothesis, plus integration and Playwright tests covering APIs, persistence, authentication, and service failure scenarios.
- Docker Compose environments, dependency lockfiles, model and corpus integrity checks, and a GitHub Actions validation workflow.

The repository includes evaluation methods, results, and limitations. Its similarity score supports document review; it does not establish plagiarism.

[Source code](https://github.com/asnorferreira/hybrid-text-similarity) · [Architecture](https://github.com/asnorferreira/hybrid-text-similarity/blob/main/docs/01-guia-base-teorica-e-arquitetura.md) · [Core tests](https://github.com/asnorferreira/hybrid-text-similarity/tree/main/core/tests) · [CI workflow](https://github.com/asnorferreira/hybrid-text-similarity/blob/main/.github/workflows/validation.yml)
