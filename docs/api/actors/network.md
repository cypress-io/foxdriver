<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [startListeners](#startlisteners)
-   [stopListeners](#stoplisteners)
-   [sendHTTPRequest](#sendhttprequest)

## startListeners

Start the given Network listeners.

**Parameters**

-   `listeners` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>** console listeners to listen to (default: NetworkActivity) (optional, default `Network.listeners`)

Returns **[Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)** resolves once request has finished

## stopListeners

Stop the given Web Console listeners.

**Parameters**

-   `listeners` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>** console listeners to stop listen to (default: NetworkActivity) (optional, default `Network.listeners`)

Returns **[Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)** resolves once request has finished

## sendHTTPRequest

Send a HTTP request with the given data.

**Parameters**

-   `request` **[Request](https://developer.mozilla.org/en-US/Add-ons/SDK/High-Level_APIs/request)** The details of the HTTP request

Returns **[Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)** resolves once request has finished
