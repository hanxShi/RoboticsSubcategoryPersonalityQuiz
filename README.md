# RoboticsSubcategoryPersonalityQuiz
Personality quiz type format, short multiple-choice quiz, for those that are unsure of where to start in robotics. 
Includes types of questions such as:
* Situational questions - what would you do if _____ happened
* Describe yourself questions
* Confession questions
* Interest questions - hobbies, likes, etc. 
* Leadership questions
* Vocabulary - identify picture and word

Possible subcategories:

ALL refers to only: [hardware, software, electrical, marketing, outreach, scouting, safety]

experience = increment these values above at different scales, sum them, and use a threshold for different levels 
* Lots of experience = +3
* Some experience = +2
* A little experience = +1
* No experience = +0

//currently approximations
* Veteran: > 50 
* Intermediate: >20
* Rookie: > 10

leadership?

Result is a bunch of numbers for each category. 

# The quiz framework

1. The robot is on fire. What do you do?
  * Not my problem. I will never have to deal with something like this. [software +2]
  * Take out your phone to video the entire scene. [marketing +2] [safety -1] 
  * Scream in terror and run as far away as you possibly can. [safety +0.5]
  * Help calm everybody down. [scouting +1] [leadership + 2]
  * Throw something at it. Like a mallet. [hardware +1] [safety -1]
  * Turn the robot off. [electrical +2] [safety +1]
  * Find the nearest fire extinguisher. [safety +2] [leadership + 1]
  
2. What is the worst thing you have done out of the below (if any)?
//maybe check all that apply
* I don't comment my code. [software +1]
* I unplugged a cord by pulling on the cord instead of the plug part. [electrical +1]
* I stalked someone on the Internet. [scouting +1]
* I don't constrain my lines in CAD. [hardware +1]
* I made an elementary-school-aged child cry. [outreach +1]
* I used Comic Sans in a formal document. [marketing +1]
* I have done all of the above. [ALL +1] (this will give you a lot of experience)
* I have never done any of these things. [safety +1]

3. What is the first thing you do at a robotics meeting?
  * Head into the shop [hardware +1.5] [electrical +1]
  * Socialize [scouting +1]
  * Obsessively check our budget [marketing +1]
  * Open your laptop or log into a computer [software +1] [hardware +1]
  * Check that everyone is wearing safety glasses [safety +2] [leadership +1]
  * Get my friend some free snacks (because you brought your friend) [outreach +1]
  * [electrical]

4. What would you most want to have if you were a tribute for the Hunger Games? Please choose one. 
* A flamethrower (to burn down enemies) [hardware +1]
* A Tesla coil (because it's cool). [electrical +1]
* Plenty of food and water (because I'm going to camp out and stay away from everyone). [safety +1]
* My friend (so they can die instead of me). [scouting +1]
* Nothing (to try and make friends with the other tributes). [outreach +1] {leadership +1}
* My laptop with unlimited, unblockable satellite WiFi (to disable the servers of the people who are running the show). [software +2]
* An invisible high-speed drone (to spy on other tributes) [marketing +1]
* What are the Hunger Games? [no point]

5. Why did you join robotics? (Please choose all that apply (?). We do not have an NLP to process open-ended responses for instant feedback) 
// can have user-ordered list or multiple selection?
* I want to pursue a technical STEM-like career in the future and thought robotics could be an excellent addition to my resume. [hardware +1] [software +1] [electrical +1]
* I want to make friends. [scouting +1]
* I want to help make a difference in my community and having a great time while I'm at it. [outreach +1]
* I want to go on cool trips. [marketing +1]
* The free snacks [no point]

6. Water game. 
* I'm sure they'll do one next year! [hardware +1] [electrical +1] 
* I am neutral in my stance. [ALL +0.3]
* What is a water game? [ALL -0.2] 

7. What is this? [image of T-handle]
* A hex shaft. [hardware -1]
* A hex key. [hardware +1] 
* A screwdriver. [hardware -1]
* A A funny-looking yellow object with something sticking out of it [hardware -1] 

8. Have you ever been to Harbor Freight? If so, how did you like it?
* Yes, it was AMAZING. [hardware +3] 
* Yes, but the products there are not of good quality. [electrical +1] [hardware +2] 
* Yes, I guess it was cool. [no point] [ALL +1]
* No, but I've heard about it. [no point]
* No, what's "Harbor Freight"? [software +2] [hardware -1]

9. What does FIRST stand for?
* Friends In Robotics, Science, and Technology [no point]
* Favorable International Relations of the Students and Teachers [no point]
* For Inspiration and Recognition of Science and Technology [ALL +0.5] (gives you a lot of experience)
* Future Innovation in Robotics, Science, and Technology [no point]
* Nothing, it's capitalized for no reason, like LEGO [no point]

10. What is the object you most often (accidentally) steal from the robotics shop?
  * I make sure to put everything back after I use it (Good job!!!) [safety +2] [leadership +1]
  * Safety glasses [hardware +3]
  * The little green battery tabs (voltage readers) [electrical +3]
  * Snacks [marketing +1] [outreach +1] [scouting +1]
  * I don't take anything from the robotics shop. [software +3] 

11. Is Topher a god? (*not a good long-term question*)
* ABSOLUTELY. [software +3] [experience +1]
* No. [ALL +0.2] [hardware +1]
* Who is Topher? [no point]

12. Which of these excerpts sounds most like you?
* "Yoooo, robotics is hella poggor. Everything else seems kinda sus" [hardware +1]
* "That's crazy. Yeah, I love robotics." [electrical +2]
* "Robotics! Word to your mother!" [scouting +1]
* "I love robotics!" [marketing +1] [outreach +1]
* "Robotics is cool." [software +0.5] [hardware +0.5] [electrical +0.5]
* "I am pleased to be accquainted with robotics." [software +2]

13. You  may be vey confused about how this quiz is related to robotics at this point. Here is a more sensible question: what would you most like to do as a part of robotics club? Short descriptions of each sub-category are listed below. 
* I have no idea. That's why I'm taking this quiz. [no point]
* Software: Java programming, machine learning, shameless pirating [software +1]
* Hardware: building things, CAD (computer-aided design), maybe welding [hardware +1]
* Electrical: soldering, checking connections and cable managment, wrangling batteries [electrical +1]
* Marketing: graphic design, ask people for money, crunch budget numbers [marketing +1]
* Scouting: troll other robotics teams online, then stalk them in-person at competitions [scouting +1]
* Safety: wear bright yellow gear and tell everyone to follow proper safety procedures [safety +1]
* Outreach: talk to people outside of robotics about robotics [outreach +1]

14. How would you describe yourself?
* Studious [software +1]
* Hands-on [hardware +1]
* Creative [marketing +1]
* Helpful to others [outreach +1]
* Good with people [scouting +1]
* Careful and assertive [safety +1]
* Chill [electrical +1]

15. Did you enjoy this quiz?
* Yes 
* No 

