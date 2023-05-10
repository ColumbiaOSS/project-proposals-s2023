# splitinerary 📝🛫

[![](https://img.shields.io/badge/project-link-green)](https://github.com/el3030/splitinerary)
[![Build Status](https://github.com/el3030/splitinerary/workflows/Build%20Status/badge.svg?branch=main)](https://github.com/el3030/splitinerary/actions/workflows/build.yml)
[![](https://img.shields.io/github/license/el3030/splitinerary)](https://opensource.org/license/mit/)
[![PyPI](https://img.shields.io/pypi/v/splitinerary)](https://pypi.org/project/splitinerary/)
[![Documentation Status](https://readthedocs.org/projects/splitinerary/badge/?version=latest)](https://el3030.github.io/splitinerary/)

Collaborative itinerary library in Python

Coordinating a group to go on a trip together is difficult because some people may fly to the same destination from different origins, some people may split off mid-trip to go somewhere else and rejoin, and some people might be staying in different places (with relatives, for example). This python program will allow users to join a specific trip and create a collaborative itinerary.

- Trips are objects that have one or more users associated with it.
- Each trip will have events inside of it like flights, hotels, trains, AirBnBs, concerts, etc. that each user can associate him or herself with.
- Each even has more granular information like flight number for flights, address for hotels and airbnbs, station for trains, etc.  
- Each event can also have a dollar amount so costs are kept track of.

In the end, there is a comprehensive itinerary where every person in the trip can see who is doing what at any given point in time.

If you’ve ever used the app splitwise, it’s like that but for travel instead of money.

