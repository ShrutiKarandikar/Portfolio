# Critique and Wireframing Solutions

### Step 1: Choice of data visualization

In this project I have attempted to redesign a web article published on Yahoo Finance, which talks about Apple as a company and its status in the market. Primary audience for it is the individual investor trying to explore Apple as a company to invest in. This visualization is a good attempt at collecting different types of resources, and attracting audience. But it may improve on the implementation of the graphs which can effectively convey essence of the data.
Here is the link to original article : Jeremy Bowman, "[Apple in 5 charts](https://finance.yahoo.com/news/apple-5-charts-141500849.html)", last modified September 22, 2018.<br>
Here is the link to the base data: [Base Data](https://docs.google.com/spreadsheets/d/1oJTscwg8jrud96mGKQXxaRHOK3BVkXbconBPnKsXJUk/edit#gid=0)


The rationale behind choosing this visualization was that it tries to tell the story of a product in the dynamic stock market domain. In finance sector, which is already overwhelmed with charts, graphs and numbers, good data visualization techniques are critical to stand out and provide wise and accurate information. 
<br>Also, prior to CMU, I was working as a Business Analyst in Regulatory Reporting domain. I used to generate graphs, design dashboard and analyze numbers for a living. Hence I can relate very well to such visualizations and audience we are trying to connect to. 
<br> After searching for a while on various sources like The New York Times, The Economist etc I found out this article which focuses on Apple’s positioning in the market after release of iPhone Xs in 2018.  The title of the article was quite attractive “Apple in 5 charts”, which intrigued me to read further. Although, as I read through it, I found a couple of issues with the graphs which made me choose this visualization for the assignment

#### Things that stood out to me & worked really well- <br>
1) Title of the article is attractive<br>
2) Information source is authentic , recent and relevant. Source : Apple's published financial reports <br>
3) It has enough charts to elaborate / visualize. Less verbose content<br>


#### Things I thought would have been done differently - <br>

I have pasted the graphs from the original website [Original Website](https://finance.yahoo.com/news/apple-5-charts-141500849.html) below for easier reference -







![pie](https://user-images.githubusercontent.com/59716372/73616817-255f0400-45e6-11ea-9e58-84fc5251a6f3.png)
![yello](https://user-images.githubusercontent.com/59716372/73616818-255f0400-45e6-11ea-92ef-d5a2533b9fc5.png)
![green](https://user-images.githubusercontent.com/59716372/73616816-24c66d80-45e6-11ea-9e13-077546ec158b.png)

In the above graphs, I would focus on modifying below - <br>
1) Updated colour-scheme of the visualizations - Colours are too bright for a laptop/mobile screen (Fluorescent yellow & green on white background)<br>
2) The title reads "Apple in 5 charts". But in practice there are only 3 charts and one is an image of iphone XS model. I would make the data and title consistent <br>
3) All the bar graphs & pie charts are 3- Dimensional. I do not find it necessary / relevant to give depth dimension to the chart. Hence would edit them to make a simpler visualization.<br>
4) In last 2 graphs ("Iphone unit sales" and  "Iphone average selling price in Dollars") , x axis years are in reverse order ( starts with 2018 and ends at 2015) This is counter intuitive to what we generally expect. Hence would redesign these bar graphs.


### Step 2: Critique the visualization

In this course, one mantra we have learnt is – To be good at creating visualizations, be good at critiquing them. In the first 3 weeks, we have studied 2 techniques of critiquing visualization. One is the Good Charts method and other is Data Visualization Effectiveness Profile method. 
Of these two, I have used the Effectiveness profile method to critique the data visualizations at hand.<br>
Areas of focus which I found where the design lacked were -<br>
•	Perceptibility <br>
•	Intuitiveness <br>
•	Aesthetics <br>

With my redesign, I would try to improve on the three areas mentioned above. Based on the assessment of "Apple in 5 charts" , using measures provided by Stephen Phew,  below are a few recommendation for the article - <br>

