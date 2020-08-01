## INTRODUCTION
Although the concern of air pollution is the emerging requirement, not much effort has done to gather air pollution with smallergranularity and high density. It is difficult for researchers to access a good source of air pollution data, except for some public websites and apps aimed at serving ordinary citizens such as AirVisual [1] and EnviSoft [2]. With the efforts of creating a scientific dataset forresearching. 
HCM-OpenData - A project collect AQI data in Ho Chi Minh City for research purpose. 
The campaign was conducted from July 20, 2020.
List of staion:

| name                                          | id                       | type    | url                                                                     | coordinates/latitude | coordinates/longitude | 
|-----------------------------------------------|--------------------------|---------|-------------------------------------------------------------------------|----------------------|-----------------------| 
| US Consulate in Ho Chi Minh City              | 56d41d3631da061e3de893a1 | station | /vietnam/ho-chi-minh-city/us-consulate-in-ho-chi-minh-city              | 10.782783            | 106.700035            | 
| Vo Thi Sau High School                        | c603867c6ca88bce24c8     | station | /vietnam/ho-chi-minh-city/vo-thi-sau-high-school                        | 10.79765507          | 106.6960189           | 
| Long Phuoc, District 9                     | E9uSpxgAETGoxTGhG        | station | /vietnam/ho-chi-minh-city/long-phuoc-district-9                            | 10.81210352          | 106.866467            | 
| VSTARSCHOOL                                   | b27657e3b7350db392db     | station | /vietnam/ho-chi-minh-city/vstarschool                                   | 10.743098            | 106.697934            | 
| Mam non Hai Au Bay                            | 7e30ef038ec047850652     | station | /vietnam/ho-chi-minh-city/mam-non-hai-au-bay                            | 10.794837            | 106.673877            | 
| Lycee Francais International Marguerite Duras | L7pAHfvvN7ePYtGT4        | station | /vietnam/ho-chi-minh-city/lycee-francais-international-marguerite-duras | 10.870602            | 106.824335            | 
| RMIT University                               | b292dea60ad90213ec05     | station | /vietnam/ho-chi-minh-city/rmit-university                               | 10.72955917          | 106.6945839           | 
| Saigon South International School             | 079def07c570801022a2     | station | /vietnam/ho-chi-minh-city/saigon-south-international-school             | 10.721702            | 106.709001            | 
| The Park Residence                            | e53b1ef9c598b1b73911     | station | /vietnam/ho-chi-minh-city/the-park-residence                            | 10.712713            | 106.707257            | 
| Thao Dien                                     | ajEovKAtQbFh4cMNk        | station | /vietnam/ho-chi-minh-city/thao-dien                                     | 10.805454            | 106.74814             | 
| Diamond Island - T4                           | 27f24326324ba3e5e268     | station | /vietnam/ho-chi-minh-city/diamond-island-t4                             | 10.7791155           | 106.7473307           | 
| THCS Thanh My Loi                             | 6c1423fd846453ffa9b9     | station | /vietnam/ho-chi-minh-city/thcs-thanh-my-loi                             | 10.77501437          | 106.7704541           | 
| FPT Software HCM                              | 88756136561e95526a3d     | station | /vietnam/ho-chi-minh-city/fpt-software-hcm                              | 10.85098936          | 106.798085            | 
| Ap Xuan Thoi Dong 2                           | 6493ed15171b3a76a4dd     | station | /vietnam/ho-chi-minh-city/ap-xuan-thoi-dong-2                           | 10.87002752          | 106.5904112           | 
| Vinhomes Central Park                         | 2Zvb7MEEdF4ixY33W        | station | /vietnam/ho-chi-minh-city/vinhomes-central-park                         | 10.79262137          | 106.7217325           | 
| SimCity Premier District 9                    | 3376727d44abe8505ff0     | station | /vietnam/ho-chi-minh-city/simcity-premier-district-9                    | 10.821354            | 106.81799             | 
| Truong THCS Thanh Da                          | 686ccb0cf2a1377d541e     | station | /vietnam/ho-chi-minh-city/truong-thcs-thanh-da                          | 10.81356068          | 106.7202117           | 


 #### You can download simple data in this repo, or you can contact me for buy this tool to collect airvisual data  anywhere.
 
 ### airvisual-crawler
 * Clone my source, install on your server, config your location you want to crawler data via API obtain on iqair.com
 * To run silently:
      1. Install PM2: https://pm2.keymetrics.io/docs/usage/pm2-doc-single-page/
      2. Run source:
 ![alt text](https://github.com/HCM-OpenData/airvisual-data-collection/blob/master/image/Screen%20Shot%202020-08-01%20at%2019.17.37.png?raw=true)
 
  * How it work:
The airvisual-crawler will crawl data via API and stored on your server as csv format.
 ![alt text](https://github.com/HCM-OpenData/airvisual-data-collection/blob/master/image/Screen%20Shot%202020-08-01%20at%2021.15.19.png?raw=true)

You can give me a coffee cup, it's can help me retain server auto collect data.
<p>
  <a href="https://www.buymeacoffee.com/qZHglXx" rel="nofollow"> 
    <img src="https://camo.githubusercontent.com/c1dad50ef8c7b0ce138c2ec7c5eff881fed84682/68747470733a2f2f692e696d6775722e636f6d2f58454b3259345a2e706e67" alt="alt text" data-canonical-src="https://i.imgur.com/XEK2Y4Z.png" style="max-width:100%;">
  </a>
</p>

 ## REFERENCES
 1. https://www.iqair.com/
 2. http://cem.gov.vn/
 
