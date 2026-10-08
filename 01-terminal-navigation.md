Terminal Navigation:
| Command | What it does               | When you'd use it                                     |
| ------- | -------------------------- | ----------------------------------------------------- |
| `pwd`   | Shows where you are        | "Where am I in the filesystem?"                       |
| `ls`    | Shows what's here          | "What's in this directory?"                           |
| `cd`    | Moves to another directory | "I need to go somewhere else."                        |
| `mkdir` | Creates a directory        | "I need somewhere to put these files."                |
| `cp`    | Copies something           | "I need a backup/duplicate."                          |
| `mv`    | Moves/renames something    | "This file is in the wrong place / needs a new name." |
| `rm`    | Deletes something          | "I no longer need this file."                         |
------------------------------------------------------------------------------------------------

Scenario 1 — "I'm trying to find a configuration file, but I'm not sure which directory I'm currently in." - pwd
Scenario 2 — "Okay, I'm in my home directory now, but I don't know what files are actually there." - ls
Scenario 3 — "The file we're looking for should be inside logs. Go into that directory." - cd logs
-----------------------------
Where am I? → pwd           |
What's here? → ls           |
Where do I need to go? → cd |
-----------------------------
Scenario 4 — You're inside 'logs', and the customer asks you to create a folder called 'backup' 
to store copies of the logs before you change anything. - mkdir backup

Scenario 5 — Now you see a file:
server.log
Before troubleshooting it, you want to make a backup inside your new backup directory. - |cp server.log backup/    |                 
                                                                                         |cp [SOURCE] [DESTINATION]|
                                                                                         ---------------------------
                                                                                         







