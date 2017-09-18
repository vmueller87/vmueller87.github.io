## C-Arrays
> [cpp][1] 4.2
- werden mit `/0` terminiert -> nicht nutzbares Byte
- Länge ist nicht aubrufbar, nur im selben Block wie Deklaration
Bsp. `char * str[] = "HALLO; 		// Zeichenkonstante`
oder `char strArr[] = "Klingeling" 	// Zeichen schreibbar`

- kopieren mit `strcpy(str1, str2)`

[1] Cpp Buch