# 5) Cykly

* slouží k vykonávání opakujících se příkazů

## cyklus s podmínkou na začátku
```cpp
int i{0};

while(i > 0) {
  std::cout << "round: " << i << std::endl;
  i--;
}
```

## cyklus s podmínkou na konci

```cpp
int i{0};

do {
  std::cout << "round: " << i << std::endl;
  i--;
} while(i > 0);
```

## cyklus se známým počtem iterací

```cpp
for(int i{0}; i < 10; i++) {
  std::cout << "round: " << i << std::endl;
}
```

---

https://www.dotnetportal.cz/clanek/176/Cykly-neboli-smycky   
https://www.itnetwork.cz/cecko/zaklady/tutorial-jazyk-c-cykly
