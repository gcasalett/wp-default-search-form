# Default Search form for WordPress

Use this code to replace the default search form. Download the php file or use this snippet:

```
<form method="get" id="searchform" action="<?php bloginfo('url'); ?>/">
	<label class="hidden" for="s"><?php _e('Search:'); ?></label>
	<input type="text" value="<?php the_search_query(); ?>" name="s" id="s" />
	<input type="submit" id="searchsubmit" value="GO" />
</form>
```
