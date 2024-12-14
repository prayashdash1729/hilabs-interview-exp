**Company:** HiLabs DS\
**Result:** Selected\
**Prayash Dash**\
**21085063**\
**B.Tech Electrical Engineering**\
**LinkedIn:** https://www.linkedin.com/in/prayashdash/
**Contact:** 8018179474\


## Resources and more tips

I have compiled all the resources that helped me in my preparation along with some general tips in the notion doc below-

https://prayashdash.notion.site/Data-Science-Placement-Roadmap-1516cd9612dd80ed9b3effb02261da4a


## Online Assessment
1.5 hr test on HackerEarth. The test contained ML and DS MCQs, 2 DSA questions (medium) and 1 coding question which asked to do a sentiment analysis using some package in Javascript (DS candidates were not required to do this question)

20 students were shortlisted purely based on test scores.

## Interview Process
Final Interviews: On 1st Dec 24, Slot 0. All rounds were online and taken by a single interviewer. Interviews for DS, APM, and SDE were taken simultaneously.
A total of 3 rounds of interviews were conducted. The first two rounds were technical and the third round was an HR round. Each round was eliminatory in nature and about 5 students were eliminated in each round. Some students also had a third technical round. At the end, 5 students gave the HR round. 1 was selected.
The company itself sent the order of students for interviews. They were sending people in batches of 5/6. I was in the second batch of students who went for the first round.

### 1st round: ~1hr
It started with a basic introduction, and then he started asking about basic ML questions- nothing specific from my resume. He asked if I knew about SVM and what challenges SVMs face in high dimensional datasets. Then he asked if I had 60000 features and if I wanted to apply SVM then what would happen. In my answer, I mentioned that we need to reduce the dimensionality- He then asked me about methods to reduce dimensions- I knew very well about PCA so I started from there. I simply mentioned that we can use PCA hoping he would ask something more on that. He asked me if I knew how PCA works- this is where I explained to him in detail how it works with the mathematics- eigenvalue decomposition of the covariance matrix and the basic intuition of why the algorithm works and how principal components capture variance and assumptions and everything. He was more than satisfied and skipped to Decision Trees. Then he asked if I knew about how DTs are constructed and what are their drawbacks- I answered and made sure to include technical terms such as recursive binary splitting and pruning including all the maths and equations. He was happy with my answer. Then he asked me about Random Forest and what is random in Random Forest and also about Xgboost since I had mentioned them in one of my projects- I followed the same method of first answering in short to provoke more questions and then answering it all in depth. This was something which seemed to work with the guy.

Then he moved to LLMs as my last project was related to finetuning an open-source model and then building a chatbot with the model. He asked me to explain the project. I mentioned that I did the project only a couple of months back and that I am a beginner and am still exploring LLMs and finetuning. I then explained to him the project and what I did. He then asked me the difference between QLoRA and LoRA- I started from peft and mentioned different techniques and then explained LoRA in depth- what it is and how it works, including some things picked up from the original paper itself. Then I explained to him quantisation, its types, the type I used etc. He was satisfied with my answer and then asked about encoder and decoder models- I did not have a very good understanding of them so I explained to him whatever I knew and then said that I don't know much as I am still exploring this domain. He then asked me what is the basic difference between a model like BERT and the model I used (Falcon7B) I could guess that one must be an encoder-only and the other must be a decoder-only model but was not able to recall which was what. I explained what I was thinking exactly to the interviewer and said that if I had to guess then I would say Bert is a decoder only model- this was wrong and he corrected me but was chill about it. He then mentioned that he did not have any other questions and the round ended here. Before leaving the call, I said "Thank you. It was nice talking to you". This was not something which I planned on saying or something I prepared. It was a genuine compliment which I felt I needed to mention because the conversation was actually good.

<br/>

After returning to the waiting room, I quickly chatgpt-ed about popular LLMs like BERT, Llama, GPT and Falcon and their architecture, revisited my notes on encoders and decoders and some common problems associated with them. I was then called for the second round after some time. I could see that some guys were already having their 2nd round.
I had a small chat with the guy who had his 2nd round before me about how it went for him and what was being asked. He mentioned that he was asking probability and DSA questions in this round. This is where it hit me- I had completely forgotten to revise any DSA for interviews. The last DSA question that I had solved was probably 2 weeks ago. I knew I could not do anything now so I somehow convinced myself that I had done enough DSA and should be able to solve standard graph and dp questions. The guy also mentioned that the interviewer was asking probability questions which seemed straightforward but the straightforward solution was not the answer the the interviewer was expecting.


### 2nd round: > 1hr
This started pretty straightforward. He asked if I was comfortable with probability. I said yes. Then he asked a question which was something like- A family has two children. Given that one of the children is a female, what is the probability that the other child is also female?


Based on my convo just a few seconds ago with that guy, I said- "If both a male and a female child have equal probabilities then I think the answer should be simply 1/2 ...(a slight pause).... but I think you are asking something related to conditional probability". The interviewer said yes. I then asked him to clarify the question once again as I was not able to understand anything. He said something which as ambiguous as his original question. Still, I said "Okay, let me try again." and I tried to find what kind of conditions can be applied to this problem. I spent a couple of minutes and gave him some answers like 1/4 and 1/2 again but those were not correct. He mentioned that I was thinking in the right direction but the answer was not correct, the correct answer was 2/3 somehow.


He then moved on to DSA. He asked how comfortable I was with DSA. I mentioned I can solve easy to medium questions. He then asked me two easy questions-

1. There is an array of balls. Each ball is of either of the three colours- red, blue, or white. Sort all the balls in a particular order- say all the reds first, then all the blues, then all the whites. Do this without taking any extra space.
   
