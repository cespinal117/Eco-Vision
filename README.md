# Eco-Vision
A collaborative project by: Gael Arriaga, Carlos Espinal, Kyle Grosman, and Lisa Nguyen <br />
https://youtu.be/Nl-8nB30MbI

## What is it?
EcoVision is an autonomous robot that uses the Google Vision Cloud API to identify objects and sort which items are recyclable or not. Once it finishes determining what objects can and cannot be recycled, it will then go and on its own grab the recyclable materials and bring it back to the waypoint. It will also record the items it has detected and send it to our database, where the information is then displayed onto our website. It also sends a photo capture of what the EcoVision is currently seeing.

## Inspiration
The inspiration for our hardware hack came from trying to find a solution to help improve reliability of identifying recyclable materials. Since the push of finding different ways to reduce our carbon emissions and become more eco-friendly, our team here at EcoVision decided to tackle the issue of recycling contamination. 

## How we built it
For the hardware, we used a combination of servo motors, 12V DC motors, a RasberryPi, and a generic USB webcam to create the EcoVision. The servo motor serves as the main mechanism to grab items and move them back to the waypoint, while the camera takes a screenshot of what it’s seeing and identifies the objects it sees. The backend of our product included sending data that the EcoVision obtained via its webcam to be used for the front end dashboard we decided to implement using Velo by Wix. The software was divided into two parts, the frontend and backend. The backend is where all the fun stuff occurs, where we used a combination of Velo and Filestore to help portray the data we send from our database to our website. 

## Challenges we ran into
There were a couple of challenges we faced when developing this project. Originally, we wanted to go ahead and showcase a live feed of what the EcoVision was seeing, however, due to YouTube requiring us to go ahead and wait 24 hours before we could livestream, we had to scrap the idea. For our database, we originally tried to design it using MongoDB, but unfortunately the Wix Velo browser did not support importing an external database from MongoDB, and thus we had to switch to using Filestore, as it is a much easier integration of our data. 

## Accomplishments we are proud of
We are extremely proud of what we accomplished in the 24 hours we had to do this project. We were able to create a front end and back end for EcoVision, its own database to store values, and implement the automation process and the self sorting process of the EcoVision all on its own. It clearly was a tough and ambitious project, so learning and troubleshooting everything within the 24 hours was tough, especially when it came to debugging.

