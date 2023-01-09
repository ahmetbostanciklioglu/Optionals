# Optionals



***Optionals:**
```
var optionalString: String? = nil
optionalString = "Ahmet"

class OptionalIntClass {
    var optionalInt: Int?
    var optionalIntNil : Int? = nil
    init(optionalInt: Int) {
        self.optionalInt = optionalInt
    }
}

let optionalIntObject = OptionalIntClass(optionalInt: 9)
optionalIntObject.optionalInt
optionalIntObject.optionalIntNil = 6
```
