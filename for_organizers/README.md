# Helpful Communication Templates for Organizers

This directory holds files that are useful for workshop organizers.  If you're a student, the stuff here probably isn't very interesting for you.  Still, feel free to look around and learn... or get this workshop off the ground in your context, using these tools to help you.

## Using the rmd files for workshop communication

This folder contains rmd files that are [parameterized reports](https://bookdown.org/yihui/rmarkdown/parameterized-reports.html). That means you can change the parameters at the top and then knit to have the report update with the new information. Parameters include the following:

- contact person (generally the team member sending all these emails)
- contact email (their email)
- workshop date, including start time (duration assumed to be 5h)
- number of participants able to sign up
- tech check date, including start time (duration assumed to be 30m)
- link to signup
- link to pre course survey
- link to post course survey
- link to course website


To generate the text for emails for a new workshop, you should be able to update just the parameters and knit, then copy-paste the resulting html into your email and send. 

**Note:** The text of the post-workshop email will change depending on the conversation that arises during the workshop. Update it as needed based on the chat record from Teams.

There is an R file of functions that get used in the rmd reports (communication_functions.r). 

## Additional tasks

### Check signups and move folks from wait list

After the initial workshop invite goes out, you'll need to keep checking the signup form daily for new people and add them to the invites for the workshop and tech check. If there's a wait list, then as people email to drop their registration, contact people from the wait list to offer them the spot. 

### Recruit TAs

Keep an eye on registrations to see if you recognize folks who have already taken the workshop in the past. If so, reach out to them and ask if they'd like to try TAing instead (see FAQs for workshop TAs in 01_announcement). Also post in the R User Group slack, and contact the Data Ambassadors. 

### Teams info

In addition, you'll need to set up Teams meetings for the tech check and workshop, and then copy-paste that Teams login information into the calendar invites for each (02_workshop_invite and 03_tech_check_invite, respectively).

When setting up the meeting for the workshop, ensure that [attendance reports are turned **on**](https://support.microsoft.com/en-gb/office/manage-meeting-attendance-reports-in-microsoft-teams-ae7cf170-530c-47d3-84c1-3aedac74d310#ID0EDBD=Desktop). In order to see these options, you'll need to be scheduling the meeting via the Teams app, rather than through Outlook calendar. 

### Save chat record during meeting

Right after the Teams call for the workshop ends, save the chat record. You'll need this to update the post-workshop email. Since CHOP has a policy of only keeping meeting chats for a short period of time, you'll want this to ensure you're covered.

Unfortunately, Microsoft Teams doesn't have a good way to export the chat from a meeting. To save, highlight all of the text in the chat (Ctrl/Cmd + A) and copy it. Then, paste this into a Word document. Depending on how long the chat record is, it may not copy everything at once. To ensure you have it all, check the beginning and end of the document to make sure you've captured the true first and last messages. If there's some portion missing, repeat this process for that section of the chat history, until you have everything. 

### Attendance record

After the workshop, download the attendance report. 
For instructions on how to do this, see the "After the meeting" section of [the same attendance report how-to article linked earlier in this README](https://support.microsoft.com/en-gb/office/manage-meeting-attendance-reports-in-microsoft-teams-ae7cf170-530c-47d3-84c1-3aedac74d310#ID0EDBD=Desktop).



Then, use this list to update attendance in redcap with attended vs cancelled vs no showed. 
