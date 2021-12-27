# Summary View - General Tab

## Addresses
| Test Case # | Action | Expected Result |
| --- | --- | --- |
| Add Address |  |  |	
| 1.1 | Pre-Condition: Open Case file exists with no existing addresses. | |	
| 1.2 |	Navigate to the General tab of the Open Case file. |	The address section shows 'No address on file.' |
| 1.3 |	 In the address section, click Add Address.	| The add address section opens. |
| 1.4 |	Without entering any text, click Submit. |	A message appears stating the following field is required: State. |
| 1.5 |	Complete the required fields and click Submit. |	The address is saved and the user is returned to the General tab. Address section displays the data entered in the previous step and now states, "1 on record". | 
| Edit Address | |		
| 2.1 |	Pre-Condition: Open Case file exists with existing address(es). At least 1 active and 1 inactive address exists. | |	
| 2.2 |	Navigate to the General tab of the Open Case file. | 	The address section shows 'X on record' where X is the number of addresses currently on record. |
| 2.3 |	 In the address section, click the edit button in the Address section. |	A popup opens with a list of existing addresses. |
| 2.4 |	Select the edit button next to the inactive address to be edited. | 	The Edit Address dialog opens. |
| 2.5 |	Update/change all of the fields and click Submit. |	The changes to the address are saved as expected. |
| 2.6 |	Edit the inactive address again. Move the Active Address, Mail Return and Verified slider buttons. Click Submit. |	The changes to the address are saved as expected. The previous active address is now marked inactive since there can only be 1 active address at a time. |
| 2.7 |	Edit the new active address. |	There is no slider button to mark the address as inactive. |
| Delete Address |	| |	
| 3.1 |	Pre-Condition: Open Case file exists with existing address(es). | |	
| 3.2 | 	Navigate to the General tab of the Open Case file. | 	The address section shows 'X on record' where X is the number of addresses currently on record. |
| 3.3 |	 In the address section, click the edit button in the Address section. |	A popup opens with a list of existing addresses. |
| 3.4 |	Select an address and click the delete button next to that address. |	A confirmation message appears asking if you are sure you want to delete the address. Yes/Cancel options are available. |
| 3.5 |	Select Cancel. |	The address is not deleted and the user is returned to the popup with a list of existing addresses. |
| 3.6 |	Select an address and click the delete button. Click Yes on the confirmation message. |	The address is deleted. The user is returned to the popup and the deleted address is not displayed. |
| 3.7 |	Click Close on the Address popup. |	The user is returned to the General tab of the Open Case file. The address section displays the new value for "X on record". |

## Demographics

| Test Case # |	Action | Expected Result |
| --- | --- | --- | 
| Demographics | | |		
| 1.1 |	Pre-Condition: Open Case file exists. | |	
| 1.2 |	Navigate to the General tab of the Open Case file. In the Demographics section, select the edit button. |	The Edit Demographics popup opens. |
| 1.3 |	Delete the data in each field and select Submit. |	A message appears stating the the required fields are: First Name, Last Name and SSN. |
| 1.4 |	Select the Individual radio button. Complete the requried fields and click Submit. |	Fields are saved the the user is returned to the General tab. |
| 1.5 |	Click the edit button again. Select the Business radio button. |	The First Name and Last Name fields are replaced with the Business Name field. | 
| 1.6 |	Complete the Business Name field and click Submit. |	Fields are saved the the user is returned to the General tab. |
| 1.7 |	Click the edit button again. Select the Individual radio button. |	The Business Name field is replaced with the First Name and Last Name fields. |
| 1.8 |	Enter a First Name and Last Name. Slide the 'Uses Alternate Name' button to the right. |	The 'Is Alternate Name an Individual or Business' question appears with Individual and Business radio buttons. |
| 1.9 |	Select the Individual radio button. |	Alternate First Name and Alternate Last Name fields appear. |
| 1.10 |	Complete the Alternate First Name and Alternate Last Name fields. Click Submit. |	Fields are saved as expected. User is returned to the General tab. The Alternate First and Last Name are displayed in the Demographics section. |
| 1.11 |	Click the edit button again. Change the 'Is Alternate Name an Individual or Business' radio button to Business. Enter an Alternate Business Name and click Submit. | 	Fields are saved as expected. User is returned to the General tab. The Alternate Business Name displayed in the Demographics section. |


## Assignments

