# EasyVisa
USA Visa application approval process for job certification (Machine Learning - Ensemble Techniques).
Business communities in the United States are facing high demand for human resources, but one of the constant challenges is identifying and attracting the right talent, which is perhaps the most important element in remaining competitive. Companies in the United States look for hard-working, talented, and qualified individuals both locally as well as abroad.
The Immigration and Nationality Act (INA) of the US permits foreign workers to come to the United States to work on either a temporary or permanent basis. The act also protects US workers against adverse impacts on their wages or working conditions by ensuring US employers' compliance with statutory requirements when they hire foreign workers to fill workforce shortages. The immigration programs are administered by the Office of Foreign Labor Certification (OFLC).
OFLC processes job certification applications for employers seeking to bring foreign workers into the United States and grants certifications in those cases where employers can demonstrate that there are not sufficient US workers available to perform the work at wages that meet or exceed the wage paid for the occupation in the area of intended employment.

Objective:
In FY 2016, the OFLC processed 775,979 employer applications for 1,699,957 positions for temporary and permanent labor certifications. This was a nine percent increase in the overall number of processed applications from the previous year. The process of reviewing every case is becoming a tedious task as the number of applicants is increasing every year.

The increasing number of applicants every year calls for a Machine Learning based solution that can help in shortlisting the candidates having higher chances of VISA approval. OFLC has hired the firm EasyVisa for data-driven solutions. You as a data scientist at EasyVisa have to analyze the data provided and, with the help of a classification model:

Facilitate the process of visa approvals.
Recommend a suitable profile for the applicants for whom the visa should be certified or denied based on the drivers that significantly influence the case status.
Data Description
The data contains the different attributes of employee and the employer. The detailed data dictionary is given below.

Recommendations

The profile of the applicants for whom the visa status can be approved:

Primary information to look at:

Education level - At least has a Bachelor's degree - Master's and doctorate are preferred.
Job Experience - Should have some job experience.
Prevailing wage - The median prevailing wage of the employees for whom the visa got certified is around 72k.
Secondary information to look at:

Unit of Wage - Applicants having a yearly unit of wage.
Continent - Ideally the nationality and ethnicity of an applicant shouldn't matter to work in a country but previously it has been observed that applicants from Europe, Africa, and Asia have higher chances of visa certification.
Region of employment - Our analysis suggests that the applications to work in the Mid-West region have more chances of visa approval. The approvals can also be made based on requirement of talent, from our analysis we see that:
The requirement for the applicants who have passed high school is most in the South region, followed by Northeast region.
The requirement for Bachelor's is mostly in South region, followed by West region.
The requirement for Master's is most in Northeast region, followed by South region.
The requirement for Doctorate's is mostly in West region, followed by Northeast region.
The profile of the applicants for whom the visa status can be denied:

Primary information to look at:

Education level - Doesn't have any degree and has completed high school.
Job Experience - Doesn't have any job experience.
Prevailing wage - The median prevailing wage of the employees for whom the visa got certified is around 65k.
Secondary information to look at:

Unit of Wage - Applicants having an hourly unit of wage.
Continent - Ideally the nationality and ethnicity of an applicant shouldn't matter to work in a country but previously it has been observed that applicants from South America, North America, and Oceania have higher chances of visa applications getting denied.
Additional information of employers and employees can be collected to gain better insights. Information such as:
Employers: Information about the wage they are offering to the applicant, Sector in which company operates in, etc
Employee's: Specialization in their educational degree, Number of years of experience, etc
