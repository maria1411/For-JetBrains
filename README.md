# Managing Changes in Project
## Table of Contents
  * [Marking Versions With Labels](#marking-versions-with-labels)
    + [Labeling Local Version](#labeling-local-version)
  * [Viewing Recent Changes](#viewing-recent-changes)
  * [Viewing Local History for File or Folder](#viewing-local-history-for-file-or-folder)
    + [Viewing Local History](#viewing-local-history)
    + [Local History Parameters](#local-history-parameters)
  * [Viewing Local History of Code Elements](#viewing-local-history-of-code-elements)
    + [Viewing Local History for Class](#viewing-local-history-for-class)
    + [Viewing Local History for Method or Field](#viewing-local-history-for-method-or-field)
    + [Viewing Local History for Selected Source Code Fragment](#viewing-local-history-for-selected-source-code-fragment)
  * [Discarding Changes and Restoring Versions From Local History](#discarding-changes-and-restoring-versions-from-local-history)

This section describes how to manage changes in a project and how to view and operate the **Local History** -- your personal version control system. 
IntelliJ IDEA allows you to:
*	[Put labels to mark and save stable versions;](#marking-versions-with-labels)
*	[View the most recent changes;](#viewing-recent-changes)
*	View changes made to:
       * [A file or a folder;](#viewing-local-history-for-file-or-folder)
       * [A certain element or code fragment;](#viewing-local-history-of-code-elements)  
       * [A method or a field.](#viewing-local-history-for-method-or-field)
*	[Discard changes and roll back to the previous version;](#discarding-changes-and-restoring-versions-from-local-history)

## Marking Versions With Labels

Before implementing any changes to a source code, you can mark a stable version with a label. You can easily roll back to this labelled version, if required.

**Note Labels** are applied to the whole project.

### Labeling Local Version
To put a label on a local version:
1.	Select a file or a folder in the **Project** window, or open a file in the editor.
2.	Do one of the following:
       *	From the main **VCS** menu, select **Local History** > **Put Label**.
       *	By right-clicking select **Local History** > **Put Label** in the context menu.
       *	Press **Alt+Back Quote** and select **Put Label** from the **VCS Operations** quick list.
3.	The **Put Label** dialogue is displayed, fill out the label name in the corresponding field.

![1](https://user-images.githubusercontent.com/31585691/30051310-8f6ea414-9232-11e7-879f-5f42b94558d0.jpg)

## Viewing Recent Changes

IntelliJ IDEA allows you to view recent changes made to a project. You can:
*	browse through the history of changes; 
*	navigate to a particular change, 
*	compare versions, 
*	discard changes, if required. 

To viewing recent changes:
1.	From the main menu, select **View** > **Recent Changes**, or use **Shift+Alt+C** shortcut.
2.	The **Recent Changes** pop-up is displayed, select the change you want to view:

![2](https://user-images.githubusercontent.com/31585691/30051354-c8d6080a-9232-11e7-9e69-ad8b61b8e3c1.jpg) 

3.	Select the change you want to view.
4.	The dialogue with change details is displayed. You can do one of the following:

![3](https://user-images.githubusercontent.com/31585691/30051370-d7d30894-9232-11e7-84d5-c9f7eb9091e1.jpg)

* Click the **Show difference** icon ![9](https://user-images.githubusercontent.com/31585691/30063274-333731de-925f-11e7-9c4a-ef3a32b2bd81.jpg) to view the differences and compare the versions;
* Click the **Revert selection** icon ![6](https://user-images.githubusercontent.com/31585691/30063259-1c7cd002-925f-11e7-9f53-b89751a409be.jpg) to discard the change.
* Click **Expand All** or **Collapse All** options to view or hide the details.

## Viewing Local History for File or Folder

The **Local History** makes it possible to view changes made to a certain file or a folder. The **Local History** for a file includes all changes that affect both the selected file and the whole project; the **Local History** for a folder shows changes to the source code tree in general. 

### Viewing Local History  
To view **Local History**
1.	Select a folder/file in the **Project** pane, or open the folder/file in the editor.
2.	Do one of the following:
      *	From the main **VCS** menu, select **Local History** > **Show History**.
      *	By right-clicking select **Local History** > **Show History** in the context menu.
      *	Press **Alt+Back Quote**, and choose the **Show History** option from the **VCS Operations** quick list.
3.	The **Local History** dialogue is displayed.

![5](https://user-images.githubusercontent.com/31585691/30063433-bc5844f8-925f-11e7-9676-9070652fc17a.jpg)

### Local History Parameters
Name | Description
------------ | -------------
The Left Pane | Contains the list of all changes within 12 hours. The time the change has been made is indicated there.
The Right Pane | Displays the contents
Viewing the contents | You can select the way the changes are displayed in the right pane in the upper panel. <li> Side-be-side viewer – divides the pane the previous and current versions and highlights the changes.</li> <li>Unified viewer – displays the current version and highlights the changes.</li>
Ignoring/not ignoring whitespaces and empty lines | In the upper pane, you can select to ignore or not ignore whitespaces and empty line. Possible options: <li> Do not ignore;</li> <li> Trim whitespaces;</li> <li> Ignore whitespaces;</li> <li>Ignore whitespaces and empty line.</li>
Highlighting certain parts of code | Enables highlighting certain parts of code. Possible options: <li> Highlight words;</li> <li> Highlight lines;</li> <li> Highlight split changes;</li> <li> Do not highlight.</li>
The **Revert** option ![6](https://user-images.githubusercontent.com/31585691/30063259-1c7cd002-925f-11e7-9f53-b89751a409be.jpg) | Click this option to revert changes 
The **Create Patch** option ![7](https://user-images.githubusercontent.com/31585691/30063622-6361acc6-9260-11e7-90ee-5815ea108e2e.jpg) | Click this icon to create a patch
**Next difference** and **Previous difference** options ![8](https://user-images.githubusercontent.com/31585691/30063666-7cee55fe-9260-11e7-91b2-bebc1344a38a.jpg) | Helps you to navigate through changes 
The **Jump to Source** option ![10](https://user-images.githubusercontent.com/31585691/30063807-e34905ba-9260-11e7-8de1-5833dfb36add.jpg) | Click this icon to quickly navigate to the source
The **Collapse unchanged fragments** option ![11](https://user-images.githubusercontent.com/31585691/30063863-12c4574a-9261-11e7-948d-9724643f1f8c.jpg) | Click it to display only the changed fragments. This option helps you to review changes quickly.
The S**ynchronize scrolling** option ![12](https://user-images.githubusercontent.com/31585691/30063873-1d62e4b4-9261-11e7-9bf5-5d94155db920.jpg) | Click this icon to synchronize scrolling 
**Settings** ![13](https://user-images.githubusercontent.com/31585691/30063883-285c2eb6-9261-11e7-973c-5f18c4a6918c.jpg) | Opens the list of available settings
 **Help** ![14](https://user-images.githubusercontent.com/31585691/30063891-2c47e1d2-9261-11e7-99d5-6e9bcccd05dc.jpg) | Opens the online Help in the corresponding section 
Browsers icons ![15](https://user-images.githubusercontent.com/31585691/30063964-6af6da32-9261-11e7-8517-c8289691344f.jpg) | Browser icons appear in the right pane, in the code body. Click one of them to view the source code in the corresponding browser. **Note** Only browsers available on your PC are displayed.

## Viewing Local History of Code Elements
You can also track local changes made to a class, its elements, or a selected block of a source code. 
**Note** This history shows only changes that affect the selected element or code fragment.

### Viewing Local History for Class
To view **Local History** for a class
1.	Select a class file in the Project window, or right-click a class name in the editor.
2.	In the main **VCS** menu, or in the context menu, choose **Local History** > **Show History for Class**.

### Viewing Local History for Method or Field
To view **Local History** of a method or a field:
1.	In the editor, place the caret at the name of a method or a field.
2.	In the main **VCS** menu, or in the context menu, select **Local History** > **Show History for Method (Field)**.

### Viewing Local History for Selected Source Code Fragment
To view **Local History** of a selected source code fragment:
1.	In the editor, select a fragment of source code.
2.	Do one of the following:
       *	From the main **VC**S menu, select **Local Histor**y > **Show History for Selection**.
       *	By right-clicking select **Local History** > **Show History for Selection** in the context menu.
       *	Press **Alt+Back Quote**, and choose a command from the **VCS Operations** quick list.
3.	The dialogue with change details is displayed.

## Discarding Changes and Restoring Versions From Local History
If necessary, you discard changes via the **Local History** and restore a selected version.
To discard changes in the **Local History**:
1.	[Open the Local History.](#viewing-local-history)
2.	Select the version you want to roll back to.
3.	On the toolbar, click the Revert selection icon  .
4.	The selected version is restored. 

