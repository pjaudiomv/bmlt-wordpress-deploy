# BMLT WordPress Deploy

You will need to add the following environment variables to your travis yml

`PLUGIN` being the wordpress repo slug

`MAINFILE` being the name of the main plugin file

For ex.

PLUGIN="bmlt-wordpress-satellite-plugin"

MAINFILE="bmlt-wordpress-satellite-plugin.php"

## Deployment

This is done automatically upon tagging a release. If you wish to tag a release for testing or a beta release make sure the tag name contains the word beta in it as the deployment to wordpress will be cancelled. For ex. `3.9.6-beta`

If you wanted to test deployment without the final svn commit add a hyphen `-` in your tag without the word beta.