| Test Case # |	Action |	Expected Result |
| --- | --- | --- |
| Assignments	|	| |
| 1.1 |	Pre-Condition: Open Case file exists.	| |
|1.2 |	Navigate to the General tab of the Open Case file. In the Assignments section, select the edit button. | 	The Edit Assignments popup opens. The available buttons are: Change Client, Change Workby, Change Paralegal, Change Category, Change County, Change Status, Change Responsible Attorney, Change Fee Basis, Change Type, and Changd Debt Type. |
|Change Client		| | |
|2.1 |	Select the Change Client button. |	The Change Client popup appears. 'Pick a new client' text box, 'Shoule the case file's fee basis change?' with yes/no radio buttons and 'Should the client number on invoices change?' with yes/no radio buttons. The 'No' options are selected by default on both questions. |
|2.2 |	Enter a new client. Select the 'Yes' response for both questions. Click Submit. |	Changes are saved as expected. |
|Change Workby		| | |
|3.1 |	Click the edit button on the Assignments section. Select the Change Workby button. | 	The Change Workby popup appears. The following fields are available: 'Pick a new workby' textbox, 'How do you want to change existing diary codes?' with the options 'Change All Dairy Codes to the New Workby', 'Change Only Dairy Codes Assigned to the Old Workby', and 'Do Not Change Any Diary Codes' options. 'Change Co-Case File to the new Workby' with the options: Yes/No. |	
|Change Paralegal | | |		
|4.1 |	Click the edit button on the Assignments section. Select the Change Paralegal button. |	The Change Paralegal popup appears. 'New Paralegal' text box, 'Change Workby of Diary Records' field with the options: None, Only Diary Records Whose Workby Is The Old Paralegal, and All Diary Records. |
|Change Category	| | |	
|5.1 |	Click the edit button on the Assignments section. Select the Change Category button. |	The Change Category popup appears. 'New Category' text box and 'Should prior transactions be changed to the new category code?' with Yes/No radio buttons. |
|Change County		| | |
|6.1 |	Click the edit button on the Assignments section. Select the Change County button. | 	The Change County popup appears. 'New County' text field is available. |
|Change Status | | |		
|7.1 |	Click the edit button on the Assignments section. Select the Change Status button. | 	The Change Status popup appears. 'New Status' text field is available. |
|Change Responsible Attorney | | |		
|8.1 |	Click the edit button on the Assignments section. Select the Change Responsible Attorney button. |	The Change Responsible Attorney popup appears. 'New Responsible Attorney' text field is available and 'Change Workby of Diary Record' question with the options of None, Only Diary Records Whose Workby Is the Old Paralegal (default) and All Diary Records. |
|Change Fee Basis		| | |
|9.1 |	Click the edit button on the Assignments section. Select the Change Fee Basis button. |	The Change Fee Basis popup appears. 'New Fee Basis' text field is available. |
|Change Fee Type	| | |	
|10.1 |	Click the edit button on the Assignments section. Select the Change Fee Type button. |	The Change Type popup appears. 'New Type' text field is available. |
|Change Debt Type	| | |	
|11.1 |	Click the edit button on the Assignments section. Select the Change Debt Type button. |	The Change Debt Type popup appears. 'New Debt Type' text field is available. |


## Hotkeys

| Test Case # |	Action |	Expected Result |
| --- | --- | --- |
| Hotkeys with Permissions		| | |
| 1.1 |	Pre-Condition: User has correct permissions to view the features. 	|
| 1.2 |	Alt+A |	Opens the Edit Addresses menu. |
| 1.3 |	Alt+D |	Opens the Edit Demographics menu. |
| 1.4 |	Alt+E |	Opens the Employers Menu. |
| 1.5 |	Alt+M |	Opens the Communication Methods menu. |
| 1.6 |	Alt+S |	Expands the Edit Assignments menu to make all of the "Change X" options available. |
| 1.7 |	Alt+T |	Opens the Third Party Contacts menu. |
| Hotkeys without Permissions		| | |
| 2.1 |	Pre-Condition: User does not have correct permissions to view the features. | 	
| 2.2 |	Alt+A |	A message appears stating user does not have permissions to view/edit the Addresses menu. |
| 2.3 |	Alt+D |	A message appears stating user does not have permissions to view/edit the Demographics menu. |
| 2.4 |	Alt+E |	A message appears stating user does not have permissions to view/edit the Employers Menu. |
| 2.5 |	Alt+M |	A message appears stating user does not have permissions to view/edit the Communication Methods menu. |
| 2.6 |	Alt+S |	A message appears stating user does not have permissions to view/edit the "Change X" options. |
| 2.7 |	Alt+T |	A message appears stating user does not have permissions to view/edit the Third Party Contacts menu. |


## Communication Methods

