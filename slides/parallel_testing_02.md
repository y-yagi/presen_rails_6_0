### Parallel Testing

```ruby
class ActiveSupport::TestCase
  # Run tests in parallel with specified workers
  parallelize(workers: :number_of_processors, with: :processes)
end
```
