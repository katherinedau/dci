---
layout: post
title:  "Data Input - Pagemaster"
image:
date:   2019-03-04 17:00
categories:
---
My last post dealt with the [struggles of collecting data]() for my web map. As it turns out that process was not nearly as simple as I had anticipated. Now, I have turned to actually putting that data into my map, a process that has become rather difficult as well.

After finally locating coordinates for each site of patronage for Guadalupe, I was ready to upload them to [The Atlantic Current]( http://dauk19.wludci.info/atlanticcurrent/). The data that I had collected (location title, latitude, longitude, category, and description) all goes into the YAML header of a post. For Flaneur, this also includes author, running title, and date. I don’t like the “date” function as it is not particularly relevant to my project. The vast majority of my map points do not have dates associated with them. To organize the data by date would be unhelpful and even confusing. However, this “date” issue is a problem for later in the term. Today I want to discuss getting all of this data that I have collected on to my map.

Mackenzie Brooks found a great tool called [Pagemaster]( https://github.com/minicomp/pagemaster). It’s a Jekyll plug-in which takes csv data and creates markdown pages. She tested it out on her computer, and with a little fidgeting, she successfully generated new pages with unique metadata in the headers. When we tried it on my computer, however, we were not so successful.

My PC did not want to run anything related to Pagemaster. We installed MSYS2 to help the plug-in along. Once we finally got Pagemaster installed and sort-of running, we tried to actually create pages from my Guadalupe sample file. This was sample file was a pared-down dataset for the purposes of the test. I saved it in CSV UTF-8 The first tries were all unsuccessful. We took accented letters out of titles and then spaces out. None of these solutions seemed to work. One tool I found very helpful in this process was [CSV Lint]( https://csvlint.io/). It helps find the problems in your csv file before actually going through the steps of converting it. As an aside, this was actually my first time working with a csv file. Finally, we tried re-saving the data. Oddly enough, this was the solution. I successfully generated four posts with YAML headers of the data in the sample set.

The next task will be to iron out the kinks in this process so that all of the metadata I need will be included. I have already collected all of the information that I need for the Guadalupe patronages, so I will try to get Pagemaster to work through all of the data. Because there are so many Remedios sites, I may generate the pages before locating the shrines and add in coordinates afterwards. This way, my site will have more information on it sooner. I hope that this may also be a more organize process.

Many aspects of this project have taken longer than expected due to my PC. I do have a high-quality HP laptop, but tools like Pagemaster just aren’t built for the windows operating system. I hope that I don’t run into any more major problems as it is slowing my project down.
