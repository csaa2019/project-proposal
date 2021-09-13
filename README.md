# Project Description
This project focuses on building a NN to generate a poem based on a general topic or theme. I chose this topic because I’m interested in the applications of neural nets in creative and artistic fields.

I plan to use existing datasets already exist containing the poem’s title, author, and tag from *poetryfoundation.org*, found [here](https://www.kaggle.com/tgdivy/poetry-foundation-poems)  and [here](https://www.kaggle.com/harunshimanto/poems-categorization-datasets?select=2.csv). *poetryfoundation.org*’s tag system labels poetry by various topics (death, love, nature, social commentary, etc.) The tag system is likely too detailed for the purposes of this project, so I plan to group similar tags together (e.g. love, relationships, engagement, anniversaries, and weddings might all be grouped together). 

If the scope of the project is too large, I plan to either focus on a singular theme (whichever one has the most data available for it) or train on the entire set and focus on generating a poem, irrespective of its topic. If the scope is too small, then I would attempt to make the generator create a poem with overlapping themes. 

Ideally, the generator will be deployed as a simple web page that will allow users to choose a general topic and then receive a poem of that theme.

---
# Project Goals
-	Combine and modify the existing datasets so that they have more generalized theme tags.
-	Train a NN to generate a poem of one specific theme.
-	Deploy an application that can generate a poem given a specific theme.
