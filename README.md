# hackathon-example-submission
This example shows how we'd like your submissions to look like.

This project was created in the Relaxdays Code Challenge Vol. 1. See https://sites.google.com/relaxdays.de/hackathon-relaxdays/startseite for more information. My participant ID in the challenge was: CC-VOL1-1

## How to run this project
You can get a running version of this code by using:
```bash
git clone https://github.com/LukasKaufmannRelaxdays/hackathon-example-submission.git
cd hackathon-example-submission
docker build -t hackathon-example .
docker run -v $(pwd):/app -p 8080:80 -it hackathon-example
```
If you now access http://127.0.0.1:8080/ you should see the thing you want to review.

