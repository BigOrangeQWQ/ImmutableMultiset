# ImmutableMultiset

# Usage

```moonbit
fn main {
    let set = @multiset.of([1, 2, 3, 3, 4])
    println(set.count(3))

    let set = @hashmultiset.new().add(1, times=4).add(2).add(4)
    if set.contains(2) {
        println(set.count(2))
    }
}
```