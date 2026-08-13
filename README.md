# ondedoi-lede
[Lede Project 3] Analysis of Sexual Assault by Medical Providers in Brazil - FINAL PROJECT

OVERVIEW
The data used in this project was collected in late 2019 and early 2020 via three Google surveys, created as part of the online awareness campaign "Onde Dói" (Where it Hurts, in direct translation from Brazilian Portuguese). The three datasets were downloaded as .csv files from Google. The first dataset was not included in this analysis. The second and third datasets, totaling 189 responses, were used for the purposes of finding trends pertaining to sexual assault crimes committed by healthcare providers against patients in Brazil.

DATA ANALYSIS
I combined the second and third datasets into one and used pandas in VSCode to clean the data. The goal was to identify which types of sexual crimes are more pervasive among healthcare providers, which medical specialties are behind the majority of cases, and where these crimes usually occur (public or private premises). I also calculated the race breakdown for victims, their age range and economic status to understand if certain groups were more targeted by perpetrators. However, I didn't identify any correlation marked by demographic profile. 

DATA VISUALIZATION
For the data visualization part of the project, I used Flourish to create three visuals:

A bar chart of the types of sexual assault usually committed by a healthcare practitioner, and the number of victims for each;

A bar chart showing the number of cases per medical specialty;

A treemap showing the most frequent locations in which reported crimes took place: private clinics, public hospitals, private hospitals or free clinics.

CSV FILES
Compiled datasets supressing sensitive information shared by respondents: https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/ondedoi_responses_public%20-%20combined.csv

https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/abuse_by_age_group.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/abuse_by_specialty.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/all_by_location.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/all_by_location_percentages.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/econ_status_victims_vs_location.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/econ_status_victims_vs_specialty.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/offenses_by_specialty_and_location.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/specialty_by_age_group.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/specialty_counts.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/specialty_percentages.csv
https://github.com/isanvmarinho-spec/ondedoi-lede/blob/main/victim_race.csv

WEBPAGE
https://isanvmarinho-spec.github.io/ondedoi-lede/

FINDINGS
The data shows that the majority of victims were female (96 percent), and the majority of perpetrators were male (91 percent). Regardless of economic status, age group or race, sexual assault by fraud or deception was the main type of abuse reported (71 percent), followed by verbal sexual harassment (35 percent). The top specialties behind most of the sexual assault cases are gynecologists and OBGYNs (37.5 percent), followed by primary care (14 percent), pediatrics and cardiology (5 percent each). Six out of ten times, the offense will take place in a private doctor's office - regardless of their specialty, the victim's age, race or economic status.

SKILLS LEARNED
I was able to practice with pandas and brush up on my Flourish and Canvas skills.
