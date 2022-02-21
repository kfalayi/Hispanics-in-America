# US isn't just attracting thousands of Hispanic immigrants with its visa annually, it's economy depends on it.
The idea behind this project was to find out which country has got the highest share of U.S. Immigrant visas in the last decade and to see if it is possible to weigh the contribution of the immigrant group on the U.S. economy.
<br>

## Findings
<hr>
The analysis of data from the State Department and Bureau of Labor Statistics show the following:
- Most immigrant visas went to countries Hispanic and Latin American countries
- Three countries - Mexico, Dominican Republic and El Salvador are the countries where most immigrants come from.
- The U.S. gave these three countries alone one quarter of all immigrant visas in the last three years.
- Documented immigrants make up about 15 per cent of the labor force. The Bureau of Labour Statistics does not count undocumented immigrants, so the figure is likely much higher.
- For many of the sectors, the ratio of Hispanic workers to population in labor force is higher. 
- In sectors where the proportion of Hispanic workers is lowest, it is stil still higher than other immigrant groups.

## Data collection and analysis.
<hr>

I downloaded a [dataset](https://github.com/kfalayi/Hispanics-in-America/blob/main/US_ImVisa_continent.xlsx) of immigrant visa approvals from 2010 to 2020 from the State Department travel [website](https://travel.state.gov/content/travel/en/legal/visa-law0/visa-statistics.html). 
I chose this time range to exclude years from 2020 till date due to how the pandemic affected travels and employment.
I filtered down the data down to the volum of visa approvals volume for each country and saved it in [this CSV](https://github.com/kfalayi/Hispanics-in-America/blob/main/visaCountry.xlsx). 
At this point, the obvious question might be why does the U.S. attracting immgrants from Hispanic countries more?
I decided to look at the share of the US labor force that identify as Hispanic with the data from the [Bureau of Labor Statistics].(https://www.bls.gov/news.release/empsit.t01.htm) which I saved in this [CSV](https://github.com/kfalayi/Hispanics-in-America/blob/main/labour_ethnicity_2020.xlsx).
It turns out that the figure is not out of the ordinary. But of course, the figure is undercounted because undocumented immigrants who are as important to the US. economy as documented are not counted in the Bureau of Labor Statistics figure.
I then decided to look into specific sectors to see the proportion of Hispanic immigrants in the labor force.
I filted the data down to top sectors where Hispanics have highest representation and also the lowest. I saved the highest representation sectors [here](https://github.com/kfalayi/Hispanics-in-America/blob/main/topfield.csv) and sectors with lowest represention [here](https://github.com/kfalayi/Hispanics-in-America/blob/main/lowfield.csv). 

## What I learnt from this project
<hr>
I learnt that data cannot always be able to answer questions one has in mind. Or maybe the kind of data that would answer such questions are just not readily available. I thought some kind of regression would give more depth and context to this story. I wanted to quantify the impact of Hispanic workers in the labor force to see if it is possible to see a correlation between increase in immigrants from Hispanic countries in the labor force on the and growth or otherwise of specific sectors of the economy where the proportion of Hispanic work force is high. But I learnt that I would need a lot more data I still haven't been able to figure out how to collect like changes in techonology use those sectors, funding pattern, climate change and other market forces.
