# Document Management

## 	DOCUMENT CONFIRMATION

### **Preconditions** - Settings > Firm Settings - Word Processing  
1. Word Processing Executable Command should be winword for MS WORD  
2.	Place the attached word merge file for the test (is using word) in the Forms Path and name it "tst.frm"  
3.	Forms Path example - c:\cpx\forms  
4.	Edit or add a Maintenance > Action document TST					

### **Instructions**
1.  Schedule Documents  
    1. 	Case Files > Case Management					
    3.	Search for a case					
    4.	Select Case
    5.	Select the Diary Quick Action					
    6.	Enter Diary Action TST					
    7.	Select an Assigned Workby
    8.	Leave 3 Diary Dates as Current Date 2 future dated
    9.	Enter a comment like "Test scheduled today" or Test future dated	
    10.	Do above steps on 5 different cases  
2.	Worklist Configuration for Word Processing Only					
    1.	Document Management > Worklists - Click (+) to add					
    2.	Create a Worklist configuration to run for Document Generation  
    2.	If required assign a worklist ID
    2.	Enter a description like Word Processing Only					
    2.	Select a beginning date that will pick up the Back Dated diary and Ending Date of the current date					
    2.	"Turn on…; All Workbys?; Recreate Unconfirmed Documents"
    2.	For Print Detail Worklist select Print Word Processing Only
    2.	Submit					
3.	Run the Worklist					
    1.	Click the Play button on the Worklist just created					
    3.	Process Runs (Worklist create succesfully)					
    3.	Click Show Me the Worklist					
4. 	Worklist Report with 5 tabs: "Summary Worklist, Detail Worklist, Merge Files, Court, Docket"  					
     1.	Click the Merge Files tab					
5. 	Merge the TST document					
    1.	Open Word and navigate the CPX\Forms directory and open tst.frm			
    5.	Merge the TST.mrg with the TST.frm  
a. Click the Mailings Tab  
b. Click the Start Mail Merge drop down and select ""LETTERS""  
c. Click Select Recipients dropdown and select ""USE AN EXISTING LIST""  
d. Navigate to CPX forms (at the bottom right of Select Data Source dialog select All Files)  
e. Select TST.mrg  
f. Click Finish & Merge dropdown and then EDIT INDIVIDUAL DOCUMENTS and ALL for Merge to a New Document  
g. The data from the mrg file creates a letter for each case included in the merge.  					
    5.	Review each record to ensure the correct cases are included based on the date scheduled.	
    5.	Save each case letter separately to c:\cpx\imagepath and save it as PDF with the name \<DOC ACTION>-\<CaseID>-\<MMDDYYYY>.pdf					
6. 	Review the merged records					
    1.	Check the field location on cases and ensure available data is merge into the form					
7.	Confirm Documents					
    1.	Visit each case from the test group and review the diaries					
    7.	Observe the Status of Confirmation Needed on those included in the merge	
    7.	Observe the Status of Ready to Merge on the future dated cases
8.	Document Management > Confirm Documents					
    1.	Observe all the cases showing as Confirmation Needed are also listed for confirmation on this screen	
    8.	Observe those showing Ready to Mergre are not listed
9.	Confirm or Reset Individual Documents					
    1.	Confirm 2 of the 3		
    9.	Enter the path and name from 5.4 for the case's imagepath			
    9.	Reset the third
10.	Review cases in Case Management					
    1.	Observe the first of the confirmed cases are no longer in the diary but now are shown in the history and document history		
    10.	Observe that the reset document remains in the diary status Confirmation Needed			
    10.	Go back to Document Management > Document Confirmation and turn on Confirm All? Confirm (do not enter the image path for this one)
    10.	Go back to Case Management on the case previously reset and observe the action is in the history now and not the diary			

## 	Extract Variables
### **Preconditions**
Test documents under 1 and 2 by saving them to your cpX forms directory

### **Instructions**
1. 	Extract Variables
    1.	Document Management > Extract Variables
    1.	Form - Click drop down and select the tsts.frm or other test doc
    1.	Form Type - Select cpX or Collection Master
    1.	Click Add
    1.	Repeat steps above for each a sample CM form
    1.	Click Submit
    1.	Wait…
    1.	Extract Variables Summary Grid displays  
2.	Extract the Variables
    1.	Click on the first form
    2.	Click the download Export Options icon top right
    3.	Click CSV and the Save As Dialog appears. Name the file and click Save
    4.	If csv file extension has an associated software like Excel, the file will open automatically, otherwise find it in the directory you saved it to for review.
    5.	Click JSON and the Save As Dialog appears. Name the file and save
    6.	If json file extension has an associated software, the file will open automatically, otherwise find it in the directory you saved it to for review.
    7.	Repeat steps for 2 on the CM form


## 	Missing Documents
### **Preconditions** - Document Confirmation without and Image path  
a.	Doc Confirmation 10.3 with no image path  
b.	Case Management - Document History Quick Action - Enter a document without an image path  

### **Instructions** - Find missing documents
1.	Document Management > Missing Documents
1.	Document confirmed in Doc Confirmation 10.3 is listed
1.	Document entered from Quick Action Document History without an image path is listed
	
