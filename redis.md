# Redis online editor
Write, Run & Share Redis queries online using OneCompiler's Redis online editor and compiler for free. It's one of the robust, feature-rich online editor and compiler for Redis. Getting started with the OneCompiler's Redis editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose database as 'Redis' and start writing queries to learn and test online without worrying about tedious process of installation.

# About Redis

Redis is a open source, no SQL database which works on the concept of key-value pair.

### Key Features:

* In-memory data structure store
* Works on Redis Client and Redis Server architecture where client and server can be on same computer or on different computers
* Extremely fast
* Supports append-only file persistence mode
* Follows a very simple and fast Master/Slave replication
* supports a number of languages

# Syntax help

## Commands

| Command | Syntax |
|----|----|
| Set| SET KEY_NAME VALUE|
| Get| GET KEY_NAME|
| Getset|GETSET KEY_NAME VALUE|
| SetRange | SETRANGE KEY_NAME OFFSET VALUE|
| Strlen| STRLEN KEY_NAME |
| Append| APPEND KEY_NAME NEW_VALUE|
| Exists | EXISTS KEY_NAME|
| Delete | del KEY_NAME|
| Increment counter | incr KEY_NAME|
| Decrement counter | decr KEY_NAME|
| Push Value to List | lpush listName value|
| Push Value to Start/Beginning | rpush listName value|
| Push Value to List only if it exists | lpushx listName value|
| Remove & return value from list| lpop listName|
| Remove & return value from Start/Beginning|rpop listName|
| Set xth position element to value | lset listName x-1 value|
| Check if hash key exists | hexists hashName field|
| Get a hash key | hget hashName field|
| Delete a hash key | hdel hashName field|
| Get all hash content | hgetall hashName|
| List all hash keys | hkeys hashName|
| List number of hash keys | hlen hashName|
| Get multiple hash keys|  hmget key1 key2 ...|
| Set multiple hash keys|  hmset key1 value1 key2 value2...|
| Increment a hash key | hincrby hashName field incrValue|
