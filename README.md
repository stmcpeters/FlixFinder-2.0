# 🍿 FlixFinder 2.0

## Overview

FlixFinder 2.0 is a full-stack movie discovery application designed to demonstrate modern software quality engineering practices.

Users can browse movies, create accounts, manage preferences, and write reviews. The primary focus of this project is building a comprehensive automated testing framework that validates application quality across the UI, API, and backend services.

This project was rebuilt from an earlier FlixFinder application with a focus on improving architecture, test coverage, automation, and CI/CD practices.

---

## Features

### Application Features

- User registration and authentication
- Browse and search movies
- View movie details
- Create, edit, and delete movie reviews
- Personalized movie recommendations *(planned)*

### QA Automation Features

- REST API testing
- Automated API regression tests
- UI automation testing
- Test case documentation
- Continuous integration pipeline
- Negative and edge-case testing

---

## Tech Stack

### Frontend
- React
- Vite

### Backend
- FastAPI
- Python

### Database
- PostgreSQL

### Testing
- pytest
- Selenium
- Postman

### CI/CD
- GitHub Actions

---

## Project Structure

```
flixfinder-2.0/
│
├── client/          # React frontend
├── server/          # FastAPI backend
├── automation/      # API and UI automation
├── postman/         # API collections
├── docs/            # Test documentation
└── .github/         # CI/CD workflows
```

---

## Testing Strategy

This project focuses on validating application quality through multiple testing layers:

- API testing
- UI automation
- Integration testing
- Regression testing
- Negative testing
- Error handling validation

---

## Getting Started

### Prerequisites

- Node.js
- Python 3.x
- PostgreSQL
- Git

### Installation

Clone the repository:

```bash
git clone <repository-url>
cd flixfinder-qa
```

Install frontend dependencies:

```bash
cd client
npm install
```

Install backend dependencies:

```bash
cd server
pip install -r requirements.txt
```

---

## Future Improvements

- Add Docker support
- Add performance testing with k6
- Expand Selenium coverage
- Add automated test reporting

---

## Author

Stephanie McPeters-Esparza