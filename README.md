# Emergency Access Risk Assessment During Extreme Wind Events

## Project Overview

This project explores how publicly available weather data can be reframed into an **operational access-risk signal** to support emergency preparedness during extreme wind events in Canada.

Rather than forecasting weather itself, the focus is on **risk awareness and decision support** — helping translate meteorological observations into interpretable signals that could inform planning and resource positioning.

This repository is part of an **ongoing personal research project** and is shared for portfolio and educational purposes.




## Motivation

Weather prediction always depends on its intended use. In the context of natural hazards, accurate forecasts alone rarely prevent impact. Instead, forecasting plays a key role in **risk management**, enabling better preparedness and response.

This project is motivated by the idea that, for emergency response contexts, the goal is not to prevent extreme events, but to **anticipate operational constraints** and reduce potential harm through better situational awareness.




## Data

- Public daily climate observations from **Environment and Climate Change Canada (ECCC)**
- Station-based wind data
- Multi-year historical coverage
- Real-world data quality characteristics, including missing values

Only publicly available datasets are used.




## Methodological Approach (High Level)

The project follows a conservative and interpretable analytical approach, emphasizing:

- Careful data quality inspection and cleaning  
- Leakage-aware temporal splitting  
- Feature construction using only historically available information  
- An interpretable classification framework to express access risk levels  

Model complexity is intentionally constrained to prioritize transparency and communicability over predictive optimization.




## Project Status

**This project is currently ongoing.**

Planned next steps include:
- Additional validation across regions and stations  
- Exploration of compound weather effects  
- Refinement of risk communication and visualization  
- Assessment of generalization to other geographic contexts  

Code, notebooks, and supporting materials will be added incrementally as the project progresses.



## Repository Structure (Planned)
```text
├── notebooks/ # exploratory analysis and modeling notebooks
├── src/ # reusable processing and modeling utilities
├── figures/ # exported visualizations
├── README.md
```



## Disclaimer & Usage

This repository is shared for **portfolio demonstration and educational purposes only**.

The analysis logic, modeling decisions, and risk framing are **not intended for direct reuse in operational or production settings** without proper validation, attribution, and domain review.




## Author

**Paula Frossard**  
Data Scientist, focused on UX Research and Human Centred Data  
Portfolio: [datascienceportfol.io/paulafrossard](https://www.datascienceportfol.io/paulafrossard/projects/4)  
