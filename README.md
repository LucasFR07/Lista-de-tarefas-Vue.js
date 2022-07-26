# Lista de Tarefas com Vue.js

## Configuração do projeto
```
npm install
```

### Compila e recarrega os arquivos para desenvolvimento
```
npm run build
```

### Lint corrige arquivos
```
npm run lint
```

## Rodar o JSON SERVER (dentro da pasta API)
```
json-server --watch database.json
```

## Rodar Servidor Local Vue.js (dentro da pasta todolistvuejs)
```
npm run serve
```

**FUNCIONALIDADES**

1-) Adicionar nova tarefa (TECLA: Enter)
- Só é possível adicionar uma nova tarefa se todas as informações estiverem preenchidas.

2-) Alterar status para concluído (Marcar como finalizado: status ficará verde)

3-) Editar tarefa (É possivel mesmo após adicionada)
- Só é possível fazer a edição se tiver algum valor diferente do valor inicial.

4-) Remover tarefa (DELETE: Icone)

**O que foi utilizado no desenvolvimento deste projeto?**

- Vue.js (Composition API)
- Axios (Consumo de API)
- JSON SERVER (Simular servidor)
- HTML
- TAILWIND.CSS
- ESlint
- SPA
- Vue CLI

### Personalizar configuração
[Configuração de referência](https://cli.vuejs.org/config/).
