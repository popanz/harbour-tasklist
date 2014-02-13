harbour-tasklist
================

A small but mighty program to manage your daily tasks.

Contact
================
Email: tasklist [at] penguinfriends [dot] org

Features
================
- multiple task lists
    - set default list which is displayed on application start
    - set the list which is displayed in the cover
    - move tasks between lists (user requested feature)
    - lock/unlock orientation on demand (user requested feature)
- cover shows current, it's own or the default task list
    - cover action to add task to list shown in cover
    - cover action to switch between lists (user requested feature)
- task can be marked as done
    - function to delete all done tasks
    - marking of done/open tasks can be inverted (user requested feature)
- orientation can be temporary locked (user requested feature)
- remorse items for all necessary actions (e.x. delete tasks/lists)
    - configurable remorse item times
- multiple languages supported (depending on system language), for more information see below

Internationalization
================
- current languages: English (default), German, Spanish
- new languages tutorial:
    - download the plain language file: https://github.com/Armadill0/harbour-tasklist/raw/master/harbour-tasklist_plain.ts
    - copy the harbour-tasklist_plain.ts to harbour-tasklist_[your_country_code].ts (e.x. harbour-tasklist_fr_FR.ts)
    - using text editor:
        - translate everything in the <source></source> Tag into the <translation type="unfinished"></translation> Tag one line below
        - send me the file via mail
    - using QT Linguist:
        - start QT Linguist (part of the Qt SDK)
        - import the harbour-tasklist_[your_country_code].ts file
        - translate all entries and save your changes
        - send me the file via mail
    - every contributor will be mentioned in the About page :-)

Known Bugs
================

Roadmap for Version 1.0
================
- jump back to task input field after adding one by default (currently the keyboard doesn't slide out)
- add multiple tasks from the clipboard, devided by new lines
- settings
    - ability to disable jump back to task in put field after adding one
    - time and date display options (there are problems to read the correct local time strings)
- duedate (no API available atm)
    - task alarms
    - dispatch calendar item

Roadmap for Version 2.0
================
- online accounting
- share lists
- csv import/export
