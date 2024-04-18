# Group-Project-2-4610

### Group members 
Gwen Wentworth 

[Caroline Cooper](https://github.com/carolinetcooper6/Group-Project-2/blob/main/README.md)

[Charlie]( https://github.com/charles8888/Project2 )

## Dataset Description:

The YTS was developed to provide states with comprehensive data on both middle school and high school students regarding tobacco use, exposure to environmental tobacco smoke, smoking cessation, school curriculum, minors' ability to purchase or otherwise obtain tobacco products, knowledge and attitudes about tobacco, and familiarity with pro-tobacco and anti-tobacco media messages. The YTS uses a two-stage cluster sample design to produce representative samples of students in middle schools (grades 6–8) and high schools (grades 9–12). The data for the STATE System were extracted from Youth Tobacco Surveys from participating states. Tobacco topics included are cigarette smoking prevalence, cigarette smoking frequency, smokeless tobacco products prevalence, and quit attempts.

## Dataset Content(s):
Each row within our dataset is a youth tobacco survey entry conducted according to the recorded year. The important columns we have focused on within this dataset are the year the YTS was conducted (YEAR), the state in which it was conducted(LocationDesc), the topic type being “tobacco usage” for all data entries(TopicType), the detailed description of that topic (TopicDesc), the source of our data (DataSource), the responses from the YTS (Response), the data value(Data_Value) and its data type (Data_Value_Type), which genders were focused per survey (Gender), what races were observed (Race), the age group(s) observed (Age), and the education level of the student(s) (Education).

## Two meaningful questions: 

1.  How does education level affect the levels at which survey respondents use tobacco over time?
  ![image](https://github.com/gaw63800/Group-Project-2-4610/assets/150155143/f68322fc-a75b-472d-a6a5-5f6149035670)

2.  How does the number of people/density of people who frequently smoke change over time by state?

### 1999 - 2005
![image](https://github.com/gaw63800/Group-Project-2-4610/assets/150155143/352deb9d-5c62-4e2d-9024-929fb5ca9593)

### 2006 - 2010 
![image](https://github.com/gaw63800/Group-Project-2-4610/assets/150155143/8478af4c-1c51-4fcf-8b72-9812de41a0c6)

### 2010 - 2017
![image](https://github.com/gaw63800/Group-Project-2-4610/assets/150155143/ad67adc5-2740-472e-9a92-40febcee4514)

##Manipulation(s) during analysis:

To accurately display the density of frequent smokers across the different periods, we had to change the color legends to be consistent with each other. The colors on the map accurately show the range of .13% - 10.83%. That way our map would show the same colors. 
Tableau also helped us generate the longitude and latitude for each state based on the name. This allowed us to accurately plot on the map. 

## Analysis & Results:

According to our histogram data analysis comparing the education levels and their responses, the most saturated section appears to be high schoolers responding with “Ever”, specifically during the late 1990s being the peak. The general trend across all six histograms is a constant decline as time goes on from 1999 to 2017. When it comes to the level of education, high schoolers seem to have a higher rate of tobacco usage than middle schoolers. In terms of the response, “Ever” appears to be the highest frequency of response type.

Based on the data analysis and results from our heat map, our team has concluded that tobacco usage among teenagers has overall been diminished across the United States as a whole. There are some outliers to the common pattern of decline in teenage tobacco usage, some of them being the states of Kentucky (KY), West Virginia(WV), and New Hampshire(NH). Looking solely at our data from 1999 to 2017, the states that appear to have little to no presence of teenage tobacco usage are California (CA), Utah (UT), Idaho (ID), Wyoming (WY), Colorado (CO), New Mexico (NM), Texas (TX), Iowa (IA), Virginia (VA), New York (NY), Maryland (MD), Vermont (VT), Massachusetts (MA), Rhode Island (RI), and Maine (ME).

