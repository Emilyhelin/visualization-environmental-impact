• First Visual Design Type: Treemap
• Name of Tool: Tableau
• Diet Groups: Veggie, Low meat eaters(<50gd-1
), Medium meat eaters(50-99gd-1
), High meat 
eaters(≥100gd-1
), Fish, Vegan
• Age groups: 20-29, 30-39, 40-49, 50-59, 60-69, 70-79
• Gender: Female, Male
• Visual Mappings:
–color: color is mapped to the difference between total environmental impact 
–shape: each bottom level rectangle represents a diet group
–size: the size of the bottom-level rectangle is mapped to the difference in participants number 
between the diet group and age group, segmented by gender.
–position: the position of each rectangle is determined by the participant's number; rectangles 
representing more participants are positioned further to the left.
–hierarchy: the rectangles are grouped by diet group → age group → gender
• Unique Observation: We can see the outliers that the veggie between 70 and 79 imposes the greatest 
burden on the environment, which surprises me. Then it is followed by high meat eaters between 20 and 
29.
Besides, the vegan between 50 and 59 has the least impact on the environment.
Given that most areas of high meat eaters are close to dark, we can estimate that the high meat eaters put 
the greatest pressure on the environment.
Also, females impose less impact on the environment as their areas are bluer than males in general.
In terms of participants’ features, the female participants outnumber male participants, with veggies
constituting the largest group This could create bias in the final output.
• Data Preparation: To calculate the environmental impact, the column of total environmental influence is 
calculated by summing standardized GHG emissions, Agricultural Land Use, Water Scarcity, Biodiversity,
Water Usage, and Acidification Potential.
• Second Visual Design Type: Radar area chart
• Name of Tool: Python
• Diet Groups: Veggie, Low meat eaters(<50gd-1
), Medium meat eaters(50-99gd-1
), High meat 
eaters(≥100gd-1
), Fish, Vegan
• Environmental impacts: GHG emissions, Biodiversity, Water use, Acidification, Eutrophication and Land 
use
• Visual Mappings:
–color: color is mapped to show differences between diet groups
–axis: each axis represents a different aspect of environmental impact
• Unique Observation:
From the radar area chart, it is obvious that high meat eaters rank highest in all aspects of negative impact
on the environment. Vegan has the least negative impact on the environment. The special thing is that the
fish diet ranks only second in water use.
• Data Preparation: Normalize different impacts like land use, GHGs, acid, water use, bio, eutrophication on 
a scale from zero to one
