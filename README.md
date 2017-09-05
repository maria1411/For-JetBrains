# Using Local History
## Table of Contents
  * [Marking Versions With Labels](#marking-versions-with-labels)
    + [Labeling a local version](#labeling-a-local-version)
  * [Viewing Recent Changes](#viewing-recent-changes)
  * [Viewing Local History for File or Folder](#viewing-local-history-for-file-or-folder)
    + [Viewing local history](#viewing-local-history)
    + [Local History Parameters](#local-history-parameters)
  * [Viewing Local History of Code Elements](#viewing-local-history-of-code-elements)
    + [Viewing Local History for Class](#viewing-local-history-for-class)
    + [Viewing Local History For Method or Field](#viewing-local-history-for-method-or-field)
    + [Viewing local history for a selected source code fragment](#viewing-local-history-for-a-selected-source-code-fragment)
  * [Discarding Changes and Restoring  Versions From Local History](#discarding-changes-and-restoring--versions-from-local-history)

This section describes how to use **Local History** -- your personal version control system. 
Via **Local History**, you can:
*	Put labels to mark and save stable versions;
*	Discard changes and roll back to the previous version;
*	View the most recent changes;
*	View changes made to:
       * A certain element or code fragment;  
       * A file or a folder.  

## Marking Versions With Labels

Before implementing any changes to a source code, you can mark a stable version with a label. You can easily roll back to this labelled version, if required.

**Note Labels** are applied to the whole project.

### Labeling a local version
To put a label on a local version:
1.	Select a file or a folder in the Project window, or open a file in the editor.
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

* Click the **Show difference** icon to view the differences and compare the versions;
* Click the **Revert selection** icon  to discard the change.
* Click **Expand All** or **Collapse All** options to view or hide the details.

## Viewing Local History for File or Folder

The **Local History** makes it possible to view changes made to a certain file or a folder. The **Local History** for a file includes all changes that affect both the selected file and the whole project; the **Local History** for a folder shows changes to the source code tree in general. 

### Viewing local history 
To view local history
1.	Select a folder/file in the Project pane, or open the folder/file in the editor.
2.	Do one of the following:
      *	From the main VCS menu, select Local History > Put Label.
      *	By right-clicking select Local History > Show History in the context menu.
      *	Press Alt+Back Quote, and choose the Show History option from the VCS Operations quick list.
3.	The Local History dialogue is displayed.

### Local History Parameters
Name | Description
------------ | -------------
The Left Pane | Contains the list of all changes within 12 hours. The time the change has been made is indicated there.
The Right Pane | Displays the contents
Viewing the contents | You can select the way the changes are displayed in the right pane in the upper panel. <li> Side-be-side viewer – divides the pane the previous and current versions and highlights the changes.</li> <li>Unified viewer – displays the current version and highlights the changes.</li>
Ignoring/not ignoring whitespaces and empty lines | In the upper pane, you can select to ignore or not ignore whitespaces and empty line. Possible options: <li> Do not ignore;</li> <li> Trim whitespaces;</li> <li> Ignore whitespaces;</li> <li>Ignore whitespaces and empty line.</li>
Highlighting certain parts of code | Enables highlighting certain parts of code. Possible options: <li> Highlight words;</li> <li> Highlight lines;</li> <li> Highlight split changes;</li> <li> Do not highlight.</li>


## Viewing Local History of Code Elements
You can also track local changes made to a class, its elements, or a selected block of a source code. 
Note This history shows only changes that affect the selected element or code fragment.

### Viewing Local History for Class
To view local history for a class
1.	Select a class file in the project tool window, or right-click class name in the editor.
2.	In the main VCS menu, or in the context menu, choose Local History > Show History for Class.

### Viewing Local History For Method or Field
To view local history of a method or a field
1.	In the editor, place the caret at the name of a method or a field.
2.	In the main VCS menu, or in the context menu, select Local History > Show History for Method (Field).
Viewing local history for a selected source code fragment
To view local history of a selected source code fragment:
1.	In the editor, select a fragment of source code.
2.	Do one of the following:
       *	From the main VCS menu, select Local History > Show History for Selection.
       *	By right-clicking select Local History > Show History for Selection in the context menu.
       *	Press Alt+Back Quote, and choose a command from the VCS Operations quick list.
3.	The dialogue with change details is displayed.

### Viewing local history for a selected source code fragment
To view local history of a selected source code fragment:
1.	In the editor, select a fragment of source code.
2.	Do one of the following:
       *	From the main VCS menu, select Local History > Show History for Selection.
       *	By right-clicking select Local History > Show History for Selection in the context menu.
       *	Press Alt+Back Quote, and choose a command from the VCS Operations quick list.
3.	The dialogue with change details is displayed.

## Discarding Changes and Restoring  Versions From Local History
If necessary, you discard changes via the Local History and restore a selected version.
To discard changes in the Local History:
1.	Open the Local History.
2.	Select the version you want to roll back to.
3.	On the toolbar, click the Revert selection icon  .
4.	The selected version is restored. 

