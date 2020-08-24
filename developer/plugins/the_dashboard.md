## The Dashboard

At the moment we removed the dashboard from the teacher/student view because *some* of the charts
that show there are *very* slow when you have a lot of data, and we believe it would be a bad 
idea to show it to all users.Recently, however, we started doing a small change to allow the 
platform admin to see one more chart than the other admins, so there is a start for doing 
role-based changes.

If you want to unlock completely the dashboard for all users, you can unlock 
the permissions at main/inc/lib/banner.lib.php, around line 319, where you have checks on 
api_is_platform_admin(), api_is_drh() and api_is_session_admin(). Remove this line and you'll 
get it for students and teachers indifferently.