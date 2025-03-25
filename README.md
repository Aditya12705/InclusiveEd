InclusiveEd AI is an AI-powered educational platform designed to address uneven access to quality education in the digital age, aligning with UN SDG 4: Quality Education. It provides personalized learning experiences for diverse learners, especially in underserved communities, by leveraging face recognition, voice interaction, and the Gemini 1.5 Flash API. This project was developed for the Google Solution Challenge 2025.

Project Overview
InclusiveEd AI tackles the challenge of uneven access to quality education by providing a scalable, technology-driven solution. It uses face recognition to identify students and adapt content to their learning style (practical, application, or theory), stored in an Excel database. The platform supports voice interaction with natural pacing, powered by the Gemini 1.5 Flash API for real-time responses, and includes offline fallback responses for low-connectivity areas. It’s designed to be inclusive, supporting students with visual or auditory impairments through voice-based interaction.

Features
Personalized Learning: Uses face recognition to identify students and adapt content to their learning style.
Voice Interaction: Supports voice input/output with 4-second silence detection for accessibility.
Real-Time Responses: Powered by the Gemini 1.5 Flash API for adaptive, personalized answers.
Offline Capability: Provides fallback responses for common topics (e.g., laws of motion) in low-connectivity areas.
Learning Style Adaptation: Tailors responses to practical, application, or theoretical learning styles.
Student Data Management: Stores student profiles in an Excel file for easy management.

Installation
Follow these steps to set up and run InclusiveEd AI on your local machine.

Prerequisites
Python 3.8 or higher
A webcam and microphone (for face recognition and voice input)
A Gemini API key (sign up at Google AI Studio to get one)

Technologies Used
Python: Core programming language.
Gemini 1.5 Flash API: For real-time, adaptive responses.
face_recognition: For identifying students.
speech_recognition: For voice input.
pyttsx3: For text-to-speech output.
pandas & openpyxl: For managing student data in Excel.
OpenCV (cv2): For webcam access in face recognition.
NumPy: For numerical operations.
python-dotenv: For secure environment variable management.
