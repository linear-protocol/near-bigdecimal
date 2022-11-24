# near-bigdecimal
Big decimal for NEAR smart contracts

## Examples
```rust
let a = BigDecimal::from(3_u128);
let b = BigDecimal::from(10_u128);
let c = BigDecimal::from(49_u128);

assert_eq!((a + b).round_u128(), 13);
assert_eq!((a * b).round_u128(), 30);
assert_eq!((b / a).round_u128(), 3);
assert_eq!((b.pow(2)).round_u128(), 100);
assert_eq!((c.sqrt()).round_u128(), 7);
```
