# module

```javascript
  console.log(`Olá, ${ESM || CJS}`); 
```

## Módulos

Primeira dica para guardar é : `Cada arquivo (.js) é um módulo`, se quisermos usar um trecho do código ou uma funcionalidade contida no módulo em questão , precisaremos exportar este trecho usando o : 
```javascript 
module.exports = <funcionalidade>; 
```
## Dica: 
Existe dois tipos de sintaxe para importar ou exportar módulos e elas são: Anterior ao Es6 cujo nome é o CommonJS ou CJS, este é o padrão exemplificado acima.

## Importando funcionalidades de outros módulos `( CommonJS ou CJS )`.

A função **require ( )** é responsável por importar funcionalidades de outros módulos. **Obs: Lembrando que módulos são todos os arquivos no formato (.js)**.

