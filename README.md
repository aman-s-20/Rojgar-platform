# Rojgar Job Search App for traders

![Alt Text](https://media.giphy.com/media/A8pRmkexvl9jCdzS5D/giphy.gif)

## ❓ Problem Statement

- Make a job-search platform for traders


**Note** : SMS can be sent to only Twilio verified numbers as I am not using the paid service.

## 🚧 Technology Stack

- **Server Enviornment** - NodeJS
- **Framework** - ExpressJS
- **Frontend** - ReactJS, HTML, CSS, Javascript
- **Database** - MongoDB
- **Cloud database service** - MongoDB Atlas
- **Module to send emails** - NodeMailer
- **SMS sending** - Twilio
- **Deployment** - Heroku


## Workflow

I have identified 9 categories of job-seekers to make the platform more intuitive and simple.

- Electrician
- Plumber
- Labour
- Driver
- Maid
- Security guard
- Cook
- Peon
- Mechanic

#### For Job Seeker

1. Register
2. Update Profile
3. Apply on jobs - just by clicking - as simple as that.
4. The applicant gets an SMS on his/her phone number after applying to a job.
   ![SMS TO APPLICANT](https://github.com/Manvityagi/Rozgaar-Blue-Collars-Job-Seach-Platform-Backend/raw/main/assets/msgToApplicant.jpg)

#### For Job Poster

1. Post Jobs
2. Get applications on your posted jobs and shortlist.
3. **Ease the flow** for both parties
   - Job Seekers Profiles will be available all throughout, Recruiters can directly see their profiles and give them a message/call
4. Job Poster gets an email when someone applies on a job posted by him/her.
   ![MAIL TO RECRUITER](https://github.com/Manvityagi/Rozgaar-Blue-Collars-Job-Seach-Platform-Backend/raw/main/assets/recruiterMail.PNG)

#### Problems in Existing Solutions

- Little Less user friendly for maybe not so literate people
- Complicated Process - Blue Collars dont have a resume.
- All in English
- Lack of Support on chat/call

### Pending Tasks

- Unit Tests - Due to shortage of time, I couldn't write many unit-test.
- Login Sessions and Dashboard of Applications

### Additional Features to be added after Hackathon:

- Multi-lingual
- Filters according to location, salary etc.
- Stars/Reviews for job seekers
- Register by calling also (for job seekers) - simply call on a support number and automated clicks on phone
