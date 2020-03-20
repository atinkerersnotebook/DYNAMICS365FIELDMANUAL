# Using Excel to Update the User Details
Updating a user manually is a good option if we have just a couple of users.  But for our demo system we have about 120 users that we need to update.  So we will want a quicker way to update the users through Excel.

## How to do it…

To do this, click on the Office icon in the menu bar and then select the OPEN IN EXCEL User Information option.

![](images/image_1.png)

This will open the Open in Excel dialog box, and we will want to click on the Download option. 

![](images/image_2.png)

![](images/image_3.png)

When the file confirmation dialog box is displayed, click on the Open option.

![](images/image_4.png)

This will open an Excel template in read only mode.To make this a live worksheet just click on the Enable Editing button.

![](images/image_5.png)

![](images/image_6.png)

![](images/image_7.png)

This will populate all of the current users within the worksheet.But the email address is not showing up in the default worksheet so we will want to modify the columns that are returned in the worksheet.To do this, click on the Design link within the add in.

![](images/image_8.png)

This will switch the add-in to Design mode.Now we will want to add a new field.To do this click on the pencil icon to the right of the SystemUser table. 

![](images/image_9.png)

This will open the table details and we will be able to see the selected fields, and also all of the available fields.Now we will want to add in the Alias – Email field as a column.To do this, select the Alias – Email field and then click on the Add button.

![](images/image_10.png)

![](images/image_11.png)

This will add the field to the selected fields.Now just click on the Update button.

![](images/image_12.png)

This will show a message box that will ask us to confirm the update.Just click on the Yes button.

![](images/image_13.png)

Now we will see that there is a new column in the worksheet for the Email address, but it is blank.All we need to do is click on the Done button.

![](images/image_14.png)

And then click on the Refresh link within the add-in.

![](images/image_15.png)

This will open another confirmation dialog box.Just click Yes.

![](images/image_16.png)

When the worksheet is refreshed we will be able to see all of the email addresses for all of our users.

![](images/image_17.png)

![](images/image_18.png)

![](images/image_19.png)

Now just do a mass Find and Replace and replace the contosoax7 domain prefix with the name of the tenant that Dynamics was deployed through.

![](images/image_20.png)

This will update all of the email addresses to match the tenant account.

![](images/image_21.png)

Now we will want to update all of the user accounts within Dynamics 365.To do this, click on the Publish button within the add-in.

![](images/image_22.png)

That will push all of the changes back to Dynamics 365.

![](images/image_23.png)

![](images/image_24.png)

![](images/image_25.png)

If we look at any of the users within Dynamics 365 then we will see that all of the email addresses have been updated.Now we can close out of the form.

![](images/image_26.png)

We know that this is probably not the most exciting update to make to the Dynamics 365 users, but if we want to use the other personas we might as well get it out of the way.

![](images/image_27.png)

