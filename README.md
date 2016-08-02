# wp-default-search-form
Code for default WordPress searchform.php. Download PHP file or copy the following code:

```
<form method="get" id="searchform" action="<?php bloginfo('url'); ?>/">
	<label class="hidden" for="s"><?php _e('Search:'); ?></label>
	<input type="text" value="<?php the_search_query(); ?>" name="s" id="s" />
	<input type="submit" id="searchsubmit" value="GO" />
</form>
```
