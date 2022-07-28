# Taylor Swift Analysis

Open EDA.pdf for a full exploratory data analysis report and data visualization.

## Abstract ##

In this study, we planned to analyze if the notion of declining attention spans has made its way into the
music industry and its listeners. We checked a) if Taylor Swift’s songs have gotten shorter over the years
and b) if her shorter songs are more popular among her streamers. We did not find any strong evidence for
either. We conducted an ANOVA F-test and a pairwise difference test and found that average song length
increased, decreased and then increased again over the years 2006-2021. We could not find a consistent
decreasing pattern, and could not conclude that Taylor Swift’s songs have gotten shorter over the years.
Additionally, with the help of linear regression analysis, we found evidence that her shorter songs are more
popular among her streamers. This was, however, a weak negative correlation. We concluded that while
there was an association between song length and popularity, it was a weak association. Hence, there is a low
probability that a song is streamed more if it is shorter. However, it could happen.

## Data ##

In this report, we analyzed a dataset of Taylor Swift’s songs from Kaggle, which contains data gathered
from songs on Taylor Swift’s albums. We analyzed if her songs have gotten shorter over the years and if a
shorter song length is more popular among her Spotify listeners. We used 3 variables to do this observational
study: release_year (release year of each song), length_min (song length in minutes), and popularity (percent
popularity of the song based on Spotify’s algorithm, possibly the number of streams at a certain period of
time). For our first relationship (determining the length over the years), the release year is the predictor
variable while the length is the response variable, and our population concerns all Taylor Swift songs released
over the years 2006-2021. For our second relationship (determining the popularity based on length), the
variable length is the explanatory variable and the popularity is the response variable. Except for the variable
for release year, which is categorical, our other two variables are quantitative. While we are only looking
at Spotify data, our data analysis concerns the population that is listeners of Taylor Swift’s music across
all streaming platforms. Since a streaming platform is chosen by a streamer due to personal choice and
prices/availability, and the song/artist does not possibly play a role, we are assuming that the Spotify data
can be used to generalize to every Taylor Swift streamer using a platform similar to Spotify.
Note: we assumed that her re-recorded albums are old albums; that is to say that we considered their
original release year instead of the year the re-recordings were released. However, the new songs on these
albums – named “From the Vault” – were categorized as new. Also, there are three songs in the dataset that have 0 popularity. Since there is no popularity information available for them, we excluded them when doing an analysis for our second relationship.

#### Datasets  ####

*Spotify_taylorSwift - spotify_taylorswift 3.csv*


