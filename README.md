AmfphpGzip
==========

Plugin for Amfphp for support gzip compression

## Configuration example

``` php
/**
 * Compression level
 * -1 => Default, usually 6
 * min: 0 // No compression
 * max: 9 // Plugin default
 */

$level = 7;
$this->pluginsConfig["AmfphpGzip"] = array( 'level' => $level);

```
