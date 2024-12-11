# Course Name : Information Visualization
# Project 2 - Visualization analysis and improvement
# Date : 2024-12-13
# Team 20

## Team members
- **Shuo Liu 320220940481**
- **Yanxi Meng 320220940591**
- **Yuxuan Lv 320220940561**
- **Sicheng Tu 320210941231**

## 1. Map Selection

The graph charts the percentage of female researchers who published papers in various scientific fields, including health sciences, engineering, physics, computer science, and mathematics, between 2011 and 2015. The figure includes data for 11 countries or regions, and the height of the columns represents the proportion of female researchers in each region. It reveals that between 2011 and 2015, the percentage of published papers by female researchers in these scientific fields is relatively low, and there are significant regional differences.

<img src="./original_picture.png" width="250" height="400" />

### The Reason for Choosing It

While the chart attempts to highlight the gender gap in research and innovation, it fails to convey the message effectively due to design and readability issues:
- **Complexity and Overlap**: The visualization includes multiple categories (areas of study) for each country, resulting in significant overlap of data points. For example, both the UK and Canada in the figure have three types of data overlapping.
- **Lack of Context**: While the title and subtitle suggest gender inequality, the chart does not address why these differences exist.
- **Improper Use of Color**: While the color and shape of the columns are used to distinguish between different subject areas, the use of color may not be intuitive or easily confused. For readers unfamiliar with these color codes, it may be difficult to distinguish between disciplines.
- **Possible Misleading**: Due to the lack of detailed data and clear explanation, charts can be misunderstood or misused. For example, readers may mistakenly assume that highly ranked countries perform well in all subject areas, while low-ranked countries underperform.

### Its Impact on Society

It shows the proportion and number of published papers by female researchers in different fields in different countries. This helps to better understand the participation and contribution of women in scientific research. By analyzing the proportion and number of female researchers in different fields, it is possible to find out which fields have high and low female participation, as well as what gender gaps may exist. This information is important for the development of targeted policies and measures to promote gender equality and the advancement of women in scientific research. In addition, the study of this chart can also promote people's understanding and thinking about gender equality. The data and information presented in the chart can arouse people's attention and discussion on gender equality, and stimulate people to think more deeply about the importance of gender equality in scientific research, and how to promote gender equality through policies and measures.

## 2. Detailed Explanation of the Information Visualization

### 2.1 Story and Purpose

#### Story Analysis

This chart, in the form of a bar chart, shows the proportion of female researchers in various scientific fields (including health sciences, engineering, physics, computer science, and mathematics) published between 2011 and 2015 in different countries. From the chart, we can observe the degree of activity and contribution of female researchers in various scientific fields in various countries.

- **Underrepresentation in STEM**: Women are consistently underrepresented in STEM fields. The reasons for the gender gap relate to the allocation of educational resources, career opportunities, and socio-cultural factors.
- **Overrepresentation in Health Sciences**: Women are generally overrepresented in health sciences, which is related to the division of gender roles in society. In contrast, women are significantly underrepresented in fields such as engineering and computer science, hindering diversity and innovation in related industries.

##### Observation

- Portugal and Brazil have the highest percentage of females in health sciences, approaching or exceeding 50%.
- In contrast, Japan has the lowest percentage of females in all fields at less than 20%, reflecting the severity of the STEM gender gap in that country.
- In most countries, the percentage of women is highest in health sciences and lowest in engineering and computer sciences. For example, women in the United States make up about 50 percent of the health sciences but less than 20 percent of engineering and computer science.

##### Reasoning

- **Portugal and Brazil**: May have benefited from better educational gender equality policies or socio-cultural support.
- **Japan**: The gender gap in STEM may be related to its traditional gender role concepts and gender discrimination in the workplace.
- **Occupational Attractiveness**: Health sciences may be more in line with traditional gender stereotypes of “caring” jobs.
- **Educational and Career Entry Barriers**: Computer science and engineering may have higher technical barriers and fewer female role models.
- **Societal Expectations**: In some societies, women may be discouraged from pursuing “scientific” careers such as engineering and math.
#### Objective Analysis

The purpose of this chart is to draw attention to gender equality in science and to show the progress and challenges that different countries have made in this area. By comparing the proportion of the number of papers by female researchers in various scientific fields in different countries, the chart aims to reveal the importance of gender equality in scientific research and encourage countries to take positive measures to promote the development of women in scientific research.

At the same time, the chart also aims to stimulate further reflection and discussion among the scientific community and policymakers on the status and contribution of women researchers in science, in order to promote the development of more equitable and inclusive scientific research policies and practices.

### 2.2 Chart Interpretation

The vertical axis shows the proportion of female researchers, ranging from 1% to 60%. The horizontal axis lists several countries or regions, such as Portugal, Brazil, Japan, etc.

The color segments inside each column indicate the proportion of female researchers in different subject areas.

Looking at the proportion of female researchers in various fields in different countries or regions, some stark differences can be found. For example, Portugal has a high percentage of female researchers in the health sciences, while France has a low percentage of female researchers in computer science.

It can also be noted that in some fields (such as computer science and mathematics), the proportion of female researchers is generally low, which may reflect the gender imbalance in these fields.

### 2.3 Visual Variables

- **Color**: Differentiates areas of study, but confuses due to overlapping bands.
- **Position**: Horizontal encoding of percentage values, but crowded data points blur the comparison.
- **Shape**: The circles designed for inventors are unique but not connected to the bar format, which creates inconsistencies.
- **Length**: Indicates the proportion of women in a given discipline, but competes for attention due to overlapping areas.

### 2.4 Explain the Effectiveness of the Visualization

