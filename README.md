# Content-based Video Relevance Prediction Challenge
### @ACM Multimedia 2018, Seoul, South Korea

* This challenge is fully sponsored by Hulu.

Video relevance computation is one of the most important tasks for personalized online streaming service. Given the relevance of videos and user behaviors, the system can provide personalized recommendation, which will help the user to discover more contents of interests. In most online service, the computation of video relevance table is based on the user implicit feedbacks, e.g. watching and searching history. That is, the system analyzes the user-to-video preference and computes the video-to-video relevance scores using collaborative filtering based methods. However, this kind of method performs poorly on “cold-start” problems - when a new video is added to the library, the recommendation system needs to bootstrap the video relevance score with very little user behavior known. One promising approach to solve “cold-start” is exploiting video content for relevance prediction, i.e. we can predict the video relevance by analyzing the content of videos including image pixels, audios, subtitles and metadata. Since understanding the content of the videos is still a challenging task, the aim of this challenge is to explore efficient ways to do content-based video relevance prediction tasks for recommendation system.

## Task and Data

The main task of this challenge is to predict the relevance between TV-shows or movies from the video contents. Specifically, there are two separated tracks for TV-shows and movies respectively. The following components will be publicly available under this challenge:

#### Track 1: TV-shows

Over 7,000 TV-shows with pre-extracted features from their video trailers. The whole set is divided into 3 subsets: training set – 3,000 shows, validation set – over 800 shows, and testing set – 3,000 shows.

#### Track 2: Movies

Over 10,000 TV-shows with pre-extracted features from their video trailers. The whole set is divided into 3 subsets: training set – 4,500 shows, validation set – over 1000 shows, and testing set – 4,500 shows.

For training set and validation set in both tracks, we also provide the ground truth (relevance lists) derived from massive user behaviors.
 
The proposed methods will be evaluated based on mean Average Precision (mAP) regarding to top K prediction (the value of K is TBD). We will provide the python script to compute mAP for evaluation.

## Registration

To register the challenge and get access to the dataset, the participants should fill in an application form. After submitting the application form, we will send the download link by email within 2 working days.

## Submission

TBD

## Schedule

TBD

## Organizers

* Mengyi Liu (mengyi.liu@hulu.com) Hulu LLC.
* Xiaohui Xie (xiaohui.xie@hulu.com) Hulu LLC.
* Hanning Zhou (eric.zhou@hulu.com) Hulu LLC.

## Contact

If you have any question, please send email to cbvrp-acmmm-2018@hulu.com
