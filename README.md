<p align="center">
  <a href="https://paypal.me/hieund9418"><img src="https://img.shields.io/badge/Donate-PayPal-dc3d53.svg"/></a>
  <a href="https://github.com/mnrteam219"><img src="https://avatars2.githubusercontent.com/u/68223577?s=50&u=29d45055839e54ac97ffe2bf2d3915ff0bf4c0e6&"></a>
    <a href="https://www.buymeacoffee.com/qZHglXx" rel="nofollow"> 
    <img src="https://camo.githubusercontent.com/c1dad50ef8c7b0ce138c2ec7c5eff881fed84682/68747470733a2f2f692e696d6775722e636f6d2f58454b3259345a2e706e67" alt="alt text" data-canonical-src="https://i.imgur.com/XEK2Y4Z.png" style="max-width:100%;">
  </a>
</p>

<p align="center">Your donation help us remain server active</p>
## INTRODUCTION

Ho-Chi-Minh city, located in the South of Vietnam, is the mostpopulous and developed city the country. Due to fast economicdevelopment, the city is facing various environmental problems,especially air pollution. 

Although the concern of air pollution is the emerging requirement, not much effort has done to gather air pollution with smallergranularity and high density. It is difficult for researchers to access a good source of air pollution data, except for some public websites and apps aimed at serving ordinary citizens such as AirVisual [1] and EnviSoft [2]. With the efforts of creating a scientific dataset forresearching.  We create HCM-OpenData - a project collect AQI data in Ho Chi Minh City for research purpose. 

The campaign was conducted from July 20, 2020.
### List of station:

| name                                          | url                                                                     | coordinates/latitude | coordinates/longitude | 
|-----------------------------------------------|-------------------------------------------------------------------------|----------------------|-----------------------| 
| US Consulate in Ho Chi Minh City              | /vietnam/ho-chi-minh-city/us-consulate-in-ho-chi-minh-city              | 10.782783            | 106.700035            | 
| Vo Thi Sau High School                        | /vietnam/ho-chi-minh-city/vo-thi-sau-high-school                        | 10.79765507          | 106.6960189           | 
| "Long Phuoc, District 9"                      | /vietnam/ho-chi-minh-city/long-phuoc-district-9                         | 10.81210352          | 106.866467            | 
| VSTARSCHOOL                                   | /vietnam/ho-chi-minh-city/vstarschool                                   | 10.743098            | 106.697934            | 
| Mam non Hai Au Bay                            | /vietnam/ho-chi-minh-city/mam-non-hai-au-bay                            | 10.794837            | 106.673877            | 
| Lycee Francais International Marguerite Duras | /vietnam/ho-chi-minh-city/lycee-francais-international-marguerite-duras | 10.870602            | 106.824335            | 
| RMIT University                               | /vietnam/ho-chi-minh-city/rmit-university                               | 10.72955917          | 106.6945839           | 
| Saigon South International School             | /vietnam/ho-chi-minh-city/saigon-south-international-school             | 10.721702            | 106.709001            | 
| The Park Residence                            | /vietnam/ho-chi-minh-city/the-park-residence                            | 10.712713            | 106.707257            | 
| Thao Dien                                     | /vietnam/ho-chi-minh-city/thao-dien                                     | 10.805454            | 106.74814             | 
| Diamond Island - T4                           | /vietnam/ho-chi-minh-city/diamond-island-t4                             | 10.7791155           | 106.7473307           | 
| THCS Thanh My Loi                             | /vietnam/ho-chi-minh-city/thcs-thanh-my-loi                             | 10.77501437          | 106.7704541           | 
| FPT Software HCM                              | /vietnam/ho-chi-minh-city/fpt-software-hcm                              | 10.85098936          | 106.798085            | 
| Ap Xuan Thoi Dong 2                           | /vietnam/ho-chi-minh-city/ap-xuan-thoi-dong-2                           | 10.87002752          | 106.5904112           | 
| Vinhomes Central Park                         | /vietnam/ho-chi-minh-city/vinhomes-central-park                         | 10.79262137          | 106.7217325           | 
| SimCity Premier District 9                    | /vietnam/ho-chi-minh-city/simcity-premier-district-9                    | 10.821354            | 106.81799             | 
| Truong THCS Thanh Da                          | /vietnam/ho-chi-minh-city/truong-thcs-thanh-da                          | 10.81356068          | 106.7202117           | 



 #### You can download simple data in this repo, or you can contact me for buy this tool to collect airvisual data  anywhere.
 
 ### airvisual-crawler
 * Clone my source, install on your server, config your location you want to crawler data via API obtain on iqair.com
 * To run silently:
      1. Install PM2: https://pm2.keymetrics.io/docs/usage/pm2-doc-single-page/
      2. Run source:
 ![alt text](https://github.com/HCM-OpenData/airvisual-data-collection/blob/master/image/Screen%20Shot%202020-08-01%20at%2019.17.37.png?raw=true)
 
  * How it works:
The airvisual-crawler will crawl data via API and stored on your server as csv format.
 ![alt text](https://github.com/HCM-OpenData/airvisual-data-collection/blob/master/image/Screen%20Shot%202020-08-01%20at%2021.15.19.png?raw=true)

Format details:
| Time                     | Location            | AQI | 
|--------------------------|---------------------|-----| 
| 2020-07-20T08:30:51.922Z | Ap Xuan Thoi Dong 2 | 62  | 
| 2020-07-20T08:40:52.251Z | Ap Xuan Thoi Dong 2 | 62  | 
| 2020-07-20T10:00:51.786Z | Ap Xuan Thoi Dong 2 | 62  | 
| 2020-07-20T10:10:51.884Z | Ap Xuan Thoi Dong 2 | 100 | 

About "Time" column you must convert to your locale timezone:
```sh
var a = new Date("2020-07-20T08:30:51.922Z");
a.toLocaleString()
>> "7/20/2020, 3:30:51 PM"
```

It's can help me retain server auto collect data.

 ## REFERENCES
 1. https://www.iqair.com/
 2. http://cem.gov.vn/
 
