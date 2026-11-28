# Mission 5 - Numbers And Data

## Task 5.1 — Convert numbers by hand

| Question | Working | Answer |
|---|---|---|
| Decimal 13 to binary | 13 = 8 + 4 + 1 | `1101` |
| Decimal 25 to binary | 25 = 16 + 8 + 1 | `11001` |
| Binary `1010` to decimal | 1×8 + 0×4 + 1×2 + 0×1 | `10` |
| Binary `1101` to decimal | 1×8 + 1×4 + 0×2 + 1×1 | `13` |
| Hexadecimal `A` to decimal | A represents ten | `10` |
| Hexadecimal `1F` to decimal | 1×16 + 15 | `31` |
| Binary `1111` to hexadecimal | 1111 in binary equals 15 in decimal | `F` |

## Task 5.2 — Verify using Python

I used Python’s built-in conversion functions to check my answers.

| Conversion checked | Python expression | Result |
|---|---|---|
| Decimal 13 to binary | `bin(13)` | `0b1101` |
| Binary `1010` to decimal | `int("1010", 2)` | `10` |
| Decimal 31 to hexadecimal | `hex(31)` | `0x1f` |
| Hexadecimal `1F` to decimal | `int("1F", 16)` | `31` |

The prefixes `0b` and `0x` indicate binary and hexadecimal values in Python.

## Task 5.3 — Test the number converter

| Test number | Binary output | Hexadecimal output |
|---:|---:|---:|
| 13 | `1101` | `D` |
| 25 | `11001` | `19` |
| 31 | `11111` | `1F` |

## Task 5.4 — How is text stored?

Computers store text as numbers because they process information digitally. A character-encoding standard assigns a number to each letter, digit, or symbol. The computer can then store and process those numbers, and compatible systems can interpret them as the intended characters.

**ASCII codes**
- Uppercase `A` has the decimal ASCII code **65**.
- Lowercase `a` has the decimal ASCII code **97**.

**Why does a computer need an encoding standard?**  
An encoding standard gives computers a shared mapping between characters and numbers. Without shared rules, the same stored data might appear as different characters on different devices. Standards help computers store, display, and exchange text consistently.

**Example of a character outside basic ASCII**  
The Indian rupee symbol `₹` is not part of basic ASCII. It is included in Unicode and can be represented using UTF-8. UTF-8 can encode a much wider range of characters than basic ASCII, including characters used in many languages and symbols.

**What I learned**  
I learned that text is represented by numeric codes rather than stored as letters in the same way people see them. ASCII provides codes for a basic set of characters, while Unicode supports a much broader set. UTF-8 is one way of encoding Unicode characters so they can be stored and exchanged as data.
