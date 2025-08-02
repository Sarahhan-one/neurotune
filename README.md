# NeuroTune - Music Therapy Analyzer using EEG Technology

NeuroTune is an innovative music analyzer designed to enhance music therapy using real-time EEG (electroencephalography) technology. This tool helps assess the suitability of songs for therapeutic purposes, allowing caregivers to select music that is more likely to benefit individuals, particularly those with cognitive or communication challenges like dementia and aphasia.

**[Check out the video in action](https://www.youtube.com/watch?v=S9OEucX8x2k)**

<img width="1000" height="600" alt="Image" src="https://github.com/user-attachments/assets/fd90740e-9ff1-4ee9-b5d0-50ca149f6fb5" />


## Problem Statement

Music therapy has been shown to improve cognitive function, emotional stability, social engagement, and communication skills. However, the success of music therapy depends heavily on **selecting the right music**. For individuals with conditions like **dementia** or **aphasia**, choosing the appropriate music can be challenging because they often have difficulty expressing their preferences reliably. Additionally, **access to qualified music therapists** is limited by factors like availability and cost.

Traditional methods of categorizing patients and using generalized songs based on disorder types are not always effective, as not every song resonates with every patient. 

NeuroTune addresses these challenges by:
1. Evaluating real-time brain activity to determine whether a song is liked, neutral, or disliked by the patient.
2. Empowering caregivers to conduct personalized, solo music therapy sessions without the need for a music therapist's presence.

## Features

- **Real-Time EEG Analysis**: NeuroTune analyzes brain activity to categorize songs as “liked,” “neutral,” or “not liked,” eliminating the need for subjective patient reports.
- **Personalized Music Therapy**: Provides caregivers with the tools to conduct solo "receptive" music therapy sessions, allowing for individualized care.
- **Improved Patient Outcomes**: Focuses on individuals with dementia and aphasia, enhancing their emotional stability, cognitive function, and communication skills.

## Target Audience

- **Caregivers** of individuals with dementia or aphasia.
- **Healthcare professionals** working with cognitive and communication impairments.
- **Researchers** interested in cognitive health and music therapy.
- **Music therapists** looking for tools to optimize therapy sessions.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/neurotune.git

## As soon as you git clone / git pull...

### Make sure you are in "neurotune" folder

Install the virtualenv package:

- pip install virtualenv

Create a virtual environment:

- virtualenv venv

Start the virtual environment:

- in Mac:
  - source venv/bin/activate
- in Windows:
  - venv\Scripts\activate

Install all packages:

- pip install -r requirements.txt

Also in a separate terminal/command prompts:

- npm i

## To start the project...

### Make sure you are in "neurotune" folder

First, do everything that was needed for "As soon as you git clone / git pull..."
Second, start the backend server:

- python {path to backend_server.py}

Example for mac:

- python ./src/model/backend_server.py

Third, start the frontend server:

- npm start

## Before you want to push...

### Make sure you are in "neurotune" folder

Save all requirements in requirements.txt:

- pip freeze > requirements.txt
