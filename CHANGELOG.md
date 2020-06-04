<a name="1.0.141"></a>
# [1.0.141](https://demo.interval-soft.com/) (2020-06-04)

### Features

* **GENERAL:** 
  * deleted by user_id integration added on all linked tables back-end (Otgoo)
   
* **LT:** 
  * all linked tables user trash/admin trash checked and added it was incomplete mostly (Otgoo)
  * LT forms title tooltip splitted by NEW/EDIT (Otgoo)
### Bug  
  * (66, 67) changed modal - map view (modal) - Aparment and Office(Daima)
  * (76) fixed - "ID" should be static and not clickable (Daima)  
  * (91) removed - "alert" on notification (Daima)  

<a name="1.0.140"></a>
# [1.0.140](https://demo.interval-soft.com/) (2020-05-28)

### Features
   * implemented tooltips on Conflict of Interest tab [finished all tooltip tasks] (Daima)  
   * ignore article of Name when sorting by name column on the Landmark list  (Daima)  
   * (74) XML file - field tooltips	Is it possible to show/hide titles/headings easily? - yes if title is no lenght on the xml, Title is not showing on tooltip
   
* **LT:** 
  * trash/admin trash added with deleted by  (Otgoo)  
  * LT forms title tooltip added (Otgoo)
  
### Bug  
  * added text "You have no notifications yet." on Notification list (Daima)
  * (68) added user name on Audit trash row (Daima)
  * (69) Apartment - map view (focus on/off error)	When you zoom in on the map, click on one apartment and then another, the pop-up 
for the first apartment doesn't close and then "focus off" doesn't work

<a name="1.0.139"></a>
# [1.0.139](https://demo.interval-soft.com/) (2020-05-27)

### Features

* **Notification:** 
  * developed all notification of Initial tab[Assignment, ToE] (Daima)  
  * developed to show a notification on the snackbar when receiving a new one (Daima)
 
  
### Bug  
  * (66) added date on Apartment - map view (modal) (Daima)
  * (68) changed date format of Audit trash row (Daima)
