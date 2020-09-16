**Project Ronin Android Take Home Assignment**

We are thrilled that you've chosen to interview at Project Ronin. We're excited to get to know you, and your coding style.

You will have one week to complete this project and submit it. Please do not spend more than ~5 hours in total. Make sure to review the details on how to submit your project, and what to include in the app. We want to see how you work in a relaxed setting and hope that this will help you to show us your best work.

**Summary**

We will work with data sourced from the NASA API ([https://api.nasa.gov](https://api.nasa.gov/)) to show photos taken by the Mars Rovers: Curiosity, Opportunity, and Spirit. The dataset we've compiled has real photos, but the notes and dates have been altered for the purpose of this project.

**Problem Statement:**

Build an app that shows a list of photos from the JSON endpoint provided.

Each item in the list should have a photo and name of the rover. You may include other pieces of information, but be careful not to make the UI confusing.

Be sure to properly handle any errors from the endpoint, and cache photos as necessary (you are welcome to use existing open-source options). The endpoint will always return the same data (we are providing one endpoint for clean data, and one for missing data).

Reload the data every time the app launches. If the network is not available, or if data is missing in the endpoint, just show an empty screen or a screen with an error message.

**Data/Endpoints**

You will be using this endpoint for the full list of photos:

[mars.json](./mars.json)

This endpoint can be used for error testing, and has missing data:

[mars-missing.json](./mars-missing.json)

Each photo item includes:

- **id:** a unique id identifying the photo
- **earth\_date:** the earth date that this photo was taken
- **notes:** any notes on the photo
- **img\_src:** the full-size image url
- **rover:** name of the rover that captured this photo
- **camera\_type:** type of camera used (FHAZ, NAVCAM, PANCAM, RHAZ, MAHLI, CHEMCAM)

**UI:**

We are expecting to see a list of photos and the corresponding rover name alongside the photo. You can show this as any type of view collection that you wish. You may include other information in each item, but it is not required.

Please sort the photos either by rover name, earth date, or camera type.

Please do **not** extend the UI beyond this.

Here's a sample app of how this _may_ look:

![Sample App Gif](./MarsCam.gif)


**Language/Code:**

Use either Kotlin or Java for this project. We have a 100% Kotlin app at Project Ronin, but please choose the language you are most comfortable with for this project. You will not be judged on the language you choose.

**Testing:**

Your code should be testable and modular and this will be an important part of the evaluation. While we don't expect 100% code coverage, please make sure you include at least 2 unit tests and 2 integration tests, providing reasonable, non-trivial test coverage.

**Important notes:**

- Feel free to use Google / Stack Overflow / Past projects as necessary. This should feel like your everyday work environment. However, please do not copy entire sections of code from other projects. If you do copy code, please note in your README.
- Please make sure to not use **any** code that belongs to your employer.
- Work on this app as if you were in a real work setting, and the code you are working on will be pushed to production.
- Be careful not to make extra calls on every phone rotation.
- Don't spend too much time on customizing the UI - the out of the box UI elements in Android are fine to use. Don't extend the app beyond the scope of this project.

**What to Submit:**

1. Project Code
2. README

Share a zipped git repository or zip your project and email us the compressed file. Please do not make your project a public git repository.

Once you zip your project, confirm that you are able to unzip it and run the project before you send it over to us in email.

Your README should include details on your focus areas, libraries used, and how we should test your project. Specifically:

- How long did you spend on this project? We want to make sure that we understand your experience level, and review the project accordingly.
- Libraries used
- What should we focus on while reviewing your project? e.g. UI

This is the time to point out your strengths so that we can evaluate you on those.

- Are there any pieces of code that you've reused from past projects?
- Which device should we run this app on? What version of Android Studio did you use?
- Is there anything else we should know about your project?
