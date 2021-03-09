### INFORMATION ###

Username Change Approval, Limit and History (1.4) for MyBB 1.8
Created by: Starpaul20
Copyright: ©2012
License: GPL

Allows you to moderate username changes (set as a usergroup permission), limit username changes in a specific time period (also set as a usergroup permission), and log all username changes.

The username history bit appears under Status near the top of a profile (it will only show if the user has any username history to show).

The setting for this plugin are located under the 'User Registration and Profile Options' setting group. The usergroup permission are located under the 'Account Management' section of the 'Users and Permissions' tab when editing a usergroup. This plugin offers full language support.

The 'oldrelease' branch contains the 1.6 version of the plugin.


### INSTALLATION ###

1. Upload all files above, keeping the file structure intact.
2. Go to Configuration > Plugins
3. Click "Install & Activate"
4. Enjoy!


### UPDATING ###

If you're updating from any previous version, you must first deactivate the plugin (do not uninstall), upload all new files and reactivate.

### Changelogs ###
1.4 (January 19th, 2019)
- Optimized PNG image
- Sanitized usernames
- Updated language string
- Updated numeric settings
- Removed PHP closing tags
- Use THIS_SCRIPT for template caching
- Handle display of deleted users in log
- Bug: Fixed PHP 7.2 does not cast unquoted string literals to strings (Issue #7)
- Updated setting display order

1.3.1 (January 1st, 2016)
- Added missing upgrade support

1.3 (November 30th, 2015)
- Added Mod CP approval page (Issue #5)
- Added ability to delete username changes (Issue #6)

1.2 (April 18th, 2015)
- Added PostgreSQL and SQLite support
- Using generate_numeric_field function
- Changed (int)$mybb->input to $mybb->get_input
- Moved hardcoded HTML to template
- Updated cache delete function
- Update check queries on change name page
- Use simple_select for simple query
- General file cleanup

1.1 (December 12th, 2014)
- Added ability to prune username change history (Issue #2)
- Added Admin CP notice of pending username changes awaiting approval (Issue #3)
- Cached and updated front end notice template (Issue #3)
- Converted javascript
- Updated old cache function
- Bug: Forced redirect page after changing username if change needs approval (Issue #1)

1.0 (September 4th, 2014)
- Updated plugin to work with MyBB 1.8

### Version number reset for MyBB 1.8 ###

1.3 (January 27th, 2014)
- Updated username change limit
- Added minimum wait between changes setting
- Moved more hardcoded HTML to template
- Updated grammar on number of changes left
- Added full log of username changes in Admin CP

1.2 (October 30th, 2013)
- Added front end notice to Administrator of pending username changes awaiting approval
- Added cache containing the number of changes awaiting approval
- Moved hardcoded HTML string to template
- Bug: fixed XHTML errors

1.1 (September 11th, 2012)
- Added number of changes left on User CP Name Change page
- Updated who's online function
- Bug: Fixed bug with Admin Log function

1.0.1 (March 12th, 2012)
- Bug: Fixed minor bug in profile display
- Updated Admin CP logging when moderating username changes

1.0 (January 29th, 2012)
- Initial release
