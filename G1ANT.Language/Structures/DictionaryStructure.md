# dictionary

The dictionary structure stores a dictionary entry, which is a key-value pair separated with an [array separator](https://manual.g1ant.com/link/G1ANT.Manual/appendices/special-characters/array-separator.md) (❚). Dictionaries are used in databases, for example.

## Example

Here is a simple declaration of a dictionary entry (key: `address`, value: `street`) and accessing a value of a specified key:

```G1ANT
♥entry = ⟦dictionary⟧address❚street
dialog ♥entry⟦address⟧
```