1) Layout can be a little more compact. Since investors may or may not have time to go through entire article, may be an executive summary in the top would help.  <br>
2) There is pie chart representation and bar graph representation of the same underlying data. This can be changed to just one more convenient data visualization <br>
3) Colours can be made colour lind and print friendly. Also, use of a different palette would help<br>
4) Use of 2D graphs instead of 3D


### Step 3: Wireframing a solution

With above changes in mind, I tried to create a draft which was easier to understand and better at aesthetics. I have tried to keep layout to be a little more compact. Since investors may or may not have time to go through entire article, may be an executive summary in the top would help. Hence I have included a summary page with gives a quick view of the market value, profit and sales information for the company in a glance. Executive summary is followed by the original content, updated with the new graphs and pie charts. 
<br>Based on the Effectiveness Profile, to improve on the perceptibility, I have eliminated the 3D graphs. Since the depth attribute is of no particular relevance for this visualization. Also, as mentioned above, I have added an executive summary. Apart from this, I have remove the bar graph displaying the same information as the pie, cause I find a pie representation would be better to show “parts of a whole” concept<br>To improve on the Intuitiveness, as Stephan Phew’s paper specifies,  I have re arranged the bar graphs where axis is from 2015 to 2018 and not otherwise. This helps the reader to understand the trend. In the pie chart, I have converted the pie chart into a doughnut chart. The colour uses a gradient to highlight most important to least important product contributing to the revenue of the company.
<br>To modify aesthetics of the graph, I have added a cover image, which acts as a background to the summary part for the article. All the graphs are in the Apple’s colour palette – Black, Gray , White. 

  
  
