# Web Development Project 6 - *Evently*

Submitted by: **Atuh Fon**

This web app: **Evently is a sleek, user-friendly web app that helps you discover and keep track of exciting events happening around you. Powered by the Ticketmaster API, Evently allows users to:**

- Search for concerts, sports games, festivals, and more  
- Filter events by city, date, or category  
- Save and revisit your favorite events  
- Get quick insights with clean visuals and a responsive interface  

Time spent: **8** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **Clicking on an item in the list view displays more details about it**
  - Clicking on an item in the dashboard list navigates to a detail view for that item
  - Detail view includes extra information about the item not included in the dashboard view
  - The same sidebar is displayed in detail view as in dashboard view
  - *To ensure an accurate grade, your sidebar **must** be viewable when showing the details view in your recording.*
- [x] **Each detail view of an item has a direct, unique URL link to that item’s detail view page**
  -  *To ensure an accurate grade, the URL/address bar of your web browser **must** be viewable in your recording.*
- [x] **The app includes at least two unique charts developed using the fetched data that tell an interesting story**
  - At least two charts should be incorporated into the dashboard view of the site
  - Each chart should describe a different aspect of the dataset


The following **optional** features are implemented:

- [x] The site’s customized dashboard contains more content that explains what is interesting about the data 
  - e.g., an additional description, graph annotation, suggestion for which filters to use, or an additional page that explains more about the data
- [x] The site allows users to toggle between different data visualizations
  - User should be able to use some mechanism to toggle between displaying and hiding visualizations 

  
The following **additional** features are implemented:

* [x] **Interactive Charts** - Added dynamic data visualizations using Chart.js
* [x] **Responsive Design** - Fully mobile-friendly layout with adaptive components
* [x] **Advanced Filtering** - Combined search and category filters with debouncing
* [x] **Loading States** - Skeleton loaders and spinners for better UX

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='Evently.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with:
- [EzGIF](https://ezgif.com/) for Windows

## Challenges

## Development Challenges

- 1. **CORS Restrictions:** Direct API calls to Ticketmaster were blocked by CORS policy  
- 2. **Data Formatting:** Inconsistent API response structures  
- 3. **Responsive Charts:** Charts breaking on mobile views  
- 4. **State Management:** Complex state interactions between filters  
- 5. **Performance Optimization:** Slow rendering with large event lists  

## License

    Copyright [2026] [Atuh Fon]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
