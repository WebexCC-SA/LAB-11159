# Location and basic calling setup

The goal of this chapter is to do the basic set up required to start making and receiving test calls using Webex Calling. This will include doing some organizational set up, configuring the first location and ordering phone numbers. This set up will lay the foundation for the rest of the work that we do in this lab.

## Organizational and service settings

- You can browse to Webex Control Hub [https://admin.webex.com](https://admin.webex.com) from your lab computer directly. Open Chrome browser from task bar & go to Collaboration Admin Links \> Cisco Webex Control Hub. 

- Once, you are logged in to the Control Hub, navigate to Organization Settings under the Management Menu.

  ![Screenshot: Once, you are logged in to the Control Hub, navigate to Organization Settings under the Management Menu.](./assets/image7.png)

- Scroll down to Control Hub’s Idle Time and select 4 hours and then click Save.

  ![Screenshot: Scroll down to Control Hub’s Idle Time and select 4 hours and then click Save.](./assets/image8.png)

- Click on Calling under the Services Menu in the left pane.

  ![Screenshot: Click on Calling under the Services Menu in the left pane.](./assets/image9.png)

- Click Settings on the top and scroll down to Call Recording. We want to ensure the default call recording provider is listed as Webex. If not, select Webex and click Save.  We also want to enable recording of Emergency Calls

  ![Screenshot: We want to ensure the default call recording provider is listed as Webex. If not, select Webex and click Save.  We also want to enable recording of Emergency Calls](./assets/image10.png)

- Scroll to Voicemail and create a default passcode, something like 113355 and then click Save.

  ![Screenshot: Scroll to Voicemail and create a default passcode, something like 113355 and then click Save.](./assets/image11.png)

## Location setup

- This Lab is provisioned out of a US Data Center and has the default location “Site1”. Locations allow us to define where we get dial tone, how we get to voicemail, 911 settings, unique call recording settings and even outbound calling privileges. Click on Locations in the left Menu, then click on the location “Site1”.

  ![Screenshot: This Lab is provisioned out of a US Data Center and has the default location “Site1”. Locations allow us to define where we get dial tone, how we get to voicemail, 9...](./assets/image12.png)

- Click ‘PSTN’ tab and then click ‘Manage’ in the “PSTN Connection” line.

  ![Screenshot: Click ‘PSTN’ tab and then click ‘Manage’ in the “PSTN Connection” line.](./assets/image13.png)

- Select Cisco Calling Plan and then click Next

  ![Screenshot: Select Cisco Calling Plan and then click Next](./assets/image14.png)

- Complete this form using Pod Name (really anything you want here is fine), your first name “WebexOne” and last name “user” and the admin email address provided for your pod and then click next (The confirm email address is case sensitive and cannot be pasted in).

  ![Screenshot: Complete this form using Pod Name (really anything you want here is fine), your first name “WebexOne” and last name “user” and the admin email address provided for y...](./assets/image15.png)

- When prompted, click “yes, change”

  ![Screenshot: When prompted, click “yes, change”](./assets/image16.png)

- As this is just a lab, using the information provided is sufficient. Scroll down to the bottom of the Emergency Disclaimer and enter Authorized Contact / Job Title and then click Agree and Continue in the bottom right.

  ![Screenshot: As this is just a lab, using the information provided is sufficient. Scroll down to the bottom of the Emergency Disclaimer and enter Authorized Contact / Job Title a...](./assets/image17.png)

- Next click Save to validate that the Emergency Service Address set up for the location matches the PSAP (Public Safety Answering Point) database.

  ![Screenshot: Next click Save to validate that the Emergency Service Address set up for the location matches the PSAP (Public Safety Answering Point) database.](./assets/image18.png)

- Assuming all goes well, you should see a screen like this. When ready, click Add numbers.

  ![Screenshot: Assuming all goes well, you should see a screen like this. When ready, click Add numbers.](./assets/image19.png)

- Make sure the tile labeled “Order New Numbers” is checked and then click Next.

  ![Screenshot: Make sure the tile labeled “Order New Numbers” is checked and then click Next.](./assets/image20.png)

- Based upon the physical address of Site1, numbers in California are pre-loaded. Select your desired area code, the quantity of numbers needed (5) and then select search.

  ![Screenshot: Based upon the physical address of Site1, numbers in California are pre-loaded. Select your desired area code, the quantity of numbers needed (5) and then select sea...](./assets/image21.png)

- For the sake of this lab the assigned numbers do not matter, but you could be more granular in your search, specifying a prefix and even choosing different numbers than the automatically added ones. When happy with your assigned numbers, click order.

  ![Screenshot: For the sake of this lab the assigned numbers do not matter, but you could be more granular in your search, specifying a prefix and even choosing different numbers t...](./assets/image22.png)

- Now that you have ordered numbers, you can click on View Orders to confirm the order status.

  ![Screenshot: Now that you have ordered numbers, you can click on View Orders to confirm the order status.](./assets/image23.png)

- This action hyperlinks you to the PSTN orders section under the PSTN & Routing section and you should see that your order has a pending status.

  ![Screenshot: This action hyperlinks you to the PSTN orders section under the PSTN & Routing section and you should see that your order has a pending status.](./assets/image24.png)

- If you click on the order ID, you should see a flyaway open and should now show the order status as provisioned.

  ![Screenshot: If you click on the order ID, you should see a flyaway open and should now show the order status as provisioned.](./assets/image25.png)

- From there, if you click PSTN & Routing, then the Numbers tab, you should see your new numbers loaded up in Control Hub.

  ![Screenshot: From there, if you click PSTN & Routing, then the Numbers tab, you should see your new numbers loaded up in Control Hub.](./assets/image26.png)

- Now that we have 5 Phone Numbers/DIDs, we will go back to our Site1 location and complete some final set up steps. Under Management in the left menu, click on Locations, Site1 and then the PSTN tab within the location. Based upon our previous efforts, you will notice that we have a PSTN connection type now defined (Cisco Calling Plan) but that we are missing a main number. This main number must be assigned for calling to work correctly. Click on the main number drop down and select one of your available numbers, then click save at the bottom right of the page. This action will clear up most of the previous warnings. This main number can still be assigned to Users, Auto Attendants, Call Queues, etc.

  ![Screenshot: Now that we have 5 Phone Numbers/DIDs, we will go back to our Site1 location and complete some final set up steps. Under Management in the left menu, click on Locati...](./assets/image27.png)

- Click on the calling tab within site one and within the calling features settings tile, select Captions for Webex Calling.

  ![Screenshot: Click on the calling tab within site one and within the calling features settings tile, select Captions for Webex Calling.](./assets/image28.png)

- Enable closed captions and call transcripts. Click on use custom settings and then enable both features and press save. You will be prompted to override the organizational setting and you want to accept this change. Then click the calling icon to take you back to the Site1 Calling setup page.

  ![Screenshot: Enable closed captions and call transcripts. Click on use custom settings and then enable both features and press save. You will be prompted to override the organiza...](./assets/image29.png)

- As we continue to work on the setup for our first location, click on the Voice Portal to enable all users/device in this location to access voicemail. If this is not set up, lines will not cover to voicemail nor will the voicemail key work on the phones.

  ![Screenshot: As we continue to work on the setup for our first location, click on the Voice Portal to enable all users/device in this location to access voicemail. If this is not...](./assets/image30.png)

- From here assign an extension 1234 for your voice portal and set your admin passcode at 113355, then click save.

  ![Screenshot: From here assign an extension 1234 for your voice portal and set your admin passcode at 113355, then click save.](./assets/image31.png)

- If you click on PSTN & Routing in the left menu and numbers, you will see all the new assignments and changes that we made to the numbering plan. (The screen below has more information than yours will)

  ![Screenshot: If you click on PSTN & Routing in the left menu and numbers, you will see all the new assignments and changes that we made to the numbering plan. (The screen below h...](./assets/image32.png)

