# Exploring Music Evolution Over the Last Century

**Contents**
- [Abstract](#abstract)
- [Repository Structure](#repository-structure)
- [Reproducibility Capsule](#reproducibility-capsule)
- [Open Science](#open-science)
- [License](#license)

---

## Abstract

In response to the industrial and technological advancement of the past century, our society has become increasingly dependent on music, which is prevalent in most of the activities of our daily lives. With societal, cultural, and technological changes, musical culture is also expected to change, raising the main research question “How did music evolve over the last century?” To address the open challenge, we investigate quantifiable metrics and select four representative metrics, used to measure music: acousticness, energy, danceability, and duration. We conduct extensive data-wrangling processes; we conduct the data collection step and select a dataset from Kaggle (the world’s largest data science online community) synthesized from Spotify Web API; we conduct the data extraction and processing to bring data to a usable form, thus enhancing readability and usability; then, using the existent data, we create ratios in the data creation step; lastly, in the data analysis process, we investigate the obtained data, conduct relevant statistical analysis and visually depict data. Through the analysis process, we observe that: (i) the energy levels almost doubled throughout the time, while the acousticness dropped by 65%; (ii) energy-danceability ratio almost halved since 1921; (iii) surprisingly, despite cultural changes, the average song duration has remained relatively steady.

**Index Terms**—music, evolution analysis, energy, acousticness, danceability, duration

---

## Repository Structure

- **Presentation (video recording)**: [YouTube Link](https://youtu.be/3emi_OeNHUA)
- **Presentation (slides)**: `slides.pdf`
- **Report**: `Exploring music evolution over the last century.pdf`
- **Code**: `src/`


---

## Reproducibility Capsule

- **Dependencies**: Python 3.12, Pandas 2.2.2 (or newer).
- **Steps**:
  1. Clone this repository.
  2. Delete the folder `plots`, from `src/plots`
  3. Navigate to `src/data_wranggler.ipynb`
  4. Run the notebook entirely.

---

## Open Science

We provide this project as open-source. All datasets originate from [Kaggle](https://www.kaggle.com/) (Spotify Web API). See `src/` folder for our code and the data wrangling scripts.

---

## Authors
Radu Nicolae, Leonid Ivanov, Ayush Khadka, Alara Karadeniz

## Acknowledgements
This research was conducted as part of the course [Data Wrangling 2024-2025 (XB_0014)](https://studiegids.vu.nl/en/courses/2024-2025/XB_0014#/), Vrije Universiteit Amsterda; many thanks to the teaching team and everybody involved.

## License

This project is provided for academic and educational purposes. No additional license is declared.
