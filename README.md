## Crio Dev community Newspaper

**Crio Dev Newspaper** is a subscription based email service which delivers aggregated and curated news (Tech blogs) to individual users based on his/her preference. 

**User Process**

 1. Go to Subscription link/page and enter required data ( Email ) .
 2. Choose from 5 #categories for preference.
 3. Accept T&C and submit.

**Script**

A Node.js script will used to collect feeds from a list of verified blog sources and store it with appropriate #Categories. This script should use a popularity check for each blog based on parameters like - claps, upvotes, comments etc. 

Another Node.js script needs to be run for with mail-gun client to send an automated mail in regular intervals to subscribed user list with appropriate data. Mail client should use a good looking UI template to highlight the articles. 

**High Level Architecture**

![enter image description here](https://i.imgur.com/15oLusF.png)
