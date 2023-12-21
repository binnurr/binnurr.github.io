---
title: "Gazebo Diary - Vol. 1 (warming up to Gazebo)"
date: "2013-11-14"
categories: 
  - "sdf-editor-for-gazebo-opw-project"
---

Gazebo GUI does not fit into my laptop and annoyingly I cannot adjust it with the setSize method. Although, it is not related to SDF editor project, I have to fix it in order to interfere with the panel which contains  simulation pause/continue buttons and run time information etc. :) After playing around Qt methods and classes, I could not find a nice solution. However, I have a workaround, I use setFixedSize method instead of resize and it handles the window size properly but qsplitter does not work properly which may be handled later on. Now, I am ready to add a text editor to gazebo. I see that it can easily be added to code by using building editor code as an example. I am studying how editors are embedded in the GUI by playing with building editor.