* **Sort issue:** 
  * Assignment list	[Assignment ID]	- Not sorting alphabetically
  * Appendix list	[#]	- Not sorting at all
  * Buildings list	[State of repair]	- This should not order alphabetically
  * Apartments list	[Building ID]	- Not sorting alphabetically
* **Tooltip:** 
  * Add/edit office - map locate tooltip change "apartment" to "office"
  * (73) Add/edit assignment - Can you remove the tooltips which are not on the sheet

<a name="1.0.138"></a>
# [1.0.138](https://demo.interval-soft.com/) (2020-05-26)

### Features

* **Assignment:** 
  * showed username who deleted the row on the trash system (Daima)

* **Notification:** 
  * developed all notification of Assignment (Daima)  
   
* **General:** 
  * add middleware for checking authenticated user request (now we can know the user of any request. if the request has no user, server deny the response)  (Daima)
  

### Bug Fixes

* **Tooltip:** 
  * Tooltip bug (2.40, 7.1, 6.1, 2.13-2.16 ) (Daima)

<a name="1.0.137"></a>
# [1.0.137](https://demo.interval-soft.com/) (2020-05-25)

### Features

* **General:** 
  * ToE conflict q24 mitigation strategy text changed (Otgoo)
  * ToE disclosure description changed (Otgoo)
  
* **Valuation:** 
  * valuations 1st tab keyplaces added (Otgoo)


<a name="1.0.136"></a>
# [1.0.136](https://demo.interval-soft.com/) (2020-05-22)

### Features

* **General:** 
  * Label Retails changed into Retail (Otgoo)
  
### Bug Fixes

  * ToE/Asset-Class dropdown standard measurements filter by asset-class-type not working fixed   (Otgoo)
  * ToE/Dashboard/Inspection map marker not showing fixed   (Otgoo)


<a name="1.0.135"></a>
# [1.0.135](https://demo.interval-soft.com/) (2020-05-21)

### Features

* **General:** 
  * Office inspection added (Otgoo)
  * ToE/Asset-Class office related changes implemented (Otgoo)

* **LT:** 
  * Measurement Standard categorized by asset_class (Otgoo)

<a name="1.0.134"></a>
# [1.0.134](https://demo.interval-soft.com/) (2020-05-20)

### Features

* **General:** 
  * added the Page tooltip on the forms (except: LTs form)
  
### Bug Fixes
  * (61, 60) fixed Inspection form - show required message on Drop down selection when focus out   (Daima)
  * (63) checked and fixed date format error   (Daima)
  * (17) checked and fixed all sort issue   (Daima)
  
<a name="1.0.133"></a>
# [1.0.133](https://demo.interval-soft.com/) (2020-05-18)

### Features

* **General:** 
  * comparable retail early verison added (Otgoo)
  * close info window when clicking on map [Building, Apartment, Landmark] (Daima)
  
  
* **Add TP dialog:** 
  * tooltips added (Daima)
  
* **Toe delivery tab:** 
  * tooltips added (Daima)  

### Bug Fixes
  * comparable office map view fixed (Otgoo)
  * (45)fixed Inspection form - copy existing building data (Daima)
  
<a name="1.0.132"></a>
# [1.0.132](https://demo.interval-soft.com/) (2020-05-17)

### Features

* **General:** 
  * type changes added (Otgoo)


 * **Comparable office:** 
  * list/map/form added (Otgoo)
  * linked tables added (Otgoo)
  
### Bug Fixes

  * datetime format chagnes leading into error fixed on comparable form  (Otgoo)

<a name="1.0.131"></a>
# [1.0.131](https://demo.interval-soft.com/) (2020-05-15)

### Features

* **Tooltip:** 
  * 
  * change page Tooltip UI (Daima)
  * added tooltip on Forms (Toe, Audit Trails, Inspection, Apartment, Building, User, Source component, Agency, Country, Landmark, Market research, Appendix)[except TP dialog] (Daima)
  
### Bug Fixes

  * add button to show Description of interaction on AUDIT Trash  (Daima)

<a name="1.0.130"></a>
# [1.0.130](https://demo.interval-soft.com/) (2020-05-14)

### Features

* **User compoent:** 
  * removed messages and activity
  * User profile button linked the User Edit Form
  
### Bug Fixes

* **General:** 
  * (47, 52) Switch support and help text around [Help -> Support, researches - research] (Daima)

* **Building:** 
  * (54) Form - fixed the updating bug (Daima)
  * Copy building Dialog - fixed the disappearing bug when the second click (Daima)
  
* **Audit Trail:** 
  * Trash- show Description (Daima)
* **Inspection:** 
  * Form- required alert of flooring and window types (Daima)  

<a name="1.0.129"></a>
# [1.0.129](https://demo.interval-soft.com/) (2020-05-11)

### Features

* **Assignment:** 
  * add a Tooltip button next to header of Form with new UI (Daima)
* **General:** 
  * (47,48,49,50,51,52) "Wrong heading" fixed too (Daima)
   

### Bug Fixes

* **Apartment:** 
  * List- fixed sort bug (Daima)
* **Building:** 
  * List- fixed sort bug (Daima)
* **Landmark:** 
  * List- fixed sort bug (Daima)
* **Currency:** 
  * List- made "symbol" heading unsortable (Daima)  
* **Contact list for company client:** 
  * List- made "phone" heading unsortable (Daima)    

<a name="1.0.128"></a>
# [1.0.128](https://demo.interval-soft.com/) (2020-05-08)

### Features

* **General:** 
  * "Please enter City Name" text removed, application wide "Please enter *" removed too (Otgoo)
  * changed some tooltip to Uppercase (Daima)
  * q1 of add target property should be "Please specify exclusions" changed (Otgoo)
  * popup text changed into Are you sure? (Otgoo)
  
### Bug Fixes

* **Toe:** 
  * discard changes? will ask on tps, payment, delivery_detail changes too (conflict, disclosure not included) (Otgoo)
  * got rid of the “Draft/Validated/Signed” droplist on ToE dashboard  (Otgoo)
  
* **landmark:** 
  * mandatory fields error message fixed (Otgoo)

* **Appendix:** 
  * List- fixed sort bug (Daima)
* **Market research :** 
  * List- fixed sort bug (sortable with "General" if sort by City ) (Daima)

<a name="1.0.127"></a>
# [1.0.127](https://demo.interval-soft.com/) (2020-05-06)

* **Assignment:** 
  * Form - Fixed working 2 event when click the tooltip (Daima)
  * List - upgraded trash system (Daima)
* **Appartment:** 
  * Form - save with city of location (Daima)
  * List - added search by city (Daima)
* **Inspection:** 
  * Form - check to discard changes (Daima)   
* **Market research:** 
  * Form - added General on the city list (Daima)  
  
<a name="1.0.126"></a>
# [1.0.126](https://demo.interval-soft.com/) (2020-05-05)

### Features

* **General:** 
  * Changed tooltips to Uppercase (Daima)
  * Rechecked and change the word TOE to ToE (Daima)
  * Changed all "specify which one(s)" to "Please specify" (Otgoo)
  * "____ is required" changed to "____ required" (Otgoo)
  * ToE -> COI group tp's "," changed into ", " try #1 (Otgoo)

* **Assignment:** 
  * Form - Fixed working 2 event when click the tooltip (Daima)

### Bug Fixes
  
* **Toe:** 
  * asset class cannot draft, validate fixed             (Daimaa)

<a name="1.0.125"></a>
# [1.0.125](https://demo.interval-soft.com/) (2020-05-04)

### Features

* **Assignment:** 
  * added small icons with Tooltip        (Daima)
  
### Bug Fixes
  
* **Toe:** 
  * payment list sort headers removed      (Otgoo)

* **Audit list:** 
  * audit list filter fix attempt #1       (Otgoo)
  
* **Apartment list:** 
  * Date format changed                    (Daima)  
  
* **Inspection form:** 
  * limitation validated                   (Daima)  
  
* **General:** 
  * Changed "No City" to "Please add city to Cities List"  (Daima)


<a name="1.0.124"></a>
# [1.0.124](https://demo.interval-soft.com/) (2020-05-01)

### Features

* **General:** 
  * zipcode label changed into Zipcode/Postalcode       (Otgoo)
  * zipcode become a freetext                           (Otgoo)
* **Project management:** 
  *  Project management and TOE Dashboard merged         (Daima)

### Bug Fixes
  * toe -> unqualified team member becoming lead valuer fixed (Otgoo)
  * inspection form -> change tooltips  (Daima)
  
<a name="1.0.123"></a>
# [1.0.123](https://demo.interval-soft.com/) (2020-04-30)

### Features

* **date format uniformed:** 
  * (25)  audit list -> interations date column                (Daima)
  * (20)  general form -> all date fields                      (Daima)
* **Appendice category:** 
  * (25)  Appendice category list -> added a new column         (Daima)

### Bug Fixes
  * (9,10)  Audit trail trashed -> fixed action button         (Daima)
  * (15)  Audit trail -> fixed back button loop                (Daima)
  * (17) Assignments list -> fixed order function tables       (Daima)
  

<a name="1.0.121"></a>
# [1.0.121](https://demo.interval-soft.com/) (2020-04-28)
<a name="1.0.122"></a>
# [1.0.122](https://demo.interval-soft.com/) (2020-04-29)

### Features

* **Report changes:** 
  * toe -> report generation file renamed                         (Otgoo)
  
* **Label changes:** 
  * (25)  toe -> COI  q4 label changed                           (Otgoo)

### Bug Fixes

* **Toe Form:** 
  * (23)  toe -> lead valuer check duplication fixed             (Otgoo)

<a name="1.0.121"></a>
# [1.0.121](https://demo.interval-soft.com/) (2020-04-28)

### Features

* **UI changes:** 
  * (19) toe -> payment sections UI changed                                    (Otgoo)
  * (18) toe -> general radio button q3 label changed                          (Otgoo)
  * (4)  toe -> asset_class delete from list will be asking Are you sure?      (Otgoo)
  * (6)  toe -> COI question 4a & other will check Asset class empty when empty
              will show following text "Target properties list empty!"         (Otgoo)

### Bug Fixes

* **Toe Form:** 
  * (7)  toe    -> payment discount, vat calculation fixed                                  (Otgoo)
  * (14) toe    -> COI  all description fields become adjustable                            (Otgoo)
  * (11) client -> deleting contact removing all newly added contact at the same time fixed (Otgoo)
  * toe -> tab layouts stacked each other fixed (Otgoo)
 * **Audit trails:** 
  * (9, 10)  implemented Trash system (Daima)
* **Appendix:** 
  * (2)  implemented Trash system (Daima)
* **Appartment form:** 
  * (3)  fixed duplication of Currency (Daima)  

<a name="1.0.120"></a>
# [1.0.120](https://demo.interval-soft.com/) (2020-04-27)

### Bug Fixes

* **Toe Form:** 
  * (27) additional cost tooltip fixed (Otgoo)
  * toe -> team members delete refixed (Otgoo)
  

<a name="1.0.119"></a>
# [1.0.119](https://demo.interval-soft.com/) (2020-04-24)

### Bug Fixes

* **Toe Form:** 
  * (24) toe draft deleteing target property fixed (Otgoo)
  * (15) toe -> target property -> external references validation fixed (Otgoo)
  * (20) toe -> back button tooltip (Daima)
* **Toe Dashboard:** 
  * (28) fixed -> back button tooltip (Daima)

* **Company Client:** 
  * (28) removed trash from contact list (Daima)
  
* **Toe List:** 
  * (10) fixed - if restore a ToE from the trash after deleting it, you cannot conduct any action (Daima)
  


<a name="1.0.118"></a>
# [1.0.118](https://demo.interval-soft.com/) (2020-04-23)

### Features

* **UI changes:** 
  * (18) ToE 3rd tab's question 4th tp pop ups button label changed (Otgoo)
  * (14) Toe 2nd tab Asset classes 1st checkboxes free text label changed into "Specify which one(s) are excluded" (Otgoo)
  * (13) Toe 2nd tab Asset classes surface field label changed into Surface area (Otgoo)
  * (31) Toe 2nd tab Asset classes surface field datatype changed from integer into decimal (Otgoo)

### Bug Fixes

* **Toe Form:** 
  * (12) team member delete issue fixed (Otgoo)
  * (22) payment NaN issue fixed (Otgoo)
  * (23) discount, vat & other vat value set 0 - by default (Otgoo)
  * (31) 2nd tab Asset classes surface field mask prefix has buggy feature inherited from 3rd party component workaround added (Otgoo)


<a name="1.0.117"></a>
# [1.0.117](https://demo.interval-soft.com/) (2020-04-22)

### Features

* **App:** 
  * implemented notification system (Daima)
  * when creating a new Assignment, the Project manager of the Assignment will receive a notification about it
  * when clicking on the notification, enter to Edit Assignment form  and the notification status will be changed 



<a name="1.0.116"></a>
# [1.0.116](https://demo.interval-soft.com/) (2020-04-20)

### Features

* **App:** 
  * implemented trash system on Market research list , Appendix category list and Training Documents list (Daima)
  * added search by city field on New Landmark form (Daima)

### Bug Fixes

* **App:** 
  * fixed Apartment form order bug of tables (Daima)



<a name="1.0.115"></a>
# [1.0.115](https://demo.interval-soft.com/) (2020-04-16)

### Release Highlights

* Report changes

### Features

* **Toe Report:** 
  * informed consent condition changed (Otgoo)
  * informed consent tp label changed situationally (Otgoo)

### Bug Fixes

* **Toe Form:** 
  * on validate checking lead valuer exists (Otgoo)
  * fixed all city dropdown bug (Daima)
  * tooltip changed on Apartments and Building List (Daima)
  * Apartment Type position changed ont Apartment form (Daima)
  * Landmark form bug fixed (Daima)
  * removed Title bar of picture table in Landmark form (Daima)



<a name="1.0.114"></a>
# [1.0.114](https://demo.interval-soft.com/) (2020-04-14)

### Release Highlights

* UI improvement
* bug fix

### Features

* **Report:** 
  * group of properties(xxx) added on tp's name (Otgoo)
  * conflict tp's name become red (Otgoo)
  * target property's inspection date will be become 'N/A' if its desktop valuation (Otgoo)
  * disclosure question 6th uploaded files description added on top of attachment (Otgoo)
  * disclosure question 6th if has uploaded file show '(Please check the attached file(s) in the Appendices section of this document)' on report (Otgoo)

* **UI:** 
  * audit report history's choosing option cleared (Otgoo)
 
### Bug Fixes
* **Toe:** 
  * cannot validate fixed (Otgoo)
  * fixed disclosure file bug (Daima)



<a name="1.0.113"></a>
# [1.0.113](https://demo.interval-soft.com/) (2020-04-12)

### Release Highlights

* UI improvement
* bug fix

### Features

* **UI:** 
  * audit reports history section added (Otgoo)
 
### Bug Fixes
* **App:** 
  * countries dropdown appears empty fixed (Otgoo)

<a name="1.0.112"></a>
# [1.0.112](https://demo.interval-soft.com/) (2020-04-10)

### Release Highlights

* Report improvement
* UI improvement

### Features

* **Report:** 
  * TOC update on word document open "downside might ask save on file close" (Otgoo)

* **UI:** 
  * generate new toe button enable delay addressed (Otgoo)
  * implemented discard function on TOE form (Daima)
 
### Bug Fixes
* **App:** 
  * fixed CSS Bug Comparable form / Considerations / Leasehold  (Daima)
  * fixed sort bug of tables  (Daima)

<a name="1.0.111"></a>
# [1.0.111](https://demo.interval-soft.com/) (2020-04-09)

### Release Highlights

* linked table features
* Report bug fixes
* UI improvement

### Features

* **discard function:** 
  * implemented to all forms of Linked table (Daima)

* **Report:** 
  * on the section VGPA 10 Local when no data showing "The valuer did not identify any local or market specific matters that may give rise to material valuation uncertainties" text (Otgoo)

* **toe-report progress:** 
  * close button delay will become smaller (Otgoo)

### Bug Fixes

* **Report:** 
  * Dev Test removed from all sections(Otgoo)
* **App:** 
  * fixed Admin trash of City bug  (Daima)


<a name="1.0.110"></a>
# [1.0.110](https://demo.interval-soft.com/) (2020-04-08)

### Release Highlights

* report progress features
* performance optimizations


### Features

* **toe-report progress:** 
  * close button added (Otgoo)
  * 5 min max tmeout added (Otgoo)
  * disable generate button during progress (Otgoo)

### Performance Improvements

* **core:** initial load time decreased (Otgoo)


### Bug Fixes

