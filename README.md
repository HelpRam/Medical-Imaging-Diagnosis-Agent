# Medical Imaging Diagnosis Agent

A Medical Imaging Diagnosis Agent build on phidata powered by Gemini 2.0 Flash Experimental that provides AI-assisted analysis of medical images of various scans. The agent acts as a medical imaging diagnosis expert to analyze various types of medical images and videos, providing detailed diagnostic insights and explanations.

## Features

- **Comprehensive Image Analysis**
- User Authentication: Configure Google API keys for secure integration.
- Medical Image Upload: Supports multiple formats (JPG, PNG, DICOM, etc.).
- AI-Powered Analysis: Provides detailed insights on medical images using a Gemini-based model.
- Patient-Friendly Explanations: Delivers simple, understandable results for non-expert users.
- Research Context Integration: Searches for relevant medical literature and protocols via DuckDuckGo.
- Interactive UI: User-friendly Streamlit interface with a sidebar configuration panel.

## How to Run

1. **Setup Environment**
   ```bash
   # Clone the repository
  git clone https://github.com/HelpRam/Medical-Imaging-Diagnosis-Agent.git

   # Install dependencies
   pip install -r requirements.txt
   ```

2. **Configure API Keys**
   - Get Google API key from [Google AI Studio](https://aistudio.google.com)

3. **Run the Application**
   ```bash
   streamlit run ai_medical_imaging.py
   ```

## Analysis Components

- **Image Type and Region**
  - Identifies imaging modality
  - Specifies anatomical region

- **Key Findings**
  - Systematic listing of observations
  - Detailed appearance descriptions
  - Abnormality highlighting

- **Diagnostic Assessment**
  - Potential diagnoses ranking
  - Differential diagnoses
  - Severity assessment

- **Patient-Friendly Explanations**
  - Simplified terminology
  - Detailed first-principles explanations
  - Visual reference points

##Technologies Used

Programming Language: Python

Frameworks:
Streamlit for UI
Gemini for AI analysis

Tools:
DuckDuckGo API for research integration
Pillow for image processing

## Disclaimer

This tool is for educational and informational purposes only. All analyses should be reviewed by qualified healthcare professionals. Do not make medical decisions based solely on this analysis.
