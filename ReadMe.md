 
# README.md for "Onidra: A Clinically Annotated Survey Dataset for Insomnia and Anxiety Assessment Based on ISI and HAM-A"

Version 1 and Version 2 of this dataset is already available in mendeley. Version 2 has data from 30 June 2022 and 21 October 2024 . And this version has data 30 June 2022 and 7 January 2025 with some additional data. 

https://data.mendeley.com/datasets/sg2whyws4h/2

The contributors of this dataset are: 
Afsana Begum,Zahereel Ishwar Abdul Khalib,Imran Mahmud,Bibhas Roy Chowdhury Piyas, K.M. Mohiuddin, Meher Durdana Khan, Bilkis Khanam, Farhana Kabir Dina, Farzana Akter Laboni,Sajia Iffat, Shahrin Islam,Shazzad Hossen, Fatama Jannat Tisha

This version is mainly upload here to upload a data analysis on this code.


## Dataset Description

Onidra is a clinically annotated large-scale survey dataset designed for the joint assessment of insomnia and anxiety disorders using the internationally recognized Insomnia 
Severity Index (ISI) and Hamilton Anxiety Rating Scale (HAM-A). The dataset contains responses from 10,008 participants collected across all eight administrative divisions 
of Bangladesh between June 2022 and October 2024.The dataset was collected through approximately 23 online and offline healthcare-linked sessions and mental health awareness 
events in collaboration with Aachol Foundation and Daffodil International University. Participants completed structured questionnaires before consultation with psychologists 
or physicians, and final clinical labels were assigned by expert clinicians using ISI scores, HAM-A scores along with behavioral and lifestyle indicators.

---

## Value of the Dataset

-First large-scale clinically annotated dataset integrating ISI and HAM-A for joint insomnia and anxiety assessment.
-Supports development of explainable and data-driven machine learning models for mental health prediction.
-Enables research in psychology, psychiatry, public health, behavioral science, and artificial intelligence.
-Useful for early-stage detection and severity classification of insomnia and anxiety disorders.
-Supports behavioral analytics and socio-demographic risk factor analysis.
-Provides clinically validated labels assigned by expert medical professionals.
-Covers participants from all eight divisions of Bangladesh, making it valuable for regional and population-level mental health studies.
-Can support digital healthcare systems and intelligent mental health screening applications.
---

## Methods

### Data Collection
- **Method Used**:Structured questionnaire-based survey.
- **Procedure**: Data were collected through approximately 23 online and offline healthcare-linked sessions, counseling programs, and mental health awareness events.
                 Participants completed the questionnaire before consultation with psychologists or physicians. Responses were later clinically validated by expert 
                 clinicians using psychometric scores and behavioral indicators.
- **Participants**: 10,008 participants from different regions of Bangladesh.
- **Data Collection Period**: June 2022 – October 2024.
- **Data Collectors**:27 trained enumerators in collaboration with Aachol Foundation and Daffodil International University, Bangladesh.
- **Clinical Validation**:Final insomnia and anxiety labels were assigned by three experienced clinicians based on ISI scores, HAM-A scores, behavioral patterns and lifestyle indicators.

---

## Data Format

The dataset is in an **Excel** file format (.xlsx).

---


### Column Descriptions:

Column Name               Description                                              Data Type   Example Values
---------------------------------------------------------------------------------------------------------------
Gender                    Gender of the participant                                Text        Male
Age                       Age group of the participant                             Text        >28
LivingStatus              Living arrangement (with/without family)                 Text        with family
Occupation                Employment or social status                              Text        job holder
EducationalYear           Academic year or level of study                          Text        graduate
MaritalStatus             Current marital status                                   Text        Married
SmokingHabit              Tobacco smoking habit                                    Text        yes
Alcohol                   Alcohol consumption habit                                Text        no
Place_of_Education        Location of study (Rural/Urban)                          Text        rural
UniversityType            Type of university (Public/Private)                      Text        public
SleepTime                 Typical bedtime                                          Text        after 1
Asthma                    History of asthma                                        Text        yes
Hypertension              History of hypertension                                  Text        yes
HeartDisease              History of heart disease                                 Text        yes
CardiovascularDisease     History of cardiovascular disease                        Text        no
Cancer                    History of cancer                                        Text        no
Diabetes                  History of diabetes                                      Text        yes

