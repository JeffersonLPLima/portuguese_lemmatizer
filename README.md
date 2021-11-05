## Fast Portuguese Lemmatizer

### Example
```

l = Lemmatizer()
l.get_lemma('carrinho')  #all words must be unidecoded and lowercased
>> 'carro'
l.get_lemma('carros')
>> 'carro'

```
### Files:

`pt_lemma.py` :  Simple class to perform lemmatization
`./data/`:  data used to generate lemma dict

