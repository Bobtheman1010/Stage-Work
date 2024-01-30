Getting Started

Put Top Level folder here "C:\XY Stage". I am dynamically loading classes from disk so the file structure should remain the same. 

Contains two projects that function as an XY stage

1st being "C:\Stage-Work\JKI Project\JKI UI Project.lvproj"

This contains a project with the JKI state machine as the UI which also contains a synconous version of Stage API.

2nd being "C:\Stage-Work\Process Actor Project\Process Actor.lvproj" 

This contains a project with the "Process Actor" method of completing the assignment. This is a slimmed down version of the architetuer i have used on some of my latest projects. It follows the Model-View-Controller Architecture. So UI that communicates with a decoupeld proccess that does the required work. I used the "Actor Framwork" as the process in this case but DOES NOT follow stand Actor Framework princiles. I am essentially highjacking the message scripting and Command Pattern from the actor framework. 