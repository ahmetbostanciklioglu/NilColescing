# NilColescing




**Nil Coalescing:**
```
func nilCoalescingFunc(_ param: Int) -> String? {
    if param == 13 {
        return "Ahmet"
    }else {
        return nil
    }
    
}
let nilCoalescingObject = nilCoalescingFunc(18) ?? "Alex"
print(nilCoalescingObject)
```
