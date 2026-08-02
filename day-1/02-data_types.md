
<img width="1122" height="1402" alt="image" src="https://github.com/user-attachments/assets/89967a95-9f99-4c56-96fe-88f302e4cec3" />
# 📚 Data Types in Python

## What are Data Types?

A **data type** defines the kind of value a variable can store. It tells Python how the data should be stored in memory and what operations can be performed on it.

Python is a **dynamically typed** language, which means you don't need to declare the data type of a variable. Python automatically identifies the data type based on the value you assign.

Python provides several built-in data types that make it easy to work with different kinds of data.

---

# 🔢 Numeric Data Types

Numeric data types are used to store numbers.

### `int`

Represents **integers (whole numbers)**.

**Example:**

```python
x = 5
```

### `float`

Represents **floating-point numbers (decimal values)**.

**Example:**

```python
y = 3.14
```

### `complex`

Represents **complex numbers**.

**Example:**

```python
z = 2 + 3j
```

---

# 📝 Sequence Types

Sequence types store multiple values in a specific order.

### `str`

Represents **strings**, which are sequences of characters.

**Example:**

```python
text = "Hello, World"
```

### `list`

Represents **lists**, which are ordered and mutable collections.

**Example:**

```python
my_list = [1, 2, 3]
```

### `tuple`

Represents **tuples**, which are ordered but immutable collections.

**Example:**

```python
my_tuple = (1, 2, 3)
```

---

# 🗂️ Mapping Type

### `dict`

Represents **dictionaries**, which store data as **key-value pairs**.

**Example:**

```python
my_dict = {
    "name": "John",
    "age": 30
}
```

---

# 📦 Set Types

Set types store unique values.

### `set`

Represents an **unordered collection of unique elements**.

**Example:**

```python
my_set = {1, 2, 3}
```

### `frozenset`

Represents an **immutable set**, which means its values cannot be changed after creation.

**Example:**

```python
my_frozenset = frozenset([1, 2, 3])
```

---

# ✅ Boolean Type

### `bool`

Represents a Boolean value, which can only be **True** or **False**.

**Example:**

```python
is_valid = True
```

---

# 💾 Binary Types

Binary types are used to store binary data.

### `bytes`

Represents an **immutable sequence of bytes**.

**Example:**

```python
data = b"Hello"
```

### `bytearray`

Represents a **mutable sequence of bytes**.

**Example:**

```python
data = bytearray(b"Hello")
```

---

# 🚫 None Type

### `NoneType`

Represents the `None` object, which indicates the **absence of a value** or a **null value**.

**Example:**

```python
result = None
```

---

# 🏗️ Custom Data Types

Python also allows you to create your own data types using **classes and objects**.

This is useful when you want to model real-world objects or build your own reusable components.

**Example:**

```python
class Person:
    pass
```
