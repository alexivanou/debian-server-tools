### Site configs diff

```bash
colordiff Skeleton-site.conf Skeleton-site-ssl.conf
```

### Apache variables

```php
<pre><?php var_export($_SERVER);

array (
  'WP_ENV' => 'development',
  'PHP_PEAR_SYSCONF_DIR' => '/home/web/public_html/pear',

  'USER' => 'web',
  'HOME' => '/home/web/public_html',
  'PATH' => '/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin',

  'FCGI_ROLE' => 'RESPONDER',
  'SCRIPT_URL' => '/i.php',
  'SCRIPT_URI' => 'https://host.tld/i.php',
  'HTTP2' => 'on',
  'H2PUSH' => 'on',
  'H2_PUSH' => 'on',
  'H2_PUSHED' => '',
  'H2_PUSHED_ON' => '',
  'H2_STREAM_ID' => '13',
  'H2_STREAM_TAG' => '72-13',
  'HTTPS' => 'on',
  'SSL_TLS_SNI' => '/host.tld',
  'HTTP_USER_AGENT' => 'Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:46.0) Gecko/20100101 Firefox/46.0.1 Waterfox/46.0.1',
  'HTTP_ACCEPT' => 'text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8',
  'HTTP_ACCEPT_LANGUAGE' => 'en-US,en;q=0.5',
  'HTTP_ACCEPT_ENCODING' => 'gzip, deflate, br',
  'HTTP_DNT' => '1',
  'HTTP_COOKIE' => 'Horde=jjjjjjjjjjjjjjjj',
  'HTTP_HOST' => '/host.tld',
  'SERVER_SIGNATURE' => 'Apache Server at /host.tld Port 443',
  'SERVER_SOFTWARE' => 'Apache',
  'SERVER_NAME' => '/host.tld',
  'SERVER_ADDR' => '11.22.33.44',
  'SERVER_PORT' => '443',
  'REMOTE_ADDR' => '88.11.99.44',
  'DOCUMENT_ROOT' => '/home/web/public_html/server',
  'REQUEST_SCHEME' => 'https',
  'CONTEXT_PREFIX' => '',
  'CONTEXT_DOCUMENT_ROOT' => '/home/web/public_html/server',
  'SERVER_ADMIN' => '[no address given]',
  'SCRIPT_FILENAME' => '/home/web/public_html/server/i.php',
  'REMOTE_PORT' => '40242',
  'GATEWAY_INTERFACE' => 'CGI/1.1',
  'SERVER_PROTOCOL' => 'HTTP/2',
  'REQUEST_METHOD' => 'GET',
  'QUERY_STRING' => '',
  'REQUEST_URI' => '/i.php',
  'SCRIPT_NAME' => '/i.php',
  'PHP_SELF' => '/i.php',
  'REQUEST_TIME_FLOAT' => 1468252641.8478279,
  'REQUEST_TIME' => 1468252641,
)
```