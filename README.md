# Interactive-Data-Vizualization
Tableau Usecases 1:Dashboard Link : Dashboard: Shifts in Student Activities and Cognitive Performance
Before and After COVID-19 -> https://public.tableau.com/app/profile/dush.sena/viz/Analysis_Students_activities/Dashboard1

![Dashboard 1](https://github.com/user-attachments/assets/8b97a2e2-8463-46cf-8f9c-3b6b665daf1b)

Data Preprocessing Steps (Programming language: Python, Libraries: pandas, numpy)
○ Subset Selection: Extracted relevant columns from the dataset for analysis.
○ Data Type Validation & Cleaning: Identified and corrected invalid string values in numeric fields.
Dropped unusable records with null or incorrect data records.
○ Age Filtering: Retained only records for students aged 10 to 18.
○ Outlier Handling: Detected and removed records with unrealistic extreme values in numeric fields.
○ Data Type Conversion: Ensured all variables had appropriate data types for analysis.
○ Feature Engineering:
■ Created pre-COVID (≤2019) and post-COVID (>2019) labels using DataYear.
■ Generated age groups: Below 13 and Above 13 based on AgeYears.

● Vizualization Tool: Tableau
● Findings:
Chart Name

Chart
Type Key Findings

Weekly Average Activity Hours
(2014–2024) Line Chart

Overall, Screen-based activities (video games, watching TV, computer use) increased
after COVID-19, especially computer use, which has significantly increased for both
groups. During the pandemic, females’ watching TV hours increased, whereas males'
video games hours increased. Outdoor activities and family time decreased.
Homework hours remained stable.

COVID Impact on Weekly Activity
Hours by Gender Bar Chart

Females spent significantly more time on computer use post-COVID. Males also
increased screen time but to a lesser extent. Outdoor activities and family time
dropped, especially for females.

Average Seconds Spent on
Cognitive Activities (Reaction Time
& Memory Score) by Gender Bar Chart

Females had slightly longer reaction times than males. Also, both male and females
have slight improvement on reaction time post-COVID period. Memory scores
remained stable, with no significant pre- vs. post-COVID changes.

COVID Impact on Reaction Time by
Gender & Age Group Box Plot

Younger students (below 13) had slightly faster reaction times compared to older
students. Males consistently showed lower reaction times than females.
Based on the findings, students' weekly activity patterns and cognitive performance exhibited noticeable changes
before and after COVID-19, with differences observed across gender groups:
In summary, after COVID-19, students, especially females, increased their screen time at the expense of outdoor
activities and family time. Cognitive performance, particularly in terms of reaction time has reduced after covid, and
memory scores, remained relatively stable, with no major changes observed before and after COVID-19 across
gender groups.
● Design Decisions and Rationale:
1. Chart Selection:
○ Line Chart for Weekly Average Activity Hours (2014–2024): The line chart was chosen to show
the trend over time, highlighting the change in students' activity patterns over the past decade. It
effectively illustrates how the different activity types (screen time, outdoor activities, family time,
etc.) have evolved, especially the spike post-COVID. A line chart was ideal here as it emphasizes
the continuous nature of time and enables clear tracking of these patterns across years.
○ Bar Charts for COVID Impact on Weekly Activity Hours by Gender, Cognitive Activities
(Reaction Time & Memory Score) by Gender, and COVID Impact on Reaction Time by
Gender: Bar charts were used for comparisons between gender groups across specific categories

like screen time, outdoor activities, reaction time, and memory scores. Bar charts are effective for
categorical comparisons, providing a clear visual representation of differences across gender and
age groups. For example, the COVID Impact on Weekly Activity Hours by Gender bar chart
compares how screen time, outdoor activities, and family time changed for males vs. females
post-COVID.
○ The Cognitive Activities box and whisker plots compare reaction times between males and
female by age groups, making it easy to identify trends or differences in performance. Also helps to
identify outliers and data distributions.

2. Visual Encodings:
○ Color: I used color coding to differentiate between genders and activity types across the charts.
This was based on the principle of visual distinction, where colors make it easy for viewers to
understand and compare categories quickly.
■ For example, distinct colors were applied to male and female data to make gender
differences easy to identify in the bar charts.

○ Position: The position of elements on the charts (e.g., bar heights for cognitive performance or
activity hours) was used to communicate quantitative differences. This choice aligns with
theoretical foundations in visual perception, where people naturally associate vertical positions with
magnitude.
○ Shape and Size: In the line chart, different colored lines were used to represent different activity
types. The size of the bars in bar charts was used to directly reflect the value of the measured
variable (e.g., hours spent on each activity or reaction time).

Design Iterations:
1. Initial Iteration: Initially, I considered using heat maps to show the correlation between variables but
identified that, with fewer points, it is not accurate. I used pie charts to show proportions of weekly activity
hours before and after COVID-19. However, the pie charts did not visualize the differences that I wanted to
highlight (e.g., showing change before and after COVID), so I switched to a stacked bar chart, which clearly
shows activity time compositions.
2. Adjustments in Data Representation: Initially, I had thought about representing all data in a single,
stacked bar chart. However, this created complexity and made comparisons between different activities
challenging. Therefore, I opted for separate bar charts to allow a more focused comparison of each variable
(e.g., reaction time and memory scores separately).
3. Gender-Specific Bar Charts: In some versions, I grouped both male and female data in the same bar, but
this made it hard to distinguish trends. To improve clarity, I decided to use side-by-side bars (grouped by
gender), which improved the visual differentiation.
Lessons Learned:
1. Importance of Clarity: Clear and simple visuals are crucial to avoid clutter and confusion, especially when
differentiating groups like gender. Distinct visuals enhance readability.
2. Choosing the Right Chart Type: Selecting the appropriate chart type is vital—line charts for time-based
trends and bar charts for categorical comparisons worked better than other alternatives.
3. Iterative Refinement: The initial design is just a starting point; iterative improvements based on feedback
and usability tests help in simplifying visuals and improving understanding.
4. Context Matters: The context, such as COVID-19's impact, must be clear throughout the design process to
ensure the significance of data changes is well understood.
5. Data Preprocessing is Key: Proper handling of missing values and outliers is essential for ensuring
accurate trends and meaningful insights.
In my perspective, aligning visual design with the data’s purpose and iterating based on feedback ensures clarity and
effective communication of insights.

