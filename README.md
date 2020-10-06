Redmine Comments plugin
=======================

This plugin improves private notes in Redmine issues.
You can manage private notes visibility through roles and permissions.
A typical usage for an tech organization is to allow staff users to see/edit comments, but not lambda users.

The plugin requires Redmine version 2.5.0 or higher.

Private comments have been added in Redmine 2.2.0 and this plugin was originally made for Redmine < 2.1.0.
It now uses Redmine's default feature and old plugin's comments are automatically migrated to the standard Redmine feature.
See http://www.redmine.org/issues/1554 for more informations.

Screenshot
----------

![plugin screenshot](https://raw.githubusercontent.com/jbbarth/redmine_comments/master/assets/images/screenshot.png)

Test status
------------

|Plugin branch| Redmine Version   | Test Status       |
|-------------|-------------------|-------------------|
|master       | 4.1.1             | [![Build1][1]][8] |  
|master       | 4.0.7             | [![Build2][2]][8] |
|master       | master            | [![Build1][3]][8] |  
|preprod      | 4.1.1             | [![Build1][4]][8] |  
|preprod      | 4.0.7             | [![Build2][5]][8] |
|preprod      | master            | [![Build1][6]][8] |  

[1]: https://travis-matrix-badges.herokuapp.com/repos/jbbarth/redmine_comments/branches/master/1
[2]: https://travis-matrix-badges.herokuapp.com/repos/jbbarth/redmine_comments/branches/master/2
[3]: https://travis-matrix-badges.herokuapp.com/repos/jbbarth/redmine_comments/branches/master/3
[4]: https://travis-matrix-badges.herokuapp.com/repos/jbbarth/redmine_comments/branches/master/4
[5]: https://travis-matrix-badges.herokuapp.com/repos/jbbarth/redmine_comments/branches/master/5
[6]: https://travis-matrix-badges.herokuapp.com/repos/jbbarth/redmine_comments/branches/master/6
[8]: https://travis-ci.org/jbbarth/redmine_comments
