# Excel-Challenge

Conclusions I Draw About the Kickstarter Campaign:
  1.	The US accounts for significantly more campaigns, especially successful campaigns, than any of the other country on the list.
  2.	The following campaign categories have a near 100% success rate:
    a.	Documentaries
    b.	Nonfiction writing
    c.	Radio & Podcasts
    d.	Tabletop Games
    e.	Pop, Metal, and Rock Music
    f.	Technology Hardware
  3.	Chances of having a successful Kickstarter Campaign are least in December.

Limitations:
  1.	The data does not reflect any demographic (for example: income level, race, geographical location) which might would assist further in predicting the success of a campaign that a business is planning.
  2.	There appears to be very little data for other countries compared to the US, is this because kickstarter is not readily available to those general populations or because the citizens of other countries are not interested in the platform? Or is it a failure of the dataset?

Other Possibilities for Tables and/or Graphs:
  1.	A pivot table to show the Average Amount Pledged per Person by Sub-Category with filters for Country and Parent Category. I’d be interested to see if the average person who pledges for documentaries pledges more or less than the average pledge for metal music, for instance.
  2.	Gross dollars pledged by sub-category, filtered by country. 

Bonus Statistical Analysis:
  Assumptions in making these calculations: I used the formulas VAR.S and STDEV.S due to the assumption that the data we are working with is a sample of the full data population available. Also, all of the calculations were expressed as whole numbers to reflect the same degree to which the data was reported.
Considering that the Median of Successful Campaigns is 62 backers with the Maximum number of backers counted at 26,457 the Mean is a more meaningful summarization of the data. I would think that if one is trying to determine if a potential campaign has a good chance of success, having more backers than the average would be more meaningful information than having the middle number of backers. 
  There is more variability with successful campaigns based on the Variability of Successful Vs Unsuccessful campaigns being 713,167 and 3,776 respectively. I think this makes sense because variability is the spread in the data and unsuccessful campaigns have both a floor (0 backers) and a ceiling (1 backer less than the minimum number of US dollars required to make the campaign successful) while successful campaigns have a floor minimum of 1 backer but the only limiting factor in pledged number of backers and dollars is the time that the campaign is run, thus the spread for a successful campaign is practically without limit. 
