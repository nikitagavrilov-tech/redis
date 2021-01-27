# Redis

Command          | Meaning
-----------------|-------------
set KEY VALUE    | Sets key/value pair
get KEY          | Gets value by key
exists KEY       | Checks if key exists
flushall         | Flushes everything
set KEY VALUE ex 20 | Sets value with expiration of 20 seconds
set KEY VALUE px 20 | Sets value with expiration of 20 milliseconds
getset KEY VALUE | Gets old value and sets new
append KEY VALUE | Appends a string to the old value. Returns number of characters of the new value
keys PATTERN    | Returns all the keys satifying certain pattern
incr KEY        | Increments value by 1
incr counter    | Creates `counter` key and sets its value to 1
decr KEY        | Decrements value by 1
hset NAME KEY VALUE | Creates hashset and sets key and value inside of it
hget NAME KEY    | Gets value inside hashset by key

