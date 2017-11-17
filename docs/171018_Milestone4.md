Report 4

Kyung Je Jo (20130799)

Chae-Ryn Chang (20150893)

John Joon Young Chung (audit) 

**Problem Statement**

It is challenging to fully and quickly understand solutions and explanations from existing question answering sites and solution booklets.

**Tasks:**

List three core tasks you've decided to support in your prototype. Again, you can reuse or improve what you had earlier.

* Prevent spammer or incapable users from answering the every user’s question

* User wants a time-effective and interactive question-answering mechanism that helps him fully understand the underlying problem concept

* User is motivated to use the application more because the user wants to accomplish achievements offered by the application.

**Prototype**

**Tool description & justification**

MarvelApp

Our team built low-fi prototype on MarvelApp. We simply chose to use Marvel because one of our team has experiences in using MarvelApp. Compared to InVision and proto.io, Marvel provides an interface that is easy for collaboration at no additional charge.

Things we liked about Marvel

Marvel was very well synchronized when our team worked together to build the prototype. It also provided a set of useful pre-made items such as input boxes and dialogs which were highly time-saving. In addition, Marvel provided alignments guidances which were as good as those of Microsoft Powerpoint. 

Things we disliked about Marvel

Marvel was often very slow, even pausing time by time, and the interface was not user-friendly. For example, Marvel did not provide cropping, which was surprising. Marvel was very inconvenient when we wanted to work on multiple pages within the same browser; moreover, command+click did not open a new tab. It was a bit annoying that all textboxes needed to be double-clicked in order to select them. 

**Design Choices**

We attempted to focus mainly on end-to-end scenario, avoiding all unnecessary details. For example, we only provide users to choose specified value from dropdown lists and users cannot answer the questions prompts that are used for controlling the quality of users that enter the system (they are rather forced to see only the flow of the controlling technique). We decided to do so because we wanted to show end-to-end scenario where users enter the system and answer others’ question in the system. 

We also tried to show how the chatting session was user-oriented, in that the user could begin the session with the desired worker and end the session by pressing the understood button. Such workflow is very time-efficient for the user, who can allot only the necessary amount of time he/she wants. Also, the understood button and the short quiz at the end verify that the worker does not leave until the user fully gets the concept. We did not include specific chat contents of the worker-user because such are trivial details that do not really reflect our design goal.

We did not show all gamified goals because some of them are similar and only differ by their requirements. Also we did not implement how goals that can be achieved in future are shown to users. In real implementation, the variety of goals being shown to users will depend on what users have accomplished before.

**Instructions**

1. Please understand that only specified buttons can be clicked and most of input boxes will not be editable.

2. To find which buttons are clickable, try to click white-spaces. Marvel will highlight clickable spots with blue rectangle. 

3. Lastly, the end-to-end scenario will help you traversing our prototype.

End-to-end scenario

1. A user will open SwiftyQ app for the first time

2. The user will need to sign up

3. As the user selects his/her expertise, the app will attempt to verify the chosen expertise using gold data (however, you will not be able to manually answer the questions in the prototype because we want everyone to experience the full scenario)

4. Only when the user passes all questions, the account will be created

5. The user can fill in a request form of the question in a specified category.

6. A live chatting session is initiated as soon as the user accepts the worker’s appeal.

7. After the worker attempts to answer the question, user presses the understood button if she understands the explanation.

8. User takes a quick quiz to make sure she understood.

9. User can rate the worker immediately (or wait until she confirms the answer).

10. While the user explains problems for others and post questions, if she meets requirements necessary for the gamified goals, then she will be rewarded with achievements. The dialogue will notify that she accomplished certain goal.

11. The user also can check how much achievements she have made, and what achievements she can make in the future by viewing achievement screen.

**Observations**

Participant 1 (P1) - KAIST Undergraduate, Department of Mechanical Engineering, 22 years old

Participant 2 (P2) - KAIST Undergraduate, Department of Mechanical Engineering, 21 years old

Participant 3 (P3) - A female college graduate, 31 years old

User-oriented

1. Pre-recruitment system of queuing workers does not consider the perspective of the workers, who may have to wait a long time before answering the question, or may not even get a chance to answer, after they accept the task. (P2)

2. The user should get a chance to choose whether or not to take a quiz after pressing the understood button. (P2)

3. Could not expect what the system would do after clicking Understood? button while receiving worker’s solution (P3)

real-time/time efficiency

1. It does not provide list of top questions for each subject which may lead to time-efficiency (P1)

quality control

1. It does not have any systematic way to prevent duplicate questions in the long-term (P1)

2. The reason why the app questions users when signing in is not explained in enough detail (P1)

Design

1. There is no reason for having a profile picture (P1)

2. A user would prefer succinct prompts when using an app (P1)

3. Achievement font does not match the font for other parts of the app (P2)

4. Could not grasp what the visualization of achievement meant (P3)

5. Could not get what number that represent number of accessible question meant (P3)  

**ScreenShots:**

![image alt text](image_0.png) 

Registration - When the user signs in, the user is required to select his/her expertise.

![image alt text](image_1.png) 

1st quality control - SwiftyQ will attempt to verify user’s expertise using three simple questions with gold data

![image alt text](image_2.png) 

2nd quality control - the user who made a question will evaluate the user who answered the question. The ratings will collectively be used for long-term quality control.

![image alt text](image_3.png)

When a user satisfies a condition, the achievement is given to the user.

![image alt text](image_4.png)

A user can view her own achievement progress and also see achievements that she can achieve in the future. 

![image alt text](image_5.png)              worker end of the platform --->  ![image alt text](image_6.png)

The user can submit request and designate a specific category, so that the program pools its workforce from workers of matching expertise. As the user is typing a question in that category, the program pre-recruits workers by sending push alarms.

 

 

![image alt text](image_7.png)

Because we employ a form of pre-recruitment, the user will get nearly real-time feedback from available workers. 

![image alt text](image_8.png)

Picture of the live chatting session with worker; after worker explains the problem to the user, the user can press the understood button to end the chatting session.

![image alt text](image_9.png)

After the user presses the understood button, she takes a quick quiz to make sure she understood.

