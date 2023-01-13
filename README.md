# Alinhar pontos

## Como utilizar esse código?
Para acessar alguma imagem localmente, na pasta aonde esse arquivo estiver, abra um terminal e inicie um servidor local com o comando <strong>python3 -m http.server 8812</strong>

A imagem estará localizada então em **http://localhost:8812/nome_do_arquivo.png**. 
No exemplo atual, estou usando o arquivo **form.png**, então será encontrado no código em **alinhar_pontos.html** como **http://localhost:8812/form.png**

---
 
### 1. Mude o nome do arquivo

No arquivo **alinhar_pontos.html**, na linha 25 mude o nome do arquivo PNG para a imagem que foi gerada da turma no notebook jupyter

```html
        .attr('xlink:href', 'http://localhost:8812/form.png')
```

### 2. Arraste e solte os pontos que estão desalinhados

### 3. Clique em Download JSON e salve em algum local de sua preferência