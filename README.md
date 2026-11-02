# Eye-Tracking Experimental Dataset

## 1. Overview

This repository contains an anonymized experimental dataset collected as part of a research project on a camera-based eye-tracking system.

The dataset records gaze-direction trials and reaction times obtained during experiments using a glasses-mounted camera. The system is designed to estimate gaze direction and support interaction with a 3D robotic eye model.

The dataset is intended to support research transparency, reproducibility, and further investigation in eye-tracking and assistive technologies.

## 2. Research Information

- **Research Title:** [Development of an Intelligent Eye-Controlled Virtual 
Keyboard System for Assisting People with Disabilities. ]
- **Authors:** [Abdel-Gawad A. Abdel-Samei1*, Mohamed Bassiouny1, Ayman M. Brisha1 and Abdel Salam Shaaban2]
- **Affiliation:** Faculty of Technology and Education, Beni-Suef University, Egypt
- **Research Area:** Eye Tracking, Computer Vision, Assistive Technology

## 3. Dataset Description

The dataset contains experimental records from participants performing gaze-direction trials.

Each row represents an individual experimental trial.

The dataset includes the following variables:

| Variable | Description |
|---|---|
| Username | An anonymized participant identifier |
| Trial | Sequential trial number for each participant |
| Target | Intended gaze direction |
| Result | Classification outcome of the trial |
| Reaction_Time | Recorded reaction time for the trial |

## 4. Gaze Directions

The experimental targets include five gaze directions:

- UP
- DOWN
- LEFT
- RIGHT
- CENTER

The `Result` variable indicates whether the system correctly classified the intended gaze direction.

## 5. Reaction Time

The `Reaction_Time` variable represents the recorded reaction time for each experimental trial.

The values are recorded in seconds, subject to confirmation of the measurement unit in the original data acquisition system.

Reaction time can be converted to milliseconds using:

Reaction Time (ms) = Reaction Time (s) × 1000

## 6. Data Format

The dataset is provided in CSV and Excel formats.

These formats are compatible with:

- Microsoft Excel
- Python (Pandas)
- MATLAB
- R
- Other statistical analysis software

## 7. Potential Applications

The dataset may be used for:

- Evaluating gaze-direction classification performance.
- Analyzing reaction-time distributions.
- Investigating differences between gaze directions.
- Supporting research on camera-based eye-tracking systems.
- Developing and evaluating assistive human-computer interaction systems.

## 8. Ethical Considerations

Participant identifiers have been anonymized.

The dataset is intended to be shared in accordance with the applicable institutional ethical approval, participant consent, and research data-sharing requirements.

## 9. Data Availability

The experimental dataset is available at:

[Insert the GitHub repository URL]

## 10. Citation

If you use this dataset in your research, please cite the associated research article:

[Insert the full citation when the article is published]

## 11. Contact

For questions regarding the dataset, please contact the corresponding author:

[Insert corresponding author email]