| Test Case # |	Action |	Expected Result |
| --- | --- | --- |
| Communication Methods - Phone | | |		
| 1.1 |	Pre-Condition: Open Case file exists with existing Communication Methods of phone number marked as "Primary".	| |
| 1.2 |	While on the Summary tab, select the edit button on the top right of the Communication Methods section. |	The Communication Methods menu opens. Any existing communication methods are listed. |
| 1.3 |	Click the Add New button. |	Add New Method of Communication popup opens. Types are are Phone Number (default) and Email Address. |
| 1.4 |	Without entering any information click the Submit button. |	A message appears stating the Phone Number field is required. |
| 1.5 |	Change Phone Type to Cell. | 	A new field appears stating, "Can Text" along with "Primary", "In Service", and "Authorized to use?" fields. | 
| 1.6 |	With the Phone Number radio button selected, enter values in the Phone Number, Extension, Time Zone, Phone Type Weekday Start Hour, Weekday End Hour, Weekend Start Hour, Weekend End Hour, and Comments fields. Click Submit. |	User is returned to the Summary tab. Communication Method fields are saved as expected. |
| 1.7 |	Select Communication Methods>Edit and edit the phone entry from the previous step. Mark the "Primary" option. Click Submit. |	The user is returned to the Summary tab and the communication method has been updated with the phone entry now showing "Primary". The previous "Primary" contact phone number no longer as a green check box. |
| Communication Methods - Email		| | |
| 2.1 |	Pre-Condition: Open Case file exists with existing Communication Method of email marked as "Primary".	| |
| 2.2 |	Select the Communication Methods edit button again. Click Add New. |	The Add Communication Methods popup opens. | 
| 2.3 |	Change the "Method of Communtication" button from Phone Number to Email Address. |	The Phone Number fields are replaced with "Email Address" and "Email type". |
| 2.4 |	Without entering any information click the Submit button. |	A message appears stating the Email field is required. |
| 2.5 |	Enter a value in the Email Address. Click Submit. |	User is returned to the Summary tab. Communication Method fields are saved as expected. | 
| 2.6 |	Select Communication Methods>Edit and edit the email entry from the previous step. Mark the "Primary" option. Click Submit. | 	The user is returned to the Summary tab and the communication method has been updated with the email entry now showing "Primary". The previous "Primary" email no longer as a green check box. |
| Next Contacted By		| | |
| 3.1 |	Pre-Condition: Open Case file exists with at least 1 existing Communication Method. | |	
| 3.2 |	Select the Communication Methods edit button. Select a line item and click the edit button. |	The lowest section shows "Next Contacted By", "Next Contact Date" and "Next Contact Time". |
| 3.3 |	Enter a value in the  "Next Contacted By", "Next Contact Date" and "Next Contact Time" fields. Click Submit. | 	Field values are saved as expected. Does this triger a queue? |


## Employers

| Test Case # |	Action |	Expected Result |
| --- | --- | --- |
| Employers		| | |
| 1.1 |	Pre-Condition: Open Case file exists.	| |
| 1.2 |	Navigate to the General tab of the Open Case file. In the Employers section, select the edit button. |	The Employers popup opens. Any existing employer is listed on the popup. |
| Add Employer		| | |
| 2.1 |	From the Employers popup, click Add New. |	The Add New Employer popup opens. |
| 2.2 |	Without entering any information, click Submit. |	A message appears stating you must complete the required fields. |
| 2.3 |	Complete the fields on the New Employers page and click Submit. |	The user is returned to the Employers popup and fields are saved as expected.|
| Edit Employer		| | |
| 3.1 |	Select an Employer record to be edited. Complete all of the fields and click Submit. |	Employer record is saved as expected.	|	
| Delete Employer	| | |	
| 4.1 |	On the Employers page, select a record and click the Delete icon. |	A confirmation message appears. |
| 4.2 |	Select Cancel on the confirmation message. |	The record is not deleted. |
| 4.3 |	Select the employer record again and click Delete. Click 'Delete This Employer' on the confirmation message. |	The employer record is deleted and no longer appears on the employer list. 		|
| Employer Template		| | |
| 5.1 |	Pre-Condition: An Employer Template has been set up in the Maintenance section of the application.  | |	
| 5.2 |	Navigate to the General tab of the Open Case file. In the Employers section, select the Add button. |	The Add New Employer popup opens. |
| 5.3 |	Observe the Employer Template drop down. |	The Employer Tempate drop down is populated with all Employer Template items on the Maintenance page. | 
| 5.4 |	Select an item from the Employer Template dropdown. | 	All available fields on the Employer page is populated as expected. |
| 5.5 |	Edit the fields that were populated by selecting the Employer Template option. |	The pre-populated fields are editable. |
| 5.6 |	Click Submit. |	The empoloyer record has been added. |


