---
title: "Project Menu"
category: "App Modeling"
description: "Describes the Project Menu in Studio Pro."
menu_order: 18
tags: ["Studio Pro", "project menu", "top bar"]
---

## 1 Introduction

In the **Project** menu you can view and/or manipulate settings that are connected to the version control or deployment. For example, you can view the history of the current development line or create a deployment package.

{{% image_container width="300" %}}![Project Menu](attachments/project-menu/project-menu.png)
{{% /image_container %}}

## 2 Update

The **Update** option updates the local app to the latest revision that was committed to the version control server.

## 3 Commit

The **Commit** option commits all local changes made to the app since the previous commit to the version control server. For more information, see [Commit](commit-dialog).

## 4 Show Changes on Disk

**Show Changes on Disk** opens a dialog that shows which files on disk have been changed since the last commit.  

## 5 More Versioning

Under **Project** > **More versioning**, you can find settings that are related to the version control, for example, you can manage branch lines. 

![More Versioning](attachments/project-menu/more-versioning.png)

### 5.1 History

The **History** option shows the history of committed revisions of the app. For more information on what is displayed in **History**, see [History](history-dialog).

### 5.2 Download from Version Control Server

The **Download from Version Control Server** option downloads an app from the Team Server or another SVN server. This creates a local working copy of the app for development. For more information on what settings are displayed in the **Download from Version Control Server** dialog window, see [Download from Version Control Server](download-from-version-control-dialog).

### 5.3 Upload to Version Control Server

The **Upload to Version Control Server** option uploads a local app to a new or existing Team Server repository, or to another SVN server. This is only possible if the app is not yet version controlled. For more information on what settings are displayed in the **Upload to Version Control Server** dialog window, see [Upload to Version Control Server](upload-to-version-control-dialog).

### 5.4 Manage Branch Lines

The **Manage Branch Lines** option manages branch lines on the version control server that can be used to develop functionality separately from the main line. For more information on the Branch Line Manager and creating a new branch line, see [Branch Line Manager](branch-line-manager-dialog) and [Create Branch Line](create-branch-line-dialog). 

### 5.5 Merge Changes Here

The **Merge Changes Here** option merges changes that were committed in another development line to the development line that is currently opened in Studio Pro.

### 5.6 Reverse Merge Changes

The **Reverse Merge Changes** option allows locally rolling back changes that were committed to the version control repository. These local changes can then be committed as a new revision.

###5.7 Add Snapshot of Data

The **Add Snapshot of Data** option creates a snapshot of the built-in database and adds that to the version control repository. This is especially useful for adding test data to your app or for demo purposes.

## 6 Tools

Under **Project** > **Tools**, you can find settings on updating widgets, button icons, and layouts, checking widgets, and converting your classes to the **Design** properties.  

![Tools](attachments/project-menu/tools.png)

### 6.1 Batch Update Button Icons

This option opens the **Batch Update Button Icons** dialog box so that you can configure the batch update of many button icons at once.

###6.2 Batch Update Layouts

This option opens the **Batch Update Layouts** dialog box so that you can configure the batch update of the layouts of many pages at once.

###6.3 Batch Convert Split Panes

This option opens the **Batch Convert Split Panes** dialog box so that you can configure the batch update.

###6.4 Update Widgets

The **Update Widgets** option presents the current versions of the widgets you are using in your app project, what the latest versions of the widgets are, and an update option.

### 6.5 Check Widgets

The **Check Widgets** option checks that the widgets you have implemented in the app project have been built correctly.

## 7 Synchronize Project Directory

The **Synchronize Project Directory** option creates folders inside the project directory (resources, widgets, theme, etc.), if necessary. It also reads the widget packages that are currently inside the widgets folders. For example, if you add widgets to the widgets folder, you needs to synchronize the project directory for them to appear in the **Toolbox**.

Shortcut key: <kbd>F4</kbd>

## 8 Show Project Directory in Explorer

The **Show Project Directory in Explorer** option shows the directory that contains the project file (*.mpr*) and other assets such as resources and Java actions in Windows Explorer

## 9 Deploy for Eclipse

The **Deploy for Eclipse** option deploys the project to the deployment directory. The Java stubs are generated so that you can start editing them in Eclipse. This action does not compile the Java actions. Use this if you are writing Java actions and you want to compile and debug them through Eclipse.

Shortcut key: <kbd>F6</kbd>

##10 Create Deployment Package

The **Create Deployment Package** option creates a Mendix Deployment Archive package (*.mda*) that contains all necessary files to run the project. This can be used if you want to deploy your project on a Windows server or on a custom Mendix Cloud.

Shortcut key:  <kbd>F7</kbd>

For more information on settings displayed on the Create Deployment Package dialog window, see [Create Deployment Package](create-deployment-package-dialog).

##11 Clean Deployment Directory

The **Clean Deployment Directory** option cleans the deployment directory.

## 12 Deploy to Licensed Cloud Node

The **Deploy to Licensed Cloud Node** option deploys the latest committed revision of a Team Server project to the associated Mendix Cloud node.

Shortcut key:  <kbd>Ctrl</kbd> + <kbd>F5</kbd>

## 13 Read More

* [Studio Pro Overview](studio-pro-overview)
* [View Menu](view-menu)