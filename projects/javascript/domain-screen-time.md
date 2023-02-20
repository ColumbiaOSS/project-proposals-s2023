# domain-screen-time

## Description
I will create a Chrone extension titled `domain-screen-time` which acts as an activity log by indicating how long a user spends on each domain site (Github, Amazon, Youtube, Courseworks, etc).

Here's how it should work:
When you start the browser window, from that point 'domain-screen-time' monitors your tabs and domain activity in that window. It logs the duration in 00:00:00 (hours-minutes-seconds format) of each domain you are visiting. When you actively visit a tab, the timer for that domain will keep going, until you switch to another tab with a different domain (at that point the timer will start for that new domain). Ultimately, the user should be able to see which domains they spent the longest time in during the past 24 hours. 

Why it's important:
While iPhone and Macs typically have screentime data, they do not specify details such as the domain the user spent more time in. But this is a unique problem and would benefit students who wish to see how long they spend on educational sites, shopping sites, social media, etc so that they can adjust their patterns upon learning this information to achieve their goals or at the very least,
they can be more aware of how much time they are spending for distractions thanks to the constant logging of 'domain-screen-time'.  

This `domain-screen-time` Chrome Extension has 3 key features:
- Timer: Upon opening a window, start timer as user visits each domain in their window session (how long user spends on each domain based on their current tab). Categorize all subdomains that are part of the same host domain so that they all count towards the corresponding main domain. Keep a "timer" for every domain the user visits.
- Cross-tab monitoring: Once the user closes a particular tab, it is in "inactive" state so stop the timer for that domain until user revists it (meaning they are active on that domain again). Essentially, domain-screen-time should log the time if the user either 1) goes back to that exact tab making it "active" or 2) opens a new tab that shares the same domain
- Aggregation: Aggregate the information for the user every hour such that the page accurately shows time spent on each domain for the past 24 hours. User can analyze this information to understand how their time is being spent across various domains. 

## Domain Logger Repo Link
Repo Link: https://github.com/faizak1/DomainLogger