2. There is a list of tuples- each tuple represents a customer- his arrival time and the time it takes to cook his order. There is only 1 cook in the kitchen who can cook only 1 dish at a time and must process all the dishes in the order they arrive. A customer places his order as soon as he arrives. Find the average wait time of all the customers.

</br>

Then he moved on to ML. He asked me what I have explored in ML and to explain my chatbot project. He asked me some questions related to Quantization and LoRA and then asked me if I knew about encoders and decoders. Thanks to what I reviewed after my first round, I was able to explain stuff easily. He then asked if I knew about how attention works in LLMs. I mentioned that I only have theoretical knowledge about this (while explaining what I know) and don't have a very intuitive or mathematical understanding of how attention works. He said it was fine and he was not expecting much since I mentioned I was only a beginner.


The interview ended here on a good note. When he asked if I had any questions, I asked about his background and his work at HiLabs. He mentioned that he was working mainly with generative AI and with LLMs. He then asked me what I wanted to do in the future. I said that I wanted to get some corporate experience and then maybe try research, primarily in generative AI and LLMs. He said that he was looking for this and the round ended here. Before leaving the call, I said "Thank you, it was nice talking to you. Have a good day! Bye". This time it was intentional and I wanted to leave a good impression.

</br>
I was almost immediately called to the HR round after only a couple of minutes.


### 3rd round (HR round): ~1.5 hr
The round started with the interviewer explaining that this would not be a technical round and rather she just wanted to have a chat with me and know me as a person.

She then asked me to tell me something about myself. I started by mentioning that I remembered her from the PPT which she was happy to hear. I gave my pre-prepared intro focusing on my background, family and education. She acknowledged that but said that she wanted to know more about me as a person and how I view myself. I tried to give an honest and balanced answer not trying too hard to impress. The interviewer was friendly and the rest of the round went similarly- questions were mainly focused on my behaviour and outlook towards life. Some of the questions which I remember are-

1. She asked me how I find conversing with people and if I find it difficult to have a conversation with people I don't know.
   
2. She asked how my school days were and whether I was very studious from the start.
3. She asked me about my friends, how big of a friend circle I have and my relationship with them.
4. She then asked me to pick 3 friends and describe them mentioning some unique qualities about them.
5. She then asked me what I think about How those 3 friends would describe me.
6. She then asked me what do I think about Banaras as a city and how do I find IIT-BHU as a place. (I gave a very beautiful answer to this thanks to all those reels)
7. She asked me what I like to do in my free time and what hobbies I follow.
8. She asked me about the clubs I was a part of and I led her into asking me about my decision to leave all other clubs to be the Jt. Secy of Astronomy Club (I had a very good answer prepared for this exact question)
9.  She asked me if I was a night owl or an early bird.
   
Situational questions-

10. She asked me if I had a conflict of opinion with a very senior manager then how I handled the situation.
    
11.  She asked if for example, the client is pushing for a very short deadline and if I know that I won't be able to able to deliver on time, what will I do in that case?

</br>
When she was done with her questions, I asked her some specific questions about HiLabs and its products that I had prepared while browsing their website. She was impressed by the questions and gave a very long answer which I just pretended to be interested in and was rather thinking about the next question that I wanted to ask her. I next asked her about where she was from about her background and how she joined HiLabs. She mentioned that she was from Dehradun and since I had previously said that I like to travel, we had a small chat and the round ended that way.

</br>


All interviews for all the 3 roles were completed by 5 am. They told us that the company will send the results by 6 am. I went to get some sleep as I had Infoedge and Ola in slot 1 but could not sleep at all. At around 6:30 am I got some hints that maybe results were already declared but could not get any solid info.

I went to DG2 at 8 am for slot 1 and around 9 am I finally got to know that the results were out and that I was the only guy selected in DS.


## Some tips-
1. Be confident. Have a genuine smile on your face.
   
2. Sense the mood of the interviewer- whether he is chill or a very serious guy.

3. Talk slowly- this will allow you to stay calm and choose your words wisely and not blabber nonsense. This is especially important when you are faced with a difficult question and need to stay calm.

4. Sense the motive of every question and what the interviewer is trying to assess. Decide how honestly you need to answer that- whether you can be completely honest, or if you are going to fake it, how much can you fake it without ruining it.

5. Show some inspiration or a purpose-driven work attitude. Have some solid reason for why you are doing what you are doing and show that you have the hunger to learn.


## How to spend the last few days before the D-Day
1. Do not start any fresh topic. Watching visual animations/videos is fine but know that you will forget that within 1-2 days because of the stress and anxiety.

2. Stop watching reels and doom scrolling and give your brain a break from months of rigorous study. Go take a walk, clear your brain, and take a shower.

3. If you have interviews in slot 0, synchronize your circadian rhythm accordingly. Wake up till late at night continuously for 2-3 before Day 0. Have a good sleep on 30th Nov. If you have your first interview in slot 1, sleep early the night before and try to get 8+ hours of sleep.

4. One of the things I felt in the last 1-2 days was I could feel my brain going numb and it felt like I did not remember anything that I studied. I was also emotionally numb- could not feel or react to anything properly. This was because of the stress and anxiety. The best method to feel good and clear your brain fog during this time is to hang out with anyone you can find who is chill and get a good laugh with them. This may be your roommate, PPO friends, family or even juniors. Coffee also helps.
   
5. Avoid people who put you under stress. Help them if you can.

6. Getting physically exhausted by taking a sprint or a jog is also a very good way to de-stress your body and mind but it is difficult in the last few days. If you are feeling tired at any point, try taking a walk.


</br>
</br>


Placement season gives you a unique experience. It is no doubt challenging and teaches you a lot of things. Believe in yourself and be confident of your grind.

Good luck ✨ and feel free to dm me if you need any help.