![WhatsApp Image 2020-02-02 at 3 09 07 PM](https://user-images.githubusercontent.com/59716372/73617274-e1223280-45ea-11ea-994b-cfc0e045d2f7.jpeg)
![WhatsApp Image 2020-02-02 at 3 09 07 PM (1)](https://user-images.githubusercontent.com/59716372/73617275-e1223280-45ea-11ea-8daa-5eecc7ba8a4f.jpeg)
![WhatsApp Image 2020-02-02 at 3 09 07 PM (2)](https://user-images.githubusercontent.com/59716372/73617273-e1223280-45ea-11ea-99e5-332b1a9f3c50.jpeg)




### Step 4: Testing of the solution 
For testing the effectiveness of new design, I sent this to a colleague of mine. She was also a Business Analyst at a consulting firm, having a similar background as mine. Her feedback was quite informative and useful.
<br>She highlighted the fact that the summary is too verbose, not really eye catchy. The title is attractive but misleading. Detailed view tabs are informative and neatly organized. 
Second, I sent to a university graduate who has a keen eye for detail and economics major! She suggested further changes and had different views about the graphs. <br> 
“This is a really creative visualization. I have just one suggestion, on the right hand side increase in Selling price has a downward arrow...the direction of the arrow for all other points is indicative of the teen. Maybe you could change the heading to decrease in Sales due to increase in costs or something on those lines. The actual market values are not clear in the first graph. I think the article is very detailed and is persuasive to an executive audience”

<br> Both these critiques helped me to fine tune the design for a broader audience. Primary take away was “You are not the user”. It doesn’t matter what kind of chart / diagram you like to make, data visualization will be useful only if it coveys correct details to the user. <br> I changed the title, made it summary part catchy and simplified the graphs. Instead of 5 charts, now I am conveying the same information in three :) <br>
Here was a new version of the wireframe -

![WhatsApp Image 2020-02-02 at 6 56 11 PM](https://user-images.githubusercontent.com/59716372/73617548-ef258280-45ed-11ea-9f2b-2d59348a49bc.jpeg)

### Step 5: Building my own solution

Utlimately, getting all the wireframes into place, I have convert my sketches to a web design. <br>
For all the new bar graphs, I have used Tableu. For the new summary cover, I have used a designing tool called Canva. 

![apple1](https://user-images.githubusercontent.com/59716372/73619089-b25f8880-45f9-11ea-9a9e-d7abe5dc76cf.png)<br>
By most conventional definitions, Apple (NASDAQ: AAPL) is the most successful company in the world. It's worth more than any other publicly traded company, with a market value near $1.1 trillion, and it's the most profitable, bringing in $56 billion in net income in its last four quarters.<br>

Apple is making headlines once again after releasing the latest versions of its flagship smartphone, the iPhone, including the iPhone XS, XS Max, and XR; the stock recently topped the $1 trillion mark and is pushing record highs. As investors consider the stock's potential with those two milestones behind it, now is an excellent time to dig into the numbers, to better understand how Apple's business works and where it's headed today.<br>

#### The iPhone company
Though Apple makes several other popular devices in addition to its trademark smartphone, including the iPad, Mac, Apple Watch, and others, the iPhone continues to drive the majority of its business as it has for the past several years. As you can see from the charts below, the iPhone has contributed about 62% of Apple's revenue over the last four quarters:
![2_small](https://user-images.githubusercontent.com/59716372/73624739-fcebff80-460f-11ea-8150-71f92b78b7fa.png)

<br>Of the company's $255.3 billion in revenue during that time, $158.3 billion has come from the iPhone, which dwarfs revenue in other categories.<br>
It's clear from those two charts, then, that Apple's fortunes will largely be determined by the success of the iPhone. However, there's a key problem with that dependency: The smartphone market has matured, and sales in the category have even begun declining for the first time ever. Consumers are delaying upgrades, as new iterations of phones become more similar to old ones. In the fourth quarter of 2017, global smartphone sales declined by 5.6% to 408 million, and have plateaued at about 1.5 billion for the year.<br>

Apple has not been able to escape this trend -- iPhone sales have been relatively flat for some time:<br>
![barfinal](https://user-images.githubusercontent.com/59716372/73625732-0aa38400-4614-11ea-8ed5-d27a834cca66.png)<br>


As you can see, iPhone unit sales peaked in fiscal 2015 when the company introduced the large-screen iPhone 6, before falling by 8% the following year. Since then, unit sales have recovered modestly, but they may never return to the heights seem in 2015. Apple, aware of this problem, has only one way to keep growing iPhone sales: [to charge more money](https://www.fool.com/investing/2018/09/13/apple-has-quickly-raised-the-entry-price-for-the-i.aspx?&utm_campaign=article&utm_medium=feed&referring_guid=52f68a30-9f6e-43b3-bae1-4f322a1e4247&utm_source=yahoo-host) per phone. <br>

Thanks to the success of the iPhone X, average iPhone selling prices have jumped this year after lagging previously:

![bar2](https://user-images.githubusercontent.com/59716372/73619809-d375a880-45fc-11ea-90b2-831425728b3b.png)<br>

Average iPhone selling prices jumped to $758 thanks to the $1,000 iPhone X. Apple is hoping to pull the same trick once again with its new lineup of iPhones, which top out at $1,100 for the iPhone XS Max with 64 gigabytes or $1,449 with 512 GB. However, the company will only be able to raise iPhone prices for so long, as it will eventually reach a ceiling in demand.<br>

Apple's services segment, made up of offerings like the App Store, Apple Music, and Apple Pay, has been growing quickly; services revenue is up 31% in the most recent quarter. But the growth of that high-margin category has not been enough to make up for rising input costs, as gross margin is down from a recent peak in 2015:<br>

#### Author's Take
Apple now finds itself again at a turning point. It's not enough for the company to rely on growth from Services or its Other Products segment, which includes devices like the Apple Watch, Apple TV, and AirPods, as sales in those categories are still just a fraction of iPhone sales. The company either needs to find another blockbuster product category that can add meaningful growth to an already enormous business, or it needs to find more ways to squeeze money out of a mature iPhone market, likely by raising prices.<br>

It won't be easy, but the early signs for Apple investors are positive. Some of the new iPhone XS model pre-orders are already selling out. However, we won't know much about actual sales for several months -- not until the company reports first-quarter earnings in January.<br>

Still, based on the latest iPhone pricing and the challenges above, Apple's strategy with the new high-priced iPhone is abundantly clear.

<br>
[Take me back to the portfolio](https://shrutikarandikar.github.io/Portfolio/)
