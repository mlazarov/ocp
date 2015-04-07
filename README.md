# OCP - Opcache Control Panel



### Changelog

0.1.6  2013-04-12  moved meta to footer so graphs can be higher and reduce clutter
0.1.5  2013-04-12  added graphs to visualize cache state, please report any browser/style bugs
0.1.4  2013-04-09  added "recheck" to update files when using large revalidate_freq (or validate_timestamps=Off)
0.1.3  2013-03-30  show host and php version, can bookmark with hashtag ie. #statistics - needs new layout asap
0.1.2  2013-03-25  show optimization levels, number formatting, support for start_time in 7.0.2
0.1.1  2013-03-18  today Zend completely renamed Optimizer+ to OPcache, adjusted OCP to keep working
0.1.0  2013-03-17  added group/sort indicators, replaced "accelerator_" functions with "opcache_"
0.0.6  2013-03-16  transition support as Zend renames product and functions for PHP 5.5 (stasilok)
0.0.5  2013-03-10  added refresh button (GK)
0.0.4  2013-02-18  added file grouping and sorting (click on headers) - code needs cleanup but gets the job done
0.0.2  2013-02-14  first public release

### Known problems/Limitations:
Unlike APC, the Zend OPcache API
 - cannot determine when a file was put into the cache
 - cannot change settings on the fly
 - cannot protect opcache functions by restricting execution to only specific scripts/paths

### todo:
Extract variables for prefered ordering and better layout instead of just dumping into tables
File list filter



#### Based on OCP - Opcache Control Panel from _ck_ (with contributions by GK, stasilok)
