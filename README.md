# ai-fairness-ensea
Projet de recherche master 2 DSML

The ProPublica data includes data collected about the use of the COMPAS risk assessment tool in Broward County, [Julia Angwin, Je Larson, Surya Mattu, and Lauren Kirchner. 2016. Machine Bias. https://www.propublica.org/article/]. It includes information such as the number of juvenile felonies and the charge degree of the current arrest for 6,167 individuals, along with sensitive attributes race and sex. Data is preprocessed according to the filters given in the original analysis Angwin et al. (2016). Each individual has a binary “recidivism" outcome, that is the prediction task, indicating whether they were rearrested within two years after the first arrest (the charge described in the data).

Les données de ProPublica comprennent des données recueillies sur l'utilisation de l'outil d'évaluation des risques COMPAS dans le comté de Broward, [Julia Angwin, Je Larson, Surya Mattu et Lauren Kirchner. 2016. Machine Bias. https://www.propublica.org/article/]. Il comprend des informations telles que le nombre de délits mineurs et le degré d'accusation de l'arrestation actuelle pour 6 167 individus, ainsi que des attributs sensibles race et sexe. Les données sont prétraitées selon les filtres donnés dans l'analyse originale Angwin et al. (2016). Chaque individu a un résultat binaire de "récidive", c'est-à-dire la tâche de prédiction, indiquant s'il a été réarrêté dans les deux ans suivant la première arrestation (l'accusation décrite dans les données).


## Instructions du projet
1. Form a group of 2.

2. Choose a subject.

3. Send an email to Dimitris <Dimitrios.Kotzinos@cyu.fr> with your group and your choice and wait for verification/approval.

4. Download the data set and read the corresponding paper(s)

5. Connect/Use the platform.

6. Draw results on fairness / bias.

7. Prepare your presentation.

## Liste des liens
### Evaluating Machine Learning Models Fairness and Bias :
https://towardsdatascience.com/evaluating-machine-learning-models-fairness-and-bias-4ec82512f7c3

### Model Fairness & Transparency :
https://medium.com/sfu-cspmp/model-transparency-fairness-552a747b444

### ProPublica recidivism Use Case :
https://github.com/propublica/compas-analysis

### COMPAS Recidivism Risk Score Data and Analysis :
https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis
* Machine Bias : https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
* How We Analyzed the COMPAS Recidivism Algorithm : https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm

### Introducing AI Fairness 360 :
https://www.ibm.com/blogs/research/2018/09/ai-fairness-360/

### Guide Fairness
http://aif360.mybluemix.net/resources#guidance

### AI Fairness 360 :
http://aif360.mybluemix.net/?_ga=2.230230748.1501284757.1641897658-1838616834.1641897658

### AI Fairness 360: An Extensible Toolkit for Detecting, Understanding, and Mitigating Unwanted Algorithmic Bias :
https://arxiv.org/abs/1810.01943

## Lecture
Liste des documents lus dans le cadre du projet
* nom de l'article
* notes : rapport

## Code
...

## Programme 1 (Mardi)
* https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing (OUM)
* https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm (OUM)
* https://arxiv.org/pdf/1810.01943.pdf (ALEX)

## Métriques

    Optimized Preprocessing (Calmon et al., 2017)
    Disparate Impact Remover (Feldman et al., 2015)
    Equalized Odds Postprocessing (Hardt et al., 2016)
    Reweighing (Kamiran and Calders, 2012)
    Reject Option Classification (Kamiran et al., 2012)
    Prejudice Remover Regularizer (Kamishima et al., 2012)
    Calibrated Equalized Odds Postprocessing (Pleiss et al., 2017)
    Learning Fair Representations (Zemel et al., 2013)
    Adversarial Debiasing (Zhang et al., 2018)
    Meta-Algorithm for Fair Classification (Celis et al.. 2018)
    Rich Subgroup Fairness (Kearns, Neel, Roth, Wu, 2018)
    Exponentiated Gradient Reduction (Agarwal et al., 2018)
    Grid Search Reduction (Agarwal et al., 2018, Agarwal et al., 2019)
    Fair Data Adaptation (Plečko and Meinshausen, 2020, Plečko et. al., 2021)

