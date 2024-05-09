HTTP Proxy with Caching

This is an implementation of an HTTP proxy server in C++ supports caching of responses. The proxy server forwards requests from clients to origin servers and caches the responses it receives. When a client requests a resource that is in the cache, the proxy can respond with the cached copy of the resource rather than re-fetching it from the origin server.

Features
Supports GET, POST, and CONNECT HTTP methods (other methods can be added)
Caches responses to GET requests using expiration time and re-validation rules
Handles multiple concurrent requests effectively using multiple threads
Logs information about each request to /var/log/erss/proxy.log
Assigns a unique identifier to each request for easy tracking in the log
Prints useful log messages to help diagnose issues

<img width="1390" alt="Screenshot 2024-05-09 at 12 50 55" src="https://github.com/jeetbhatkar2004/HTTPProxyCache/assets/108226250/83e01f99-cab2-4aef-9e2e-f5048f093962">