## 	Redaction Template
### **Preconditions** -	Prepare pdf version of document action to create a template
a.	If it does not exist, create path c:\cpx\redaction_templates  
b.	Take the redact.frm test document embedded herewith and open in in Word and save it as redact.pdf to c:\cpx\redaction_templates  

### **Instructions** - Create Redaction Template
1.	Document > Redaction Template
1.	For "Document" click dropdown and select the document action that the template should be associated with
1.	For "PDF to Use for the Redaction Template" click the folder button and navigate to redaction_templates and select the tst.pdf
1.	Select the redaction areas with the "Rectangle" tool and Submint
1.	Redaction Template is saved

## 	Redact Documents
### **Preconditions** - Redaction Template
1. Create a Redaction Template using the test case Redaction template  

### **Instructions**
1.	Redact Documents  
    1.	Select Document Management > Redact Documents
    2.	Select the Source Folder. This is where the un-redacted pdf files are saved  
2.	Saving Redacted Document
    1.	Select one of the Redaction Templates
    2.	Select to delete or overwrite source documents with the 2 toggles
    2.	Select the "Folder for Redacted Documents" (This is where the redacted version will be saved
    2.	Enter _redacted for "Filename Suffix To Use For New Document"
3. 	Handling Error Documents
    1.	Select NO for Disregard Errors and Do Not Save Copies
    3.	Enter the path for documents that error 
    3.	Enter the "_error" for "Suffix for Errored Documents"
    3.	Click Apply Redactions
4.	Review the "Folder for Redacted Documents"
    1.	Review the redacted versions 
    4.	Ensure the _redacted suffix
    4.	Review any error versions with the _error suffix

## Unassigned Documents - Empty

## 	Worklists
### **Preconditions**	
None

### **Instructions** - Add a Worklist
  1.	Document Management > Worklists - click + Add
  1.	If required select an available Worklist ID (selection to be deprecated)
  1.	Enter a description
  1.	Date Options  
a. Turn on ""Use the Run Date as the Ending Date""
        the ""Ending Date"" will Grey out-Unavailable  
b. Turn off ""Use the Run Date as the Ending Date""
       the ""Ending Date"" will be available for selections  
c. Beginning Date defaults to the current date and can be back-  
      dated  
d.  Ending Date can be future dated must be after the beginning 
      date  
  1. Workby and Client Options  
a.  If All Workbys? Is turned on, then you have the option to
      exclude up to 3 workbys (dropdown lists are populated from 
      Maintenance> Workby  
b. If all Workbys? Is turned off, then you must select a workby  
c.  You have the option to select a range of clients
      Beginning and Ending Client dropdowns are populated from
      Maintenance > Client. The Beginning Client number must 
      be less than the Ending Client number.  
d.  You can optionaly select a single Responsible Attorney 
      the dropdown list is populated with Maintenance > 
      Workby where the Bar Number is not empty/null  
  1. Settings  
a. Create a Complete Worklist ""ON"" will result in th WP worklist 
     (W), Review (R) and Credit Bureau (C) worklist being created  
b. Create a Complete Worklist ""OFF"" will require you to select
     one of the 3 worklists W, R or C  
c.  If the Use Only Lead Files for Linked Sets ""ON"" will result in the
     worklist only listed the Lead case ID where there is linked set  
d. Recreate Unconfirmed Documents ""ON"" will cause document
     actions that are in the ""Confirmation Needed"" status to be
     included in the merge records again.  
e. Use Return Date Processing ""ON"" will cause the return date
     settings to be applied to cases with suit  
f. Print Detail Worklist dropdown provides 3 options: Print
    Word Processing Only, Print Both Word Processing and Review
    and Do Not Create Detail Worklist  
g. Print Summary Worklist ""ON"" will include the Summary level
     report of the worklist.  
h. Print Court Worklist ""ON"" will include the Court actions list  
i. Print Docket Worklist ""ON"" will include the Docket actions
    list.  
j. Court Dropdown will allow you to filter the lists for only the 
    selected Court  
k. County Dropdown will allow you to filter for a County  
l. Garnishment Date will allow you to create a list for only
   cases with the selected date as the Garnishment date.  
1.	Submit to retain the configured worklist
1.	Observe the newly added Worklist under the Worklist menu option.

## 	Review Lists
### **Preconditions**
Schedule Review Actions on Selected Cases

### **Instructions**	
1.	Run the Review Worklist
    1.	Select the play button for the correct worklist configuration
    1.	Click the Show Me the Worklist
2.	Summary Worklist
    1.	By Workby Files to Be Reviewed  
a. A grid lists the Workby, Name, Total actions assigned, Average 
     Age, Average Priority    
b. Click on a workby to see an Aging (of scheduled actions) pie 
     chart    
    2.	By Workby Files Sent to the Dialer  
a. A grid lists the Workby, Name, Total actions assigned, Average 
     Age, Average Priority  
b. Click on a workby to see an Aging (of scheduled actions) pie 
     chart  
    2.	By Workby Outstanding Word Processing Files, Summary  
a. A grid lists the Workby, Name, Total actions assigned, Average 
     Age, Average Priority  
b. Click on a workby to see an Aging (of scheduled actions) pie 
     chart  


## WP List - Empty
## Call Queue - Empty