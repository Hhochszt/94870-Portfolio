[Home](https://hhochszt.github.io/94870-Portfolio) | [About Hillel](AboutHillel.md) | [Portfolio](Portfolio.md)

# Why Jews Live in New York: The Downfall of Rural Judaism

### Outline (and Some Initial Sketches)
The goal of this project is to look at the way American life has changed Judaism to exist primarily in the cities and suburbs.

1.	The problem Statement - Distribution of Jews by state
      1.	Map of synagogues – current climate as a visualization
      ![map of synagogues provided by homeland security](https://dl3.pushbulletusercontent.com/qPHHjQfB8pzXAiXf2XzSL3fVScjCaNN5/Synagogues%20in%20us%20draft.jpg)
      1.	Trend graph (slope or moving scatter) – change in Jewish Schools by state (growing in NY area, dropping almost everywhere else)
      ![Change in school attendance vs change in population density from 1998 to 2013](https://dl3.pushbulletusercontent.com/5HGQw8BDB0diJ51faY1QDPhiJV9sfuJq/20200209_124542.jpg)
      
1.	Political Cause:
      1.	Political Leaning (pie) – from pew
            <svg width="300" height="300" xmlns="http://www.w3.org/2000/svg"><g transform="translate(150, 150)"><g display="none"><path d="M6.4946704217662e-15,-106.06601717798213A106.06601717798213,106.06601717798213,0,1,1,-6.4946704217662e-15,106.06601717798213A106.06601717798213,106.06601717798213,0,1,1,6.4946704217662e-15,-106.06601717798213Z" style="stroke: rgb(255, 255, 255); fill: rgb(255, 0, 0); fill-rule: evenodd;"></path><text transform="translate(3.2473352108831e-15,53.033008588991066)rotate(90)" text-anchor="middle" dx="6" dy=".35em" style="font-size: 11px; font-family: Arial, Helvetica;"></text><title>undefined: none</title></g><g><path d="M9.184850993605149e-15,-150A150,150,0,0,1,145.28747416929465,-37.303483074728234L102.73375820657363,-26.377545844017938A106.06601717798213,106.06601717798213,0,0,0,6.4946704217662e-15,-106.06601717798213Z" style="stroke: rgb(255, 255, 255); fill: rgb(255, 0, 0); fill-rule: evenodd;"></path><text transform="translate(78.47233406460475,-101.1659234861311)rotate(-52.2)" text-anchor="middle" dx="6" dy=".35em" style="font-size: 11px; font-family: Arial, Helvetica;">Conservative</text><title>Conservative: 21</title></g><g><path d="M145.28747416929465,-37.303483074728234A150,150,0,0,1,149.70400926424074,-9.418577929397019L105.85672012155835,-6.659940323010583A106.06601717798213,106.06601717798213,0,0,0,102.73375820657363,-26.377545844017938Z" style="stroke: rgb(255, 255, 255); fill: rgb(148, 191, 105); fill-rule: evenodd;"></path><text transform="translate(126.45670979466361,-20.0287752061101)rotate(-9.000000000000012)" text-anchor="middle" dx="6" dy=".35em" style="font-size: 11px; font-family: Arial, Helvetica;">Do Not Know</text><title>Do Not Know: 3</title></g><g><path d="M149.70400926424074,-9.418577929397019A150,150,0,0,1,-131.44600200657948,72.2630511152574L-92.9463593787129,51.09769347282862A106.06601717798213,106.06601717798213,0,0,0,105.85672012155835,-6.659940323010583Z" style="stroke: rgb(255, 255, 255); fill: rgb(0, 7, 255); fill-rule: evenodd;"></path><text transform="translate(35.72007067577279,122.94928970622992)rotate(73.79999999999998)" text-anchor="middle" dx="6" dy=".35em" style="font-size: 11px; font-family: Arial, Helvetica;">Liberal</text><title>Liberal: 43</title></g><g><path d="M-131.44600200657948,72.2630511152574A150,150,0,0,1,-2.7554552980815446e-14,-150L-1.94840112652986e-14,-106.06601717798213A106.06601717798213,106.06601717798213,0,0,0,-92.9463593787129,51.09769347282862Z" style="stroke: rgb(255, 255, 255); fill: rgb(148, 105, 191); fill-rule: evenodd;"></path><text transform="translate(-110.20339133630152,-65.1741039549194)rotate(390.6)" text-anchor="middle" dx="6" dy=".35em" style="font-size: 11px; font-family: Arial, Helvetica;">Moderate</text><title>Moderate: 33</title></g></g></svg>
      1.	Political Leaning relative to state leaning
      ![map of political demographic, overlayyed with demographic of jews](https://dl3.pushbulletusercontent.com/xP8PqLDOrbbUz5ksEEGgqsuGZqNohfhM/political%20map%20unfiinished.jpg)
      I want to create show a map that compares the jewish political leanings in a given state to the state's overall leanings. Currently this just show's the jewish populations average leaning, but I am going to look for a way to compare this with the states leaning (such as a colored bubble overlapped on the colored state map)
      
      
      
1.	Practical Cause (still need data that shows this well):
      1.	Resources (spiral away from rural areas, will focus on orthodoxy - the most extreme case of required proximity)?
      basically, need kosher food, synagogues and mikvahs which are all expensive, so they pop up where they are best supported, which causes more people to move there, which makes more of them be built)
            1.  Synagogue Distance (see if I can use a synagogue directory or two to calculate)
                  most orthodox jews need to walk to synagogue
            1.  I am still working on other ways to visualize the various reasons why Judaism necesitates closer proximity
      1. diversity
            1.  Some metric to show general homogeneity in rural areas (ex: number of members of the top two local denominations/total number of surveys in that region)
            1.  Some way to show diversity of Judaism is huge (religious practice and other ways)
                  Maybe a web chart of different key elements of the religion (sabbath, kosher, creationism, etc.)
1.    Anti Semitism
      There is a lot of data out there, and this would serve as a great conclusion to the piece, as a sort of take away. However, it is worthy of it's own article (or even a book), so I would like to leave it as a stretch goal for this project.
### Data Sources
Much of my background information, such as knowledge of religous practices, will be based on my personal jewish education. 
I Am using a [Department of Homeland Security dataset]() to show the location of synagogues in the US (this only includes organizations that have filed for a federal security grant, but it is indicative of the entire country's synagogue presence).
Much of my US demographic information will be from the Pew Center for Research's [Religious Landscape Study](https://www.pewforum.org/religious-landscape-study/). This study covers all religions and links results for politics, social status, and other categories to religion. The study includes 847 Jewish participants, from most of the states with large jewish populations. Obviously. I will be using this study primarily for its political-religious connections.
My Information on Jewish Education and population is from The Avi Chai Foundation, which completed their [Census of Jewish Schools](https://avichai.org/knowledge_base/a-census-of-jewish-day-schools-in-the-united-states-2013-14-2014/) in 2013. As well as from various studies out of the [Berman Jewish Databank](https://www.jewishdatabank.org/databank) which is run by the Jewish Federations of North America. This includes a wealth of information on both local and national scales, but since not all of the surveys are standardized, I am still looking to find the data that best supports my Practicality arguement
finally for the diversity argument, I will endeavor to create a measure of religous homogeneity by region using the pew study, and then I want to create a web visualization of the diversity of Jewish denominations, using resources like http://www.jewfaq.org/movement.htm to identify metrics by which to compare the jewish denominations. This will both highlight judaism's need for a more diverse invironment and explain better the different facets of judaism.

### Story Arc
![Story arc for my article](https://dl3.pushbulletusercontent.com/pW0UP9AgVOxotEDvqS32xjZ43BZnXyOE/20200209_142708.jpg)
The goal here is to inform the public about a series of niche topics, so I am measuring my story's novelty as a function of the progression of the story. I beleive that the political section of the article will be the least novel, but the explanation of jewish life, both in terms of resources (the need to live near a synagogue, butcher, "mikvah" etc) and denomination will be very interesting to people who are new to the subject. Finally, I included a dashed line for the reach goal, a short conversation on antisemitism's role. Since antisemitism has been in the news more and more regularly, this wont necessarily be novel, though it will hopefully be a great chance to contradict misinformation and educate people about the real trends.

### Method and Medium
I plan to build my article in Shorthand. It seems like a great way to build a very attractive and inviting narrative. I will likely make many of my graphics in either Tableau or RawGraphs, both because I am bad at drawing, and because I believe they represent more accurately the types of tools I will be using in the future, as an engineer. I would really like to build a full Tableau dashboard, but as of yet, I have not found a series of data for which this would be worth the effort.
