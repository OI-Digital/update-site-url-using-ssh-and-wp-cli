# update-site-url-using-ssh-and-wp-cli

This is the most reliable method for changing a websites' URL:

https://developer.wordpress.org/cli/commands/search-replace/

At the minimum:

    wp search-replace 'http://example.test' 'http://example.com'
