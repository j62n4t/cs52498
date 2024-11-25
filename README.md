java c
ELECTRONIC, ELECTRICAL AND   SYSTEMS ENGINEERING
MSc Coursework Software and   Systems
2024-2025
Design   and   Implementation   of   a   Pac-Man   Style   Computer
Game   (GUI)
Aims and   Objectives
You   are   required   to   design   and   implement   object-oriented   software   for   the   game   Pac-Man.
This   is a small group piece of coursework   (maximum   3   group   members) which   contributes 60% of the total mark for the Software and   Systems   module. You   are   expected to submit the following:
•          Design   Report - the   report accounts for 50% of the coursework   mark   and   is   assessed as a   group
•          Python   program - the   program accounts for 50% of the coursework mark
o   25% will   be assessed on your individual contribution to   the   code
o   25% will   be assessed as a group on the   GUI design,   integration   and   overall functionality of your application
Tasks
Using   the   object-oriented   approach,   design   and   implement   the   game   Pac-Man   as   a   Python application – details of   the game play and required functionality are below.
1.    As    a    group    design    the    application    using      UML    diagrams    to    formalize    your   design
2.      Once      your      design      has      been      completed      programming      tasks      should      be   assigned to individual members of your group to   complete
o   Each class should   include   in the code comments who the   author   is
o   Continue       to       discuss         with          your       other       group          members       to          limit   complications with the integration
3.    As    a    group    integrate    the    different    components    of   your   game    into    a    single   application   (Note: make   sure   you   allow   plenty   of   time   for   this!)
4.      Provide the prototype of your application to your testers
o   You will be assigned testers for your game from other groups
5.      Play the games you   have   been provided to test and   give   your feedback
o   Timelines for providing your game and feedback will be   provided
6.    As   a   group   consider   your   feedback   and   any   changes   that   could   be   made   to   your design and implementation to address any   issues   raised
o   Your response to the feedback should be   included   in   your   report
Keep   a   record   of   your   group   meeting   notes   these   will   be   required   for   your   report
Game Requirements
Your game will   be   a   simplified version   of the   game   pac-man   and   will   be   played   as   a   single   player game.
The   objective   of   the   game   is   for   the   player   to   collect   all   of   the   dots   within   the   time   limit without   running   into a ghost.
1.      Game   Setup
Your playing area must   consist of a   maze   such   as   the   one   shown   in   Figure   1.
Figure   1: Example Maze
Image courtesy:https://pacman.fandom.com/wiki/Pac-Man_Maze?file=Originalpacmaze.png   You are free to design your own maze   but   the   maze   must   have:
•          Internal walls that   result   in at   least 30   corners
•          Enough space for (see   Figure   2):
o   1 x   pac-man
o   3 x   ghosts
o   At   least 240 x dots (the exact   number will depend on   your   maze)
•          1   pair   of gaps   in   the   outside   wall   where   it   is   possible   to   exit   from   one   side   of   the maze and   renter   on   the   other
Each   location   in the maze should contain only   1   item   either   pac-man,   ghost or   dot
•         The   Pac-man should always start at the same   location   in the   maze
•          Ghosts should   be   positioned on the maze   in   randomly assigned   locations
o   Note ghosts are   not   required to   move
•         Any   location which does   not contain pac-man or a ghost   should   contain   a   dot
Figure 2: Example pac-man, ghost and   dots
Images courtesy:https://pacman.fandom.com/wiki/Pac-Man_(game)?file=Pac8bit.png
https://pacman.fandom.com/wiki/Pac-Man_(game)?file=Blinky8bit.png   https://pacman.fandom.com/wiki/Pac-Dot?file=Pac-Dot_Arcade.png
2.      Gameplay
The   player must   move the   pac-man   icon around the   maze to   collect as   many   dots   as   possible within a given time   limit
•         The   player should not be able to   move the   pac-man through   the walls
•         The   dots   should   be   removed   from   the   maze   once   the   pac-man   moves   onto   the same   location as   them
•         At   a   pre-defined   time   after   the   start   of   the   game   2   pieces   of   fruit   (Figure   3)   should appear   in   random   locations   in the   maze   (not   occupied   by the   Pac-man   or   the   ghosts)   and   as   with   the   dots   should   be   removed   once   the   pac-man   moves over them.
•         The game should end when one of the following occurs:
o   The   pac-man moves onto the same   location as   one   of the   ghosts
o   The decided   upon time limit   is   reached
o   The   user has collected all   dots   and fruit
The game should   keep track of how many   points the   player   has   earned:
•          Each dot should   be worth   10   points
•          Each fruit should   be worth   100   points
•         The total points should be   displayed   at the   end   of the game
Figure 2: Example fruit
Image courtesy:https://pacman.fandom.com/wiki/Pac-Man_(game)
3.      GUI
The   application   should   be   able to   create   a   GUI   containing all widgets   required to   run   the game smoothly. The application should have the   following   functionality:
1.    Allows the player to start the game   which   will start the   timer
2.      Displays the maze   with the locations of   the   dots,   ghosts   and starting position   of   the   pac-man
3.      The player should be able to use specified keys to   move   the pac-man   up,   down, left,   right
4.    A代 写Design and Implementation of a Pac-Man Style Computer Game 2024-2025Python
代做程序编程语言fter the decided amount of   time displays the   fruit on   the   maze
5.    After the one of   the end game conditions   is   reached   the   game   should conclude
6.       Displays the players score and asks the   user to   quit or   play another   game.After creating your GUI with all the above   widgets,   you   will   then   have   to   bind   these   to   the functions to get your application working.   You   will   need   to   handle   any   exceptions   that may arise   during   its   use.


