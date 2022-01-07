# Project 1: Extinct Languages

![Extinct Languages Image](https://raw.githubusercontent.com/RubyRondina/Project-1--Extinct-Languages/main/Visuals/intro-1523990289.webp)

**Project Creation Date**: *September 2021*

For those of you who speak more than one language, have you noticed that you think differently in each language? Do you notice that some concepts exist in one language but not in others?  So if we lose a language, what else are we losing with it?

According to [Ethnologue](https://www.ethnologue.com), there are 7,139 languages spoken in the world at the time of this project. But that number is constantly in flux.  As time goes on, new languages are discovered, some languages become endangered or vulnerable, while others become extinct.  

Roughly 40% of languages are now endangered, often with less than 1,000 speakers remaining.

The dataset I am working with comes from [The Guardian](https://www.theguardian.com/news/datablog/2011/apr/15/language-extinct-endangered#data), who in turn, sourced the data from [UNESCO](http://www.unesco.org/languages-atlas/en/atlasmap.html#) in 2017.  They indicate 228 extinct languages on record.

![Babel](https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Babel.jpg?raw=true)

## Dataset
The full detailed dataset can be downloaded [here](https://docs.google.com/spreadsheets/d/1mUYwl5ZUTp2OHDr0hsco89YY5J8Qx2GWzTLFETzVnB4/edit?hl=en&hl=en#gid=1).  
It includes the _names of languages_, _number of speakers_, the _names of countries where the language is still spoken_, and the _degree of endangerment_. 

### Classification
The UNESCO endangerment classification is as follows: 
- **Extinct**: there are no speakers left
- **Critically endangered**: the youngest speakers are grandparents and older, and they speak the language partially and infrequently 
- **Severely endangered**: language is spoken by grandparents and older generations while the parent generation may understand it, they do not speak it to children or among themselves 
- **Definitely endangered**: children no longer learn the language as a 'mother tongue' in the home 
- **Vulnerable**: most children speak the language, but it may be restricted to certain domains (e.g., home)

## Initial Questions and Hypothesis  
- Where are these languages located?  Are they more concentrated in certain regions?
- My initial hypothesis is that most extinct languages were located in former British and Spanish Colonies.

So in order to answer these question, I had to supplement the data by scraping more datasets on countries according to their world regions, sub-regions, official languages and former colonizers. 
<br/>

## Answers and Insights Visualized


![Map](https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Map.png)

As per the map above, there are large clusters of extinct, endangered and vulnerable languages between the tropics of Cancer and Capricorn, along the equator.<br/><br/><br/>




![Chart-Regions](https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Chart-RegionsbyEndangerement.png)

Most of these languages are located in the Americas, followed closely by Asia.<br/><br/><br/>




![Chart-SubRegions](https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Chart-Sub-regions.png) 




Most extinct languages come from North America while most of the endangered and vulnerable languages are in Latin America and the Caribbean.<br/><br/><br/>




![Dashboard-ByColonies](https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Dashboard-ByColonies.png)
The hypothesis that most extinct languages come from former British and Spanish colonies is both correct and incorrect. 

As per the chart above, most extinct languages came from *British and Spanish* colonies respectively but it is *British and French* colonies that produced the most endangered and vulnerable languages. 
<br/>
<br/>


## Additional Questions and Answers

**Question**: Is a language more likely to be wiped out if spoken in only 1 country? 



![Table-CountriesperLang](https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Table-Numberofcountriesperlanguage.png)



**Answer**: As per the chart above, a language is more likely to be extinct if it is only spoken in one country vs. spread out across multiple countries.

Romani is the endangered language spoken in the most number of countries (29), followed by Yiddish which is spoken in 25 countries.

<br/><br/>


**Question**: Is a language more likely to go extinct if the country has more than 1 colonizer?
<br/>


<p align="left"><img width="550" height="" src="https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Table-NumberofColonizers.png"></p>



**Answer**: A language is more likely to go extinct if it is from a country that only had one colonial power that ruled.

A language is more likely to survive if the country it comes from had multiple colonial powers that took hold.  
<br/><br/><br/>


**Question**: Which dominant language is responsible for pushing out the most number of native tongues?

<br/>


![Dashboard-ByCurrentOfficialLanguage](https://github.com/RubyRondina/Project-1--Extinct-Languages/blob/main/Visuals/Dashboard-ByCurrentOfficialLanguage.png)

<br/>


**Answer**: As per the chart above, it is the English language that has pushed out the largest number of native languages.

<br/>


### Data Limitations

In the original dataset, there is a large number of null values in the *number of speakers* column.  It is impossible to obtain all of this information due to the remoteness of some of the speakers of these languages. This is why I could not use this measure in my analysis. I had to rely on the *degrees of endangerment* data for most of my investigation and supplement it by adding the following columns: *Region, Sub-Region, Former Colony of, Official Language (if world's Top 10 Language).*

It's also important to note that UNESCO does not use the number of speakers as a determining  factor on the language's degree of endangerment.  Their measure is which generation currently speaks it (ie, is the lanuage only spoken by grandparents? Are children currently using the language?)

And since this study can be quite extensive, I decided to only study the effects of the top Western European colonies in the modern era (between 1500-1900). So this leaves out, in particular: 

**China**:  As a whole, this country is still technically an empire since it includes many different cultures and ethnicities spread out over a very large area.  

**Russia**:  This country is not included as a former colonizer in my data although their influence still looms in Central Asia in the former Soviet states (eg. Tajikistan, Kyrgyzstan, Uzbekistan etc). They also only started their colonialism in the 1900

**Japan**:  This country only colonized countries for less than 5 years during WWII. 

**USA**:  Not a colonizer in the common sense of the word but they have been an imperial power for quite some time. <br/>
<br/>

### Conclusion

It would be interesting to do a more in-depth study of extinct and endangered languages that take into account the other colonial powers I mentioned above, as well as others, like Belgium, Sweden, Norway, Austria and Austria-Hungary, the Ottoman Empire etc.

That being said, human language is tied to human history, even before the dawn of civilization.  This dataset does not include all the languages that ever existed on Earth since we probably started speaking as early Homo sapiens in the Stone Age before we could keep track of languages.  

It's also important to note that this dataset does not include "dead" languages, like Latin for example. The difference between an extinct language and a dead language is that an extinct language no longer has any speakers, especially if the language has no living descendants. In contrast, a dead language is one that is no longer the native language of any community, even if it is still in use.  Although there are no longer any native speakers, Latin is still in use in medicine, science, law and liturgy etc.

Language also evolves.  There is no doubt that we do not speak the same kind of English they spoke hundreds of years ago.  New words are born as new concepts, inventions and behaviours take hold in society. 
 
But one thing is for sure.  Languages disappear because they are replaced by a more dominant language.  What makes a language more dominant is a subject for another analysis that would be wonderful to dive into... 


**Please also visit my [Tableau Public](https://public.tableau.com/app/profile/ruby.rondina/viz/ExtinctLanguages_16414222503700/Story1) to see interactive dashboards and the full story on this project.**
