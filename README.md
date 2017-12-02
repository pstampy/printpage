# Print this page

This is a js line that can be added to a site create a "print this page" link (with icon) so users don't need to use the browser menus to print a page off your website.

Make sure that there is a decent print style sheet set up.

If used in drupal, it can be added to the page.tpl.php file within the region, and the image added to the /images folder within your theme.

``` 
<div class="print"><a href="javascript:window.print()" title="Print this page">Print This Page  <img src="<?php print base_path() . path_to_theme() . '/images/icon_print.png' ?>" </a></div>

``` 
