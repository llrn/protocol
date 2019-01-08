# LLRN Recruitment
## Operating Procedure

### To-Add:
1. **Exact procedure for logging and updating contact history**
2. Short script for emails and calls (need to develop this for general use)

### Rules for Using the Database
1. You must following frequency and method of contact preference
2. Pay attention to subjects' research location preference
3. Respect participants' privacy
  - Do not keep paper or electronic copies of the database or participants' identifiable information in the lab. Delete old copies of the database after you have created and expended a contact list. Re-export and create a new contact list each time you contact participants.

### Recruitment Criteria & Accessing the Dashboard
1. Decide on your recruitment criteria: Age, sex, race, locations, etc.
2. Log in to the WordPress admin dashboard.
  1. Navigate to https://sciences.ucf.edu/psychology/llrn/wp-admin/
  2. Sign in with NID & NID password

### Export Registration Data
1. On the left sidebar, navigate to:
  - `Forms` -> `Import/Export`
2. Select Form: "Subject Registration"
3. Export as CSV file:
  1. Select Fields: "Select All"
    - You will most likely not use all these fields, but it is easier to just export them all and filter them out later.
  2. You can apply conditional logic to filter for your recruitment criteria if you wish. It is generally easier to do so in Excel (see below)
  3. The "Date Range" filter only serves to filter out subject entries based on the date they were created. It is suggested to leave it blank.
  4. Click: `Download Export File`
4. Open CSV export file in Excel and save it as an Excel Workbook.
  - Filters and sorting will not save with your export if you keep it as a CSV file.
  - `File` -> `Save As` -> `location` -> `Save as type: Excel Workbook`
  
  ![Save As Example](graphics/save-as-example.png "Save As Example")

### Create Contact List
1. Create a new worksheet in the Excel workbook, and call it "Contact List"

  ![New Worksheet Example](graphics/new-worksheet-example.png "New Worksheet Example")
  
2. Go back to the original worksheet and apply your filters:
  1. Highlight entire worksheet with Ctrl+A
  2. `Data` -> `Filter`
  3. Select your criteria, filter and sort columns to determine who you will contact
  4. **Be sure** to check when each subject was last contacted, by filtering the first several columns, against their preference for contact frequency ("*How often would you like to be contacted by us?*")
    - i.e., if their preference isto be contacted no more often than once a month, do not contact them if they have been contacted within the month.
9. Once filters and sorts are applied, copy and paste the remaining subjects’ information into your “Contact list” worksheet.
  1. If you have a lot to deal with, it can be useful to add these in batches, based on separate filters.

### Contact subjects from your contact list
1. When the list is complete, Sort the contact list by preferred contact window and contact subjects within their preferred contact window.
  1. Morning (6 AM – 10 AM), Mid-day (10 AM – 2 PM),					 Afternoon (2 PM – 6 PM), Evening (6 PM – 10 PM)
1. As you move down the contact list, log the result of each contact and any notes for yourself or the database.
1. Contact subjects in batches, based on the time you have available or based on the contact windows.
2. When a batch of subjects has been contacted and the result of each contact logged in your worksheet, return to the Wordpress admin dashboard and update each contact’s entry in the Subject Registration form.
  1. On the left sidebar: “Forms” -> “Entries”. Make sure Subject Registration is the active form in the top left.
  2. Search for each contact by last name and select “View” to open their entry in a new tab.
  
  ![entry search example](graphics/entry-search-example.png)
  
  3. On each entry page, select the “Edit” button on the right sidebar. 

  ![entry edit example](graphics/entry-edit-example.png)
  
  1. Add a new line to the contact log for each subject with the date, your name, the project title, and the result of your contact. Also add any notes to the “Relevant notes” field, with the date and your name.
  
  ![contact record example](graphics/contact-record-example.png)
  
  2. When finished updating a subject entry, select “Update” button on the right sidebar. 
  
  ![entry-update-example](graphics/entry-update-example.png)
