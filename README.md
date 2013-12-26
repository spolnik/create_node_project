create node project
=================================

Create common Node.js project structure.

Structure:
--lib/
--public/
----javascripts/
----css/
------styles.css
----index.html
--server.js

To run:
>> node create_node_project.js <dir> (dir is optional argument)

To clean existing structure (having in mind, no additional files are put into the directories)
>> node create_node_project.js -clean
