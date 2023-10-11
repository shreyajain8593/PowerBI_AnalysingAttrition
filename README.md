# Analysing Factors Contributing to Employee Attrition at a Fictitious Company
## Interpretation Report
### Introduction

*   A beginner in Power BI, this is the first independent project that I’ve completed using a data set downloaded online.
*   The dataset is from the HR domain, and the key objective of this project is to understand the relationship between employee turnover/attrition and various factors related to employees, job-related aspects, and their psychological condition at work.
*   The project involves end-to-end data analysis, including data cleaning, data transformation, analysis, and visualisation.
*   While there were numerous ways through which data was analysed during the exploratory data analysis stage, I’ve presented only the key insights through the Power BI report.
*   This document entails an interpretation of the results of this analysis and will walk you through the entire project journey.
*   I sincerely welcome all constructive feedback, and invite you to share your thoughts on the analysis.

### Data Description:

*   Data downloaded from GitHub
*   Dataset link: https://github.com/Krishnkumar542/INX-Future-Inc-Employee-Performance-Analysis-using-Power-BI/blob/main/INX_Future_Inc_Employee_Performance_Data.xls
*   Data description: The dataset was downloaded from GitHub and comprises information on 1200 employees of a fictitious company called 'INX Future Incorporation.' Each employee's entry corresponds to one row, with various data points provided for each employee. To give more structure to my thought process and streamline the analysis, I categorized the variables into three key groups:
*   Employee Attributes: These variables encompass a range of employee characteristics, including age, Gender, Education Background, Employee Education Level, marital status, and total work experience.
*   Job and Work-related Factors: This group of data points sheds light on the context and conditions in which employees operate. It covers variables such as job role, job level, department, business travel frequency, distance from home, hourly rate, last salary hike percent, years since last promotion, experience years at this company, experience in the current role, years with the current manager, training times provided last year, overtime, and performance.
*   Psychological Satisfaction: This set of variables offers insights into employees' mental states and their satisfaction with their experience at INX. It includes job involvement, job satisfaction, relationship satisfaction, environment satisfaction, and work-life balance.
*   Additionally, the dataset indicates each employee's attrition status, indicating whether they are currently active at INX or have departed

### Objective:

*   The primary question answered through this project is: “What are the factors that contribute to attrition at INX Future Inc.?

### Dashboard Overview & Analysis Sections:

The Power BI report for this project consists of five pages, each exploring the analysis from different perspectives:

*   Employee Dashboard: This page presents essential employee information and the distribution of employees throughout the organization based on various attributes.
*   Attrition Analysis by Employee Attributes: This section delves into how attrition correlates with various employee-related characteristics or attributes.
*   Attrition Analysis by Job-Related Factors: This page explores how attrition relates to various job-related conditions.
*   Attrition Analysis by Work and Compensation Factors: Here, we examine how attrition varies with different job-related conditions.
*   Attrition Analysis by Satisfaction Levels: The final page scrutinizes how attrition is influenced by different levels of satisfaction in key areas. These 4 variables have been measured on a 4 point likert scale from 1 to 4, i.e. from low to very high. I have analysed how attrition rate is different across these categories for each of these variables.

### Analysis Results & Key Insights:

