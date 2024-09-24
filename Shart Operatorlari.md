### Masala 1: Yosh toifalovchi

###### Tavsif

> Biror shaxsni yosh toifalariga ajratuvchi dastur yozing.
> - Agar `0 ≤ A < 13` bo'lsa: "Bola"
> - Agar `13 ≤ A < 20` bo'lsa: "O'smir"
> - Agar `20 ≤ A < 60` bo'lsa: "Katta yoshdagi"
> - Agar `A ≥ 60` bo'lsa: "Qariya"

###### Input

Bitta butun son `A` (yosh).

###### Output

Yosh toifasiga qarab, mos ravishda "Bola", "O'smir", "Katta yoshdagi" yoki "Qariya" matnini chop eting.

###### Namuna 1

| Input | Output |
| - | - |
| `25` | `Katta yoshdagi` |

###### Namuna 2

| Input | Output |
| - | - |
| `70` | `Qariya` |

###### Namuna 3

| Input | Output |
| - | - |
| `12` | `Bola` |

###### Namuna 4

| Input | Output |
| - | - |
| `16` | `O'smir` |

---

### Masala 2: Uchburchak turi aniqlovchi

###### Tavsif

> Uchta butun sonni o'qing va uchburchakning turini aniqlang.
> - Agar barcha tomonlar teng bo'lsa, "Teng tomonli" deb chop eting.
> - Agar ikki tomon teng bo'lsa, "Teng yonli" deb chop eting.
> - Agar barcha tomonlar har xil bo'lsa, "Har xil tomonli" deb chop eting.

###### Input

Uchta butun son \( a \), \( b \), va \( c \) - uchburchak tomonlari.

###### Output

Uchburchak turini aniqlab, mos ravishda "Teng tomonli", "Teng yonli" yoki "Har xil tomonli" matnini chop eting.

###### Namuna 1

| Input | Output |
| - | - |
| `3 3 3` | `Teng tomonli` |

###### Namuna 2

| Input | Output |
| - | - |
| `3 4 4` | `Teng yonli` |

###### Namuna 3

| Input | Output |
| - | - |
| `3 4 5` | `Har xil tomonli` |

---

### Masala 3: Unli yoki undosh harf aniqlovchi

###### Tavsif

> Berilgan belgi unli yoki undosh harf ekanligini aniqlaydigan dastur yozing.

###### Input

Bitta belgi \( ch \) - harf.

###### Output

Agar harf unli bo'lsa, "Unli" deb chop eting. Aks holda, "Undosh" deb chop eting.

###### Namuna 1

| Input | Output |
| - | - |
| `a` | `Unli` |

###### Namuna 2

| Input | Output |
| - | - |
| `b` | `Undosh` |

###### Namuna 3

| Input | Output |
| - | - |
| `e` | `Unli` |

---

### Masala 4: BMI Hisoblagich

###### Tavsif

> Tana Massasi Indeksi (BMI) ni hisoblaydigan va uni toifalaydigan dastur yozing.
> - Agar BMI < 18.5 bo'lsa: "Ozish"
> - Agar 18.5 ≤ BMI < 24.9 bo'lsa: "Normal vazn"
> - Agar 25 ≤ BMI < 29.9 bo'lsa: "Semizlik"
> - Agar BMI ≥ 30 bo'lsa: "Ortacha semizlik"

###### Input

Ikki suzuvchi nuqtali son \( weight \) (kg da) va \( height \) (metrlarda).

###### Output

BMI ni hisoblang va mos ravishda toifani chop eting.

###### Namuna 1

| Input | Output |
| - | - |
| `70 1.75` | `Normal vazn` |

###### Namuna 2

| Input | Output |
| - | - |
| `85 1.75` | `Semizlik` |

###### Namuna 3

| Input | Output |
| - | - |
| `50 1.60` | `Ozish` |

---

### Masala 5: Haftaning kuni

###### Tavsif

> Haftaning raqamlangan kunini aniqlab, mos keluvchi kun nomini chop eting.
> - 1: "Dushanba"
> - 2: "Seshanba"
> - 3: "Chorshanba"
> - 4: "Payshanba"
> - 5: "Juma"
> - 6: "Shanba"
> - 7: "Yakshanba"

###### Input

Bitta butun son \( D \) (1-7 oralig'ida).

###### Output

Kiritilgan raqamga mos haftaning kunini chop eting.

###### Namuna 1

| Input | Output |
| - | - |
| `3` | `Chorshanba` |

###### Namuna 2

| Input | Output |
| - | - |
| `7` | `Yakshanba` |

###### Namuna 3

| Input | Output |
| - | - |
| `5` | `Juma` |