ISI1                      Difficulty falling asleep at night                       Integer     1
ISI2                      Difficulty staying asleep during the night               Integer     3
ISI3                      Waking up too early in the morning                       Integer     4
ISI4                      Satisfaction with current sleep pattern                  Integer     4
ISI5                      Impact of sleep problems on quality of life              Integer     4
ISI6                      Degree of worry or distress about sleep                  Integer     4
ISI7                      Daytime impairment due to sleep difficulties             Integer     4
ISI_Total_Score           Total Insomnia Severity Index score                      Integer     24
Insomnia_Category         Clinical category of insomnia severity                   Text        severe_Insomnia

HAM1                      Anxious mood and excessive worry                         Integer     3
HAM2                      Tension and restlessness symptoms                        Integer     2
HAM3                      Specific or generalized fears                            Integer     4
HAM4                      Sleep disturbance due to anxiety                         Integer     4
HAM5                      Cognitive difficulties (concentration and memory)        Integer     2
HAM6                      Depressed or low mood symptoms                           Integer     0
HAM7                      Muscular somatic symptoms                                Integer     2
HAM8                      Sensory somatic symptoms                                 Integer     2
HAM9                      Cardiovascular anxiety symptoms                          Integer     3
HAM10                     Respiratory anxiety symptoms                             Integer     4
HAM11                     Gastrointestinal disturbances                            Integer     2
HAM12                     Genitourinary symptoms                                   Integer     0
HAM13                     Autonomic nervous system symptoms                        Integer     4
HAM14                     Observable anxiety behavior during interview             Integer     2
HAM_Total_Score           Total Hamilton Anxiety Rating Scale score                Integer     34
Anxiety_Category          Clinical category of anxiety severity                    Text        Severe_very severe

AD1                       Duration of sleep difficulties                           Text        2–4 weeks
AD2                       Perceived causes of sleep problems                       Text        Health issues
AD3                       Impact on daily activities                               Text        Moderately
AD4                       Frequency of sleep disturbances                          Text        Rarely
AD5                       Coping strategies for insomnia                           Text        Get out of bed and do something relaxing
AD6                       History of clinical diagnosis                            Text        Anxiety disorder
AD7                       Recent major life events                                 Text        Yes, related to relationships
AD8                       Use electronic devices before bed                        Integer     1
AD9                       Consume caffeine or alcohol close to bedtime             Integer     2
AD10                      Exercise vigorously in the evening                       Integer     5
AD11                      Nap during the day                                       Integer     5
AD12                      Follow a regular sleep schedule                          Integer     4
AD13                      Self-perceived sleep severity                            Text        Mild

Doctor_Opinion_Insomnia   Doctor’s assessment of insomnia                          Text        severe_Insomnia
Doctor_Opinion_Anxiety    Doctor’s assessment of anxiety                           Text        Severe_very severe

---


## File and Folder Structure
  
  - **README.txt**: This file containing general description of the dataset.   
  - **Onidra.xlsx**: File containing the developed dataset. 
  - **MoU with Aachol Foundation.pdf**: File containing the Memorandum of Understanding between Aachol Foundation and Daffodil International University for research collaboration.
  - **Informed Consent Form for Participants.pdf**: File containing the consent statement provided to participants before data collection.
  - **Ethical Approval Statement.pdf**: File containing the ethical approval statement for conducting the study.
  - **Complete Survey Questionnaire.xlsx**: File containing the complete survey questionnaire used for collecting participant responses.
  - **Codebook.py**: File containing the source code file for data analysis, variable processing and dataset preparation.


---

## Usage of Dataset

The dataset is useful for researchers, clinicians, psychologists, public health analysts, and AI practitioners working in the fields of mental health and behavioral analytics. 
It can be used for developing predictive models for insomnia and anxiety detection, severity classification systems, explainable AI applications, behavioral pattern analysis, 
and population-level mental health studies. The clinically annotated labels also make the dataset suitable for supervised machine learning research and intelligent healthcare applications.
---


## Acknowledgements
We express our sincere gratitude to all co-authors and collaborators whose contributions were essential to the successful completion of this research. We also gratefully acknowledge 
the support of Aachol Foundation and Daffodil International University for facilitating the data collection process. Finally, we thank all participants who voluntarily contributed their 
responses to this study.


---

## Contact Information

For any inquiries regarding this dataset, please contact:
  ** Afsana Begum ** or **Bibhas Roy Chowdhury Piyas** 
  Email: [ afsana.swe@diu.edu.bd or piyas.swe@diu.edu.bd ]  
  Affiliation: [Department of Software Engineering, Daffodil International University, Daffodil Smart City, Ashulia, 1341, Dhaka, Bangladesh]



