# Verification of Webex AI Calling features

Lets login to the Webex app(s) with the two end user accounts 1. Paralegal and 2. Attorney.

## Sign in to the Paralegal Webex app

1. Open the Webex app in the Laptop that you are using.

2. Enter the email address of the Paralegal user – make sure to use the Paralegal email address of your pod. If you are not sure of the email address, navigate to Users page in the Control Hub and get the email address. Click “Next”

    ![Screenshot: Enter the email address of the Paralegal user – make sure to use the Paralegal email address of your pod. If you are not sure of the email address, navigate to Users...](./assets/image66.png)

3. Enter the User password as “WebexOne2026!” and click “Sign In”

    ![Screenshot: Enter the User password as “WebexOne2026!” and click “Sign In”](./assets/image67.png)

4. Click “OK” in the Emergency Calling Notification screen. Please do not dial 911 during the lab

    ![Screenshot: Click “OK” in the Emergency Calling Notification screen. Please do not dial 911 during the lab](./assets/image68.png)

5. Click “Calling” tab in the left pane of the Webex and you should a screen similar as this

    ![Screenshot: Click “Calling” tab in the left pane of the Webex and you should a screen similar as this](./assets/image69.png)

## Access the second workstation

1. Now, click the following link and obtain a dCloud pod.

2. click this [link](https://www.ciscodcloud.com/apps/expo/db3dxike9xqe4tz8gxyslj8u0) to open the dCloud eXpo page and you should see this below page

    ![Screenshot: click this link to open the dCloud eXpo page and you should see this below page](./assets/image70.png)

3. Click ‘Explore’.

4. You will then be asked to enter your email address, please enter your email address. Check the box to agree to terms & conditions and then click “Launch”.

    ![Screenshot: You will then be asked to enter your email address, please enter your email address. Check the box to agree to terms & conditions and then click “Launch”.](./assets/image71.png)

5. We will be using Workstation1 (wkst1) for our lab. The machine can be accessed by clicking the “Open” option next to it.

    ![Screenshot: We will be using Workstation1 (wkst1) for our lab. The machine can be accessed by clicking the “Open” option next to it.](./assets/image72.png)

6. Repeat steps 2-4 for the “Attorney” user and login. You should see a screen similar as follows for the Attorney user

    ![Screenshot: Repeat steps 2-4 for the “Attorney” user and login. You should see a screen similar as follows for the Attorney user](./assets/image73.png)

Now we have both the users logged in to their Webex app in two machines.

## Test the AI Receptionist

1. Navigate back to Control Hub and click “PSTN & Routing” under Service in the left pane. You should see the Numbers tab

    ![Screenshot: Navigate back to Control Hub and click “PSTN & Routing” under Service in the left pane. You should see the Numbers tab](./assets/image74.png)

2. Make a note of the “AI Receptionist” number

    ![Screenshot: Make a note of the “AI Receptionist” number](./assets/image75.png)

3. Now from your Cellphone / mobile, dial this 10-digit number. Please note, use the number from your Control Hub and not the number from the above screenshot.

4. The AI Receptionist answers the call and it will read the “AI Transparency” message followed by the “Welcome Message”.

5. Remember, we have setup a Knowledge base for our AI Receptionist with some Law Firm FAQs. Lets go ahead and test this functionality.

6. Ask the AI Receptionist questions such as A). what is working hours of the firm? B). what is the address of the firm. C). what services are offered by the firm? You can always refer to the Knowledge base document and make sure the AI receptionist is giving you the correct answers.

7. Once you have tested that, lets now ask the AI receptionist to transfer the call to the Paralegal team. It will confirm your transfer request and the call is now seen on the Paralegal’s Webex app as shown below

    ![Screenshot: Once you have tested that, lets now ask the AI receptionist to transfer the call to the Paralegal team. It will confirm your transfer request and the call is now see...](./assets/image76.png)

8. Lets go ahead and answer this call, you can see the Caller ID shown and also the call being forwarded from the AI Receptionist.

    ![Screenshot: Lets go ahead and answer this call, you can see the Caller ID shown and also the call being forwarded from the AI Receptionist.](./assets/image77.png)

## Test the AI Assistant and live transcript

1. The important piece for us is the AI Assistant option, lets go ahead and click on that option

    ![Screenshot: The important piece for us is the AI Assistant option, lets go ahead and click on that option](./assets/image78.png)

2. You will now see the Cisco AI Assistant for this Call open up on the right side. This window indicated that the Call is being summarized and the transcript is on.

    ![Screenshot: You will now see the Cisco AI Assistant for this Call open up on the right side. This window indicated that the Call is being summarized and the transcript is on.](./assets/image79.png)

