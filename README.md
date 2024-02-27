#### Write a regular expression for the following languages

###### a) Strings over Σ = {0} of even length.

```
^(00)*$
```

###### a) Strings over Σ = {0, 1} with an even number of zeros.

```
^(1*(01*0)*)*$
```

###### c) Strings over Σ = {0, 1} with an even number of zeros and an odd number of ones.

```
^(((1(11)*0)(1(00)*1)*((1(00)*01)|0))|(0(00)*1(1(00)*1)*((1(00)*01)|0))|((0(00)*01)|1))(((((10(00)*1)|0)(1(00)*1)*((1(00)*01)|0))|(11))*)$
```
