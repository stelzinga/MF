*********************************************
# INTRODUCTION
This note provides details for Management Tools or Tools in short, as discussed in [MGT: 99.Legend # PROFILE].  

This note has the following L1 sections: 

General 
- Introduction
- License
- Disclaimer
- Notes
- Information

Management Functions 
- Management
- Planning
- Organising
- Leading
- Controlling

Operations
- Operations
- Staff
- Assets
- Suppliers
- Liabilities
- Equity

Business Functions
- Finance
- Human Resources
- IT
- Risk
- Compliance
- CorpSec (Legal, Tax)
- Procurement 
- Other

Versioning Information
- Versions

Within each L1 section, a tool is defined on L2 and has the type in brackets (...). Types are not part of Note References i.e. [## Tool] and not [## Tool (Type)].  

References to [MGT: Planning], [MGT: Organising], [MGT: Leading], [MGT: Controlling] and [MGT: Tools] can be substituted with references to [MGT: 01.Planning], [MGT: 02.Organising], [MGT: 03.Leading],  [MGT: 04.Controlling] and [MGT: 80.Tools], i.e. pre-fixed with 01, 02, 03, 04, etc.   

The raw text of this note is available on GitHub in the following location:   https://github.com/stelzinga/MF


*********************************************
# LICENSE
The license applicable to this Note and any tools referenced in it is the one in [MGT: 99.Legend # LICENSE] a summary of which is copied below:

Copyright (c) 2022 Sander Elzinga, sander.elzinga@gmail.com

The text below is issued by Sander Elzinga as an Attribution Share-alike license, code CC-BY-SA 4.0. 

You are free to:
- Share: copy and redistribute the material in any medium or format
- Adapt: remix, transform, and build upon the material for any purpose, even commercially.

This license is acceptable for Free Cultural Works.

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:
- Attribution: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- ShareAlike: If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
- No additional restrictions: You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Notices:
- You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.
- No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.

License Deed: 
<https://creativecommons.org/licenses/by-sa/4.0>

Legal Code: 
<https://creativecommons.org/licenses/by-sa/4.0/legalcode>

The license is applicable to all sections in this note.


*********************************************
# NOTES
Notes are any form of document capturing data for any topic or series of topics. The Management Framework is maintained within notes, and the conventions used have been formalised in this section. Understanding this section helps to better understand all other parts of the Management Framework but it is not a prerequisite as ultimately the conventions used are intuitive.
________________________________________
## Note Name Format
Notes have names that they can be referred by. There are many manners to name name notes. The one used here in the Management Framework is the following:

CAT: Des

in which:  
CAT Note Category, all caps  
Des  Note Description  

Note that the colon is followed by a single space. Details of these items are found in the sections below.

Examples: MGT: 99.Legend, PRD: Workout

This format has the advantage that the note is more structured, which in turn helps with grouping notes together. If a note is stored as a file, then a colon.is not allowed, in which case it should be replaced with a '_'. 
________________________________________
## Note Category
In the Management Framework, Note Categories are based on *Goals* applicable to a Venture, see [## Profile Overview]. This means that Goals should be shortened to three character codes. 
The reason to use three characters is both practical (instead of making long note names , they remain short) and aesthetic (always three characters better shows the group categories and thus the entire note structure). Obviously, the reader can choose any length, but this MF uses three. 
________________________________________
## Note Description
The Note Description explains the *purpose* of the note. Ideally, it should be one word. If it is only possible to explain the purpose with several words then use '-' *hyphen* or '_' *underscore* to link them into one. In other words, there should not be any white space (space, tab).
________________________________________
## Note Content

### Sections
Notes are composed of sections (same as chapters). Sections can be numbered, but don't need to be. They do have a hierarchy: level 1, 2, 3, 4, 5 and 6 or short L1, L2, L3, etc. Section format and level is determined by *Markdown* header conventions, see below. Important: if a section level N exists then it is preferable to also have a section N-1, i.e., if there is an L3 in an L1 then there should be an L2.  

### Markdown
Text in the MF is written using *Markdown*.  Markdown is a protocol to write text in a manner that when displayed in a Markdown editor or viewer will yield an output that is user friendly to read (HTML-like), yet without a Markdown editor the raw text a.k.a. plain text still clearly shows sections, bulleted lists, etc. Many websites nowadays support Markdown pages. For example, this text is available in the public domain in Git and will display in Markdown when visiting the website.
   
Markdown has two forms:
- Standard Markdown
- Extended Markdown
  
Both forms use the *.md file extension and are discussed below, including conventions used within the MF.
  
### Standard Markdown
Standard Markdown is the most used form of Markdown and is sufficient for most purposes.
  
#### Escape Character
In below examples, the Markdown protocol is used. If that would be used in a Markdown editor it will show the Markdown output, instead of how that output is achieved by writing in 'plain text'. For those cases, the plain text version is shown in addition to the desired Markdown version, by using the escape character '\'. See examples under [#### Formatting] and the sections thereafter. 
  
#### New Line
To achieve a new line in Markdown, type two spaces and a carrier return. 
To achieve an empty line do a carrier return + 2x white space + carrier return.  
  
#### Horizontal Lines
To create horizontal lines use either 3x '*' or 3x '-' or 3x '_'. Use these to create H1, H2 level separators (see below) as follows: 
- H1 Separator = 45x '*' preceded by 2x newline
- H2 Separator = 40x '_'  preceded by 0x newline

The above yields in plain text clear separators whilst also following Markdown protocol.

For large blocks of text use 2x H1 separator above and below the block, and use capital letters for the block name. This is useful in very long notes.

#### Header Labels
Header labels are created with one or more '#'. Use these to create H1, H2 level captions:
- H1: # ALL CAPS 
- H2: ## First Letters Of Each Word Capitalised 
- H3: ### First Letters Of Each Word Capitalised
- H4: #### First Letters Of Each Word Capitalised
- H5: ##### First Letters Of Each Word Capitalised
- H6: ###### First Letters Of Each Word Capitalised

Headers L1 and L2 are preceded by header separators (see above). Header L3-6 are all preceded by one newline (2x space + carrier return). If the subject of a L2-L6 header is an acronym then all caps are permitted e.g., SWOT.
  
Once in a Markdown compatible viewer, the '#'s will not be visible, and it is the formatting (font size, bold) that determines the level of Header. This is also one of the reasons why L1 and L2 are preceded by '******' and '_____' respectively. 
Another consequence is that references to other sections (see below) are valid, but not always clear e.g., the reference [### Some Section] would show up in Markdown Editor like that, but the section it refers to would show up with the same name in the format of H3 mentioned above i.e., bolder format and larger font size but *without* the "###".

#### Formatting
Text formatting is as follows (note no spaces between the special character and the start and end of words between the special characters):
- *italic text* or  _italic text_  (plain: \*italic text\* OR \_italic text\_)
-  **bold text** or  __bold text__ (plain: \*\*bold text\*\* OR \_\_bold text\_
\_).
-  ***bold italic text***, (plain: \*\*\* bold italic text \*\*\*) 
 
#### Lists
For unordered lists use '-', '+' or '*' after a newline.
Below follow three times the same bulleted lists, using respectively the three list bullets mentioned above. In all three cases the plain text shows different list characters, but in Markdown, it shows three times the same bulleted list!

- bullet list item 1
- bullet list item 2   
    - Add 4x <space> to indent bullet item 2.1 
    - Add 4x <space> to indent bullet item 2.2
- bullet list item 3  

* bullet list item 1
* bullet list item 2   
    * Add 4x <space> to indent bullet item 2.1 
    * Add 4x <space> to indent bullet item 2.2
* bullet list item 3  

+ bullet list item 1   
+ bullet list item 2   
    + Add 4x <space> to indent bullet item 2.1 
    + Add 4x <space> to indent bullet item 2.2
+ bullet list item 3

For ordered lists use 1., 2. etc.
1. Numbered list item 1
2. Numbered list item 2
    - Add 4x <space> to indent bullet item 2.1
    - Add 4x <space> to indent bulleted item 2.2
3. Numbered list item 3  

NB : some Markdown converters support '1)' i/o '1.' but not all do, so stick to using the dot e.g., '1.' 
'A.' or 'i.' do not always work as numbered items. 

#### URLs
For Internet URL's use:  
- [A name](http://www.google.com)  (plain: \[A name\]\(http://www.google.com\)  
- <https://www.google.com>  (plain: \<https://www.google.com\>)  

The latter version uses the URL as the link name. The former shows the link name as 'Name'. Certain websites, like Github,  will detect that an URL is an URL and display it as such regardless of having used markdown protocol.

#### Images
Insert images: ![image name](/file/path/image.jpg)  (plain: \!\[image name\]\(/file/path/image.jpg\)

### Extended Markdown
Extended Markdown supports fenced code blocks.
This allows writing chunks of code without needing to use 4x space for each line. To create a fenced code block use 3x ` (back-tick) at start and end of the code block.

### Problems with Markdown
Markdown translates into HTML. However, in HTML there is one aspect of text rendering that is not very fluent: white space. HTML trims spaces if there are more than one including at the start of a sentence, so the following:

   Some    text.

Will appear in HTML as:

Some text.

Therefore aligning text across sentences using spaces may have unexpected and undesired results.
One way to circumvent this is to use the Unicode U+2003 "em space" character: " " . Alternatively, one can use the Unicode U+2002 "en space" character which is half the size of the "em space" and has the same size as an actual space character: " ". See also respectively:  
<https://unicode-table.com/en/2003/>  
<https://unicode-table.com/en/2002/>

These characters are also in [# SPECIAL SYMBOLS].

### Markdown Reserved Characters
In Markdown certain characters have special meaning, they should be escaped with the '\' character if the character is meant, not the Markdown version of it:
\-  : unordered list
\+ : unordered list
\* : unordered list
\** :  bold **bold** 
\*:   italic *italic*
\__:    __bold__
\_ :  _italic_
\# : start of header
\( ) : used for links, images requires [ ]
\{ } : 
\[ ] : used for links, images, requires ( )
\! : used for images (if before [...])

Characters that can be freely used at start of a line:
.
^
/
x
~ (but special in Excel, so substitute first in formulas)
%
$ 
&
^
?
= (but special in Excel so: avoid)
@ (but is used in certain websites like Github, so: avoid)

### Word Capitalisation
Words that start with a capital, like 'Planning' have been defined in this note or in [MGT: 80.Tools].

### Markdown in other Editors
Some editors, like OneNote, Outlook mail, use some of Markdown features albeit it different: *italic* in Markdown will show *italic* entirely  in bold (and it will keep  the two '*' .

### Triple @
A special convention in the MF is triple @ or '@@@'. This notation reflects that more information is still to be written but currently not available. The combo is easy to use in searches as no text uses a triple @.
________________________________________
## Note Reference
Within notes a Note Reference a.k.a. Reference Indicator or [...] is used to provide more details or to refer to a source of data that holds more details. That source can be anything as long as the type and location of the data are clear. 

A Note Reference starts with a '[' and ends with a ']'. The data in between determines the type referred to as one of the following:
1. Section or Note
2. File
3. URL
4. Mail
5. Database
6. Meeting
7. Free Text
8. Reference to academic research
8. Etc

### Section or Note
For a Section or Note there are three references:
[# SEC]                   -> refers to section L1 SEC in same note
[CAT: Des]             -> refers to a note CAT: Des
[CAT: Des # SEC] -> refers to a section L1 SEC in note CAT: Des

e.g., [MGT: 99.Legend ## Note Reference] which is this section you are reading.

In addition to the above it is possible to have references like [# SEC1 ## Sec 2] which explicitly refers to L2 Section 'Sec2' *in* L1 Section 'SEC1' 

In notes it is possible to use such references by explicitly using the words 'section(s)' or 'note(s)' in front of, or behind the item. e.g. "... section ## Routines in section # OBJECTIVES in note MGT: Planning ..."

### File
For a file the Note Reference is [File Path], [F: File Path] or [F: File Path] in which File Path is either a full path to a file or directory or a shorter version of such path. File Paths are operating system specific. 

Examples:  
    $HOME/data_private/mgt/51.finance/       (Linux)
    $HOME/utils/scripts/ubu2usb.command  (Linux)
    C:\Users\yourname\mgt\finance\              (Windows)
    C:\SomeDir\SomeDoc.docx                         (Windows)
  
The only requirement for a File Path is that it is clear it concerns a path to a file or directory. When a full path is used it will be obvious. Depending on Operating System there are various ways of managing File References. Details in [MGT: 80.Tools].
  
In certain cases it may be necessary to refer to a page or sheet or chapter within a file. This can be achieved using extra info within the reference relating to the type (page, sheet, chapter), an '=' sign and the value (page nr, sheet name, chapter name etc.)

Examples:  
    C:\SomeDir\SomeDoc.docx Page = 100  
    $HOME/data_private/mgt.xlsx Sheet = Planning

### URL
For a URL, the Note reference is [Weblink] or [URL: Weblink], in which Weblink refers to *anything* that can be accessed through a web browser: classic web pages, sharepoints, PowerBI pages, etc.] i.e., http://something.xyz and without < and > and where 'http' can be any supported service (http, https, ftp, ftps, ssh, ...).

### Mail
For Mail the Reference format is: [Mail: Subject] or [M: Subject] in which Subject is the Mail's Subject that was sent/received. Alternatively,  [Subject: Subject] can be used.

### Database
Databases come in many forms but all do the same: store data. Databases have their own manner of connecting and retrieving/entering data. Reference to a database depends on the type of database e.g., [Oracle: scheme/table_name], [Oracle: table_name], etc.

### Meeting
Sometimes it is relevant to refer to a meeting that was held in which specific information was shared. In this case the reference should show [Meet: Text] in which Text is the Subject of the Meeting's invite mail. Lo

### Free Text
The Reference Indicator can also contain free which acts as a clarification, a question one should ask oneself, e.g.,  [Purely some comment without any value].

### Research  
It is possible to refer to a domain of research specific research articles, etc using a reference as well. There are two ways of doing it. 

The formal academic referencing a.k.a. citation, which looks like this (author name, year) or similar. This is the often used citation in academic articles (journals, thesis etc). Such references follow standard academic protocol, which may slightly differ across discipines [1].

The second style is used above, where the [1] means there is further down in the section more information linked to [1].

[1] University of Pittsburgh, Citation Styles: APA, MLA, Chicago, Turabian, IEEE, https://pitt.libguides.com/citationhelp, viewed Jan 2025.
________________________________________
## URL

### POLC
<https://saylordotorg.github.io/text_international-business/s14-05-managing-the-international-bus.html> 


*********************************************
# MANAGEMENT
Management is the term reflecting the organisation of human capital (Staff, Groups) such as to yield the best Client Services as output of the Venture's Activities with available Assets and Suppliers such as to achieve and optimise the Venture's target of highest possible Revenue at lowest possible Cost and lowest possible Risk under the constraints of Environment and Financing (Equity, Liabilities) of all Resources. 
________________________________________
## Overview
This overview shows on the first level the key deliverables as per [MGT: 99.Legend ## Management]. On the second level are the Tools, each of which has a dedicated L2 section. The same tool can be used for different deliverables:

- Management Cycle
    - PDA
    - Eisenhower Matrix 
    - MSS
    - MTrack
    - MC
    - Governance Matrix 
- Management Improvement
    - Skill Inventory
    - Writing Style 
    - Style Inventory
    - Study
- Planning
    - Dedicated Planning note
- Organising
    - Dedicated Organising note
- Leading
    - Dedicated Leading note
- Controlling 
    - Dedicated Controlling note
________________________________________
## PDA (Software)
Throughout the Management Cycle, certain Tools are deemed 'standard' or 'baseline'. This standard is referred to as the *Personal Digital Assistant* or *PDA* and is composed of:

- Mail 
- Calendar
- Tasks
- Notes
- Contacts
- Chat
- Phone incl Video
- Browser
  
Depending on the apps used, and whether a Venture requires the use of specific apps, different implementations are possible. 

- Mail (Outlook, Gmail, Yahoo! Mail, Thunderbird Mail...)
- Calendar (MS Calendar, Google Calendar, ...)
- Tasks (MS Tasks, Google Tasks, ...)
- Notes (MS OneNote, Google Notes, Standard Notes, ...) 
- Contacts (MS Contacts, Google Contacts, ...)
- Chat (MS Teams Chat, Whatsapp, Signal, WeChat, ...) 
- Phone incl Video (MS Teams Phone, ...)
- Browser (MS Edge, Google Chrome, Firefox, ...)

Because they can be used in different manners by different people, this note will not prescribe particular uses.   
________________________________________
## Eisenhower Matrix (Framework)
The *Eisenhower Matrix* or *Eisenhower Decision Tree* or *Eisenhower Box* is a decision tool to plan work, named after Dwight D. Eisenhower, general during WWI and 34th President of the USA who used it to manage his time. The decision tree is based on *two dimensions* of Tasks. These dimensions are *urgency* and *importance* and are used by a Manager to decide what to do with each Tasks coming his way. Note that instead of Tasks one can read Objectives.
  
### Important
Something is important for different reasons, but the following criteria are deemed relevant:
-Task cannot be delegated (simply because the right skills are not there right now, training would take too much time given urgency, etc.) and/or
- Task relates to a topic that has a lot of attention from senior stakeholders (internal or external) and/or
- Task completion has a direct impact on Revenues, Cost or Risk.
  
### Not Important
This includes all tasks that are potentially important in the long run, but not important enough for the Manager to do himself. The following criteria are relevant:
- Task requires a skill set the Manager does not have (and would thus require delegation anyway)
- Task requires application of Skills the Manager has, but which are at a level the Manager does not Operate at (anymore). This typically involves Tasks related to Goal = prd i.e., Tasks related to Maintenance, Enabling and Support.
  
### Urgent
Something is urgent for different reasons. The following criteria are deemed relevant -there is sometimes a link with *Important*-:
- Not performing the Task soon has a knock on effect on several other Tasks and/or
- There is a deadline imposed by a senior stakeholder (internal or external)
- The completion of the task has a direct impact on Revenue, Cost or Risk
  
### Not Urgent
Something is not Urgent if the non-performance of the Task any time soon is not going to make a huge difference. 
  
### Decision Quadrants
The above two dimensions yield four combinations a.k.a. *Decision Quadrants*, which drive what to do with the Task:
1. Urgent + important -> Do Task Now
2. Important + not urgent -> Do Task Later
3. Urgent + not important -> Delegate Task to someone
4. Neither urgent + not important -> Delete Task altogether
  
The dimensions are applicable to the person needing to make the decision between 1,2,3 and 4 and can thus apply to Managers as well as Staff, provided the Staff has been given the right to delegate to someone, see [## Delegating Definition]. As can be clearly seen, according to the Eisenhower Matrix oneself should work only on Tasks that are Important.
  
### Decision Outcomes
The use of the Eisenhower Matrix helps scale works. It is important to note here that the decision of what constitutes Important and Urgent, requires rather black and white reasoning. If one is not strict enough, one ends up with many tasks under 1 and 2 and almost none under 3 and 4. If the decision was made correctly, and there are still many tasks under 1 and 2, then one should reflect upon the sheer amount of work and look more holistically into the origin of so many tasks.  
  
### Eisenhower Decisions
 Important and Urgent are criteria to make a decision. It assumes though, that the Tasks coming the way of the Manager *should be done at the level of* the Manager. By design of the Organisation within a Venture, certain Tasks are done by specific Groups responsible for specific Processes in Activities they are responsible for. In those cases the use of Eisenhower Decisions does not really apply: the tasks should have gone to the relevant Staff directly, and if somehow they did not, the decision is to simply delegate by default to the dedicated Group of Staff.  
________________________________________
## MSS (Software)
The Management Spreadsheet (MSS) is a GNU license file built in Calc, LibreOffice and saved as Excel file. 
  
### MSS Master
The master MSS file, mgt.xlxs,  is available in GitHub here:
https://github.com/stelzinga/MF

### MSS Slave
It is possible to add functionality to any instance of MSS Master and which is not available in MSS Master e.g. macros. Such instance is called MSS Slave. 

### MSS References
To refer to sheets in MSS use [MSS: xxx] with xxx is the name of the sheet in the MSS, i.e., equivalent to Note Naming conventions. Columns are referred to as [MSS: xxx ## yyy] with yyy the name of the Column. Rows can be referred to by number which really only applies to the first 5 rows i.e. [MSS: xxx ## 1] is first row in sheet xxx.

### MSS: Mxx Sheets 
See [## Mxx] in [# MANAGEMENT].

### MSS Note Management
A key feature is the ability to write *Notes* in Col = Notes, This column drives the content of Cols = *First Note*, *Last Note* and then *Creation Date* and *Update Date*. 

MSS Note Notation
MSS Note Management follows a specific form of Task Notation, namely the dated comment version.i.e. dd-mm-yy: xxx, see [## Task Notation]. Exemple:
23-02-21: ##1 First review of audit results show overall good insight in business. Next: complete review. {Joe} [~/file/path] ##2 Received purchase order for 20 new products from client ABC (20210731) [https:/internal/website/page]

### MSS Task Management
Another feature of MSS is the integration of Tasks using [## Task Notation] in the dedicated Column = Tasks.  

### MSS Hierarchy
Sheet = M5, dedicated to Projects has an *Integrated Hierarchy*. 

Venture 
    Project p
        Stream p,i
            Action p,i,j

The hierarchy is determined by Column = *Link*, the value of which is the value of the Column = *Key*. 

In addition to the Link, *manual indentation* makes the hierarchy visible:
- Run/Chg Goals, Routine, Project = 0x space
- Sub, Stream = 4x space
- Drill, Action = 8x space 

NB: as the spaces are in Col = Name it is important to make sure they are applied *before* creating the link! 

### MSS Dynamic Gantt Chart
Sheet = M5 has an *Integrated Dynamic Gantt Chart* based on the Integrated Hierarchy (see above) which helps in Project Management. The Chart runs for a *dynamic period* determined by the earliest occurrence in Column = Start Date and the latest one in Column = End Date. Each column in the Chart thus represents a number of days that depends on the Total Period divided by the nr of Columns in the Chart (52). Color codes in the Gantt Chart are as follows:
- Venture: shows today's date in red, rest white
- Project: shows bar from Start to End in dark blue
- Stream: shows bar from Start to End in light blue
- Action: shows bar from Start to End in soft grey
- Project/Stream/Action: Red (overdue) and Green (complete) in decreasing intensity based on Project, Stream (light red/green), Action (soft red/green).

### MSS Reporting
MSS has built-in capabilities for *Reporting* using Pivot Tables. There are many different options for reporting. The logic used in [MSS Note Management] is a key feature on MSS Reporting. 
________________________________________
## MTrack (Software, Framework)
MTrack refers to any implementation of the Managerial 7, see [MGT: 99.Legend ### Management Cycle] in MSS (see above). This is achieved through 7 dedicated sheets as follows: M0 = 0.Management, M1 = 1.Revenue (or  Income Statement), M2 = 2. Cost (or Balance Sheet if required), M3 = 3.Risk, M4 = 4.Run (Run Goals / Routines), M5 = 5.Change (Change Goals / Projects), and M6 = 6.Intel. 

All sheets except M0 and M6 have a bottom and top section, where the latter contains stats of the bottom. They all use Digital Bullet Journaling, see [## BuJo MSS]. 

### MTrack0
Sheet M0 a.k.a. MTrack0 contains several rows:
- Tracking Type = Management
    - Name = nn. Manage xxx, for each Profile Tree item xxx
        - Each has Tasks as per deliverables in [MGT: 99.Legend]
        - MSS Master has default entries for these Tasks 
        - Each has a dedicated Note with more details.
    - Name = Do MC - n.xxx for each Managerial 7 item n.xxx
    - Name = Check xxx - n, for a Check xxx for a period n
    - Name = Review xxx - n, for a Review xxx for a period n
    - Name = Attend xxx - n, similar to Review xxx - n
- Tracking Type = Incident
    - For any new Incident from Run
- Tracking Type = Audit
    - For any new Audit, from Controlling
- Tracking Type = ToDo
    - For each one-off Task that is not part of above
    NB: Hybrid Managers can use for non-roadmap Projects 

### MTrack1
Sheet M1 a.k.a. MTrack1 contains Revenue details or alternatively details of the Income Statement. It is possible this sheet refers to a central location, or that the maintenance of Revenue information is fully delegated to, for example, the Finance department.

### MTrack2
Sheet M2 a.k.a. MTrack2 contains Cost details or alternatively details of the Balance Sheet. It is possible this sheet refers to a central location, or that the maintenance of Cost information is fully delegated to the Finance department for example.

### MTrack3
Sheet M3 a.k.a. MTrack3 contains Risk details. It is possible this sheet refers to a central location, or that the maintenance of Risk information is fully delegated to, for example, the Risk and Compliance departments.

### MTrack4
Sheet M4 a.k.a. MTrack4 contains the Run Inventory i.e. all Routines across all Run Goals and Sub-Goals including Management Routines. This sheet is updated as a result of Change, see below. It contains:
- Routines for non-manager roles (Goal = prd, ovs, ovh)
- Routines for manager roles (Goal = mgt)
  
It is possible this sheet refers to a central location, or that the maintenance of Run information is fully delegated to for example a COO.

### MTrack5
Sheet M5 a.k.a. MTrack5 contains the Change Inventory i.e. all Projects across all Change Goals and Sub-Goals (Roadmap). This sheet is re-created at the start of each year and then maintained throughout the year. It contains:
- Projects for non-manager roles (Goal = gro, pro, sec, opt)

It is possible this sheet refers to a central location, or that the maintenance of Change information is fully delegated to for example a Project Management Office.

### MTrack6
Sheet M6 a.k.a. MTrack6 contains Intel or Intelligence both from within, as well as outside of the Venture. This sheet is updated continuously. 
________________________________________
## MC (Framework)
MC is the Framework to perform the Management Cycle (MC). It is composed of various Processes performed at different frequencies using relevant Tools. 

There are two main parts to the MC:
- Initiation
- Recurring 

### MC Initiate
This part of the MC initialises the minimum Management Structure. Set up:
1. a PDA structure  [## PDA] 
    - Mail 
    - Calendar
    - Tasks
    - Notes, see [## BuJo]
    - Contacts
    - Chat
    - Phone incl Video
    - Browser
3. as many meeting Notes as meetings [MGT: Attend-mmm], see [## Meetings]
4. as many OM Notes as Activities [MGT: OM-aaa], see [## Operating Model]
5. BuJo Notes and Mtrack Sheets, see [#### MC BuJo & MSS] below 
6. MTrack sheets, see [#### MC MTrack] below

#### MC BuJo & MTRack
The default notes, and the Managerial 7 sheets in [MSS: MTrack] a.k.a. MTRack need each to be intialised as follows: 

MTrack 0
For each Profile Tree Item xxx there should be:
- A dedicated row in MTrack0 with Name = nn. Manage xxx
- A dedicated note [MGT: nn.xxx]
- A dedicated folder ~\mgt\nn.xxx\

in which:
    nn = 00, 01, 02, 04, etc
    xxx = name of Profile Tree item

MTrack0 has, out-of-the-box these dedicated rows and for each exists one or more default Tasks as follows:

. Maintain yyy [MGT: xxx # YYY]

In which:
    yyy = name of each Profile Tree Item xxx's deliverables, see [MGT: 99.Legend]. 

In each [MGT: nn.xxx] note, a Level 1 section [# YYY] provides the details for the deliverable yyy. Those [# YYY] sections contain:
- Details of the deliverable yyy itself and/or 
- References to locations where those details are held e.g., MTrack

Similar as above, each folder nn.xxx has a sub-folder representing the key-deliverable as per the Profile Tree.

Example for Profile Tree Item: Planning.
- MTrack0 row: Name = 01.Planning
- Note: [MGT: 01.Planning]
- Several section level 1 in that note e.g.:
    - CONTEXT 
    - PURPOSE 
    - etc
- A Folder ~/mgt/01.planning/ with sub-folders:
    - 01.01.context
    - 01.02.purpose
    - etc

MTrack0 does not define the Venture, but drives the collection of all other details. Note that the note [MGT: 00.Management] has a special content, as per [## Bujo].

MTrack1, MTrack2,  MTrack3, contain Venture specific details of the Revenue, Cost and Risk respectively (or alternatively: Income Statement, Balance Sheet, Risk), see [## MTrack].

MTrack4
For tracking Routines create:
- An Entry rrr in MTrack4
- A Note PRD: rrr (Routines with many details)
- A Folder PRD: rrr (Routines with many details)
- A sub-folder in Mail Folder 2_DoLater (Routines with many details)

in which:
    rrr =  name of the Routine. 

The reason to set up all four (Row in MTrack4, a note, a folder, a sub-folder) is because:
1. MTrack4 helps in providing *statistics* on all Routines 
2. The note helps logging processes, context etc. and can thus act as a *manual*
3. The folder helps storing procedures, etc. 
4. There may be specific emails exchanged each time the Routine is performed

Instead of a note per Routine, it is also possible to use the [MGT: OM-aaa] i.e. the Operating Model note for each Activity aaa that embeds that Routine. 

MTrack5
For Projects create: 
- An Entry ppp in MTrack5
- A Note: [PRJ: ppp] or [GRO: ppp], [OPT: ppp] etc.
- A Folder ~\prj\ppp\ or ~\gro\ppp, ~\opt\ppp\ etc.
- A sub-folder in Mail Folder 2_DoLater (optional)

in which:
    ppp = name of Project. 

The reason to set up all four is because:
1. MTrack5 helps in Project Management 
2. The note helps notably at the start when the project management structure is not yet established
3. The folder is useful for storing project plans, process descriptions etc. 
4. There may be many emails for that particular Project.

Details on what qualifies as a Project vs a Routine are discussed in [## Objective Definition]. Both for Routines and Projects it is possible to create dedicated Teams in MS Teams, dedicated Chats etc.

MTrack6
Initialise MTrack6 so that Intel can be tracked. Intel involves a large variety of sources. The summary of, as well as the link to the source is provided in MTrack6. Details on intel entities are maintained in [# PLANNING]. 

### MC Recurring 
Once initiation is completed, the recurring Management Cycle begins.

#### MC Monday
- Review Calendar for the week and solve conflicts 
- Review MTrack0 ToDo/Tasks to do during the week.
- Review MTrack4 (optional)
- Review MTrack5
- Review and update [MGT: _Main] 

#### MC Daily
- Review Calendar for the day and for each Meeting check:
    - A note exist and has spare L2 sections ddmmyyyy 
    - Agenda is prepared 
    - ToDo reflects latest status
- Review Mail and update: MTRack as follows:
- MTrack0
    - Management entries 01-99 (rare to need any update)
    - Managerial 7 entries (Name = Review n xxx)
    - Incident details
    - Audit details
    - ToDo entries
- MTrack1-3: Revenue, Cost, Risk 
- MTrack4: Routines
- MTrack5: Projects
    - Projects not worked on get a Hold Date
    - Projects that have completed get a Complete Date
- Prepare, attend and minute Meetings, using notes.
- Work on Projects and Routines

#### MC Friday
- In _Main start writing a manual report for the week using input from _Main and Mtrack.
- Create any MSS Report based on MTrack.
- Migrate older Report entries from _Main to _Archive.
- Migrate closed Task entries from _Main to _Archive.

#### MC Yearly
@@@ Roadmap @@@

### MC Pitfalls
Some Tools have limitations that are overcome in other Tools. As such overlap between Tools is inevitable e.g., 
- Mail has folders for short and longer term tasks
- _Main has short term and long term sections
- MTrack has recurring items as well as projects (long term)

Both _Main and MTrack can be used for reporting, with the former very manual, the latter more automated and customisable. There is no simple way around such overlaps and it is left to the Manager to optimise the use of the Tools.

### MC _Main vs MTrack
One of the strengths of the Management Framework and it's implementation is also its weakness: the flexibility and versatility. As a result, in above sections one often has a choice between maintaining _Main and MTrack, but which one is best? The choice is left with the Manager, but there are some best practices. 

- MTrack is ultimately preferred, because the MSS Software has improved *reporting* capabilities.
- MTrack is preferred for Project updates.
- _Main is preferred for Routine updates. For reporting purpose, the details of these updates can be bundled in a single comment in MTrack0 under Name = Review 4. Run. 
________________________________________
## Governance Matrix
The Governance Matrix is a two-dimensional matrix that is used to establish what it is the Manager wants to put in place as Governance. Its core use is in Ventures where the focus is on Risk (often Ventures in heavily regulated sectors like Finance, Petrochemical, Automobile, Pharmaceutical, Flight ...). 

The matrix' purpose is to show which Risks exists, which Activity (or Business Function) is subject to the Risk, and then on the intersection, how the Risk can materialise and  what is put in place to mitigate or at least oversee the Risk.

The two dimensions of the matrix are thus: Risk (vertical) and Activity or Business Function (horizontal).

@@@ to be expanded
________________________________________
## Skill Inventory (Framework)
Skills required for Management are below. Details of skills can be found under [# HUMAN RESOURCES] the rest are mentioned behind each Skill.

### Hard Skills
- Accounting
- Analytics & Data
- Budgeting
- Economics
- Finance
- Marketing
- Mathematics
- Operations
- Information & Communication Technology 
- Project Management
- Statistics

### Soft Skills
- Coaching
- Communication 
- Curiosity (ask "Why?")
- Delegating
- Flexibility
- Mentoring
- Motivating
- Multitasking
- Pragmatism
- Presenting
- Problem solving
- Self-learning
- Teamwork
- Time Management
________________________________________
## Writing Style (Framework)
Written communication is key to the day to day of a Manager. The following guidelines aid in writing text that people will read, finish and follow through:
- Use few adjectives/adverbs: use strong verbs and nouns. Adverbs and adjectives often disrupt clarity.
- Break it down: split up beefy thoughts and sentences. As a pro once said, “The period never comes soon enough.”
- Cut caveats: every argument has exceptions. Every topic demands context. Still, unless specifically citing disclaimers, minimize hedging of statement.
- Clean out residue: With each new draft refine, reinforce, reiterate, and restate. Go back and strip out extraneous wording.
- Keep it short: don’t write more than required for the audience.
________________________________________
## Style Inventory (Framework)
@@@
Get back the details from [STD: Management # MANAGEMENT STYLE].
@@@
________________________________________
## Study (Research)
@@@
________________________________________
## MBA (Research)
The Master of Business Administration is a postgraduate University degree that focuses on Management. There are many Universities and Business Schools that offer such programs. 
  
Although a vast multitude of programs exist, sometimes for specific Sectors, the majority of MBA programs contain subject matters that are relevant to running a Venture and may include: background knowledge (Economics, Sociology, ESG) fundamental knowledge of Business Functions (Accounting, Operations, Marketing, Procurement, Human Resources) and academic knowledge of Management (Strategy, Corporate Governance, Management Theory including POLC). 
  
In addition of being a well established form of Research, it has the advantage of establishing a baseline level of knowledge, confirmed through a degree. 
________________________________________
## Dedicated Planning Note (Framework)
See [MGT: 01.Planning]
________________________________________
## Dedicated Organising Note (Framework)
See [MGT: 02.Organising]
________________________________________
## Dedicated Leading Note (Framework)
See [MGT: 03.Leading]
________________________________________
## Dedicated Controlling  (Framework)
See [MGT: 04.Controlling]


*********************************************
# PLANNING
Planning is the first Management Function and is concerned with defining a Strategy from a high level Mission to detailed Objectives. It aims at defining *why, what, where and when* and also the *how*. It is one of the most complete Functions within Management.
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Planning]. On L2 are the Tools:
- Context
    - Business Model
- Purpose
    - Purpose Statement
- Vision 
    - Vision Statement
- Mission 
    - Mission Statement
- Core Values
    - Core Values Definition
- Bylaws
    - Bylaw Definition 
    - Articles of Association 
    - Memorandum of Association 
- SWOT
    - SWOT Analysis 
    - Value Chain
    - VRIO
    - Pestel
- Goals 
    - Goal Definition
    - SMART
    - MSS
    - Budget
- Objectives
    - SMART
    - Objective Definition
    - Objective Properties
    - Objective Notation
    - MSS 
    - Project Management
    - Gantt Chart 
- Tasks
    - Task Definition 
    - Task Notation 
    - MSS
- Benchmark
    - @@@
- Strategic Plan
    - @@@
- Tactical Plan 
    - Planning Hierarchy
    - Tactical Plan
    - Roadmap
    - MSS
- Operational Plan
    - Operating Model Definition
    - COM
    - TOM
    - CMM
    - MSS
- Market Intel
    - Trends
________________________________________
## Business Model
A Business Model is the Venture's reason of existence mapped against the Profile.

### Design
The design of the Business Model follows the Profile.

### Clients
Understanding which Services (or Products) Clients' desire is key to delivering those Services. For this, additional properties for Clients extend insight into what is required:
- Customer Segments: give insight into the segment, or segments Clients fall into based on specific traits e.g. personality, interests, age, income, industry. Segmentation helps managing the relationship with clients (through Marketing), see [## Marketing]. 
- etc

### Services
Additional properties are important what Service (or Product) really means:
- Value Proposition: the value a Venture aims delivering Clients when they choose to buy Services or Products. 
- Distribution Channels: the Services (Products) need to be distributed to Clients. The manner in which this is done determines a significant part of the Venture's output. This may also rely on Suppliers (see below). 

### Operations
Understanding Clients and Services (Products) determines how the Operations contribute to what the Venture outputs. There are some specific considerations and manners in which one can look at Operations. Bear in mind that in Operations Staff use Assets and Suppliers to deliver the Services:   
- Core Capabilities
- Supplier network
- Cost structure
- Revenue model

### Management
Understanding the manner in which the above items are optimized using POLC.

### Business Model Types
There are various ways to set out the key elements of the Planning Function in simple overviews. Such representations can be used together with, or in, the Tactical Plan.
________________________________________
## Purpose Statement
<https://www.aespire.com/blog/communications/the-difference-between-your-purpose-and-mission>
________________________________________
## Vision Statement (Framework)
As per [MGT: 99.Legend]. Refer to:
- <https://www.atlassian.com/work-management/strategic-planning/mission-and-vision>
- <https://www.aespire.com/blog/communications/the-difference-between-your-purpose-and-mission>
- <https://asana.com/resources/vision-statement>
________________________________________
## Mission Statement (Framework)
As per [MGT: 99.Legend ### Mission]. A Mission Statement expresses *how* the Venture is going to achieve its Purpose. In other words, it explains a Venture's value proposition as follows:

    "Achieve X by doing Y for the benefit of Z"
    in which:
    X: What (type of) Services get delivered
    Y: How are they delivered (differentiating factors)
    Z: Whom receives the benefit i.e. Stakeholders

The Mission Statement is high level and sets out the overall direction the Venture should go into. Refer to:
<https://www.aespire.com/blog/communications/the-difference-between-your-purpose-and-mission>
________________________________________
## Values Definition (Framework)
@@@
________________________________________
## Bylaw Definition (Framework)
Bylaws, policies or equivalents define the boundaries, methods and obligations the Venture operates under. Depending on the Venture the above terms are used interchangeably or not. Bylaws are defined by Top Management for the entire Venture, whereas Policies are defined by the Management of the Activities. 

Bylaws are strongly driven by laws applicable within a Venture's country of incorporation. Other influences on the Bylaws are society, regulations, industry forums. Bylaws are reviewed on a periodic basis to assure they remain within the laws, regulations, and implicit expectations set out.
  
Bylaws should be easily accessible to anyone within the Venture. Nowadays this is mostly achieved through the use of intranets and equivalent repositories of information. 
________________________________________
## Memorandum of Association (Definition)
The Memorandum of Association (MoA) is a legal deed that builds foundation of a company, and outlines its Goals and scope of Activities and limitations of the Venture. It also maps out the relationship it has with Stakeholders including Investors, Creditors and Directors. The MoA is used to define the Articles of Association (see below). 

Key aspects of a MoA are:
- Name of the Venture
- Registered Office location
- Objective or Goals of the Venture
- Liability of shareholders a.k.a. members
- Capital restrictions in terms of total size, and distribution 
________________________________________
## Articles of Association (Definition)
The Articles of Association (AoA) is a legal deed that builds the Venture's internal norms, rules and processes for the Management and Operations of a Venture. 

Key aspects of the AoA are:
- Name of the Venture and form of business
- Purpose of the Venture
- Capital Structure
- Corporate Governance, incl rules related to decision making
- Administration of corporate records
  
AoA vs MoA
https://www.onboardmeetings.com/blog/articles-of-association-vs-memorandum/

Note that depending on the country, it is possible to not be required to have both MoA and AoA. For example in Hong Kong, only AoA are required since the new Companies Ordinance of 2006.
________________________________________
## SWOT Analysis (Framework)
Strength and Weaknesses of a SWOT refer to *internal* forces, whereas Opportunities and Threats refer to *external* forces. Internal means *within* the Venture. In other words, Strengths and Weaknesses (internal) refer to aspects that are in control of the Venture, whereas Threats and Opportunities (external) are not in control of the Venture. Details of how to perform a SWOT can be found here: 
<https://www.managementstudyguide.com/swot-analysis.htm> 

Each item in the SWOT should answer specific questions:

### Strengths
- What are differentiators in existing Services/ Operations?
- Which existing Services are most profitable?
- Which Services are better than competitors'?
- What do Clients perceive Strengths to be?
- What features do Services/Operations offer that competitors lack?

### Weaknesses
- What are areas in Services/Operations that could be improved upon?
- What shortcomings exist in Services/Operations?
- What Resources are missing (Assets, Suppliers, Staff)?
- What features/functionality do the Services lack?
- What characteristics might a Client view as a weakness?

### Opportunities
- Can additional value be created to existing Clients?
- Are there similar Services that could be delivered that provide an opportunity?
- Are there new markets that can be pursued?
- Are there new Clients in existing markets that can be  pursued?
- Can more of existing Services be generated with existing Operations?
- Can new Services be generated with existing Operations?

### Threats
- What hurdles are there?
- Who are competitors?
- Has competition increased?
- What are competitors doing?
- Are customers buying alternate Services? Why?
- Is changing technology making providing existing Services difficult?
- Are there economic issues or changes in your industry?

There are various Tools that further help in a SWOT analysis:
- Value Chain, see [## Value Chain]
- VRIO, see [## VRIO]
- Pestel, see [## Pestel]
________________________________________
## Value Chain (Framework)
Value Chain is a tool used to define and analyse *internal* aspects (Strengths, Weaknesses) of a SWOT (see above). It was designed by Michael Porter and is a useful tool to assess organisational capabilities. Note that the term Value Chain is sometimes also used within Operations to denote the Activities generating Revenue.
________________________________________
## VRIO  (Framework)
VRIO stands for Valuable, Rare, Inimitable, Organisation. It is another Tool used to define and analyse the *internal* aspects (Strengths, Weaknesses) of the SWOT (see above).
________________________________________
## Pestel  (Framework)
Pestel stands for Political, Economic, Socio-cultural, Technological, Environmental, Legal environments. It is a Tool used to analyse and define the *external* aspects (Opportunities, Threats) of the SWOT analysis, see above).
________________________________________
## SMART (Framework)
SMART (Specific, Measurable, Aggressive, Realistic, and Time-bound) is a Framework used to define Objectives.

### Specific 
Objectives need to be specific, well scoped. This is achieved by applying the 6W, see [MGT: 99.Legend #### 6W Framework].

### Measurable
Measurable relates to the *expected Result*. For simplicity it is broken down into the following *Measurement Types*. The *verbs* are also discussed in [## Objective Notation].
- Quantitative: Result can be measured and has many possible values, indicated by verbs like: 'Decrease ...', 'Increase ...', 'Expand ...'.
- Binary: Result is either done or not, indicated by verbs like 'Do ...', ' Study ...', 'Get ...', 'Produce ...', 'Create ...', 'Build ...'
- Qualitative: Result is open to interpretation: to be avoided!

The notion of an expected Result is important when considering performance management frameworks in the Management Function Controlling. Examples of such frameworks are Management By Objectives (MBO), Balance Score Card (BSC) and Objective & Key Result (OKR). The choice of model depends on corporate push, manager preference etc. Details in [MGT: 80.Tools ## Performance Management].

### Aggressive
Objectives need to push the Venture further and should thus be aggressive or ambitious. 

### Realistic
Despite the above ambition Objectives should be attainable else there is little incentive to work on them. 
NB: for OKR, see [## OKR], actually completing an Objective is *not* a requirement.

### Time-bound
Objectives need to be Time-bound. Time constraints dictate urgency and dependencies. it also adds a dimension to Measurable i.e., *complete before some deadline*.
________________________________________
## Goal Definition (Procedure)
Goals are established based on the Mission as well as medium term view of where the Venture should go. Structurally, Goals follow a very similar pattern regardless of the Venture. Below two sections detail the Standard Run Goals and Change Goals using Objective Notation, see [## Objective Notation]. CEO represents the owner of the owner of the Goals, it is to be replaced with the name or initials of the Managers. 

#### Work Run Goals
% mgt (19700101:99991231) {CEO} |VNT| [Perform Management. Perform the Four Management Functions of the POLC that assure the Venture keeps up and running. This Goal assures a structure is put in place, and maintained, such as to generate and optimise Revenues, Cost, Risk, Liabilities and Equity in order to support all other Goals. This goal also drives Change.]

% ovh (19700101:99991231)  {CEO} |VNT| [Perform overhead. Perform Processes that do not directly contribute to Services but that need to be performed nevertheless. It is a default Goal that should not be used often simply because any Process that does not increase Revenue and/or decrease Cost  and/or decrease Risk is essentially a Cost.]

% ovs (19700101:99991231) {CEO} |VNT| [Perform Oversight. This is the performance of Routines in relation to data from Operations with a focus on Risk Management & Production Performance. There are four different categories of Routines: Checks, Reviews, Attendance in meetings and Audits. This Goal includes the definition of KPIs and  KRIs to measure against. It also includes Routines to investigate incidents and  problems when they occur -mostly unexpected- in order to define mitigants. Lastly, this includes assisting Suppliers like internal Auditors to perform reviews/audits of Activities and similarly it includes assisting external parties from the Environment like Regulators or Government in their reviews and audits.] 

% prd (19700101:99991231) {CEO} |VNT| [Perform Production. Perform Routines that directly contribute to the delivery of Run Services. Depending on the Activity, this Goal has different Routines. Some can relate directly to the generation of Revenue, whereas other Activities perform Routines to support the generation or Revenue. This Goal can include Routines delegated by Management that relate to the maintenance of Environment, Services, Staff, Suppliers and Assets, and that are each not part of a dedicated Activity e.g. HR, Procurement.]

NB: The Management Function Controlling is generally reviewing performance of the Venture Activities represented through Goal = Perform Production as well as the review of risk mitigation through Goal = Perform Oversight. Ultimately, Management is accountable for the proper performance of those Goals even if it delegates the performance of those Goals to various Activities. Management obtains assurance that those Goals are achieved through Controlling. See also [## Delegating Definition] under [# ORGANISING].

Above Run Goals are generic and apply to all Ventures.  

#### Work Change Goals
$ prj (19700101:99991231) {CEO} |VNT| [Deploy Projects. A catch all Change Goal for any Project that cannot, or should not be captured, in any of the other Change Goals. It also includes Projects to improve Goal = mgt and Goal = ovh and it includes Projects that arrive throughout the year and that are urgent to complete but which are not originally planned in the other Change Goals and which are, by choice, not added to those other Change Goals.]

$ gro (19700101:99991231) {CEO} |VNT| [Grow Venture. All initiatives aiming at growing Goal = prd i.e. adding new or changing existing Production Processes enabling the financial growth of the Venture by offering more/better Services and/or to more/better-suited Clients with the aim to increase Revenue. This goal is pro-active.]

Key deliverable for above goal = Revenue addition.

$ pro (19700101:99991231) {CEO} |VNT| [Protect Venture. All initiatives aiming at protecting Goal = prd i.e. adding or changing Production Processes with the aim to preserve/protect Revenues in Goal = prd. This is achieved by offering similar/equivalent Services and/or to similar/equivalent Clients. This Goal is often required as a result of changes in the Environment. Contrary to Change Goal = gro this goal is reactive.]

Key deliverable for above goal = Revenue protection.

$ opt (19700101:99991231) {CEO} |VNT| [Optimise Venture. All initiatives aiming at improving Goal = prd i.e. improving existing Production Processes to do more/faster/smarter/etc. with the aim to increase Revenue and/or decrease Cost in Goal = prd . This includes Routines specifically related to Cost Management.]

Key deliverable for above goal = Revenue addition, Cost reduction

$ sec (19700101:99991231) {CEO} |VNT| [Secure Venture. All initiatives aiming at improving Goal = ovs i.e. improving existing Oversight to do more/faster/smarter/etc Reviews and/or Controls and/or Committees and/or MIS with the aim to decrease Risk in Goal = prd.]

Key deliverable for above goal = Risk Reduction, and thus Revenue Protection. The difference with Goal = pro is that Revenue is know to be eroded and unless that goal is to achieve Revenue will be less. For secure venture, we talk about risk, i.e. the probability that Revenue might be eroded, not that it will be eroded. Also, not all cases.of risk are viewed as Revenue impacting.

$ tmp (19700101:99991231) {CEO} |VNT| [Temporary Items. All initiatives that have been raised but never prioritised, or items which were prioritised but deprioritised and never reprioritised. This goal serves as a parking spot for initiatives and avoids cluttering of initiatives within the other Goals. Initiatives in this Goal should be reviewed yearly to see if they should be deleted altogether.]

The latter goal ties in to the prioritisation process discussed in [## Project Management].

$ oth (19700101:99991231) {CEO} |VNT| [ Other items. All initiatives that are not worked on by the Venture, but impacting the Venture or, more generally, need to be tracked without working on it]

These Standard Change Goals are applicable to any Venture. Obviously, the focus on each Goal, expressed as the number and complexity of the Objectives within each Goal will change from Venture to Venture and even within a Venture from year to year. 

### Sub-Goals 
Sub-Goals regroup Objectives of a similar *theme*. This is mostly done to focus on a specific set of Objectives. 
Using such Sub-Goals is optional. If Sub-Goals are one can obtain the following hierarchy:

    Change Goal                 
        Change Sub Goal 
            Project                   -> Change in Routines
                Stream
                    Action
                        Process 
                            Activity (Group) ⇔ Staff  -> Revenue, Cost, Risk  
                                Asset          -> Cost, Risk
                                Supplier     -> Cost, Risk 
                                Liabilities   -> Cost, Risk
                                Equity         -> Cost, Risk
  
Run Sub-Goals have several standard values for each Run Goals as per below:
  
### Quantification of Goals
Goals can be quantified in different manners. The above Goals have not been quantified yet (they are generic).

Run Goals are composed of Routines, see below. Quantification of Routines can be through:
- Revenues generated
- Cost generated
- Risk generated
- Count nr of Routines
- Count nr of Processes within Routines
- Count Effort spent on Process(es)
- Count nr of Results e.g., nr of documents produced, etc.
- A combination of the above by Routine or across all Routines and within or across all Run Goals
  
Change Goals are composed of Projects, see below. Projects change the Run by improving it or extending the output of Run (adding Routines etc). Quantification of Projects can be as follows:
- Extra Revenues generated
- Extra Cost generated or avoided
- Extra Risk generated or avoided
- Compare Nr Routines added to existing Routines
- Compare Nr Processes added to existing Processes
- Compare Effort reduction for existing Processes
- Compare change of Result (new, improved Results) 
- Combination of above all Projects affecting a  single Routine or many Routines and that within a Run Goal or across all Run Goals.
________________________________________
## Objective Definition (Framework)
Objective Definition is about the differentiation between what constitutes a Routine, a Project or a standalone Task. This was previously explained in [MGT: 99.Legend ## Objectives] and is elaborated on here.

To be specific:
- Routines: linked to Run Goals i.e., focus is on generation of Revenue (prd), assuring Revenue is as expected, at lowest Cost and/or lowest Risk (ovs) but with some work done that does not directly or indirectly contribute to Revenue (ovh) or to assure the previous Goals are all optimised (mgt).
- Projects: focus is on Change Goals i.e., the improvement of the Run.
   
There are cases where work is being asked to be performed which is neither specifically Run and also not a Project. In that case the Manager has two options to record that work:
- Run Goal = ovh -> Run Sub-Goal = one-off
- Change Goal = oth

The differentiating factor is whether it it worth tracking as an actual Project or not.
________________________________________
## Objectives Properties (Framework)
See [MGT: 99.Legend ## Objectives] for basic definitions. 

Objectives can have either a precise required Effort to execute, a reasonable expected required Effort or at best an estimated required Effort. Consequently, and depending on when the Result is desired, a Start and End time for the Objective can be accurately planned. Objectives can be prescribed i.e. documented/ formalised or not and such details can be pointed to with a Reference to a File, URL, Note, etc. Objectives can have various Status indicating where they are at: Open (not started), Started, Pending (something else), Completed, or if the Result is required on a periodic basis an indicator that the Objective is a Routine. 

The note MGT: 99.Legend explains 5 properties for Objectives:
1. Clear and unambiguous description of target
2. Measurable
3. Linked to a Goal
4. Specify *Start* and *End* date or *Recurrence*
5. Specify *Who* is accountable for delivery, tying it into Organising

In addition to these properties, SMART principles apply, see [## SMART]. The 6W of SMART are mapped as follows:

- What: point 1
- When: point 4
- Who: point 5
- Why: point 3
- How: not addressed
- Where: not addressed, mostly the Venture location

### How Specifics for Objectives
The *How* is more detailed which can be free text, reference to documents etc., see [## Objective Notation] on how this achieved. 
  
### Who Specifics for Objectives
There is a difference between *Who* owns the Processes within the Objectives (*owner*) versus *Who* receives the benefit of the Objectives (*beneficiary*). When *who* is referred to the former is often meant. The difference is clarified in [## Objective Notation].  
 
The owner of an Objective is either a specific Staff or a Group. By default, the owner is the Group associated to the Activity in which the Objective is performed. Within that Group a specific owner can be assigned. 
By default, the Manager of an Activity in which an Objective is performed is responsible for the Objective. The manager gets those responsibilities delegated by the Manager of the Venture. See also [## Objective Definition], [## Activities Definition] and [## Delegating Definition].
________________________________________
## Objective Notation (Framework)
Objective Notation is an expansive formalised structure to write down anything from Goals all the way to Actions/Drills and even Comments. Although the primary use is for Objectives (Projects, Routines) it can be used for Tasks as well. In this section, and unless mentioned otherwise, when *Objective* is mentioned it can be replaced with *Project*, *Routine* or *Task*. 
For example, *Objective Indicator* is the same as *Task Indicator* or *Sub Indicator*, *Objective Notation* is the same as *Task Notation*, etc. Specifically, Task/Project and Recurring Task/Routine are equivalent. See also [## Task Notation].

Although the Objective Notation is well structured and appears very formalised, this does not mean  formalism is required. Ultimately, the user of Objective Notation can use it in many ways, depending on needs. Below explains the formalism, and also shows a less rigid interpretation.  

### Objective Notation Format
The Objective Notation Format uses 6 so called *Objective Components* or *Objective Indicators* as follows:

status name (date) {owner} |link| [reference]

This notation links to the 6W as follows:
- status: this is not part of the 6W
- name: indicates *What*
- (date): covers all elements of *When* 
- {owner}: covers all elements of *Who*. 
- |link|: explains *Why*.
- [reference]: pointer to details, explaining *How* 

There is no Objective Indicator for *Where* because:
a. Objectives are owned by Staff 
b. Staff are mostly located in a single location 
c. An Objective is often agnostic to the location and if it is really not it can be added in the *How*.

The order of components is critical:
1. Certain combinations have special meaning in Markdown: [...](...) w/o space between ']' and '(' is a URL.
2. Date Indicator can be considered part of an Objective Measurement e.g. "Check output (daily)".

The number of spaces *between* components is optional i.e., there could be none or many. However, there *cannot be any* space *before* the Status Indicator and their *must* be at least one space after it. Note that when using Objective Notation in a *hierarchy* it *is* possible to precede Status with spaces see [### Objective Notation Hierachy]. Only Status and Name are mandatory. 

###  Objective Notation Status Indicator
Status is mandatory and uses symbols:  
%                 Run Goal, Run Sub-Goal (percentage)
$                  Change Goal, Change Sub-Goal (dollar)
&                  Routine (ampersand)
.                    Project, Not Started (dot)
/                   Project, Started (forward slash)
~                  Project, Pending or Delegated (tilde) 
x                   Project, Closed (lower case letter x)
!                    Project, Urgent (exclamation mark)
-                    Comment (dash or hyphen)
+                   Comment (plus)
_                   Comment (underscore)
dd-mm-yy: Comment (date format comment)

As can be seen, the Status Indicator symbol is a single character, except for the last form, the *date format comment*. A Status Indicator does two things simultaneously: indicating whether an entry is a Goal, Project, Routine or Comment, and in case of a Project, it also shows the status of the Project.
NB: the '~' in Excel is a special character (escape char). To use '~' in functions like VLOOKUP() substitute it first using SUBSTITUTE (). 
The use of '-', '+', '_' and 'dd-mm-yy:'to reflect *comments* means Objective Notation can be used for writing *any* form of text, keeping a log, etc. It also allows the use of the other Indicators which adds insight into aspects of the comment e.g. dates, who is involved, etc.

### Objective Notation Name 
The Name is mandatory. For Goals the Name is a short three character code, see [## Goals Definition]. For Sub-Goals a one or two word label is used. For Objectives (and the levels below) the Name should adhere to four requirements:  
1. Start with a *verb*
2. Contain a *measurable* expected *Result*
3. Cannot contain any indicator brackets: (, ), [, ], {, }, |
4. Can contain any other characters that are not the ones in  item 3. above e.g., #Hashtag, ##1, *italic*, /slashes\, **bold**, Stop!, Say: "This shall be done!", etc  

Note that *if* for aesthetic or sorting reasons, it is preferable to start the name for an Objective with a number then this is possible e.g., 01.Planning, 02.Organising, ... 

Verbs are an indication of *targeted Result*, see [## SMART]:
- Assess: obtain a result and compare against expectations 
- Assist: somebody in execution of their Process
- Attend: prepare + attend a meeting/event
- Audit: an Activity or entire Profile Tree 
- Build: something new from scratch and deploy it
- Complete: something started elsewhere/prior 
- Check: verify Result against benchmark + remediate
- Control: see Check
- Create: same as Build
- Define: Target/expected Result
- Deploy: as new something existing elsewhere 
- Design: something to be built by others
- Discuss: a topic at one point (can act as a reminder)
- Expand: something existing by adding to it
- Explore: establish if something merits in eating into
- Improve: something existing by automation etc.
- Increase: something existing by a numeric value 
- Learn: how something operates 
- Maintain: something existing at current level
- Manage: as per the definition of Management 
- Meet: someone on regular or ad-hoc basis 
- Perform: one or more specific Processes 
- Plan: a meeting 
- Prepare: a deliverable for completion elsewhere
- Process: take in a request and deliver Result
- React to: a situation with specific measures 
- Report: inform results from a Process' result to someone
- Resolve: a problem 
- Review: a Result vs Target + determine if change needed 
- Rewrite: an existing document

Short versions of Verbs are possible e.g.:  
- "D: " refers to "Discuss"
- "P: " refers to "Plan" 

The short versions serve visually as a reminder to do something.

Routines can be appended with " - D", " - W", " - BW",, " - M", " - Q", " - H", " - Y"  , " - AH" for daily, weekly, bi-weekly, monthly, quarterly, half-yearly or semi-annually, yearly or ad hoc. Although such indicators for periodicity are also reflected in the Date Indicator (see below, it is sometimes useful to see it in the Name because the Name often appears in Reports. Depending on the context other post-fixes can be added such that they add additional information to the name e.g., " - Prio", " - Budgeted", ...

The Name indicator is the least rigid of the Objective Indicators. Although starting with a verb is strongly recommended, nothing stops someone from using names like:
. Main Project: do something
/ WARNING: this to be done before all others
etc 

### Objective Notation Date Indicator
The Date Indicator reflects *start*, *end* and *complete* dates for Projects and *frequency* for Routines:
- Projects:  (start:end:complete:effort)
- Routines: (period:start:end:effort)

The start (start date), end (expected completion date), complete (actual completion date) are of format yyyymmdd-hhmmss i.e., year, month, day, hour, minute and second digits with hhmmss being optional.   
The *period* can be any alphanumerical characters e.g. daily, monthly, Jan, Feb, 2021. The start and end in case of a Routine are optional and they indicate when a routine was first / last used. If a Routine is deprecated, both start and end have to be provided because only one date is asumed to be a start date.   
The *effort* is a number of type float e.g. 1, 0.33 indicating the number of *days* that will be or have been, spent on the Objective in a *year*. Effort for Routines is *total* effort in *days* spent on that Routine per *year*. When start and end are omitted for a Routine, the colon ':' is also omitted leaving (period:effort). For Projects it is the effort in days for the duration of the project, regardless of whether it is within the year or across years. It is possible to have an effort even if the Project has not started. In that case effort represents *expected* effort. The combination of Status, End and today's date can indicate if a Project is overdue. For Goals and Sub-Goals the same logic as for Projects can be used.

As with the Name Indicator, the Date Indicator can be used less rigidly e.g., (Deadline: next week), (tomorrow), (Start tomorrow, Due 31 Dec 2021), etc.

### Objective Notation Owner Indicator
The owner of an Objective represents the *performer*, i.e., the Staff or Group responsible for the completion of the Objective *and*, in addition, it represents the *beneficiary* of the Objective i.e., the Activity for, or in, which the Objective is performed. By default, performer equals beneficiary, but this is not always the case: an Activity ABC providing Services to another Activity XYZ: performer = ABC, beneficiary =XYZ. The format is as follows:  
  
{performer:beneficiary} or {perf:benef}
  
In which: 
- performer is a Staff or a Group. 
- beneficiary is an Activity or the entire Venture. 
  
If no performer is mentioned i.e., {:beneficiary} then the Group associated to the Acvitity benefitting the Objective should be interpreted. Similarly, if there is no Beneficiary i.e., {performer:} then the beneficiary should be read as the Activity linked to the Staff or Group performing the Objective. If neither is explicitly provided i.e., {entry} then both Performer and Beneficiary are the same i.e., {entry} = {entry:entry}. Note that if Status indicator is ~ (delegated Project) and Owner Indicator is provided, it effectively means that the Objective has been delegated to the Staff or Group indicated by the Owner indicator.  
  
Owner Indicator is optional in which case it can be written as {} or omitted altogether.
  
### Link Indicator
A Link Indicator is used to link:
i.   Goals (Run-Goals, Change-Goals) to the Venture or
ii.  Sub-Goals (Run-sub-Goals, Change-sub-Goals) to Goals or 
iii. Objectives (Routines, Projects) to Sub-Goals or
iv.  Routines to Run Sub-Goals or directly to Run-Goals or
v.   Projects to Change Sub-Goals or directly to Goals or
vi.  Streams to Projects / Subs to Routines or
vii. Actions to Streams / Drills to Subs
  
The link indicator is considered text even if stated as a number e.g.,'1', '1.1'. 
  
Link Indicator is optional in which case it can be written as || or omitted altogether.

### Objective Notation Reference Indicator
The Reference Indicator 'refers' to a separate location with more information using the logic as described in [MGT: 99.Legend ## Note Reference] *or* contains free text. In other words, Reference Indicator is:
1. Free text or
2. Reference to a Section or Note or
3. Reference to a File or
4. Reference to a URL or
5. Reference to a Mail or
...
etc.
  
Free text can be used to provide comments, but can also be used to show the next Task, using Task Notation *within* the Reference Indicator i.e., [. nnn], [/ nnn],  [! nnn], [~ nnn] and [x nnn] in which nnn is the Task to be done using Task Notation. With Task Notation being the same as Objective Notation it is thus effectively possible to nest Tasks within Tasks and Objectives within Objectives which can also be considered nesting Tasks within Objectives. Alternatively, one can see this as Streams within Objectives. Don't get confused by the terminology! Concatenation of Tasks is possible as well using a double '&' symbol (ampersand) e.g., [/ Do something && . Do something else afterwards]. See examples below.
  
Reference Indicator is optional in which case it can be written as [] or omitted altogether.  
  
### Objective Notation Hierarchy 
As was mentioned in [MGT: 99.Legend] there exist two hierarchies that drive work throughout a Venture: the Project Hierarchy and Routine Hierarchy, depicted visually below. 
 
Venture
    Run Goal  
        Run Sub-Goal      
            Routine  
                Sub  
                    Drill  
    Change Goal  
         Change Sub-Goal  
            Project  
                Stream  
                    Action  
   
Instead of using the Link Indicator to Link Sub-Goals to Goals, Objectives to Sub-Goals, Streams to Projects, etc. it is possible to omit the Link Indicator and instead apply an Objective Notation Hierarchy using indentation as follows:

status name (date) {owner} [reference]
    status name (date) {owner} [reference]
        status name (date) {owner} [reference]
            status name (date) {owner} [reference]
                status name (date) {owner} [reference]

This format is useful to visually show the relation between Goals, Sub-Goals, Projects/Streams/Subs and Routines/Actions/Drills. The above is a *possible* display, it may not be *desirable* to use this too often: it can become difficult to read.

### Objective Notation Expanded Format
With above details of the various Indicators, the expanded format for Objective Notation can be written as per below:
  
Run Goals and  Sub-Goals:  
% name (period:start:end:eff) {perf:benef} |link| [ref]  
  
Change Goals and Sub-Goals:  
$ name (period:start:end:eff) {perf:benef} |link| [ref]  
  
Routines:
& name (period:start:end:eff) {perf:benef} |link| [ref]
  
Projects (any of below, depending on status):  
!  name (start:end:compl:eff) {perf:benef} |link| [ref]   
.  name (start:end:compl:eff) {perf:benef} |link| [ref]   
/  name (start:end:compl:eff) {perf:benef} |link| [ref]  
~  name (start:end:compl:eff) {perf:benef} |link| [ref]  
x  name (start:end:compl:eff) {perf:benef} |link| [ref]   

### Objective Notation Examples
& Backup data (weekly) [MGT: 12.Assets ## Backup Weekly]
. Build control against corruption (20210131)
/ Study Book HHGG (20210331)|learn| 
/ Prepare diner [x Purchase ingredients && . Make meal]
~ Pay tax (20220630) [~ Get details (20220515) && . Lodge details (20230630) [URL: http://taxwebsite.com]]
x Build software to automate mail sending (20190101:20190228:20) {SE} |opt|
/ Build software to automate mail reading (20220323)
    x Design program [Based on document received]
    / Purchase SDK from Supplier [~ Complete contract w supplier]
    . Develop code
    . Test code 
    . Deploy software (20230323)
~ Wait for approval to do something smart 
. D: Discuss something with someone else (next time we meet)
/ Study Astronomy (20220531) {myself} |std| [/ Get book (20220304) {Gary} [Borrow for 2 months] && . Read book && . Pass astronomy exam (20220515) ] 
  
### Objective Notation Weaknesses 
There are some weaknesses in Objective Notation:
- Objectives consume Assets and/or Suppliers which are not reflected in the Objective Notation Format and can only be detailed through the Reference Indicator. 
- Objective Notation is very versatile and allows for intricate details (see last example above). There is a risk that entries become too long to be practical.
  
### Objective Notation and Eisenhower Matrix
Tying the five status indicators of Projects to the Eisenhower Matrix principles (see [## Eisenhower Matrix]), yields:

urgent + important                -> do now    ->  !
not urgent + important         -> do later   ->  / and .
urgent + not important         -> delegate ->  ~
not urgent + not important  -> delete      ->  x 

The latter one reflects an Objective that would be created *and* completed, or, because a Project has finished, it is neither urgent nor important anymore. 

From a managerial perspective this means only Projects of the following type are performed by the Manager himself: "!", "/" and "." Other projects are delegated "~" or deleted "x".

So what if a Manager would need to do something himself, but them requires some input from someone else. One way to achieve that is as follows:
/ Do some task [~ Get input {someone}]
________________________________________
## Tasks Definition (Procedure)
Tasks can be used to add granularity to Objectives, Streams, Subs, Actions and Drills. Tasks can *also* be used to more generally indicate *work to be done*, without them being linked to Objectives.

Tasks are managed in different ways:
1. Task Apps
2. Mail to self
3. Tasks in notes
4. Tasks in MSS

### Task Apps
As mentioned in [# BASELINE] various apps exist to manage Tasks: Google Tasks or Outlook Tasks.

### Mail to Self
It is possible to send one-self a mail as a form of Task. 

### Tasks in Notes
There exist different types of notes that hold Tasks i.e. Journal related notes, Meeting notes, etc. Refer to [## Task Notation] below for more details. 

### Tasks in MSS
There exist sections in MSS that hold Tasks. Refer to [## Task Notation] for more details. 
________________________________________
## Task Notation (Framework)
See [## Objective Notation]. 
________________________________________
## Project Management (Framework)
Managers deal with Project Management, either because they manage Projects as part of the Planning or they manage Staff who manage Projects. 

### Project Attributes
Project Management has three key attributes:
1. Scope
2. Cost
3. Time

This is referred to as *Project Management Triangle* (PMT) which says that increasing/decreasing any aspect affects the other two (one or both). The role of a Project Manager (PM) is to optimise this and to report progress and issues to Key Stakeholders including Sponsors, see [### Sponsorship}, under [## Delegating Definition].

#### Scope
Scope is determined by the expected Result and the Implementation to achieve that Result. Scope drives complexity and breadth of a Project and thus the Resources (Assets, Staff, Suppliers) required. Scope is constrained by available Resources, and reversely, Resource availability drives the Scope.

#### Cost
Cost is driven by Resources. For any Project, one, two or all Resource tyoes are required (Staff, Assets, or Suppliers). Cost is constrained by Budget and reversely drives Budget.

#### Time
Time is driven by availability of Resources and constrained by internal / external deadlines. Reversely, availability or lack of Resources drives deadlines. 

### Project Phases
The Project Management Institute defines five phases of Project Management:
  
1. Conception & Initiation
Broad definition of the Project, often driven by a Business Case, in turn driven by one of the Change Goals discussed above, which is driven ultimately by a Beneficiary.  Deliverables:
- Key Stakeholders: Staff and Suppliers likely involved in executing the different Tasks of the Project and Sponsors (beneficiary of the Project)
- Business Case: why the expected Results are desired.
- Goal: clear description of expected Results.
   
2. Definition & Planning 
Establish specific Project Objectives according to SMART principles, see [## SMART]. Deliverables:
- Scope Statement
- Gantt Chart with Project, underlying *Streams* (the completion of which being called a *Milestone*) and *Actions* with Start/End/Complete, Owner, and Status. See also [MGT: 99.Legend ### Projects] for breakdown of Projects. 
- Risk Management: details of Risks that could materialise and how to mitigate these
- Communication Plan: manner in which above two items will be reported on over the timeline of the Project including whether Risks have materialised.
- Definition of KPI, see [##KPI] to be able to perform step 4. 
   
3. Execution
This is actual work done on the Project by the Stakeholders, i.e. execution of the Streams and Actions.
  
4. Performance & Control
A PM monitors and tracks progress of phase 3. through [MSS: M5] which helps execute the above.

5. Project Close
The last phase of a Project is the closure. The purpose is to formally halt the contribution of resources to the Project, and validate that the deliverables have been achieved (fully or partially). The closure of a Project also aids in learning from the successes and mistakes of the Project. This in turn will enhance the next Project the PM and the members of the Project will work on. 

### Project Hierarchy
As indicated above, Projects are often divided in smaller chunks each with clear deliverables, the total of which is "The Project". The following hierarchy is used in this note, but it is perfectly possible to have variations:
 - Project
    - Stream
        - Action
  
### Project Priority
Inevitably, Projects often have a certain level of priority attached to it. One way of managing this is through a notion of *Project Priority* with the following values (in brackets the MSS values): Critical (0-Crit), High (1- High), Medium (2-Med) and Low (3-Low). By keeping the number of priorities low, it remains manageable. Often they are color coded: Red, Amber, Yellow, Green or Black, Red, Amber, Yellow.  Project Priority is determined by the beneficiary of the Project. However, and particularly if the Project Manager has many Projects to manage, the tendency will be for each Beneficiary to say their Project is the most important and should thus have the highest Priority. This is where the Priority Guidelines come in!

### Priority Guidelines 
The main idea is to delimit the criteria for a Project (and Stream, Action) to appear under a priority. The result of below approach, is that at the *start* of the Roadmap, see [## Roadmap] Projects should be having priority High or Low and that during the year some Projects can appear in Critical, and Medium. The duration of a Roadmap is deemed a year, but have a longer or shorter cycle. Similar guidelines apply to Streams and Tasks within the Project if they have been defined. 
  
Note that above approach depends on how Resources are managed. It is possible that a Venture keeps some slack in their Project assignments to be able to cope with new Projects arriving during the year. The availability or not of such Resources will mostly change in priority Medium.
    
0-Crit
Applies only to non-planned Projects, i.e., not part of the Roadmap. Such un-planned work can only be done for two type of Goals: Secure the Venture (Goal = sec) and Protect the Venture (Goal = pro). The reason is that growing or optimising a Venture (Goal = gro or opt) is not something that comes unplanned. 
There should be very few of such unplanned Projects. Priority Critical supersedes all existing Projects. So the number of Projects with this priority should be kept close to 0, and there can be only as many as required to Protect or Secure a Venture on short term. 
In most cases Critical Projects emanate from specific demands or opportunities from the Environment e.g. Regulators, from senior Management or internal Suppliers in control functions, or alternatively by self-identified major zones or risk that were unknown until recently. 
Note that in MSS items of Planning Type = Venture, or Chg Goal are flagged Critical as well. This assures that they are always picked up on when doing filtering on priority).
  
1-High
This priority should be given to those Projects planned for this years' Roadmap. This priority can also be given to Projects that appear during the year, and that if they would have been known about at the start of the Roadmap, they would have been in the Roadmap. This may, however, mean that other Priority 1-High Projects need to be reclassified! Declassifying existing Projects' priority depends on a) whether existing High Projects were completed before their deadline and b) Resources, which may have increased. 
  
2-Med
This criticality is used for any Project that is not Critical or High but that ideally should be done during the year nevertheless. The real purpose of this criticality is to keep track of existing Projects without prioritising work on them. This helps keeping track of need for Resources and such Projects may be used as input for the Roadmap the year after. Note that if a Venture uses a planning approach where Resources are not fully allocated to Projects for the Roadmap, then this priority represents those Projects that can be worked on *in addition* to the Roadmap. Thus, Projects with this priority are worked on if there is some slack in the Planning *by design*!  
    
3-Low
Anything that will not be done this year but the year after i.e., it is known at the start of the year that this will not be worked on! This priority acts as a placeholder. Note that any residual Project not finished from above three cases will likely also move to next year but unless they are de-prioritised they will have a 1-High Priority at the start of the year.  It is very well possible that all Priority Low projects are flagged under Goal = tmp to clear out the Projects that  are not being worked on.  
  
4-non
This Priority is used for anything that is not the above (in MSS it is used for the Run i.e. Run Goals, Routines, Subs and Drills). 
   
5-tbc
This Priority is temporary and means what it says: To Be Confirmed. It is entered as a placeholder for items for which the priority still needs to be defined. 
  
NB: if the Priority of Projects is never established, or if a Project is deemed not worthy of investing in anymore it should be deleted.

### Project Urgency
In addition to the manual priority described above, there is a notion of *urgency* caused by an approaching deadline of the Project (End Time). 
  
The following gives a good indication of urgency. By using this approach it can be easily programmed in MMS. The approach avoids maintaining an actual level of completion of the Project (not tracked in MSS) and uses only the duration between Today and End time. Similar observations apply to Streams and Actions. 
   
0-Crit
Projects that are overdue:
    Today >    End Date

In MSS this Urgency is also used for Chg Goals.
   
1-High
Projects within 1 week of the deadline:
    Today < End Date
    Today => End Date - 7
  
2-Med
Projects within 1-2 weeks of the deadline: 
    Today <    End Date - 7
    Today => End Date - 14
  
3-Low
Projects more than two weeks of the deadline. 
    Today <    End Date - 14
  
4-non
Projects that are completed. In MSS it is also used for Run Goals, Routines, Subs and Drills.  
________________________________________
## Gantt Chart (Framework)
A Gantt Chart is a chart in which horizontal lines show work (effort) -to be- done in certain periods of time in relation to the amount planned for those periods. It is very useful to give an overview of planned work and how much of that has been achieved and can thus act as a Tactical Plan, see [## Tactical Plan]. It is a good way to measure progress, see [## Measurement]. It does, however, not measure progress against deliverables e.g. Cost reduction, which needs to be measured separately.
MSS has a built-in Gantt Chart, see [## MSS].
________________________________________
## Tactical Plan (Framework)
A Tactical Plan sets out a higher level view of Goals, Sub-Goals and Objectives throughout the year. More info on p. 217 of Principles of Management. In addition to showing progress, a Tactical Plan also shows the ratio of Effort in Run vs Change.
________________________________________
## Roadmap (Framework)
A Roadmap is an implementation of the Tactical plan that is used to communicate with Stakeholders. It is an often referred to term to indicate "key targets to be delivered this year" and these are effectively *Change Goals*.

A Roadmap focuses on specific *initiatives* which are essentially the Change Sub-Goals, see [## Goal Definition]. These Sub-Goals, given they are considered specific initiatives, facilitate communication with Stakeholders. 

For example, Goal = Optimisation, can contain a set of Objectives all aiming to eradicate duplicate processes and as such can be regrouped in Sub-Goal  "Eradicate duplicate effort".  

Roadmaps thus include Sub-Goals and are most often visualised through a Gantt Chart. Roadmaps are mostly planned for a calendar year. Structurally a Roadmap could thus look like this:

Change Goal abc
    Change Sub-Goal abc - def
        Objective 1.1
        Objective 1.2
    Change Sub-Goal abc - xyz
        Objective 2.1
        Objective 2.2

and similar for each Change Goal. 
________________________________________
## Operating Model Definition (Framework)
An Operating Model, *Operational Model* or *OM* lays out the various aspects that make up a Venture across the Profile Tree. Although this section focuses on a Venture it could as easily be used for an Activity within the Venture.
  
The purpose of this section is to give explain the OM through the 6W Framework i.e.:
  
What is it the Venture does (Activities), Why the Venture does it (Revenue generation whilst minimising Cost and Risk), How the Venture achieves it (Routines, Projects and deployment of Assets), Who does it (Staff, Suppliers), When do they do it (timing of Routines, Projects), and Where is it done (locations). In addition, the Operating Model also explains the Management of the Venture.
  
The OM is relevant to a broad range of users: the Manager of the Venture, direct support functions of the Manager like a Chief Operating Officer or Chief of Staff, Suppliers, Business Functions, Clients and other Stakeholders from the Environment like Regulators.

The OM is explained through the Expanded Profile Tree, with a list of aspects to consider for each Item. The list is indicative, i.e., it is possible to omit aspects if deemed relevant. The order in which they appear is also flexible.

An OM has at least the following components:
- Executive Summary
- Definitions
- Revenue
- Cost
- Risk
- Environment
- Clients
- Services
- Activities 
- Group
- Staff
- Assets
- Suppliers
- Liabilities
- Equity 
- Goals 
- Objectives
- Management

### Executive Summary
The Executive Summary explains below sections in a single paragraph of 5-20 lines. This helps in three ways: 
1. It gives the reader a quick overview of the Venture, and thus prepares for what is to follow in more detail. 
2. It forces the writer of the OM to be able to explain in a few lines what a Venture does, and 
3. It can be used for documents that require such a short description of the Venture.

### Definitions
This contains definitions of words and acronyms relevant to the OM. This is optional. 

### Revenue
This explains the *sources* of Revenue. It should give the details of the last 2-3 years. Revenue is linked to the Services, see below, but this section should avoid going into detail of those. Revenue can be expressed in different KPIs: Full Year Revenue, YTD Revenue, last year's Revenue YTD, Revenue broken down by Service type etc. 

### Cost
This explains the *sources* of Cost. It should give the details of the last 2-3 years. Cost is linked to the Services, see below, but this section avoids going into detail of those. Costs can be expressed in different KPIs: Full Year Costs, YTD cost, last year's Cost, YTD, Cost broken down by Service type etc. 

### Risk
This explains the *sources* of Risk. Unlike Revenue and Risk, the details provided are likely to be more diverse, depending on the sources and types of Risk. Risk is linked to Resources (Assets, Staff, Suppliers) used within the Venture and the manner in which the Venture's Objectives are performed (details of the latter are in the section below). The data to provide can be expressed as losses incurred, insurances taken out to cover risk, etc. Depending on the Venture, it is here, or under Services that Risk related to Services should be discussed. If relevant, the manner in which Risk is mitigated can be discussed here as well. 

### Environment
This explains the environment in which the Venture operates. Various aspects can be considered, depending on the exposure of the Venture to the Environment and whether a Legal Entity or a Business is covered. Examples include Corporate Structure (Investors/Holding Company), Capital Structure, Competitors, Regulators, Tax, Corporate Governance, ..
NB: Internal constraints and Policies are part of the Key Deliverable "ByLaws" from  Management Function Planning and can be discussed either there or  there. Aspects like Investors and Creditors are less relevant for Activities but more for the Venture. Strictly speaking Corporate Structure is a Finance as a Business Function topic, but for simplicity it is captured under Environment.

### Clients
This explains whom the Venture provides Services for. Various aspects can be considered like Client Categories, geographic location, top 10 clients, the 20% of Clients contributing 80% of the Revenue, etc. 

### Services
This explains which Services the Venture provides to Clients. The manner in which they are described is specific to the type of Services. Because Services are intrinsically linked to Activities, one can choose to provide the description of Services within Activities, and this section can be omitted in that case.

### Activities
This describes the Activities that make up the Venture. For each Activity describe what it is they do, and how they contribute to the Services the Venture offers. 
It is possible an Activity is sub-divided in smaller Activities specialising in one or more specific Services, Clients and/or to reflect a geographic distribution of the Activity. 
If the Operating Model is for an Activity and not for a complete Venture. then this section should only focus on the sub-Activities of that Activity.

### Groups
This explains the Group and sub-Groups associated to the Activities and sub-Activities. 
Due to the naming convention of Activity = Group it is possible to merge this section into previous Section, if the focus is more on the Activity than on the Groups. 

### Staff
This provides details of the Staff involved in the Groups and sub-Groups. This may or may not be relevant. Typical details would be name, corporate title, job title, roles and responsibilities. 

### Assets
This explains the Assets involved in the delivery of the Services across the Activities. The total number could be large, and therefore a summary of key ones, or groupings of Assets may be preferred. 

### Suppliers
This explains which Suppliers provide Services to the Activities. The total number can be quite large, and therefore a focus on key ones, or groupings of them may be preferred. 

### Liabilities
This refers to any Liabilities, short and long term, the Venture uses to fund the performance of it's Goals.

### Equity
Equity explains the Equity the Venture uses to achieve its Goals. Often this is not relevant for an Activity within a Venture. If deemed relevant for an Activity, then details as to how the Equity allocated to the Activity can be mentioned here. 

### Goals 
This explains the Goals the Venture tries to achieve. Given that Goals are standardised, a focus on Sub-Goals (and thus the Roadmap) may be more relevant, particularly if the OM is for an Activity and not a Venture. Depending on the OM, Change Goals may or may not be relevant. 
 
### Objectives
This explains the Objectives the Venture performs across the different Activities to achieve the Goals. It differentiates between Routines and Projects. To avoid a detailed enumeration of such Objectives, they can be regrouped. This section is critical to understanding what the Activities do and more importantly, how they do it. Like for Change Goals, Projects can be omitted if not deemed relevant. 

### Management
This explains the manner in which the Venture is maintained and improved on an ongoing basis. It can be broken down in the four Management Functions i.e. Planning, Organising, Leading and Controlling.  
For Planning Goals and Objectives are explained above. Other key deliverables that may be discussed are: Mission, Vision, Purpose, SWOT, Bylaws. 
For Organising the above sections on Activities, Groups and Staff may be sufficient. Leading focuses on the manner in which the Venture is being directed, and may be less relevant to an Operating Model. 
Controlling may be important, particularly if quality control and risk mitigation are deemed critical to the Venture. 

### How To Use
The above details can be used in several ways. For starters they are used as preamble in the template note [MGT: 80.Tools-OM-template]. This note can be used as the input for the Operating Management notes, which should be stored as: [MGT: OM-aaa] in which aaa is the name of the Venture or Activity. The note [MGT: OM-ALL] can be used to reflect transversal Activities and thus also transversal Routines.   
The components mentioned above can be reflected in L1 or L2 sections, depending on the required granularity and detail. They can form, in the order stated, the basis of a written document or memo, or alternatively they are used in a presentation. Not all details need to be used and some can be merged into something more relevant for the Venture. Also, above is a suggested level of detail. It is possible to add other, more detailed aspects of the Profile e.g. Mission or Finance. It is also possible to combine aspects, for example Revenue and Services can be linked in a table showing which Services generated which Revenues, same for Costs and Risk, etc. It may also be relevant to compare Activities (or sub-Activities) to explain how the different Activities contribute to the Venture.  
Ultimately, the Operating Model needs to consider the context in which the Venture operates. For example, a manufacturing Venture may have a strong focus on the Suppliers providing raw material (supply chain) and similarly the distribution chain for the delivery of the end Products to Clients. On the other hand, for a Service based company like an Investment Bank, a supply chain is less relevant, but risk management of the financial products created or issued, is more critical.    
Therefore, for each Venture the focus will be on different aspects of the Profile Tree, and the manner in which they are described will be different in each case.
If the above is used for the Operating Model of an Activity within the Venture, then much can be kept as is, but the focus should of course be on what is relevant to the Activity. So certain aspects of the Environment may not impact a specific Activity, so it can be left out.  
Once the Operating Model has been completed as a one-off it should be maintained regularly.
________________________________________
## COM (Framework)
A Current Operating Model focuses on what the Operating Model is, and how that ties in to the Tactical Plan. It links *all* items of the Profile Tree and as such is actually *not limited* to Planning. A COM, a.k.a. Operational Plan is based on the Profile. 

The Operating Model is explained above. Below follow alternative implementations.

### COM 1
Useful for Legal Entity (LE) level Operating Model.

- Context  (similar to Exec Summary, can include history of LE)
- Activities incl Goals and Objectives performed in the LE
- Rules, Policies (a specific part of Environment) applicable to the LE
- Corporate Structure explaining Management structure, Financing structure) partially embedded in Management 
- Oversight a.k.a. Governance, Mostly Planning and Controlling part of Management.

### COM 2
________________________________________
## TOM (Framework)
The Target Operating Model or TOM is a *desired* version of the Current Operating Model. It is most often drawn up if sue to Projects the existing Routines are going to change such that the COM is not relevant anymore. A TOM is also actively pursued when there are new business initiatives, essentially creating new Routines. The same template as for COM can be used: [MGT: 80.Tools-OM-Template]
________________________________________
## CMM (Framework)
A Maturity Model is a framework of improvement of Processes to achieve an ultimate goal of the Process being self-improving. It is used  to develop and refine maturity of a Venture over time and its key tenet is Skill and Knowledge growth. There are various Models with different names, and they aim achieving similar results. The most used model is called the *Capability Maturity Model* or CMM which is from 1990, by Carenegie Mellon Uni and which is referred to mostly for Software Development, although it can be used elsewhere. Later the CMMI was developed as an improved version of the CMM. See also: <https://www.tutorialspoint.com/cmmi/index.htm>.
________________________________________
## BIA (Framework)
Business Impact Assessment is a method that looks at the key Activities and Routines within a Venture and assesses the impact of them not being able to be performed anymore due to (partial) lack of:
- Staff and/or
- Assets and/or
- Suppliers and/or

The BIA expresses itself in terms of Services not delivered as a result of the partial lack of the above.
________________________________________
## TRA (Framework)
A Threat and Risk Assessment formalises the type of Threats and the level of Risk such Threat poses to the Venture. The TRA can then be used combined with the BIA to provide a holistic overview of the various risk scenarios and the impact to the Venture. 
________________________________________
## Trends (Framework)
One way to obtain notably Market Intel is by subscribing to or following on the internet Trend related persons, institutions or companies (Trend Entities). As part of the default Routines, see [## Objective Definition] there should be one Routines reflecting a recurring spending of time in obtaining Market Intel through trend entities.
Note that if a Trend is deemed important it may lead to a dedicated Projects or may obtain dedicated attention in Goal = prd, Sub-Goal = Research & Development.  
  
  
*********************************************
# ORGANISING
Organising is the second Management Function and is concerned with defining the organisational structure required to execute the Plan. It aims at defining *how is it to be done*.
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Organising]. On L2 are the Tools:
- Activities
    - Activities Definition
    - MSS, see [## MSS]]
    - Resource Planning
    - Job Description Definition 
- Groups
    - Group Definition
    - Organisation Chart
    - MSS, see [## MSS]
- Roles & Responsibilities
    - Delegating Definition
    - Delegating Checklist
    - Job Description
    - RACI
________________________________________
## Activities Definition (Procedure)
Activities regroup a set of Objectives aiming at achieving, or contributing to, a specific Service. For each Activity define name and subsequent properties at L2 and L3 within [MGT: Organising # ACTIVITIES] as per [MGT: 99.Legend ## Activities] . 
  
The name of the Venture is determined by the owners of the Venture. It is essentially the top level of all Activities (and thus Groups) within a Venture. 
For any other Activity within the Venture, the Manager of the Venture effectively delegates the Management of the Activity to the head or Manager of said Activity. The result of this, is that for example details as discussed in the notes MGT: 99.Legend and MGT: 80.Tools are maintained by the Activity Manager and not the Venture Manager. Note that, as per delegation principles, the Manager of the Venture remains accountable for the performance of the Activity. See also [## Delegating Definition.
________________________________________
## Resource Planning
With the Tactical Plan, see [## Tactical Planning], the target Objectives are identified for 1 year (or more) including when they will be worked on. However, resources are not attributed to those Objectives. The Tactical Plan is most often designed around known Resources. Nevertheless, there are considerations for planning resources.

Resource planning, a.k.a. Budgeting is a two way exercise in which Resources (Staff, Assets, Suppliers) are compared with the target set out by Goals. 

Resources and Objectives are related: 
    Assets + Staff + Suppliers = Routines + Projects

Changes in Resources have an impact that needs to be managed through Business Functions: Finance, Human Resources and Procurement.
________________________________________
## Group Definition (Framework)
Groups regroup Staff involved in the performance of Processes that are part of an Activity. Often the Group is headed by a Manager, most often of Lower Level Management i.e. operationally very involved. 
________________________________________
## Organisation Chart (Framework)
Although the Group Definition is defined by the Activity Definition, the relation between Activities, is often capture in an Organisation Chart, and not an Activity Chart! In other words, the manner in which Activities relate to each other is reflected in how Groups related to each other. 
________________________________________
## Delegating Definition (Framework)
The definition of Delegating is as per [MGT: 99.Legend ### Roles & Responsibilities]. This section sets out further details of Delegating.

### Delegating Conditions
Legally speaking delegation is possible only if:
- The delegator actually has the responsibility and authority they wish to delegate
- Delegation is permitted as part of the authority

### Delegating Delegation
Delegation of delegation a.k.a. sub-delegation occurs when a delegatee delegates a Process that was delegated to him/her to another delegatee. This is only possible if the original delegator gave the authority to sub-delegate. 

### Delegating Antonym
No delegation means authority and responsibility is *retained*. If a Process was previously delegated but the delegator wants to do the Process him/herself then that is referred to as *revocation*.

### Accountability vs Authority vs Responsibility 
Responsibility: duty and ability to perform a Process such that it yields the expected Result.
Authority: right and ability to exert power, make decisions (where, when, why, what, who, how) and give orders such as to fulfill said responsibility. 
Accountability: duty and ability to report on the Result and duty to accept consequences of the Results if they are not, or wrongly, achieved.

The key difference between Accountability and Responsibility is that the Responsibility is related to *performing* a Process such that it yields a Result and Accountability is related to *reporting* on that Result. Or in other words Accountability is the *ownership* after a Process has been completed. This ownership includes being able to explain the Result to others (shareholders, managers, regulators, tax office etc). Accountability cannot be delegated, but follows from the fact that Responsibility has been delegated.

### Accountability without Authority
It is possible, although not at all desirable, that one is made responsible, and thus accountable, without the appropriate authority, which is referred to as *Accountability without Authority*. This happens, for example in matrix organisations where there are two or more reporting lines across functional and entity level reporting lines. It can also occur in Projects, where the Project Manager may not have authority over resources, but the Sponsor has, see below. 

### Oversight
The delegator needs to assure the delegatee completes the delegated Process, because of said accountability of the delegator. This is called *oversight*. Oversight is an integral part of Delegation. Oversight is also the Goal focusing on assuring the Production operates as expected, see [MGT: 99.Legend ## Goals].

### Sponsorship
A Sponsor is sometimes used in Project Management. It is a person who is not directly involved in the Project, but who has the right level of Authority w/r to one or more of the three items of the Project Management Triangle i.e. Scope, Cost and/or Time, which often simply means he has authority over part or whole of the resources. This in turn allows the Sponsor to redirect resources to a Project, whereas the Sponsor is him/herself not responsible for the successful delivery of the Project.
  
### Escalation
Escalation is the process of moving up the delegation tree to a level of Authority able to make a decision, commit resources or otherwise enforce obedience, because the person escalating does not have the Authority to do that him/herself. 
  
### Delegating Workflow
In order to delegate the delegator needs to 
1. Free time to Delegate i.e., determine:
    - What to delegate i.e., which Process 
    - What Authority goes with that Process
    - Whom to delegate to i.e. finding the Delegatee
    - How to delegate i.e. identifying optimal handover 
2. Free time to perform Oversight i.e. determine:
    - How to perform Controls
    - When and how often to perform Controls 
    - Performing the Control
    - Monitor action plans that result from Controls

The above is detailed in [## Delegation Checklist].

### Delegating Principles
From a manager perspective, delegating is a crucial tool to be able to focus on Management rather than Operations. Line Managers and Team Leaders in particular have a dual role that also includes operational work.

The following principles aid in maximising delegating:
1. The basic principle is that Operational work should be delegated
2. Quick wins (taking less than 5 minutes) can be done without delegating
3. Anything above Quick wins, duration wise, should be delegated. 
4. If the Job Description includes operational work, then that needs to be clearly defined and delineated, the rest: principle 1-3.

### Pros and Cons
There are pros and cons of Delegation, but, if done well, pros outweigh cons, see [### Delegation Conundrum].

Delegator:
- Pro: Time gets freed up. 
- Con: Effort has to be done to 1) delegate (takes time) and 2) to assure Oversight.

Delegatee:
- Con: More work gets added: 1) learning what gets delegated, 2) doing the Process that gets delegated.
- Pro: Creates opportunity to increase knowledge, Skills and experience.

Venture:
- Pro: Builds Leaders / Managers of tomorrow

### Delegating Conundrum
There are several conundrums in Delegation. 
  
1. No time to delegate
This conundrum refers to investing time to delegate a Process, i.e. In order to delegate, effort has to be done, see [### Delegation Workflow]. An often heard reason to not delegate is because of that. 
  
2. No time to perform Oversight 
Similar as 1., Oversight takes time which is scarce. 
  
3. Accountability suggest knowing all
Being accountable does not mean knowing the details of Processes that yield the Results for which the delegator is accountable. However, the delegator does need to understand the Result and should have the ability to understand the Process if necessary.
  
It is true that the effort to Delegate + performing Oversight should be less than the actual time to perform the delegated Process, at least from a delegator perspective. However, the advantages to the delegatee are still relevant, and in the long run the time saved by a delegator might increase with more delegation being possible for other tasks, simply because of the overall increased skills.
   
### Delegating and Activities
Within the Venture there are most often many Activities. A Manager  of a Venture does not manage the day to day of each Activity within the Venture and for all intents and purposes delegates day to day Management i..e., the Objectives to the Manager of the Activity. See also [## Activities Definition] and [## Objective Definition].
  
### Delegating and MSS
The MSS, see [## MSS] has an embedded logic to capture what is, and what is not delegated.
________________________________________
## Delegating Checklist (Framework)
Once the decision to delegate has been taken, the Process of Delegation kicks in. The following are guidelines, see: [data_public_study_HBR_Delegation_Checklist_2019.pdf]

1. Process: clarify which Process can be delegated, for how long and the level of required authority.
2. Delegatee: choose the delegatee. This should *not* only be based on who *can* perform the Process, but also who *needs* the experience, who has shown *interest*, who would see it as a *reward*, ...
3. Result: what Result is expected, which includes *why* we do it, and how to *measure* a successful Result. Make sure the delegatee knows the expected Result and how it will be measured.
4. Enable: make environment available for delegatee (training, time, space), assure other Staff are well aware of the Delegation and Authority going with it. 
5. Feedback: provide periodic feedback throughout the delegation period.
6. Innovate: stimulate delegatee to do things differently. This is not strictly part of Delegation, but of general Process improvement.
7. Motivate: compliment, coach, step in, step back, adjust expectations, make available, etc.
8. Tolerate: permit mistakes and the taking of Risk and see them as learning opportunities i/o of proof it should not have been delegated!
9. Oversight: assure above steps are reviewed continuously as part of Oversight in which the Result is measured, Process adjusted, delegatee receives feedback etc.
________________________________________
## Job Description Definition (Framework)
A Job Description or JD aims at achieving the following:
- Defining Roles & Responsibilities (R&R) of a position within a Group
- Defining Required Skills, Knowledge and Experience to fulfill those R&R
- Explaining how the JD contributes to the Activity

A Job Description has the following components:
- Executive Summary 
- Definitions
- Venture Description
- Activity Description
- Roles
- Responsibilities
- Skills, Knowledge & Experience 

These aspects are explained below.  

### Executive Summary
The Executive Summary explains below sections in 5-30 lines. This helps in three ways: 
1. It gives the reader a quick overview of the Job Description, and thus prepares the reader for what is to follow in more detail; 
2. It forces the writer to explain in a few lines what it is the JD is about, and;
3. It can be used for documents that require a short description of the JD.

The Executive Summary should contain:
1. One-liner setting out the overarching target of the Role. It can be expressed as a Mission, see [MGT: 99.Legend ### Mission].
2. Explanation of Run Goals including Routines with a reasonable level of detail. 
2. Description of the Change Goals and, specifically, how the Role contributes to them.

The above should be done in such a manner that even if the Executive Summary is read in isolation it it still clear what the JD is about. The Executive Summary of a JD is often what is referred to within exchanges between HR and a Manager when hiring new Staff. 

### Definitions
This contains definitions of words that are relevant to this note. This section is optional, but a recommended part of the definition includes an explanation of the concept of Profile.

### Venture Description
The Venture Description explains the high-level context of the Venture the Activity is part of. This includes very standard language and can come from the Venture's marketing material. There is no need to go through the Profile Tree items as they will be discussed in more detail on the Activity level.
  
Optional details for the Venture Description are:
- Quantitative: Revenue, Staff nrs.
- Qualitative: key achievements, impact on the market segment it operates in, etc. 
  
The Venture Description leads into the Activity relevant to the JD.
 
### Activity Description
The Activity Description sets out the detailed context in which the JD is performed. It is possible to revert to the Activity's Operating Model (detailed in a separate document), specifically the Executive Summary, [MGT: 80.Tools-OM-Activity].

The Activity Description should cover the following items from the Profile and the RPT, each being an L3 section, e.g., [### Environment], [### Clients], etc.:
- Environment: in which the Activity operates. Note that the Activity does not necessarily have exposure to the Environment of the entire Venture, which is why Environment is discussed specifically on Activity level.  
- Clients: represents the *Who* the Activity provides the Services. Like for the Environment, not all Clients of the Activity are the Clients of the Venture. It might be the Activity performs Services to other Activities (making those Clients) within the Entity i.e. a supporting Activity (see below) instead of Clients of the Venture. 
- Services: represents the *What* the Activity delivers and also how they contribute to the Venture or to other Activities within the Venture if it is a supporting Activity (in which case details of those Activities should be provided).
- Activity: notably the mention of sub-Activities, if they exist. It is here also that other Activities can be mentioned if the Activity is providing Services to other Activities. If there are no sub-Activities nor other Activities to describe, then this section is very slim.
- Group: represents *Who* performs the Activity and should notably reflect the organisation of Staff within the Group.
- Staff: the Staff making up the Group, optional and should be excluded for external JDs
- Assets: part of the *How*. The setup used within the Activity. Without going into details, the key ones, or the key types, can be enumerated. 
- Suppliers: part of the *How*. Providers to the Activity, both Internal and External. 
- Goals: and/or Sub-Goals if relevant
- Objectives: of the Activity, ultimately yielding the Services. It is often not possible to describe all Routines and Projects, in which case a thematic approach can be used. However, it is this part that is critical, as is Objectives reflect the *How* of an Activity and is this also the one that is likely to be described in most detail.

Optional details for the Activity Description:
- Management details: Planning, Organising, Leading and Controlling
- Quantitative: Revenue (as % of Venture Revenues), Costs, Risks, Staff nrs, ...
- Qualitative: key achievements, relevance to the Venture, ...

### Roles
Although the word Roles suggest multiple positions within the Group, it is most often a single position and associated Role. A Role is often a formal name and suggestive of the Authority that comes with the position. It has the following properties:
- Name of the Role
- Location(s) where the Role will be fulfilled
- Seniority (Analyst, Associate, VP, Director, MD, Senior VP, etc.)
- Authority (may also be detailed under Responsibilities)
- Reporting lines: whom the Role reports into and who reports into the Role (none, some, entire Group)

Additional details can include specific constraints like working hours, travel requirements etc.

### Responsibilities
Responsibilities are effectively the list of Objectives to be performed, or to be contributed to, within the Activity. These Objectives are the ones discussed in Activity Description above. Either the Role does all of them, or only a sub-set. This section should just refer to the applicable Objectives. Note that it is possible to detail Authority here instead of under Roles.
 
### Skills, Knowledge & Experience 
Skills refers to the know-how in order to be able to achieve the Responsibilities. Knowledge refers to what is required in understanding the topics involved in the Responsibility. 
Skills and Knowledge can often be 'proven' from similar Roles and Responsibilities which is referred to as Experience. Experience gives more weight to the relevance of Skills and Knowledge.
  
Skills use the key-words "How to ...". Knowledge uses the key-words "Understanding of ..." or "Knowledge of ... ". Experience is expressed as "Similar roles for X years in Y type of company".

### How To Use
The above information can be used in various manners, but in most cases it will form the basis of a written document. This depends mostly on the type of role and how that role positions itself within the Activity, and how the Activity positions itself within the Venture.

### Example for a COO role
Below example is an Executive Summary of a JD where each new level builds on previous levels. 

Venture Description
The Venture is a leading producer of ... etc. There are two main functions in the organisation: the business functions, which produce directly or directly ... and the support functions which assure continuity of the production line including the supply of raw material and the distribution of end products .... 

Roles and Responsibilities 
The COO is an important role within the Division. The COO oversees the day-to-day of the Division and together with the CEO drives the strategy of the Division. The COO Reports into the CEO. Managers of both production and support functions report in to the COO. 

Knowledge and Skills 
The role of a COO is demanding in that the scope it covers is broad  and requires specific Knowledge and Skills as follows:

1. Business knowledge relative to the Venture's business model and the sector(s) it operates in including the Clients it produces for and Competitors it competes against.
2. Knowledge of Laws, Rules & Regulations (external constraints on how 1 can be performed)
3. Knowledge of Internal Policies (internal constraints on how 1 is performed, often driven by 2)
4. Knowledge of the Venture specific Processes (the Venture's implementation of 1 under the constraints of 2-3)
5. Knowledge of the organisation of the Venture's Staff (responsible for the execution of the Processes of 4).
6. Knowledge of Assets (the implementation and use of Assets in the performance of 4)
7. Knowledge of the Suppliers (providing Services and/or Assets in the performance of 4)
8. Skills relative to Run i.e. Routines in the scope of the Role (capacity to perform Routines specific to the Role such as to oversee and maintain 1-7)
9. Project Management skills (general skills to initiate, and manage Projects to improve on 1-7).
10. Management skills, to drive 1-9, which include, but are not limited to:
- Communication: ability to convey and share ideas effectively to a wide range of stakeholders
- Flexibility: ability to accept new challenges calmly and without restraint
- Leadership: ability to help oversee Activities, guide initiatives and steer Staff toward the achievement of Goals through Leading
- Motivation: ability to keep going even in the face of setbacks
- Multitasking: ability to manage different Objectives efficiently by prioritising them 
- Problem Solving: ability to analyse a problem efficiently to create a solution, including breaking up larger problems in smaller ones
- Teamwork: ability to cooperate with others and build relationships
- Time Management: ability to plan different tasks and track them such that they complete at the expected time 
- Self-learner: ability to teach oneself new topics by finding and using relevant sources of information adequate for that topic
- Self-critical: ability to question oneself to improve the quality of one's output and to increase one's understanding of relevant topics 
- Self-starter: ability to see tasks requiring to be done and start working on them without being asked by someone else to do so
- Analytical: ability to collect, process and transform Data (records of fact) into  Information (interpretation of facts) relevant to a topic 
- Strategical: ability to identify potential and actual Opportunities that grow Revenue and/or reduce Cost and/or reduce Risk under the constraints of potential and actual Threats given the actual Strengths and Weaknesses of the Venture.
________________________________________
## RACI (framework)
Responsible, Accountable, Consulted, Informed (RACI) is a manner in which roles and responsibilities are defined for specific tasks. It can be used for Operations in general, and is often used for Project Management, see [## Project Management].   
    
The definition of RACI often implies an oversight committee that oversees progress of whatever the RACI have been defined for.
  
### RACI Overview
The underlying of RACI is one or more Tasks, or Objectives. The principles associated to RACI are Delegating, see [## Delegating]. 
  
The four Roles in RACI are defined as follows:
- R (Responsible): person who performs a Task.
- A (Accountable): person answerable for completion of the Task i.e., the person reporting on completion to someone e.g., a Committee.
- C (Consulted): person whose subject matter expertise may be sought (two way communication)
- I (Informed): person who may be informed of progress and/or completion (one way communication).

The two most important two roles are A and R. Sometimes they are the same, but not always.

### RACI Rules
A hard rule is that there can be only one 'A' for a given Task. If there are more than A, then that is indicative of a need to split the Task into smaller Tasks. 
It is possible to have more than one R for a given Task. 
  
### RACI Weaknesses
RACI do not include Authority. Often Responsibility is assigned but this Responsibility does not carry any , or sufficient Authority. In these cases the Responsible person will need to Escalate e.g., to the committee.
Another weakness is that Consulted and Informed are not well defined: do those people need to be Consulted and Informed or *can* they be Consulted or Informed? To avoid this optionality or not, the actual expectations should be defined as part of the RACI definition.


*********************************************
# LEADING
Leading involves processes to drive those *who do it*. This third Management Function assures Staff perform tasks as per Planning and within the Organisation using Leadership principles.
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Leading]. On L2 are the Tools:
- Safe Space
    - Communication
    - Listening
    - PSS Toolkit 
    - Story
    - Feedback
    - Meeting
    - One-on-One
    - Team Meeting
    - Whiteboard Session
    - Braintrust
    - Hidden Relationships
    - Superiors
- Direction
    - @@@
- Collaboration
    - Communication
    - Team
    - Brainstorming
    - Mentoring
- Motivation
    - Communication
    - Motivating
- Inspiration
    - @@@
- Leaders
    - Communication
    - Presenting
    - Due Diligence
    - Mentoring
    - Coaching 
________________________________________
## Communication (Framework)
In order to Lead, some form of interaction is necessary, and the main method of this interaction is Communication. As such across all Key Deliverables in Leading Communication is the main Tool. 

### Communication Properties
One-way vs two way
@@@

### Verbal Communication
@@@

### Non-Verbal Communication
@@@

### Written Communication
@@@

### Oral Communication
@@@

### Formal Communication
@@@

### Informal Communication
@@@
_________________________________________
## Listening
Listening is part of communication. Good listening means understanding the purpose of the conversation. A conversational goal is composed of needs of the listener the needs of the speaker and the needs of the Venture. Not all aspects are present in each conversation. 

There are four distinctive listening styles and Managers need to be able to differentiate between them:  
- Analytical Listening: aims to analyse a problem from a neutral starting point.
- Relational Listening: aims to build a connection and understand the emotions underlying a message.
- Critical Listener: aims to judge both content of the conversation and reliability of the speaker.
- Task-focused Listener: shares a conversation towards an efficient transfer of important information.

Five paths to improving listening:
1. Establish the conversational goal: are you asking for a conversation, has the speaker explicitly said they want to have a word, or that they have a concern or idea? Is there a company directive or policy that comes into play? Does the speaker know what they want to get out of the conversation.
  
2. Recognise how you listen normally: pay attention to what you normally do versus and how that would intervene or reinforce the conversational goal.
  
3. Be mindful of whom the focus of attention: in simple words do not interject too casually with personal stories even if well intended. This is particularly important if the goal is to alleviate concerns of the speaker.
  
4. Adapt listening style to achieve the conversational goal.
  
5. Ask yourself if the conversational goal was addressed? This is even more relevant if the speaker does not know what to get out of the conversation.
  
Sources: 
- Hardvard Business Review, Whats-Your-Listening-Style (2015)
- Harvard Business Review, Mindful Listening (2022)
_________________________________________
## PSS Toolkit
The following is from "The Fearless Organisation" by Amy Admonson. There are three steps for Managers to work on to continuouslycreate a Psychological Safe Space (PSS). When *Manager* is used it can be any Leader not necessarily a hierarchical Manager, although they often are in the best position.

1. Setting the Stage
The purpose of this step is to create *shared expected Results and meaning*. It reinforces the understanding that although it may considered a *Risk* to speak up about *failures*, including ones own, but that Speaking up is effectively aiding the Venture to *learn* and thus improve.
Note: the book has a strong focus on actual failures. It is assumed here that failures include actual failures but also weaknesses that could lead to future failure. 
  
Frame the Work
Framing work consist of setting expectation w/r to failure, uncertainty and interdependence to clarify the *need* to speaking up. Staff needs to understand that *learning from failure* is key to continuous improvements even if speaking up feels like a Risk to themselves. Failure requires definition:
- *Preventable Failure* (Processes deviation): deviations from known Processes producing unwanted Results. Caused by Behavior, Skill or Attention Deficiencies. 
- *Complex Failure* (System Breakdown): unique and novel combinations of events and actions that yield unwanted Results. Caused by complexity, variability, and novel factors imposed on familiar Processes and Environment. 
- *Intelligent Failure* (Unsuccessful trial): Novel forays into new Services leading to unwanted Results. Caused by uncertainty, experimentation and explicit Risk taking.
  
Frame the Roles
Review the role of Managers: they *do not* know the answers to all questions, but can set direction, ask for input and clarifications and can thus create the conditions for continuous improvement with the contribution of Staff. 
Review the role of the Staff:  they *do* have insight,  answers, concerns and relevant questions and by voicing those, improvements are possible. 
  
Emphasise Purpose
Make sure everyone understands why speaking up is important. Rephrase and emphasise purpose w/r to the mission of the Venture. 
  
2. Inviting Participation 
This step assures Staff effectively contribute by speaking up about failures and thus participate in growth, by providing *input*. It has the following characteristics:
   
Demonstrate Situational Humility
Managers need to constantly display the fact they do not know all and that they can, and do, rely, on Staff on the ground to help make changes. This should not be confused with lack of confidence. In effect, Managers should be able to be confident in their lack of knowledge, and more so, they should be inclusive of all Staff when approaching for answers to questions the Manager or Staff may have.
  
Practice Inquiry
Learn the art of *Inquiry*: *purposeful probing to learn more about issues, situations, or person(s)*. This requires a Skill to cultivate genuine interest in Staff's responses. This is harder than it sounds due to a cognitive bias called *naive realism* (stronger with high achievers!) that gives the idea that one *is* seeing a reality, rather than a *subjective view* of the actual reality.  Inquiry requires asking *powerful questions* which have the following properties:
- You don't know the answer
- Ask questions that do not limit answer to Yes/No
- Phrase the question such that Staff share their thoughts in a focused way.

Powerful questions have the following attributes:
- Generate curiosity in the listener
- Stimulates reflective conversation
- Is thought-provoking
- Surfaces underlying assumptions
- Invites creativity and new possibilities
- Generates energy and forward movement
- Channels attention and focuses inquiry
-  Stays with participants
- Touches a deep meaning
- Evokes more questions
  
Examples: "What leads you to think so?", "What might we be missing?"
  
Setup Structures & Processes
A last manner to increase participation is to create structures facilitating input from Staff. Example: focus groups, special blogs, etc. 
  
3. Responding Productively
The last step of setting up PSS is by responding to the input provided in above stage in a manner that does not stint the PSS Process and effectively make it a self-maintained Process.
  
Express Appreciation
As a Manager, be receptive of, and even praise, the fact that someone has spoken up. The more uncertain the environment (incl at the start of setting up a PSS), the more the Manager should be vocal about it. Example: "Thanks for letting us know".
  
Destigmatise Failure
The fear to fail is, especially in the beginning of implementing a PSS, very large. Therefore, reinforce the first step related to the Framing of Failure:
- Concept of Failure: a natural by-product of experimentation and learning
- Beliefs about effective performance: produce, learn from and share lessons learnt from Intelligent Failures.
- Goal: promote fast and broad learning
- Impact of above: open discussion, fast learning, innovation
  
Sanction Clear Violations
Implementing a safe space and reframing Failure does not mean all failure is acceptable. If a Venture has specific policies that dictate certain behaviour as unacceptable e.g. disclosing proprietary information then no matter what the purpose of speaking up is, sanctions can be imposed (including dismissal). The vague the policies, the less such sanctions are considered reasonable. 
________________________________________
## Story (Framework)
Having a Story facilitates interaction with Staff, Suppliers and Clients. Storytelling is defined as the strategic sequencing of facts and emotions. The most common misstep in crafting a story is to mistake recounting events as synonymous with telling a story. It is not! To be strategic means resisting the default mode of following chronology: first this, then that, and then bla-bla-bla. The audience’s attention drifts away before they know why they should care. Details here:
<https://www.forbes.com/sites/estherchoy/2020/01/26/what-is-leadership-storytelling/?sh=1d7eba947b17>
________________________________________
## Feedback (Framework)
The purpose of feedback is not to praise/criticise the past, it is to *encourage* future effective behaviour. Negative feedback assumes Staff will do better in the future. 

### Feedback Given
Four steps to provide feedback:
1. Can I give feedback/ Can I make an observation? / Can I focus on what just was said?

Regardless of the type of feedback (positive or negative) the *intonation* of above steps is the same. Not negative, not positive but with a positive afterthought i.e. it will be better in the future. 

The reason to *ask* nr 1. is to make sure they are ready to listen! This is important because the purpose of feedback is to reinforce future behaviour. What if they say 'no'? Then move it to later.

@@@
________________________________________
## Meeting (Framework)
One of the most suitable forms of Communication is through a Meeting.
Like communication there are two key types of Meetings: formal and informal.

A Meeting is either owned by the Manager or not. 

A meeting is either recurring or not. Non-recurring Meetings can still be deemed 'recurring' in below procedure, except that there are no recurring dates available. 

The purpose of a Meeting is to either regularly exchange updates between participants e.g. an item in MGT: 04.Controlling # JOURNAL), and/or it is used as a form of Control or Oversight e.g. an item in MGT:  04.Controlling # SUPERVISION and/or it is used as a form of Reporting to senior management or more generally to stakeholders e.g., an Item in [MGT: 04.Controlling # REPORT].

### Meeting Procedures
For each Recurring Meeting set up a note. The note drives how the meeting is done.

### Meeting Note
Create notes with the following conventions:
- Note name: MGT: Attend-xxx-yyy
    with xxx = Activity/Supplier and yyy =  Staff
- Note content: see below.

The following is the default content of a Meeting Note (items refer to L1, L2 and L3 sections):
- L1: Introduction: overal purpose of meeting and audience (Activity, Supplier and Staff or type of Staff within). 
- L1: Todo: optional, items to be done 
- L1: List of Meetings: with L2 sections as follows:
    - dd Mmm yyyy, with following L3 sections
        - Agenda
        - Present (omit if 1:1 meeting)
        - Apologies (omit if 1:1 meeting)
        - Minutes
        - Details (details, can be omitted)
        - Actions

### Meeting Preparation
Ahead of a Meeting use L3 section = 'Agenda' of the upcoming Meeting to mention a topic to discuss. This is done on an ongoing basis. Use Task Notation to maintain these, see [## Task Notation] using '.' i.e. Not Started.

### Meeting Process
During the meeting take notes in the section 'Minutes'. For each item, use '-', dash or '+' 'plus, for a topic brought forward that was not on the agenda. For topics from section 'Agenda' that were discussed, move them from that section to section 'Minutes' and change the '.' to 'x'. 

### Meeting Minutes
Use L3 section = 'Minutes' to prepare Meeting Minutes to attendees, if relevant or required.
The Actions resulting from the Meeting can be added to the ToDo section for that meeting. 

Use L3 section 'Present' to populate To: in the mail with the minutes and L3 section = 'Apologies' for Cc:  

Meetings can also be processed in BuJo MSS, see [### BuJo MSS Process - Meetings].
________________________________________
## One-on-One (Framework)
One-on-One meetings are meant to give Staff the opportunity to communicate concerns to the Manager and vice-versa. Concerns can be interpreted broadly, but the focus should be the non-operational part of a Staff's responsibilities. This can include, but is not limited to, team-interaction, issues in handling of operational topics etc. A key part of a One-on-One is to provide feedback to and collect feedback from Staff, see [## Feedback].

### One-on-One Agenda
Review this <https://manager-tools.com>
@@@ and then update. Put in [## Staff Meeting] if necessary.
________________________________________
## Team- Meeting
@@@
________________________________________
## Whiteboard Session (Framework)
A Whiteboard session a.k.a. WBS is a form of presenting in a more informal manner. The  idea is that someone knowledgeable about some topic presents it to a small audience e.g. a Group and that, *this is important*, without any specific preparation i.e., no presentation material. To the presenter this means the time spent is limited to the time of the WBS. For the audience, it means they can focus on things they are more interested in than what a presentation would somewhat force them to pay attention to. 

Managers can use WBS to achieve three things:  
- Share knowledge within or across Groups
- Make knowledge sharing a standard feature of the Operating Model of a Group
- Show to the Group that the Manager him/herself is not knowledgeable

Particularly the last part is powerful: often Staff dare not ask questions at risk of being seen incompetent. If the Manager asks any question, both 'smart' and 'dumb' Staff in the Group wil be more likely to also ask questions, which has a knock-on effect that everyone in the Group becomes more knowledgeable.

If done well, Staff within a Group will look forward to the WBS, and as such they constitute a form of team building at the same time.

 ## Hints at running WBS:
- Always ask someone very knowledgeable including with Suppliers to present a topic that person would be *very* comfortable presenting out of the blue. 
- Do them on Friday afternoon, near the end of the day: this pulls people out of the grind and because it is Friday end of the day, there should be no need to go back 
- As a Manager ask questions and positively reinforce questions asked by others in the Group.
________________________________________
## Braintrust
Braintrusts are groups of people with a shared agenda who offer candid feedback to their peers. See also the Fearless Organisation.
@@@
________________________________________
## Hidden Relationships (Framework)
This concept explains relations between Staff within a Group, across Groups and between Groups, and which are not part of the official Relationships, see above. Identifying and understanding Hidden Relationships is important in understanding how the Venture operates outside the official Organisation and is a key ingredient in the manner in which best to lead Staff. More importantly, hidden relationships can impede on, or facilitate, the creation of a Safe Space.
________________________________________
## Motivating (Framework)
Motivating is the framework by which Managers encourage or stimulate employees to achieve the Goals set out for the Venture. Motivation ties in to:
- Needs: Maslow's hierachy of needs, EG theory
- Satisfaction: Herzberg's two-factor theory.  
  
Job characteristics that contribute to motivation:
- Skill variety
- Task identity
- Task significance via recognition programs
- Autonomy
- Task feedback
  
Known motivators in business context:
- Money although short term
- Praise
- Empowerment
- Recognition
- Respect
- Challenging work
________________________________________
## Brainstorming (Framework)
Brainstorming is used to find a viable solution to a problem. It does not work for complex, multifaceted problems. There are two key principles: 
-Defer judgment i.e., do not  conclude a good solution has been found when one idea sounds really good
-Go for quantity, get as many ideas as possible.

The Process (stick to it!):
1. Get a group of Staff, preferably from different disciplines, limit size to around 10-12 
2. Define the problem clearly
3. Ask Staff to come up with as many ideas as possible, each expressed in a few words. 
4. All ideas are welcome, preferably wild ideas
5. Withhold criticism, see point 4.
6. Combine (group similar ideas together) and improve ideas.

Brainstorming is vulnerable to *motivations to conform* which means people may risk not giving their best afraid to not confirm. If that is a concern, the above steps may be improved by doing a *silent brainstorming* where Staff write the ideas on pieces of paper in step 3 and hand them to a facilitator.
________________________________________
## Mentoring (Framework)
Mentoring is a Process in which a Mentor increases a Mentee's *performance* by *teaching* the Mentee based on the Mentor's own skills, knowledge and network. The aim is to develop career/life. Mentoring is often long-term 1-2 years. See also [## Coaching vs Mentoring].
________________________________________
## Coaching (Framework)
Coaching is a Process that consists of a Coach unlocking a Coachee's *potential* by helping the Coachee to *learn* rather than to teach them (which is done in Mentoring). This *helping to learn* is achieved  through asking questions including on Topics not relevant for day to day work. Coaching requires expertise in coaching and not in the subjects at hand i.e., the Processes. Coaching is about seeing Staff in terms of their future potential not of their past performance. The aim is to develop raw talent with new skills. It is short term from weeks to months. See also [## Coaching vs Mentoring].
________________________________________
## Coaching vs Mentoring (Framework)
The difference between coaching and mentoring is sometimes small. There are also companies that switch the definition around or that morph them into one Process to achieve a hybrid result.

The difference maintained here is that Mentoring is a long term Process where the Mentee taps into the skills of the Mentor to develop more broadly (and less performance based on the current role of the Staff). Coaching is a shorter term process in which the Coach helps Coachee to improve specific topics.

Below two links explaining the various aspects involved in Coaching and Mentoring:
<https://www.skillpacks.com/coaching-vs-mentoring>
<https://www.kent.edu/yourtrainingpartner/know-difference-between-coaching-and-mentoring>
________________________________________
## Presenting (Framework)
@@@


*********************************************
# CONTROLLING
Controlling involves Processes to establish *how well it was done*.
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Controlling]. On L2 are the Tools:
- Journal
    - Journalling
    - BuJo
    - BuJo MSS
- Supervision  
    - MTrack
    - Sup7 Tables
    - Holistic Data Approach
    - Progress Tracking
    - Committee
    - BOD
    - MBO 
    - BSC
    - OKR
    - Process Review
    - Staff Reports
    - Staff Meeting
    - Management Meeting
    - Check Standards
    - Control Conundrum
    - Self-Contained Mail
- Reports
    - Reporting Definition
    - Reporting Standards
    - Reporting via MSS
    - Exec Summary
    - Briefing Notes
    - Dashboard
- Monitoring
________________________________________
## Journaling (Framework)
Journaling, logging or more generally writing entries in a Journal is a good way to keep track of specific topics, concerns, etc. Journal entries feed into almost all aspects of Management e.g.:
- SWOT, see [## SWOT]
- Report, see [## Reporting]
- Meetings, see [## Meetings]
- Management Cycle, see [## MC]
- etc

What goes into Journaling is Manager specific. It also depends on Reporting requirements, see [MGT: 99.Legend ## Reports]: the type of information that goes into a Journal on depends very much on the type of reports that need to be written. Generally speaking, anything can go into a Journal: descriptions of what has happened, thoughts, ideas, things to do, routines, projects, etc. 

Note that basic Journaling is essentially just structured notetaking. This can be done on paper or preferably digitally using Note apps, see [## Notes]. The result of Journaling is a Journal a.k.a. Logbook. In French this is called a "Livre de bord" and in Dutch it is called a "Logboek", etc.

Journaling with a *focus on Planning* can be done through Bullet Journaling, see below. For large Ventures or more generally when many Journallng entries are expected, the use of specific software designed to aid in Journaling is recommended, see [## BuJo MSS].
________________________________________
## BuJo (Framework)
Journaling is the notion of writing down text. A framework called *Bullet Journaling* or *Bujo* (lower case 'j' ) is a specific implementation of it, originally designed for a paper notebook. Bujo is built around *three* aspects: 

1. Taking notes of meetings, experiences, ideas, results of checks, etc.;  *and* 
2. Planning work: Projects/Routines/Tasks, generally referred to as simply 'Tasks' in Bujo; *and* 
3. Controlling the work done in 2.

As such Bujo is an excellent multi-dimensional framework for a Manager allowing both Planning and Controlling!

Modern day Bujo can be done *digitally* which has several advantages over the notebook implementation. The framework discussed here, called *BuJo* (upper case 'J') is used within the Management Framework and is *adapted* from the original Bujo. BuJo forms the basis for *BuJo MSS*, see section below.

### BuJo Basics
The basic requirement for BuJo is a Note Taking app like MS OneNote or Standard Notes.

### BuJo Concepts
There are several concepts involved in BuJo which are derived from standard Bujo.

Data 
Data in BuJo can be of any type: ideas, experiences, meeting content, observations etc. It can and will also include Tasks, which is BuJo lingo for the broader Management Framework concepts related to doing things: Routines, Projects and Tasks. Data in BuJo is recorded either using verbose sentences or using *Rapid Logging*, see below. Entries can occur in different places: Index, Logs, Collections (see below).

Index
An Index is at the very start of BuJo and shows where Logs and Collections are. 

Rapid Logging
Rapid Logging is a shorthand notation where the first character indicates what the rest of the entry is about. This is achieved using Objective Notation, see [## Objective Notation]. Note that using Rapid Logging expects short entries as opposed to long sentences. 

Logs
A Log is what it says: a tracker of experiences, meetings, observations, ideas, tasks, items to be reported. Logs can be created within a dedicated Note or using a section within a Note. Standard Bujo method recognises three default Logs, with more being possible:
- Daily log: things to do today, meetings, reminders, etc. 
- Monthly log: things to do this month
- Future log: things to do possibly, one day

Collections
Collections are Journal Entries belonging to the same category or theme and grouped together. 

Migration 
Migration is the process of moving entries from one location to another i.e., from a Log to another Log or to a Collection. In classic Bujo this is done by recopying the data and changing the original entry status to '<' or '>'. In BuJo it is achieved through cut-and-paste of data. There is no real reason to show on an entry that it has been moved and thus record it twice. Just move it!

### BuJo Setup
The setup for BuJo within the MF can be done in any notes app using the following conventions:

Index
The Index is composed of the list(s) of Notes which each Notes Software is capable of showing. The names of the notes follow Note Name Format rules as per [MGT: 99.Legend ## Note Name Format]. The Index adjusts automatically each time a note is added or deleted so there is no need to maintain references to or from the Index. 
Alternatively, one can create a dedicated Note, or a section in a Note referencing other Sections and or Notes using the [ ... ] reference indicator.

Logs
These are the individual notes, for the MF at least a note per Profile Tree Item. Each of these notes can contain that: scribbles of ideas, thoughts, or more formally, definitions, rules etc. related to the topic of the note. The logs for the MF are by default the following notes:

MGT: 00.Management
MGT: 01.Planning
MGT: 02. Organising
...
...
MGT: 51. Finance
MGT: 51.HR
...
...
MGT:80.Tools
MGT:99.Legend

Collections
There are many collections by design of the notes framework:
- Each note is a Collection
- Each section in a note can be a Collection

The Management notes mentioned above are thus also a Collection. 

### 00.Management
The note MGT: 00.Management is a special log. It has a flexible setup to reflect Management overall. Although the setup is flexible, it has the following recommended L1 sections from the Key deliverables for Management:
- Introduction
- Scribble
- Management Cycle
- Management Improvement
- Planning
- Organising
- Leading
- Controlling

Introduction
Explains what the note is about including a list of the above L1 sections (itself included). It is possible to omit the list of L1 sections to save space. 

Scribble
A section where anything can be jotted down to be deleted, or transformed into another note, or into another section. 

Management Cycle
The Management Cycle can have an L2 section per MC cycle i.e., Management. Revenue, Cost, Risk, Run, Change and Intel (all optional). In addition, it can have the following L2 sections:
- Knowledge
- Dates
- My Things, with following blocks using Objective Notation:
    - Things to highlight in reporting period
    x Things that were completed in the reporting period
    / Things being worked on
    . Things not started
    ~ Things pending with others
- Staff Things (as many sections as Staff to be tracked), each staff has the same blocks as under Myself above.

The My Things and Staff Things sections can be used for reporting in L1 section Report, see below.

Management Improvement 
Management Improvement has notes related on how to improve as a manager.

Planning 
Reflects Management Function Planning, and serves as a scribble section for aspects of this Management Function. In most cases it just points to [MGT: 01.Planning], but during the performance of the Management Cycle, ideas, small projects to improve Planning can be collected here, and later ported to the permanent note or to MSS.

Organising 
Reflects Management Function Organising, and serves as a scribble section for aspects of this Management Function. In most cases it just points to [MGT: 02.Organising], but during the performance of the Management Cycle, ideas, small projects to improve Organising can be collected here, and later ported to the permanent note or to MSS.

Leading
Reflects Management Function Leading, and serves as a scribble section for aspects of this Management Function. In most cases it just points to [MGT: 03.Leading], but during the performance of the Management Cycle, ideas, small projects to improve Leading can be collected here, and later ported to the permanent note or to MSS.

Controlling 
Reflects Management Function Controlling, and serves as a scribble section for aspects of this Management Function. In most cases it just points to [MGT: 04.Controlling], but during the performance of the Management Cycle, ideas, small projects to improve Controlling can be collected here, and later ported to the permanent note or to MSS.
________________________________________
## BuJo MSS (Software)
MSS, see [## MSS], has 7 Sheets implementing the BuJo concepts discussed above to the Managerial 7, see [MGT: 99.Legend ## Management Cycle]. BuJO MSS is essentially BuJo logic implemented within the MSS framework.

### BuJo MSS Concepts
A key feature is the fact that 7 dedicated *Logs* are used, one for each of the Managerial 7. These Logs are captured in [MSS: M0] to [MSS: M6]. BuJo MSS is similar to standard BuJo, but the implementation is simpler because of the use of:
- Only a few dedicated sheets collecting entries relevant to each Managerial 7
- Formulas to generate enriched data (Calculated Columns)
  
Data
A dataset in BuJo MSS is called a *Journal Entry*, an *MT Entry* or just *Entry* and is entered as a single row in the sheet. Unlike BuJo, BuJo MSS has a broader dataset driven by various columns. As a result, an MT Entry is broken down across several columns as opposed to the single item/line in standard BuJo. There are two *types* of columns: *Calculated Columns* and *Manual Columns*. The content of the Manual Columns drive all other aspects of BuJo MSS through the Calculated Columns. 
  
Goals, Sub-Goals and Tracking Type are maintained as Static Data in [MSS: Static] and have attributes associated to them that are used in Calculated Columns like the order of Sorting, whether or not to report, etc. Goals are standard and require, in general, no updates. Sub-Goals depend on the focus a Venture wants to have within a Goal each year.
  
Index
There is no index as data is logged in one sheet for each of the Managerial 7.

Rapid Logging
The Rapid Logging method is used in Column = Tasks. 

Log
There is only one Log per each Managerial 7. Each sheet's calculated columns display dimensions like Day, Week, etc., which in standard BuJo are considered separate Logs.

Collections
Collections are represented by Column headers. All column headers can be used. Tag, specifically, was designed for the purpose of Collections. As the name implies, Tag allows setting one *or more* key words for an Entry. 

Migration
There is *no* notion of migration of data from one Log to another or to a Collection in BuJo MSS. The capacity to filter and sort data achieves the concept of migration e.g. filter on Time, Open Tasks, Tags, etc. 
There *is* a notion of year-end cleaning, see below.

### BuJo MSS Process - Yearly - Cleaning
TBC

### BuJo MSS Process - Yearly - Roadmap
At the start of each year the Roadmap needs to be established, see also [## Roadmap], as follows:
- If Sub-Goals have been pre-defined, use those, else create them in [MSS: Static ## Sub-Goal].
- Add new Projects and assign a Sub-Goal
- Update existing Projects / Potentials similar to the step above if they are to be in the current Roadmap 

From this point onward, maintain the Projects that are part of the Roadmap through Notes and Tasks. See also [### BuJo MSS vs Planning]. The same can be done for Management and Routines. 

### BuJo MSS Reporting
BuJo MSS is setup in line with MSS principles in that reporting from it is achieved using pivot tables. The use of Tag helps defining content for different Stakeholders.
________________________________________
## Holistic Data Approach
See [STD: Data Science # DATA & INFO].
________________________________________
## Manager Meeting (Framework)
See [## Reporting via MSS].
________________________________________
## Progress Tracking (Framework)
A key component of Measurement is Progress Tracking. This consists of tracking status of all Routines and Projects against expected target. 

There are various ways to track progress. For Projects it is mostly done through the Project plan, see [## Project Management].

For a more continuous Progress Tracking, use the Management Tracker, see above.
________________________________________
## Committee (Framework)
This framework uses the following definition of a Committee:

A Committee is a *recurring meeting* that relevant *Members* attend with the *Purpose* to make *Decisions* for one or more *Proposals* based on *Information* in relation to one or more *Topics*. Committees are framed by the *Terms of Reference*.
  
These aspects are discussed below.
   
### Committee Recurring Meeting
A meeting or session takes place in presence or on-line with a predefined recurrence or frequency, with the option to initiate ad-hoc meetings when relevant.

### Committee Members
There are several Member Profiles with different accountabilities:
- Secretary: accountable for the administrative aspects of the Committee (planning meetings, circulating agenda, recording and circulating minutes, etc)
- Chair: accountable for assuring the committee achieves its stated Purpose. The Chair is often a Voting Member (see below). The Chair and the Secretary can be the same person. 
- Voting Members: people accountable for *and* having the authority to make decisions for Proposals made. They can also make new Proposals through the Chair. 
- Non-Voting Members: people who are Subject Matter Experts (SME) in relation to one or more Topics. 
- Guests: people acting as SME for a Topic that may not require standing membership, or people who may use the outcome of the Committee as input of another Committee or other Process. 

Depending on the Committee it is possible for a Voting Member to delegate the voting power to a delegate. This is valid only if the Terms of Reference permit such delegation.
  
A *Quorum* refers to the minimum number of Voting Members necessary for a Decision to be made and to be valid. Every Committee has a Quorum, and that rarely changes for a given Committee. There is no general rule on how to establish a Quorum. However, for a given Committee, the rules for a Quorum are formalised in the Terms of Reference, see below. If the Quorum cannot be met the session has to be adjourned i.e., suspended to be continued later.  
  
### Committee Proposals & Decisions
Decisions a.k.a. Resolutions consists of a binary approved/no approved, yes/no, accept/reject or similar construct, of a specific Proposal through a vote. This means that Proposals need to be presented in a form that facilitates such vote, which is often achieved by framing the Proposal as a question e.g. , "Do the Voting Members approve the following Proposal to ..." or more formally "Do the Voting Members approve the motion to ...". 
  
There are two key types of Proposals:
1. Proposal to *do* something i.e., if the Proposal is approved, an Action will be taken.
2. Proposal to *agree* on Information provided without leading to an Action i.e., if the Proposal is approved, a formal record exists that the Committee saw and agreed with the Information.
  
The approval of a Proposal may require unanimity or just a majority. Approvals can be accompanied by one or more conditions restricting the scope or the actual implementation of the Proposal. Some or all Voting Members can have the right of Veto which means a single Vote can reject a Proposal. 
  
It is important to note that it is possible to have Committees whose purpose it is not to make decisions. This framework, however, as mentioned earlier, assumes Decisions *are fundamental* to a Committee. There are two reasons for this:
1. If no Decision is taken, any purpose of a Committee is really questionable. 
2. As mentioned above, it is possible to construe a Decision for a Proposal to merely agree on Information provided.
  
### Committee Topics
Proposals presented for approval relate to one or more Topics. Conceptually, a Topic is either concerned with the Run of Production, the Change of Production or a combination of these and it can concern both the *result* of Run/Change or the *manner* in which Run/Change are conducted. 
As a Committee concerns recurring meetings, the Topics themselves are often recurring as well. If a Topic is not recurring it is an ad-hoc Topic (which could be an action point of a previous meeting). The list of Topics for each meeting are reflected in the Committee's *Agenda*. 

### Committee Information
The Topics for Proposals rely on Information a.k.a. Intel. As explained elsewhere, Information and Data are related. Data is defined as individual facts, whereas Information is the organisation, interpretation and visualisation of those facts i.e., a Process is involved to transform Data into Information. Therefore, assuming Data w/r to a Topic is available it needs to be transformed such that it yields Information for a Proposal to be made and for the Committee to base its Decision for the Proposal on.   
Depending on the Information type, the determination of whether a Proposal is required can be framed within the information creation process. For example, if the Topic is related to the monitoring of a production aspect "Number of failures of some Asset ...", "Percentage of breaches of protocol of some process", the Information creation process can dictate the use of a threshold like a cap or floor above or below which a Proposal has to be made, but below or above which such Proposal is not necessary. This could be something like: "If threshold is breached the information is presented in the appendix, else an explanation needs to be provided and a proposal needs to be formulated." The manner in which Information is produced including thresholds as well as the manner in which they are used to yield Resolutions should be reflected in the Terms of Reference.  
In many cases, the Data collection and Information creation as preparation of the Committee can be, and often is, more time consuming than the actual meeting.  

### Committee Purpose
Ultimately the purpose of a Committee is to make Decisions. However, not every Committee makes on the same Topics of course. As such, a given Committee focuses on a group of Topics or type of Topics across a given Scope e.g., Client Onboarding, Quality Control of the assembly line, etc. 
  
A specific type of Committee is the *Oversight Committee*:
- Company Board Meeting, Executive Committee
- Specific functionality Committees: Risk Committee, Sales Committee, ...
- Committees focusing on Projects: Operational Committee (Opco), Steering Committee (SteerCo)
  
### Committee Minutes
Minutes reflect the Decisions that were taken including the formalisation of Action Points that were decided. Minutes should in general only be concerned with decisions.
  
### Committee Terms of Reference
The Terms of Reference (TOR), Committee Charter or Committee Mandate of a Committee reflect all the above aspects in a single document. The content of the TOR itself is proposed for validation by the Committee's Voting Members. As some of the aspects can change over time i.e., new Chair, new Voting Members, different Quorum, different recurrence, etc. the TOR is reviewed and approved regularly.  
  
### Committee Rules of Order 
Committees often follow certain guidelines on how to prepare, hold and minute the meeting. This is often based on some form of Robert's Rules of Order. These Rules are available as books. 

### Committee Obligations Under Law
Depending on the law under which a Committee operates the above mentioned generalities may be overruled or enforced. For example it is possible, that under certain laws or regulations, every discussion within a Committee needs to be recorded and minuted, even if no Decision was taken. Similarly, under certain laws the Quorum is 100% of the Voting Members, etc.  A typical example of specific obligations arising out of law, are Board of Directors in many jurisdictions. This can go as far as dictating the manner in which Resolutions are presented. 
________________________________________
## BOD (Framework)
The Board of Directors is an efficient tool for oversight and delegation.

### BOD Research
By hbr:
~/data_public_study_HBR_BOD_Are_You_Ready_to_Serve_on_a_Board.pdf
~/data_public_study_HBR_BOD_Proactive_Questions_Every_Board_Member_Should_Be_Asking_.pdf
~/data_public_study_HBR_BOD_the_boards_most_important_function.pdf
________________________________________
## MBO (Framework)
@@@
________________________________________
## BSC (Framework)
@@@
________________________________________
## OKR (Framework)
@@@
________________________________________
## Process Review (Framework)
See [STD: Management # PROCESS REVIEW]
________________________________________
## Staff Reports (Framework)
@@@ weekly reports to be sent by Staff@@@
________________________________________
## Staff Meeting (Procedure)
The purpose of individual Staff Meeting is as follows:
1. Review progress of Staff w/r to the Run i.e. Routines, details of which can be Tasks
2. Review progress of Behavioural, Operational and Ad-hoc Objectives. 
3. Act as a one-on-one, see [## One-onOne].
4. AOB (Any Other Business)

The expected output is:
1. Updated Routines (Tasks)
2. Updated Projects (mostly AO, potentially BO, OO)
3. Concerns / updates w/r to personal progress
4. Concerns / udpates w/r to business progress

The process of setting up and running a meeting is:
- Have Staff setup a recurring meeting with manager
- Staff drives the meeting, manager guides it
- Ahead of meeting review [MGT: Planning] for Staff
- During meeting:
    - Review [MGT: Planning] with Staff (Routines and Projects)
    - Update [MGT: Planning] AO for Staff (see below)
    - Give feedback to Staff, see [## Feedback]
    - Ask feedback from Staff, see [## Feedback]

Updates to [MGT: Planning] are done as follows:
- Update Status/Dates of existing BO/OO/AO
- Create new AO if warranted during meeting
________________________________________
## Management Meeting (Framework)
A Management Meeting consists of meetings with Managers of Activities where those Activities have not been delegated by the Manager. This is for example the case of the Manager is a COO or Business Manager where the delegation of Activities is done by the CEO or Head of Department etc.

The concepts of a Staff Meeting, see above, are applicable to a Management Meeting, but in a slightly modified version.
________________________________________
## Check Standards (Framework)
As a reminder, to Check is one of four different manners to establish Supervision (the others being to Review, to Attend and to Audit). A Check consists of a verification of some measurement against a well established baseline. Many companies refer to this as a Control, but the Profile defines a Control as any of the Four Supervisory Processes.    

The Check Standards define how a Check should be designed. The Check Standards are entirely based on the general Control Process concept discussed in [MGT: 99.Legend ## Controlling].
   
1. Establish the *Purpose*;  
2. Establish the *Baseline* or Benchmark  
3. Get a *Measurement* of output of one or more Objectives;  
4. Perform a *Comparison* of Measurement vs Baseline;  
5. Perform an *Analysis* of the Comparison and, if relevant;  
6. Define a *Remediation*;  
7. Keep a *Written Trail* of 1-6, use it to *Report* and track Remediation.  

Purpose  
In above 7 steps, Purpose is key in setting up a Check. It sets out what the Check is to achieve ultimately. In many cases Checks are designed to avoid the occurrence of Risk, or to assure a minimum level of quality or performance has been reached. The Purpose will explain this Risk (including how it can materialise), or what the minimum level of quality or performance is (including what influences it). It will also explain how the Check helps avoiding the Risk, or helps assuring a minimum level quality or Performance. This section may depend on the next step.
The purpose can also provide additional information including:
- How the check is to be performed  i.e. where to get the data, how to get the data, how to process the data etc. 
- The names of Subject Matter Specialists who can help with more difficult findings 
- The names of the people to be informed 
- Etc. 
 
Baseline  
The Baseline defines what exactly needs to be measured, and critically, the thresholds at which a *Breach* is deemed to have occurred i.e., the variance or dispersion allowed from the Benchmark. A Baseline depends on a good understanding of the Purpose. The Baseline may require insight in the next step: the definition of Baseline has potentially a dependency on how a Measurement can be performed in the first place. It is possible that there are more than one type of Breaches in a single Check. These are referred to as *Breach Types* and establishing these at the start of the design of the Check greatly helps in the Remediation step.   
  
Measurement  
Once the Baseline is established the actual work takes place: Measurement. Ultimately, a Check relies on Info produced from Data. Measurement consists both of collecting Data (potentially from several sources, and including cleaning, transforming, enriching etc) and then establishing some Info from that Data (potentially different forms of Info). Note that Data can be both quantitative as well as qualitative.  
Measurement is heavily proceduralised, which allows to accurately reproduce the same Info over and over. This step includes rendering the Info in the desired format to be able to compare where applicable: numbers, ratio, graph,... 
NB: Data represent facts, Info is them organisation and interpretation of those facts. 

Comparison  
The Comparison of the Measurement vs the Benchmark is effectively what it says: put the result of Measurement in front of the Benchmark. 

Analysis  
The Analysis should yield a single conclusion: a breach or not. A breach means that a Remediation is required. This is simple on paper, but in reality it is not because Analysis may yield different outcomes, out of which the first two are true breaches are really relevant, and the other two are noise that may require remediation nevertheless (of the Control process).
1. True Positive: a breach that is indeed a breach
2. True Negative: a lack of breach that is indeed no breach
3. False Positive: a breach that is actually not a breach
4. False Negative: a lack of breach that actually should have shown a breach. 
  
Remediation   
Remediation a.k.a. Action Plan should avoid the breach found in Analysis (most often for the next time the Check is performed) *or* should remediate the control  such that the False Positives and False Negatives are avoided. 
As such, this step may require going back to the Analysis step to clearly identify the best way to remediate.   
Remediation should clearly explain how to implement it and should include the manner in which the desired effect will be measured (normally through a re-run of the check).
Often, the occurrence of breaches can be expected. In other words, it is possible to define so called *Possible Remediation* which are Processes to perform if a specific Breach Type occurs. Possible Remediation helps speeding up the remediation process by avoiding spending time on investigation.   
  
Report  
All of the above steps are documented or Journaled, and a Report is produced.
The Report is used in the two last deliverables of Controlling: Reports and Monitoring, which will assure Management is aware, and can track the progress, of Checks in general and of Action Plans in particular. 
________________________________________
## Control Conundrum (Definition)
The Control Conundrum reflects the following counter-intuitive proposition:

"Too Many Controls Kills the Control."

This stems from the fact that the Check Standards can be heavy to implement. If it is done for many different checks and Reviews, then the time spend on Controlling might be disproportionate to the time spent on the Run that those Controls are supposed to supervise. 
In addition, the moment the execution of the Checks Standards yields many false positives the Staff involved in analysing such False alerts, will get bogged down in doing Control work. The same is true for too many True Alerts generated as a resulf of Benchmarks that are not calibrated correctly i.e. too conservative versus the Risk it tries to avoid, or the Service or Product Quality it tries to ascertain. 
________________________________________
## Self-Contained Mail (Framework)
Many Checks are fully automated and should aim at embedding above Check Standards within the automation. Often, the results of Checks are sent by e-mail. In such cases, the content of the Mail should be what is called Self-contained i.e., the receiver of the Mail should be able to understand what is expected. 

When setting up a Self-Contained Mail system, assume that the Receiver of the mail: 
- is completly unaware of why he/she receives such Mail;
- has little knowledge of the Activity(ies) the Check is relevant to.  

The following are guidelines on how to set this up:
- Design the Check according to the Check Standards, see [## Check Standards], in which the step 7, Report, is effectively the mail. 
- Design the Content of the mail such that all Steps of the Check Standards are presented to the Receivers of the mail.
- Use a Subject such that the Receiver can see the urgency of the mail.

The first step is documented in [## Check Standard].  

The second step is organising the content such that the Receiver has all information requried to make an assessment. The content itself does not need to be in the mail. It could be presented in another location e.g., a clickable URL. The suggested content is as follows (in order):
- Purpose
- Analysis -> shows whether there are breaches or not
- Appendix
    - Baseline
    - Measurement -> description of how Measurmeent is performed, not the Data 
    - Comparison
    - Remedation -> notably Possible Remediation
    - SME -> whom to reach out to in case of questions
  
The third step is implementing a logic to show to the Receiver which Urgency and type of Check the mail represents . Below follows a possible implementation:
- INFO xxx
- WARNING xxx
- CRITICAL xxx   
  
In which:  
- xxx = short decription of the Check
- INFO = no breaches were found
- WARNING = breaches were found
- CRITICAL = check could not run at all
  
There are other Subjects possible. For example, "Breach: Breach type yyy for xxx", etc.  
As can be seen, applying the Check Standards drive most of a well conceived Self-Contained Mail framework!
________________________________________
## Reporting Definition (Framework)
Reporting is conceptually simple, but not always easy to implement because:
- Reader of the report may not be familiar with the lingo/acronyms/topics.
- Inconsistent manner of writing down the facts
- Too many details provided
- Data is not always available at the time of writing a Report.


### Management Report
The Management Report focusses on the Managerial 7. There are different ways to report the various facts, depending on: 
a. Frequency at which Report is needed
b. Frequency at which data is produced 
c. Need for that data to be reported. 

0. Management
@@@

1. Revenue
- Actuals: YTD, MTD, WTD, Trends, Avgs, vs Y-1, budget etc.
- Exceptionals: unexpected or exceptional Revenues or lack thereof 

2. Costs
- Actuals: YTD, MTD, WTD, Trends, Avgs, vs Y-1, budget etc.
- Exceptionals: unexpected or exceptional Costs or lack thereof 

3. Risk
- Actuals: dependent on the sector the Venture operates in. 
- Exceptionals: losses 

4. Run
- Exceptionals: the Run is expected to operate as expected. Only Exceptionals should be reported.

5. Change
- Actuals: updates on progress of Projects, but focus on:
- Exceptionals: the Projects that are ahead or behind schedule. 

6. Intel
- Updates: relevant ones to the Venture both from internal and external 
________________________________________
## Reporting Standards (Framework)
The Reporting Standards frame how facts should be reported in the most basic manner.

### Reporting Standards Principles
The following principles should be observed:
- if relevant show the date of reporting
- Use past simple tense the type of update (Completed, Progressed, Started or Kicked-off, Put on hold,...)
- Indicate *what* was completed
- If relevant, indicate when it was started
- If relevant, indicate when it was completed and if late 
- If relevant, indicate whom it was completed by
- If relevant, indicate whom it was completed for
- If relevant, indicate comment 
- If relevant, indicate next actions including deadline

Note that most reports are of the form: report for week ending dd Mmm yyyy wit various reporting entries in which case the date of reporting is omitted. 

Example: 
Completed review of audit report started on 1 Oct 2022 on 15 Nov 2022 and before due date by John Doe for the Car Testing Department. Conclusion: department overall in ok state vs regulations but improvements necessary due to new regulations on gas emissions. Next: deploy 2 action plans before 15 May 2023.
  
### Reporting Standards Implementation
Above principles are implemented through Objective or Task Notation, see [## Objective Notation], [## Task Notation]. Reminder of the expanded Format for both in non-recurring Objectives and Tasks:

status name (start:end:compl:eff) {perf:benef} |link| [ref]

The following indicators on the expanded format are kept as is, if the reader is familiar with the Objective/Task Notation Format, or replaced with specific words:
- Status: "Completed ...", "Started...", "Progressed ...", "Moved to pending ..."
- Start, Complete in human readable form and "before due date" or " late" to indicate complete date versus targeted end date 
- Owner: "...by performer ..." , "... for beneficiary..."
- Link: mostly omitted
- Reference: details of "Comment:" and of 'Next:'
________________________________________
## Reporting via MSS (Procedure)
For work context, MSS, see [## MSS], has built in Reporting capabilities through Pivot Table logic. 

There are various aspects built in MSS that facilitate the reporting process. Reporting is mostly of the back of the Data Sheets. Those sheets have various columns that facilitate the Reporting process:
- Report? (manual)
- Last Note (calculated from Column = Notes)
- Last Task (calculated from Column = Tasks)
- Last Update Date (calculated from Last Note)

Combined with the rest of the columns the above columns, together with Pivot Table logic help generate reports that can be used as a periodic static report or as an interactive report for management meetings.
________________________________________
## Executive Summary (Framework)
A Manager needs to be efficient in what it does over the time given to a Manager. This means *Topics* the Manager needs to be made aware of, and Topics Stakeholders need to be aware of need to be clear and concise for both. This is even more important for *Evolving Topics* e.g., incidents, new regulations, etc. An Evolving Topic's status changes over time. A Manager also needs to be able to communicate efficiently around Topics. The Executive Summary helps in achieving this and is composed of 6 points:

### Name
Name or very Short description of the Topice.g., Project, an event.

### Context
The context should answer the 6W of the Topic. They can be used freely, but mostly go along with the 6W Method defined above, see [MGT: 99.Legend ### 6W Method]. The context can be omitted if the Manager knows the audience are aware of the context already.

### Last Status
This reflects the Status of when the Topic was last discussed. The Last Status should be indicative how close the Topic was of being concluded at that time of discussion e.g. 60% done, 3 actions left out of 20, expected closure 20 Sep 2030, etc.

### Current Status
The Current Status is similar as the Last Status in terms of type output. It also includes what was done compared to the Last Status. e.g. 10% works was done, so 30% remains for the next two weeks, expected closure moved forward to 10 Sep 2030, etc. 

### Attention Points
Any aspects that are a potential impediment in the conclusion of any remaining actions of the Evolving Topic. It is possible to put Attention points *before* the Current Status, if the Attention Points are a reason for delays to have occured compated to the Last Status.

### Next Actions
Given the above, what are the expected actions to be able to conclude the Evolving Topic. Of course, if the Current Status = Completed then there are no Next Actions.
________________________________________
## Briefing Note (Framework)
@@@
________________________________________
## Dashboard (Framework)
Dashboard are a tool to present *information* based on *data*. Data is defined as individual facts, while information is the organisation and interpretation of those facts. 

The creation of a Dashboard should thus consider the following aspects:

### Data Production
The extraction of Data from Data sources.
@@@

### Data Collection
Data is obtained from various sources, but often those are Electronic records @@@

### Information Production
Information should abide by the following criteria:
@@@ see if this is not already discussed somewhere in this note @@@

@@@
- Decisional vs Informational
- Short vs vs Medium vs Long Term
- Tabular vs Graph
- Thresholds
@@@


*********************************************
# OPERATIONS
Operations is the total of all Objectives performed within a Venture.
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Operations]. On L2 are the Tools:
- Run
- Change
- Income
- Cost
- Risk
________________________________________
## Life Cycle (Framework)
Not always applicable, a lifecycle explains how the various Routines and Projects interact and recur. Key elements of an Operational Lifecycle are:
@@@


*********************************************
# STAFF
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Staff]. On L2 are the Tools:


*********************************************
# ASSETS
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Assets]. On L2 are the Tools:

- Accounting Assets incl. Cash
- Infrastructure
- Intangibles
- Data
    - Data & Info
- Services (from Suppliers)
________________________________________
## Data & Info (Framework)
Data is a topic that should really be split into two aspects: *Data* and *Info*. Below discussion drills in to both aspects individually, as well as how they relate to each other. Various definitions are provided, and although not all of these are strictly speaking industry standards, they help in framing an overall Data & Info Approach. 

### Data
Data is a *record* of *fact* or facts. A record contains one or more facts each stored as a *Data Field* or field in short. Facts are broad: revenue, COGS, suppliers, Operational Costs, staff skills,...

Below follow key aspects involved in Data. 

Data Set
A regrouping of records of the same fact(s) is called a *Data Set*. For example, all records related to Revenues is the Revenue Data Set. A record can contain several facts and so a single set of records showing both Revenues and Cost is a single Data Set.

Time-Bound & Instance-Bound 
Facts can be *time bound* as well as *instance bound*. Time bound data is a natural consequence of measuring facts over time. An instance is a general term for a scope or a combination of scopes e.g., geography, temperature zone, department within an organisation, departments within geographies, etc. 

Variable 
A fact is often a Data Variable or *variable* i.e., its value changes over time and/or across one or more instances. In other words, *change* is embedded in Data. 
If a fact does not change by *design* it is deemed a *constant*. Constants are regrouped into a Data Set called *Static Data* an example of which is the income tax rate per country for a given year (which indeed can change over time).

Data Representation
Facts can be represented in different manners:
- Numbers
- Text
- Audio
- Video
- Images

Of these, numbers and text are the most used for the simple reason that they embed very few facts but are easy to use. A video is difficult to interpret as a single fact, and even if decomposed in individual facts over time, there are many facts: colours, shapes, audio, etc. 

Data Owner
The person owning a Data Set. Often this is the person responsible for one or more Processes related to the Data Set. Often such Processes are captured in Software and the underlying Data in a *database*.

Data Types
There are three key Data Types:
- Time-series: a Data Set representing an evolution of one or more variables over time. 
- Cross-sectional Data: a Data Set that is a snapshot in time of one or more variables across an instance. 
- Panel Data : also known as Cross-sectional Time-series is a combination of above two types, i.e., collection of variables at multiple times across multiple instances. Panel Data is probably the most used form of Data. 

Data Equation
The variable or fact changes within one of the three Data Types. As such, the variable can, in theory at least, be captured mathematically as an equation:  y = f(x) in which y is the fact and f(x) is a function of the Data Type, bearing in mind that Panel Data is a combination of time and one ore more instances i.e., a multi-dimensional relation!
In reality the  Data Equation often does not exist, or only on a too small subset of data to be relevant. The attempt to find the equation is part of Info.

Data Quality
Data Quality is the state of Data that tells how reliable a Data Set is to be considered for the production of Information. If a data set is of high quality, it must fit the intended use or purpose. It must be complete, accurate, reliable, easy to access, consistent with different sources, and easy to represent in Info.
NB: there is no universally accepted standard for Data Quality as this is very much organisation dependent.  

### Info
Information or Info is the organisation and interpretation of facts embedded in Data. In other words, it attempts to find a relation between a variable and passage of time and/or changes of instances. Another word for Info is Descriptive Statistics or Descriptive Data.

Most often, Info requires more than one Data Set to be used. In other words, Info becomes more relevant when there are relations between different variables across different Data Sets. Or yet differently, the manner in which change, embedded in Data Sets, can be shown to be linked across those Data Sets in the the past and across instances gives the means to make decisions for the future and across instances. 

Info Owner
The person responsible for Information. This is the person accountable for providing information to Info Consumers. 

Info Consumer
The person using information for some purpose. Examples: Department head, Support unit manager.

Info Purpose
The purpose for which Information is used. Not all Data Sets yield to the same information. Data Sets can in fact be used for different purposes. Example: Nr Products Sold gives the Marketing department insight in success of marketing campaigns, but it gives the Finance department insight in total manufacturing costs 

Info Representation
There are various manners to render or represent Info. The two most common Info Representations are Tables and Graphs a.k.a. Charts. 

- Table: Prepped Data -see below- (or a subset of it) is displayed in *tabular* format. If the table is small it may convey useful information, but if the Prepped Data is complex Panel Data then the reader will quickly get lost in *data overload*.  The only way to help the Info Consumer in this case is to highlight specific parts in the table like outliers or trends,  using specific formatting (different background, different font colour or size) or adding indicators (arrows, encircling the data)
- Chart: Prepped Data (or a subset of it) is displayed in a  *graphic* format. There are many types of charts (see below). It is possible to provide multiple variables in a single Chart, but like with Tables, the Info Consumer risks suffering data overload. In addition, although there are many options to render info in a chart, this does not mean that all types of charts need to be tried when rendering Info.

Chart Types
The types of charts one can choose form are numerous: Bar Charts (horizontal), Column Chart i.e. a vertical Bar Chart, Pie Charts, Scatter Chart, Area Charts, Line Charts, Bubble Charts, Net Charts a.k.a. Spiderweb charts, Waterfall charts., Stock Charts a.k.a. Box Charts, Mekko Charts, Histograms,... and combinations of all those charts, using various techniques including two vertical axis (major, minor), using three dimensional versions of the above, using logarithmic scales etc.

Refer to the following websites for examples of charts:
<https://www.stratechi.com/business-charts>
<https://www.theanalystacademy.com/mckinsey-report-breakdown>

Absolute vs Relative Info
Within both Tables and Charts, Info can be rendered in two distinct manners: 
- Absolute rendition e.g. revenues in 2020, 2021 & 2022 
- Relative rendition e.g. % change 2022 vs 2021, 2021 vs 2020

Static Info or Dynamic Info
Info can be rendered statically, i.e., a a single snapshot of one or more Data Sets, according to the scope defined by the Info Owner. 
Alternatively, the Info Owner can give the Info Consumer the ability to zoom in to a more detailed level of one or more Data Sets, or reversely zoom out, to get a broader view of the facts. This dynamic a.k.a. interactive manner of providing Information has various advantages, and is particularly well suited for Simulation Info.

Simulation Info
It is possible to provide info based on hypothetical facts, in other words, *create* non-factual Data Sets that could exist at some point in time and/or within an instance, and then use that Data Set to display theoretical Info which may better help an Info Consumer to make decisions. 

Info Types
The usefulness of Info is ultimately defined by how well the Info Consumer can make decisions based on it.
There are three essential types of indicators that allow managers to make decisions

KPI
A Key Performance Indicator or *KPI* is a quantifiable measure of performance for an Objective. Where the Objective says what is aimed for, the KPI makes it quantitative and therefore easier to track. This is the most simple form of Information and it is relatively easy to produce it: there is an Objective that is performance related: nr Products produced , nr Products sold, total revenues, total cost etc. These types of indicators are bound in time e.g. a year or an instance e.g. a geography. Once that objective is there, the only thing to do is collect the data related to the Objective and transform it in the Objective's target unit and then compare with the target. Example: i) NBI objective full year = 950 M EUR. KPI = NBI YTD annualised vs Objective as a %, ii) Cost objective full Year = 170 M EUR. KPI = Cost Annualized vs Objective as %, iii) ROE Objective = +1 % vs Previous Year. KPI = expected ROE vs Previous Year.

NB: the above assumes that Objectives were defined according to SMART principles which includes the notion of Measurable i.e. quantitative facts . Objectives that use a qualitative expression like "make things better" are of course impossible to raise KPIs for.  

KRI: 
A Key Risk Indicator or *KRI* helps Info Consumers identifying Risk caused by weaknesses in Processes or in the Services/Products created by those Processes. KRIs are used to give insight into Risk. This is where KRIs deviate from the simplicity of KPIs: Risk is unknown, by design. Risk is the *probability* of an *adverse event* occurring at some point in the future. Although not always morally correct, adverse events are eventually all a form of money: fines, loss of revenues due to non-production, loss due to recall of a product, loss of staff (this is where the moral piece pops up), etc. Methods like back-testing can help identify expected failures in specific Processes, but often losses occur in Activities that are a complex combination of many Processes that make it hard and/or economically nonviable to back-test. 
The conclusion of the above that it is often hard to produce KRIs. Most KRIs are at best a proxy, an indication of how things stand today, but do not truthfully show either probability or the impact of the event occurring. However, all is not lost, although precise data may not be produced, a lot of data is available w/r to trends related to either Activities or Processes within those Activities. Example: i) Nr of Server Processes not available to traders at 08h30. KRI = Process up-time, ii) Total Loss amount related to Processes not available for traders at 08h30, iii) Nr Systems used in Production, v) Nr Handoffs between Processes, etc.

NB: it is possible to set an objective to stay within certain risk limits for example. Such cases can then be deemed KPIs. It may be that the KPI depends on data collected to produce KRIs.

KCI: 
A Key Control Indicator or *KCI* a.k.a. Control Effectiveness Indicator provides information on the extent to which a Control is meeting its intended objective in terms of Risk prevention or reduction. In order to provide such information, the KCI has to have an explicit relationship to both the Control and to the Risk against which the Control has been implemented. As such, a KCI has a relationship with KRI.  Info Consumers can define desired tolerances or thresholds for controls. The KCI´s role is to ensure that adequate responses and monitoring have been provided to a risk situation identified by KRIs. Control verification is a key component of a KCI, and it usually includes auditing, quality assurance and improvement programs. Typical KCIs cover the reliability of financial reporting, number of audit issues or product quality assurance ratios. Example: i) nr of morning checks not performed before 08h30,  This ties in with the example given for the KRI above.

### Data Management
Data Management, or Data to Info or D2I represents the Input and Output of specific Processes in the production of Info from Data.

There are 4 levels of Objects (top) and 4 Processes (bottom) interacting with each other. 

Source Data        Raw Data     Prepped Data         Info
                  ⇘       ⇗          ⇘       ⇗               ⇘        ⇗           ⇘
                Collection  Preparation  Transformation  Disposal 

Source Data
Data is stored in various locations and formats (files, databases,...). This original set of Data is referred to as the Source Data and it is the start of the D2I Cycle. Each Source Data has a Source Data Owner. 

Data Collection
Data Collection is the process of obtaining Source Data. This may be done directly e.g. through an API, or indirectly e.g. the Source Data Owner generates a data extract and delivers them as a file. 

Data
Raw Data is the result from Data Collection Process. It is the most basic level of data before it becomes Info. This level of data is the same as the Data Owner knows. Raw Data may or may not be stored as part of the cycle. 
One important thing to note is that Raw Data may be less complete than Source Data. This happens when the Data Collection process re-scopes the Source Data e.g. show only records for the year 2020 or only provide 100 out of the 1000 fields available for a single record (because the other 900 fields are not very useful). Each Raw Data set has a Raw Data Owner, which is most often the person assuring the Data Collection. Raw Data is often stored in Data Lakes in case of industrial approaches to Data, where organisations want to make Data available to a large scope of people.

Data Preparation
Raw Data often requires preparation to make it usable for the final step. Typical actions in Preparation include: 
1. Data Cleaning: data may  have missing fields that need to be defaulted, shifted fields that need to be moved back to the right column, etc.
2. Mapping: some fields are not meaningful unless they are mapped to a more meaningful value e.g. a User Id can be mapped to a User Name. 
3. Reformatting: data fields may need to be standardised e.g. the date 4 May 2000 can be received from one Data Source as 04/05/2000 and in another Data Source as 05/04/2000 and in yet another Data Set using Excel date number as 36650 and from a UNIX based source 1588597200.
4. De-duplicating: certain records may be duplicate within the Raw Data or across Raw Datasets.
5. Scoping: Raw Data may contain records for a far larger scope than is needed e.g. all records for an entire company, whereas Info needs to be produced only for a department within.

Prepped Data
The result of Data Preparation is Prepped Data. It can be used to create Info. It is in most cases not easy, or if at all possible to go back from Prepped Data to Raw Data, unless detailed audit trails are kept during Data Preparation. 
A good Data Preparation Process creates Data that can be used for more than one Info, either in its own, or by combining it with other Prepped Datasets. Prepped Data is often stored for use later. Like with the other Data Sets, Prepped Data has a Prepped Data Owner. Prepped Data can be part of a *Data Warehouse*, which is a industrial scale repository of Prepped Data.  

NB: sometimes Source Data is in effect Prepped data. This means it has been modified to fit a specific purpose before it was made available as Source Data, which in turn may cast doubts on the Data's validity. Only if the Data is *certified* as being a true reflection of the Source Data, can such Data be used. The advantage is of using Prepped Data as Source Data is of course that Preparation process may be simplified. 

Data Transformation
The last Process, ultimately creating Info, consists of manipulating Prepped Data. Data Transformation is composed of one or more of the following:
1. Filtering: explicitly including/excluding records 
2. Sorting: ordering data such that it follows a trend (alphabetical, numerical, date,...)
3. Linking: combining one Prepped Data set with another a.k.a. Data Aggregation.
4. Calculating: using Prepped data to calculated new Facts, which can be stored as new Prepped Data e.g. calculating an average, median, a moving average, min, max, standard deviation... 
5. Rendering: using graphical tools to highlight trends, concentration, outliers (smoothing), new calculated Facts like Thresholds, etc. such that the Prepped Data, becomes more meaningful than in its existing form. 
6. Enriching: it is possible to use static values that are stored for specific Datasets. For example, a static value could be 10% (static) of Revenue as a Threshold for Operational Losses. Other static values are max nr counts, max values, etc. Such values often appear as straight lines, with or without a slope. 
7. Manual Analysis: iteratively producing Info and adjusting it to achieve the best possible Info. 
8. Automatic Analysis: advanced Processes to find relevant Info  in the Data that the person performing the Data Transformation is unaware of. This is the remit of advanced Data Science technologies. 

Info
Is the desired result of the Data Management Process.

Disposal
The last step is not a mandatory step and does not only apply to Info but also to the various forms of Data. Disposing of Data and/or Info may be required when they have outlived their worth or when for regulatory reasons retaining the data is not mandatory anymore.  Storing data is implied by all above steps, but storage has a cost and that cost may not necessarily be worth the Info that can be obtained from the Data. Disposing of such Data this becomes an economically viable choice.

Data Approach to D2I
There are various aspects of Data that need be considered before starting to work on the D2I cycle, these considerations are referred to as Data Approach. The Data Approach goes hand in hand with the Info Approach, see below.

The following guidelines help in framing Data Management
- Think larger than the scope of the Department in the Organisation for which data is needed: the same Data Set(s) are probably needed for other departments
- Review Source Data exhaustiveness and assure it has all fields required to produce Info before trying to productionalise the Data Management. 
- Test the D2I cycle on each Source Data and look at the Info that can be generated, and the extent to which the Source Data for that Info is complete or requires enrichment with other Source Data
- Never assume that *manually* performing the Processes involved in management of Data is worth the effort: it is not in the long run.  Building automation into the Processes should be considered from the very start.

Info Approach to D2I
An Info approach aims at assuring consistency in the manner in which Info is produced. This in turn drives consistency in the manner in which Data is managed throughout the D2I cycle, see also above.

The following guidelines help producing smart Info.
- Do not overestimate the skills of the Info Consumer: if the charts become too complex, you may miss out on the opportunity to convey the message.
- Do not overestimate the time Info Consumers will spend on the Info provided. This combined with the above guidelines means simply put: do not produce too much info! Stick to 2-3 messages and make them appear in the Info.
- Familiarise yourself with all Chart types, to see what can be done. 
- For time-series use the same overall period e.g. 2020/2021 across all variables e.g. NBI, Operational Incidents 
- For Chart types that group Data Points e.g. Bar Charts per month, use as much as possible the same grouping range e.g. all charts monthly.
- Stick to the same Info Representation for similar variable types i.e. if various Data Sets consist of time series for the same frequency then stick to a single Chart Type as much as possible, e.g. Area Chart for daily, Column Chart for quarterly, etc.
- Calculate new Data whenever possible to give a sense of perspective. This is particularly helpful for time series e.g. average or median.
- If data is Panel Data, try using bubble charts, or maximum two charts that show both the time series and the relative size/impact across the instances. 
- Minimise the use of Tables, rather move them to the Appendix
- In contradiction to the above, if the data set is small, and simple, do not use a Chart to convey the Data of a Table of small size!
- Highlight important parts (concentration, deviation, specific trends,..) within the chart rather than using words next to the chart
- More generally, a chart should be self explanatory. If many words are needed to explain a chart, then the chart does not capture the right Info.
- Prefer interactive over static Info, but be mindful of providing too many interactive charts. 


*********************************************
# SUPPLIERS
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Suppliers]. On L2 are the Tools:


*********************************************
# LIABILITIES 
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Liabilities]. On L2 are the Tools:


*********************************************
# EQUITY 
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Equity]. On L2 are the Tools:


*********************************************
# FINANCE
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Finance]. On L2 are the Tools:
- Accounting
    - Bookkeeping
    - Financial Reporting
    - Managerial Accounting
    - Revenue Measurement
    - Cost Measurement
    - Cost Allocation
    - Budgeting
- Finance
________________________________________
## Bookkeeping (Framework)
Bookkeeping is the process of recording financial transactions to the accounting books of the Venture.

### Accounting Equation
The process revolves around the Accounting Equation:

    Assets = Liabilities + Equity

This equation essentially represents the Balance Sheet. Assets are abbreviated A, Liabilities L. Equity is also called Owners Equity or OE (not E as that is used for Expenses, see below)..

The equation thus becomes:  

			A = L + OE

OE can be rewritten as:  

    OE = Stock + Retained Earnings 

In which: 
Retained Earnings = Revenue - Expenses - Dividends (or Drawings if it is a sole proprietorship). This can be rewritten as OE = R - E - D.
Common Stock, abbreviated as S a.k.a. Contributed Capital, Share Capital = initially invested money by owners in the form of Capital (see below). Mostly this is Cash, but can also be Assets like a building (although that is rare in the case of listed companies). 

Substitution of the first above in the Accounting Equation yields the *Expanded Accounting Equation*:
  
    A = L + S + R - E - D
  
    Assets = Liabilities + Stock + Revenues - Expenses 
     - Dividends

Or written differently:

 Revenue + Liabilities + Stock 
 = 
 Asset + Expenses + Dividends 

or written differently

 R + L + S =  A + E + D

Revenue, Expense and Dividend accounts are 'temporary' accounts. They need to be closed at the end of each reporting period, a.k.a. Financial Year.
Assets, Liabilities and Equity accounts are 'permanent' accounts. The ending balances in these accounts determine the starting balance as the start of the next Financial Year. 

### Accounts
A company has many different *accounts* which act as containers to collect data. The data is monetary value (not necessarily cash). Each account is of a type from the Expanded Accounting Equation i.e. Revenue Account, Asset Account, etc. There can be many different accounts for a single Account Type. This makes accounting granular. 

### Book Keeping Journal
The Journal represents the impact on accounts for each transaction.  Bookkeeping uses a logic of Credit (Cr) and Debit (Dr) entries to show that an account is increasing or decreasing. This increase or decrease depends on which item in the accounting equation the account belongs to, depending on whether it is the Left Hand Side (LHS) or Right Hand Side (RHS) of the last version of the Expanded Accounting Equation: 
- LHS ->  R, L, S  ->  Cr increase, Dr decrease 
- RHS ->  E, A, D ->  Dr increase, Cr decrease

Each transaction has at least one Dr and one Cr entry associated to it. More of each are possible but not very common. Each transaction's Cr and Dr totals are of equal size. 

Depending on the accounts associated to the Dr and Cr it will be construed as an increase or decrease with four possible combinations: increase/decrease, increase/increase, decrease/decrease, decrease/increase. All journal entries start with the Dr side of the transaction and then the Cr side. 

Some examples:

Sale of goods produced and paid in Cash
Dr Cash   934.50       # asset increase
 Cr Sales   934.50   # revenue increase

Purchase of food 
Dr Food   120.25        # expense increase
 Cr Cash   120.25     # asset decrease

Investment in an asset 
Dr fixed asset 450.00       # asset increase
 Cr cash    450.00  # asset decrease

Purchase of pens on credit card (a form of Payables account, a liability)
Dr office supplies 23.20     # expense increase
    Cr credit card   23.20  # liability increase

Monthly credit card payment
Dr credit card 230.00       # liability decreased
    Cr cash    230.00    # cash has decreased

### Book Keeping Ledger
Whereas Journal entries show the use of accounts scattered across a single place (the Journal) but with details of the transaction, the Ledger shows each account with all the Dr and Cr to that account and thus the net result. They tend to be shown in so called T accounts in paper versions with the Dr on the left and the Cr on the right side e.g. for the cash account in above trasnactions:

   Cash
_________________
934.50 |     
    |    120.25
    |    450.00
    |

### Book Keeping Process 
The bookkeeping process has specific steps to yield the Financial Statements for Financial Reporting, see next section. 

1. Collect Financial Transactions
2. Write Financial Transactions in Journal using Journal Entries
3. Post Journal Entries to relevant Accounts in Ledger
4. Calculate Unadjusted Trial Balance
5. If items don't add up post corrections to Trial Balance in worksheet
6. Post adjusting entries (accruals for expenses paid now for next Period, expenses to be paid for this Period, but deferred to next Period and similar for revenues) in Journal and Ledger and create Adjusted Trial Balance
7. Produce Income Statement, Balance Sheet, Cash Flow statement from Adjusted Trial Balance  
8. Close Trial Balance and prepare for next Period.

Note that Income Statement, Balance Sheet and Statement of Cash flow follow directly from the Adjusted Trial Balance based on the Accounts:
- Income Statement: Income and Expense Accounts
- Balance Sheet: Assets, Liabilities and Equity (broken down in Stock, Dividends and Retained Earnings) Accounts. 
- Cash Flow Statement: Cash Account (an Asset Account)

### Equity vs Capital
Strictly Speaking the difference between Capital and Equity was explained in [MGT: 99. Legend ## Equity]. But as mentioned there, sometime different definitions are used.

Equity is the amount of money shareholders get if all assets are liquidated and all liabilities are paid off.
Capital is the amount of money available to spend.
Capital is a sub-category of Equity by the above definition. 

In regulations Capital is used slightly differently as well: 
Tier 1 Capital = Shareholder Equity + Disclosed Reserves
Tier 2 Capital = Undisclosed Reserves = Reval Reserves + Provisions + Subordinated debt.

### Book Keeping Accounts
There are various account types used in accounting. Some are quite standard.

Receivabled & Payables
Receivables is a form of Asset Account that reflects Cash to be received in the future. This occurs for example when Sales are done on credit, i.e. a customer purchases a Service or Product on credit. Ultimately, when the cash gets paid, the Cash account is debited, and the Payables account is credited. 
Payables are similar, but on the Liabilities side. Payables reflect account types in which the Venture needs to pay Cash in the future. Once a Payable is paid, the Cash account is Credited and the Payables account is debited. 

Reserves & Provisions 
Reserves are a lability (counter-asset) that reflects amounts that are essentially an appropriation of profit for future *unexpected* losses or expenses.
Provisions are amounts set aside to meet *expected* losses or expenses. So both are for future use, but one is for unknown events, the other for known events.

The journal entries would be the following:

Reserve for a future cost of fixed asset in M USD
Dr Expense 123.00      # earnings decreased
   Cr Reserve  123.00   # increase of reserve

Provision
Dr Expense  123.00  
 Cr Provision  123.00

Once the expense for which a Reserve was made has been made, things get reversed. For example if the final cost of the fixed asset turned out to be 120 M USD two years later we get:

Dr Fixed asset 120. 00      # actual value of asset
 Cr Cash    120.00  # paid for in cash

Dr Reserve  123.00      # reversal  
 Cr Expense  123.00   # reversal 

The last transaction is increasing the total profit. Reserves (and provisions) decrease current Profit which means that if profit is high now, the decrease will yield less money to pay dividends from. Similar logic applies to provisions.

Note that provisions can be a liability account, or a contra-asset account. A contra-asset account is on the asset side (a Cr entry thus just reduces the value of the asset as one would expect).

Dividends
Dividends are not counted as an expense but as a reduction of Owner's Equity, specifically reduction in Retained Earnings. They do not appear in the Income Statement but in the Balance Sheet and Cash Flow Statement (if paid in Cash). Of the board approves a 500 dividend payment then record:
Dr Retained Earnings 500
  Cr Dividends payable 500

When payment takes place a month later:
Dr Dividends Payable 500
  Cr Cash        500

In which Retained Earnings is an Equity account and Dividends Payable is a liability account.

Retained Earnings
Retained Earnings were mentioned at the very start of this section, without any further explanation. Here, they are explained a bit more. Retained Earnings, is, as shown above an Equity Acccount type. In addition, it is also a concept, directly linked to that account: Retained Earnings are what the Venture 'Retains" after having collected all Revenues, paid out all Costs (including taxes) and paid out Dividend (listed companies) or Drawings (sole proprietor Venture). 
We know that Revenue is reflected in the Cash or Receivables accounts, Cost is reflected in Cash or Payables accounts. Dividends is reflected in Cash or Payables accounts. What is often confusing is the fact that Retained Earnings does not reflect Cash or is not 'held' in Cash account. An example will clarify this.
Assume a Venture has Assets = 1000 (of which Cash = 0, Buidlings = 1000) , Liabilities = 750  and Owner's Equity = 250.
Now at the start of the year we get:

Sales of a product
Dr Cash 150
 Cr Sales 150

The total value of Cash = 150

Purchase of an Asset
Dr Asset 75
 Cr Cash  75

The total value of Cash = 150 -75 = 75.

At the end of the Book Keeping Process and closing the accounts (no Dividends are paid and there were no Expenses):

Dr Sales 150
 Cr Retained Earnings 150

The Venture ends up with:
A =  1150 (1000 + 150 -75 + 75)
L = 750
OE = 400 (250 + 150).

Zoom in on Assets accounts:
Cash = 75
Equity = 400 of which Retained Earnings = 150.

Cash != Retained Earnings. The reason is that part of the Cash was transformed in another Asset. Retained Earnings reflect this what was retained by the company in some form of Asset (Cash, Receivables, Land, Property, Machines, etc). 

### Book Keeping Literature
A very good introduction to accounting can be found here: prj_world_of_finance_accounting_101_original.doc

Full details can be found in the following books:
Business Accounting - 1 - Frank Wood & Alan Sangster
Business Accounting - 2 - Frank Wood & Alan Sangster
________________________________________
## Financial Reporting
The three key documents to report in Financial Statements are Income Statement (IS), Balance Sheet (BS) and Statement of Cash Flow (CF). See also below examples. Details of each can be found in [STD: Investment # KEY FINANCIAL STATEMENT DEFINITIONS]. 

Between (...) are different terminologies for the same definition.

Manufacturer with tax and debt interest:
+ Sales (Revenue, Income)
 - COGS 
    --------------------
   Gross Income (Gross Profit)
 - Operating Expenses (Operating Costs) 
    - Rent
    - Salaries / Marketing / General Expenses
    - Amortisation
    - Depreciation
    --------------------
   Operating Income (Operating Profit)
 - Interest
 - Taxes
    --------------------
   Net Income (Earnings, Net Profit)

In addition to the 3 key documents in the Financial Statement, Key Performance Indicators are calculated as follows:

### ROE
Return on Equity 

### RORWA
Return on Risk Weighted Assets.

### ROA
Return on Assets 
________________________________________
## Managerial Accounting (Framework)
Managerial Accounting provides information about the Revenue generated by the sales of Services and the Cost of delivering said Services, and thus whether a Service is profitable. It also provides information whether to invest in a new business initiative, and how to budget. It compares actual performance to planned performance and facilitates many other important decisions critical to the success of a Venture.

There are various components involved:
- Revenue Measurement
- Cost Measurement
- Budgeting

These aspects are detailed below.
________________________________________
## Revenue Measurement (Framework)
@@@

### Revenue Clasification
There are various sources of Revenue.

#### Sales Revenue vs Service Revenue
Sales Revenue is the Revenue as a result of the sale of products (manufacturing Ventures). Service Revenue is the Revenue from the sale of Services Provided (service Ventures like banks)

#### Operating vs Non-Operating Revenue
Operating Revenue is the Revenue from the core Activities of a Venture i.e. Revenues linked to Services offered (Products sold) directly linked to the Mission.
Non-operating Revenue are those Revenues from Services offered (Products sold) but that are not  core to the Venture. 

#### Interest Revenue vs Fee Revenue
This is key for financial institutions. They get Revenue from Interest on loans and or Fees charged on services e.g. brokerage. Fee Revenue is also referred to as Non-interest income. 

NB: in investment banking, the classification of specific types of profit and loss of trading activities is called income atribution.
________________________________________
## Cost Measurement (Framework)

### Cost Classification
Costs can be divided into several types of buckets:

#### Fixed vs Variable Costs vs Mixed Costs
Fixed Costs remain *same in total* but *changes per unit* e.g. monthly rent , monthly salary, .... Note this is true on short term, but for longer time periods fixed costs also change.
Variable Costs remain *same per unit*, but *changes per total* e.g. hourly workers, sales commission. In other words, Variable Costs scale to the Output of the Activity.
Mixed costs are a mix between the above two: it has a fixed costs upto a certain level of output of the Activity and then increases as output increases. 

#### Direct vs Indirect Costs
Direct Costs can be traced directly to an Objective, or even Process. In financial statements they appear as Cost of Goods Sold (COGS) or Cost of Sales (COS) if it concerns a Service company. They include:
- Direct Materials (manufacturing)
- Direct Labor (manufacturing, service)
- Fees (service)

Indirect Costs, are those costs not directly related to a specific Service or Product. In Financial Statements they appear as SGA (Selling, General and Administrative). Such costs often need to be allocated to the revenue generating Activities such as to create a complete picture of Profit. Indirect Costs include:
- Overhead Costs
    - Selling Expenses
    - Administrative Expenses
- Period Costs
    - Salary of IT department employees

#### Controllable vs Non-controllable Costs
Controllable costs are those costs a Manager can control. Non-controllable costs cannot be controlled i.e. the manner in which costs are allocated to the department if forced by the company.

#### Differential Costs vs Sunk Costs
Differential costs represent the difference between two alternatives including opportunity costs which are what you give up by choosing another alternative. Sunk costs are not relevant for decision making as they cannot be recovered at a later date.

#### Running Costs vs Change Costs
Another way of looking at Costs is to focus on those required for the Run to be maintained, vs those required to Change the Run. The former are Cojsts involved in Routines, and the latter are Costs involved in Projects. 

#### Observations
Depending on the venture, names may be different. For example, Direct Costs, may be defined as Costs that are under the Direct Control of an Activity, rather than Directly related to a Service or Process. This in turn may be the consequence of corporate policies to allocate certain costs to certain Activities.

### Cost Calculation
In addition to classifying Costs, one has to quantify them such that they assist managers in Planning.

#### CVP
The Cost-Volume-Profit analysis links the effect of output of an Activity to Revenue and Costs through a linear equation: P = n(R - C) - F 

in which:
P = Profit
n = nr units
R = Revenue per unit
C = Cost per unit
F = Fixed cost
R - C = Contribution Margin
This allows calculating the breakeven i.e. the level of units produced where profit = 0. This model also can be used to calculate the required nr units to be produced for a given net Profit. 
________________________________________
## Cost Allocation (Framework)
@@@ https://courses.lumenlearning.com/managacct/chapter/allocation-of-service-department-costs/
________________________________________
## Budgeting (Framework)
There exist various budgets. The most relevant ones are *Operational Budget* and *Financial Budget*, which combined are the *Master Budget*. All budgets tie in to the RPT, see [## RPT]. Note that all Budgets are for a certain future Period.

The Operating Budget helps plan future Earnings and Costs and results in a *Projected Income Statement*. The Financial Budget helps plan the financing of Assets and Liabilities and results in a *Projected Balance Sheet*.  

### Operating Budget
From a high level, Operating Budget considers:
1. Goals and underlying Objectives
2. Resources involved in 1: Staff, Assets, Suppliers

Goals express what Services (or Products) are going to be delivered to Clients. Services yield Revenue.
Objectives explain how the Goals are achieved through the use of Resources. More specifically they explain how Staff use Assets and Suppliers to deliver Services. Resources in turn generate Cost and Risk (a potential future Cost).

By understanding how Services yield Revenues and how Operations generate Cost, a Budget can be made. Budgets are interactively used in Planning: a plan which decides Goals and underlying Objectives may need to be adjusted to accomodate budget and vice versa , the Planning drives the sources of Revenue and Cost.

#### Operating Budget Process
- Define Run Goals, yielding
    - Services and thus Revenue
- Define Change Goals: yielding
    - New or Changed Services and thus Revenue
- Define Routines: yielding
    - Staff requirements
    - Supplier requirements
    - Asset requirements
- Define Projects: yielding
    - Staff requirements
    - Supplier requirements
    - Asset requirements
 
When making a Budget, the term *Projection* is often used. A Projection is an estimate or forecast of a future situation based on a present trend.

There are several Projections m for the next Period:
- Quantifiable measure of Run Services 
- Quantifiable measure of Run Revenues 

@@@
- Determination of dependency between Services and Assets, Suppliers and Staff 
@@@

#### Operating Budet Quick and Dirty
In established businesses where there is little change (be that growth or decline), a safe bet for a big part of the Budget is to assume that next period is closely related to the previous period. More specifically:
- Assume the Run remains unchanged
- Assume the only difference comes from Change

In this simplified approach the budget is composed of two seperate elements:
- Run Budget: deemed the same as previous period
- Change Budget: determined based on initiatives for the next period.

In effect this approach looks mostly at anticipated delta of the next period versus the previous period.


*********************************************
# HUMAN RESOURCES
Human Resources involves Processes to *assure skillful Staff is recruited, kept skilled and retained*. 
There is a dedicated note: [MGT: 52.HR].
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Human Resources]. On L2 are the Tools:
- Skill Management
    - Skill Review
- Recruitment
    - Interview
    - Candidacy Rejection
- Training
- Performance Management
    - Performance Target
    - Performance Evaluation
    - Performance Review
- Remuneration
    - Promotion 
    - Remuneration
- Employee Relations
- Employment Law
________________________________________
## Skill Review (Framework)
Skill Review is a framework that helps in defining and measuring Skills. This framework has similar features as the Performance Review framework (see below).

See also the following source: 
<https://www.valamis.com/hub/hard-skills-vs-soft-skills>
<https://www.valamis.com/hub/skills-matrix>

A Skill Review does not follow a rigid Process. However, there is a framework facilitating the Process and which involves the following:
- Skill Categories
- Skill Rating
- Skill Target
- Skill Result
- Skill Context
- Skill Template

### Skill Categories
Skills can be grouped in various categories. There is no accepted consensus for the best type of grouping. This framework uses a binary grouping.

#### Soft Skills
These are subjective Skills that are hard to quantify. They are also known as *people skills* or *interpersonal skills*. Soft-skills are often developed over a longer time, sometimes from a very young age. Soft Skills are some of the most important skills underpinning good Management. Many of below soft skills have dependencies on each other:   
- Communication: ability to convey and share ideas effectively to a wide range of stakeholders
- Flexibility: ability to accept new challenges calmly and without restraint
- Leadership: ability to help oversee Activities, guide initiatives and steer Staff toward the achievement of Goals through Leading
- Motivation: ability to keep going even in the face of setbacks
- Multitasking: ability to manage different Objectives efficiently by prioritising them 
- Problem Solving: ability to analyse a problem efficiently to create a solution, including breaking up larger problems in smaller ones
- Teamwork: ability to cooperate with others and build relationships
- Time Management: ability to plan different tasks and track them such that they complete at the expected time 
- Self-learner: ability to teach oneself new topics by finding and using relevant sources of information adequate for that topic
- Self-critical: ability to question oneself to improve the quality of one's output and to increase one's understanding of relevant topics 
- Self-starter: ability to see tasks requiring to be done and start working on them without being asked by someone else to do so
- Analytical: ability to collect, process and transform Data (records of fact) into Information (interpretation of facts) relevant to a topic 
- Strategical: ability to identify potential and actual Opportunities that grow Revenue and/or reduce Cost and/or reduce Risk under the constraints of potential and actual Threats given actual or perceived Strengths and Weaknesses of the Venture. 

#### Hard Skills
Hard Skills are teachable abilities that are easy to quantify. They are taught and acquired through books, classroom sessions, internet, but also on the job. Hard Skills are often but not always knowledge based. Hard skills can be recognised through diplomas and certificates. They include:
- Foreign Languages
- Programming Languages
- IT Systems 
- Mathematics
- Accounting 
- Trading
- Data Science
- Project Management 
- Marketing
- Use of Venture specific Assets
- Use of Venture specific Processes
- Etc

### Skill Rating
Skill can be rated using a quantitative scale based on a qualitative assessment of knowledge and/or experience. The qualitative assessment looks at the *amount of work that can that be done* without referring to a *Specialist* be that within the Venture or outside i.e. books, websites. etc. The Skill Rating is very similar to the Performance Rating (see below). 
- 0: none:     0%, no work done
- 1: little:     20%, little work done
- 2: some:  40%, some work done
- 3: much:   60%, much of the work done 
- 4: most:    80%, most work done ==> target 
- 5: full:     100%, all work done, teach others 
- 6: extra: >100% rarely observed, Staff is a contributor to the Skill i.e. the Staff expands the Skill scope inside or outside of the Venture.

### Skill Target
For each Skill there are three numbers. 

Target:Rating:Result

in which Target is the desired level of Skill, Rating is the actual Observation and Result is the numerical Difference between the two i.e.  Result = Rating - Target 

Unlike Performance Rating (see below), the target for Skill Rating is in most cases set at 4 i.e. 80%. This is because in the majority of Ventures, a broad based Skill set is more important than a deep Skill set. Although having both is ideal, it may not be attainable. However, for certain Job Descriptions a rating of 5 is necessary. For example, a developer for Python software should be closer to a Rating of 5 than a rating 4.  

### Skill Result
Skill Results can be remapped as follows:
Result =  0  ==>  At expectations
Result =  1  ==>  Above expectations
Result >  1  ==>  Exceed expectations
Result = -1  ==>  Below expectations
Result < -1  ==>  Far below expectations

### Skill Context
Different companies use different methods of Skill Management. The framework provided here may need to be tuned to such existing frameworks. However, in absence of a formalised framework, this framework should be used as much as possible.

### Skill Template
Skills should be formalised in a manner that is coherent for a Venture. The best known formalisation is JD or Job Description (see above), and the framework provided in this section permits structuring the Skills section on the Job Description. 
________________________________________
## Interview (Framework)
The following are guidelines for performing an interview.

### Preparation
Read the CV and for every entry in it assess aspects like:
- Scope of responsibilities
- Scope of products/clients
- Examples of what/how/where etc when a statement is made e.g. "I otpimised...", "Worked with XXX to deliver YYY"
________________________________________
## Candidacy Rejection
When a candidate postulates for a job, he is likekly not going to be accepted (only a few make it to an interview based on CV / motivation letter or cover letter).
Once a decision has been made to not proceed with a candidacy, the candidate needs to be informed. This should be done in writing (mail, paper, either). The content of the rejection letter should be as follows:
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 
Dear xxx,
Thank you for taking the time to consider this role. Our hiring team reviewed your application and we'd like to inform you that we are unable to advance you to the next round at this stage. 
We are looking for profiles that have more experience in the specific business division this role functions in. 
Best Regards,
yyy
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 
Dear xxx,
Thank you for taking the time to consider this role. After review of your CV and our first interview, we'd like to inform you that we are unable to advance you to the next round at this stage. 
We are looking for profiles that have more experience in the specific business division this role functions in. 
Best Regards,
yyy
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 
________________________________________
## Training (Framework)
@@@ internal, external, formal, informal, link to mentoring
________________________________________
## Performance Target
Defining the target of Objectives for a Staff is composed of the following:
- Understanding the Venture's Mission
- Understanding the Venture's Goals (Run and Change)
- Understanding the Venture's Objectives broken down by Routines (Run) and Projects (Change)
- Understanding the Job Description

NB: the above can also be reviewed in light of the Group the Staff belongs too, i/o of the Venture.

The manager is responsible for making sure Staff knows what their role is through the Job Description.

The following needs to be enumerated throughout the Performance Target for each Staff:
- List of Routines the Staff is responsible for (this establishes the Run part of the Venture for the Staff)
- List of Goals the Venture is trying to achieve
________________________________________
## Performance Evaluation (Framework)
There are various methods in which Performance can be evaluated. These are called evaluation methodologies or appraisal methodologies. Each has pros and cons, and none is specifically recommended.

### 90-degree
These type of appraisal is with the direct manager. This is the type of appraisal done in most companies.

### 180-degree
These type of appraisals are between Staff carrying out the same Activities and can include the Manager.

### 270-degree
This uses a broader range of reviewers: Manager, regular colleagues (Staff) and peers (Suppliers within the organisation). 

### 360-degree
The 360 degree appraisal or 360 feedback is an often used method in which manager, colleagues, collaborators (outside the team), Partners/Suppliers, subordinates and Clients all provide input. 
NB: the 360 feedback has become somewhat of a fad in many companies and care should be taken not to overindulge in it. 
________________________________________
## Performance Review  (Framework)
Performance Review looks at how Staff worked towards achieving the Objectives, see also [## Objectives]. The review focuses on *Staff* Skills and behaviour, as opposed to the *Process and Result* aspects of Objectives that is measured through the Management Function Controlling. 
A Performance Review looks across the various dimensions of a Venture, from strategic levels like Misson Statement and Goals to more operational levels of Objectives and Processes. 

A Performance Reviews does not follow a rigid Process. However, there is a framework facilitating the Process which involves the following:
- Corporate Title
- Performance Categories
- Performance Rating
- Performance Target
- Performance Result
- Performance Context
- Performance Template

### Corporate Title
Corporate title is an indicator of seniority and implies expected knowledge, skills and behaviour. There are many types of corporate title. In banks for example the following exist: 
- Analyst
- Associate
- VP
- Director
- Managing Director

Corporate Titles can have sub-levels like Senior Vice President etc. The Director title may be reserved for a member of the board (Board of Directors) which is not strictly speaking a corporate title in that case. For this framework for Performance Review the five levels above will be used. If other titles or different number of levels are used then they can be  implemented by extrapolation of the above.

Although knowledge is important, the focus is mostly on skills related to the acquisition, and use, of knowledge as well as behaviours in relation to interaction with colleagues and Suppliers such as to achieve the Objectives. 

### Performance Categories
Performance Categories refer to the various aspects of behaviour involved in achieving Objectives. There are three Performance Categories:
- Dependability
- Proactivity
- Leadership

Other categories are possiblez but the above three cover the broadest range of behaviours as explained below:

#### Dependability
Deliver Objectives (Routines and Projects) on time. Dependability focuses on *What*, *When* and *How* to complete assigned, and thus known Objectives and their underlying Processes. It is what most people have in mind when asked to review a Staff's performance. Dependability relates to the Staff's *competency* which is the ability to carry out Processes effectively, autonomously and timely to yield the expected Result and includes the capacity to: 
- Adhere to the notion of "See the work", defined as "Identifying and following up on a need for effort to help others or oneself to complete a task without having to be told". It is a catchall and may not even be related to Objectives e.g. lifting a glass from a table when someone else cleans the table. It is a mindset thing!
- Act autonomously, which includes knowing which Objectives to own based on Job Description as well as which Processes are involved and need to be executed how and when.
- Take decisions in line with the authority granted with the Staff's role, as formalised in the Job Description.
- Understand Objectives and Processes involved to achieve them as well as the deadlines related to them.
- Understand and consider dependencies on Resources (Assets, Staff and Suppliers) and other Processes (performed by oneself or someone else).
- Plan work according to deadlines, expected Processing time and dependencies.
- Prioritise Objectives according to urgency, quick wins and short/long term priorities, and readjust priorities dynamically based on circumstances.
- Be analytical and pragmatic when assessing information
- Ask the right questions to the right person.
- Break down complex Objectives in simpler ones.
- Escalate problems arising in completing an Objective.

#### Pro-activity
Act entrepreneurial i.e., self-initiate Objectives and (Sub-)Goals. Pro-activity focuses on *missing*, *ineffective* or *inefficient* Objectives i.e., parts of the Venture's Goals that are not met with existing Objectives and includes the capacity to:
- See the bigger picture, being able to zoom-out of Objectives and seeing how Objectives feed into Goals and Goals into the Mission and thus the Venture's overall result.
- Have a strong focus on the Mission and Goals rather than Objectives alone.
- Understand if the Mission is only partially met and why
- Understand which Goals are missing/incomplete such that the Mission would be fully met.
- Define missing Goals including targeted Result.
- Understand Goals of the Venture and how underlying existing Objectives align to that Goal, including Objectives that are not covered by him/her.
- Understand which Goals are partially or not met and why
- Understand which Objectives are missing/incomplete such that those Goals would be fully met.
- Define/re-define missing/incomplete Objectives including Result, Processes involved, dependencies on other Processes and Resources (Assets, Staff, Suppliers). 

#### Leadership
Use leadership principles to initiate new Goals and Objectives as well as to complete existing Objectives more efficiently. Leadership focuses on with *whom* to achieve Objectives and includes the capacity to:
- Drive and motivate others i.e. Peers, Suppliers (internal and external) to achieve one's own Objectives
- Listen to others both to improve Results, but also to understand concerns and constraints.
- Understand that Skilled staff can still underperform due to reasons unrelated to the Process they perform i.e., due to Corporate culture, personal circumstances, etc.
- Always approach with "How can I help?'
- Expect different Stakeholders to need a different manner of answers for the same question.
- Work with others in the understanding that achieving Goals and Objectives are of common interests.
- Delegate part or whole of Objectives.
- Use meetings (1:1 Meeting, Team Meeting) effectively 
- Use Communication means effectively (Mail, Chat, face to face).
- Use Feedback to grow others (give feedback) and oneself (collect feedback).
- Understand, respect and use people's natural resistance to change.
- Work towards Psychological Safety.
- Act as a Mentor.
- Act as a Coach.
- Report, unsolicited, on progress to relevant Stakeholders.

Note that Objectives are deemed allocated to the right level of Seniority, see [### Corporate Title] e.g., someone very junior will not be given Objectives that require a very high level of Dependability. On the other hand, the three Categories are defined such that in theory any Objective can be allocated to any level of seniority. The reason is that the Performance Rating System is designed such that at low seniority levels, the Performance Targets are low, see below.

### Performance Rating
Performance Rating uses the notion of Observation of behaviour. This can be done by oneself and/or by others. Feedback from others assists in a more complete Observation. Observation means that:
a) There was an opportunity for that behavior to be displayed; *and* 
b) The Staff indeed displayed it; *and*
c) Someone was there to actually observe that behaviour.

Numeric ratings are used to establish the level of Observation within a Performance Category:
- 0: none:       0%, never observed 
- 1: little:      20%, sometimes observed
- 2: some:    40%, frequently observed
- 3: often:     60%, often observed   
- 4: mostly:  80%, very often observed 
- 5: fully:     100%, always observed ==> target 
- 6: extra: >100% rarely observed    ==> exceptional situation 

NB:100% is very difficult: most often there is some scenario where a Performance Category is not observed. Those cases should be exceptional and as such a Rating of 5 can still be given. Therefore, practically speaking rating 5 can be given for anything above 90%. The rating 6 is used only to be able to rate when a Managing Director outperforms the Target Rating.

Observation quality should also be considered. If someone observes something only once then that has less value versus someone observing the desired and/or the reverse of it, several times. Low Observation rates may need to be discarded. Managers having little interaction with Staff are less likely to see sufficient behaviours to have a good opinion, which is why they can and should rely on observations by others.

By design, the above method relies on observation by oneself or others. Observing such behavior is affirmative, but that does not mean that the Staff had an opportunity to display that behavior but did not. It might just have been missed because nobody was around to Observe it. As such the method is slightly biased towards positive outcomes, and is also at best a reflection of a reality, not an actual reality.

### Performance Targets
For each Corporate Title and for each Performance Category there are three numbers as follows: 

Target:Rating:Result

in which Target is the desired level of Observations, Rating is the actual Observation and Result is the numerical Difference between the two i.e. Result = Rating - Target 

Below is the template to measure performance using the concepts discussed above.

#### Analyst
- Dependability: 2:Rating:Result 
- Pro-activity:     1:Rating:Result
- Leadership:     1:Rating:Result

#### Associate
- Dependability: 3:Rating:Result 
- Pro-activity:     2:Rating:Result
- Leadership:     2:Rating:Result

#### Vice President
- Dependability: 4:Rating:Result 
- Pro-activity:     3:Rating:Result
- Leadership:     3:Rating:Result

#### Director
- Dependability: 5:Rating:Result 
- Pro-activity:     4:Rating:Result
- Leadership:     4:Rating:Result

#### Managing Director
- Dependability: 5:Rating:Result 
- Pro-activity:     5:Rating:Result
- Leadership:     5:Rating:Result

These ratings are rigid and don't take into account the longevity *within* a role/corporate title. It is up to the Manager to adjust where deemed relevant. Half ratings like 2.5 can be used where necessary.

Structurally, the higher the Corporate Title the higher the Target Rating and the harder it becomes to outperform. 

### Performance Result
Performance Result can be remapped to qualitative labels like for example as per below:
Performance Result =  0  ==>  At expectations
Performance Result =  1  ==>  Above expectations
Performance Result >  1  ==>  Exceed expectations
Performance Result = -1  ==>  Below expectations
Performance Result < -1  ==>  Far below expectations

### Performance Context
Different companies have various manners of grouping Staff's Objectives. Often the following groupings are used:
- Job Description, Run Objectives, Day-to-day etc
- Operational Objectives, Change Objectives, etc.
- Behaviour, Attitude, etc.

The Performance Categories do not map directly to these and in most cases work across such groupings. One way of forcing a  mapping on such categories is as follows:
- Job Description, Run, Day-to-day, etc <-> Dependability 
- Operational Objectives, Change, etc <-> Proactivity 
- Behavioral Objectives, Attitude, etc. <-> Leadership

### Performance Template
When reporting on the assessment of performance for a Staff the following sections are suggested:
- Context: Corporate Title, time in current role, scope, constraints, sub-team part of, key Suppliers, etc.
- Run: Routines owned by Staff.
- Change: Projects owned by Staff including ad-hoc Projects
- Assessment: details of assessment including the Performance Categories with Target, Rating, Result and a description as to why those ratings were given as well as an action plan to remediate if relevant.
- Methodology: description of Performance Review framework as described here.
________________________________________
## Promotion (Framework)
Promotion ties in to the Performance Evaluation and Performance Review frameworks. Promotion is a form of remuneration and a signal that the Staff's current performance is at the next Performance Target level. 

It is not necessary to promote a Staff right away when the Performance Result > 0 . In general such over performance should be sustained over a period. In addition qualitative measures can come into play, as well as corporate rules on promotions which can include specific training programs, interviews with senior managers, etc.
________________________________________
## Remuneration (Framework)
Remuneration is what Staff get in exchange for the contribution to the Venture. This section will not effectively give a Framework of what to do or even how to price, but more a Framework to understand what is involved in Remuneration. A detailed analysis can be found in the URL below. The various aspects related  to Remuneration are discussed below. 

### Base Salary 
The Base Salary includes Salary based on a monthly pay, and Wages which is based on a hourly rate and links to the hours worked by the Staff.

### Variable pay
Variable pay a.k.a. bonus depends on performance, see [## Performance Review]. This can also include incentives, although the intent of the latter is more to give an 'incentive' to stay with the company long term.

### Flexible benefits  
Flexible benefits, a.k.a. Benefits in kind are benefits that are not monetary (and thus not taxed!). There are various options e.g.:
- Company car
- Health Insurance
- Vouchers (restaurant, childcare, etc.)
- Pension plans
- Transport subsidies

### URL
<https://www.kenjo.io/hr-remuneration-guide>
NB: very Euro focussed, but gives good insight.


*********************************************
# PROCUREMENT 
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Procurement]. On L2 are the Tools:


*********************************************
# MARKETING
Marketing is the Business Function  of exploring, creating, and delivering value to meet the needs of a target market in terms of goods and services.

There are two approaches to it: inside out (the 4 P), outside in (the 4Cs). They are very similar and are reflected here each time in conjunction.
________________________________________
## Overview
This overview shows on L1 key deliverables as per [MGT: 99.Legend ## Marketing]. On L2 are the Tools:
- Product / Client
    - Client Segmentation
    - Product Specification
- Price / Cost
    - @@@
- Place / Convenience
- Promotion / Communication
________________________________________
## Client Segmentation (Framework)
Client Segmentation ties into the Business Model, see [## Business Model Design].

### Classification
There are various axis to segment clients against. The following are not exhuastive but recurring:
- Geographic: country, region, town, rural, urban 
- Psychographic: lifestyle traits (tech savvy, gamers, sporty, party goeretc), or personality traits
- Demographic: age, gender, socio-economic class, education. 
- Life-cycle or generation: baby-boomer, GenX, Gen Y (Millenial), Gen Z,
 - Behavioural: brand loyalty

### DAMP
Ascertain whether a segment is worth the invesment. The following determines whether a segment can be:
- Discernable: differentiated from other segments.
- Accessible: be accessed via Promotion?
- Measurable: quantified and its size determined?
- Profitable: yield a sufficient ROI?


*********************************************
# VERSIONS
Versions are using yyyymmdd. Each version has a level 3 header. Future improvements are recorded in [### Planned]. Once an actual date is put in a header the version is deemed released.
________________________________________
## List of Versions

### 20230322
First implementation of versions. Inserted the Job Description Definition from the original [MGT: 99.Tools-JD-template], where it was deleted, and instead refers to the definition in this note. 

### 20230403
Updated  [### BuJo MSS Reference] with Staff and Suppliers. 

### 20230414
- Updated [### How to Use] in [## Operating Model Definition]

### 20230501
- Updated [## Operating Model Definition] with clearer guidelines and fact that sections can be omitted

### 20230506
- Updates in [# GENERAL] and [# BASELINE]: clean up and some additions. 

### 20230520
- Added [## Whiteboard Sessions]

### 20230610
- Deleted [# GENERAL] and moved the hierachy from that section to [MGT: 99.Legend ## Tools].

### 20230611
- Cleaned out all Appendices which were already deleted from MGT: 99.Legend

### 20230614
- Added Run Sub-Goals for prd, ovs and ovh in [### Sub-Goals]

### 20230624
- Updated [## MC] w/r to the various initiating steps

### 20230712
- Updated [## Objective Notation],  [## Task Notation] with addition of #Hashtag in name being allowed, clarified the differences between Task and Objective Notation. 

### 20230719
- Updated [## Objective Notation],  [## Task Notation] with addition of Task Notation *within* the Reference Indicator including multiple Tasks using '&&'.

### 20230923
- Updated [## Operating Model] to reflect the Naming Convention of Operating Model notes. 

### 20230924
- Renumbered MGT: 99.Tools to MGT: 80.Tools and applied throughout all notes

### 20230930
- Updated [# MANAGEMENT] in line with [MGT: 99.Legend]

### 20231216
- Added [## Check Standards], [## Self-Contained Mail]

### 20231227
- Added Oversight Support and expanded on Production Support in [### Sub-Goals].

### 20240107
- Added reference to the public domain github page

### 20240131
- Added Operations, Staff, Assets, Suppliers, Liabilities, Equity
- Added [## Data & Info] under [# ASSETS]

### 20240211
- Update various sections in line with changes made in [MGT: 99.Legend]

### 20240725
- Updated  [## Performance Review] with some new criteria under the Performance Categories.

### 20241109
- Added [# DISCLAIMER]
- Updated [## Eisenhower Matrix] with more details
- Added [## Articles of Association] and [## Memorandum of Association]

### 20250105
- Corrected small typos

### 20250601
- Overhaul of [## Committee]
- Addition of [## Control Conundrum]

### Planned

