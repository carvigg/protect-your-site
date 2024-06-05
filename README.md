# protect-your-site
Wordpress Plugin for disabling basic features that can be potentially dangerous


## What this plugin does

The main objective of this plugin is to make it more difficult to identify the WP version the site uses to ensure we are not giving potential hackers the ability to check quickly for vulnerabilities, stop code being sent through the forms in the site and preventing the access to sensitive features like updates or theme editing.

- Deletes default wp install readme.txt file.
- Disables theme editing from admin.
- Disables HTML in comments.
- Hides Wordpress version in generator head and feed.
- Hides Stylesheet version = WP version.
- Hides WPML generator.
- Disable scripts in forms/inputs.
- Modifies login error messages to ensure no one knows if the error is a missing password or the user.
- Deactivate plugin updates to ensure they aren't modified by a professional and break the site.

## Installation

- This plugin should be installed in the mu-plugin archive to ensure it can't be disabled through the admin.

## Compatibility
- Wordpress 6.4 +

