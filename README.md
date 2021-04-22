# Budget-Tracker
Allows a user to track their withdrawals and deposits with or without a data/internet connection.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Features

* In order to cache dynamic content, i.e. users' inputs for withdrawals or deposits, `indexedDB` was used.