1.  Attrition Analysis by Employee Attributes
    1.  We begin to answer the primary question of this project with this page.
    2.  Objective: To demonstrate how attrition varies with various employee-related characteristics or attributes.
    3.  Key Findings:
        1.  The findings reveal that the rate of attrition decreases as the education level increases. Those with a doctorate degree have the lowest rate of attrition, while those without any higher education qualification have the highest. There needs to be a further probe to determine what factors influence individuals across different education levels that in turn impact the turnover rate.
        2.  Given that the dataset lacks precise dates of birth for employees and provides only their ages, I’ve assumed that these ages are current as of October 2023, the time of this analysis. Consequently, for the purposes of our analysis, we have categorized employees into four generational groups: Generation Z (18-26), Millennials (27-42), Generation X (43-58), and Boomers (59-60). This categorization allows us to explore whether attrition rates vary across different age groups and generations. The analysis reveals that the highest attrition rate, reaching 35%, is observed among the youngest workforce, Generation Z. In contrast, there is no recorded attrition among Boomers. However, it is important to note that Boomers comprise only 0.75% of the total workforce. Therefore, it may be challenging to draw definitive conclusions from this observation.
        3.  It was found that males experienced a slightly higher attrition rate of 16% compared to 13% among females. Males also contributed to about 60% of the organisation’s total turnover. Interestingly, in the human resources department, a higher attrition rate is noted amongst female employees than males - 43% and 14% respectively.
        4.  For both males and females, a higher attrition rate is noted amongst single employees. While further investigation would be required to determine the reasons behind this trend, a possible reason could be that single employees may be more open to exploring new career opportunities and taking risks. They might be less tied down by family responsibilities and more inclined to seek better job offers or career advancements elsewhere.
    4.  Recommendations:
        1.  INX could potentially gain valuable insights by conducting an organization-wide survey to gather additional data regarding the significant factors that matter to employees across various age groups. Such a survey could shed light on the factors that influence their choices when deciding whether to remain with the organization or explore other opportunities. The objective should extend beyond conducting exit interviews and include the implementation of "stay" interviews as well. These stay interviews are essential for identifying the factors that contribute to employee retention and understanding what motivates them to remain with the organization.
        2.  Since the younger, single workforce exhibits the highest attrition rates, it is plausible that this group is more inclined towards career mobility and the flexibility to explore different career paths. To enhance the retention of employees in this demographic, the organization can focus on offering improved career growth opportunities. This involves fostering an environment where employees can engage in open and candid discussions with their managers regarding their career aspirations. Additionally, providing transparent insights to employees about internal career prospects that align with their goals can be a valuable strategy. This approach provides employees with the opportunity to grow within the organization, reducing the inclination to seek external opportunities.
2.  Attrition Analysis by Job-Related Factors
    1.  Objective: To demonstrate how attrition varies with various job-related conditions.
    2.  Key insights:
        1.  The highest attrition rate is seen in the sales department, which is due to the reason that it has the role with the highest attrition rate, i.e. sales representatives with a 35% attrition rate. Moreover, all sales representatives are the 1st job level, which itself is a category with the highest attrition rate of 25%
        2.  A noticeable trend is that with an increase in job level, there is a decline in the attrition rate. This is similar to the pattern exhibited by education levels.
        3.  A key crucial insight is that at the highest job level - i.e. the 5th job level that is espoused by managerial roles, attrition is observed only amongst females. While overall there is relatively less turnover at this level, it is concerning that it’s only the women managers quitting their jobs.
        4.  A prominent difference in the time spent with the manager is observed between active and departed employees. Across all departments, employees who left the organisation spent considerably less number of years with their manager than active employees. This indicates that managers have a crucial role in determining their team members’ retention.
        5.  It seems there is a consistent pattern of difference in the tenure and work experience at INX between active and departed employees. Across all age groups, departed employees had lesser working experience and a relatively smaller tenure at INX, indicating that even within the same age group, those with a lesser number of years behind them had a higher tendency to exit the organisation. This is consistent with the previous observation that with increasing age, the likelihood of exit also increases.
    3.  Recommendations:
        1.  There is a need to delve deeper into the underlying causes behind the elevated turnover rates observed at the entry-level positions within the organization. Further analysis has indicated that one potential contributing factor may be the higher likelihood of overtime work among employees at these lower job levels compared to their counterparts in higher positions. If this pattern of increased overtime is consistently prevalent throughout the organization, it becomes imperative to implement improved resource management strategies aimed at reducing overtime hours within this specific employee cohort or provide fair compensation to employees for working overtime.
        2.  Further probe should be done to identify what is driving attrition among female managers, and whether there are any unique challenges faced or experienced by this group of individuals. One avenue of inquiry could revolve around identifying any unique leadership challenges that female managers face in their roles. These may encompass conflicting personal and professional commitments or instances of bias, such as gender-based stereotypes.
        3.  Finally, employees with less experience might be more eager to advance their careers quickly, explaining their increased tendency to exit the organization. If they perceive limited growth opportunities within INX, they may be more inclined to explore external options. This is consistent with the earlier recommendation to provide employees with internal career movement opportunities.
