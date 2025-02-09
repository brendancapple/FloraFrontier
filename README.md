# FloraFrontier
You're tired of grey goo, aren't you?


## Inspiration
Our inspiration for the project was improving the lives of astronauts, specifically at meal times. While living on a space station, the menu can be minimal and repetitive. We aimed to improve astronauts' condition of living by compiling a list of untested plants that may thrive in space, allowing astronauts to grow a wider variety of food.

## What it does
Flora Frontier creates a list of potential plants that could be grown in existing infrastructure in space. Using the plants that have been grown in space already, it finds other plants that grow in the same environment that have significant nutritional value. 

## How we built it
We used Jupyter notebooks to compile and process data from the USDA Natural Resources Conservation Service and "". We compiled a list of plants grown in space, downloaded their common location distribution from the USDA database, and determined the list of states all plants grew in. Then, we searched that database for a list of plants in each state, pruned only to keep plants that grow in all the states. Finally, we sorted the remaining plants according to their nutritional properties, edible parts, etc. This provides our final list of plants to try growing in space.

## Challenges we ran into
One of our biggest challenges was finding an API or data set that would allow us to look at plant species, growing conditions, and nutrient values. We had to compile data from multiple datasets, all with different APIs or data download schemes.

## Accomplishments that we're proud of
Setting up GitHub in a local IDE and learning how to deal with a variety of API types may both seem like trivial, preliminary stages. They were anything but. Each took upwards of 4 hours, just troubleshooting all the problems that arose from using unfamiliar tools in often unintended manners. For that, we're proud of these seemingly trivial victories; they were the hardest fought.

## What we learned
This project was full of lessons learned the hard way. The first is that data science projects require data, so any rapid data science projects should have an API or dataset in advance. We searched for our data after ideating and had to fit a hodge-podge of data into a coherent analysis. This wasted a lot of time we could have used for more complex analysis. We also learned that version control is a must. We started this project in Colab, without Github, and it quickly became a nightmare to work on the code concurrently. If we'd started on GitHub, we also wouldn't have wasted so much time transferring Colab-specific code into standard ipynb code. Finally, we learned to vet datasets before using them, as we lost around three hours to implementing an API that didn't contain the plants we needed.

## What's next for Flora Frontier
The next step would be to merge the individual tools into one tool, wrapped in an app or other UI. With the general lack of information we were able to find from NASA and the almost non-existent USDA database API, our project is limited in scope. However, this tool will hopefully allow people with access to that information to achieve our goal.
