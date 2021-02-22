## Asian-American COVID-19 Related Discrimination 

For this assignment, we were tasked to take an existing data visualization from the wild and redesign it based on our own critiques of it. The visualization I chose to critique and redesign is this one:

![Types of Discrimination](https://i.imgur.com/nB6VsDw.png)

This visualization was taken from a [bigger report](https://secureservercdn.net/104.238.69.231/a1w.90d.myftpupload.com/wp-content/uploads/2020/10/Stop_AAPI_Hate_CA_Report_200630.pdf) provided by the [Stop AAPI Hate](https://stopaapihate.org/) organization. This organization was put together in the face of the rising rate of hate crimes and discrimination against Asian-Americans in the United States amidst COVID-19. As can be seen in the visualization above, this graph shows the amount of discrimination by type in California and America as a whole over the past "thirteen weeks", according to the report. This report [is listed](https://stopaapihate.org/reportsreleases/) as being published on June 30, 2020, so the data for this visualization spans from late March to late June 2020.  

I chose this visualization for a few reasons. First, this topic is personally relevant to me. I am Asian-American, and further, I have family in California who have shared with me that they have faced discrimination since the start of COVID-19. Recently, my uncle in California told me about how his parents&mdash;my grandparents&mdash;were afraid to go out because of a rash of physical assaults and mugging incidents towards elderly Asian-Americans in their area. My grandpa has never been afraid to go out before&mdash;in fact, he always said how grateful he was to start a new life in America after immigrating here&mdash;so to hear him say something like this both broke my heart and got me interested in just how severe the uptick in crimes against Asian-Americans was. I was happy to find that this data was being recorded and visualized! 

## Critique and Wireframing 

For the purposes of this assignment, we first critiqued our chosen visualization using Stephen Few's (Data Visualization Effectiveness Profile)[http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf]. My main takeaways using this critique were the following: 

* The graph was generally effective at showing the comparison of discrimation between US and California 
* The graph was effective at displaying the most prevalent and least prevalent discriminiations in order, with the most prevalent being at the top and the least being at the bottom. 
* The choice to use orange for the US incidents drew the eye too much, especially considering the intended audience is probably more interested in California's incidents 
* The title for the graph can be misleading, because it does not specify that these are only reported incidents to the Stop AAPI hate organization (versus a gross estimate) 

Generally, I thought that the graph did well at displaying the overall number of discrimination incidents as well as comparing between the US and California, but there were still some areas for improvement: highlighting California's incidents over the US, for example, and clarifying what the data represents in the title. 

But were these the only changes that could be made to this visualization? This visualization was a bar chart, and it was effective at comparing two types of data, US and California, but I wondered if a dot plot would be more appropriate to focus exclusively on Californian incidents. I tried reflecting this in a few sketches of a new graph: 

![Wireframes 1]( )

It was immediately evident to me that a dot plot might not be a good idea; a lot of the data was clustered below 10%, and there were at 4 data points for California that were approximately 5% or below. Even when I tried to increase the scale, the dots seemed to be close enough that they would be overlapping between two types of discrimination, which in turn might give the impression that two very different types of discrimination might be grouped together because they look like they are associated with a single dot.

After thinking about it for a bit, I thought I might go back to the bar graph model, but completely eliminate the US data and just focus on California's. I hoped that this would fix the scaling issue while maintaining the focus on California. 

![Wireframe 2]( ) 

## User Feedback 

I actually have a few Asian-American friends in California, so I sent over my wireframes for their opinions on it (including the dot plots). I asked them what they thought the graphs represented, anything they found confusing, and if there was anything they would change. 

Overall, my two friends responded more positively to the bar charts because they felt that the bottom-clustered data points were too hard to parse. However, they did say that the fact that the verbal abuse dot on the dot plot was so high compared to the others was very impactful, and they could tell right away that verbal abuse was by far the most common and prevalent. While the bar chart had a similar effect, both felt that the dot plot showed this difference more dramatically. 

From the first bar graph, which kept the comparison between US and California, both of my friends said it was pretty clear that these were reported COVID-19 related discriminations, since in the title. However, both of them were slightly confused about other things. One friend wasn't sure what the discrimination was for at first. He asked me, "Oh wait, is this about the stuff that's happening to Asians in California right now?" I clarified that this was actually on data older than recent events, but this still showed that the racial group that this visualization focused on should be clear. I took it for granted because I had the context from the Stop AAPI Hate organization and its report. 

My other friend was actually confused on what "CA" meant from the key. She actually thought that it meant "Canada" because the other label said "US"; she thought this was a comparison between countries, not a country and a state. Again, I didn't notice this because I already knew from context that this was from a report specifically on California. I knew I had to clarify that in the final design. 

Overall, both of my friends felt the bar graphs displayed the less prevalent discimination types better than the dot graphs. I asked them if they felt that it was important that these smaller items were shown individually like in the bar graph. The emphasis on the dot plot on the verbal abuse was striking, after all&mdash;more than the bar chart, according to both of them. 

One of my friends said that she felt seeing the individual smaller items was still important: "They're not as common, but they're still happening". My friend said that while it was clear verbal abuse was the most prevalent form of discrimination, clustering all the smaller ones at the bottom seemed almost dismissive; it felt as if some of these incidents were disappearing from focus, even though all these discriminatory experiences should be acknowledged. She added that she didn't even know there were people being barred from establishments or transportation, for example, and she felt like she saw those instances more clearly in the bar graphs than she did in the dot plot. 

I thought that was incredibly telling, and that after this conversation, perhaps the dot plot wasn't the best choice after all for more reasons than I had thought. I thought too much about the dramatic differences between verbal abuse and the other types of discrimination, while my friend considered the smaller types individually and learned something from them. For her, having these smaller types appearing clearly meant more to her, as she felt that all these experiences should be acknowledged with equal prevalence. So, with that, I already knew I would probably be settling on the bar chart. 

But what did my friends think about the bar chart with the US on it versus the one without? This was actually split between the two of them; one of my friends thought that having the context 

## Final Design 

<div class="flourish-embed flourish-chart" data-src="visualisation/5360600"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<hr>

[Return Home](https://ascho18.github.io/cho-portfolio/) 
