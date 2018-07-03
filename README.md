# GigTab
Program that allows user to keep track of freelance work or gigs.

GigTab - Gig tracking database app

Intro Pane 1:
  -Welcome
  -Enter username
  -Enter password
// Use username and password to log into database. Notify and loop prompt if 
  incorrect entry

Intro Pane 2:
  -Button 1: Punch In
  -Button 2: Punch out
  -Button 3: Add Service
  -Button 4: New Gig
  -Button 5: Edit Gig
  -Button 6: View Gig / Generate Invoice

Punch In Pane:
  - Select Gig Name (show only gigs within timeframe)
  - Pull down menu for date (default sysdate)
  - Pull down menu for time (default sysdate)


Punch In Pane:
  - Select Gig Name (show only gigs within timeframe)
  - Pull down menu for date (default sysdate)
  - Pull down menu for time (default sysdate)

New Gig Pane:
  Enter Following:
    - Gig Name 
    - Contractor name
    - Client name (can be null)
    - Venue
    - Position (default- general tech)
    - Enter pay rate
    - Show Lead (can be null)
    - Show Run (pull down menu for start date and end date)
    - Notes (large format text box. Limit 500 Chars
// Program searches for: 
    *contractor name
    *client name
    *venue
  If any fields are not in database user will be prompted to enter info 
    in the following order
    *contractor
    *client
    *venue

New Contractor Pane
  Enter Following:
    -Contractor Name (completed with the name held over from new gig pane.)
    -address
    -city
    -State
    -zip
    -phone
    -contact first
    -contact last

New Client Pane
  Enter Following:
    -Client Name (completed with the name held over from new gig pane.)
    -address
    -city
    -State
    -zip
    -phone
    -contact first
    -contact last

New Venue Pane
  Enter Following:
    -Venue Name (completed with the name held over from new gig pane.)
    -address
    -city
    -State
    -zip
    -phone
    -contact first
    -contact last

Edit Gig Pane:
  Show Following (fields can be modified):
    - Gig Name 
    - Contractor name
    - Client name (can be null)
    - Venue
    - Position (default- general tech)
    - Enter pay rate
    - Show Lead (can be null)
    - Show Run (pull down menu for start date and end date)
    - Notes (large format text box. Limit 500 Chars
// Program updates new info and searches database for updated info for: 
    *contractor name
    *client name
    *venue
  If any fields are not in database user will be prompted to enter info 
    in the following order
    *contractor
    *client
    *venue

Search Gig Pane:
    -Search field: enter Gig name
    -Or Search by date range that generates a list of gigs that can be entered 
      into search field
    -Button 1: View Gig Pane
    -Button 2: Generate Invoice

View Gig Pane:
  -Dispaly:
    -Gig name
    -Position
    -Show_run
    -Venue
    -Contractor name
    -Contractor Contact name
    -Contractor Contact email
    -Contractor Contact Phone
    -Client name
    -Client Contact name
    -Client Contact email
    -Client Contact Phone
    -Invoice number
    -Invoice total
    -Invoice Date
    -Invoice status

Generate Invoice Pane:
-Dispaly:
    -Gig name
    -Position
    -Show_run
    -Venue
    -Contractor name
    -Contractor Contact name
    -Contractor Contact email
    -Contractor Contact Phone
    -Invoice number
    -Invoice Line Items
      *
      *
      *
    -Invoice total
    -Invoice Date
    -Invoice status (default unpaid)
    -Button 1: Change invoice status
    -Button 2: Save Invoice to file 







