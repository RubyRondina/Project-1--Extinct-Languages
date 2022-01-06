{\rtf1\ansi\ansicpg1252\cocoartf2580
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red255\green255\blue255;\red52\green52\blue52;
\red16\green60\blue192;\red251\green0\blue7;\red45\green101\blue22;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\cssrgb\c100000\c100000\c100000;\cssrgb\c26667\c26667\c26667;
\cssrgb\c6667\c33333\c80000;\cssrgb\c100000\c0\c0;\cssrgb\c21961\c46275\c11373;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{none\}}{\leveltext\leveltemplateid1\'00;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{none\}.}{\leveltext\leveltemplateid101\'01.;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{none\}}{\leveltext\leveltemplateid201\'00;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}}
\margl1440\margr1440\vieww20740\viewh11880\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs22 \cf0 # Project 1: Extinct Languages\
\
\pard\pardeftab720\partightenfactor0
\cf0 \expnd0\expndtw0\kerning0
![Extinct Languages Image](intro-1523990289.webp)\
\
**Project Creation Date**: September 2021\
\
For those of you who speak more than one language, have you noticed that you think differently in each language and that some concepts exist in one language but not the other?  So if we lose a language, what else are we losing with it?\
\
\pard\pardeftab720\partightenfactor0
\cf0 ### Introduction\
\pard\pardeftab720\partightenfactor0
\cf0 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 According to Ethnologue, there are 7,139 languages spoken in the world at the time of this project. But that number is constantly in flux.  As time goes by, new languages are discovered, some languages become endangered or vulnerable, while others become extinct.  \
\cf4 Roughly 40% of languages are now endangered often with less than 1,000 speakers remaining.\cf2 \cb1 \
\cb3 The dataset I am working with comes from [\cf2 The Guardian](https://www.theguardian.com/news/datablog/2011/apr/15/language-extinct-endangered#data)\cf2 , who in turn, sourced the data from [UNESCO](http://www.unesco.org/languages-atlas/en/atlasmap.html#) in 2017.  They indicate 228 extinct languages on record.\
\
\pard\pardeftab720\partightenfactor0
\cf0 \cb1 ![Babel](Babel.jpg)\
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 \
### Dataset\
The full detailed dataset can be downloaded [here](https://docs.google.com/spreadsheets/d/1mUYwl5ZUTp2OHDr0hsco89YY5J8Qx2GWzTLFETzVnB4/edit?hl=en&hl=en#gid=1).  It includes the _names of languages_, _number of speakers_, the _names of countries where the language is still spoken_, and the _degree of endangerment_. \cb1 \
\cb3 ### Classification\
The UNESCO endangerment classification is as follows: \cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls1\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 - **\expnd0\expndtw0\kerning0
Extinct**: there are no speakers left\
- **Critically endangered**: the youngest speakers are grandparents and older, and they speak the language partially and infrequently \cb1 \
- **\cb3 Severely endangered**: language is spoken by grandparents and older generations; \cb1 \uc0\u8232 \cb3 while the parent generation may understand it, they do not speak it to children or among \cb1 \uc0\u8232 \cb3 themselves \cb1 \
- **\cb3 Definitely endangered**: children no longer learn the language as a 'mother tongue' in \cb1 \uc0\u8232 \cb3 the home \cb1 \
- **\cb3 Vulnerable**: most children speak the language, but it may be restricted to certain domains (e.g., home)\cb1 \uc0\u8232 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 \cb3 ### \cf2 Initial Questions and Hypothesis \cf2 \cb1 \uc0\u8232 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls2\ilvl0\cf2 \cb3 - Where are these languages located?  Are they more concentrated in certain regions?\
- My initial hypothesis is that \cf7 most extinct languages were located in former British and Spanish Colonies.\
\ls2\ilvl0\cf2 So in order to answer these question, I had to supplement the data by scraping more datasets on countries according to their world regions, sub-regions, official languages and former colonizers. \cb1 \uc0\u8232 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 ### Answers and Insights Visualized\
\pard\pardeftab720\partightenfactor0
\cf0 ![Map](Map.png)\
\
As per the map above, there are large clusters of extinct, endangered and vulnerable languages between the tropics of Cancer and Capricorn, along the equator.\
\
![Chart-Regions](Chart-RegionsbyEndangerement.png)\
\
Most of these languages are located in the Americas\
\
![Chart-SubRegions](Chart-Critically.png)\cf2 \
\cf0 ![Chart-SubRegions](Chart-Severely.png)\
![Chart-SubRegions](Chart-Definitely.png)\cf2 \
\cf0 ![Chart-SubRegions](Chart-Vulnerable.png)\cf2 \
\
\pard\pardeftab720\sa240\partightenfactor0
\cf2 Most of the extinct languages come from North America while most endangered and vulnerable languages are in Latin America and the Caribbean.\
\
![Table-CountriesperLang)(Table-Numberofcountriesperlanguage.png)\
From the chart above, a language is more likely to be extinct if it is only spoken in one country vs. spread out in different countries.\
Romani is the endangered language spoken in the most number of countries (29), followed by Yiddish which is spoken in 25 countries.\
\
![Table-NumberofColonizers](Table-NumberofColonizers.png)  \
A language is more likely to go extinct if it is from a country that only had one colonial power that ruled them.\
A language is more likely to survive if the country it comes from had multiple colonial powers that took hold.  \
\
![Dashboard-ByColonies](Dashboard-ByColonies.png)\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls3\ilvl0\cf2 \cb3 The hypothesis at the beginning of this research was that most extinct languages took place in former British and Spanish Colonies. That is both correct and incorrect. As per the chart above, most of the extinct languages came from British and Spanish colonies respectively but it is British and French colonies that produced the most endangered and vulnerable languages. \cb1 \uc0\u8232 \
\pard\pardeftab720\sa240\partightenfactor0
\cf2 ![Dashboard-ByCurrentOfficialLanguage](Dashboard-ByCurrentOfficialLanguage.png)\cb3 \
\cb1 Lastly, as per the chart above, it is the\expnd0\expndtw0\kerning0
\outl0\strokewidth0  English language that has pushed out the largest number of native languages.\
\
### Data Limitations\

\f1\fs24 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \uc0\u8232 
\f0\fs22 \cb3 There is a large number of null values in the \'93number of speakers\'94 column in the original dataset, and it\'92s impossible to obtain some of this information due to the remoteness of some of the speakers of said language. This is why I could not use this measure in my analysis. I had to rely on the \'93degrees of endangerment\'94 data for most of my investigation and supplement it by adding the following columns: \'93Region,\'94 \'93Sub-Region,\'94 \'93Former Colony of,\'94 \'93Official Language (if world's Top 10 Language).\'94 \
\cb1 \uc0\u8232 \cb3 And since this study can be quite extensive, I decided to only study the effects of the top Western European colonies in the modern era (between 1500-1900). So this leaves out, in particular: \
\cb1 \uc0\u8232 \cb3 **China** \cb1 \uc0\u8232 \cb3 As a whole, this country is still technically an empire since it includes many different cultures and ethnicities spread out over a very large area. \
\cb1 \uc0\u8232 \cb3 **Russia** \cb1 \uc0\u8232 \cb3 This country is not included as a former colonizer in my data although their influence still looms in Central Asia in the former Soviet states (eg. Tajikistan, Kyrgyzstan, Uzbekistan etc). They also only started their colonialism in the 1900\'92s. \cb1 \uc0\u8232 \cb3 \
**Japan** \cb1 \uc0\u8232 \cb3 This country only colonised countries for less than 5 years during WWII. \cb1 \uc0\u8232 \cb3 \
**USA** \cb1 \uc0\u8232 \cb3 Not a colonizer in the common sense of the word but they have been an imperial power for quite some time. 
\f1\fs24 \cb1 \uc0\u8232 \

\f0\fs22 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 Please also visit my [**Tableau Public**](https://public.tableau.com/app/profile/ruby.rondina/viz/ExtinctLanguages_16414222503700/Story1) to see interactive dashboards and the full story on this project.\
\
\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \
}# Project-1--Extinct-Languages
