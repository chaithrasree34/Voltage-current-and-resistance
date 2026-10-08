# Voltage-current-and-resistance
Here is a simple Python program to calculate **Voltage, Current, or Resistance** using **Ohm’s Law**:

$$
V = I \times R
$$

```
print("Ohm's Law Calculator")
print("1. Calculate Voltage")
print("2. Calculate Current")
print("3. Calculate Resistance")

choice = int(input("Enter your choice (1/2/3): "))

if choice == 1:
    I = float(input("Enter current (A): "))
    R = float(input("Enter resistance (Ω): "))
    V = I * R
    print("Voltage =", V, "V")

elif choice == 2:
    V = float(input("Enter voltage (V): "))
    R = float(input("Enter resistance (Ω): "))
    I = V / R
    print("Current =", I, "A")

elif choice == 3:
    V = float(input("Enter voltage (V): "))
    I = float(input("Enter current (A): "))
    R = V / I
    print("Resistance =", R, "Ω")

else:
    print("Invalid choice")
```

### Example

If you enter:

```
Enter your choice (1/2/3): 1
Enter current (A): 2
Enter resistance (Ω): 5
```

Output:

```
Voltage = 10.0 V
```

This program uses the three forms of **Ohm's Law**:

- **Voltage:** `V = I × R`
- **Current:** `I = V / R`
- **Resistance:** `R = V / I`
