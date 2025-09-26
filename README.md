🇸🇱 Salone Plant Doctor: AI-Powered Crop Health Diagnosis
Project Overview
The Salone Plant Doctor is a mobile-first web application designed to provide immediate, actionable diagnosis and treatment advice for plant diseases and deficiencies common in Sierra Leone and West Africa. The primary goal is to empower local farmers and home gardeners with the technology needed to quickly identify crop health issues, minimizing yield loss and promoting sustainable agricultural practices.

Key Features
1. 🌿 Instant AI Diagnosis (Core Feature)
Users can take or upload a photo of a sick plant leaf or area. The application leverages the Gemini API with image understanding capabilities to:

Identify the Disease or Deficiency (e.g., Early Blight, Nitrogen Deficiency).

State the Cause of the problem.

Provide a list of Actionable Treatment Steps suitable for local application.

2. 🔔 Notifications & Reminders
A central notification system to keep users updated:

Treatment Reminders: Alerts for scheduled treatment steps saved after a diagnosis.

Expert Replies: Notifications when a query submitted to an agricultural expert is answered.

Community Alerts: Broadcasts on regional pest warnings or essential farming tips.

3. My History (Planned)
Allows users to save all previous diagnoses and treatment plans to track the health progression of their crops over time.

4. Chat with Experts (Planned)
A feature allowing users to submit specific questions about their diagnosis to local agricultural officers or experts for personalized, human-reviewed advice.

Technical Implementation
The application is built as a single-page, fully responsive web application using modern standards:

Frontend: HTML5, CSS (via Tailwind CSS for rapid, responsive styling), and pure JavaScript.

AI Backend: The Gemini API (gemini-2.5-flash-preview-05-20) is used for multimodal analysis. The API is configured to return a structured JSON output, ensuring reliable data extraction for the diagnosis title, cause, and treatment steps.

Data Storage (Planned): Firebase Firestore will be used to handle user authentication, and persistent storage for diagnosis history and real-time chat data, ensuring data integrity across user sessions.
