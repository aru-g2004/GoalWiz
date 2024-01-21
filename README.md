# GoalWiz
Whiz your goals into reality with GoalWiz!


## Inspiration
We created GoalWiz after frustrations regarding a lack of motivation and repeated failures to achieve our goals in college. We found it difficult to manage our time: we started semesters enthusiastically with tasks we wished to accomplish, but we did not plan out and schedule these goals correctly, leading to forgetfulness and unfulfilled ambitions. 

## What it does
GoalWiz lets the user enter a goal that they wish to achieve, along with a time frame, frequency (per week), and session duration. We used OpenAI API in GoalWiz to create clickable hyperlinks - these URLs are links to Google Calendars with events outlining what the user needs to do to achieve their goal. The user has to press “Save”, and they now have a detailed outline behind achieving their goals saved to their Google Calendar - all with just a few clicks! 

## How we built it
We built this App using Flutter, Android Studios, and Dart: we found the SDK packages for the OpenAI API online, obtained a personal secure Key for the API, and implemented the API into our Flutter program on Android Studios. We then edited our program on Dart for design and functionality purposes. 

## Challenges we ran into
We ran into various challenges over the duration of BoilerMake. The ideation process proved to be difficult: we had to be realistic about what we could achieve in the limited time-frame we were provided with. We were on a time crunch, with about 10 hours to create our product. Friday was spent ideating and finalizing our product idea. 
Many problems arose on Saturday. We installed various softwares and programs; furthermore, our OpenAI API key had limitations in storage, and it took us 5+ hours and countless failures until we found an API implementation that worked. The struggles did not stop there: OpenAI was not providing a hyperlinked URL on Google Calendar for us, which is what we wanted. We had to write commands to ensure the AI did what we asked it to. Then, we had to parse the hyperlink it provided and turn that into a more accessible and user-friendly link. Our biggest challenges proved to be installing and understanding new software with a time-constraint. 

## Accomplishments that we're proud of
We are proud of what we learned using Flutter and Android Studios - Flutter proved to be a learning curve for our team as we had not used it frequently before - we learned a significant amount of Flutter over the course of the hackathon in order to utilize it correctly. We were also extremely proud of our work with the OpenAI API implementation - we did not give up even after 6 hours of failure, and kept persevering until we got our software to work. We displayed tremendous work ethic and time management: we took breaks at appropriate times, and did not neglect fun activities that BoilerMake had. These breaks helped us stay refreshed and energetic. We also switched tasks frequently and made sure everyone worked on a little bit of everything. We persevered until the end and kept a positive mindset about the hackathon.

## What we learned
BoilerMake taught us a lot on a technical and personal level. Technically speaking, we were faced with many unknown softwares and languages - we had to watch various tutorials and review blog posts by experts in order to understand the software that we needed to work with. The primary languages and softwares that we worked on and improved our skills with were: Flutter, Android Studios, Dart, Canva, and Figma. 

## What's next for GoalWiz
Our next steps for GoalWiz are to implement a Google Calendar API into our product to make our program even more user-friendly. We also look forward to working with the Apple Calendar API and the Notion API to diversify our user range. We also wish to make a “Friend-Sharing” option where, if the goal is collaborative, the user can share their Google Calendar schedule link with their friends so they achieve their goals via Google Calendar together.
