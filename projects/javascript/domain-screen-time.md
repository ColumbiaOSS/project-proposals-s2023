# domain-screen-time

## Description
I will create a Chrone extension titled `domain-screen-time` which acts as an activity log by indicating how long a user spends on each domain site (Github, Amazon, Youtube, Courseworks, etc).

Here's how it should work:
When you start the browser window, from that point 'domain-screen-time' looks at all of your tabs, and the user should be able to see under which tabs they had the domain open the longest in the past 24 hours. While iPhone and Macs typically have screentime data, they do not specify details such as the domain the user spent more time in. But this is a unique problem and would benefit students who wish to see how long they spend on educational sites, shopping sites, social media, etc so that they can adjust their patterns upon learning this information to achieve their goals or at the very least,
they can be more aware of how much time they are spending for distractions thanks to the constant logging of 'domain-screen-time'.  

This `domain-screen-time` Chrome Extension has 3 key features:

- Timer: Upon opening a window, start monitoring to know how long user spend on each domain based on their current tab 
(categorize all subdomains to all count towards the corresponding main domain and start timer once the site loads). Keep a "timer" for every domain user visits.
- Cross-tab monitoring: Once the user closes a particular tab, stop the timer for that domain until user revists that domain. Essentially, log the time if the user either 1) goes back to that exact tab or 2) opens a new tab that shares the same domain
- Aggregation: Aggregate the information for the user every hour such that the page accurately shows time spent on each domain for the past 24 hours. User can analyze this information to understand how their time is being spent across various domains. 

