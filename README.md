# Week of 11/16/2023
**Final Project Proposal**

**SUMMARY**
My idea for my final project is to create an interactive environment to creatively express emotion. I would like to create a projection that maps the users body and allows them to move and create physical reflections of their emotional state. The technologies I would use might include an Xbox Kinect for body mapping and touch designer for creating the projection reflections.

**RESEARCH PLAN**
My research plan involves getting an Xbox Kinect, which is priced at about $10, to understand how it maps human bodies. Since this is a new thing for me, I've been watching several videos to understand its workings and potential applications. I am particularly interested in exploring how I might use the Kinect in conjunction with TouchDesigner to create interactive visual gestures.

<img width="617" alt="Screenshot 2023-11-20 at 6 18 06 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/396ea65d-b5b0-485b-88c2-3f4c2a32a9df">

I plan to start with studying the Kinect's technology. I want to learn about its depth sensor, RGB camera, and understand how these components work together to track motion and gestures.  Once I have the Kinect, I want to create some experiments to test its capabilities. 

Integrating Kinect with TouchDesigner will be an important part of my project. I want to research existing libraries or APIs that could help with this integration. I'll document setting up this environment, from initial trials to troubleshooting and configuration.

<img width="622" alt="Screenshot 2023-11-20 at 6 18 43 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/35ef9faf-29ee-4d3c-9170-652913a4731f">

**CURRENT WORK**
I don’t have current work that I’ve done myself, but have watched several videos.

**MOTIVATION** 
I hope to learn more about body mapping and using touch designers.

**CHALLENGE LEVEL** 
Triceratops

**TIMELINE** 
Thursday, Nov 16 - Try and get the Kinect
Thursday, Nov 23 - Have an understanding of how these functions work together
Thursday, Nov 30 - Work with Kinect and Touchdesigner to have some sort of interaction together
Thursday, Dec 4 - Be done! Hopefully!

# Week of 11/09/2023
**Social Media Agent Support**

**Introduction**
My project was to create a social media assistant that knew my style, energy, and content creation type to efficiently provide ideas for my video content. The idea was this would be a mini version of my persona on social media. She would know what I like, how I film, and be able to provide ideas and a shot list for a video. Ultimately, it worked out really well and was able to provide accurate ideas for videos that align with my branding.

**Level Selection**
I chose to work at the Platypus level because the project seemed like an interesting challenge, and I was eager to learn how to use LLM and understand how they work. 

**Experiments**
To start, I fed my AI a bunch of information about myself. In the initial ideas, I told it that it was a social media assistant, and gave it rules about myself, who was their target audience. Inside that same instruction, I gave it information about their job and what they needed to do as my mini me. Embedded inside this informational context was a knowledge base, and the knowledge base has additional information about myself and who I am.

<img width="651" alt="Screenshot 2023-11-20 at 6 13 21 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/89df45a9-8f93-40e5-bcba-78d24c3c86ea">

Now inside of the knowledge base, I had a lot more information that was much longer than what I provided in the informational portion. I included things about myself that came from my LinkedIn, statements I’ve written, along with other information I’ve written down previously. However, I analyzed my videos that I’ve created previously, and wrote down a bunch of information about these videos. Because it’s primary goal was to provide me ideas for videos, I fed it quite a few examples of videos I’ve done, shot lists, and ideas that I would like so it had an idea of what I might like to do in a video.

<img width="633" alt="Screenshot 2023-11-20 at 6 13 50 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/6b076757-51e9-4ef5-b0b1-7afc5d7d5387">

First, I wanted to play with the temperature and see how this mechanism worked. I set the temperature to two, and it was way too much because my responses wouldn't load. I waited about 5 minutes and nothing happened. After this, I lowered it to 1.5, but I still had no luck. It wasn't until I brought it down to 1 that things started to work. However, I eventually found that setting it to 0.7 was the sweet spot, which is pretty close to what was suggested for getting more creative responses.

<img width="584" alt="Screenshot 2023-11-20 at 6 14 19 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/916502f8-f283-475a-afb2-3108ade60cd4">

When it came to tokens, I decided to go all in and turned it up to the highest setting just to see what would happen, but my mini me crashed. After that, I tried setting it to around 6000 tokens, but I ran into the same problem. Ultimately, I've settled on using about 2000 tokens, and it's working smoothly without any issues.

<img width="607" alt="Screenshot 2023-11-20 at 6 14 45 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/c41215d8-f03a-4674-b194-ed4b564c565f">

**Demonstration**

View the demonstration here!

**Reflections**