3. You can click on Catch me up and check the summary

    ![Screenshot: You can click on Catch me up and check the summary](./assets/image80.png)

4. You can then click the “Prompts” and click “Find” and choose the option “Give me more info about \[topic\]” – replace the word \[topic\] with what is relevant to your call. For example, here it is about the case.

    ![Screenshot: You can then click the “Prompts” and click “Find” and choose the option “Give me more info about topic” – replace the word topic with what is relevant to your call. ...](./assets/image81.png)

5. You will then the Cisco AI Assistant gives you more info about the call and the “Source” for the info

    ![Screenshot: You will then the Cisco AI Assistant gives you more info about the call and the “Source” for the info](./assets/image82.png)

6. There is indication in the top-right to denote the Call Recording and the Call Summarization is in-progress

    ![Screenshot: There is indication in the top-right to denote the Call Recording and the Call Summarization is in-progress](./assets/image83.png)

7. You can also click the “Transcript” icon on the bottom right-corner to look at the live call transcript.

    ![Screenshot: You can also click the “Transcript” icon on the bottom right-corner to look at the live call transcript.](./assets/image84.png)

    ![Screenshot: You can also click the “Transcript” icon on the bottom right-corner to look at the live call transcript.](./assets/image85.png)

## Transfer the call with its summary

1. Now lets try transferring the call to the Attorney and share the Call summary with the Attorney. Click the 3 dots (…) and then click “Transfer”

    ![Screenshot: Now lets try transferring the call to the Attorney and share the Call summary with the Attorney. Click the 3 dots (…) and then click “Transfer”](./assets/image86.png)

2. Now you will see the following screen, notice the “Include the call summary” option enabled in the bottom – this will ensure we are transferring the call with the summary to the other party.

    ![Screenshot: Now you will see the following screen, notice the “Include the call summary” option enabled in the bottom – this will ensure we are transferring the call with the su...](./assets/image87.png)

3. Now lets click the “Preview” option here and we can see the Call Summary that is about to be shared during the Transfer. If needed and there is a requirement to edit the summary, click the pencil icon and edit/modify the summary.

    ![Screenshot: Now lets click the “Preview” option here and we can see the Call Summary that is about to be shared during the Transfer. If needed and there is a requirement to edit...](./assets/image88.png)

4. Once you made the changes, click “Back to Selection”

5. Now enter the Attorney extension 1001 and hit “Transfer now” button

    ![Screenshot: Now enter the Attorney extension 1001 and hit “Transfer now” button](./assets/image89.png)

6. In the Attorney Webex app, you should now see the Call ringing. You can answer the call by clicking the “Green” button but before that, notice the “Caller Intent” – this is a Webex Calling AI feature to give the caller information about the caller intent even before answering the call

    ![Screenshot: In the Attorney Webex app, you should now see the Call ringing. You can answer the call by clicking the “Green” button but before that, notice the “Caller Intent” – ...](./assets/image90.png)

7. After answering the call, the Attorney can now see the Caller Intent and the Transfer Call Summary show up

    ![Screenshot: After answering the call, the Attorney can now see the Caller Intent and the Transfer Call Summary show up](./assets/image91.png)

8. Once you have reviewed the info, you can now disconnect the call.

## Review post call summaries and recordings

1. Now return back to the Paralegal Webex Workstation and you might see this notification in the bottom right-corner. This is indicating us that the Call Summary for the call is ready now. Click the “Close”button for now.

    ![Screenshot: Now return back to the Paralegal Webex Workstation and you might see this notification in the bottom right-corner. This is indicating us that the Call Summary for th...](./assets/image92.png)

2. Click the “Calling” tab in the left pane of the Webex app and then click “All”. You should see all the call list here.

    ![Screenshot: Click the “Calling” tab in the left pane of the Webex app and then click “All”. You should see all the call list here.](./assets/image93.png)

3. Click the “AI Summary” icon in the Call list to view the AI Summary.

    ![Screenshot: Click the “AI Summary” icon in the Call list to view the AI Summary.](./assets/image94.png)

4. You can now see the “Short Summary” of the call

    ![Screenshot: You can now see the “Short Summary” of the call](./assets/image95.png)

5. Click “Call Summary” to view the full Call Summary and the Action items from this call

    ![Screenshot: Click “Call Summary” to view the full Call Summary and the Action items from this call](./assets/image96.png)

6. Close the Call Summary window after reviewing the info.

7. To access the Call recordings, click the Recording tab in the top. You will be able to see the list of Call Recordings, click on a particular call and click the Play button to listen to the Call Recording.

    ![Screenshot: To access the Call recordings, click the Recording tab in the top. You will be able to see the list of Call Recordings, click on a particular call and click the Play...](./assets/image97.png)

This completes the lab!

Thank you!

