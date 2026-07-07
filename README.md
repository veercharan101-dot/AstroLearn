# AstroLearn

**AstroLearn** is an AI powered personalized astronomy education platform that combines emotion recognition with trusted astronomical datasets to create engaging and personalized learning experiences. Instead of providing the same astronomy content to every learner, AstroLearn understands a user's emotional context and recommends celestial events, NASA imagery, and educational resources that best match their interests and current state of mind.

The project demonstrates how artificial intelligence can be used to make STEM education more interactive, adaptive, and engaging while encouraging curiosity and exploration of the universe.

---

## The Problem

Most educational platforms follow a one-size-fits-all approach, presenting identical content regardless of a learner's emotional state, motivation, or engagement level. This often results in reduced interest, lower knowledge retention, and a less meaningful learning experience.

AstroLearn addresses this challenge by using artificial intelligence to personalize educational content. By combining natural language emotion recognition with real astronomical datasets, the platform recommends astronomy experiences that encourage curiosity, engagement, and exploration while making science education more accessible and enjoyable.

---

## Our Solution

AstroLearn uses Natural Language Processing (NLP) to analyze how a user is feeling through text input. The detected emotional context is then combined with trusted astronomy datasets to generate personalized recommendations, including celestial events, NASA imagery, constellations, planetary observations, and other astronomy-related educational content.

Rather than simply displaying astronomical information, AstroLearn provides contextual explanations describing what each recommendation is, why it is scientifically significant, and why it was selected for the user.

### Key Features

- AI-powered emotion recognition using Natural Language Processing
- Personalized astronomy recommendations based on user context
- Integration with NASA's Astronomy Picture of the Day (APOD)
- Meteor shower and celestial event recommendations
- Educational explanations accompanying every recommendation
- Clean and interactive web interface
- Scalable recommendation engine that can support additional educational domains in the future

---

## Repository Structure

```
AstroLearn/
│
├── app/
│   ├── main.py                  # Main Streamlit application
│   ├── pages/                   # Application pages
│   ├── components/              # Reusable UI components
│   └── assets/                  # Images, icons and styling
│
├── data/
│   ├── astronomy/               # Astronomy datasets
│   ├── emotions/                # Emotion datasets
│   └── processed/               # Cleaned datasets
│
├── models/
│   ├── emotion_classifier/      # NLP emotion recognition model
│   └── recommender/             # Recommendation engine
│
├── notebooks/                   # Model experimentation
│
├── docs/
│   ├── research/                # Literature review
│   ├── proposal/                # Project proposal
│   ├── presentation/            # Pitch deck
│   └── architecture/            # System diagrams
│
├── results/
│   ├── evaluation/              # Performance metrics
│   ├── screenshots/             # Application screenshots
│   └── demo/                    # Demo assets
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Datasets

### Emotion Recognition

- **GoEmotions Dataset**
  - https://github.com/google-research/google-research/tree/master/goemotions

### Astronomy Data

- **NASA Astronomy Picture of the Day (APOD) API**
  - https://api.nasa.gov/#apod

- **International Meteor Organization Meteor Shower Calendar**
  - https://www.imo.net/resources/calendar/

---

## Technology Stack

- Python
- Streamlit
- Hugging Face Transformers
- PyTorch
- Pandas
- Scikit-learn
- NASA APOD API

---

## Contact

- Veer Charan
- veer.charan101@gmail.com

---


---