It was a really interesting project to take part in, as I haven’t personally built an LLM before. I’ve ‘trained’ AI’s previously by using the same one over and over, but this experience was completely different. I thoroughly enjoyed being able to actually customize my mini and direct it to be what I imagined.
I think in the future, I would like to see more customization features with these kinds of algorithms. We’ve already seen this at with ChatGPT allowing certain instructions to be added, but would be so awesome to see this is a greater scheme.

**Speculations**

**How will this technology impact the design of human experiences?**

We have already seen massive waves with what artificial intelligence can do, such as provide academic support, build companies, expose information, simplify text, etc. It has already impacted the experience of humans all around the world, and will continue to do so no doubt. 
I imagine that moving forward, it will ease the lives of many human beings. Ideally at a large scale, but of course this is more than likely going to positively influence the middle and higher classes. It may also, as some speculate, reduce the amount of simple jobs that exist. I’m not entirely sure if this will happen, but the floodgates have been opened, and I believe that either way this may lead to more jobs being created. Who knows!

**How will this technology impact engineering and how we build?**

Again, we’ve already seen this positive influence. Many engineers are using AI to streamline their own practices, and be even better developers. It’s only going to continue to increase the support these engineers have, as I know many of the people on my team have already used the support of AI. I think for how we build, it may overall make these processes more efficient and faster.

**Next Steps**

The feedback I received from my peers was great overall. Compartmentalizing the feedback, people seemed to enjoy the concept that I created for the project, as well as liked the video style of the presentation. Moving forward, I’ll be sure to include a full screen recording of the demonstration as opposed to just snippets and screenshots, since that’s what some wanted to see.

**Conclusion**

As scary as AI may seem, I think as long as humanity abides by a singular code of ethics, we should ideally be okay. Obviously, that is much easier said than done, but the same can be said with so many other kinds of technology. The boom of the internet was intense, but eventually we developed laws and policies around what can and cannot be done legally. I imagine the same being done now with this new tool, hopefully sooner rather than later.


# Week of 11/02/2023
**Work in Progress**
I have several projects that I'm working on from different classes, so it's been a bit chaotic. For this class specifically I started working on the LLM project, and exploring different features of ZeroWsith. I find the project to be fairly interesting, and think I may try to create a malious AI bot that spews nothing but misinformation. To be continued..

# Week of 10/26/2023
**Introduction**
Our concept for Rescue Ring was to create a product that would allow friends at a party to communicate with each other in a discrete fashion in case they’re experiencing anxiety, panic attacks, or just not having a good time. The idea here is that both friends would be wearing a ring with a Force Sensitive Resistor and Haptic Feedback buzzer. If one of the friends want to notify the other friend that they need them, then they would simply tap the ring and it would send a buzz to the other person.

<img width="623" alt="Screenshot 2023-11-20 at 6 06 38 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/f1165134-04ea-4220-a340-df0bf0f5e8b9">

**Level Selection**
For this project, I wanted to work at an Axolotl level because I’ve never worked with photons before this program, and really wanted to learn more about this skill and explore what could be done. I figured if I worked at this level, then it would force me into learning more about photons and trying to make things work.

**Contributions**
For Rescue Ring I took on several roles, particularly in areas where I had a strong skill set. One area that I was confident in was soldering. It came to our attention that no one in the group had substantial experience with this technique. Recognizing the opportunity, I not only executed the soldering tasks but also took it upon myself to guide my teammates through the process. This hands-on experience greatly enhanced my proficiency, and it was rewarding to witness the collective progress of the group. As we worked together, it was clear that my contribution was important in ensuring the successful functionality of our product, without taking much time away from other people to teach students to solder. Not only did this experience bolster my soldering skills, but it also gave me a chance to mentor and share knowledge with my peers. 
In addition to this, I helped with setting up the circuit and auditing the code to find any issues that may have arisen. For example, when we were trying to get the photons to communicate, we ran into an issue. One of them would cause the other photon sensor to buzz, but it would not work vice versa. I looked at the code that Vidit has created, and changed aspects of it to try and mediate this situation. Even though we couldn’t get it before class on Thursday, it was still a great opportunity to test my circuit and programming knowledge


<img width="620" alt="Screenshot 2023-11-20 at 6 06 59 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/59f11dae-4322-4368-b27a-f3f23a9d8565">

<img width="625" alt="Screenshot 2023-11-20 at 6 07 21 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/e41840d4-2fa3-48ea-af29-832d968f37eb">


**Reflections**
Our project aims to transform the way people perceive safety at large events. The significance of personal safety in crowded spaces cannot be understated, and our observations have highlighted a consistent need in this domain. Our initial thoughts were related to a pair of friends being separated at a party, and notifying each other of their need for the other.


