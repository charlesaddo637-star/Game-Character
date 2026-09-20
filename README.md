# GameCharacter Class

A Python class that models a simple game character with attributes like health, mana, and level.  
It demonstrates the use of properties, setters, and methods to manage character state safely.

---

## Features
- **Initialization**:
  - Characters start with:
    - Health = 100
    - Mana = 50
    - Level = 1
- **Properties with validation**:
  - `health`: Cannot exceed 100 or drop below 0.
  - `mana`: Cannot exceed 50 or drop below 0.
  - `name`: Read-only property.
  - `level`: Read-only property.
- **Leveling up**:
  - Increases level by 1.
  - Resets health and mana to maximum values.
- **String representation**:
  - Displays character details in a formatted string.

---

## Usage

### 1. Create a Character
```python
hero = GameCharacter("Kratos")
print(hero)
