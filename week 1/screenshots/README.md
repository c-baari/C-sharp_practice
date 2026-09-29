### Screenshot one

## String variable in a Message Box:
This code runs when **Button 1** is clicked and displays `"Jamhuuriya University"` in `textBox2`.

```csharp
private void button1_Click(object sender, EventArgs e)
{
    String productDescription = "Jamhuuriya University";
    textBox2.Text = productDescription;
}
```

### How It Works

* `button1_Click` → Event handler for the button click.
* `String productDescription` → Creates a string variable.
* `"Jamhuuriya University"` → Value stored in the variable.
* `textBox2.Text` → Displays the value inside the TextBox.
* `object sender` → Identifies the object that triggered the event.
* `EventArgs e` → Provides event information.

### Output

When **Btndisplay** is clicked:

```text
Jamhuuriya University
```


### Screenshot two

## # C# String Concatenation

This code demonstrates how to **join two strings together** and display the result using a `MessageBox`.

```csharp
String messsage;

messsage = "Jamhuuriyа" + " University";

MessageBox.Show(messsage);
```

### How It Works

* `string messsage;` → Declares a string variable.
* `+` → Concatenates (joins) strings together.
* `"Jamhuuriyа" + " University"` → Produces `"Jamhuuriyа University"`.
* `MessageBox.Show(messsage);` → Displays the message in a pop-up box.

### Output

```text
Jamhuuriyа University
```