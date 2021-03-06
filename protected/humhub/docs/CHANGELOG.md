HumHub Change Log
=================

1.2.0-beta.2 under development
------------------------------
- Fix: TimeAgo locale not loaded in production mode, added AppDynamicAsset (luke-)
- Enh: Translation message rebuild and auto translated duplicates (luke-)
- Enh: Combined all directory translations into base message category (luke-)
- Enh: Added logging table cleanup job (luke-)
- Enh: Added new version check as ActiveJob (luke-)
- Enh: Moved user configuration params 'minUsernameLength' + 'adminCanChangeProfileImages' to user module class (luke-)
- Enh: Added .editorconfig code style configuration file (luke-)

1.2.0-beta.1 (February 08, 2017)
--------------------------------
- Enh: Moved HumHub browser icons to HumHub theme (luke-)
- Enh: Moved support css/js for older IE version into own AssetBundles (luke-)
- Enh: Moved CSRF Tag output to View renderHeader (luke-)
- Enh: Moved LayoutAddons widget from main layout to View endBody() method (luke-)
- Enh: Added PJax page loading (luke-)
- Enh: Refactored File module (luke-)
- Enh: Added yii2-imagine Extension (luke-)
- Enh: Use of blueimp image gallery (buddha)
- Enh: JS module system with build in logging/text/config features (buddha)
- Enh: JS core api under humhub namespace (buddha)
- Enh: Use of compressed assets (js,css) in production mode (buddha)
- Enh: Enhanced testability (buddha)
- Enh: Added administrative backend group permissions (buddha)
- Enh: Enhanced AccessControl filter with permission rules. (buddha)
- Enh: Splitted less files to facilitate theming. (buddha)
- Enh: Added user status bar for user feedback (buddha)
- Enh: Better UserFeedack (buttons/messages) / Replacement of old DataSaved widget (buddha)
- Enh: Overwrite default permission settings (buddha)
- Enh: SpaceChooser rewrite with following spaces and remote search (buddha)
- Enh: Modal widget rewrite.
- Enh: Enhanced Archived Space handling (buddha)
- Enh: Upload widget rewrite. (buddha)
- Enh: Picker widgets rewrite (UserPicker/SpacePicker/MultiselectDropdown). (buddha)
- Enh: Richtext widget rewrite. (buddha)
- Enh: Removed almost all inline JS blocks. (buddha)
- Enh: StreamAction now uses flexible StreamQuery Model. (buddha)
- Enh: Post markdown support. (buddha)
- Enh: Added 'live' module for push/pull messages to the frontend (luke-)
- Enh: Added asynchronous job queues (luke-)
- Enh: Changed minimum PHP version to 5.6
- Enh: Added possibility of global content (content w/o contentcontainer) (luke)
- Enh: Added new profile field type: checkbox (luke-)
- Enh: Refactored mail summaries activity module (luke-)
- Enh: Moved all static files (js, fonts, css) into own static folder @web-static (luke-)
