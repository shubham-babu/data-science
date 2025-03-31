# 📊 Types of Means in Statistics

## 1️⃣ Arithmetic Mean (AM)
The **Arithmetic Mean (AM)** is the simple average of a set of numbers.

### **Formula:**
```math
AM = \frac{1}{N} \sum x_i
```

### **Example:**
For values **(4, 8, 16):**
```math
AM = \frac{4 + 8 + 16}{3} = \frac{28}{3} \approx 9.33
```

### **Use Cases:**
- General **average calculations**.
- **Data analytics & statistics**.

---

## 2️⃣ Geometric Mean (GM)
The **Geometric Mean (GM)** is useful when dealing with **multiplicative** processes like **compound interest**.

### **Formula:**
```math
GM = \sqrt[N]{\prod x_i}
```

### **Example:**
For values **(4, 8, 16):**
```math
GM = \sqrt[3]{4 \times 8 \times 16} = \sqrt[3]{512} = 8
```

### **Use Cases:**
- **Stock market returns**.
- **Interest rates**.
- **Population growth**.

---

## 3️⃣ Harmonic Mean (HM)
The **Harmonic Mean (HM)** is best for **rates and ratios**.

### **Formula:**
```math
HM = \frac{N}{\sum \left( \frac{1}{x_i} \right)}
```

### **Example:**
For values **(4, 8, 16):**
```math
HM = \frac{3}{\left( \frac{1}{4} + \frac{1}{8} + \frac{1}{16} \right)} = \frac{3}{0.4375} \approx 6.86
```

### **Use Cases:**
- **Speed calculations**.
- **Electrical resistance**.
- **Rates of return**.

---

## 4️⃣ Quadratic Mean (Root Mean Square - RMS)
Used when dealing with **varying positive and negative values** like **voltage and signal processing**.

### **Formula:**
```math
RMS = \sqrt{\frac{1}{N} \sum x_i^2}
```

### **Example:**
For values **(3, 4, 5):**
```math
RMS = \sqrt{\frac{3^2 + 4^2 + 5^2}{3}} = \sqrt{\frac{50}{3}} \approx 4.08
```

### **Use Cases:**
- **Physics (AC voltage calculations)**.
- **Signal processing**.
- **Machine learning (MSE)**.

---

## 5️⃣ Weighted Mean
The **Weighted Mean** is used when some values have more importance.

### **Formula:**
```math
WM = \frac{\sum w_i x_i}{\sum w_i}
```

### **Example:**
For scores **(80, 90, 70)** with weights **(3, 2, 1):**
```math
WM = \frac{(80 \times 3) + (90 \times 2) + (70 \times 1)}{3 + 2 + 1} = \frac{490}{6} \approx 81.67
```

### **Use Cases:**
- **Grading systems**.
- **Stock market indices**.
- **Economic indicators**.

---

## 6️⃣ Truncated Mean (Trimmed Mean)
Removes **outliers** before computing the mean.

### **Example:**
For values **(10, 12, 14, 100, 110)**, removing **extreme values (10, 110):**
```math
Truncated Mean = \frac{12 + 14 + 100}{3} = 42
```

### **Use Cases:**
- **Sports scoring**.
- **Economic indicators**.

---

## 7️⃣ Mode
The **Mode** is the **most frequently occurring value**.

### **Example:**
For **(3, 5, 5, 7, 8, 5, 9):**
```math
Mode = 5
```

### **Use Cases:**
- **Surveys & polls**.
- **Retail sales**.

---

## 8️⃣ Median
The **Median** is the **middle value** of a sorted dataset.

### **Example:**
For **(1, 3, 5, 7, 9):**
```math
Median = 5
```
For **(1, 3, 5, 7):**
```math
Median = \frac{3 + 5}{2} = 4
```

### **Use Cases:**
- **Income distribution**.
- **Real estate prices**.

---

## 9️⃣ Harmonic-Geometric-Arithmetic (HGA) Mean
Combines AM, GM, and HM into a single formula.

### **Formula:**
```math
HGA = \sqrt{\frac{AM \times GM \times HM}{3}}
```

### **Use Cases:**
- **Theoretical analysis** in mathematics.

---

## 🔥 Summary Table
| **Mean Type** | **Formula** | **Use Cases** |
|--------------|------------|--------------|
| **Arithmetic Mean (AM)** | ```\( \frac{1}{N} \sum x_i \) ```| General averages |
| **Geometric Mean (GM)** | \( \sqrt[N]{\prod x_i} \) | Growth rates, finance |
| **Harmonic Mean (HM)** | \( \frac{N}{\sum \left( \frac{1}{x_i} \right)} \) | Speed, rates |
| **Quadratic Mean (RMS)** | \( \sqrt{\frac{1}{N} \sum x_i^2} \) | Physics, ML |
| **Weighted Mean** | \( \frac{\sum w_i x_i}{\sum w_i} \) | Grades, stock market |
| **Truncated Mean** | AM after removing outliers | Robust statistics |
| **Mode** | Most frequent value | Surveys, retail |
| **Median** | Middle value | Income, real estate |
| **HGA Mean** | \( \sqrt{\frac{AM \times GM \times HM}{3}} \) | Theoretical studies |

---

### ✅ **Key Rule:**
```math
HM \leq GM \leq AM
```
(Harmonic Mean is always the smallest, and Arithmetic Mean is always the largest!)

---

### **📌 Save this for reference!** 🚀

