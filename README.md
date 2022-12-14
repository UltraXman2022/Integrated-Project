<h1>Project description</h1>
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.
In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.
(The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2017 sales based on data from 2016.)
The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

<h2>Instructions for completing the project</h2>

<h3>Step 1. Open the data file and study the general information</h3>

Download dataset

<h3>Step 2. Prepare the data</h3>
<ul><li>Replace the column names (make them lowercase)</li>
<li>Convert the data to the required types</li>
<li>Describe the columns where the data types have been changed and why</li>
<li>If necessary, decide how to deal with missing values:</li>
<ul><li>Explain why you filled in the missing values as you did or why you decided to leave them blank</li>
<li>Why do you think the values are missing? Give possible reasons</li>
<li>Pay attention to the abbreviation TBD (to be determined). Specify how you intend to handle such cases</li></ul>
<li>Calculate the total sales (the sum of sales in all regions) for each game and put these values in a separate column</li></ul>

<h3>Step 3. Analyze the data</h3>
<ul><li>Look at how many games were released in different years. Is the data for every period significant?</li>
<li>Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year. Find platforms that used to be popular but now have zero sales. How long does it generally take for new platforms to appear and old ones to fade?</li>
<li>Determine what period you should take data for. To do so, look at your answers to the previous questions. The data should allow you to build a prognosis for 2017.</li>
<li>Work only with the data that you've decided is relevant. Disregard the data for previous years</li>
<li>Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms</li>
<li>Build a box plot for the global sales of all games, broken down by platform. Are the differences in sales significant? What about average sales on various platforms? Describe your findings</li>
<li>Take a look at how user and professional reviews affect sales for one popular platform (you choose). Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions</li>
<li>Keeping your conclusions in mind, compare the sales of the same games on other platforms</li>
<li>Take a look at the general distribution of games by genre. What can we say about the most profitable genres? Can you generalize about genres with high and low sales?</li></ul>

<h3>Step 4. Create a user profile for each region</h3>
<ul><li>For each region (NA, EU, JP), determine:</li>
<li>The top five platforms. Describe variations in their market shares from region to region</li>
<li>The top five genres. Explain the difference</li>
<li>Do ESRB ratings affect sales in individual regions?</li></ul>

<h3>Step 5. Test the following hypotheses:</h3>
<ul><li>Average user ratings of the Xbox One and PC platforms are the same</li>
<li>Average user ratings for the Action and Sports genres are different</li>
<li>Set the alpha threshold value yourself</li></ul>

Explain:
- How you formulated the null and alternative hypotheses<br>
- What significance level you chose to test the hypotheses, and why<br>

<h3>Step 6. Write a general conclusion</h3>

<h4>Data description</h4>
<ul><li>Name</li>
<li>Platform</li>
<li>Year_of_Release</li>
<li>Genre</li>
<li>NA_sales (North American sales in USD million)</li>
<li>EU_sales (sales in Europe in USD million)</li>
<li>JP_sales (sales in Japan in USD million)</li>
<li>Other_sales (sales in other countries in USD million)</li>
<li>Critic_Score (maximum of 100)</li>
<li>User_Score (maximum of 10)</li>
<li>Rating (ESRB)</li>
<li>Data for 2016 may be incomplete</li></ul>
