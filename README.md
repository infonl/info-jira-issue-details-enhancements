# jira-issue-details-enhancements
Enhance your JIRA issue details page

Creates nice copypasteable text in JIRA issue page, including copy-to-clipboard-button

This text can be used for instance in copyTextSlack
- Format: ISSUEID - Issuetitle
- Format: ISSUEID - Issuetitle (StoryPoints)  
The ISSUEID is linked to the story  
- Example DBI-2334 - Create new form (8)


![Screenshot](https://raw.githubusercontent.com/infonl/jira-issue-details-enhancements/main/Screenshot%20Issue%20details.png?token=AGHGX76TF42B3WUL2IY6SLC77VRRE "Screenshot")


## INSTALL
1. Install 'User JavaScript and CSS' extension for Chrome https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en
2. Open a random JIRA issue in your browser. The url probably contains "/jira/browse/" now.
3. Click 'User JavaScript and CSS' icon in Chrome (Blue/red dotted lines-icon)
4. Click 'Add new'
5. fill in:
 - Name: JIRA issue details
 - URL: replace url by `*/browse/*`
 - Options: enable JavaScript and JQuery 3
 - Open https://raw.githubusercontent.com/infonl/jira-issue-details-enhancements/main/js%2Cjs in a browser tab and copypaste this whole script in the JS-pane. Keep CSS pane empty
6. Save
7. Go to JIRA issue and refresh. The copypasteable link should appear now directly under the issue action buttons [Edit | Comment etc].
