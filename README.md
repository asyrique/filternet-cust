# filternet-customised - A simple way to filter http in node.js

All functionality mirrors that in [filternet](https://github.com/axiak/filternet) except below:

### Event: interceptRequest <tt>function (requestOptions, callback)</tt>

requestOptions is a map of data to be sent to http.request. callback expects requestOptions to continue the request.

The default behavior is callback(requestOptions, eventEmitter);

An eventEmitter can be passed to callback to copy out the request data;


