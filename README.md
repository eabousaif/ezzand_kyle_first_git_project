# My 4 Favorite Ruby Methods

### `pop`
### removes last element and return it
```a = [ "a", "b", "c", "d" ]
a.pop     #=> "d"
```
### `push`
### pushes objec to an end of a array
```a = [ "a", "b", "c" ]
a.push("d", "e", "f")
```

### `map`
### invokes a block for each element, and returns an array
```a = [ "a", "b", "c", "d" ]
a.collect { |x| x + "!" }
a.map.with_index { |x, i| x * i }
```
### `each`
### calls a block once for each element
```a = [ "a", "b", "c" ]
a.each {|x| print x, " -- " }
```
