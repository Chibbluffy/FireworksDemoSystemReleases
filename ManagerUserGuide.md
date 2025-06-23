# Product Manager User Guide

## Table of Contents
- [Getting Started](#getting-started)
- [Adding Videos](#adding-videos)
- [Managing Products](#managing-products)
    - [Searching Products](#searching-products)
    - [Tagging Products](#tagging-products)
- [Managing Playlists](#managing-playlists)
    - [Creating Playlist](#creating-playlist)
    - [Adding Playlist Items](#add-to-playlist)
    - [Reordering Playlist Items](#reorder-playlist)
    - [Deleting Playlist](#deleting-playlists)
    - [Deleting Playlist Items](#deleting-playlist-items)


### Getting Started
1. Open the `Manager.exe` application
    - The first time this application is run, it will generate a `Videos` folder and a `config.json` file
    ![First time the application is opened](ManagerImages/FirstOpen.png)
    ![files generated](ManagerImages/FilesGenerated.png)
2. Exit the `Manager.exe` program

### Adding Videos
1. After the `Videos` folder is created, you can move or copy all videos you want into it
![Adding Videos to folder](ManagerImages/VideosAdded.png)
2. Ideally, you should update the Videos folder videos before opening the Manager.exe application  
But if you added or deleted videos while the manager was open, there is a "Refresh Videos" button  
![Refresh Videos](ManagerImages/RefreshVideos.png)  
It will put the program into `edit products` mode and remove the assigned videos that were deleted  
![None Video](ManagerImages/NoneVideo.png)  

### Managing Products
1. After your videos are added into the `Videos` folder, you can start up the `Manager.exe` application again
2. Click `edit` in the products section
![Edit](ManagerImages/EditButton.png)

3. Edit data
    - Add new rows as needed
    ![Add New Product](ManagerImages/AddProductButton.png)
    - Edit Row(s)
    ![Edit Product Data](ManagerImages/EditProductData1.png)

4. Click `Done` when finished
![Done Button](ManagerImages/DoneButton.png)
    - Incomplete Product row
        - If you did not complete any product rows, it will notify you
        ![Product Editing failed](ManagerImages/ProductEditingValidation.png)
        - Problematic cells are also highlighted in red
        ![Product Editing Errors highlighted](ManagerImages/ProductEditingErrors.png)
    - Products are all valid
        - It will prompt you if you are sure you want to save if you have videos that have not been assigned to a product
        ![Unassigned Videos](ManagerImages/UnassignedVideos.png)
        - Press Continue to save
        ![Configuration Saved](ManagerImages/ConfigurationSaved.png)

5. If you close out of the program with unsaved changes, it asks for confirmation
![Unsaved Change exit](ManagerImages/UnsavedChangesExit.png)

#### Searching Products
1. Search in the search box to find only rows you want. It searches all data fields
![Search Box](ManagerImages/SearchBox.png)
![Search F](ManagerImages/SearchF.png)
Fan Out 46 got filtered out
![Search Fi](ManagerImages/SearchFi.png)
- This works while editing products too  
No filter
![No Filter](ManagerImages/SearchEdit.png)
![Search Edit 3](ManagerImages/SearchEdit3.png)


#### Tagging Products
1. Create a tag
![Create a tag](ManagerImages/CreateTag.png)
![Tag Created](ManagerImages/TagCreated.png)
2. Update the color if desired
    - Click on the tag to edit the color  
    ![Tag](ManagerImages/Tag.png)
    ![Tag Color](ManagerImages/TagColor.png)

3. Apply tag to product
    - Edit Product Button
    ![Edit Product button](ManagerImages/EditProductButton.png)
    - Select the tag at the bottom
        - Selected tag will have a gray outline around it
    ![Select Tag](ManagerImages/SelectTag.png)
    - After Tag is selected, click `+ Add Tag` button
    ![Add Tag](ManagerImages/AddTag.png)
    ![Tag Addded](ManagerImages/TagAdded.png)
4. Click `Done`
![Tag Added](ManagerImages/TagAdded2.png)

Example:
![Example Full Tags](ManagerImages/UsingTagsFull.png)

### Managing Playlists
IMPORTANT!! Make sure you always have a Playlist marked "Active"  
If you do not, your system will not be able to play a playlist  

#### Creating Playlist
1. Create Playlist
![Create Playlist](ManagerImages/CreatePlaylist.png)
![Created Playlist](ManagerImages/CreatedPlaylist.png)

#### Add to Playlist
1. Select Playlist
![Empty Playlist](ManagerImages/EmptyPlaylist.png)
2. Select Products with checkboxes
    ![Select Products](ManagerImages/SelectProducts.png)
    - The last checkbox you clicked will update the Video Preview, in case you need a reminder of what the video is
    ![Video Preview](ManagerImages/VideoPreview.png)
    - Tip: You can use the search feature and then select all
    ![Search and Select All](SearchAndSelect1.png)
    ![Search and Select All](SearchAndSelect2.png)
3. Click `Add to Playlist`
    ![Add To Playlist Button](ManagerImages/AddToPlaylist.png)
    ![Added to Playlist](ManagerImages/AddedToPlaylist.png)

#### Reorder Playlist
- 2 ways to change order of items
    1. Click the UP/DOWN arrow buttons
    ![Reorder Playlist](ManagerImages/ReorderPlaylist1.png)
    2. Click and drag the item
    ![Reorder Playlist](ManagerImages/ReorderPlaylist2.png)

#### Deleting Playlists
1. Click the delete button
![Delete Playlist Button](ManagerImages/DeletePlaylistButton.png)
![Confirm Delete Playlist](ManagerImages/ConfirmDeletePlaylist.png)
![Deleted Playlist](ManagerImages/DeletedPlaylist.png)
2. Make sure you have a Playlist marked Active 

#### Deleting Playlist Items
1. Click the delete button
![Delete Playlist Item Button](ManagerImages/DeletePlaylistItemButton.png)
![Deleted Playlist Item](ManagerImages/DeletedPlaylistItem.png)