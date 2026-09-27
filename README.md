## What I Learned

- How to calculate a price based on a per-day rate selected through an `if / else if` on vehicle type
- How to apply a conditional discount to an already-calculated value (`price = (price * 90) / 100`)
- How two separate `if` blocks (type selection, then discount check) can each modify the same variable in sequence
- How percentage-based discounts can be applied using integer arithmetic

## Note
If `type` is entered as something other than 1 or 2, `price` is never assigned a value in the first `if / else if`, so it would be used uninitialized. Adding a final `else` to handle invalid input would make this safer.
