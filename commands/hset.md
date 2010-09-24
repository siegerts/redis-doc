@complexity

O(1)


Set the specified hash _field_ to the specified _value_.

If _key_ does not exist, a new key holding a hash is created.

If the field already exists, and the `HSET` just produced an update of the
value, 0 is returned, otherwise if a new field is created 1 is returned.

@return

@integer-reply



[1]: /p/redis/wiki/ReplyTypes