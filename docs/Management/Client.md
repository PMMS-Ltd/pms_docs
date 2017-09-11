# Clients
___
Clients (or Sites) are the entities to which PMMS are responsible for providing property management services. Clients usually consist of a number of Properties (or Units) which each contribute towards the cost of the upkeep of any common parts which the Client is responsible for (e.g. interior hallways, stairwells, or exterior grounds).

## Fields
  Clients consist of the following fields:

Field  | Required  | Description
--|---|--
Name | &fa-check; | This is the legal registered name of the Client
ClientID  | &fa-check;  |  This is the 3-4 character shorthand designation for each client
Managed Properties  | &fa-check;  | This is the list of Properties which this client is responsible for, which may span multiple blocks, roads, or postcodes.
Registration No.  | &fa-times;  |  The registration number of the company, if it is registered with Companies House.
Registration Date  |  &fa-times; |  The date of the registration of the company with Companies House
Year Start  | &fa-check;  |  This the start of the current financial year for the Client
Year End  | &fa-check;  |  This is the end of the current financial year for the Client
Property Manager  | &fa-check;  | This is the Property Manager responsible for this Client
Account Name | &fa-check; | This is the Client bank account name
Account Number | &fa-check; | This is the Client bank account number
Sort Code | &fa-check; | This is the Client bank account sort code (typically 20-05-57)

---
## Client List
The Client List is a list of all the Clients currently being managed by PMMS. It can be accessed from the top menu bar under the "Management" drop-down category. The list can then be filtered and sorted to show only the required sub-set of Clients.  

![Jobs List Menu](../img/Client/management-menu-clients.png)  
----
### Client List Options
Once the Client List screen has been opened there are a number of additional options that can be accessed via the drop-down menu adjacent to <button class="btn btn-xs btn-primary"><i class="fa fa-fw fa-caret-down"></i> Filters</button>  
![Client Drop-Down Menu](../img/Client/client-dropdown-menu.png)
#### <i class="fa fa-fw fa-plus text-success"></i> Add New
Selecting this option opens the Create Client screen

#### <i class="fa fa-fw fa-file-excel-o text-success"></i> Download template
This option downloads the Excel template file necessary to import Client(s)

#### <i class="fa fa-fw fa-upload text-info"></i> Import Client(s)
This option opens an upload dialog for completed Client import spreadsheets

---
## Client Filters
The Client list can be filtered by using the collapsible filter panel, which can be opened by clicking <button class="btn btn-xs btn-primary"><i class="fa fa-fw fa-caret-down"></i> Filters</button>

Multiple filters can be applied simultaneously by entering values into the appropriate fields and clicking  <button class="btn btn-xs btn-info"><i class="fa fa-fw fa-filter"></i> Apply Filter</button>

All filter values can also be reset by clicking <button class="btn btn-xs btn-danger"><i class="fa fa-fw fa-times"></i> Clear Filter</button>

The Job filters panel contains the following filters:

Field  |  Description
--|--
Client ID  |  This allows the list to be filtered to a single Client reference code
Name  |  This is a free text search of the name field
Managed Properties  |  This is a free text search of the Managed Properties field
  Year Start|  This is a drop-down list of calendar months which allows all clients with a Year Start date within the selected month to be selected
Year End   |  This is a drop-down list of calendar months which allows all clients with a Year Start date within the selected month to be selected
PM  |  This is a drop-down list of maintenance department members which allows all clients managed by a particular Property Manager to be selected.

---
## Refresh List
The list of currently displayed clients can be refreshed by clicking on the <button class="btn btn-xs btn-success"><i class="fa fa-fw fa-refresh"></i>Refresh</button> button.

---
## Print Client List
Once a desired list of clients has been achieved by applying filters the list can be printed by clicking the <button class="btn btn-xs btn-info"><i class="fa fa-fw fa-print"></i>Print</button> button.

!!! info "NOTE:"
    This will only print what is currently displayed on the screen. If the list of Clients spans multiple pages, please make sure that "All" has been selected from the page-size drop-down.
---
## Client Details
Once a client has been chosen from the Client List, the Client Details can be shown be clicking <button class="btn btn-xs btn-primary"><i class="fa fa-fw fa-eye"></i> View</button>

The Client Details screen contains several panels (each with a title that describes its contents), a number of statistics boxes (similar to the User Dashboard), and a tab menu at the upper right.

### Client Statistics
![Client Stats](../img/Client/stats.png)  

This area shows the total number of Open Jobs, Open Issues, New Issues, and (optionally) any Calendar Events coming up.

### Client Details
![Client Details](../img/Client/client-details-panel.png)  

This panel shows information about the Client (such as Name, Managed Properties, Year Start, Year End, etc.) as well as a map showing the location of the first property associated with the Client.

### Files
![Client Files](../img/Client/files-panel.png)  

This panel shows any files or documents which have been attached to this client. This can include: Copies of Leases, Insurance Documents, Site Plans, or any other documents relevant to the Client.

### Properties
![Properties](../img/Client/properties-panel.png)  

This panel shows a list of the properties associated with the Client. The information displayed consists of Property ID, Address (Unit No, Address 1, and Post Code), Property Type, and the current Account No.

### Directors
![Directors](../img/Client/directors-panel.png)  

This panel shows a list of the current Client Directors who are responsible for making decisions and approving expenditure on behalf of the Client.

### Contracts
![Contracts](../img/Client/contracts_panel.png)  

This panel shows any current Contracts associated with the Client (i.e. Communal Cleaning, Grounds Maintenance, Lift Maintenance, Entry Phone Services, Fire Alarms, etc.) This panel is useful for determining not only which contractors supply regular services to the Client, but also how often and when is that service usually supplied.

---
## Add new Client
Clients can be added in two ways: either individually or in bulk via excel import.

### Add Client Individually
Clients can be added individually by following the below:

1. From the [Client List Options](#client-list-options) drop-down select <i class="fa fa-fw fa-plus text-success"></i> Add New

2. The "Create Client" form is now displayed. Complete the form (all fields marked with <i class="fa fa-fw fa-asterisk text-danger" style="font-size: 0.6em; vertical-align: super;"></i> are required) and click <button class="btn btn-sm btn-success"><i class="fa fa-fw fa-save "></i> Create</button>  
![Create Client Form](../img/Client/create-client-form.png)  


### Client Excel import
Multiple Clients (or a single Client) can also be imported via an Excel template:

1. From the Client Options drop-down menu select <span style="background: #efefef; padding: 4px;"><i class="fa fa-fw fa-file-excel-o text-success"></i> Download Template</span>
2. Open the Excel template file and complete the relevant fields (please refer to the [Client Fields](#fields) section to determine required/optional fields) for each Client to be imported
3. Save the file and from the Client Options drop-down menu select <span style="background: #efefef; padding: 4px;"><i class="fa fa-fw fa-upload text-info"></i> Import Client(s)</span>
4. Select the file saved previously and click <button class="btn btn-sm btn-info"><i class="fa fa-fw fa-upload"></i> Upload</button>
5. Assuming that no errors have occurred then you will be re-directed to the Client List screen once the import is complete.