Large events, whether they are music festivals, parties, or conventions, bring together vast numbers of people in confined spaces. During events like these, concerns about safety can overshadow the actual experience. Our goal for the Rescue Ring began from this very observation. Our goal is to provide a solution that not only addresses safety concerns, but also reinforces a sense of empowerment among attendees. The intention is to ensure that everyone can enjoy these events to the fullest, with an assured sense of security, and a way to connect back with their friend without the need for a phone.
With our project, we are offering more than just a temporary fix. We are laying down the foundation for a sustainable change in the way safety is perceived and experienced at large gatherings. By centering our approach on genuine empowerment, we aim to make people confident about their well-being at any event, allowing them to focus on the experience itself. We are hopeful that our efforts will redefine the standard for safety in crowded settings.


<img width="520" alt="Screenshot 2023-11-20 at 6 07 35 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/202ece77-700f-4ff8-960b-5d2c27cb3c7f">

<img width="340" alt="Screenshot 2023-11-20 at 6 07 51 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/b15c9f1e-1154-4374-8caf-974b39f5eb34">


**Speculations**
I speculate that with this device, a lot of people will be more comfortable going out to large functions with friends. It is a very simple device that empowers people to go out and not be afraid of what may happen if they can’t get in contact with their friend. Safety unfortunately is such a huge market, as we've seen with cup covers blowing up and being passed out at parties to make sure someone isn’t drugged. I believe this device would be at the forefront of partying and enjoying large functions safely.

<img width="610" alt="Screenshot 2023-11-20 at 6 08 03 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/bf6893b7-0a0b-423c-8635-7088f880c91c">


# Week of 10/19/2023
**Chaos Arises**

My week has been fairly chaotic, dealing with tons of work and outside stressors. I've been in midterm grading mode, and can't wait to be done with this.

As for TDF, it was a fairly slow. The conversation with the ZeroWidth founder was interesting, so I really enjoyed that. I have created a few knowledge sets in ZeroWidth, and have been updating them throuhgout the week.


<img width="1038" alt="Screenshot 2023-10-28 at 4 18 03 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/941f8c39-8b4d-4afc-9c66-cc44c9db78b3">

She's.. excited?


<img width="602" alt="Screenshot 2023-10-28 at 4 18 57 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/82c9c66c-f6e9-4806-a8bf-b2e1dd6ae6e9">

I don't think she understands how to use emojis.


Work in progress!


# Week of 10/19/2023

**Conceptualizing our Idea**

Our concept for Rescue Ring was to create a product that would allow friends at a party to communicate with each other in a discrete fashion in case they’re experiencing anxiety, panic attacks, or just not having a good time. The idea here is that both friends would be wearing a ring with a Force Sensitive Resistor and Haptic Feedback buzzer. If one of the friends want to notify the other friend that they need them, then they would simply tap the ring and it would send a buzz to the other person.


<img width="588" alt="Screenshot 2023-10-23 at 5 20 18 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/79a653ff-e3b6-433a-be71-8d99f8a5c035">


**Level Selection**

For this project, I wanted to work at an Axolotl level because I’ve never worked with photons before this program, and really wanted to learn more about this skill and explore what could be done. I figured if I worked at this level, then it would force me into learning more about photons and trying to make things work.


<img width="497" alt="Screenshot 2023-10-23 at 5 21 24 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/23200244-131f-4870-a2ce-4229a59a4195">

**Changes**

Originally we were thinking of doing something like a clip on that could be attached to your shirt, and this way you could tap it and/or feel it buzz. However, I noted that this may not be as discrete as we would want it to be. It might be a bit obvious on your clothing, and obvious when you're tapping it. Additionally, if you're wearing loose clothing, then you might not feel it buzz all togther!


<img width="1007" alt="Screenshot 2023-10-23 at 5 23 53 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/b4be9ac8-02cd-4e62-8dbf-2815aa6d90e2">

As a result, I came up with the idea of "Resuce Ring", and more discrete and functional wearable.


**Contributions**

For Rescue Ring I took on several roles, particularly in areas where I had a strong skill set. One area that I was confident in was soldering. It came to our attention that no one in the group had substantial experience with this technique. Recognizing the opportunity, I not only executed the soldering tasks but also took it upon myself to guide my teammates through the process. This hands-on experience greatly enhanced my proficiency, and it was rewarding to witness the collective progress of the group. As we worked together, it was clear that my contribution was important in ensuring the successful functionality of our product, without taking much time away from other people to teach students to solder. Not only did this experience bolster my soldering skills, but it also gave me a chance to mentor and share knowledge with my peers. 


