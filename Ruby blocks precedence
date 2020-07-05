Curly braces blocks have higher precedence than do end blocks

```ruby
# The block is interpreted as a parameter to `map`
p [1, 2, 3].map { |item| item * 3 }
# [3, 6, 9]
```

```
# The block is interpreted as a parameter to `p`
p [1, 2, 3].map do |item| item * 3; end
#  #<Enumerator: [1, 2, 3]:map>
```
