# Minitask Algoritma

Membuat algoritma menentukan bilangan ganjil atau genap

Langkah-langkah:
1. Mulai
2. Memasukkan X
4. Jika X lebih besar dari 0, maka lanjutkan ke langkah berikutnya, jika tidak maka kembali ke langkah kedua
5. Jika X dapat habis dibagi 2, maka outputkan "genap"
6. Jika X tidak habis dibagi 2, maka outputkan "ganjil"
8. Selesai

# Flowchart

```mermaid
flowchart TD
A((Mulai))
B[/X/]
C{X > 0}
D{X % 2 == 0}
E[/'"Genap"'/]
F[/'"Ganjil"'/]
G(((Selesai)))

A --> B --> C --Ya--> D
C --Tidak--> B
D --Ya--> E
D --Tidak--> F
E & F --> G
```

# Pseudo-Code
```
// Program Ganjil Genap

DECLARE X: INTEGER

WHILE X <= 0 OR X == NULL
    INPUT X
    IF X MOD 2 = 0 THEN
        OUTPUT "GENAP"
    ELSE
        OUTPUT "GANJIL"
    ENDIF  
ENDWHILE 
```