PowerAnnouncement Configuration
===============================

Overview: 
-------------
This solution helps Organization admins to configure/display announcements at the top of UCI app per specific set of users by UCI App / Business Unit / Security Role(s) / Team(s)


Pre-Requisites
--------------

-   Login to your PowerPlatform environment
-   https://web.powerapps.com/
-   Select your organization
-   Click Solutions -\> Import
-   Import solution PowerAnnouncement\_1\_0\_0\_2\_managed.zip
-   Provide Organization level Read permissions on Announcement
    Configuration entity to all security role(s) which needed this new
    feature

Instructions
------------

-   Open Power Announcement Model driven app
-   https://ReplaceOrgURL/apps/PowerAnnouncement (Ex: https://xxxxxx.crm.dynamics.com/apps/PowerAnnouncement)
-   Click Announcement Configurtions -> Click New
-   Enter the details as below and click Save
-   Ex: Field Data can be entered as: {"UCIApps":"Power
    Announcement","BusinessUnits":"BUName","SecurityRoles":"Role1,Role2","Teams":"Team1,Team2"}
-   Data field can be configured to support currrent logged in user
    properties such as the Current UCI App Name, User Business Unit
    Name, User Role(s), User Team(s)
-   Refresh the app. If required do Ctrl+F5

Announcement Configuration Grid
-------------------------------

![PowerAnnouncement
Grid](https://github.com/anilvem1/PowerAnnouncement/blob/main/PowerAnnouncement%20Grid.png?raw=true "PowerAnnouncement Grid")

Announcement Configuration Record
---------------------------------

![PowerAnnouncement
Sample](https://github.com/anilvem1/PowerAnnouncement/blob/main/PowerAnnouncement%20Sample.png?raw=true "PowerAnnouncement Sample")

Announcement Display
--------------------

![PowerAnnouncement
Demo](https://github.com/anilvem1/PowerAnnouncement/blob/main/PowerAnnouncement%20Demo.png?raw=true "PowerAnnouncement Demo")
