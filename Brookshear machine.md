# Brookshear machine 

## The different op codes

* Op-code 1 contains the address of the data to be loaded 

```
MOV AA -> R2
```

* Op-code 2 contains the data to be loaded 

```
MOV data1 -> R3
data1: DATA 10101010
```

* Op-code D load register with contents from memory location 

```
MOV 80 -> R4
MOV data1 -> R5
MOV [R4] -> R5
data1: DATA 10101010
```

* Op-code E Store contents of register in memory location 

```
MOV 80 -> R4
MOV data1 -> R5
MOV R5 -> [R4]
data1: DATA 10101010
```
