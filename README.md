# exploratory-analysis-of-A-and-E-data
This exploratory analysis is based on a synthetic AandE dataset where there is no concern surrounding patient privacy and confidentiality.

# What was the purpose of the analysis?
The purpose of the exploratory analysis was to give a brief insight into the data, answering questions such as the missingness of the data, and using available entries for use in an equation.

One of the questions this analysis set out to answer was whether heart rate, or temperature, had a correlation with mortality. When a patient suffers from a heart condition such as a myocardial infarction (MI), the cardiac muscle dies; resulting in a significantly decreased amount of force produced by the left ventricle to propel the blood towards critical organs. This causes a reduction in the cardiac output (CO), and the reduced blood flow results in insufficient oxygen being delivered to these organ systems, and results in a hypoxic state. THe body is excellent at adapting. The overall aim is to increase the cardiac output. Cardiac output is the product of the heart rate and stroke volume (CO = HR x SV). Stroke volume cannot be readily increased due to regions of the cardiac muscle being dead. As a result, the body compensates by increasing the heart rate. The dead cardiac muscle forms scar tissue which impacts the conduction system of the heart, risking the formation of re-entry currents (also known as circus currents) which facilitate arrhythmia. Therefore, with the increased heart rate there is an increased risk of arrhythmia, and might increase the moratlity of the patients. This analysis attempts at elucidating whether this correlation exists.

# Results of the analysis

#[](https://github.com/Ilja-Lom/exploratory-analysis-of-A-and-E-data/blob/main/images/HR%20Vs%20Mortality.png)

This analysis found no correlation between heart rate and mortality. A potential reason for this is the small sample size, particularly of patients who have passed away. Additionally, the dataset does not include any records of the reason behind the patient's admission to the hospital; if they were admitted for cardiac related reasons, this correlation might be uncovered, as currently, their mortality might be as a result of a different cause other than cardiac related.

# What have I learnt?
This project gave me more experience into processing the data before it can be used. Many of the tasks, such as plotting the Mean Arterial Pressure (MAP), contained several steps for completion. Overall, this project gave me more confidence in manipulating and processing the data.

# Challenges
One of the challenges that I have come across was attempting to plot all 1000 plots into a single image using subplots. When I attempted to do so, the plots would overlap each other. To overcome this, I could use the 'tight' plotting configuration which automatically assigns the plots a position.