#  Week of 10/12/2023
**Communication & Particle Configuration**
We've spent a lot of time trying to make the particle board work. I managed to get some portion of it working, but still trying to figure out the vibration portion of our board.
![IMG_2113](https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/162c4a1d-ad31-43e9-baf4-d6226380df07)

#  Week of 10/5/2023
**Brainstorming for the Particle Projects**
My group and I were trying to figure out what we wanted to do for our project. We had initially thought of overcoming language barriers by creating sunglasses that would translate real time conversations, but quickly realized that that would be really difficult to do.

We then decided to pivot! We're still staying along the lines of communication, but maybe considering between two people trying to discretely communicate.
<img width="944" alt="Screenshot 2023-10-14 at 11 19 46 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/956e554e-d164-45fe-af53-8016f4b02475">

#  Week of 09/28/2023
**Not much to report**
Got hit by a motorcycle this week. Not very fun.

# Report 3 - Week of 09/11/2023
**🏃‍♀️ Rushing towards the finish line**

Last week I was able to come up with a great example for a phone stand in Rhino. Only thing was, I didn't find much interested in creating a phone stand. I have a lot of different tripods and stands for my phone already, and didn't want to waste product for something I might not use very often.

I started to think more about what I wanted to do, and what would be realistic to use on a regular basis. As I started thinking more about it, I really wanted to try and make a vase. I wanted one, and so I thought this would be a really cool idea.

<img width="161" alt="Screenshot 2023-09-14 at 10 41 12 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/4754823f-ba2e-4ddd-8675-a1de89596387">
<img width="372" alt="Screenshot 2023-09-14 at 10 41 36 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/3cd7f3f7-9521-49c0-b11a-5f99f24554ac">

I wanted something that had curves and wasn't fully straight, so I really liked the ones I found above. After than, I tried drawing out some sketches that don't really match, but still wanted to try and draw them gain that skill.

![IMG_255E3014F477-1](https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/c71f55e3-98a9-4fa5-bc54-f993e288cf3d)
![IMG_7138001BA0AE-1](https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/4fabb3c4-7c1a-476c-aa53-2964051019ab)

Something felt off with these thought, I realized that I actually wanted to try something a bit different. I wanted some texture and geometry so I could make it a little more diffitult (AKA Platypus level). So I drew out something that was a big more low poly and geometric. 

**Here are some images of my inspiration.**

![IMG_1601](https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/10ee1d69-6bc7-485f-ae89-6fe98c521e40)
![IMG_1600](https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/a332ab10-e7dc-4e64-a9ac-16c3b86d1dfb)

And this is what I tried sketching to start working in Rhino!

<img width="376" alt="Screenshot 2023-09-14 at 1 49 44 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/7111f2aa-74cf-427e-a76e-1088448fb713">


**Images of my creation in Rhino and Grasshopper.**
![71636397974__06FA34D0-3093-4A06-A87C-71303C881E5F](https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/ea913fc9-1ed8-4dd3-ae6f-b6696ef63654)
![71636366890__EE49C23A-4409-4105-A674-312E2E198602](https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/07623704-b7d3-41b5-95ab-dd1a6e272c7c)

