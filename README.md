# Content-based Video Relevance Prediction Challenge
### @ACM Multimedia 2018, Seoul, South Korea

(This challenge is fully sponsored by Hulu.)

Video relevance computation is one of the most important tasks for personalized online streaming service. Given the relevance of videos and viewer feedbacks, the system can provide personalized recommendations, which will help the viewer discover more content of interest. In most online service, the computation of video relevance table is based on the viewers' implicit feedback, e.g. watch and search history. The system analyzes the viewer-to-video preference and computes the video-to-video relevance scores using collaborative filtering based methods. However, this kind of method performs poorly for “cold-start” problems - when a new video is added to the library, the recommendation system needs to bootstrap the video relevance score with very little historical viewer feedbacks. One promising approach to solve “cold-start” is analyzing video content itself to predict the relevance score, i.e. predicting the video-to-video relevance by analyzing the keyframes, audio, subtitles and metadata. With the relevance score, we can provide better recommendations for our viewers.

## Task and Data

The main task of this challenge is to predict the relevance between TV-shows or movies from video content and its features. Specifically, there are two separated tracks for TV-shows and movies respectively. The following components will be publicly available under this challenge:

#### Track 1: TV-shows

Pre-extracted features derived from nearly 7,000 TV-show video trailers. The whole set is divided into 3 subsets: training set (3,000 shows), validation set (over 800 shows), and testing set (3,000 shows).

#### Track 2: Movies

Pre-extracted features derived from over 10,000 movie video trailers. The whole set is divided into 3 subsets: training set (4,500 movies), validation set (over 1000 movies), and testing set (4,500 movies).

For training set and validation set in both tracks, we also provide the ground truth (relevance lists) derived from implicit viewer feedbacks. The viewer feedbacks have been cleaned to avoid any privacy issues.
 
The proposed methods will be evaluated based on recall rate regarding to top K prediction (the value of K is 100 as the final criteria). We will provide the python script to compute recall for evaluation.

## Citation

If you use the CBVRP dataset in your work, please cite it as
 
Mengyi Liu, Xiaohui Xie, Hanning Zhou. "Content-based Video Relevance Prediction Challenge: Data, Protocol, and Baseline". arXiv preprint arXiv:1806.00737. 2018.

The full paper is available from https://arxiv.org/pdf/1806.00737v1.pdf
 
BibTex:
 
@misc{cbvrp-acmmm-2018,   
  title={Content-based Video Relevance Prediction Challenge: Data, Protocol, and Baseline.},   
  author={Liu, Mengyi and Xie, Xiaohui and Zhou, Hanning},   
  journal={arXiv preprint arXiv:1806.00737},   
  year={2018}   
}

## Registration

To register for the challenge and get access to the dataset, please complete the [Online Agreement Form](https://freeonlinesurveys.com/s/lDBaYlvA). We will send you the download instructions by email after the challenge data available date (Apr. 20th, 2018).

## Submission

The participants should prepare a csv file for testing set (please refer to provided evaluation example to see the format of the submission file) and send the csv file to cbvrp-acmmm-2018@hulu.com. After receiving the submission csv file, we will evaluate the results and send back to the participants by email no later than July 1st.

## Schedule

April 2nd: Registration open.   
April 20th: Challenge data available.   
July 1st: Deadline for results submission.   
July 8th: Deadline for paper submission (Optional, for more details, please refer to “Submissions” on http://www.acmmm.org/2018/multimedia-grand-challenge/).   
August 5th: Notification of winners and paper acceptance.   
August 31st: Winners submit the tech report and source code.

## Organizers

Mengyi Liu (mengyi.liu2012@gmail.com) Hulu LLC.    
Peng Wang (peng.wang@hulu.com) Hulu LLC.   
Xiaohui Xie (xiaohui.xie@hulu.com) Hulu LLC.   
Hanning Zhou (eric.zhou@hulu.com) Hulu LLC.   

## Prizes

The total reward is $2,000 USD including the taxable amount, which will be fully sponsored by Hulu LLC. The number of winners will depend on the number of participants and the quality of the results. The organizers reserve the complete right in the final judgement and decision.

The winners of the challenge are required to provide a technique report describing the details of the winning algorithms, and provide the source code to the organizers. The organizers will also run the released the code to test the reproducibility of the winner algorithms. The winners will give a presentation during the conference.

## Contact

If you have any question, please send email to cbvrp-acmmm-2018@hulu.com.
