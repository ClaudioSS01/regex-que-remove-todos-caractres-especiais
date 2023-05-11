# regex-que-remove-todos-caractres-especiais
```
const string = 'Exemplo!@#$ de {string} com [caracteres] especiais.';
const resultado = string.replace(/[^\w\s]/g, '');

console.log(resultado);
// Saída: Exemplo de string com caracteres especiais

```
