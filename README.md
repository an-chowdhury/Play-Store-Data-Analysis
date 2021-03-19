[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<p align="center">

  <h1 align="center">Google Play Store Data Analysis Using Python</h1>

  <p align="center">
    <br />
    <a href="https://github.com/an-chowdhury/Play-Store-Data-Analysis"></a>
    <br />
    <br />
      </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents
<details open="open">
  <summary>Contents</summary>
  <ol>
    <li>
      <a href="#Introduction-to-the-project">Introduction To The Project</a>
      <ul>
        <li><a href="#Summery">Summery</a></li>
        <li><a href="#Project-Objective">Project Objective</a></li>
        <li><a href="#Project-Data-Source">Project Data Source</a></li>
      </ul>
    </li>
    <li>
      <a href="#Analysis-&-Visualization">Analysis & Visualization</a>
      <ul>
        </ul>
    </li>
    <li><a href="#Reference">Reference</a></li>
  </ol>
</details>

## Introduction To The Project

![product-screenshot]

Google Play Store serves as the official app store for certified devices running on the Android operating system, allowing users to browse and download applications developed with the Android software development kit (SDK) and published through Google.The Google Play store has over 100 billion app downloads and reached over 3.5 million apps published in 2017.
### Summery

Using Statistical Analysis on Play store app details and their reviews, actionable insights can be drawn for developers to work on and capture the Android market.

### Project Objective
The goal of this project is to use techniques of statistical analysis to get beneficial insights and the strategy behind app-making businesses to success. i.e we will work on all possible patterns and corelations to find the trends from avaiable app details and their reviews.
### Project Data Source
* **googleplaystore.csv** and **googleplaystore_user_reviews.csv** is collcted from [kaggle Play store dataset by Lavanya Gupta.](https://www.kaggle.com/lava18/google-play-store-apps)  

### Analysis & Visualization
![Figure-1]

**Figure1** shows the rating distribution of all apps in play store. As we can see between 4.5 to 4.0 is the most densed area where lion's share of apps lies. Average of rating of application in store is around 4 which is very high.

![Figure-2]

![Figure-3]

**Figure3** shows through histogram that which age group has most number of COVID-19 cases. As we can see aapeople between 20-40 has contracted the disease most.

![Figure-4]

**Figure4** indicate that state with the darkest color i.e Maharashtra and other southern states has had chunk number of confirmed cases.

![Figure-5]

**Figure5**, we can see that now  Kerala, floowed by maharashtra has most number of active cases.

## Reference

1. https://www.kaggle.com/lava18/google-play-store-apps

[contributors-shield]: https://img.shields.io/github/contributors/an-chowdhury/Play-Store-Data-Analysis?style=for-the-badge
[contributors-url]: https://github.com/an-chowdhury/Play-Store-Data-Analysis/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/an-chowdhury/Play-Store-Data-Analysis?style=for-the-badge
[forks-url]: https://github.com/an-chowdhury/Play-Store-Data-Analysis/network/members
[stars-shield]: https://img.shields.io/github/stars/an-chowdhury/Play-Store-Data-Analysis?style=for-the-badge
[stars-url]: https://github.com/an-chowdhury/Play-Store-Data-Analysis/stargazers
[issues-shield]: https://img.shields.io/github/issues/an-chowdhury/Play-Store-Data-Analysis?style=for-the-badge
[issues-url]: https://github.com/an-chowdhury/Play-Store-Data-Analysis/issues
[license-shield]: https://img.shields.io/github/license/an-chowdhury/Play-Store-Data-Analysis?style=for-the-badge
[license-url]: https://github.com/an-chowdhury/Play-Store-Data-Analysis/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/ankan-chowdhury-00bb3b141/
[product-screenshot]: https://cdn.wccftech.com/wp-content/uploads/2017/09/download-google-play-store-1.png
[Figure-1]: Insights/Overall%20Rating%20Distribution.jpg
[Figure-2]: Insights/Bulky%20or%20Light.jpg
[Figure-3]: Insights/Category-wise%20App%20Demand.png
[Figure-4]: Insights/Number%20of%20downloads%20of%20paid%20apps%20Vs%20free%20apps.jpg
[Figure-5]: Insights/Paid-Rating%20vs%20Size.jpg
