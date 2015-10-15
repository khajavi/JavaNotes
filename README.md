# JavaNotes

## Security

1. Authentication: Who is the user?
2. Authorization: What user are authorized (allowed) to do?
3. confidentiality
4. Integrity

### Authentication

#### HTTP Authentication
##### 1. basic authentication
1. very weak: base64 encode of  usser:password transmited
2. no integrity
3. no confidentiality
4. server must maintain raw password (bad idea)
5. example:
    username: webmaster
    password: try2gueSS
    Authorization header: BASIC d2VibWFzdGVyOnRyeTJndWVTUw

##### 2. Digest authentication
1. digest: md5 of (username, password, URI, HTTP Method, randomly generated "nonce")
2. server must maintain raw password


## Interfaces

* [What does it mean to “program to an interface”?](http://stackoverflow.com/questions/383947/what-does-it-mean-to-program-to-an-interface)
