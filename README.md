# Xush kelibsiz
# Mantiqiy ma'lumot turlari (Boolean Data Types)

Uy vazifalari va testlarni avtomatik baholash uchun:
- ushbu repozitoriyani **fork** qiling  
- vazifani bajaring  
- to‘g‘ri xabar bilan commit qiling  
- to‘g‘ri xabar bilan commit qiling  

# Vazifalar
## bool01

  Quyidagi bayonotni tekshiring: **"ular teng"**

**Misol 1:**

```Python
Input: a=1 b=1
Output: True
```

**Misol 2:**

```Python
Input: a=3 b=1
Output: False
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool02

  Quyidagi bayonotni tekshiring: **"O‘zgaruvchi 'a' 7 ga teng"**

**Misol 1:**

```Python
Input: a=1
Output: False
```

**Misol 2:**

```Python
Input: a=7
Output: True
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool03

  Quyidagi bayonotni tekshiring: **"O‘zgaruvchi 'b' musbat"**

**Misol 1:**

```Python
Input: b=-3
Output: False
```

**Misol 2:**

```Python
Input: b=8
Output: True
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool04

  Quyidagi bayonotni tekshiring: **"O‘zgaruvchi 'a' manfiy"**

**Misol 1:**

```Python
Input: a=-3
Output: True
```

**Misol 2:**

```Python
Input: a=8
Output: False
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool05

  Quyidagi bayonotni tekshiring: **"O‘zgaruvchi 'a' toq son"**

**Misol 1:**

```Python
Input: a=8
Output: False
```

**Misol 2:**

```Python
Input: a=5
Output: True
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool06

  Quyidagi bayonotni tekshiring: **"O‘zgaruvchi 'a' juft son"**

**Misol 1:**

```Python
Input: a=8
Output: True
```

**Misol 2:**

```Python
Input: a=5
Output: False
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool07

  Quyidagi bayonotni tekshiring: **"Ular teng emas"**

**Misol 1:**

```Python
Input: a=3 b=1
Output: True
```

**Misol 2:**

```Python
Input: a=5 b=5
Output: False
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool08

  Butun sonni tekshiring. **Butun sonlar - 0 va musbat sonlar.**

**Misol 1:**

```Python
Input: a=3
Output: True
```

**Misol 2:**

```Python
Input: a=0
Output: True
```

**Misol 3:**

```Python
Input: a=-1
Output: False
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

## bool09

  Natural sonni tekshiring. **Natural sonlar sanashda ishlatiladigan sonlardir.**

**Misol 1:**

```Python
Input: a=3
Output: True
```

**Misol 2:**

```Python
Input: a=-1
Output: False
```

**Misol 3:**

```Python
Input: a=7
Output: True
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>, a!=0

---

## bool10

  Sonning mukammal kvadrat ekanligini tekshiring.

**Misol 1:**

```Python
Input: a=9
Output: True
```

**Misol 2:**

```Python
Input: a=15
Output: False
```

**Misol 3:**

```Python
Input: a=121
Output: True
```

**Cheklovlar:**
- -10<sup>18</sup> <= num <= 10<sup>18</sup>

---

# Ogohlantirish
- Boshqalarning yechimlarini yoki har qanday tayyor yechimni **ko‘chirmang**  
- Izohlarni **o‘chirmang**
