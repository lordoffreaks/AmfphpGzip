AmfphpGzip
==========

[![Join the chat at https://gitter.im/lordoffreaks/AmfphpGzip](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/lordoffreaks/AmfphpGzip?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

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