AssessmentThe   design   report   and   python   code   (.py   file)   must   be   submitted   via   canvas   as   two   separate files   in   one go.   Click on the   + Add   Another   File   link   to   add   another   ‘Choose   File’   button while   submitting your assignment.   Only   one   member of   the   group   needs   to submit the files.
1.    Design   Report
At   the   start   of your   report   there   must   be   a   statement   on   the   use   of generative   AI   as   follows:
We have used   generative AI tools such as   ChatGPT (or any equivalent
alternative) in   the   preparation   of   the   submission.   (Yes/No)
You      can      find      the      University’s      guidelines      on      the      use      of      generative      AI      here:
https://intranet.birmingham.ac.uk/student/libraries/asc/student-guidance-gai.aspx
•         The   report   must   contain   the   relevant   UML   diagrams   produced   to   design   this   game
•         The   report must fully address all   relevant   issues
•         The   assignment    is   open-ended    but    it    is    important    that    all    diagrams   of   the   design process are considered to a   reasonable   level   of detail
•         The   report should   include a record of the group   meeting   notes as   an   appendix
•         The   report should   include the feedback from the testers as an appendix
•          If   generative   AI   tools   were   used   the   report   should   include   an   appendix   with   the following:
o   A   reference to the generative AI system   used
o   The   prompts   provided to the generative AI
o   The   responses obtained
o   Details of how the output was changed   by   yourself
Note   without this you risk breaching academic integrity (see below)
•         The    figures,    tables    and    pages      should      be      numbered.      Captions    should      be   beneath figures and   above tables.
•         The   report should not exceed   10 pages   (not   including appendices).
•         The   report must be submitted via canvas   as   one   single   pdf file.

This assignment   involves the development of designs on   paper.   It should   be   possible   to draw good quality design diagrams   using Word   or other word   processing   package,   adopting   the   correct   notation.   There   is   no   need   to   use   any   Object-Oriented   Design   Tools.   This    is    because    the    learning    curve    associated   with   object-oriented   design   tools   is   normally steep.   Many design consultants   use graphical   design   programs   and   not    object-oriented    design    tools    to    document    designs.    Tools    that    you    might    find   useful are Visio   (might require   licence),   Modelio, draw.io and ArgoUML.
The    report    will    be    first    assessed    on      English      language      proficiency    which    will      be   assessed as follows:
•          Pass and   above:
o   The work   is written / spoken to an acceptable standard of   English
o   Spelling, punctuation, vocabulary, sentence construction, and textual   coherence   is of an acceptable standard.
•          Fail:   (zero   marks)
o   Poor standard of written / spoken   English, making   it difficult to   understand the   points being   made.
o   Weaknesses of writing / speaking are so frequent   or serious that they   impede communication.
The mark distribution will   be   as follows:
a)       Introduction,       which          includes       the       discussion          and       interpretation       of         the   specification,    and    should       identify    any       issues    that       require    clarification.      (3   marks)
b)       Use-Case   Diagram,   Use-Case description and CRC cards. (15   marks)
c)       Detailed class diagram with all attributes,   methods, their visibilities,
arguments,   return types and relationships to define architecture.   (6   marks)
d)       Detailed   interaction diagrams, both collaboration and sequence   diagram.   (10   marks)
e)       Detailed state machine (chart) diagram   to   show   events,   actions   and   qualifiers.   (6   marks)
f)       Discussion of non-functional   and   usability   requirements.   (5   marks)
g)       Discussion of feedback from your testers and any constraints limiting you   to   implement   part(s) of your design   (5   marks)
2.    Python   Program:This    should    be    the      implementation      of    your      design      for      the      game.      The      classes,   methods    and    attributes      created      during      the      design       process    should       be       used      in   implementation.The   marks   will   divided   between   an   individual   component   based   on   the   code   you   have written and a group mark on   how well   your   game   is   integrated   and functions   The   individual mark distribution will be   as follows:
a)       The quality of programming – appropriate design of the   code,   use of classes,   methods, attributes,   reusability of code, etc. (20   marks)
b)      Well documented code.   (5   marks)
The group mark distribution will   be   as follows:
c)       Game   Functionality.   (15   marks)
d)      GUI design – note the design of the GUI   should   have   been   agreed   upon   as   a      group even   if the code is   implemented by one   individual   member of the   group.   (10   marks)



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
