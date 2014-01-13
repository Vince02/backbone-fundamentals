## 2.1.2.rc1 [2014-01-13]

#### Bugfixes:

-  Filter in widgets show wrong values

#### Features:

-  Reset column search


## 2.1.1.rc1 [2014-01-11]

#### Bugfixes:

-  Change Label for Categorized view 
-  CRM Dashboard Fixes
-  Campaign Form 
-  Pagination footer fix
-  Integrity constraint error on widgets


#### Features:

- Version number should not uodate if commit failed
- Restriction on commit
- Yellow message boc on lead conversion should point to opportunity

## 0.0.8[2012-06-25]

- Graph views to be build on top of index view with group by cluase in reports
- Drill down graphs from categorized view -  drill down graphs from categorized view Graphs to be build from categorized view Every level of categorization along with summary data, can be rendered 
- Mobile look and feel -  use icons on menus for module/web time for 13/june
- font in mobile list views -  only display field should be bold , rest should be normal font
- listview enhancement for mobile devices -  user story: pagination bar looks ugly.
- mobile devices not capturing href all time on actual device -  In desktop browser it works , but on mobile browser href is not detected for 70% cases. use data-url instead
- mobile login page -  USER STORY: logo back gound need to merge with form background. 1. Either make everything while. 2. Use image gradient to merge while with form background.
- spacing between icons and label -  minimum 5 px spacing between. 1. 5 px menu icon and label. 2. 3 px filter icon and label. 3. vertical alignment in menus of label.
- align pagination bar in center. right now its falling towards left. -  USER STORY align pagination bar in center. right now its falling towards left. ACTION TAKEN -> DONE.
- below the drill down graph the "showing .... " not looking so good -  USER STORY #12, below the drill down graph the "showing .... " not looking so good ACTION TAKEN -> I HAVE DISABLED IT FOR MOBILE DEVI
- blank column at end -  USER STORY blank column at end after No. of Employees it's better for us to paint the empty blue on the other side it will make the whole thing look aligned
- [ ] brackets on drop down -  USER STORY now the [ ] brackets on drop down is it possible to configure it say one drop down has it and other does not. i can see them being needed in complex cases
- drill down should have headers -  USER STORY and this is last drill down should have headers which say something so I can clearly know which is what, you are doing it for the graph do it for the list view, you can e
- Grids line spacing -  USER STORY Grids given they are like list views the way I see, they are a special type of list view, i want to do something there cant figure out complet
- list views have unequal space on the top of a cell v/s bottom of a cell -  USER STORY list views have unequal space on the top of a cell v/s bottom of a cell. plus i see no reason to keep everything in its own line the 0.00
- The RED in menu is very ugly -  USER STORY #4 - very important, the RED in menu is very ugly just play with the 2 background and 2 foreground colors only dark on light and light on dark top bar you keep it
- The title bar of the graph on home screen and the pop-ups you open are different -  USER STORY #11, the title bar of the graph on home screen and the pop-ups you open are different ACTION TAKEN -> DONE / hom epage we show name of wid
- The whole date thing is too wide in mobile, i will be okay in keeping it to date only in both mobile and web -  USER STORY #9 the whole date thing is too wide in mobile, i will be okay in keeping it to date only in both mobile and web ACTION TAKEN -> better
- Country based drill down -  USER STORY: Drill down at country/state level. DEVELOPMENT STEP. implemented generic country drill down
- Horizontal view collapsing to vertical on simulator -  USER STORY: horizontal view collapsing to vertical in iphone simulator, when a text field is edited
- Jquery mobile overwriting href of list url -  provide an alternate url with attribute name "url"
- Login page collapsing for mobile
- Mobile drill down of gaphs
- Mobile menus back fix -  USER STORY: when click back on 2nd level menu, it shows hidden popup page
- All action menus in black bar on iphone should not have plus icon. Today I noticed all edit, delete and convert with + icons. -  USER STORY: All action menus in black bar on iphone should not have plus icon. Today I noticed all edit, delete and convert with + icons. DEVELOPMENT STEPS: modified j
- UI for field selection in list view/report view panel -  Implement following fetch level // 0: all columns except foreign_key + standard columns + private columns. // 1: all columns except private columns.
- Field to specify row_class formatting -  USER STORY: maax has a support for specifying either css class name for row or php call callback to compute row class name. Provide field in list view form for this.
- Campaign attachments -  USER STORY: campaign attachments block looks bad as a separate grid. DEVELOPMENT STEP. Implement simplified grid which can be embedded in mail information block. build
- Campaign subject -  USER STORY: right now we have 2 fields 1. subject 2. template selection popup. Most of time both will have same content and its confusing for end user. Comb
- Show graph header title as caption for mobile
- Spacing in graph header title -  spacing between comparator and value
- Bake Process Created Multiple Menu Items -  USER STORY: Bake Process Created Multiple Menu Items whenever changes are made. PROBLEM AREA. bake is creating single entry into menus, but duplicate values are being i
- Hide breadcrums and add title -  Ajay : Since breadcrum reflect internal information , we need to remove it Shyam : Adding list view or form name to the title , may be a good idea
- Hide document information block in add/create view
- Remove ff_ from flex flow module.
- Smaller grid buttons
- Change ui helpers into proper classification for auto detection -  USER STORY: Presently all helpers are static classes and place in common folder helpers. Split them into 1. data_view => all listviews helpers goes here. 2. form_vie