[You can watch my journey more in depth here!](https://youtu.be/YEtRWLvp9wQ)

# Report 2 - Week of 09/04/2023
**Overcoming Rhino**

## 🚖 Wednesday 9/6 Recap

Rhino and Grasshopper has been a really frustrating learning curve for me. Initially with the first file, I was distraught (to be dramatic) when I first saw the original phone model. Lowkey- felt like crying.

HOWEVER- things have become better. Last week was a bit better in terms of learning how to use these platforms. I think my main issue was not understanding the fundamentals of the different tools and the actions they do. I took it upon myself to watch some Youtube videos just to get a basic foundation for how to use them, because I felt if I didn't then I wouldn't truly understand it.

THANKFULLY, TJ uploaded the wonderful video explanation that helped break down the cell phone stand project. Honestly I probably would not have had the understanding I now have without it. Thank you TJ 🫡 Here are a few things that I now understand.

1. Setting a plane ✈️

Originally Cody in the makerspace explained to me hoe planes work, and helped me set this in the original cell phone stand file. While it was really helpful, I didn't fully understand it in terms of the overall contribution to the project. We used it so I would not lose the phone stand and could type 'ZS' to find it. The walkthrough of seeing the plane in within the box and spheres helped to solidify where the phone lies within this realm.

2. Baking 🧁

When I created my phone stand last week, baking was realtively easy, but I did run into some problems and learned what not to do. The entire process seemed relatively self explanatory, but alas- it was **_not_**. When it came to exporting, I didn't realize you could bake it several times, so in illustrator I literally had 6 layers to sort through.

<img width="1878" alt="Screenshot 2023-09-07 at 7 49 45 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/02ebe2a4-3ba8-4260-a280-9f4ce937e3cd">

<img width="946" alt="Screenshot 2023-09-07 at 7 52 16 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/6b1d96f5-eddf-46e6-af80-02e6321846c7">

3. Stabiltiy ⎍

I  didn't even know that we could analyze our model within Grasshopper, so to find out we could find the stability of an object was pretty cool. If I'm correct, last week when I was adjusting the original file, I noticed that when I was trying to change my phone stand from horizontal to vertical, it turned red unless I manipulated some of the values. I probably worked through this for about 2 hours which was very very annoying. I assumed that it was red and not blue because something was wrong, but I now know more specifically that this was because it was not stable. Makes a lot of sense.

4. Shapediver

I didn't know this existed, so seeing the file outside of Grasshopper was interesting. I  really llike this because you can play with the adjustments without worrying about ruining the actual file. Something I know I'm always scared of.

## Overall
I'm feeling more confident in using Grasshopper after watching some Youtube videos and watching TJ's tutorial. Next I want to try and create something super simple from scratch, just to make sure I'm grasping all of the content correctly!

# Report 1 - Week of 08/28/2023
**Eliza Gonzles, Tech Des Found**

## 🪑 Monday 8/28 Recap

It has been a long long week! But, I have made some really awesome progress and am ready to share what I've managed to complete thus far.

Earlier this week on Monday, I attempted to laser cut the basic model of the phone stand with no modifications with a fellow classmate, Abigail! It was a bit of a learning curve, but nonetheless we were able to figure it out. Most of it was just remembering how to work on Adobe Illustrator, and printing it to the laser cutter. 

Here are some of the awesome results we got!

<img width="634" alt="Screenshot 2023-08-30 at 8 08 30 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/68164ee7-c347-4d99-b8d4-d7551b7ed300">
<img width="660" alt="Screenshot 2023-08-30 at 8 08 22 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/94511544-9f09-45c8-8917-104b37731d90">

## ✏️ Wednesday 8/30 Recap

After class on Monday, I wanted to try and explore Rhino and Grasshopper to make modifications to the file. Boy was that rough! I spent quite a few hours working on it and just trying to understand how it worked. 

My phone measurements for safe keeping 👩🏽‍💻

🔸 **Width:** 81.75mm 

🔸 **Length:** 165mm

🔸 **Depth:** 13mm


Here are some annoying b I ran in to:
1. **Vertical vs. Horizontal**

Attempted to make the stand vertical. I struggled with this for a while because what I initially did was reverse the input, so I put length into width and vice versa. Because of this, it was incredibly difficult to adjust the height of the stand itself. I tinkered with this for a LONG time. Finally saw there was an option for Portrait vs Landscape in GS, so started over

2. **Perspective??**

First of all, there are so many views, why?? Second of all, I learned NOT to drag one view into full screen, and to simply double tap the view I want in 4View. Cody was a miracle worker here, because I was deepyly confused.

3. **Plane**

Cody also helped me to set up a plane so I wouldn't lose the object so easy. It basically required typing in plane, placing it on the object, and making sure it's correctly dragged to the object. Great learning yay!

4. **Shake n' Bake n'**

Baking was easy! Learned that this should not be done in perspective view otherwise it was actually bake in perspective. There is a little vroom vroom car that shows it from the top view that was great. Baking was easy, but I just ran into a few issues with exporting this into Illustrator.

I also learned about the Move command and moving the baked portion to 0, because it was floating off into space and not showing up in Illustator. 

## Photo time!
<img width="603" alt="Screenshot 2023-08-31 at 9 55 57 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/43857ec4-d970-40f4-ab02-8e1f8e253faa">

<img width="617" alt="Screenshot 2023-08-31 at 9 56 42 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-eliza-m-gonzales/assets/143106992/b55cfe17-719e-45f9-b409-1bcc0cc61779">

## Outcomes
The final one wasn't put together very well, I believe it was to do with the sizing of the acrylic OR I need to adjust the holes they go in to. TBD!

Learning do be fun sometimes!

--------

- [TDF Wiki](https://github.com/Berkeley-MDes/desinv-202/wiki) - the ultimate source for truth and information about the course and assignments

- [Google Drive Folder](https://drive.google.com/drive/folders/1OjFgu4llHn-2WayQFVWRKFyOkQ_WaQRx?usp=drive_link) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1528355) - where the grading happens


