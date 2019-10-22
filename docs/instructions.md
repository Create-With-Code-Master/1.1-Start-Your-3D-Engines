---
layout: tabbed-assignment
---

# Instructions

{% include time-estimate.html %}

This assignment starts in the middle of the Start Your Engines lesson &mdash; follow the instructions below till get to the end. You will pick up the lesson after third video on step 4 (Right-click + drag to look around at the start of the road).

1. Launch **GitHub Desktop** and confirm that you are on the **step-1** branch of the **Prototype-1** repository. Also confirm that the branch has been published on GitHub. You can tell if a branch has been published by:
   - Looking for a "friendly suggestion" to **Create Pull Request** in GitHub Desktop (there will be a message there saying "The current branch (step-1) is already published to GitHub." if the branch has been published).
   - Looking under the Branches drop down on GitHub.
1. Launch **Unity Hub,** there should be a shortcut on your desktop, or your can search from the start menu.
   - Click on Projects in the left sidebar. Then click on the Add button.
   - Navigate to the folder **Prototype-1** folder in your GitHub folder and select it.
   
     After selecting the Prototype-1 folder you may see a message that the required version of Unity is not installed. If that happens, click on the Version drop down and select the next highest installed version with the same major (e.g., 2018) and minor (e.g., 4) release number. A change of the major number indicates _breaking_ API changes &mdash; your code may not be compatible with the newer version of Unity. A change in the minor number indicates a _backwards compatible_ feature has been added &mdash; your code should still run correctly. Changes to the third number, the _patch_ level, indicate _backwards compatible_ bug fixes &mdash; changes that make the code work the way it was supposed to.
   - Click on the project to launch Unity. The first launch of any project will be quite slow.
1. While Unity is loading, open the [lesson][] in your browser and move the browser to window to your secondary monitor.
1. Since we are downloading our starter assets from GitHub you will not need to _do_ anything for the first two sections and most of the third. **But,** do watch the videos. The videos introduce vocabulary and important Unity concepts and techniques. As you watch the videos **make notes**.
1. Once Unity has launched check that the Prototype-1 _scene_ has loaded. You should see a road surrounded by mountains. If you don't:
   - Find the Scenes folder in the Project window (or panel or pane).
   - There you should find the **Prototype-1** scene.
   - Open it by double-clicking on it.
1. Find the section **3. Import assets and open Prototype 1**
1. Follow the instructions in the [lesson][], starting from **step 4 (Right-click + drag to look around at the start of the road)** to:
   - Add a vehicle (and make a commit)
   - Add an obstacle (and make a commit)
   - Position the camera (and make a commit)
   - Customize the Unity UI (user interface)
   
   In general, whenever you have completed a "hunk" of work &mdash; such as adding a vehicle &mdash; make a commit. Be sure to describe the commit. The description can be brief.
1. In **GitHub Desktop**, commit any outstanding changes and push them to GitHub.
1. Go to the submission tab and submit your work.

[prototype1]: <https://github.com/Create-With-Code-Master/Unit-1-Prototype>

<!-- Don't edit links here, change them in _data/assignment.yml instead, -->

[lesson]: <{{site.data.assignment.lesson}}>
[slides]: <{{site.data.assignment.slides}}>
[template]: <{{site.data.assignment.template}}>

