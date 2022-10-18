# Resumate

## Description
View the project on [Devpost][https://devpost.com/software/placeholder-jsx57d##updates].

## Inspiration
A resume is something that we will all have to make, some time or another. It plays a major role in determining future opportunities. A weak resume could lead to an automatic no, but a great one will lead to success. Many companies use ATS, or applicant tracking system. It's used to scan resumes and see whether they are worthy of consideration/interviews. So, our service uses AI trained on great resumes to help you get approved by both the ATS and your employers.

## Usage
Resumate guides you through the tough task of creating a resume. You start off by picking one of four modern resume templates. Then you enter in your information such as your name, location, school, relevant work experience or any projects that you are proud of. This information then gets automatically displayed on the template you chose. As you enter in the bullet points for your experience, Resumate will give you feedback and tell you how well your bullet points are. Lacking bullet points will be boxed in red and there will be helpful suggestions to improve your lacking bullet points. There will be a score displayed for how well your resume is out of 100. Finally, you will be able to download the resume you created as a PDF.

## Development
We built it using Vue for the frontend and we used Cohere's API to generate feedback for the bullet points and an overall score for the resume.

## Challenges
One challenge we ran into was trying to collaborate on the same files at the same time as other teammates. This made it hard to merge changes, and we had to take extra care into making sure that there were no problems with integration.
We originally had the translator to workplace-appropriate language as one of our main features, but it had to be scrapped because of difficulties.

## Accomplishments
One accomplishment we are proud of is successfully integrating the Cohere API in our project. For two of our team members, this was the first time learning how to use an API. We were satisfied that we were able to provide them with a hands on experience of setting up and working with an API.

## Lessons
For two of our team members, this was their first time working with Vue.js. This gave us a unique opportunity to have two members teach and two members learn. All in all, it was a great learning experience for everyone.

## Future
We are planning for Resumate to be an application that helps prepare you for the workforce in general. We are planning on adding interview practice simulations that will give you questions based on the prompts you select, gauging your eye contact and confidence levels. Another addition would be a "translator" for common informal English phrases into their workplace-appropriate equivalents. As for the core resume functionality itself, we are looking to improve templates and increase the AI mode's accuracy.
