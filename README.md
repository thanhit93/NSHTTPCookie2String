# NSHTTPCookie2String


#### WKWebView是iOS 8提供的新的API，用于代替之前的UIWebView，同样的之前传递Cookie的方法也不再适合


#### 从Native传Cookie到WKWebView是在实例化WKWebView时，通过WKUserScript将Cookie传到WKWebView，而WKUserScript的参数是Sting。苹果之前提供的NSHTTPCookie没有办法之前转化成String，所以我写了这个extension用来更加方便的进行Cookie传递