The human visual system processes graphics and images much faster than text. The chart draws the reader's attention and reduces cognitive load by using visual elements such as color, height, and position to distinguish between different countries, fields, and proportions. According to cognitive load theory, effective visualization can reduce redundant information and improve the efficiency of information processing.

Dual coding theory states that information is stored in memory in both verbal and non-verbal forms, and there is an interaction between the two. The chart combines both verbal (such as country names, domain names, and scale numbers) and non-verbal (such as color and height of bar charts) encoding to help readers understand and remember information more fully. This dual encoding method can enhance the memory effect of information and improve the accessibility and extractability of information.

By comparing data across countries, fields, and proportions, the chart provides readers with a frame of reference that allows them to more accurately assess the participation of women researchers in science. This way of comparison and reference helps readers to form a comprehensive cognitive structure and deepen their understanding of gender differences and scientific research.

### 2.5 Background and Improvements

This visualization stems from a report on the gender gap in global research, a key topic driving equity policies in education and STEM fields. However, its current design limits its effectiveness.

Here's how to improve the original chart.

- **Separate Areas**: Use small multiples to reduce overlap and improve clarity.
- **Highlight Key Trends**: Use annotations or narratives to highlight important findings (e.g., which countries are leading in gender equality).
- **Clear Labeling**: Clearly label the meaning of each column in the chart, such as the country name and the corresponding field.
- **Color Differentiation**: Use different colors to distinguish different areas of science to make the chart more intuitive and understandable.
- **Distribution Map**: Using the violin plot of the distribution of each country in various fields, it can comprehensively show the participation of women in different fields in each country.

## 3. Replicate the Information Visualization 

<img src="./replicated_picture.png" width="450" height="300" />

## 4. Propose Changes That Would Improve the Graph

### Improvement Objectives

1. **Comparison Between Countries**: Demonstrate, through a clear layout, the gaps in female research participation in different countries, with notable comparisons in the health sciences and engineering in particular.
2. **Comparison Between Disciplines**: Highlight the differences in disciplines within the same country, emphasizing contrasting gender ratios in fields such as health sciences and computer science/engineering.
3. **Intuitive and Logical**: Optimize the color scheme and type of charts to reduce cognitive load and enable viewers to quickly grasp the main information.

### Specific Improvements

#### Clustered Bar Chart to Show Data Distribution

- **Logic**: The Clustered Bar Chart allows for a visual comparison of the proportion of females between countries and across disciplines within the same country, avoiding the confusion caused by overlapping multiple data bars in the original chart.
- **Method of Implementation**:
  - Each country is a cluster (group), and the cluster is divided into five columns corresponding to each of the five data categories (health sciences, physical sciences, engineering, computer science/math, and inventors).
  - The height of the columns indicates the percentage of females, the horizontal axis is the country, and the vertical axis is the percentage.

#### Optimizing the Color Scheme to Highlight Key Trends

- Use significant color contrasts for the two data categories, Health Sciences and Inventors:
  - **Health Sciences**: Use a bright color (e.g., green) to highlight its relatively high percentage of females.
  - **Inventors**: Use a bright contrasting color (e.g., crimson or bright yellow) to highlight significantly lower female participation rates.
- For the remaining three disciplines (Physical Sciences, Engineering, and Computer Science/Mathematics), since their overall trends are similar and their proportions are close, use **gradient colors in the same color family** (e.g., different shades of blue). This treatment reduces the visual load on the viewer while clearly showing small differences between these fields.
- **Logic**: This color scheme establishes a clear visual hierarchy (health sciences highest, inventors lowest, and the remaining disciplines in the middle), allowing viewers to quickly pinpoint the main message points of the data.

#### Layout Adjustment and Grouping Contrast

- **Grouping by Country**: Arranging countries on the horizontal axis and displaying disciplines in clusters allows for at-a-glance comparisons of differences in gender ratios of disciplines within the same country.
- **Faceting Layout (Faceting) Aids Analysis**:
  - For larger data volumes, key areas within the five disciplines (e.g., health sciences and engineering) can be mapped individually, arranging the columns by country to help focus on significant gender differences across countries.

#### Enhanced Logical Flow of Data

- **Between-country Analysis**: Using clustered bar charts can quickly present which countries are performing better on gender equality. For example, Portugal has close to 60% women in health sciences, while Japan performs poorly in all subject areas.
- **Interdisciplinary Analysis**: The difference in height of the bars clearly demonstrates that health sciences are much higher than disciplines such as engineering and computer science in each country. This performance directly leads the viewer to think about gender inequality within STEM.

#### Moderate Annotation and Labeling

- Label extreme values (e.g., countries with the highest percentage of health sciences and the lowest percentage of inventors) directly on the chart to help the viewer focus on important data points.
- Clearly explain the color logic in the legend, e.g., “Green indicates health sciences, representing disciplines with a high percentage of women.”

### Improved Benefits

1. **Clear Logic**: The combination of clustered bar charts and a faceted layout demonstrates the differences between countries while focusing on comparisons within disciplines, making the information more logically coherent.
2. **Significant Contrast**: The color scheme is optimized to emphasize the specificity of health sciences and inventors, highlighting key information.
3. **Reduced Cognitive Burden**: Reducing the distraction of overlapping data and color clutter helps viewers quickly understand the core issue of gender inequality in STEM fields.
4. **Assisted Reasoning**: Clear data distributions and trends can trigger deeper thinking among viewers, such as whether the high percentage of health sciences is influenced by gender roles in society, and whether the low percentage of inventors is related to barriers to career entry.

## 5. Improve the Information Visualization

<img src="./improved_picture.png" width="500" height="700" />