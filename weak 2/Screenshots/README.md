


### Screenshot one

## Explicit Conversion

This code demonstrates **explicit conversion (casting)** from an `int` to a `double`.

```csharp
int number1 = 10;
double number2 = (double)number1;
```

### How It Works

* `int number1 = 10;` → Creates an integer variable.
* `(double)` → Casts the integer to a `double`.
* `double number2` → Stores the converted value.

### Result

```text
number1 = 10
number2 = 10.0
```


### Screenshot two


# C# Integer Division

This code demonstrates **integer division** in C#.

```csharp
int x = 7, y = 3;
MessageBox.Show((x / y).ToString());
```

### How It Works

* `int x = 7, y = 3;` → Creates two integer variables.
* `x / y` → Performs integer division.
* `7 / 3` → Result is `2` because the decimal part is discarded.
* `.ToString()` → Converts the result to a string for `MessageBox.Show()`.

### Output

```text
2
```


### Screenshot three

# C# Try-Catch Example

This code uses `try-catch` to safely convert text from a TextBox into an integer.

```csharp
try
{
    int number = int.Parse(txtshow.Text);
    MessageBox.Show(number.ToString());
}
catch
{
    MessageBox.Show("Please enter a valid number.");
}
```

### How It Works

* `try` → Attempts to execute the code.
* `txtshow.Text` → Gets the text entered in the TextBox.
* `int.Parse()` → Converts the text into an integer.
* `MessageBox.Show()` → Displays the number.
* `catch` → Handles the error if the input is not a valid integer.

### Example

**Input:** `25` → Displays `25`

**Input:** `abc` → Displays `Please enter a valid number.`





