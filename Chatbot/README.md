# NavRakshak Chatbot – Voice-Enabled Tourist Safety Assistant

## Overview

NavRakshak is a bilingual (English/Hindi), voice-enabled chatbot designed to assist tourists with emergency support, location-aware services, and safety information. Built with AWS services, it combines a seamless conversational AI experience with real-time safety features to empower travelers.

---

## Features

- Voice-first interaction with push-to-talk mic and smooth audio playback  
- Automatic language detection and bilingual UI  
- Real-time emergency SOS alerts with location sharing  
- Nearby police station and hospital info with Google Maps links  
- Area safety assessment and latest safety updates  
- Digital ID management for tourists  
- Mobile-optimized, clean UI with compact hide-menu button beside the mic  

---

## Architecture

- **Frontend** hosted on Amazon EC2 handles audio capture, voice playback, and geolocation  
- **Amazon Lex V2** powers conversational AI, with Lambda hooks for backend logic  
- **AWS Lambda** implements business logic and interfaces with databases  
- **API Gateway** securely exposes Lambda functions as APIs  
- **Amazon RDS** stores persistent user data, profiles, and logs  
- **Amazon Cognito** manages user authentication and authorization  

---

## Installation and Setup

1. Setup AWS resources: Lex V2 bot, Lambda functions, API Gateway, RDS, Cognito user pool  
2. Configure bot and API IDs in `script.js`  
3. Deploy frontend on EC2 or static web server  
4. Enable mic and location permissions in browser  

---

## Usage

- Speak or type to interact with the chatbot  
- Get immediate help and safe-route info based on your location  
- Access digital ID and safety updates at your fingertips 

---

## Technologies Used

- HTML, CSS (glassmorphism, responsive), JavaScript frontend  
- Amazon Lex V2, AWS Lambda, API Gateway, Amazon RDS, EC2, Cognito  
- Browser APIs: MediaRecorder, SpeechSynthesis, Geolocation  

---

## Contributing

Contributions welcome! Fork, improve, and submit pull requests to enhance features or language support.

---

## License

MIT License - free to use and modify.