## 0.0.7[2012-06-01]

- Export module -
    - Select records / select all records (google style) in modules(eg. leads) list view and send for export.
	- Export module importable compatible export files .
- All core tables moved into design DB
- Move Help text into tool-tip in module bake
- Format tool-tip icons to look better.
- HTML error editor - The layout of the HTML editor not being seen properly in some cases
- Naming convention -  naming convention module__config_table_name for masters. module__configurations
- Read_count keep into report.
- Referrer in action history
- Remove tables classifies as red in app database;
- Translation layer build on top of php array -
	- In addition to .po files, generate php arrays for localization. Use soft configuration to specify which one to use.
- All info related to sessions goes into login history
- Maax ui slow in firefox
   upgrade jquery, replace live with on event, remove addresses plugin.
- Removed Model_extension
- Removed notifications+notified
- Removed tracker log
- Storing login session id into action history
- List view export to csv
- List view export to pdf
- Removed lookup model and split into multiple config table
- Create default list view when baking module.
- Upgrade calendar/events to related with multiple accounts/leads/contacts
- Upgrade calendar/task to related with multiple accounts/leads/contacts
- Google style action menu to fix overflow
- Panel on Left hand tree shows masters / configs

#### 0.0.5.1[20-02-01]
- bug fixed to recreate table indexes.
- maax now support xvars in find statement.
-
      MODEL
	  PRIMARY_KEY
      DISPLAY_FIELD
      CURRENT_USER
      XVAR_NULL
	  XVAR_TODAY
      XVAR_YESTERDAY
      XVAR_TOMORROW
      XVAR_DAY
      XVAR_WEEK
      XVAR_MONTH
      XVAR_QUARTER
      XVAR_YEAR
      XVAR_LAST_2_DAY
      XVAR_LAST_2_WEEK
      XVAR_LAST_2_MONTH
      XVAR_LAST_2_QUARTER
      XVAR_LAST_2_YEAR
      XVAR_NEXT_2_DAY
      XVAR_NEXT_2_WEEK
      XVAR_NEXT_2_MONTH
      XVAR_NEXT_2_QUARTER
      XVAR_NEXT_2_YEAR

## 0.0.5[2012-01-29]

#### Features added

- Added updated code of theme roller for generating web client themes.
. modified code for loading google chart libraries at run time. This will load libraries only where required.

## 0.0.4[2012-01-27]

#### Features added.
- Integration with google chart.
- Now maax mobile client also show graphs.
- Changes made to core/list views form.
- Maax find statement can auto detect 2nd level model(limited to only sub model)
- Dynamically binded model are flagged for runtime processing.
- Maax now allows to add resource files from anywhere when in scope of view.(elements/action views).
- change password now shows up in edit view.

## The big bang started somewhere at 2:30 AM on Feb 2011.
#### Tushar Takkar
