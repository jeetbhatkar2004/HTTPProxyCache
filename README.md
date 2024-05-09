HTTP Proxy with Caching

This is an implementation of an HTTP proxy server in C++ supports caching of responses. The proxy server forwards requests from clients to origin servers and caches the responses it receives. When a client requests a resource that is in the cache, the proxy can respond with the cached copy of the resource rather than re-fetching it from the origin server.

Features
Supports GET, POST, and CONNECT HTTP methods (other methods can be added)
Caches responses to GET requests using expiration time and re-validation rules
Handles multiple concurrent requests effectively using multiple threads
Logs information about each request to /var/log/erss/proxy.log
Assigns a unique identifier to each request for easy tracking in the log
Prints useful log messages to help diagnose issues
Getting Started
Clone the repository: git clone git@github.com:syhuang22/HTTP-Caching-Proxy.git
Run the below command in HTTP-Caching-Proxy directory
sudo docker-compose up
