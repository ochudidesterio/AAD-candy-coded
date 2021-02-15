## Table of Contents

  - [Android Candy Store App](#android-candy-store-app)
  - [Prerequisites](#prerequisites)
  - [Project Flow](#project-flow)
    - [Detail Intent](#detail-intent)
    - [InfoIntent](#inforintent)
    - [Map Intent](#map-intent)
    - [Phone Intent](#phone-intent)
    - [Share Intent](#share-intent)
    
    <br>
    :point_down: :point_down: :point_down: :point_down: :point_down:
    
    
<br>

   <img align="center" src="https://forthebadge.com/images/badges/built-for-android.svg" alt="droidconKE2020 built for Android">


[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ochudidesterio/AAD-candy-coded)


# Android Candy Store App

This app leverages the use of google map and sharing information via email intents. It displays the candies in a recyclerview and each recycler view is attached to a 
listener whereby when clicked, it launches an activity to diplay the candy image and its discription. It has a hard coded location intent and phone call intent.

# Prerequisites

- Android studio and emulator running on API level 29

- Knowlegde of Android implicit and explicit intents


## Project Flow


### Detail Intent


It contains the recycler list of the candies in the store and its description


![DetailIntent](https://github.com/ochudidesterio/AAD-candy-coded/blob/master/images/DetailIntent.png?raw=true)



### InfoIntent


This intent shows the information about location, phone number and time


![InforIntent](https://github.com/ochudidesterio/AAD-candy-coded/blob/master/images/InfoIntent.png?raw=true)


### Map Intent


This is an intent showing a hard coded google map location and its launched on clicking the location item on the menu


![map Intent](https://github.com/ochudidesterio/AAD-candy-coded/blob/master/images/MapIntent.png?raw=true)



### Phone Intent


This is an intent showing the phone dial pad and its launched on clicking the phone number on the menu


![Phone](https://github.com/ochudidesterio/AAD-candy-coded/blob/master/images/PhoneIntent.png?raw=true)


### Share Intent


This intent allows the sharing of candy images and its description  by invoking the built in email applications like gmail.


![Share Intent](https://github.com/ochudidesterio/AAD-candy-coded/blob/master/images/ShareIntent.png?raw=true)



