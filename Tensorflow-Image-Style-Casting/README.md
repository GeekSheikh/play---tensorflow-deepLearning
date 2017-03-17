# How-to-Generate-Art-Demo
This is the code for "How to Generate Art - Intro to Deep Learning #8' by Siraj Raval on YouTube - Dude is awesome, I highly recommend you check him out!

## Overview
Initially cloned thi from Siraj but then have since played with it such that it runs on Spark in a Hadoop Distributed Cluster but primarily I run this on a GPU enabled machine from AWS to make it go a little faster. Sometimes, I'll come back in here to look at code samples but this was an early tensorflow + deep learning demo.

## Dependencies

run `pip install -r requirements.txt` to install the necessary dependencies


## Usage

If it doesn't exist, create a file called ~/.keras/keras.json and make sure it looks like the following:

   ```
   {
       "image_dim_ordering": "tf",
       "epsilon": 1e-07,
       "floatx": "float32",
       "backend": "tensorflow"
   }
   ```

Then you can run the code via typing `jupyter notebook` into terminal


# Coding Challenge - Due Date is Thursday, March 9th at 12 PM PST

Use 2 different style images and transfer them both onto a base image. This can be done several ways, take your pic! And if you want even more of a challenge, bonus points are given if you instead perform basic style transfer on video. Remember, a video is just a series of image frames. You'll learn a lot about matrix operations by doing this. Good luck!

