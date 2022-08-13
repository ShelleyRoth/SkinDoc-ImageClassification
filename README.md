# SkinDoc-ImageClassification
On-demand skin health evaluation performed by artificial intelligence


---
FROM DEVPOST SUBMISSION

## Inspiration
Every year people around the world go undiagnosed with severe skin conditions. According to a study written by L. Tizek et. al. regarding the prevalence of common skin diseases in Europe,  "Several skin diseases are often treated by physicians, but it is estimated that more than *70%* of affected people do not consult with a physician." ([link](https://onlinelibrary.wiley.com/doi/full/10.1111/jdv.15494)).  Whether it be financial restrictions or pure inconvenience, millions of people around the world don't seek proper medical treatment due to their false notion that their condition is benign. **I believe that everyone deserves a free and accessible way to evaluate their skin health— a life-saving opportunity.**

## What it does
Using tens of thousands of carefully selected medical images from a database, artificial intelligence is able to accurately identify various skin conditions. All the user has to do is to point their phone's back camera at the concerning area, and the app will output a health report along with a confidence rating.

## How I built it

I consulted a University student and the person referred me to the possibility of building an AI model through Xcode. Upon my own investigation, I learned that Xcode provides a free developer tool for building AI models. So, I took the opportunity to build my own Machine Learning Model (MLModel). On Kaggle, a site that a conveniently discovered, I found multiple datasets of thousands of images of stale and fresh fruits. With that, I went to Youtube to find some guidance on how to code a real-time back camera in the app.  Finally, I assembled the ML Model and was able to integrate it into my app through the code that I wrote on Xcode.

## Challenges I ran into

Initially, it was difficult to find an appropriate way to create an artificial intelligence model, and I indulged in a lot of Google Searches that ultimately lead me astray. In addition, later on in the project, I had many difficulties with putting a back camera on the app.  

## Accomplishments that I'm proud of

I am proud of the fact that I was able to successfully make a machine learning app that correctly identifies skin conditions, seeing as was my first time with any sort of machine learning environment.

## What we learned

I learned how accessible it is to build an ML Model and integrate it into any code.

## What's next for SkinDoc

In order to make SkinDoc as accurate as possible, I would need to aggregate more images of the given conditions in the dataset. The more images that are in the dataset result in a more accurate report and a higher confidence rating. Furthermore, I would make a five-second stopping point for the imaging and have a screen pop up with the mean result that appeared after the camera sees the user's concerning area.
