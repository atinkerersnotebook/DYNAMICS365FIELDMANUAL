# Configuring the User Defaults
The first thing that we will do in order to polish up our Dynamics 365 environment is to tidy up a couple of the user settings that have been missed when the system was initially deployed.  This includes setting a couple of the default user regional options and also setting the default company to be something other than the DAT company.

## How to do it…

Start off by opening up Dynamics 365 on the default workspace page.

![](images/image_1.png)

Now we will want to access the user options.To do this, just click on the gear icon in the top right hand corner of the form and select the User Options menu item.

![Click on the gear icon and select the User Options](images/image_2.png)

This will open the user Options form and we will be able to start making a couple of changes.

![](images/image_3.png)

Start off by clicking on the Preferences tab on the left hand side to show the default user preference options.

![Click on the Preferences tab](images/image_4.png)

The default Company is set to DAT when we first configure the system, but we will want to change this so that whenever we log in we go straight to the company that we want to transact in.  To do this we will want to click on the Company dropdown list and select the default company that you will want to log into from the dropdown list.In this case we will want to set it to USMF to log into the manufacturing company.

![](images/image_5.png)

![](images/image_6.png)

![](images/image_7.png)

Next we will want to specify a default date, time and number format for our user to match our regional preferences.  Out of the box, this is blank.To do this, click on the Date, time and number format fields dropdown list and select the region code that you want to use for the user.Here we will want to select the en-US option for US English.

![](images/image_8.png)

![](images/image_9.png)

Next we may want to change the default time zone that is associated with the user.To do this, just click on the dropdown list for the Time Zone and then select the users preferred time zone.For us it was already set to Eastern time so we will leave it at that for now. 

![](images/image_10.png)

![](images/image_11.png)

![](images/image_12.png)

![](images/image_13.png)

Now we will want to update the default preferences for the Account.To do this, click on the Account tab on the left hand side of the form. 

![Click on the Account tab](images/image_14.png)

Next we will want to configure some of the email defaults that are associated with the user.  To do this click on the Email provider ID and select the SMTP option.

![](images/image_15.png)

![](images/image_16.png)

Then, if check the Email address and make sure that it is the default address for your user account.  If it isn’t then you may want to update it.

![](images/image_17.png)

Next we will want to tweak some of the workflow options for the user account.  To do this, click on the Workflow tab to view all of the user workflow options.

![](images/image_18.png)

By default, email notifications are not sent to the user, but we want to enable that for our environment. To do this we just need to toggle the Send notifications in email switch.Here we want to have the notifications sent as emails so we will set the Send notifications in email switch to Yes.

![Set the Send notifications in email switch to Yes.](images/image_19.png)

### Step 1: Change the Send notifications to Action Center
To do this just switch the Send notifications to Action Center value.This time, we will want to click on the Send notifications to Action Center toggle switch and update it to the Yes value.

![Toggle the Send notifications to Action Center switch and make it Yes.](images/image_20.png)

Also if we have workflows that send out line level notifications then we will want to receive notifications individually so that we can approve them one by one. To do this we just need to select the Line-item workflow notification type option that we would like to use.Here we want to send a single email for each workflow task that we have been assigned so we will set the Line-item workflow notification type to the Individual option.Now we have configured the user defaults we can exit from the form.

![Click on the Line-item workflow notification type and select Individual](images/image_21.png)

![](images/image_22.png)

There are other tweaks that you can make here if you like, including changing the spacing of the fields, and also updating the default color for the workspaces.  These changes add small visual cues as to the system that you are logged into and can help you differentiate between user personas if you are logged into multiple users at the same time.But for now we have enough for our demo environment.

![](images/image_23.png)

