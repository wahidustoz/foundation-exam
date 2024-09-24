### Masala 1: Palindrom tekshiruvi

##### Description

> Berilgan matnni o'qing va uning palindrom ekanligini tekshiring. Palindrom - teskari o'qilganda ham bir xil bo'lgan matn.

> `is_palindrome()` funksiyasi:
> - Argumentlari: bitta string `s`.
> - Return type: `bool`.
> - Agar `s` palindrom bo'lsa `true`, aks holda `false` ni qaytaradi.

#### Input

Bitta string `s` (faqat kichik lotin harflaridan iborat, uzunligi `1 ≤ |s| ≤ 100`).

#### Output

Agar `s` palindrom bo'lsa `true`, aks holda `false` ni chop eting.

###### Namuna 1
| Input | Output |
| - | - | 
| `madam`  | `true` |

###### Namuna 2
| Input | Output |
| - | - | 
| `hello`  | `false` |

###### Namuna 3
| Input | Output |
| - | - | 
| `racecar`  | `true` |

###### Namuna 4
| Input | Output |
| - | - | 
| `level`  | `true` |

---

### Masala 2: So'zlarni teskari tartibda chop etish

##### Description

> Berilgan matnni o'qing va undagi so'zlarni teskari tartibda chop eting.

> `reverse_words()` funksiyasi:
> - Argumentlari: bitta string `s`.
> - Return type: `string`.
> - `s` dagi so'zlarni teskari tartibda qaytaradi.

#### Input

Bitta string `s` (faqat kichik lotin harflaridan iborat, uzunligi `1 ≤ |s| ≤ 100`, so'zlar orasida bitta bo'sh joy mavjud).

#### Output

So'zlarni teskari tartibda chop eting.

###### Namuna 1
| Input | Output |
| - | - | 
| `hello world`  | `world hello` |

###### Namuna 2
| Input | Output |
| - | - | 
| `i love coding`  | `coding love i` |

###### Namuna 3
| Input | Output |
| - | - | 
| `this is a test`  | `test a is this` |

###### Namuna 4
| Input | Output |
| - | - | 
| `example input`  | `input example` |

---

### Masala 3: Unli harflarni sanash

##### Description

> Berilgan matnni o'qing va undagi unli harflar sonini hisoblang. Unli harflar: `a, e, i, o, u`.

> `count_vowels()` funksiyasi:
> - Argumentlari: bitta string `s`.
> - Return type: `int`.
> - `s` dagi unli harflar sonini qaytaradi.

#### Input

Bitta string `s` (faqat kichik lotin harflaridan iborat, uzunligi `1 ≤ |s| ≤ 100`).

#### Output

Unli harflar sonini chop eting.

###### Namuna 1
| Input | Output |
| - | - | 
| `hello`  | `2` |

###### Namuna 2
| Input | Output |
| - | - | 
| `programming`  | `3` |

###### Namuna 3
| Input | Output |
| - | - | 
| `university`  | `4` |

###### Namuna 4
| Input | Output |
| - | - | 
| `education`  | `5` |

---

### Masala 4: Eng uzun so'zni topish

##### Description

> Berilgan matnni o'qing va undagi eng uzun so'zni toping. Agar bir nechta eng uzun so'zlar bo'lsa, ularning birinchisini qaytaring.

> `longest_word()` funksiyasi:
> - Argumentlari: bitta string `s`.
> - Return type: `string`.
> - `s` dagi eng uzun so'zni qaytaradi.

#### Input

Bitta string `s` (faqat kichik lotin harflaridan iborat, uzunligi `1 ≤ |s| ≤ 100`, so'zlar orasida bitta bo'sh joy mavjud).

#### Output

Eng uzun so'zni chop eting.

###### Namuna 1
| Input | Output |
| - | - | 
| `i love programming`  | `programming` |

###### Namuna 2
| Input | Output |
| - | - | 
| `hello world`  | `hello` |

###### Namuna 3
| Input | Output |
| - | - | 
| `find the longest word`  | `longest` |

###### Namuna 4
| Input | Output |
| - | - | 
| `example input string`  | `example` |

---

### Masala 5: Matnni shifrlash (Caesar Cipher)

##### Description

> Berilgan matnni Caesar Cipher usuli bilan shifrlang. Caesar Cipher - har bir harfni alifboda `k` pozitsiya o'ngga siljitish orqali shifrlash usuli.

> `caesar_cipher()` funksiyasi:
> - Argumentlari: bitta string `s` va bitta butun son `k`.
> - Return type: `string`.
> - `s` ni Caesar Cipher usuli bilan shifrlab qaytaradi.

#### Input

Bitta string `s` (faqat kichik lotin harflaridan iborat, uzunligi `1 ≤ |s| ≤ 100`) va bitta butun son `k` (`1 ≤ k ≤ 25`).

#### Output

Shifrlangan matnni chop eting.

###### Namuna 1
| Input | Output |
| - | - | 
| `abc`<br>`3`  | `def` |

###### Namuna 2
| Input | Output |
| - | - | 
| `xyz`<br>`2`  | `zab` |

###### Namuna 3
| Input | Output |
| - | - | 
| `hello`<br>`5`  | `mjqqt` |

###### Namuna 4
| Input | Output |
| - | - | 
| `caesar`<br>`4`  | `geiwev` |
