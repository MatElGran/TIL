The return value of an attribute writer is **always the value of the parameter**; the return value of the method is discarded.

In the code that follows, result will be set to 2, even though the attribute setter actually returns 99.

```ruby
class Test
  def val=(val)
    @val = val
    return 99
  end
end

t = Test.new
result = (t.val = 2)
result # => 2
``` 
