
---

# Speed Dating EDA (Exploratory Data Analysis) Project

## Project Objective

Speed dating is a captivating process that allows individuals to meet numerous potential matches in a short span of time. This analysis seeks to grasp the various factors influencing successful matches and to delve into the dynamics and individual preferences within the speed dating experience. The marketing team of a dating app seeks guidance for a new venture. They've observed a decline in match numbers and are endeavoring to discern what draws people to one another.


## Methodology

To analyze the data, we will employ a range of statistical techniques. This may encompass descriptive analysis, correlation analysis, and the like. We will also leverage visualization techniques to depict our findings.
The dataset contains some missing values. For instance, the 'positin1' column has 1,846 missing values, 'undergra' has 3,464 missing values, 'mn_sat' has 5,245 missing values, and 'tuition' has 4,795 missing values. It's likely that this dataset demands some preprocessing to handle these missing values before it can be utilized for data analysis or machine learning. Addressing these missing values might involve strategies such as imputation, discarding the missing values, or utilizing algorithms capable of managing missing values.

## Installation Instructions

The project is executed using Python and requires the installation of the following packages :

- pandas
- numpy
- matplotlib
- seaborn

These packages can be installed using pip :

```
pip install pandas numpy matplotlib seaborn
```

## How to Use the Dataset

The dataset is a CSV file named 'DS_speed_dating.csv'. It can be loaded in Python using the pandas library :

```python
import pandas as pd

data = pd.read_csv('chemin_vers_le_fichier/DS_speed_dating.csv', encoding='ISO-8859-1')
```

## Results and Conclusions

   - **Key Findings :**

   This analysis unveiled several intriguing insights about the factors influencing match decisions during speed dating events. Attractiveness seems to play a pivotal role, while ambition is less valued. The field of study greatly influences the match decision, contrary to belonging to the same ethnic group. Participants tend to misjudge their attractiveness and their perceived market value in the dating scene. Lastly, post-match communication appears to play a key role in securing a second date outside of the event.
   
   
   - **Recommandations** Based on the findings of our analysis, we can put forth the following recommendations :

**Target a Broader Audience** : Our study indicated that age, age difference, and even race had no influence on matching decisions. Hence, it would be beneficial to target a wider demographic to enhance the likelihood of matches. Efforts should be made to attract a greater number of singles to use the app.

**Highlight Attractiveness** : Attractiveness emerged as a key characteristic in match decisions, regardless of age or gender. Consider incorporating features that accentuate user attractiveness, such as a robust profile picture system, filters, or even preset camera settings in the app.

**Promote Shared Interests** : Common interests played a role in match decisions. Users could be encouraged to share their hobbies and search for individuals with similar pursuits. A "Interests" section could be added to profiles, which is visible to other users and could even be integrated into the profile matching algorithm.

**Encourage Post-Match Communicationh** : Participants who communicated post-event were more likely to secure a second date. The app could motivate users to continue interactions after a match, perhaps by suggesting conversation starters or offering rewards for consistent engagement.

**Provide Tailored Advice** : Participants' self-perceived scores often diverged from their actual perceived values. The app could offer bespoke advice to users on how to bolster their match prospects, such as by illustrating how their preferences compare with those of others.

**Conclusion**

We managed to explore various avenues and unearthed several insights that can be instrumental for our Marketing team. This will enable them to boost the number of user matches, thereby fostering longer-term, loyal engagement.
These insights offer valuable perspectives on the dating preferences and behaviors of participants at these speed dating events. Nevertheless, it's crucial to underscore that these findings pertain specifically to this dataset and may not universally apply to other contexts or populations.
Further, in-depth analysis using variables not considered in this study might yield new, intriguing insights.

## License and Citation

The speed dating data was collected from participants of experimental speed dating events. The events were orchestrated by Columbia Business School professors, Ray Fisman and Sheena Iyengar, for their paper "Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment". The dataset is publicly available for use in research and education.
This dataset is freely accessible for non-commercial use on Kaggle.com.
The dataset can serve a myriad of purposes in the realms of social sciences, psychology, and machine learning. For instance, it can be employed to study factors influencing attraction and decision-making in dating, to examine racial preferences in dating, or to construct predictive models for partner matching. The vast array of variables within the dataset allows for the exploration of numerous research questions and potential hypotheses.

## Contributions

Contributions to this project are warmly welcomed. If you're keen on contributing, please initiate by opening an issue to discuss what you'd like to modify.

## Contact

Should you have any queries or feedback regarding this project, please reach out to me at :

*abajolah@gmail.com*

---
