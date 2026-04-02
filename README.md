# 🛒 Carrinho de Compras em JavaScript

Um projeto educacional de e-commerce desenvolvido em **HTML5**, **CSS3** e **JavaScript vanilla**, apresentando um catálogo dinâmico de miniaturas de aviões históricos da Segunda Guerra Mundial com sistema completo de carrinho de compras.

## 📚 Sobre o Projeto

Projeto desenvolvido em **2021**, durante aulas de Linguagem e Desenvolvimento Web, do curso **Técnico de Informática integrado ao Ensino Médio**, no **Instituto Federal de Caraguatatuba**.

## ✨ Funcionalidades

- ✅ **Catálogo Dinâmico** - Modelos de aviões carregados via JSON
- ✅ **Sistema de Carrinho** - Adicionar, remover e ajustar quantidades de itens
- ✅ **Modal Detalhado** - Visualizar informações completas do produto
- ✅ **Múltiplos Tamanhos** - Diferentes escalas de miniaturas (1/144, 1/72, 1/48, 1/32)
- ✅ **Preços Variáveis** - Valores diferentes por tamanho selecionado
- ✅ **Interface Responsiva** - Design adaptado para diferentes dispositivos
- ✅ **Ícones Material Design** - Integração com Google Material Icons

## 🏛️ Produtos Disponíveis

O catálogo inclui aviões históricos icônicos:

- **F4F Wildcat** - Caça da Marinha dos EUA (Pacífico)
- **Focke Wulf Fw190 A5** - Caça da Luftwaffe
- **Ki 61 - Hien** - Caça Japonês (Kawasaki)
- **Me 109 G6** - Caça Alemão (Messerschmitt)
- **P47 D - Thunderbolt** - Caça-Bombardeiro Americano (FAB)

## 🗂️ Estrutura do Projeto

```
carrinho_compras_js/
├── index.html              # Estrutura HTML principal
├── README.md               # Este arquivo
├── Códigos/                # Documentação adicional
├── css/
│   └── style.css           # Estilos do projeto
├── img/                    # Imagens dos aviões
├── js/
│   ├── models.js           # JSON com dados dos produtos
│   └── script.js           # Lógica e interatividade
```

## 🚀 Como Usar

1. **Clone ou baixe o repositório**
   ```bash
   git clone https://github.com/seu-usuario/carrinho_compras_js.git
   cd carrinho_compras_js
   ```

2. **Abra no navegador**
   - Duplo-clique em `index.html` ou
   - Arraste o arquivo para o navegador ou
   - Use um servidor local (recomendado):
     ```bash
     python -m http.server 8000
     # Acesse em http://localhost:8000
     ```

3. **Navegue pelo catálogo**
   - Clique em um modelo para abrir os detalhes
   - Selecione o tamanho desejado
   - Ajuste a quantidade
   - Clique em "Adicionar ao Carrinho"

4. **Gerencie o carrinho**
   - Clique no ícone do carrinho (🛒) no canto superior
   - Aumente/diminua quantidades conforme necessário
   - Remova itens quando quiser

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e layout responsivo
- **JavaScript ES6** - Dinâmica e interatividade
- **Google Fonts** - Tipografia (Hepta Slab, Lato)
- **Material Icons** - Ícones elegantes

## 🎯 Conceitos Aprendidos

Este projeto aborda:

- Manipulação do DOM
- Clonagem de elementos
- Tratamento de eventos
- Estruturas de dados (arrays e objetos)
- Métodos úteis do JavaScript (`.map()`, `.forEach()`, etc.)
- Armazenamento de dados em estruturas
- Design responsivo
- Padrões de UX em e-commerce

## 📖 Estrutura de Dados

### Modelo de Produto (models.js)

Cada produto segue esta estrutura:

```javascript
{
    id: 1,
    name: 'Nome do Avião',
    img: 'img/caminho.png',
    price: [100.00, 150.00, 200.00],
    sizes: ['1/72', '1/48', '1/32'],
    description: 'Descrição do avião'
}
```

### Item do Carrinho

```javascript
{
    key: 0,           // Índice do produto
    size: 2,          // Índice do tamanho selecionado (0, 1 ou 2)
    quantity: 1       // Quantidade
}
```

## 📝 Licença

Projeto educacional. Criar e modificar livremente para fins educacionais.

## 👤 Autor

Desenvolvido como trabalho acadêmico no Instituto Federal de Caraguatatuba.

---

**Dica:** Para uma melhor experiência visual, certifique-se de que todas as imagens dos aviões estão na pasta `img/`.
