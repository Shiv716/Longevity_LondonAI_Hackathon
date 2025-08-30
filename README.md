# Longevity

**Voice-to-Insight Lung Cancer Risk Assessment Tool**

Longevity is a web-based proof-of-concept demonstrating AI-powered conversation analysis for lung cancer risk assessment. It integrates audio transcription, natural language analysis, and voice synthesis to showcase how AI could assist in clinical decision support.

---

## Important Clarifications

This is a **demonstration application** that:
- Transcribes audio using the OpenAI Whisper API
- Analyzes transcribed text for lung cancer symptoms using GPT-4
- Generates voice output of results via ElevenLabs TTS
- Provides static medical report samples for UI demonstration

---

## Features

### Actual Implementation
- Audio transcription with OpenAI Whisper API
- Symptom and risk factor extraction using GPT-4
- Voice synthesis of results using ElevenLabs TTS
- Risk visualization with percentage scores and severity indicators
- API response logging for monitoring and debugging

### Demo Elements
- Predefined static medical documents (UI only, not analyzed)
- Risk meter visualization based on GPT-4 analysis

---

## Tech Stack

- Frontend: HTML5, CSS3, Vanilla JavaScript  
- Transcription: OpenAI Whisper API  
- Analysis: OpenAI GPT-4  
- Voice Output: ElevenLabs TTS API  
- Deployment: Static HTML (localhost or any web server)  

---

## Setup

1. Clone or download this repository.  
2. Open `index.html` in Chrome or Edge.  
3. Provide required API keys:  
   - OpenAI API key (with Whisper and GPT-4 access)  
   - ElevenLabs API key (for voice output)  

---

## Workflow

1. Record or upload an audio file → sent to Whisper API  
2. Transcription → audio converted to text  
3. Analysis → GPT-4 extracts symptoms and risk factors  
4. Risk calculation → risk score derived from extracted findings  
5. Voice output → ElevenLabs TTS generates spoken summary  

---

## Security Considerations

- API keys are stored in-browser; not secure for production  
- No real patient data is processed  
- Demo documents are static and illustrative only  
- All processing is performed via external APIs  

---

## Medical Disclaimer

This is **not a medical device or diagnostic tool**.  
- Intended for demonstration and educational purposes only  
- Not validated for clinical or diagnostic use  
- Does not provide medical advice  
- Always consult qualified healthcare professionals for medical decisions  

---

## Known Limitations

- Requires an OpenAI account with Whisper enabled  
- Browser-based API key handling (security risk)  
- Static demo documents (no real EHR integration)  
- Risk scores are illustrative only, not clinically validated  

---

## What This Is vs. What It Appears To Be

- **Appears to be:** A clinical decision support system integrating medical records  
- **Actually is:** A transcription + text analysis demo with UI visualization and optional voice synthesis  

---

## Contributing

This project is a proof-of-concept. For real-world medical applications, additional requirements include:  
- HIPAA/GDPR compliance  
- Medical device regulatory approval (FDA, CE)  
- Clinical validation studies  
- Healthcare IT security standards  

---

## Contributors

Thanks to everyone who has contributed to **Longevity**:  

- [Shivang Chaudhary](https://www.linkedin.com/in/shivang-chaudhary-2235831b5/)
- [Aswin Giridhar Subramanian](https://www.linkedin.com/in/aswin-giridhar-subramanian/)

---

## License

MIT License.  
Use at your own risk. Not intended for clinical or medical use.
