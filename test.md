object(Hyperf\HttpMessage\Server\Request)#85 (16) {
["server":protected]=>
array(0) {
}
["uri":protected]=>
object(Hyperf\HttpMessage\Uri\Uri)#89 (7) {
["scheme":"Hyperf\HttpMessage\Uri\Uri":private]=>
string(4) "http"
["userInfo":"Hyperf\HttpMessage\Uri\Uri":private]=>
string(0) ""
["host":"Hyperf\HttpMessage\Uri\Uri":private]=>
string(9) "127.0.0.1"
["port":"Hyperf\HttpMessage\Uri\Uri":private]=>
int(9601)
["path":"Hyperf\HttpMessage\Uri\Uri":private]=>
string(12) "/hello/index"
["query":"Hyperf\HttpMessage\Uri\Uri":private]=>
string(0) ""
["fragment":"Hyperf\HttpMessage\Uri\Uri":private]=>
string(0) ""
}
["method":protected]=>
string(3) "GET"
["requestTarget":protected]=>
NULL
["headerNames":protected]=>
array(3) {
["host"]=>
string(4) "host"
["user-agent"]=>
string(10) "user-agent"
["accept"]=>
string(6) "accept"
}
["headers":protected]=>
array(3) {
["host"]=>
array(1) {
[0]=>
string(14) "127.0.0.1:9601"
}
["user-agent"]=>
array(1) {
[0]=>
string(11) "curl/7.68.0"
}
["accept"]=>
array(1) {
[0]=>
string(3) "*/*"
}
}
["protocol":protected]=>
string(3) "1.1"
["stream":protected]=>
object(Hyperf\HttpMessage\Stream\SwooleStream)#87 (3) {
["contents":protected]=>
string(0) ""
["size":protected]=>
int(0)
["writable":protected]=>
bool(true)
}
["swooleRequest":protected]=>
object(Swoole\Http\Request)#94 (8) {
["fd"]=>
int(1)
["header"]=>
array(3) {
["host"]=>
string(14) "127.0.0.1:9601"
["user-agent"]=>
string(11) "curl/7.68.0"
["accept"]=>
string(3) "*/*"
}
["server"]=>
array(10) {
["request_method"]=>
string(3) "GET"
["request_uri"]=>
string(12) "/hello/index"
["path_info"]=>
string(12) "/hello/index"
["request_time"]=>
int(1650141006)
["request_time_float"]=>
float(1650141006.896714)
["server_protocol"]=>
string(8) "HTTP/1.1"
["server_port"]=>
int(9601)
["remote_port"]=>
int(46040)
["remote_addr"]=>
string(9) "127.0.0.1"
["master_time"]=>
int(1650141006)
}
["cookie"]=>
NULL
["get"]=>
NULL
["files"]=>
NULL
["post"]=>
NULL
["tmpfiles"]=>
NULL
}
["attributes":"Hyperf\HttpMessage\Server\Request":private]=>
array(0) {
}
["cookieParams":"Hyperf\HttpMessage\Server\Request":private]=>
array(0) {
}
["parsedBody":"Hyperf\HttpMessage\Server\Request":private]=>
array(0) {
}
["queryParams":"Hyperf\HttpMessage\Server\Request":private]=>
array(0) {
}
["serverParams":"Hyperf\HttpMessage\Server\Request":private]=>
array(10) {
["request_method"]=>
string(3) "GET"
["request_uri"]=>
string(12) "/hello/index"
["path_info"]=>
string(12) "/hello/index"
["request_time"]=>
int(1650141006)
["request_time_float"]=>
float(1650141006.896714)
["server_protocol"]=>
string(8) "HTTP/1.1"
["server_port"]=>
int(9601)
["remote_port"]=>
int(46040)
["remote_addr"]=>
string(9) "127.0.0.1"
["master_time"]=>
int(1650141006)
}
["uploadedFiles":"Hyperf\HttpMessage\Server\Request":private]=>
array(0) {
}
["bodyParams":"Hyperf\HttpMessage\Server\Request":private]=>
NULL
}
