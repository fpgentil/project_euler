A Pythagorean triplet is a set of three natural numbers, a < b < c, for which,

a^2 + b^2 = c^2

For example, 3^2 + 4^2 = 9 + 16 = 25 = 5^2.

There exists exactly one Pythagorean triplet for which a + b + c = 1000.
Find the product abc.


# Benchmarks

### Python
```bash
$ python solutions/problem_9/solution.py
=> Result: 31875000
=> Time: 0.045771s
```

### Ruby
```ruby
$ ruby solutions/problem_9/solution.rb
=> Result: 31875000
=> Time: 0.094352s
```

### Go
```go
$ go run solutions/problem_9/solution.go
=> Result: 31875000
=> Time: 0.05498431s
```

### C
```c
$ gcc -o p9 solutions/problem_9/solution.c utils/c/utils.c -I./utils/c
$ ./p9
=> Result: 31875000
=> Time: 0.024204s
```