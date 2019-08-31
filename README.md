### minimalftp
---
https://github.com/Guichaguri/MinimalFTP

```java
File root = new File(System.getProperty("user.dir"));
NativeFileSystem fs = new NativeSystem(root);
NoOpAuthenticator auth = new NoOpAuthenticator(fs);
FTPServer server = new FTPServer(auth);
server.listenSync(21);
```

```
```

```
```


