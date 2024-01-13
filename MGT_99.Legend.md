*********************************************
# INTRODUCTION
This note acts as the legend, or explanation, of the *Management Framework* a.k.a. *MF*, an intertwined set of concepts and conventions for the purpose of Managing a *Venture*, see section PROFILE below.

The MF is composed of two notes: this note, MGT: 99.Legend. The first one explains overall concepts, whereas the second one focuses on the application of those concepts through so called *Tools*, see also section PROFILE below. 

This note can be used for *perso* (personal) and *work* (professional) context. Conventions are such that, except for specific differences, they apply to both contexts. References to *notes* imply notes in the context used. Although this note *can* be used in both contexts, it has most value in a work context, and the remainder of the note is written from that perspective. 

This note has the following sections:
- Introduction 
- License
- Notes
- Profile
- Index
- Legend Explained
- Special Symbols
- Versions

A *section* is the same as a chapter in text books at any level e.g. 1 Chapter, 1.2 Sub chapter, 1.2.1 Sub-sub chapter, etc. The words 'note' and 'section' are common enough not to require a definition nor the use of a capitalised first letter, which denotes a word defined elsewhere.

The various conventions used in this note like [# NOTES] and [MGT: Planning] as well as formatting like *italic* and **bold** are explained in [## Note Reference] and [##  Note Content] below.

Frameworks, procedure and software specific aspects in relation to the Management Framework are discussed in a separate note MGT: 80.Tools.

An audit trail of changes is in [# VERSIONS]. 

This note is available in the public domain on GitHub in the following location: https://github.com/stelzinga/MF


*********************************************
# LICENSE
The notes MGT: 99.Legend and MGT: 80.Tools ("The Notes") are licensed under a Creative Commons Attribution -NonCommercial-ShareAlike 4.0 International License. 
Software implementations referenced in the note MGT: 80.Tools are licensed under a GPL 4.0 License. Both licenses are explained  below.

When using specific sections of the Management Framework, the summary below should be referenced.
________________________________________
## Attribution-ShareAlike 4.0 International 
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
________________________________________
## GNU Public License 3.0
Copyright (c) 2022 Sander Elzinga, sander.elzinga@gmail.com
 
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
 
You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.


*********************************************
# NOTES
Notes are any form of document capturing data for any relevant topic or series of topics. The Management Framework is maintained within notes, and the conventions used has been formalised in this section. Understanding this section helps better understand all other parts of the Management Framework but it is not a prerequisite as ultimately the conventions uses are rather intuitive.
________________________________________
## Note Name Format
Notes have names that they can be referred by. There are many manners to name name notes. The one used here is the following:

CAT: Des

in which:  
CAT Note Category, all caps  
Des  Note Description  

Note that the colon is followed by a single space. Details of these items are found in the sections below.

Examples: MGT: 99.Legend, PRD: Workout

This format has the advantage that the note is more structured, which in turn helps with grouping notes together. If a note is stored as a file, then the name of the file won't allow the colon, Instead it should be replaced with a '_'. 
________________________________________
## Note Category
In this Management Framework, Note Categories are based on *Goals* applicable to a Venture, see [## Goals]. This means that Goals should be shortened to three character codes. 
The reason to use three characters is both practical (instead of making long note names , they remain short) and aesthetic (always three characters better shows the group categories and thus the entire note structure). 

There are two default categories:
1. 'MGT' which as a category is also a Goal and 
2. '_TP' which is a temporary category that can be used for anything that is not an actual Goal. The underscore is just to assure it appears at the top of  the list of notes. 
________________________________________
## Note Description
The Note Description explains the *purpose* of the note. Ideally, it should be one word. If it is only possible to explain the purpose with several words then use '-' *hyphen* or '_' *underscore* to link them into one. In other words, there should not be any white space (space, tab).
________________________________________
## Note Content

### Sections
Notes are composed of sections (same as chapters). Sections can be numbered, but often are not. They do have a hierarchy: level 1, 2, 3, 4, 5 and 6 or short L1, L2, L3, etc. Section format and level is determined by *Markdown* header conventions, see below. Important: if a section level N exists then there should be a section N-1, i.e. if there is an L3 in an L1 then there should be an L2.

### Markdown
Section text is written using Markdown protocol. See following websites:  
<https://wilsonmar.github.io/markdown-text-for-github-from-html>  
<https://www.markdownguide.org>  
<https://gist.github.com/VEnis/7465176>  
<https://pandao.github.io/editor.md/en.html> -> allows testing Markdown  
<https://dillinger.io> -> allows testing Markdown  

Markdown is essentially a protocol to write text in a manner that when used in a Markdown editor or viewer it will yield an output that is user friendly to read (HTML-like), yet without a Markdown editor the raw text a.k.a. plain text still clearly shows sections, bulleted lists, etc.

This text is available in the public domain in Git and will display in Markdown format!

Markdown has two forms:
- Standard Markdown
- Extended Markdown

Both forms use the *.md file extension and are discussed below, including conventions within this notes framework.

### Standard Markdown
Standard Markdown is the most used form of Markdown and the fast majority of notes is in Standard Markdown.

#### Escape Character
In below examples, the Markdown protocol is used. If that would be used in a markdown editor it will show the Markdown output, instead of how that output is achieved. For those cases, the 'plain text' version is also shown by using the escape character '/', 

#### New Line
To achieve a new line in Markdown, type two spaces and a carrier return.  
This is sentence followed by two spaces and a carrier return.  
  
This is a sentence that follows an empty line with two spaces and a carrier return (i.e. follows an empty line).

#### Horizontal Lines
3x '*' or 3x '-' or 3x '_' creates a horizontal line in Markdown output.
Use these to create H1, H2 level separators as follows: 
- H1 Separator = 45x '*' preceded by 2x newline
- H2 Separator = 40x '_'  preceded by 0x newline

Block creation: 2xH1 separator above and below capitalised block name. Used in very long notes.

#### Header Labels
Header labels are created with one or more '#'.
Use these to create H1, H2 level captions:
- H1: # ALL CAPS 
- H2: ## First Letters Capitalised 
- H3: ### First Letters Capitalised
- H4: #### First Letters Capitalised
- H5: ##### First Letters Capitalised
- H6: ###### First Letters Capitalised

Header L1-2 are preceded by horizontal lines (see above). Header L3-6 are all preceded by one newline. If the subject of a L2-6 header is an acronym then all caps are permitted e.g. SWOT.

Once in a Markdown compatible editor/viewer the '#' will not be visible, and it is the formatting of font size (bold, bigger) that will determine the level of the Header. This means it is not always easy to differentiate between L2 or L3. This is also one of the reasons why L1 and L2 are preceded by '******' and '_____' respectively. 

Another consequence is that references to other sections (see below) are valid, but not always clear e.g. the reference [### Some Section] would show up in Markdown Editor like that, but the section it refers to would show up with the same name in the format of H3 mentioned above i.e., bolder format and larger font size and without the ###.

#### Formatting
Text formatting is as follows:
- Type:  *italic text*  OR  _italic text_  (plain text /*italic text/*/ OR /_italic text/_
- Type:  **bold text**  OR  __bold text__
- Type:  ***bold italic text*** 
 
#### Lists
For unordered lists use '-', '+' or '*'.
- bulleted list item 1
- bulleted list item 2
    - Add 4x <space> to indent bulleted item 2.1
    - Add 4x <space> to indent bulleted item 2.2
- bulleted list item 3

* bulleted list item 1, different format, same result
* bulleted list item 2, different format, same result
 
+ bulleted list item 1, different format, same result
+ bulleted list item 2, different format, same result

For ordered lists use 1., 2. etc.
1. Numbered list item 1
2. Numbered list item 2
    - Add 4x <space> to indent bulleted item 2.1
    - Add 4x <space> to indent bulleted item 2.2
3. Numbered list item 3  
NB : some Markdown converters support 1) i/o '1.' but not all do, so stick to using the dot e.g., '1.'
A. or i. do not always work as numbered items. 

#### URLs
For Internet URL's use:
Insert links: [Name](http://www.google.com)
Insert links: <https://www.google.com>
The latter link version shows the URL as the link name. The former shows the link name as 'Name'.

#### Images
Insert images: ![image name](/file/path/image.jpg)

#### Newlines 
Sentence 1. ==> add two spaces before <newline>
Sentence 2. ==> add two spaces before <newline>
  ==> add <newline>
Start of second paragraph.

### Extended Markdown
Extended Markdown supports fenced code blocks.
This allows writing chunks of code without needing to use 4x space. To create a fenced code block use 3x ` (back tick) at start and end of the code block.

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
@ (but is used in Github, so: avoid)

### Word Capitalisation
Words that start with a capital, like 'Planning' have been defined in this note or in [MGT: 80.Tools].

### Markdown in other Editors
Some editors, like OneNote, Outlook mail, use some of Markdown features albeit it different: *italic* in Markdown will show *italic* entirely  in bold (and it will keep  the two '*' .

### Triple @
A special convention is triple @ or '@@@'. This notation reflects that more information is still to be written but currently not available. The combo is easy to use in searches as no text uses a triple @.
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
8. Etc

### Section or Note
For a Section or Note there are three references:
[# SEC]                   -> refers to section L1 SEC in same note
[CAT: Des]             -> refers to a note CAT: Des
[CAT: Des # SEC] -> refers to a section L1 SEC in note CAT: Des

e.g. [MGT: 99.Legend ## Note Reference] which is this section you are reading.

In addition to the above it is possible to have references like [# SEC1 ## Sec 2] which explicitly refers to L2 Section 'Sec2' *in* L1 Section 'SEC1' 

In notes it is possible to use such references by explicitly using the words 'section(s)' or 'note(s)' in front of, or behind the item. e.g. "... section ## Routines in section # OBJECTIVES in note MGT: Planning ..."

### File
For a file the Note Reference is [File Reference] in which File Reference is either a full path to a file or directory or a shorter version of such path. File References are operating system specific. 

Examples:
$HOME/data_private/mgt/51.finance/       (Linux)
$HOME/utils/scripts/ubu2usb.command  (Linux)
C:\Users\yourname\mgt\finance\              (Windows)
C:\SomeDir\SomeDoc.docx                         (Windows)

The only requirement for a File reference is that it is clear it concerns a path to a file or directory. When a full path is used it will be obvious. Depending on Operating System there are various ways of managing File References. Details in [MGT: 80.Tools].

In certain cases it may be necessary to refer to a page or sheet or chapter within a file. This can be achieved using extra info within the reference relating to the type (page, sheet, chapter), an '=' sign and the value (page nr, sheet name, chapter name etc.)

Examples:
C:\SomeDir\SomeDoc.docx Page = 100
$HOME/data_private/mgt.xlsx Sheet = Planning

### URL
URL refers to *anything* that can be accessed through a web browser: classic web pages, sharepoints, PowerBI pages, etc. For URL the Note Reference is: [URL] in which URL is of form http://something.xyz and without < and > and where 'http' can be any supported service (http, https, ftp, ftps, ssh, ...).

### Mail
For Mail the Reference format is: [Mail: Text] in which Text is the Mail's Subject that was sent/received. Alternatively, one can use [Subject: Text]. The use of 'Mail:' or 'Subject:' is mandatory.

### Database
Databases come in many forms but all do the same: store data. Databases have their own manner of connecting and retrieving/entering data.

### Meeting
Sometimes it is relevant to refer to a meeting that was held in which specific information was shared. In this case the reference should show [Meet: Text] in which text is the Subject of the Meeting's invite mail. 


*********************************************
# PROFILE
Here the notion of a Profile is explained and how it is used in Management. The first section gives an overview of what a Profile is, which can be used in other documents. The Level 2 sections thereafter provide further details for each of the aspects of the Profile.
________________________________________
## Profile Overview
The Profile a.k.a. Management Profile, is an essential part of the Management Framework, incorporating fundamental concepts of management theory. It explains the structure a Manager is accountable for in a holistic manner, whilst leaving room to adapt to specific circumstances.

A Profile is designed around the concept of a *Venture* or *Enterprise*. A Venture can be the entire company (manager = CEO) down to a Helpdesk (manager = team-leader) and anything in between (manager = desk head, Business Line head, Department Head, etc.) This means the scope of a Venture can be considered *within* a company or the *entire company*. The Profile also acts as a framework for non-managers to understand the dynamics of a Venture.

### Profile Tree
A Profile expresses a Venture through a *Profile Tree*, composed of interrelated *Profile Tree Items* as follows:

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
- Environment
  ⇕
- Clients
  ⇕
- Services
  ⇕
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
- Operations ⇒ Run, Change ⇒ Revenue, Cost, Risk
    - Staff
    - Assets
    - Suppliers
    - Liabilities 
    - Equity
  ⇕
- Management
    - Planning
    - Organising
    - Leading
    - Controlling
  ⇕
- Business Functions
    - Finance 
    - HR or Human Resources
    - IT or Information Technology 
    - Risk
    - Compliance
    - CorpSec or Corporate Secretary
    - Procurement 
    - Others
  ⇕
- Tools 
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

### Profile Tree Explained
A Venture's main purpose is to generate more *Revenue*, or *Income*¹⁾ from the sales of *Services*²⁾, a.k.a. *Products*, to *Clients* than the *Cost* to yield those Services through *Operations*. Operations consists of all *Processes* contributing directly or indirectly to the continuous delivery (a.k.a. *Run*), as well as continuous improvement of that Run (a.k.a. *Change*), of Services in a *sustainable* manner. A Process consists of *Steps* applied to *Input* to achieve a *Result*. The Processes in Operations are performed and/or overseen by *Staff* using *Assets* and *Suppliers*. Combined, Staff, Assets, Suppliers are called *Resources*. Resources generate Costs (salaries, rent, depreciation, electricity, costs of goods sold, fees, etc.) as do the results of Operations e.g., tax. These Costs are covered by *Funding* through Cash (a fundamental Asset) made available continuously through Revenue, *Liabilities* a.k.a. *Debt* and *Equity*. Operations also generate *Risk*, defined as the probability of adverse outcomes, either directly (loss of Revenue, fines) or indirectly (loss or damage of Resources which in turn affects Revenue). Adverse outcomes occur as result of either i) weaknesses in Processes performed or supported by Staff, Suppliers or Assets and/or ii) as a result of unforeseen conditions created internally (Management, Staff, Suppliers, Assets) or externally (Suppliers, Clients, and *Environment*), where Environment³⁾ is composed of *Natural factors*, *Investors* a.k.a. *Shareholders*, *Creditors*, *Competitors*, *Governments*, *Regulators*, *Tax offices*, *Labour Unions*, *Markets* etc. In short, Risk⁴⁾ is a form of *probabilistic* Cost and the management of Risk incurs a direct Cost e.g., insurance, hedge transactions, backup Assets, etc. Revenue minus Cost is called *Earnings* or *Profit*. Revenue, Cost and Profit are expressed in monetary values, as is Risk. Revenue and Cost make up one of the key *Financial Statements* called *Income Statement* whereas Assets, Liabilities and Equity make up the other statement called *Balance Sheet*. Operations are maintained (Run) and improved (Change) continuously, through *Management*. Management consists of four *Management Functions* called *Planning*, *Organising*, *Leading* and *Controlling* a.k.a. *POLC*, such that Profit is maximised and Risk minimised within the constraints of Funding.
Management is aided by *Business Functions* and management *Tools*. Management permeates the entire Venture. 

Notes:
¹⁾ For non-profit Ventures (charities) Income is obtained through donations, not sales of Services, even if provided. 
²⁾ Services can also be generated internally e.g., quality control. 
³⁾ Although Environment is at the top of the Profile Tree, it impacts *the entire Venture*. 
⁴⁾ Services often embed Risk e.g., financial products, machinery, cars, etc. The pro-active management of this Risk is integral part of Operations.

### Operations
Operations is central to the Profile Tree. It has five key deliverables explained above: *Run*, its continuous improvement through *Change*, with both ultimately yielding *Revenue*, which comes at a *Cost* and generates *Risk*. These are not just deliverables for Operations, they are the ultimate outputs of the entire Venture!

### Profile Tree Top and Bottom
Another way to understand the Profile Tree is to break it down into two parts: *Top Profile Tree* and *Bottom Profile Tree*, indicated by the block between the dotted lines in above diagram. The Top Profile Tree says: 
- What is created (Services)
- Whom receives those Services (Clients)
- Which constraints and dependencies affect the manner in which the Services are created and maintained (Environment)

The Bottom Profile Tree focuses on:
- How is the Top Profile Tree is achieved (Operations)
- How are Operations improved (Management)
- How is Management aided (Business Functions & Tools) 

The Bottom Profile Tree emphasises the fact that Management creates and maintains Operations which ultimately yield Revenue, Cost and Risk, and that those Operations are performed by Staff using Assets and Suppliers which are (self-)funded by Cash from Revenue, Liabilities and Equity.

### Business Functions
Business Functions contribute Services aiding in the Management of one or more Profile Tree Items e.g., Human Resources aid in Management of Staff. It is possible to outsource Business Functions to external Suppliers. Business Functions can thus be internal or external to the Venture. Business Functions are effectively a form of Supplier. If a specific Business Function is not available, then that Business Function is in general performed within Management. It is worth noting that Operations is sometimes considered a Business Function. The Profile can be applied to Business Functions as well. 

### Tools
Tools consist of *Frameworks*, *Procedures* and *Software* that *aid* in Management. A Framework is a supporting structure underlying a topic essentially acting as a guideline that helps Managing the topic without being specific about Processes involved in the topic. A Procedure is a document describing how to perform one, or more, Processes. Software performs Processes through digital or IT means. 
Note that a "Tool" used within Operations e.g., a wrench, is deemed an Asset. The Profile is itself a Framework. Another Framework fundamental to understanding the Profile is the *6W*.

#### 6W Framework
The 6W Framework aids in framing *any* topic by enforcing answers to 6 fundamental questions: *What*, *Where*, *When*, *Who*, *Why* and *How* or *Which* (hence 6W). The following are examples for each:
- What: short name, description, overview, ...
- Where: geographical location in building, asset, ...
- When: history of topic, future deliveries, ...
- Who: person/people involved, skills, ...
- Why: purpose of topic, relevance to other topics, ...
- Which: manner in which topic is achieved, ...
NB: the *where* is not necessarily a geographic location but could be an Asset with an embedded Process.

### Stakeholders
People involved in, and affected by, the Venture are internal (Staff, Manager) or external (Environment, Clients, Suppliers, and including people impacted without being any of the previous). The sum is called *Stakeholders* and considering their interests falls within a Manager's remit.

### Reduced Profile Tree
The Reduced Profile Tree or *RPT* focuses, and expands, on part of the Bottom Profile Tree. It contains 13 *RPT Items* discussed in detail in the sections below:
- 3 Resources: Assets, Staff and Suppliers
- 2 Funding items: Liabilities and Equity 
- 4 Management Functions: Planning, Organising, Leading and Controlling
- 4 *Key Deliverables* from Planning and Organising namely *Goals* & *Objectives* and *Activities* & *Groups* respectively.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
Planning ⇔    Goals & Objectives ⇔  Controlling
                   ⇕
Organising ⇔ Activities & Groups ⇔ Leading
                 ⇕       ⇕
               Assets   Staff  
              Suppliers
               Liabilities                     
                   Equity
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

### Goals
Goals represent medium to long-term targets of the *Strategy* of the Venture. We differentiate between *Run Goals* and *Change Goals*. Run Goals focus on continuously delivering, contributing to, or enabling of *existing* Services that Clients already get or should get, whilst assuring the manner in which this is done is as expected. There are four essential Run Goals:
i.  mgt -> Manage Venture;
ii.  prd -> Perform production
iii. ovs -> Perform oversight I.e., oversee production; and 
iv. ovh -> Perform overhead i.e., anything not contributing to above three Goals but which are required nonetheless e.g. mandatory training;

Change Goals aim to *improve* Run Goals. The essential Change Goals are: 
i.   gro -> Grow Revenue by adding Clients, Services
ii.  pro -> Protect existing Revenue at risk of being lost due to a changing Environment;
iii. sec -> Secure Operations to reduce Risk; and 
iv. opt -> Optimise Operations to reduce Cost and/or increase Revenue. LP

Goals can, but don't need to, have *Sub-Goals*: *Run Sub-Goals* and *Change Sub-Goals*. It is through Run Sub-Goals within Goal *prd* that Activities can be differentiated by focusing on aspects of the Services and/or Clients that set each Activity apart e.g., Sub-Goal is *prd - Build Car Engines*. Change Sub-Goals refine Change Goals into a detailed *Roadmap* where each Change Sub-Goal reflects a specific theme Management wants to focus on for the current period, mostly a year e.g., *opt - Reduce Cost of Suppliers*. 

Goals and Sub-Goals can be transversal across Activities. When Goals are referred to, Sub-Goals are deemed included. Goals are a key deliverable of Planning and it is Goals, Sub-Goals and Objectives that yield Services which is why in the RPT Services are not explicitly mentioned. 

### Objectives
An Objective is a *precise*, *time-based* Process, or series of Processes, the output of which supports the completion of a Goal and thus the delivery of a Service. Objectives consume Assets and Suppliers, and are performed by Staff. 
In the 6W Framework the Why of an Objective is the Goal the Objective contributes to. 
Objectives are either *Routines* or *Projects*. Routines tie into Run Goals and are performed on a recurring or continuous basis whereas Projects tie into Change Goals and are performed as one-offs aiming at improving Routines (adding, optimising, reducing, automating, ...). Objectives are specific to, or transversal across, Activities. Objectives are what makes a Venture do what it is supposed to deliver. 

### Activities
An Activity is a grouping of one or more Objectives that are relevant to the delivery of one or more Services. An Activity can be linked to a single Sub-Goal or several. Activities can roll up into other Activities, called grouping of Activities and an Activity can have sub-Activities. Each Activity is performed by a Group. 
As mentioned, Run Sub-Goals for Goal = prd drive what an Activity is ultimately about, even if the Activity also has Objectives related to for example Goal = ovs. 

### Groups
A Group represents one or more Staff e.g., department, team. Groups can roll up into other Groups, called grouping of Groups. The sum of Groups is called Organisation and the relation within a Group and between Groups is reflected in an *Organisational Chart* or *Org Chart*. The name of a Group is the name of the Activity, and they are often used interchangeably. Although an Activity may have sub-Activities this does not mean that the Group has sub-Groups i.e., all staff in a Group can perform Objectives across different sub-Activities.

Ultimately, when referring to an Activity one refers both to the associated Group *and* to all Routines and Projects that make up the Activity performed by that Group.

### Staff
Staff refers to people directly responsible for achieving the Objectives within Groups by using Assets and Suppliers. They already have, or are trained to acquire, the relevant *Skills*, *Knowledge* and *Experience* to fulfil the *Roles & Responsibilities* attributed to them.

### Assets
Assets are the setup available to Groups to achieve Objectives. They are tangible (physical) or intangible and cover a vast range from buildings, desks, servers, raw materials, inventory, software, cash all the way to referential data and documentation. Assets include *Data* and *Information*. Data is a *record of fact*, whereas Information or *Info* is the *organisation and interpretation of Data* and is used by Staff and Managers alike to make decisions and perform oversight.
The scope of Assets in the Profile is broader than in Business Function Finance. In Finance, only those resources owned by the Venture *and* which can be converted to Cash are deemed Assets and will appear on the Balance Sheet. The rest of the Assets being considered as *off-balance sheet*. For example, in the Profile a procedure is an Asset but in Finance it is not always e.g., the Coca-Cola recipe would be an Asset for the Balance Sheet (goodwill), but the procedure how to clean the drums in which that drink is mixed likely not. 

### Suppliers
Suppliers contribute to the achievement of Objectives without being accountable for them. Suppliers provide and/or maintain Assets and/or Services to the Activity. They can be internal or external. An alternative way to look at a Supplier is to consider it a dedicated Activity inside or outside of the Venture. The Profile Framework can be applied to each Supplier.

### Liabilities 
The Venture needs to pay for Resources but often does not have the necessary Cash at the required time (Revenue has not yet been generated). To overcome such timing differences, the Venture enters into Liabilities like short- & long-term loans, overdrafts, purchases on credit etc., which most often come at a Cost (interest). In summary, Liabilities are what the Venture owes others, and which need to be paid at one point in the future ranging from short term (daily, weekly) or long term (monthly, yearly, decennial). Not all Activities are directly affected by this.

### Equity
For a listed company Equity represents the net worth of the Venture and is the difference between Assets and Liabilities. For a non-listed company, the name used is Capital. Equity includes Shares issued as well as retained Earnings. Issuing Shares relinquishes control of the company to Shareholders who expect sustained positive performance of the company i.e., Earnings redistributed as Dividends or share price increase or both. As a form of funding, it is long term and infrequent. It is mostly a concern for Management on company level.

### Management
The Management Functions of the POLC i.e., Planning, Organising, Leading and Controlling, academically explain the foundations that continuously drive and optimise Operations. They are the four main deliverables of Management and are what Management in its essence is about. In addition to the above four Management Functions, there are two more deliverables within Management.
The first one is the *Management Cycle*, or *MC*, which reflects the continuous performance of the four Management Functions, but expressed in terms of the key deliverables of Operations: *Revenue*, *Cost*, *Risk*, *Run*, and *Change*, with the rest of the Profile Tree Items (Staff, Assets, Suppliers, Equity, HR, Finance, etc.) all captured in the generic cycle called *General Management*, *General* or just *Management*. Combined with *Intel* as the information contributing step, these 7 items of the Management Cycle are referred to as *Managerial 7*. 
The second deliverable of Management is *Management Improvement*, which, as the name suggests, involves improving the performance of Management itself, including improving Managers. Note that involvement in the deliverables in Management, Planning, Organising, Leading and Controlling depends on the *Management Level* e.g., CEO, department head, line manager, team leader, etc.

### Planning
Planning involves Processes to establish *what is to be done where, when and why* and *how*. This first Management Function defines why the Venture exists (*Context*, *Purpose*, *Vision* and *Mission*), within which boundaries it expects its Staff to operate (#Values* and *Bylaws*), and how it assesses the Environment versus its own capacity (*SWOT* and *Intel*). 
Planning ultimately yields the aforementioned deliverables Goals and Objectives which drive the Services to produce. By design, Planning also establishes metrics for Objectives, expressed as Revenue, Cost and Risk, including metrics for Balance Sheet, which are subsequently used in Controlling. 
The result of Planning is a *Plan* or *Planning* and depending on detail and how forward looking they are, they are called *Strategic Plan* a.k.a. *Strategy*, *Tactical Plan*, or *Operational Plan* a.k.a. *Operating Model*. The latter is the blueprint of everything involved across the Profile Tree but focussing on the Run of the Venture. 

### Organising
Organising involves Processes to establish *who does it* and *how to do it*. This Management Function frames the Activities that perform specific Objectives defined in Planning, and it defines how Staff are organised in Groups such that they can use Assets and Suppliers to achieve those Objectives within the Activities. Organising also establishes *Roles & Responsibilities* of Staff using the concept of *Delegation* of *Responsibility* and *Authority*, thus creating *Accountability*. The result of Organising is an *Organisation*, both of Activities and Groups.

### Leading
Leading involves Processes to *drive* those *who do it*. This third Management Function entails directing, influencing, and motivating individual Staff and Groups to achieve the Objectives, whilst considering concerns and interests of Staff. Deliverables are a *Safe Space* for Staff such that *Collaboration*, *Motivation*, *Inspiration* and *Learning* are all maximised. Leading, if well done, *also* grooms future *Leaders*.

### Controlling
Controlling involves Processes to establish *how well it was done*. This fourth Management Function assesses the Venture's performance across all Activities versus metrics determined in Planning, and adjusts through Planning, Organising and Leading. 
Controlling uses *Journaling* to record any matters related to the other Controlling deliverables and more generally, to keep track of work done across all four Management Functions.
The assessment of the efficiency of Operations is done through *Supervision* which is performed through a *Supervision Framework* composed of *Supervision Processes* a.k.a. *Controls* applied to a *Supervision Scope*. There are four Supervision Processes:
i.   A *Check*: verify Processes and/or Results vs formal benchmark;
ii.  A *Review*: verify Processes and/or Results against experience, or opinion;
iii. An *Attendance*: attend a *Committee* to verify Processes and/or Results through discussion with others, thus attaining a broader range of opinions than a Review; or 
iv) An *Audit*: an *independent* verification of Processes and/or Results, the result of which is used by Management.

The Supervision Scope is either one of the following:
i.   The *Activity Based Scope*, which focuses on all the Venture's Activities
ii.  The *Business Function Based Scope*, which focuses on the Venture's Business Functions.
iii. The *Hybrid Based Scope*, a combination of the above two.

The Supervisory Processes yield *Reports* to Management or other Stakeholders. The Reports contain suggestions for, or decisions of, improvements (often expressed as Projects), which need to be embedded into Operations through Planning, Organising and Leading. Lastly, *Monitoring* assures tracking, and the actual implementation, of these improvements.    

### Expanded Profile Tree
By combining the Profile Tree and the Reduced Profile Tree we obtain the most comprehensive view called the *Expanded Profile Tree* with 28 Expanded Profile Tree Items:        

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
               Environment
                   ⇕
                 Clients
                   ⇕
                 Services
                   ⇕
            Revenue, Cost, Risk
                   ⇕
Planning ⇔  Goals & Objectives ⇔  Controlling
                   ⇕
Organising ⇔ Activities & Groups ⇔ Leading
                ⇕             ⇕
              Assets      Staff  
             Suppliers
              Liabilities
                 Equity
                 ⇕
                            Finance             
                               HR
                                IT  
                              Risk
                        Compliance
                           CorpSec
                        Procurement 
                             Others
                 ⇕
                             Tools
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

The Profile Tree, Reduced Profile Tree and Expanded Profile Tree provide *structure* and *insight* as to how each item plays a part in a Venture and how all items are interrelated. The relative importance of each depends on the Venture. 

### Wrapping it up
Operations as mentioned as the central part of the Profile Tree Item, is represented by the combination of Activities & Groups + Goals & Objectives + Resources + the funding of those Resources via Liabilities and Equity. Operations are often divided into different functional units like Sales, Marketing, Research & Development, etc. However, from a Profile perspective these functional units are just different names for Activities. Management initiates and continuously optimises how Operations are performed.
Operations and Management both have the notion of Process embedded and as such, Processes are not reflected as a Profile Tree Item. Finally, the Profile is a *framework*. There are many ways to use it and it is up to the Manager and Staff to use it such that it adds the most value to the Venture.
________________________________________
## Profile Tree Items in Tools
From a managerial perspective the order of the items in the Profile Tree is mostly followed in reverse order i.e. first Management, then Operations, Services, Clients and last but not least Environment. In other words, and using numbers to enforce the order in which they are used: 

00.Management
    01.Planning
    02.Organising
    03 Leading
    04.Controlling
10.Operations
    11.Staff
    12.Assets
    13.Suppliers
    14.Liabilities 
    15.Equity
20.Services
30.Clients 
40.Environment

and the Business Functions in the 50 range: 

50.Business Functions
    51.Finance
    52.HR
    53.IT
    54.Risk
    55.Compliance
    56.CorpSec (Legal, tax)
    57.Procurement
    59.Other (Marketing, Procurement, ...)

80.Tools

It is this naming and numbering that is used in the various MGT:xxx notes and any other Tool referencing a Profile Tree Item as well as file paths. Note that a reference to for example MGT: Tools or MGT: 80.Tools is deemed equivalent. The above Business Functions are an example and the items/numbers can differ for each Venture.

All Profile Tree Items, in the order they appear in the Profile Tree as well as the Business Functions are explained in below sections, as is the definition of Process which is fundamental to the entire Venture.

Each deliverable for each Profile Tree can have a number as well. The number is composed of the Profile Tree Item nr and then a new nr e.g.

02.01.Activities as the deliverable within Profile Tree Item 02.Organising etc.

The Legend, with the Profile as overarching Framework, has the highest number in the naming convention: 99.Legend. 
________________________________________
## Process
A Process is so fundamental to what happens within a Venture that it has a dedicated section to define it.

A Process is one or more *triggered* or *continuous* *Steps* applied to one, or more, forms of *Input* to achieve one, or more, forms of desired *Output* or *Result*, or:

    Input(s)  ⇒  Step(s)  ⇒  Result(s)

A Process is defined by the 6W Framework: Where, What, When, Who, Why and How or. Which. In other words What Result is to be delivered, Where and When, *by* Whom *and* *for* Whom, Why is the Result important, and How is the Result achieved i.e. which Inputs are used and what does each Step do with the Input. Note that Where can be a geographic location, but can also refer to an Asset in which a Process is embedded.

Output is purely determined by the *desired* Result and thus drives the design of the Steps and the Input. 
Input can be any of the following: Assets, Services from Suppliers and Results from other Processes or from the Process itself (internal loop back). Therefore, they have constraints: time, energy, manpower, cost, etc. 
Steps are the logic of the Process: they determine how Input is transformed into a specific Result and they may be manual or automatic (the latter case is triggered manually or by another Process).
It is possible, and even likely, that several Processes, and thus Results, need to be combined to obtain a final Result. Such combined Processes have different names e.g. Activities, Macro-Processes, Process Group, etc.

*Process Maintenance* is the notion of manually or automatically applying specific Processes to assure another Process keeps yielding the expected Result over time. As it is an extra Process purely built to keep another Process operational it adds to the Cost of the original Process.
 
*Process Complexity* is determined by the multitude and complexity of the Steps and/or Input. Process Complexity has an impact on Process Maintenance.

A *Process Owner* is the Group or Staff expected to yield a Result, making a Process Owner = Result Owner. However, they may not own the Input which may be produced by Processes outside of Process Owner remit, i.e. the owner faces a *dependency* on other Process and thus Process Owners. 

*Process Cost* is the cost of a Process. Often this Cost is hard to price, and may not be relevant on a per Process basis. Nevertheless, each Process incurs cost. Process Cost can be related to time spent by Staff on a Process.

A Process has Risk associated to it, by definition, see [## Profile Overview]. The assessment of that Risk, for a given Process is key in Risk Management. Sometimes specific Processes are designed to verify another Process has yielded a specific Result as per expectations. Such a Process is referred to as a Control or Check. By definition, even Controls have Risk embedded in them.

Optimising Processes such that they are at lowest Cost and generate the least Risk possible, is key in Management in general.

Any Process should directly or indirectly :
- Maintain or Increase Revenue and/or
- Maintain or Reduce Risk and/or
- Maintain or Reduce Cost and/or
- Report to Stakeholders

If a Process does not do the above, directly or indirectly then it is likely it should not be performed at all. 
________________________________________
## Environment
The Environment of a Venture consists of *external forces* that can, and often will, influence Clients / Services / Operations / Management, either directly or indirectly and without the Venture having any form of control over that influence. Even if the Profile Tree shows it at the top, Environment is applicable *throughout* the entire Venture. Environment is important in SWOT analysis (see below) and general Risk Management. The Environment can also include the history of the Venture. 

Key deliverables of a Venture is either one or both of:
- Country XXX
- Region XXX / Transnational / Global 

With as many XXX entries as are relevant for the Venture. The following can be important to each deliverable:
-  Geography: includes consequences of the location the Venture operates in and which are not Climate related e.g. soil, volcanoes. risk of earthquakes, tsunamis.
- Climate: a catch-all term for weather and climate.
- Nature: natural plant and wildlife as a result of Climate, Geography as well as Society. 
NB: Agriculture, if any, is discussed under Economy.
- Infrastructure: represents the facilities supporting the Venture including Architecture, Energy, Telecommunication and Transportation.
- Society: total of social forces excluding Politics and Economics. It includes aspects like Art, Cuisine, Music, Movies, Sports, Religion, Healthcare and Demographics.
- Politics: represents the governmental and judicial structure, including Military as extension of Politics. 
- Economy: supply/demand of goods and services.
- Tax Authority: often country specific, they determine Profit tax, but also taxation of Staff salaries, and often also accounting standards to be used by the Venture 
- Regulators: regulations have a direct impact on Services and/or Operations and/or an indirect impact through Clients, Suppliers. 
-Competitors: offer similar/same Services to similar/same Clients. They are an integral part of Economics in terms of supply and demand. Competitors offering services closest to the Venture's Services are called *Peers*. 
- Investors: represent people financing the Venture. The Business Function Finance, see below, is directly related for this aspect. 
- Technology: a main driver of innovation and thus is key to the Venture.
- Other: anything else that is not part of the above.
________________________________________
## Clients
Clients consist of *external* or *internal* individuals, groups, or corporations receiving the benefit of Services. Without Clients, there is no purpose for Services to be delivered. Understanding Clients's needs and constraints is critical to assuring Services are optimal. Obtaining this insight is part of the Business Function Marketing, a.k.a. Sales.

Key deliverables for Clients are 
- Clients XXX

With the following being relevant for each Client XXX:
- Overview: Description, can include, history, Environment business Client operates in, the Venture's Competitors having a relationship with the Client, etc.
- Contact: Group/Groups owning or having a relationship with the Client.
- Service: Services used by the Client in general, and the ones offered by the Venture in particular.
- Revenue: the Revenue associated to the Client
- Cost: Cost associated to maintaining the relationship with the Client
- Risk: Risk associated to maintaining the relationship with the Client
________________________________________
## Services
Services, or Products in the case of manufacturing Ventures, are items of value to Clients and for which they are willing to do an effort to obtain them, or for which they will be appreciative in some manner, most often monetary. In certain cases Services can be composed of Services *and* Products. For example stock exchanges deliver various Products (Stock, ETF, Warrants, Options, ...) through various Services (Trading, Clearing, Settlement, Market Data, ...) or Computer Hardware companies sell Products (computers) but also offers Services (repair, advice) to service those Products.
Client demand drives what needs to be delivered, where and when through Operations. Some Services are for the benefit of the Venture itself i.e., internal Services e.g., Risk Management, Helpdesk Support.

Key deliverables for Services are:
- Run
- Change

### Run
These are the Services Clients tend to expect either because they already receive it, or because they are an accepted norm of level of Service, or because it is a mandated Service e.g., regulatory requirement.

### Change
Change Services consists of Services applied to Run Services such that the Run Services generate more Revenue and/or at lower Cost and/or at lower Risk.  

For each Service XXX, there are various aspects that are relevant to keep track off:
- Overview: description which can include aspects like history, Environment, and including details of what the Service consists of and what the benefit is for the Client / Venture.
- Internal/External: is the Service delivered internally (to another Objective that needs it as input) or externally (to a Client).
- Activity: the Activity/Activities delivering the Service. 
________________________________________
## Operations
Operations is the active component of the Profile Tree. It involves the performance of Processes through Resources (Staff, Assets and Suppliers) to deliver Results in the form of Services as per the Strategy. Operations generate Cost and Risk. 
The so called *Operating Model* a.k.a. Operational Plan construed as part of Planning reflects the manner in which Operations are performed. 
Operations are the most work intense part of the Profile as they reflect actual work done to deliver the Services. Operations is *also* a Business Function which adds to the importance of this Profile Tree Item as it involves additional Processes not directly related to the provision of Services, but rather support of, sustainability and resilience.

Operations are performed by Groups of Staff within the Activities of a Venture, see [## Organising] and they tie directly in to Goals and Objectives, see [## Planning],. 

Key deliverables for Operations are:
- Run
- Change
- Revenue
- Cost
- Risk

### Run
The Run a.k.a. Production or Prod, is composed of Routines, done in a recurring manner, which generate Run Services. Recurring can be continuously, hourly, daily, weekly, monthly, quarterly, semi-annually, annually, ad-hoc (triggered). Run can be broken down into two types:
- Value Chain: Revenue generating Processes
- Control Chain: Oversight Processes

### Change
Change is composed of Projects that improve the Run. Change is performed within Activities and thus by Groups. These Activities can be the same ones as for Run or different ones. Change is composed of Projects. 

Note that Run may require the execution of potentially effort intense Processes. However, if those Processes do not effectively yield Change then they are not Projects. There is no fixed ratio between Run and Change for any given industry. At average, in the past it was more around 80% Run and 20% Change, over time this has shifted to 20/80. There are extreme cases: some companies have an Operating Model based on custom made Products, effectively reducing Routines to nearly 0 and Projects to almost 100% of the modus operandi e.g. custom made furniture. In some companies Operations is deemed Run and Projects are not within Operations. This choice does neither invalidate the concept of Operations nor the Profile.

### Revenue
This explains how sales of Services contribute to Income of the Venture. Understanding of Revenue and its evolution and future expectations of Revenue is key to good Management. 
 
### Cost
Operations creates Cost in different forms:
- Costs of Good Sold: costs directly related to the manufacturing of goods or delivery of Services a.k.a. Operating Fees, Negative Income (for Banks). In other words: if a Service is not delivered, the cost is also not Incurred. 
- Operating Costs: costs required to keep Operations up and running, incl. Salaries, Utilities, Rent, etc. These costs are incurred, even if a Service is not delivered.

Cost is an undesirable, but necessary deliverable, and its minimisation through Cost Management is an important responsibility of a Manager. 
NB: Cost is sometimes expressed via proxies (time, headcount), they ultimately still have a monetary impact.

### Risk
Risk reflects adverse, unplanned -not necessarily unexpected- outcomes that emerge as a result of Run and Change being performed in a dynamic Environment. More specifically, adverse outcomes occur as result of either i) weaknesses in Processes performed or supported by Staff, Suppliers or Assets and/or ii) as a result of unforeseen conditions created internally (Management, Staff, Suppliers, Assets) or externally (Suppliers, Clients, and Environment). The first one is often referred to a lack of quality of the Operations, whereas the former is more often referred to as external Risk.
Management of Operations invariably includes *mitigation* of Risk which are the processes put in place to pro-actively-identify zones of Risk and remediate the cause of that Risk. In the case of i) above, Risk Mitigation is referred to as Quality Control, and for ii) it is referred to as Risk Management. Combined they are part of Risk Management. Ultimately, Risk can be seen as a form of *probabilistic* Cost and the mitigation of Risk incurs a *realised* Cost e.g., insurance, hedge transactions, backup Assets, etc.

Several types of Risk exist:
- Strategic Risk: Managerial decisions yielding a specific Change yield a Result that is unexpected,
- Financial Risk (Market Risk, Credit Risk, Counterparty Risk)
- Operational Risk: risk that Operations yield unexpected Services or byproducts
- Regulatory Risk incl Tax Risk: risk that the results yielded by Operations create a dispute with an authority (tax, regulator, ...) leading to a cost in the form of legal counsel fees, fines by regulators, etc.
- Other: there are Risks specific to each industry

Risk is an undesirable consequence of conducting Operations and Management and its minimisation through Risk Management is an important responsibility of a Manager and expressed within the Goal oversight. Risk is also the focus of dedicated Business Functions Risk, Quality Assurance and Quality Control (different names, similar coverage).
It is important to note that depending on the Venture, Risk is fundamental or incidental to the Venture. For example, in Financial Institutions Risk is fundamental and the very active management of Risk is core throughout Operations, on the other hand a local furniture manufacturer risk is more incidental to the Operations, and it can be -partially- managed through for example Insurance. 
________________________________________
## Staff
Staff refers to people directly responsible for performing Objectives. Staff are grouped into Groups in which they have specific *Roles and Responsibilities*. It is the Staff in each Group that work together to deliver Services. To fulfil the Roles & Responsibilities Staff need *Skills*, *Knowledge* confirmed through *Experience*. Staff is managed through Business Function Human Resources although Managers play a key role in the day to day of Staff.

Key deliverables for Staff are:
- Staff XXX 

For each Staff XXX the following aspects may be relevant:
- Internal/External: is Staff internal (employee) or external (temp staff, contractor, consultant).
- Overview: description which can include aspects like how the Staff got to join the Venture etc,.
- Manager: whom the Staff reports to 
- Category: often the corporate title which is also used for Evaluation, see below.
- Group: which Group the Staff belongs to. The Group gives the Staff an identity within the Venture and indicates the type of work. 
- Job Description: the type of work the Staff is expected to perform see [## Roles & Responsibilities]. 
- Role: the title the Staff has within the Venture e.g. developer, trader, sales.
- Role Start Date: date at which the Staff got into the Role.
- Role End  Date: date at which the Staff existed the Role.
- Hire Date: date the Staff entered the Venture. It is possible the Staff takes on different Roles within the Venture which is captured by above Role Date. 
- Leave Date: the date at which a Staff exits  the Venture.
- Skills: the ability *to do* something well. Skills can be obtained through study and practice. The Process involved in identifying Skills sits under Human Resources, see [## Human Resources].
- Knowledge: Knowledge means an *understanding* of a topic. Knowledge is, like SKklls, obtained through Study and Practice. The Process involved in identifying Knowledge sits under Human Resources, see [## Human Resources].
 - Experience: refers to professional experience i.e. former job experience or equivalent that confirms the Staff's Skills and Knowledge.
- Training: the training record of Staff, including before and during the Venture. Training aims at increasing Skills. The Process involved in Training sits under Human Resources, see [## Human Resources].
- Evaluation: reviews of the Staff's performance in achieving the Objectives, be they individual or collective. Evaluation feeds Remuneration. The Process involved in Evaluation sits under Human Resources, see [## Human Resources].
- Remuneration: the recurring Cost of Staff, which includes salary but also secondary forms of remuneration like health insurance, social security, retirement, holidays etc. The Process involved in Remuneration sits under Human Resources, see [## Human Resources]. Although this item may not be recorded directly on the Staff, the details need to be collected so they can be used in Budgeting which is part of Planning. Bonus is part of remuneration but is not shown as a recurring Cost. 
________________________________________
## Assets
Assets refers to the setup available to Staff, and Suppliers, to perform Operations, including the financial means (cash) to acquire those Assets. Assets can be tangible and intangible. For the purpose of the Management Framework, a tangible asset is a physical item including land, building, vehicle, furniture, fixings, server, PC, laptop, cash, receivables, etc. An intangible asset is a non-physical item that has a multi-period useful life like patents, copyrights, client lists, trademarks, brand names, logos, procedures, data, referential & static data, analytical structures, Special Purpose Vehicles as well as knowledge which is developed over time through training, experience and recruitment etc.
Note that not all intangible assets in this framework can be found on the balance sheet e.g. referential data or procedures. Assets are for a large part managed through Business Function e.g. Finance or through dedicated Activities (see below). Assets often have a dependency on Suppliers which service them, see below.
As mentioned, Assets includes Cash made available through Funding or the sale of Services. Assets in this note have a broader definition than the ones used in Finance.
A special type of Asset is Legal Entity, which is managed by Business Function CorpSec.
NB: it is possible to hear the term human capital, which would denote Staff as a form of Assets. The Management Framework set out here makes a clear distinction between the two and thus does not include Staff within Assets.

Key deliverables for Assets are:
- Accounting Assets incl. Cash
- Infrastructure
- Intangibles
- Data
- Services (from Suppliers)

Instead of the above, it is possible to simply distinguish between:
- Internal 
- External

Alternatively a combination is used.

### Accounting Assets incl. Cash
Accounting Assets are those assets officially maintained in accounting records (Balance Sheet) including Fixed assets e.g. buildings and machinery as well as Current Assets e.g. Receivables and *Cash*. Cash is used to fund ongoing *Operating Costs* i.e. rent, raw material, utilities, etc. It is also used to purchase Infrastructure. Cash is made available from ongoing sales of Services and financing, see [## Finance]. Accounting assets includes liabilities and equity from an accounting perspective. Liabilities can be included in the details of this section if relevant. The Management of Accounting Assets (incl. Liabilities and Equity) is managed through Finance. 

### Infrastructure
Infrastructure or Infra a.k.a. Systems, refers to the physical setup used on a day to day basis whether part of Accounting Assets or not (off-balance sheet). Infra is purchased from Suppliers with Cash. Included is IT infrastructure (PC, servers, software).

### Intangibles
This includes all those intangible assets like procedures, referential, etc that are not Accounting Assets either.

### Data
The terms *Data* and *Information* a.k.a. *Info* are often used interchangeably, but they aren't the same. Data is defined as individual facts, while information is the organisation and interpretation of those facts.
Data is an intangible Asset, but has its own classification given its importance. Data is technically a combination of a physical repository (classified under Infrastructure) and the content held therein. Content can be anything broken down into two key types: *Structured Data* spreadsheets, databases and *Unstructured Data* like videos, music, pictures, text, presentations, source code, etc.

### Services
This refers to Services provided by Suppliers and which are not any of the above e.g.  trading venues.

For each Asset XXX in above key deliverables the following aspects can be relevant: 
- Type: whether the Asset is serviced/procured internally i.e. through an Internal Supplier or externally i.e. through an external Supplier.
- Overview: description which can include aspects like history.
- Category: the category of the Asset (software, hardware, ...).
- Supplier: name of the Suppliers servicing the Asset.
- Output: he output(s) of the Asset, i.e. what does it do.
- Cost: Cost per year. This  includes recurring license fees, support fees but not one-off fees which should be captured under Project Costs. Cost details are used in Budgeting which is part of Planning. 
________________________________________
## Suppliers
Suppliers contribute to the performance of Operations without being accountable for it. Suppliers can be embedded, internal or external (see below). They include distributors, utilities as well as internal departments /groups /teams. Suppliers can provide raw materials, finished products, commodities like electricity, water as well as intangibles e.g. custody, advisory, etc. Suppliers are closely linked to Assets as they often provide and/or service Assets. The definition is thus very broad e.g. a company's legal entities used as Special Purpose Vehicles are considered Suppliers as they own and service the SPV. Suppliers can also provide services to Management, although in that case they are covered under Business Functions.

There are two types of Suppliers: *Internal Suppliers* and *External Suppliers*:
- Internal Suppliers: Suppliers within the same Venture but which are *not* part of the Venture. This is the case where there is a department or team that is deemed a Supplier to other Activities within the Venture.
- External Suppliers: these are the 'classic' Suppliers outside the Venture 

Other names for Suppliers are *Service Provider*, *Solution Provider*, or *Support Function*.

The word Supplier is sometimes interchanged with *Business Partner* or *Partner*. Although Suppliers and Partners both offer Services to a Venture there is a difference which lies in the *relationship* with the Venture. Suppliers provide services based on a bidding process and for a specific purpose e.g. buying furniture, consuming utilities, after which the relationship often ceases to exist until it is required again. Partners, on the other hand, work with Management to optimise Operations such as to achieve the best Services. The relationship with Partners is long-lasting and based on *trust* in addition to the commercial terms. The word Supplier is used throughout this Profile to reflect either.  

Key deliverables for Suppliers are:
- Supplier XXX

For each Supplier XXX the following aspects can be relevant: 
- Internal/External: whether the Supplier is an internal Supplier or not. 
- Overview: description which can include aspects like history, Environment, etc.
- Category: the category of the Supplier (hardware, software, legal, etc).
- Contacts: key persons within the Supplier including contact details.
- Output: Services provided by the Supplier:
    - Services e.g. Accounting, Helpdesk, etc.  
    - Products which are either raw materials or Assets
    - A combination of the above
- Cost: the Cost per year. This includes license fees, support fees, allocation Costs but not one-off fees which should be captured under Project Costs. Cost details are used in Budgeting which is part of Planning.
________________________________________
## Liabilities 
In order to pay for Staff, Assets and Suppliers the Venture needs Cash. Cash is often not available the moment it is required, and overcoming the timing differences between needing Cash and Cash being generated from Revenue the Venture can take on so called Liabilities.

Liabilities can take various forms:
- Short term loans 
- Purchases on credit 
- Bank overdrafts
- Long term loans 
- Bond Issuance

The result of taking on Liabilities is the Asset called Cash, which then is used to pay for all resources (Staff, Assets, Suppliers). The processes involved in assuring Cash is available are referred to as Funding or Financing, see also [### Financing].
________________________________________
## Equity
The difference between Assets and Liabilities represents the net worth of the Venture. For non-listed companies i.e. sole-proprietorships this net-worth is often called Capital.  If a Venture has issued Shares, it has effectively passed control of the Venture over to shareholders and in this case the term Equity is used instead of Capital.
The notion of Capital, or Equity, is important and used in many different manners. In all cases, the underlying concepts are similar: it is the Net Worth of a Venture capable of generating further Profit. As can be seen, the definition only includes Assets and Liabilities, whereas the ability of a Venture's Operations to generate Profit also depends on Staff and Suppliers. However, from a monetary perspective Staff and Suppliers are pure Cost, and so the notion of Equity (monetary) being able to generate Profit(monetary) is correct, but incomplete from a Management perspective, which is particularly true in Ventures heavily dependent on Staff. 

Equity has several types:
- Retained Earnings
- Shares issued
- Reserves 

The processes involved in issuing Shares is discussed in Financing, see [### Financing].
More generally speaking, a Manager, in particular at higher levels, are expected to understand the relationship between Assets, Liabilities and Equity.
________________________________________
## Management
Management, or Managing, focuses on a person, called *Manager*, proactively using Tools to continuously fund (through Revenue, Liabilities and Equity), enable and deploy Resources (Staff, Suppliers, and Assets) at a Cost, such that the continuous performance *and* improvement of Operations (Run and Change) is assured and controlled such as to minimise Risk in order for Services to be delivered to Clients yielding Revenue, and this despite constraints emanating from the Environment  This is essentially the summary of the Profile. To achieve the aforementioned, Management consists of continuously and interchangeably performing four *Management Functions* called *Planning*, *Organising*, *Leading* and *Controlling* or *POLC* as per below dedicated sections. 

Planning consists of strategy *formulation* for short, medium and long term *periods*, whereas Organising and Leading constitute strategy *implementation* over those Periods and Controlling consists of *verifying* the results of that implementation against the Planning. The four functions are theoretically cycled through in the order they are given above, but in reality Managers continuously alternate between them.

Management vs Governance
Often the term Governance is used separately from, or in combination with, Management. Depending on the context used it means different things. The different interpretations can be expressed as function of one or more Management Functions, or specific deliverables within the Management Functions. Below follow two key cases, but other interpretations are possible:
- Scholarly view: Governance = Planning + Organising, Management = Leading + Controlling 
- Risk view: Governance = Planning + Controlling, Management = Organising + Leading

Specifically, the latter view is often the view used in companies concerned about Risk. In such cases, Governance focuses on the following deliverables from the Management Functions:
- Intel (Planning), specifically w/r to the Environment, and particularly regulations
- SWOT (Planning), using the Intel to assess to what extent Risk is covered by controls either embedded in Production Routines or Oversight Routines. 
- Supervision (Controlling), specifically to assure all Risks are covered
- Report (Controlling), specifically reporting to senior Management.

The distinction between Governance and Management is not relevant for a Profile. The Profile deems Management is holistic, all-encompassing, as discussed above. It is, however, important to recognise that some Ventures make such distinction.

Management vs Leadership
From a definition perspective, Management consists of Planning, Organising and Controlling the Venture's Suppliers, Assets and Staff to accomplish the Goals whereas Leadership refers to an individual's ability to direct, inspire, influence, motivate, and enable Staff to contribute toward those Goals. In short, the main difference between the two is that leadership is about influencing Staff to follow, while Management focuses on maintaining systems and processes. As can be seen from the POLC, Leading or leadership is a key aspect of Management and as such, Management and Leading are fundamentally intertwined in the Profile.
Note that one can be good in the POC of Management but not in the L, which makes a less effective Manager. Reversely, a good Leader may not be an efficient Manager.

Management Level
As explained above, a Venture can be at various levels. A *Management Level* indicates at what level within the organisation Management is performed. 
Top Management is Management of the entire Venture often represented through a *Board of Directors* , particularly if it is a listed company or an incorporated company. 
Middle Management involves running Activities on department level, whereas Low-level Management or Line Management relates to teams. Obviously, many more Management Levels are possible. Ultimately, Top Management delegates (see [## Organising] ) a vast amount of Management Functions to Middle Management and they in turn delegate to Line Management. At each level Management still consists of the Four Management Functions, but the lower we get, the more the functions focus on Short Term and Operational aspects and less on Strategic aspects. 
Note also that for lower levels Management itself is not a full time job, instead it is part of the job, and the Manager may be involved in the Operations. This is referred to as a *hybrid Management/Operations* role or a *Hybrid Manager*. 

Management has 6 key deliverables (including the four Management Functions):
- Management Cycle a.k.a. MC 
- Management Improvement a.k.a. MI
- Planning
- Organising
- Leading
- Controlling

The latter four are effectively what Management is composed of, and have their own section below. These 6 deliverables are also considered the Sub-Goals of Management.

### Management Cycle
The *monetary output* of Operations is Revenue, and the *monetary input* is Cost (of Staff, Assets and Suppliers), with a collateral *monetary output* being Risk, and this is funded by monetary inputs Cash, Liabilities and Equity. These three aspects (Revenue, Cost, Risk) are the Manager's main, albeit high-level gauges for success of Operations. They are in turn generated by the Run of Operations, and that Run is subsequently improved by Change, all overseen by Management. These key aspects of the Profile Tree, are what make up the Management Cycle, and they are each referred to as a Cycle: 

0. Management
This baseline cycle represents all aspects of the Profile other than the 6 items below. This cycle is used to initiate a so called *Management Structure* i.e., the total of Tools and Processes the Managers uses.  

1. Revenue (or alternatively Income Statement)
The Revenue cycle aims at collecting Revenue data and use it to assess the Revenue generation of Operations. Alternatively, for higher level Managers, this cycle may focus on the Income Statement i.e. Revenue *and* Cost with the second Management Cycle being focused on the Balance Sheet, see also the cycle below.

2. Cost (or alternatively Balance Sheet)
The Cost cycle aims at collecting Cost data and use it to assess the Cost consumption within Operations. Alternatively, for Higher Level Managers this cycle focuses on the  Balance Sheet (Assets, Liabilities and Equity which in turns allows focusing on KPIs like Capital Ratios, Equity, RWA, Inventory KPIs etc. 

3. Risks
The Risk cycle aims at collecting Risk related data and use it to assess how Risk is  generated within Operations as well as within the Services produced by Operations. This cycle also includes Risk mitigation through Controls. 

4. Run
The Run cycle involves everything related to Run Goals and Routines performed within the Activities that make up Operations. This can involve anything from a detailed list of Goals and Routines a.k.a. *Run Inventory* or a higher level description of Activities.

5. Change
The Change cycle involves everything related to Change Goals and Projects performed within the Activities that make up Operations. This often involves anything the detailed list of Goals and Projects a.k.a. *Roadmap*.

6. Intel
The Intel cycle collects internal and external knowledge and is effectively a rather broad one and can include anything from Bylaws to competitor analysis to rumours. It is  the only cycle within the MC that is not explicitly part of the Profile Tree, but given the dependency of the Manager of Intel, it is integral and explicit part of the MC. 

### Management Improvement 
The aim of Management is to maintain and improve Operations. In order to maximise the result and efficiency of this, Management itself requires constant improvement: Management Improvement or *MI*.
This deliverable puts the onus on Managers to continuously learn about the Profile (Venture specific) and Management Theory in general. Management Theory is a vast topic that continuously grows, and Managers are expected to stay informed of this within the context of the Venture they work in. Below follow a few topics relevant throughout the Manager's career in any single or multitude of Ventures. 
________________________________________
## Planning
Planning involves Processes to establish *what is to be done, where, when and why* and also *how*. It is one of the most holistic Functions within Management.

This Management Function continuously defines why the Venture exists and which Services need to be delivered now and in the future, in which location and for which Clients. The Planning process, by design, establishes metrics for the output of Operations including Revenue, Cost and Risk. These metrics are used in Management Function Controlling, see below.

Key deliverables of Planning are:
- Context
- Purpose
- Vision
- Mission
- Values
- Bylaws
- SWOT
- Goals (K)
- Objectives (K)
- Tasks
- Strategic Plan
- Tactical Plan 
- Operational Plan
- Intel

### Context
The Context a.k.a. *Business Model* gives the Manager visibility on what the Venture is about, or said differently, what the *Value Proposition* i.e. what aspect(s) about the Service(s) are a differentiator for Clients. A key input to the Context is the result of SWOT (see below). Managers spend considerable time on assuring they know ins and outs of the Venture, constantly collecting information through Management Functions and Business Functions such that a holistic insight can be obtained and formalised in the Business Model. Note that a Business Model is related to, but not the same as *Operating Model* or Operational Plan, which is explained further below.

### Purpose
A Purpose Statement articulates the *why* of the Venture *now*. It explains the reason of its existence and the impact it wants to make, or in other words, what it does beyond the generation of Profit, *today*.  Most Venture's do not use Purpose Statements, and they focus on Vision Statements, or they refer to Purpose Statement which is actually a Vision Statement.

### Vision
A Vision Statement expresses the *why* of the Venture in the *future*. It explains what it thinks the reason of its existence should be and the impact it should have, or in other words, what it should do beyond generation of Profit, *tomorrow*. 

They are often of the form:

    To *verb* *object*

which is short for: 

    "Our purpose is to verb object."

Sometimes the verb object pattern is repeating.

Examples (company name, sector):
- To improve the world through trust (Everledger, Technology)
- To make active goals accessible (Sporting Wheelies, Disability Services)
- To simplify technology to empower business (Over the wire, Communications)
- To connect patients to advancements in cancer care (Icon Cancer Foundation, Healthcare)

### Mission
A Mission Statement expresses *how* the Venture achieves the Purpose. In other words it explains the Venture's value proposition, and does that in the following manner:

    "Achieve X by doing Y for the benefit of Z"
    in which:
    X: What (type of) Services get delivered
    Y: How are they delivered (differentiating factors)
    Z: Whom receives the benefits: Clients / Stakeholders

The most important one is Y as that sets the Venture apart from Competitors. The differentiating factors can be related to the Service itself (quality, availability, aesthetics, taste, ...), the cost to the Client, or it can be more focused on how the Service is produced (environmentally friendly, with involvement of the Client, etc).

### Values
Values a.k.a. Core Values are *guiding principles* crucial to the Venture. They affect the Venture as a whole and each individual working within and for it i.e. Suppliers. They also set requirements in terms of recruitment. 

Examples for LinkedIn:
    - Members first
    - Relationships matter
    - Be open, honest, and constructive 
    - Inspire excellence
    - Take intelligent risks
    - Act like an owner of #OneLinkedIn
    - Embody diversity, inclusion, and belonging

### Bylaws
Bylaws a.k.a. Company Laws, Policies, Normative Documentation, or Company Rules frame the *conditions* under which the Venture *should* operate and how it should organise itself.  
Bylaws represent the Venture's interpretation of rules, regulations and guidelines imposed by the Environment and which effectively provide *boundaries* on Services and on how Operations can, and should be performed. They result from the fact that the Venture operates directly or indirectly in one or more countries/states or in a business sector that is heavily regulated globally and/or nationally. 
In addition, Ventures can themselves define rules with regards to what it deems the Venture should comply with even if this is not mandated by any official institution. Often, such company imposed rules will also embody the Values. The definition of Bylaws is a result from the SWOT process, see below.

Obtaining insight into applicable laws, rules and regulations is part and parcel of Bylaws. This insight is often obtained through the Business Functions:
- Compliance: regulations specific to the Services delivered or to the type of Venture 
- Risk: specific regulations w/r to Risk if applicable 
- CorpSec - Legal: corporate law 
- CorpSec - Tax: taxation rules, applicable to Profit
- Human Resources: employment law
- Finance: Financial reporting standards, capital requirements

It is up to Management to assure Objectives are implemented such that they comply with Bylaws.
NB: documents to be filed with governmental institutions e.g. articles of association, are not deemed Bylaws in the Profile.

### SWOT
A SWOT, or *Impact Assessment* reviews all internal aspect of the Venture (Operations, Management and their respective deliverables including Services) versus external forces (Clients, Suppliers, Environment and their respective deliverables) to assess to what extent the Venture's *internal* *Strengths* and *Weaknesses* combined with *external* *Threats* and *Opportunities* make the Mission achievable, or more generally enable the increase of Revenue, decrease of Cost and of Risk. 
SWOT is an important deliverable for a Manager as it allows to define how to adjust the Venture to avoid or counter Threats and to take advantage of Opportunities given the Venture's Strengths and Weaknesses. More generally, SWOT is the term used for any impact assessment of changes coming from outside or inside. 
The key inputs to a SWOT are the Operational Plan (or less holistically the Tactical or Strategic Plan) and Intel (both discussed below). 
The SWOT feeds into the definition of Sub-Goals and Projects (see below) to seize Opportunities and/or remediate Weaknesses in Routines. Additionally, a SWOT can yield changes in deliverables of the other Management Functions (Organising, Leading and Controlling). The SWOT also feeds Context (see above). SWOT is most impactful when performed as a continuous process. 

### Goals 
Goals are outcome statements that define how the Venture is trying to accomplish its Mission and how it tries to align the Mission to the Vision over time. Goals are most often expressed in terms of Revenue, Cost and Risk, and thus indirectly the Services it aims to deliver through Operations. Goals are an intrinsic part of the RPT, see [### Reduced Profile Tree], and are the overarching driver for Objectives. 

Goals have the following properties:
1. Clear and unambiguous description of target
2. Measurable
3. Linked to Mission, Purpose and Vision
4. Specify period over which the Goal applies -mostly indefinitely-

Goals, like Services, differentiate between *Run Goals* and *Change Goals*:

#### Run Goals 
Run Goals relate to Run Services and are expressed in Revenue, Cost and Risk targets. They constitute, in most cases, the vast majority of work performed in Operations. Run Goals drive Run Objectives. Standard Run Goals in most Ventures are: 
1. Manage the Venture (Management, mgt); 
2. Produce the Run Services (Production, prd); 
3. Oversee Production, a.k.a. Quality/Risk Control (Oversight, ovs); and 
4. Perform Overhead (ovh), an unrelated effort not contributing to any of the above.

NB: ovs is similar to what a Manager does in Management Function Controlling, and as such can be considered a form of delegation of Controlling, see [#### Delegating]

#### Change Goals 
Change Goals relate to Change Services. Change Goals drive Change Objectives. Standard Change Goals in most Ventures are: 
1. Grow Revenue (gro);
2. Protect existing Revenue from change in Environment (pro);
3. Secure Operations to reduce Risk (sec); and 
4. Optimise Operations to reduce Cost/Risk and/or increase Revenue (opt). 

#### Sub-Goals
Sub-Goals are defined for both Run and Change Goals. For the former they regroup Objectives that contribute directly or indirectly to Run Services and thus reflect the Activities in the case of Goal prd. For the latter they are defined as themes Management wants to focus on over a short period of time e.g. 1 yr see [### Tactical Plan]. In the sections below, where *Goal* is mentioned, it can also mean Sub-Goal if one has been defined for a Goal. Change Sub-Goals are often presented in much detail to Stakeholders as part of the Strategy. The definition of Sub-Goals (and changes in Sub-Goals) is done as a result of SWOT. 

##### Run Sub-Goals
The following represent default Run Sub-Goals for each of the 4 Run Goals. 

Goal = mgt
The Sub-Goals for Goal mgt are essentially the 6 deliverables of Management:
- Management Cycle
- Management Improvement
- Planning
- Organising
- Leading
- Controlling

Run Goal = prd
The following are Run Sub-Goals for Run Goal prd:
- Activity XXX: all Routines performed within a specific Activity XXX. There are as many such Sub-Goals as there are Activities in the Venture. 
- Staff Maintenance
- Asset Maintenance
- Supplier Maintenance
- Service Maintenance, including Marketing
- Client Maintenance
- Environment Maintenance
- Revenue Maintenance
- Cost Maintenance
- Business Continuity (Routines to continue all other prd Sub-Goals in case of a disruption or more broadly a disaster). 
- Production Reporting (of all aspects related to Production to Stakeholders)
- Continuous improvement (small Project performed within Production)
- Production Support

In which:
Maintenance is a catch-all for: implementation, on/offboarding, integration, update, purchase and/or disposal of the Sub-Goal topic. It can include validation workflow, referential updates, software configurations, documentation, meetings in relation to the topic, etc. Maintenance could be construed as Change and not Run. The difference is subtle, and at the discretion of the Manager. In most cases, if maintenance is rather small compared to the resulting Growth of Revenue or decrease in Cost, decrease in Risk then it is deemed Run.

The last Sub-Goal, Production Support, is typically used for roles within an Activity that are a direct support to, without being accountable for Production, but also not being considered a Supplier e.g., Business Managers, COOs, Function Support, Team Support, Trade Support, Business Support, etc. Often, this Sub-Goal embeds interaction with the Business Functions, and potentially performance of processes related to such Business Functions. Production Support cannot perform, or assist in, any Routine of Activity xxx, but can assist in any of the other Sub-Goals. It is possible that there are as many Production Support Sub-Goals as there are Activities, which is the case if each Activity has a dedicated Support.   
Note also that It is possible that the various Maintenance Sub-Goals in prd are owned by Suppliers. 

Run Goal = ovs
The following are Sub-Goals for Run Goal ovs:
- Attend: prepare, attend and/or minute a meeting to perform a Review (see below) in relation to data from Operations a.k.a. Committee, see [## Committee]
- Audit: verify independently data from Operations and/or Management against a benchmark determined most often as part of the audit itself
- Check: verify data from Operations against a formal benchmark
- Review: verify and/or validate data from Operations against an opinion of an experienced individual
- Oversight Reporting: report on all aspects related to Oversight to Stakeholders
- Oversight Support: maintenance of Routines supporting the above Sub-Goals within one or more Activities.

The notion of *data from Operations* includes qualitative and/or quantitative data from production (Results, Processes) either in isolation or as one or more Activities, including data of Staff, Assets, Suppliers, Services and/or Clients and including/against an assessment of the Environment. The first four Sub-Goals represent the Supervisory Processesl found in Controlling. Each of those Sub-Goals can yield weaknesses or possibility of improvement that can be addressed through a Project (Change). 
Oversight Sub-Goals may be defined across the Venture and/or for each Activity (most organisations).
The last Sub-Goal, Oversight Support, is typically used for roles within an Activity that are a direct support to Oversight, without being accountable for Oversight.

Run Goal = ovh
The following are Sub-Goals for Run Goal ovh:
- Training: on the job training, safety/regulatory training, external training etc.
- Evaluation: definition of yearly personal objectives, evaluation against those objectives, compensation discussions, etc.
- Admin: company questionnaires, company initiatives for charity/sustainability/etc., holiday planning, etc.
- Legacy: Staff working on transferring knowledge to a replacement or covering Roles & Responsibilities for previous work
-  One-off: any work done for (small) Projects that are neither change nor Continuous Improvement under prd 
- Info: attend town halls/fireside chats, read emails, etc. on topics unrelated to any of the other Sub-Goals in prd, ovs, ovh, mgt. 

For default Change Goal prj there are dedicated Sub-Goals as well. They are standardised so the Roadmap can focus on gro, pro, sec, opt:

Change Goal = prj
The following are Sub-Goals for Change Goal prj:
- prj - gro: projects related to Revenue growth
- prj - pro: projects related to Revenue protection
- prj - sec: projects related to securing Operations
- prj - opt: projects related to Revenue growth, Cost Reduction

### Objectives
Whereas a Goal is broad, an Objective is a precise, time-based Process, or set of Processes, the output of which is measurable and which supports the completion of a Goal and thus the delivery of a Service.
Objectives consume Assets and Suppliers and are performed, or at least initiated by Staff. An Objective is performed within an Activity and they play a key role in the RPT, see [### Reduced Profile Tree].

Objectives are defined by the 6Ws and have the following key properties:
1. What: Unambiguous and measurable, reflected by the name of the Objective
2. When: have a *Start* and *End* date or *Recurrence* and an expected *Effort*
3. Who: performed by a Staff/Group *and* for the benefit of an Activity, see [## Organising].
4. Why: linked to a Goal i.e. what is the aim of the Objective.
5. How: detailed Processes involved in achieving the Objective.

The *Where* aspect is relevant for Venture's where the delivery of Service is not the same as where the Clients are, or where Assets used in Operations are not in the same location as the Venture. If this is not relevant, the *where* can be defaulted to the Venture's or Activity's location. 

Objectives are either *Routines* or *Projects*. Both have to be Measurable which ties them into Controlling, see below. Both also have a notion of *Effort*, or time spent, involved in performing them, but they differ in property nr. 2: Projects are *limited* in time, whereas Routines are *recurring* in time. Conceptually there is also an important difference which is explained below.

#### Routines
Routines are composed of one or more Processes performed on a periodic basis that contribute to a Run Goal by virtue of them being performed periodically. Routines do not have an End Date and are thus never completed, even if the Process(es) the Routines are composed of do complete each time the Routine is performed. The periodicity can be short (minutes, hours, days), medium (weeks, months) to long (quarters, years) or ad hoc i.e. they start when a trigger event occurs e.g. request.

Once a Routine is started it can take seconds to several weeks or even months to complete. Effectively, in certain case Routines can behave like Projects in that they have a start date (trigger date) and an end-date (completion date). For example, a custom production company (custom car, custom furniture, etc.) will take several weeks if not months to design and build i.e. behaves like a Project potentially including a Plan, resource allocation etc. What sets Routines apart from Projects is that the former are part of the Run, i.e. the Revenue generating cycle, whereas Projects are part of Change.

Routines can be further broken down into one or more *Subs* (sub-routines) which each can be broken down into one or more *Drills*. Drills thus link to Subs and Subs link to Routines. This allows building a hierarchy as follows:

Venture
    Run Goal
        Run Sub-Goal    
            Routine
                Sub
                    Drill

Such a hierarchy enables a detailed level of Planning (also means more maintenance). 

#### Projects 
Projects are composed of one or more Processes that contribute to Change Goals by being performed as a one-off. They start at one point in time and complete by an end date. The aim of Projects is to change the Run in one of two manners:
- Add new Routines to the Run (scope Change)
- Alter existing Routines to make the Run efficient (efficiency Change). Efficiency leads to improved Services and/or reduced Assets and/or reduced Suppliers and/or reduced Staff and/or reduced Effort. These reductions can be achieved through:
    - Deleting Processes or entire Routines
    - Automating Processes in Routines
    - Centralise Processes for several Routines
    - Simplify Processes in Routines

Note that for a Process, or group of Processes, to be considered a Project it needs to effectively change the Run. Work asked to be done at one point but which does not factually change the Run is actually a Routine with an ad-hoc trigger date, even if it occurs only once.

Projects can be further broken down into one or more *Streams* which each can be broken down into one or more *Actions*. Actions thus link to Streams and Streams link to Projects. This allows building a hierarchy as follows:

Venture
    Change Goal
         Change Sub-Goal
            Project
                Stream
                    Action

Such a hierarchy enables a detailed level of Planning (also means more maintenance). 

Goals (incl Sub-Goals) and Objectives combined serve to:
1. Gauge and report performance
2. Drive and improve performance
3. Align effort across the Venture, and
4. Manage accountability within the Venture. 

The definition of, and change in, Goals (incl Sub-Goals) and Objectives as well as Management in general are a consequence of SWOT.

NB: Services, Vision, Mission, Goals and Objectives are intertwined: setting Goals and Objectives defines the Services that will be delivered. In fact Goals are expressed as the performance of specific Objectives to achieve those Services. On the other hand Services that should be delivered are shaped by Clients which in turn drive the Mission from which follow Goals and Objectives, as it drives the longer term Vision.

### Tasks
Tasks are similar to Objectives but on a smaller scale i.e. there are Tasks that are more like Routines and Tasks that are more like Projects. Tasks can also be used to reflect specific Processes within Routines or Projects and/or Subs/Drills, Streams/Actions and are thus an efficient manner to keep track of progress within Objectives without necessarily breaking those down in Subs/Streams and Drills/Actions. 
Alternatively, Tasks can also reflect work to do without being specific on whether it is an Objective or whether it is part of a Goal or whether it contributes to a Service.  Effectively, Tasks are then a catch-all for "things to do" without the formalism of Objectives. They do not need to be defined for a Venture to exist, but they may help defining smaller scale Ventures or Activities within Ventures. 

### Strategic Plan
Strategic Plans include Purpose, Vision, Mission, SWOT and Goals and possibly Sub-Goals. It has a long time frame (3 years or more) and is descriptive. The Strategic Plan is defined by senior management.

### Tactical Plan 
A Tactical Plan aims at showing a high-level timeline for Goals and Objectives over a shorter period than the Strategic Plan (often 1-3 years). They are more precise than a Strategic Plan and show *what* will be achieved *when*. The Tactical Plan can cover all four Management Functions, but is mostly focused on Planning and Controlling. Depending on the manner in which Management wants to focus on specific themes within the Tactical Plan, the use of Sub-Goals may be used extensively. 

### Operational Plan
An Operational Plan a.k.a. Operating Model describes *how* the Tactical Plan is achieved. More specifically, it explains *how* and *when* Assets and Suppliers are used by Staff to achieve both Run and Change Goals through the realisation of specific Objectives, ultimately yielding Revenue at Cost and Risk.
An Operational Plan contains often *all* aspects of the Profile Tree from Environment at the top, all the way down to the Business Functions and all the deliverables for each Profile Tree Item. As the focus is on the aspects of Operations, items like Mission, Vision, Values are often omitted but can, if desired, be included. 
The level of detail of an Operating Model can be elaborate, for example it can contain details of how Staff communicate, how they are organised in terms of seats, how requests are managed, how infrastructure is implemented, how that infra is supported, how Staff is trained, etc. The level of detail can also vary by Activity if relevant. 
As a result of being all encompassing, the Operational Plan cannot be defined before Organising, Leading and Controlling, but instead is defined iteratively throughout the Management Cycle. The Operational Plan includes resilience which is the Venture's ability to withstand abrupt or dramatic changes in its Environment yet still function. As such, the Operational Plan is a blueprint of Operations and thus of the entire Venture. The Operational Plan feeds into the SWOT as the most detailed level of the Venture's internal workings. 

### Intel
Intel or intelligence is the collection of information of military, political, economical, financial, technological or generally operational or strategic value. Within Planning it is composed of two types: Venture Intel and Market Intel i.e. Intel from within and from outside the Venture.

#### Venture Intel
Venture Intel represents any form of Intel generated within the Venture. This goes across all internal aspects of the Profile Tree i.e. everything except for the Environment. It thus includes Intel from staff, Groups, Suppliers and Management and of course the Business Functions.

#### Market Intel 
Market Intelligence or Market Intel is external data generated outside the Venture. This data can be used for three purposes:
1. Comparison of Venture versus Competitors
2. Insight in the position within the market the Venture operates in.
3. Obtaining insight in where the Environment is going as a whole and which may force, the Venture to accommodate its plan, or it may create an opportunity for the Venture to seize.

Market Intel is a key contributor to the Strategy of the Venture. It feeds directly into SWOT, and more holistically, it gives a continuous feedback loop w/r to Goals and Objectives as well as input to the Strategy of the Venture. Market Intel may lead to renewed Vision, Mission, Goals and/or Objectives (mostly Projects) to steer the Venture according to the intel gathered and processed. 
There are different sources for Market Intel: newspapers, ex-colleagues, journals, academic research, consulting companies, head-hunters, magazines, websites, etc.
Critically, Market Intel also includes any sudden change in the environment that forces the Venture to react directly, and in a non-planned manner e.g. an incident at a competitor that puts a lot of negative news on the entire sector both the Venture and competitor operate in. 
________________________________________
## Organising
Organising involves Processes to establish *how to do it*.

This Management Function defines how Staff, Assets and Suppliers are organised to deliver the Strategy defined in Planning, and ultimately the Services. The result is an Organisation in which Staff know what to do and how, using Assets and Suppliers.

Key deliverables of Organising are:
- Activities (K)
- Groups (K)
- Roles & Responsibilities

### Activities
An Activity is essentially a container of Objectives that all work towards delivering one or more Services that are similar and/or related. Often this means that an Activity is framed by one or more Activity specific prd Sub-Goals representing those Services. Activities can roll up into other Activities, called regrouping or grouping of Activities. Activities are a fundamental part of RPT, see [### Reduced Profile Tree]. Grouping of Activities also includes the assessment of whether certain Activities should be outsourced outside of, or internally within, the Venture through Suppliers, see [## Suppliers]. Activities are linked to Groups, see below. The Profile Framework can be applied to an Activity in which case the Activity can be considered the Venture, and as a result, the Activity will have its own RPT. 

Deliverables for Activities are:
- Activity XXX

For each Activity XXX the following aspects can be relevant: 
- Overview: description which can include aspects like history. This may contain details as to how the Activity earns Revenue and manages Risk and Cost.
- Output: the Services being delivered (internal to other Groups, external to Clients). 
- Clients: the receiver of the Services: other Groups within the Venture or Clients. 
- Group: the Group that performs the Activity. 

A special Activity called ALL regroups all Processes that are transversal i.e. used in two or more Activities. Having such a transversal Activity helps centralising Process information like manuals etc in a single location.

### Groups
Once relevant Activities have been identified, Staff performing the same Activity can be identified and grouped. Note the use of *relevant*: It is possible to break work down in many different Activities but it has to be relevant to the Planning. 
The *Grouping of Staff* working for the purpose of a specific Activity results in Groups and different names exists for them: teams, department, etc. Groups are a fundamental component of the RPT, see [### Reduced Profile Tree] and thus the Venture.
Groups can also roll up into other Groups which is called regrouping e.g. several Teams can be part of a Division etc. The total structure of all Groups is called the Organisation of the Venture and the relation between them is reflected in an *Organisation Chart* or *Org Chart*. Groups permeate all Management Functions and as such are an important deliverable. 

Deliverables for Groups are:
- Group XXX

For each Group XXX the following aspects can be relevant: 
- Overview: description which can include aspects like history.
- Parent: Name of the Group this Group is part of. This permits setting up a hierarchy of Groups.
- Manager: the name of the Manager for the Group. This person is ultimately accountable for the performance of the Activity associated to the Group.

NB: in most cases an Activity equals Group. In other words, the Activity is determined by the existence of a Group of Staff performing Processes, and vice versa the Group of Staff performing the same Processes reflects the Activity. As such, above properties of a Group can be omitted and one can refer to the Activity. The details for Activity and Group can thus effectively be merged. Groups form the link between Activities and Staff. Therefore, the regular review of Groups implies regular review of Staff within the Group.

### Roles and Responsibilities
Once Activities have been identified and Groups have been defined, Staff need to be made aware of what is expected of them within the Group. This is defined through Roles & Responsibilities which formalises the Role of the Staff within a Group and the Responsibilities assigned to that Role through *delegating* or delegation.

Deliverables for Roles & Responsibilities are:
- Delegating
- Role
- Responsibilities
- Job Description 
- Other Roles

#### Delegating
Delegating is a key concept in the design of a Venture and is defined as:
1) the act by which a *Delegator* (mostly the Manager)
2) gives *Responsibility* for completion of a Process to 
3) a suitable *Delegatee* (Staff), including 
4) the associated *Authority* that goes with said Responsibility 
5) which bestows upon the delegatee *Accountability* to the Delegator for the Result of said Process, yet
6) without the Delegator losing the original *Accountability* which
7) requires *Oversight* from the Delegator over the Delegatee
NB: the singular *Process* can be read as an Objective, an entire Activity or Venture.

The Responsibility to perform a Process requires Authority which is the power or right to give orders and expect them to be obeyed (exact obedience), commit Resources (Staff, Assets, Suppliers), and make decisions. Clearly defined Authority is key in the ability to achieve the Result expected from the Responsibility of performing a Process. This goes two ways: 
1. The Delegatee knows which Authority was delegated; 
2. Staff, Group(s) and Suppliers subject to this Authority know that the Delegatee has obtained that Authority.
 
Once Responsibility has been Delegated, the Delegatee is automatically bestowed with the Accountability to *discharge the Responsibility* i.e., for the delivery of the Result of the Process. Accountability means one is liable to report to someone (Manager, CEO, Board of Directors, etc.) on the Result of a Process and face consequences if it is not achieved. 
Note that one can delegate Responsibility and Authority, but one *cannot* delegate Accountability! In other words, a Delegator *can* delegate Responsibility (and the Authority that goes with it), from which automatically flows the fact that the Delegatee owes Accountability to the Delegator. However, a Delegator *cannot* delegate that Accountability on a standalone basis i.e., cannot make a Delegatee accountable for a Process for which the Delegator has *not* delegated Responsibility nor Authority to the Delegatee.

As part of the overall Accountability the Delegator performs Oversight of the Delegated Process, and thus the Delegatee, to assure the expected Results have been obtained *and* in return to be able to report to the person who delegated the Process to the Delegator etc. Oversight is an integral part of Management Function Controlling, see [## Controlling].

In order to delegate a Process, the Authority that goes with a Responsibility must *permit* Delegation to take place. Without such permission a Process cannot be delegated.

A Manager can choose not to delegate i.e., to *retain* Responsibility and also Authority. A Manager can also claim responsibility back, a.k.a. to *revoke* Responsibility and Authority.

A Manager who has been delegated a Responsibility and Authority can delegate to someone else, provided that the Authority permits it. This is called *sub-delegation*.

It is technically possible to delegate Responsibility without also delegating Authority, resulting in *Accountability without Authority*. This is not desirable, but it happens. It essentially means that the Delegatee will depend on the Delegator to get access to resources, and to use the Delegator to exact obedience.

Escalation is the process of moving up the delegation tree to a level of Authority able to make a decision, commit resources or otherwise enforce obedience, because the person escalating does not have the Authority to do that him/herself.  

An often referred to term is "to discharge one's duties*" which is regulatory lingo for "completing one's responsibilities" or "completing the processes for which one was made responsible".

Last but not least, often Managers do not explicitly delegate Responsibilities to Staff within the Group they are the Manager: Responsibilities are often delegated by design of the Activity organisation within the Venture. Although this is not a restriction, it does mean that Managers may not always be aware of Responsibilities being fulfilled (or not!) within the Activity they are being held Accountable for!

In summary, when delegating Responsibility and Authority for a Process the Delegator remains accountable for the Result to whomever the Delegator is accountable to (Manager, CEO, Board of Directors, Shareholders,...), whereas, at the same time, the Delegatee becomes responsible for assuring the Process delivers the expected Result using the Authority granted and in doing so automatically becomes accountable to report to the Delegator with regards to said Result.

The above explains the fundamental concepts of delegating. There exist some subtleties. One is that Responsibility (and Authority) can be bestowed upon a Group instead of an individual Staff. This then means, in theory at least, that the Group is also accountable. This Accountability sits in reality with the Manager of the Group, not the entire Group. 

#### Roles
The Role of a Staff within a Group is indicative of two key aspects from the concept of Delegating discussed above: Responsibility and Authority. The Role is most often formalised with a Job Title and/or a Corporate Title. A Job Title is a short label indicating what type of Processes the Role is responsible for and potentially what type of Authority goes with that. The Corporate Title implies both a level of seniority as well as Authority e.g. Associate, Vice President, Senior Vice President, Director, Managing Director, etc.
A Role helps convey an overall idea of the level of Responsibility delegated to the Staff for a specific functional scope. In addition, it helps defining what type of Responsibilities can be delegated to Staff holding that Role. This is particularly useful for Managers. Note that it is possible to have more than one Role within a Group or across Groups! 

#### Responsibilities
Where the Role is high level and indicative, the actual Responsibilities detail what it is that Role is really responsible for. It should also, but often does not, clarify in detail the Authority the Role has to exact obedience i.e., whom should execute instructions from the Role, and for what type of Processes. Clearly defined Responsibilities are important for two reasons: a) the obvious one of making sure what it is a Staff or Group is expected to do, and b) less obviously, clarifies also what the Staff is *not* supposed to do. For a Manager clearly defined Responsibilities enable to assign work, by delegating to the best suited Staff or Group.

#### Job Description
The Job Description or JD is a document that formalises Roles, Responsibilities and Authorities. If often gives a high-level description of the Venture in which the Activity operates and a more detailed description of the Activity in which the Role operates to provide context. In addition, a JD also details required Skills and Experience.

#### Other Roles
It is possible that various positions are held either within or outside the Venture that do not directly contribute to the Job Description. The scope is broad but can include memberships of clubs within the Venture or, more commonly, positions held in outside organisations representing the sector the Venture is part of, or positions held within other Ventures e.g. Director on the board of a non-competing organisation.
Although such roles so not directly contributed to the. Entire, they can contribute to the well being of Staff or allow them to get a different experience and grow their Skills. 
________________________________________
## Leading 
Leading involves processes to *drive* or *motivate*  those *who do it*. 

This third Management Function entails directing, influencing, and motivating Staff to perform Operations as per the Planning and within the Organisation. It also involves the social and informal sources of influence to inspire others whilst considering concerns and issues the Staff may have. Effective Managers lead Staff through motivation to progressively attain Objectives.

Leading is often seen as a different manner to realise Objectives than managing. However, in the broader context suggested above, Leading and Managing go hand in hand. In effect, leadership involves a manner of *interacting* with Staff that is less based on a hierarchical position or authority (established in Organising) and more on an approach based on interpersonal skills. Leading, more than Managing, is key to drive Change. 

Change is the paradigm of Management in modern days. It is impossible for most Ventures to survive without a near continuous adaptation to a changing Environment: new and improved technology, changing demands, ever evolving constraints (social, economical, regulatory, political, fiscal). Change is a necessity for many reasons but also often viewed as a constraint or stifling force. Leaders propose and guide change throughout a Venture. By growing ideas, knowledge and individuals new Leaders will emerge within the Venture and prepare it for the future.

In below Key Deliverables the common theme is interaction. As such, a core Process involved in Leading is some form of communication with one or more individuals.
Note that none of the Key Deliverables for Leading are tangible nor easily measurable, unlike the deliverables for Planning, Organising and Controlling.

Key deliverables of Leading are:
- Safe Space
- Direction
- Collaboration
- Motivation
- Inspiration
- Learning
- Leaders

### Safe Space
Safe Space involves two aspects: General Safe Space and Psychological Safety. The former is the overall approach of a group of people towards subjects like inclusion, appreciation across all possible subjects of difference: gender, race, sexual orientation, religion, politics and more generally different perspectives. Psychological Safety refers to the belief that the work environment is safe for interpersonal risk taking. This refers to the experience of feeling able, and even obligated, to speak up with ideas, criticism, concerns or questions without risk i.e. without being scorn, seen as incompetent, ignorant, disruptive, betraying trust of the team etc. Psychological Safety is present when colleagues trust and respect each other and feel able, even obligated, to be candid. It is the responsibility of a Manager to assure a Safe Space is created such that all Staff are aware and can, and will, use it as intended.

### Direction
Directing is the Process of guiding, inspiring, overseeing and/or instructing Staff towards accomplishment of the Venture's Goals and more specifically Objectives. It is  the responsibility of a Manager to assure Direction is shared with all Stakeholders: Staff, Groups of Staff, Suppliers, senior Managers and Shareholders. 

### Collaboration
Collaboration is the Process of two or more people working together to achieve an Objective. People can be Staff but also Suppliers. Collaboration, a.k.a. Teamwork is a catalyst for knowledge sharing and creation. This in turn positively affects Motivation. 
It is the responsibility of the Manager to assure Collaboration is facilitated such that all Staff use it as an integral part of Operations.

### Motivation
Motivation is the Process of stimulating Staff to act in a *specific manner* to achieve Objectives. Motivation is a key driver for the success of a Venture. Motivated Staff are more likely to:
- Have a higher propensity to contribute to Safe Space
- To drive Collaboration, and thus 
- To to drive Innovation
- To take responsibility and become the Leaders of tomorrow
- To stay with the Venture for longer

It is the responsibility of the Manager to assure Motivation of Staff is achieved throughout the lifetime of the Venture.

### Inspiration
Unlike Motivation, inspiration is the Process of influencing Staff emotionally and mentally do be *creative*. As such Inspiration is a key deliverable to yield Change. In fact, rather than asking for a specific Change through Motivation, Manager's can generate Change, without asking, through Inspiring.
It is the responsibility of the Manager to assure Staff is inspired throughout the lifetime of the Venture.

### Learning
Any Venture will undergo Change and in order to accommodate that the entire Venture often needs to learn new aspects of one or more items of the Profile Tree. Often this relates to Technology, which grows at a fast pace, but it also includes changes in Management theory, including Leading. 

### Leaders
A key deliverable for Managers, is to help groom the leaders of tomorrow. Managers need to know how to lead, but they also need to prepare the new leaders for the future. This is done through identification of potential leaders and grooming them through above Processes.
________________________________________
## Controlling
Controlling involves Processes to establish *how well it was done*.  

This fourth Management Function continuously measures output of Operations versus some form of reference, which is in most cases the Benchmark determined in Planning, and adjusts where necessary through the other Management Functions: Planning, Organising and Leading. 

In other words, for Goals and Objectives defined in Planning, the Management Function Controlling will check whether the targeted results were achieved. This means that even if a Goal is itself related to Checks with regards to production Processes,it is Controlling that verifies whether those Checks achieved what they were set out to do!

Controlling is performed through Controls, which in general involve 7 steps: 
1. Establish the *Purpose*;
2. Establish *Baseline* or Benchmark (often done in Planning); 
3. Get *Measurement* of the output of Goals/Sub-Goals/Objectives;
4. Perform a *Comparison* of Measurement vs Baseline;
5. Perform an *Analysis* of differences from the Comparison and, if relevant;
6. Define some form of *Remediation*;
7. Keep a *Written Trail* of 1-6, use it to *Report* and track Remediation.

The Control's Purpose, is fundamental. It sets out what a Control aims to achieve and why that is relevant. Particularly for Staff (or other Stakeholders) who are not privy to all details of the Operations a Purpose helps setting the stage for understanding steps 2 to 6 and, more generally, facilitates the performance of controls without needing to acquire a vast background knowledge. This is particularly important for Checks, see below. 

The Benchmark establishes *expected* Results from the Goals and Objectives defined in Planning. Often, the Benchmark is referred to as KPI (Key Performance Indicator), or KRI (Key Risk Indicator) depending on whether the Objective is Profit or Risk related. Other indicators are possible e.g. KEI (Key Efficiency Indicator). When Controlling Goals and Sub-Goals measurement is done against an overall expected outcome. 

Depending on the Objective, Measurement requires a clearly defined Process describing how to measure the outcome of Objectives i.e. how to collect Data, how to create Information from the data to perform the actual Measurement from it, or it can do without such detailed steps. Measurement also considers the type:  binary (done, vs not done), quantitative (100 EUR, 1000 lines of code,...) or qualitative (glossy, pleasing to the eye, increased sales) with a preference for quantitative measures.

The Comparison can be expressed as count, percentage etc. and that in tables, graphs or any format that makes the Comparison easy to interpret.

An Analysis consists of reviewing the Comparison and drawing conclusions as to how well the Objective was achieved. Depending on the type of Objective, Analysis as a Process can be simple, but for certain Objectives filtering, discarding outliers etc. may be required. Analysis should yield conclusions as to *why* there are differences between Measurement and Benchmark. The *why* should be explained as part of the Process to achieve the Objective either because of issues within the Process or because other Processes negatively (or positively) affecting the Objective's Process.

Remediation consists of defining actions from the conclusions from Analysis. These actions will need integration in Planning, Organising and/or Leading.

Key deliverables of Controlling are:
- Journal
- Supervision 
- Reports
- Monitoring

### Journal
A Journal reflects the result of Journaling which is the Process of ongoing recording of relevant topics in a Journal as Journal entries, which is similar to a ship's log book. For the purpose of Management this  includes *all* topics that occur throughout Management i.e. Journaling is *not* limited to Controlling. Well established Journaling aids in *all* Management Functions. Journaling can be time intense, depending on how much of it the Manager does versus how much the Manager has it done for him, or her, by someone. Another factor is the format of Journaling; using pen and paper, spreadsheets, databases, etc.

### Supervision 
The various steps of Controlling, described above, are fundamentally captured in Supervision. Supervision can be applied to every part of the Venture. 
The manner in which Managers decide to assure Supervision is done through a Supervision Framework. The Supervision Framework frames which Supervision Processes are applied to which Supervision Scope.

There are four *Supervision Processes* a.k.a. Controls: *Check*, *Review*, *Attendance* and *Audit*. Note that Control is taken broadly, and as can be seen includes attending for example a Committee.

#### Check 
A Check: is the full cycle described above i.e. understand the purpose of the Control to be performed, verify the result of a Process against a predetermined threshold and remediate of there is a deviation. This has a strong focus on *avoiding Risk* and/or *assure Service quality*. Checks are most often performed periodically, with a focus on breaches between Measurement and Benchmark. They tend to be performed on Routines, more than on Projects. Often, when a Control is referred to, it means a Check in terms of this Management Framework.

#### Review
A Review is a verification of the result of a Process against a Manager's (or other relevant Staff's) opinion based on experience and knowledge and potentially some benchmark. It is generally less formalised than a Check. A Review is an often used method to verify progress (Performance) and/or zones of risk within Operations and/or Management and/or Clients in combination or not with the Environment (Market Intel). A Review may also act as a validation as part of a mandatory step in a broader Process. Note that the Process for Review may differ on a case by case basis. Review, is mostly performed periodically. Unlike Checks, Reviews rely on a more holistic knowledge of the Processes being reviewed as well as the Activities those Processes are part of. When doing a Review, the second step, Establish Baseline, is replaced by that holistic knowledge. 

#### Attendance 
An Attendance a.k.a. Meeting is similar to Review except that the Manager's opinion is replaced by a meeting with a group of people most often referred to as a *Committee*. Attendance can include the preparation of the Committee if the Manager is Chair of the Committee. Committees are mostly periodic. Certain committees e.g. Board of Directors are highly formalised and scrutinised. 

#### Audit
An Audit is an independent verification of part or whole of the Profile i.e. not just Results of Processes but also the Processes themselves! Audits are done by a Group not directly related to either Operations or Management. An Audit uses a broad range of Processes to obtain results that provide sufficient insight. Audits verify Processes and Results and work against a broad range of benchmarks defined at the start of the audit e.g. revenue targets, regulatory obligations, and/or Routine execution time etc. Unlike the previous Monitoring types, Audits are mostly ad-hoc and can often be considered a Project.

Supervision Processes can result in a need for improvements which are addressed through Projects.
Supervision Processes are applied to the *Supervision Scope* which refers to what it is the Managers want to supervise. In general. the Supervision Scope is the entire Venture, specifically Operations, against the backdrop of the constraints imposed by the Environment. However, depending on the manner in which a Venture is run, Managers may choose to use a different categorisation of the scope with the ultimate objective to still cover Supervision of the Operations. 
The following are the most common Supervision Scopes, but others may be possible, depending on the Venture.

#### Activity Based Scope
In the Activity Based Scope the Supervision Processes are applied on Activities. This means that if a Venture has many Activities, there is a change that similar topics e.g. Finance, or HR are recurring often across the Activities, which may not be an efficient use of Resources. On the other hand, it has the Advantage that Activities are well understood. 

#### Business Function Based Scope 
In the Business Function Scope the Supervision Processes are applied to the Business Functions, which each cover a specific aspect of the Venture but across all Activities. 
This type of scope, avoids the problem mentioned above for a Venture with many Activities. On the other hand, if a Venture has defined only a few specific Business Functions, some functional aspects of the Venture may not be well covered. 

#### Hybrid Based Scope
The Hybrid Based Scope is a combination of the Activity Based Scope and Business Function Based Scope, and allows Managers to use different manners of Supervision. 

The output of the Supervision Framework i.e., Supervision Processes applied to the Supervision Scope is used by the Manager to make decisions. Dissemination of the results from Supervision can be done through various, potentially complementary means: mails, committees, dashboards, etc. This also includes overseeing all work delegated to Staff and Groups.

### Reports
A Report aims at informing someone (the Receiver) of facts and/or opinions/alerts/etc (the Content) by someone (the Reporter) for a specific reason (the Purpose). 
The Receiver can be one or more persons and can be a Manager, Staff, Supplier, Project Team, Stakeholder, etc. The content of a Report is mostly in written form (mail, memo, but could also be through a presentation either orally and/or with a deck, or even more formally through a booklet like Financial Statements. The Reporter consists of the person(s) disclosing the Report and can be a Manager (to his/her Manager), a Staff (to his/her Manager), the board (to Shareholders) etc. The Reporter often, but not always, prepares the Content.

The Purpose of a Report depends on the previous aspects as follows:

#### Management Report
A Report for a Manager provided by a Staff, a Group or Business Function or a a Manager! 
The Purpose is for the Manager to oversee Results from the Processes that were delegated (Routines and Projects) and adjust where necessary i.e. the focus is performance. In addition, this report is also used to report on concerns coming from the Environment (Market Intel). 
The Manager may obtain multiple Reports for each of the Managerial 7.

#### Staff Report
A Report for Staff or a Group. The purpose of such Report is to inform Staff how they are performing on their Job Description. It is used by the Manager to get indirect insight into the Managerial 7 and is important for Staff to know where to adjust time, focus, resources, or to highlight bottlenecks in output.   

#### Marketing Report
This is a Report that is tailored to the Strengths of the Venture and can be used for Clients, or more generally any Stakeholder. 

### Monitoring
The content of the Report yields a cycle of feedback and follow-up. Feedback comes in the form of suggestions for improvements. These suggestions are translated into actions and these need to be planned and monitored. Planning is done in the Planning cycle of Management, or within Operations if the action is to improve Run or Change. In all cases, it is important that any actions determined within a Supervisory Process is closed timely.
________________________________________
## Tools
In the above sections we saw what makes up a Venture. To aid in managing this complex structure, a Manager can use Tools composed of *Frameworks*, *Procedures* and *Software*.

A Framework is a conceptual structure intended to support a specific aspect of a Management Function's Processes. It gives guidance and direction, but not solutions.
Example: Value Chain is a Framework that helps defining internal forces of a Venture within SWOT.

A Procedure is an established or formalised manner of performing a Process. It is a well documented explanation of what to do, how, where, when, and by whom. Procedures are used to define, configure and perform certain Processes in an optimal manner. Unlike Frameworks, Procedures yield precise Results, but it does involve manual work.
Example: managing email. 

A Software is downloaded for free, purchased or it is built. It achieves a specific outcome either by configuration, automating a manual Process, and/or by simplifying a Process even if it remains partially manual. Software mentioned in this note has configuration in dedicated OVH: ITC-xxx notes (perso  and work).
Example: a Note Taking application. 

More details in: [MGT: 80.Tools].
________________________________________
## Business Functions
Business Functions are functions within a Venture that provide specialised services permitting the Venture to operate its core activities. The difference between Suppliers and Business Functions is that the latter is often deemed internal to the Venture and often, but not always, has a strong focus on services provided to Management and less to the Operations. Which is mostly covered by Suppliers. Another difference is that details w/r to Business Functions focus on the Processes involved, whereas for Suppliers they focus on the Profile of the Supplier.

In very small corporations Business Functions may be performed by the Manager as part of Operations, whereas in very large corporations those functions are performed by dedicated departments. Alternatively, Business Functions can be outsourced (creating a dependency on Suppliers). 

A typical example for a financial institution follows and is used throughout the sections below:
- Finance (applies to Revenues, Cost and Funding)
- Human Resources (applies to Staff)
- IT (applies to Operations)
- Risk (applies to Operations)
- Compliance (applies to Environment)
- CorpSec or Corporate Secretary, composed of:
    - Legal (applies to Environment)
    - Tax (applies to Environment)
- Procurement (applies to Suppliers)
- Others, including:
    - Marketing (applies to Clients, Services, often an Activity)

NB: Operations (a Profile Tree Item) is *also* considered a Business Function, but in the Profile it is not. The above may be re-organised differently according to the type of Venture (Manufacturing, Service, Charity) and the sub-type within (Petrochemical, Cars, etc and Bank, Utilities etc).

The following sections cover the Business Functions:
________________________________________
## Finance
Finance, or more holistically Accounting & Financing is the Business Function concerned with measuring and reporting financial items related to the Venture and to assure Funding is available to start, and continue, the Venture (going concern principle).

Key deliverables of Finance are the following:
- Accounting
- Financing

### Accounting
Accounting assures the Accounting Cycle is performed. Essentially this means: 
1. Collecting and processing of financial data like Assets, Liabilities, Equity, Revenue, Expenses (Cost) and Dividends (Withdrawals) and assuring the Accounting Equation remains balanced:  A = L + E + R - E  - D 
Note that a key part of Accounting includes Processes to formalise in which manner Revenues are *recognised*, same for Expenses, Assets, Liabilities, etc. Such recognition should be formalised throughout the Venture.
2. Reporting of those data both economically and accounting-wise through relevant reports for internal and external use e.g. Balance Sheet, Income Statement, Statement of Cash flows, and any Key Performance Indicators (KPI) that are relevant to the Venture.

### Financing
Financing a.k.a. Corporate Financing is concerned with implementing a corporate, or legal, structure and funding that structure as a going concern i.e. for continuous Operations. It has the following key elements:
1. Initial Funding for Assets, Staff and Suppliers and 
2. Continuous funding for Operating Costs
3. Investing in the Future of the Venture (funding Projects)
4. Optimizing the above a.k.a. Capital Management 

As discussed in [## Liabilities] & [## Equity]Financing can be achieved through various manners:
- Long term debt  
- Short term debt including overdraft
- Purchase on credit 
- Share issuance
- Retained earnings

This deliverable is also referred to as Financial Planning or Budgeting. NB: in some text books Finance & Accounting are each considered separate Business Functions. 
________________________________________
## Human Resources
Human Resources a.k.a. HR is the Business Function concerned with attracting, training and retaining Staff with the right Skills within the boundaries of employment laws. 
A Skill is defined as the learned ability to perform a Process such that the expected Result is yielded within the constraints and dependencies imposed on the execution of said Process. 
In addition, HR is also the central function for disseminating the Venture's Mission and Values.
Although managers are heavily involved in the various deliverables involved in HR, the Business Function HR is central to the overall functioning.

Key deliverables of HR are the following:
- Recruitment
- Skill Management
- Training
- Performance Management
- Remuneration Management
- Employee Relations
- Employment Law

### Recruitment
Recruitment is the Process of attracting Staff with the right Skills i.e. for a specific Job Description. 

### Skill Management
Skill Management is the function defining Skills as well as measuring those Skills in prospect and existing Staff. Skills are formalised in the Job Description (see above). 

### Training
Training is the process of adding new Skills or improving existing Skills through various means. 
 
### Performance Management
Performance Management is the function defining the setting of Objectives for Staff as well as measuring how well Objectives were met. Objectives are as per the Planning and include both Routines and Projects. An important aspect of Performance Management is reviewing *how* Objectives were achieved.

### Remuneration Management
Remuneration Management details the manners in which Staff can be attracted and retained. 

### Employee Relations
Employee Relations refers to the relationship with Staff on a broader basis. It includes creating awareness of the Venture's Values, providing a platform for dispute resolution, etc.

### Employment Law
Ventures operate under various laws depending on the Environment in which they operate. Most countries have some form of Employment Law and the HR department's role is to assure compliance with such laws.
________________________________________
## IT
Information Technology (IT) or Information & Communication Technology (ICT) are two different but very similar topics. IT includes use of computers, networks, software and other electronic or digital devices for the management and communication of information. ICT focuses more on how digital technologies assist users in handling information. Without going into details of the subtle differences. 
IT including ICT is critical to most Ventures because the majority of Input in the various Processes throughout a Venture are all digital. Even if an Activity's purpose within a Venture is to make say closets from wooden plates, the details of the inventory used (Asset) are all stored digitally, as are details of the Suppliers delivering it including detail of shipment etc as are details of the end-products, and to which Clients they go. Even the manufacturing Process itself can be wholly or partially automated, which means, again, IT involvement.

Key deliverables for IT are:
- Infra
- Applications

### Infra
IT Infrastructure or Infra is the total of hardware and software needed to run Applications. This includes, but is not limited to:
- Servers
- Routers
- Switches
- Cables
- FIrewalls
- NAS
- SAN
- Cloud
- System Software

Most of the components above have a minimal software referred to as system software. This includes operating systems and  utility software. Both have no direct use for the Services  of the Venture. The latter includes backup-software, anti-virus etc. 

### Applications
Applications are the software used within a Venture and that aid the Venture directly or indirectly in producing the Services. There are two main types of Applications:
- Supplied Applications
- In-house Applications

The former is all off-the-shelf software. This is mostly software that is not part of the core Services of the Venture, and which as such do not have, or lead to a competitive edge.  The latter is software that contributes directly to the Services and either may have a competitive edge and/or has features that cannot be found in off-the-shelf software.
________________________________________
## Risk
Risk is both a result from Operations as well as the name of the Business Function dedicated to the management of Risk from Operations.
Risk as a Business Function is concerned with the assessment of Risk resulting from the performance of Operations which includes both risk embedded in the Services resulting from Operations as well as the Risk that the performance of Operations engender. Assessment includes analysing, measuring, comparing to benchmarks of Risk as well as defining plans to mitigate said Risk. 

There are different classifications of Risk:
- Financial Risk (mostly financial institutions)
- Operational Risk (all type of Ventures)
- Regulatory Risk (all Ventures)
- Legal Risk (often considered part of Operational Risk) 
- Tax Risk (often considered part of Operational Risk)
- Reputational Risk (often considered part of Operational Risk)
- Strategic Risk: all types of Ventures
________________________________________
## Compliance
The Business Function Compliance is concerned with the assessment of compliance with rules and guidance imposed by the Environment and potentially compliance with internal rules and regulations.
Regulations are defined by regulators and can involve all types of topics:
- Environmental (nature, polution)
- Client protection (ombudsman, financial regulations, data protection)
Etc.

Effectively, Compliance is concerned with a specific form of Risk mentioned above: Regulatory Risk. 
________________________________________
## CorpSec
Corporate Secretary also referred to as Corporate Secretariat, is the Business Function concerned with two key corporate functions that apply to the Venture transversally:  Legal and Tax. 

### Legal
The Business Function called Legal is concerned with the assessment of contractual obligations the Venture engages or envisages to engage with Stakeholders (this can thus be internal as well as external) or, by virtue of law, is applicable to the Venture. This also involves anything related to the obligations that weigh upon legal entities involved in the Venture. 

Deliverables for legal are:
- Legal Opinions
- Court Cases

### Tax
The Business Function Tax is concerned with the assessment of tax obligations the Venture is required to comply with as part of its role in the Environment, including arm's length principles across wholly or partially owned legal entities in different countries involved in the Venture.

Both are each concerned with a specific form of Risk mentioned above: Legal Risk and Tax Risk, and which both work on the Venture level, particularly if the Venture is a listed company.

### Legal Entities
The legal scope of CorpSec is also concerned with legal entities, which, from a Profile perspective are captured under Assets, and for which the data is owned by Legal.  
________________________________________
## Procurement
Procurement a.k.a. Supply Chain Management a.k.a. Purchase is the Business Function concerned with defining which Suppliers would be best suited to provide Assets and Services, Staff (in the form of Consultants), and attracting and retaining these Suppliers, whilst controlling the Cost related to the Suppliers.
________________________________________
## Other

### Marketing
Marketing is the Business Function concerned with intentionally stimulating demand for and purchase of goods and services. It includes defining target *Clients*, attracting them and retaining them. Defining Clients involves establishing the Services and/or Products the Clients desires/needs as well as pricing those services/products and establishing how to advertise the Venture's capabilities to deliver the Services/Products in a manner optimal for the Client. From a Management perspective the Sales activity is part of Marketing. In many cases, Sales and/or Marketing are considered Activities instead of Business Functions. 

Key deliverables of Marketing are the following:
- Product / Client
- Price / Cost
- Place / Convenience
- Promotion / Communication


*********************************************
# INDEX
This section explains which Expanded Profile Tree Item and which Deliverable a topic is part of. If relevant, details within the Deliverable are provided.
________________________________________
## List
Below list is in alphabetical order of the topic. 

Topic | Expanded Profile Tree Item | Deliverable 
- Legal Opinions | CorpSec |Legal
- Transversal Processes | Activity | special Activity ALL


*********************************************
# LEGEND EXPLAINED
This section explains the background of some fundamental concepts used in this note.
________________________________________
## Use of Markdown
By using Markdown, see also [## Note Content], which is a widely used standard, all notes adhere to a form of standard that can be converted to HTML on a whim. Major advantages of Markdown are:
- Portability: use with any editor
- Scope: use for books, notes, tech docs,...
- Platform independence: use on any device, any OS
- Future compliant: accommodate future demands
- Broad use: many sites including GitHub use it
________________________________________
## Section Separators
The reason to use separators just above level 1 and 2 sections is because one of the core principles underpinning this legend is that notes should be created and maintained using any tool. Some tools may not have different header fonts for example. So by using standard keyboard combinations there is no dependency on the functionality offered by a note-taking app whilst allowing for clear visual separators.
________________________________________
## Length of Section Separators
The length of section separators is such that on a SmartPhone is does not wrap around and even has some extra margin, in case font size is increased.
________________________________________
## Format of Note Name
The formalised name format is for multiple reasons:
1. Force the use of Note Categories: clarifies type of content of a note.
2. Assure short names


*********************************************
# SPECIAL SYMBOLS
There are numerous special symbols that are available in UniCode (see: https://en.wikipedia.org/wiki/Unicode) but not readily on any keyboard. This section has UniCode symbols that are accepted in the majority of text editors.

@ = missing symbol
________________________________________
## URL
<https://unicode-table.com/en/>
<https://en.wikipedia.org/wiki/List_of_mathematical_symbols>
<https://en.wikipedia.org/wiki/Greek_alphabet> <https://en.m.wikipedia.org/wiki/Mathematical_-Operators_(Unicode_block)>
<https://www.compart.com/en/unicode/U+1D4A>
<https://www.rapidtables.com/math/symbols/Basic_Math_Symbols.html>
________________________________________
## White space
See also [## Note Content]
" "   em space character
" "     en space character
________________________________________
## Currency Symbols
¥    JPY
$    USD
€    EUR
£    GBP
________________________________________
## Greek Symbols
Capital  Normal -Subscript Superscript
Α α 	@ ᵅ    alpha
Β β ᵦ ᵝ    beta
Γ γ ᵧ ˠ    gamma
Δ δ @ ᵟ    delta
Ε ε @	ᵋ    epsilon
Ζ ζ @	@    zeta
Η η @ @    eta
Θ θ @	ᶿ    theta
Ι ι @ @     iota
Κ κ @ @    kappa
Λ λ @ @    la(m)bda
Μ μ @	@    mu
Ν ν @ @    nu
Ξ ξ @ @    xi
Ο ο @ @    omicron
Π π @ @    pi
Ρ ρ ᵨ @    rho
Σ σ/ς @ @    sigma
Τ τ @ @    tau
Υ υ @ @    upsilon
Φ φ ᵩ ᶲ    phi
Χ χ ᵪ ᵡ    chi
Ψ ψ @ @    psi
Ω ω @ @    omega
________________________________________
## Mathematical Symbols
ℂ  Complex numbers
ℝ  Real number (subset of ℂ)
ℚ  Rational numbers (subset of ℝ)
ℤ   Relative integers (subset of ℚ)
ℕ   Natural integers (subset of ℤ)
∂ 	Partial derivative
±    Plus/minus
∓   Minus/plus
÷    Division
√    Square root of  
≈    Almost Equal, Approximately Equal
≠    Inequality
≤    Smaller than or equal to
≥    Greater than or equal to
≫  Much greater than
≪  Much smaller than
∅   Empty Set
∈   Element of a set 
∉   Not an element of a set
∫     Integral
∬   Double Integral
∭  Triple Integral
∯   Surface Integral
⌠ 	Top half of an integral
⌡ 	Bottom Half of an integral
≡   Equivalence
≉  Non-equivalence
∝  Proportional to
e   constant e
π   constant pi
∑   Sum of
Π  Product of
∞   Infinity (lemniscate)
⊗  Tensor product
⊖  ???
⊕  ???
⊜  ???
∡  Measured angle
⊥  Orthogonal angle
∇   Nabla
∙   Dot product
xˉ x bar
ȳ  y bar
________________________________________
## Various Other Symbols
©   Copyright symbol
®   Registered symbol
™    Trademark symbol
________________________________________
## Arrow Symbols
↺  arrow circle anti-clockwise
↻  arrow circle clockwise
⇑  arrow north
⇓	 arrow south
⇗	arrow north-east
⇖	arrow north-west
⇘	arrow south-east
⇙	arrow south-west
⇕  arrow north-south
⇒ arrow east
⇐ arrow west
⇔  arrow west-east
⇆  arrow back-forth
↶	arrow semi, anti-clock wise
↷	arrow semi, anti-clock wise
________________________________________
## Superscript Symbols
⁰ 	superscript zero 	
¹ 	superscript one 	
² 	superscript two 	
³ 	superscript three 	
⁴ 	superscript four 	
⁵ 	superscript five 	
⁶ 	superscript six 	
⁷ 	superscript seven 	
⁸ 	superscript eight 	
⁹ 	superscript nine 	
⁺ 	superscript plus sign 	
⁻ 	superscript minus 	
⁼ 	superscript equals sign 	
⁽ 	superscript left parenthesis 	
⁾ 	superscript right parenthesis
· 	superscript comma / dot (not 100% accurate)
° 	degree (temperature or angle) 	
⁄ 	slash for fraction
ᵃ superscript a
ᵇ superscript b
ᶜ superscript c
ᵈ superscript d
ᵉ superscript e
ᶠ superscript f
ᵍ superscript g
ʰ superscript h
ⁱ superscript i
ʲ superscript j
ᵏ superscript k
ˡ superscript l
ᵐ superscriptm 
ⁿ superscript n
ᵒ superscript o
ᵖ superscript p
@ superscript q 
ʳ superscript r
ˢ superscript s
ᵗ superscript t
ᵘ superscript u
ᵛ superscript v
ʷ superscript w
ˣ superscript x
ʸ superscript y
ᶻ superscript z
ᴬ superscript Capital A
ᴭ superscript Capital  AE
ᴮ  superscript Capital B
ᴰ superscript Capital D
ᴱ  superscript Capital E
ᴳ superscript Capital G
ᴴ superscript Capital H
ᴵ superscript Capital I
ᴶ superscript Capital J
ᴷ superscript Capital K
ᴸ superscript Capital L
ᴹ superscript Capital M
ᴺ superscript Capital N
ᴼ superscript Capital O
ᴾ superscript Capital P
ᴿ superscript Capital R
ᵀ superscript Capital T
ᵁ superscript Capital U
ᵂ superscript Capital W
________________________________________
## Subscript Symbols
₀ 	subscript zero 	
₁ 	subscript one 	
₂ 	subscript two 	
₃ 	subscript three 	
₄ 	subscript four 	
₅ 	subscript five 	
₆ 	subscript six 	
₇ 	subscript seven 	
₈ 	subscript eight 	
₉ 	subscript nine 	
₊ 	subscript plus sign 	
₋ 	subscript minus 	
₌ 	subscript equals sign 	
₍ 	subscript left parenthesis 	
₎ 	subscript right parenthesis 	
ₐ  subscript a
@  subscript b
@  subscript c
@  subscript d
ₑ  subscript e
@  subscript f
@ subscript g
ₕ  subscript h
ᵢ  subscript i
ⱼ  subscript j
ₖ  subscript k
ₗ  subscript l
ₘ  subscript m 
ₙ  subscript n
ₒ  subscript o
ₚ  subscript p
@  subscript q
ᵣ  subscript e
ₛ  subscript s
ₜ  subscript t
ᵤ  subscript u
ᵥ  subscript v
@ subscript w
ₓ   subscript x
@  subscript y
@   subscript z
________________________________________
## Fraction Symbols
½
⅓
⅔
¼ 	
¾
⅕
⅖
⅗
⅘
⅙
⅚ 	 
⅐
⅛
⅜
⅝	
⅞
⅑
⅒


*********************************************
# VERSIONS
Versions are using yyyymmdd. Each version has a level 3 header. Future improvements are recorded in [### Planned]. Once an actual date is put in a header the version is deemed released.
________________________________________
## List of Versions

### 2021013
- Initial version of this note including formatting. 
NB: Exact implementation date not recorded.

### 20210331
- Created the notion of Profile in Perso: Legend. 
- Added Profile in MGT: Management and Perso: Objectives.
NB: Exact implementation date not recorded.

### 20210531
- Added this versioning section. 
- Added Markdown in [## Conventions within Notes]
- Updated method of indicating headers of sections
- Changed note reference [* ] to [=] because Markdown makes * italic.
- Modified all notes: Markdown, sections, references 

### 20210615
- Changed perso context categories to 3 capital character acronyms in [## Note Category].
- Added notion of tables in [## Specifics Work]

### 20210604
- Changed PRS: Objectives to MGT: Management (same for MGT: Objectives)
- Added in [# PROFILE] one note for each item in the Profile tree.

### 20210618
- Changed [## Work Notes for Meetings] to use systematically 3 section levels
- Changed [## ## Work Notes for  Governance] to use  strictly same logic as in [## Work Notes for Meetings] when governance is related to meetings.

### 20210628
- Added MGT as category within perso context and dedicated that to all notes related to the 'Profile'.
Renamed PRS: Legend to MGT: 99.Legend in perso context.
- Work context notes follow the same principles.

### 20210706
- Updated [### Markdown] with clearer level 4 headers.

### 20210713
- Updated [# WORK SPECIFICS] to use MGT: Strategy [=] for the roadmap i/o MGT: Management [=] / MGT: Staff [=]
- Updated [# PROFILE] with clearer guidelines for dedicated MGT notes

### 20210719
- Added job description in [## Staff] in [# PROFILE]
- Added [### Sections] and the constraint that every level N section requires a N-1 section.
- Changed Objective Status for routine to '&' and Reference Indicator from '=' to '~'. The reason for the latter is that excel tries to make '=' a formula in tracker.py when exporting to csv.
- Space between '~' and '#' optional in [## Note Reference] and [Objective Reference]

### 20210725
- Added [# PERSO SPECIFICS] with few directives
- Updated [# PROFILE] with no directives 
- Updated [# WORK SPECIFICS] with many directives
- Update [## Management]  and [## Tools] with Planning, Organising, Leading, and Controlling (the four key activities of Management).

### 20210822
- Overhaul of [## Note Reference]
- Overhaul of Objectives + moved to [MGT: Tools]
- Overhaul of [# PROFILE], see also [PRJ: Framework]
- Overhaul of all MGT: xxx notes

### 20210824
- Updated [## Note Reference] to allow files and URL
- Made the note read only again

### 20210901
- Updated [## Note Categories] to use Goals
- Updated perso categories in [MGT: Planning] 

### 20210905
- Updated [## File Reference]

### 20210908
- Added [## Environment]

### 20211107
- Added  [### Superiors] in [## Leading] 
- Updated [### Safe Space] in [## Leading] with the notion of Psychological Safety.
- Updated [## Leading] to have more meaningful  deliverables

### 20211228
- Updated Human Resources to focus on Skills
- Added L3 sections in Human Resources

### 20220102
- Updated [## Profile Introduction] adding notion of Top and Bottom Profile
- Updated [## Services] and [## Operations] to reflect the fact that they are respectively represented by [## Goals] and [## Objectives].

### 20220110
- Added [## Reduced Profile Tree]
- Added prescriptive details to Suppliers, Assets, Staff, Activities and Groups 

### 20220113
- Updated logic for Objective Notation to have links for both Goals (to Activities, new) and Objectives (Goals, existed already)

### 20220124
- Updated the notion that Management does have a MGT; xxx note

### 20220127
- Added notion of Resilience in Planning

### 20220128
- Added type of Tools from [MGT: Tools] to [## Tools]

### 20220202
- Closed out [MGT: Tools] and MSS as projects. They continue in maintenance mode.

### 20220208
- Updated [## Assets] overview to differentiate between tangible and intangible

### 20220215
- Changed license from a single GNU license to a combined Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International + GNU Public License.

### 20220306
Formalised the fact that in work context:
- Routines can be broken down in Subs and Drills
- Projects can be broken down in Streams and Actions

### 20220313
Added a paragraph (not section) on Management vs Leadership in [## Management]

### 20220319
- Clarified how Goals are Venture wide and Objective are Activity specific.  
- Reorganised the Reduced Profile Tree so that it better reflects the order of POLC

### 20220326
- Deleted [# FILES] and integrated it in [## Note Reference]
- Added [## Leadership Attributes]

### 20220330
- Updated [## Suppliers] with: Embedded / Internal / External Suppliers
- Updated [## Organising] to reflect the above

### 20220331
- Updated [## Planning], [## Organising] to reflect that Objectives are hierarchically linked to Goals but also have a link to Groups (=Activity) which thus means Activities are composed of one or more Objectives

### 20220409
- Updated [### Operational Plan] to make it the link between all elements of the POLC.

### 20220415
- Added [## Management Cycle]
- Added [### Delegation] which was already a Tool in [MGT: Tools]

### 20220418
Full review of text with corrections and clarifications throughout.

### 20220421
Reduced key deliverables in [## Planning], [## Organising], [## Leading] and [## Controlling].

### 20220426
Updated [## Leading] to incorporate [### Direction] and moved [### Delegation] from [## Leading] to [## Organising].

### 20220427
Updated [## Leading] to incorporate [## Training]. Note that it might be moved to Organising, as it could fit in there as well.

### 20220525
Updated [### Journal] to reflect that it covers all forms of meetings with individual Staff, Groups and Suppliers. 

### 20220606
Added [### Context] in [## Planning]. 

### 20220609
Changed logic to use XX. in front of all Profile Tree Items with X being digits 0-9.

### 20220807
Added the notion of Policies in [### Operational Plan].
Added the notion of Board of Directors to [### Management Level].

### 20220814
- Created a new section [### Bylaws] in [## Planning]
- Moved [### Income] from [## Services] to [## Operations] in [MGT: 99.Legend].

### 20220907
- Added hierarchies [## Planning]

### 20220924
- Added the 5 specific Review items in [### Review].

### 20221022
- Added notion of Value & Control Chain in [## Operations].

### 20221119
- Updated [### Objectives] with 6W as it is so fundamental.

### 20221207
- Updated CorpSec details to include the notion of legal entity.

### 20221215
- Moved the Business Functions into the Profile Tree

### 20230112
- Split Deliverable Review under [## Controlling] in Control, Assessment and Audit.

### 20230127
- Updated [### Goals] to include Sub-Goals.

### 20230309
- Deleted all sections [### Appendix] in [# PROFILE]

### 20230311
- Updated section on Risk including insurance. 

### 20230218
- Rewrote [### Roles & Responsibilities] by adding [#### Delegating] from [MGT: 80.Tools], and breaking the Role and Responsibilities out in dedication L4 sections, and adding [#### Job Description]

### 20230219
- Updated [# PROFILE] to have a first section that is essentially an Executive Summary that can be copied in other notes.

### 20230226
- Updated [# PROFILE] notably the sections dedicated to Business Functions.

### 20230301
- Updated [## Profile Exec Summary] notably the sections dedicated to Management.

### 20230307
- Renamed [## Profile Exec Summary] to [## Profile Overview] and rewrote the content a bit.

### 20230309
- Completed [## Profile Overview] for use in production.

### 20230314
- Added mgt as Goal in [## Profile Overview] and enumerated all Goals 

### 20230323
- Updated [### Market Intel] with sudden changes. 
- Updated [### Supervision] with the *Big 6" and broke [### Reports] down in more detailed L4 sections.  

### 20230325
- Changed [### Market Intel] to [### Intel]. Reflected the same change everywhere else.

### 20230329
- Changed [## Profile Overview] to include Processes in the definition of Risk

### 20230401
- Updated [## Profile Overview] to include Products in addition to Services

### 20230405
- Reduced importance of personal context as a preparation to release the content to GitHub.

### 20230414
- Created [## Expanded Profile Tree].

### 20230427
- Updated [### Goals] in [## Profile Overview] with more details about sub-Goals including for Run.

### 20230501
- Updated [## Profile Overview] to clearly reflect that Services are embedded in Sub-Goals. 

### 20230520
- Expanded upon [#### 6W Framework]
- Expanded upon [## ByLaws]
- Added a paragraph on Governance vs Management in [## Management]

### 20230604
- Moved Supervisory 7 to Managerial 7 and moved those into [## Management]

### 20230610
- Renamed [## Conventions within Notes] to [## Note Content]
- Deleted [## Note Management]

### 20230624
- Specified Routines as being a Project in [### Routines] 
- Reiterated Projects need to factually change Run in [### Projects]

### 20230704
- Added the notion of Liabilities and Equity in [## Profile Overview]
- Added [### Liabilities and [## Liabilities]
- Added [### Equity and [## Equity]
- Updated [### Financing]

### 20230726
- Added [#### Other Roles] in [### Roles & Responsibilities]

### 20230726
- Added [# INDEX] to facilitate the managers job in establishing which topic maps where in the Expanded Profile Tree.
 
### 20230924
- Renamed the note to MGT: 99.Legend and updated references in all other notes.

### 20230930
- Updated [# PROFILE]: added [### Operations] highlighting the 5 deliverables there and tie those in to the Management Cycle in [### Management].
- Updated [## Management] keeping only two deliverables: Management Cycle, Management Improvement.

### 20231025
- Added the notion of Supervision Scope in [### Controlling] and [### Supervision]
- Added the notion of Supervision Framework in [### Controlling and [### Supervision]
- Added Notion of Management vs Governance in [## Management]
- Updated Bylaws and added more relevant Business Functions  

### 20231029
- Updated [### SWOT] to better reflect that it is a key process within Planning using Intel and Operational Plan as input, and yielding data for Goals/Objectives as well as Context

### 20231104
- Several updates in [## Equity] -explaining Capital-, [### Roles & Responsibilities] -clarifying that a Role implies the type of Responsibilities can be attributed to the Staff holding the Role

### 20231212
- Added details to [### Delegating Definition]

### 20231216
- Updated [## Management] to integrate the 4 Management Functions as key deliverables. 
- Updated [## Controlling] to add a step 1 to define the purpose of the control in the existing steps.
- Added a fourth deliverable to [## Controlling]: Monitoring. 

### 20231226
- Updated [## Operations] with a more detailed description of Risk

### 20240106
- Added [#### Sub-Goals] with details originally found in [MGT: 80.Tools].
- Reviewed all section up to Business Functions and simplified them.

### 20240107
- Added reference to the public domain github page

### 20240108
- Corrected some spelling mistakes after a check in Word
- Added Sub-Goal = Oversight Reporting for ovs
- Updated [### Management] to delegate involvement in deliverables and Management Level

### Planned

