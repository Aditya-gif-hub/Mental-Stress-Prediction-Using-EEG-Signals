# Mental-Stress-Using-EEG

This project analyzes brain activity patterns from 13 EEG electrodes to classify cognitive states and detect potential neurological abnormalities. The system provides real-time analysis, visualization, and prediction capabilities through an interactive web interface.
✨ Features

Multi-electrode EEG Analysis - Processes signals from 13 brain regions
Real-time Stress Detection - Classifies focus levels and mental states
Abnormality Detection - Identifies potential cognitive issues
Interactive Dashboard - User-friendly Streamlit web interface
Data Visualization - Comparative charts and statistical analysis
Alert System - Color-coded warnings for abnormal patterns

🚀 Quick Start
Prerequisites
bashPython 3.7+
pip (Python package manager)
Installation

Clone the repository
bashgit clone https://github.com/yourusername/Mental-Stress-Prediction-Using-EEG-Signals.git
cd Mental-Stress-Prediction-Using-EEG-Signals

Install dependencies
bashpip install -r requirements.txt

Run the application
bashstreamlit run app4.py

Open your browser and navigate to http://localhost:8501

📦 Dependencies
Create a requirements.txt file with the following packages:
txtstreamlit>=1.0.0
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
scikit-learn>=1.0.0
pickle-mixin>=1.0.2
🧪 Usage
Basic Usage

Launch the application:
bashstreamlit run app4.py

Input EEG values for each brain region (0-5500 range)
Select blink state (0 or 1)
Click "Predict" to get focus classification and analysis

EEG Regions
The system monitors 13 EEG electrode positions:
RegionElectrodesFunctionFrontalAF3, AF4, F7, F3, FC5, FC6, F4Attention, Executive FunctionsTemporalT7, T8Memory, Language ProcessingParietalP7, P8Spatial Awareness, Sensory IntegrationOccipitalO1, O2Visual Processing
Application Versions

app.py - Basic 5-region interface for quick analysis
app2.py - Detailed 13-electrode analysis with defect detection
app3.py - Enhanced visualization with user statistics
app4.py - Complete interface with comprehensive reporting ⭐ Recommended

📊 Output Interpretation
Alert Levels

🔴 High Alert: Potential anxiety, hyperactivity, or stress
🟡 Low Alert: Possible depression, attention issues, or cognitive decline
🟢 Normal: Values within expected range

Predictions

Focused (1): User shows concentrated attention patterns
Not Focused (0): User exhibits distracted or unfocused brain activity
