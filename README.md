# 🧮 Calculadora de Desconto
 
Calculadora web que aplica desconto automático sobre o valor de uma compra, de acordo com faixas de preço. O usuário informa o valor, e a página mostra o percentual aplicado e o valor final. Projeto acadêmico da faculdade **Piaget**, desenvolvido para praticar **variáveis e estruturas condicionais em JavaScript**.
 
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Linguagem principal](https://img.shields.io/github/languages/top/ThomazLaizo/CalculadoraDesconto-Piaget)
 
## 🎓 Sobre o projeto
 
Este projeto foi desenvolvido na faculdade **Piaget** como atividade prática de JavaScript, com foco em **variáveis** e **condicionais** (`if / else if / else`).
 
> 🤖 **Uso de IA:** o front-end (HTML e CSS) foi criado com auxílio de inteligência artificial. A lógica em JavaScript, que é o objetivo da atividade, foi desenvolvida por mim.
 
## ✨ Funcionalidades
 
- Entrada do valor da compra em reais (aceita centavos)
- **Desconto automático por faixa de valor**
- Exibição do valor original, do percentual de desconto e do **valor final**
- Valores formatados no padrão brasileiro (`R$ 0,00`)
- Layout em formato de "recibo", responsivo e com foco em acessibilidade (`aria-live`, `role="alert"`, estados de foco)
## 💸 Regras de desconto
 
| Valor da compra | Desconto |
|---|---|
| Menor que R$ 100,00 | Sem desconto |
| De R$ 100,00 até R$ 499,99 | **5%** |
| A partir de R$ 500,00 | **10%** |
 
## 🧠 Conceitos praticados
 
| Conceito | Onde aparece |
|---|---|
| **Variáveis** | Valor da compra, percentual de desconto e valor final (`var`) |
| **Estruturas condicionais** | `if / else if / else` para definir a faixa de desconto |
| **Operadores lógicos e de comparação** | `>=`, `<` e `&&` nas faixas de valor |
| **Manipulação do DOM** | `getElementById` e `textContent` para exibir os resultados |
| **Eventos** | `addEventListener('submit')` com `preventDefault()` |
| **Conversão e formatação de números** | `Number()`, `toFixed(2)` e `replace('.', ',')` |
 
## 🗂️ Estrutura do projeto
 
```
CalculadoraDesconto-Piaget/
├── index.html    # Estrutura da página
├── styles.css    # Estilos (feito com IA)
├── main.js       # Lógica do cálculo de desconto
├── LICENSE
└── README.md
```
 
## 🛠️ Tecnologias
 
- **HTML5**
- **CSS3** (variáveis CSS, Flexbox e Grid)
- **JavaScript** (puro, sem bibliotecas)
## ▶️ Como executar
 
Não é necessário instalar nada. Basta clonar o repositório e abrir o `index.html` no navegador:
 
```bash
# 1. Clone o repositório
git clone https://github.com/ThomazLaizo/CalculadoraDesconto-Piaget.git
 
# 2. Entre na pasta do projeto
cd CalculadoraDesconto-Piaget
 
# 3. Abra o index.html no navegador (ou use a extensão Live Server do VS Code)
```
 
## 🖥️ Como usar
 
1. Digite o valor da compra no campo **Valor da compra (R$)**.
2. Clique em **Calcular desconto**.
3. Veja o valor original, o percentual aplicado e o valor com desconto.
**Exemplo:** uma compra de `R$ 250,00` recebe 5% de desconto e o valor final é `R$ 237,50`.
 
## 🛣️ Roadmap
 
- [ ] Validar a entrada (a mensagem de erro já existe no HTML, mas ainda não é usada pelo JavaScript)
- [ ] Exibir também o valor do desconto em reais, não só o percentual
- [ ] Mostrar as regras de desconto na própria página
- [ ] Trocar `var` por `let` e `const`
- [ ] Declarar todas as variáveis (`campo_desconto` está sem declaração)
- [ ] Testes automatizados
## 📄 Licença
 
Distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
 
## 👤 Autor
 
Feito por **[Thomaz Laizo](https://github.com/ThomazLaizo)**.
