# PA #4 Nathan Josh Cacho

## Visayas Communication DataFrame

* For this task, I needed to create a DataFrame containing students who are from Visayas and are in the Communication track. I used Pandas to filter the original dataset using both conditions at the same time. After filtering the data, I selected only the Name, Gender, Math, Electronics, and Average columns. The resulting DataFrame contained 5 students. This showed me how multiple conditions can be used together to create a more focused DataFrame.

## Visayas Female DataFrame

* The second task asked me to find female students whose hometown is Visayas. I used Pandas again and applied both the Hometown and Gender conditions to the original dataset. I then selected only the Name, Track, GEAS, Electronics, and Average columns. After displaying the DataFrame, I used another filter to show only students whose Average was at least 60. I kept the original VisFemale DataFrame unchanged while doing this second filter.

## Category-Average Visualization

* The last task involved comparing the Average of students across Track, Gender, and Hometown. I used groupby() and mean() in Pandas to calculate the mean Average for every category. I then displayed the three summary tables and created three bar charts in one figure. The charts made it easier to compare the average values between the different groups. I also wrote statements describing which category had the highest sample mean for each feature. This activity helped me understand how Pandas can be used to summarize data and how graphs can make comparisons easier to see.
