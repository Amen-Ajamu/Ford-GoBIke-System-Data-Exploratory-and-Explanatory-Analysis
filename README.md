# Ford-GoBIke-System-Data-Exploratory-and-Explanatory-Analysis
## by Amen T.  Ajamu


## Dataset

The dataset contains 174952 non-null entries of individual bike rides made on Ford GoBike's bike-sharing platfrom in the greater San Francisco Bay area. The ratio of numeric to non-numeric features is almost equal, to make up a total of 16 features. Upon discovering that all the data were collected in february 2019, I decided to extract the days of week during which the users booked the bikes. I named this new feature, 'start_day' and made sure to convert the default numeric encoding from 0 through 6 to Sunday to Saturday

## Summary of Findings
The majority of the bike users on this bike sharing platform identified as male. Also, their major proportion were subcribers. This is consistent with the general social construct. It was also observered that the bike sharing platform is not popular among older adults. Factors such as increased risks for fall and limited physicality may be responsible for this. 

Surprisingly, I did not observe any key relationship between the users' age and their duration of use of Ford's GoBike service. However, users during the weekend (Sunday and Monday), subcribers and females were found to be the youngest of the whole lot. A rather unexpected, but interesting discovery is that a larger proportion of subcribers used the bikes for a lesser duration of time than regular customers. Nonetheless, the user who used the bike for the longest duration of time is a male subcriber who hired the bike on a thursday and had it with him until the next day.

There is a correlation between the start station id and the users' destination. This posits that a good number of the users have fixed routes on which they use these 

## Key Insights for Presentation

For the presentation, I will be considering days of the week when clients used the Ford GoBike system the most and the effect the type of user (subcriber or non-subscriber) has on the routes toured and the duration of use of the system.
I will first plot a distribution of the duration of use and that of the user type. Afterwards, I will do a scatter plot of the start point against the destination encoding user type with color to make the third variable.
This project involves the use of relevant python packages to analyze bike share data on the Ford GoBIke platform in the San Francisco Bay Area
