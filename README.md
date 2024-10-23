# AI Technical Interviewer

A Python-based AI interviewer that conducts technical interviews focusing on Python and Algorithms topics.

## Overview

This application simulates a technical interview by:
- Asking questions about Python and Algorithms
- Adapting difficulty based on performance
- Analyzing responses using keyword matching
- Providing real-time feedback and scoring

## Project Structure

```
.
├── main.py                 # Entry point of the application
├── interviewer.py          # Core interview logic
├── candidate.py            # Candidate tracking and scoring
└── interview_questions.py  # Question bank and categories
```

## Requirements

This project runs in WebContainers and uses only Python standard library modules. No additional package installation is required.

Python Version: 3.10+

## Running the Application

To start the interview:

```bash
python main.py
```

## Features

- Adaptive difficulty levels (easy/medium/hard)
- Multi-topic assessment
- Real-time response analysis
- Performance tracking
- Detailed feedback system

## Interview Topics

1. Python
   - Language fundamentals
   - Data structures
   - Advanced concepts

2. Algorithms
   - Basic concepts
   - Sorting algorithms
   - Data structures
   - Advanced algorithms

## Scoring System

- Score range: 0-30
- Difficulty adjusts based on performance:
  - Score ≥ 8: Hard level
  - Score ≥ 5: Medium level
  - Score < 5: Easy level

## Future Enhancements

Potential improvements when running in a full Python environment:
- Integration with NLP libraries
- Machine learning-based response analysis
- Extended question bank
- More sophisticated scoring algorithms