3.  Attrition Analysis by Work and Compensation Factors
    1.  Objective: To demonstrate how attrition varies with various job-related conditions.
    2.  Key insights:
        1.  It seems that travel demands on employees play a key role in their decision to exit the organisation. With the increase in distance from home, there's a noticeable increase in attrition rates. In fact, the average distance from home for active employees is 8.95, compared with 10.40 for departed employees. The highest attrition rate is also observed amongst those who are required to travel frequently for business.
        2.  As one would expect, employees who report working overtime are more likely to quit: the attrition rate is 27.2% for those working overtime vs 9.68% amongst those who do not report working overtime. In fact, this pattern is observable across all levels of work-life balance. Even those employees who report the best work-life balance are more likely to quit because they work overtime.
        3.  Even though the levels of working overtime do not vary a lot across age groups, Gen Z seems to be the most affected by overtime conditions. About 60% of the workforce aged below 26 (Gen Z) that reported overtime decided to quit the organisation, in stark contrast to 26% among millennials and only 15% among Gen X. Working overtime seems to be a key reason behind attrition of Gen Z employees. Amongst those who do not report working overtime, the attrition rate remains lower than 25% across all age groups.
        4.  Finally, a key finding from this page is that even on receiving the same salary hike, those from the lower age groups quit the organisation. This means that there may be other factors influencing the younger workforce to leave the organisation that outweigh compensation factors. For instance, earlier noted that overtime was one such key factor influencing the younger age groups.
    3.  Recommendations:
        1.  One of the ways to improve retention of talent is providing specific benefits to relief to employees who travel to the office from distant locations. For instance, implementing hybrid work arrangements or flexible hours can significantly mitigate the stress associated with long commutes. In fact, these benefits can be provided to all employees, wherever possible, to improve their work experience.
        2.  When it comes to addressing the issue of overtime, it is evident that urgent action is required as it significantly contributes to the company's attrition levels. Immediate steps should be taken to alleviate the burden on employees. For instance, identifying the root causes of overtime is crucial. Are there specific managers who consistently require their employees to work overtime? Is there a shortage of resources or inadequate skills in managing workloads effectively? Interventions can then be designed based on these findings. For instance, closely monitoring and tracking employees' overtime hours and implementing a system that enables employees to report excessive hours can be valuable steps in this regard. Additionally, measures can be taken to provide relief to employees facing excessive overtime demands, such as workload redistribution, improved resource allocation, or targeted training programs for managers to better manage workloads and avoid unnecessary overtime.
4.  Attrition Analysis by Satisfaction Levels
    1.  Objective: To demonstrate how attrition varies with various satisfaction levels.
    2.  Key Findings:
        1.  Across all 4 variables, i.e. environment satisfaction, relationship satisfaction, job satisfaction, and job involvement, those with lower levels of satisfaction are more likely to leave.
        2.  This effect is most notable for job involvement, wherein more than 30% of employees with low job involvement decided to exit the company.
    3.  Recommendations:
        1.  Given that low job involvement has a significant impact on attrition, the company should focus on strategies to enhance employees' engagement with their roles. This can include providing opportunities for skill development, clear career progression pathways, and regular feedback and recognition.

### Conclusion:

In conclusion, the analysis of employee attrition within INX Future Incorporation has illuminated critical insights into the multifaceted factors influencing workforce retention. We've observed the significance of education levels, generational dynamics, gender, marital status, job levels, overtime, and satisfaction in shaping attrition patterns. These findings underscore the need for tailored retention strategies that encompass career growth opportunities, support for entry-level employees, and measures to mitigate overtime demands. By addressing these factors, INX can proactively work towards nurturing a satisfied and engaged workforce, fostering long-term commitment, and ultimately reducing attrition.
