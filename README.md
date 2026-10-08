# 🚀 Landing Page de Captura — Workshop Corporativo

<p align="center">

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">

  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">

  <img src="https://img.shields.io/badge/UI%2FUX-Conversion-48C5CE?style=for-the-badge" alt="UI/UX Conversion">

</p>

## 🌐 Demonstração Online

<p align="center">

  <a href="https://projeto-workshop-two.vercel.app/" target="_blank">
    <strong>🚀 Acessar o projeto online</strong>
  </a>

</p>

> A versão publicada está disponível na **Vercel**, permitindo visualizar a Landing Page diretamente no navegador.

---

## 📌 Sobre o Projeto

O **Workshop** é uma **Landing Page** desenvolvida para promover um evento corporativo e recolher informações de potenciais participantes através de um formulário de inscrição.

Criado a partir de desafios práticos propostos pela plataforma **ProgramadorBR**, o projeto apresenta uma interface dividida em três áreas principais: um cabeçalho com a proposta do evento, uma seção central com imagem de destaque e formulário de inscrição e um rodapé dedicado à apresentação do palestrante.

O principal objetivo é aplicar conhecimentos de **HTML5 e CSS3** na construção de uma página orientada para apresentação de conteúdo, interação com formulários e adaptação visual dos componentes nativos do navegador.

---

## 🛠️ Detalhes Técnicos

### 📝 Formulário HTML5

O formulário utiliza recursos nativos de validação do HTML5 para verificar os dados introduzidos pelo utilizador antes da submissão.

Entre os recursos utilizados estão:

- `required` para definir campos obrigatórios;
- `minlength` para estabelecer um tamanho mínimo;
- `maxlength` para limitar o número de caracteres;
- tipos específicos de `input`, de acordo com o conteúdo esperado.

Exemplo:

```html
<input type="text" required minlength="10" />
```

Estas regras fornecem uma primeira camada de validação diretamente no navegador.

> **Nota:** a validação do lado do cliente não substitui a validação no servidor numa aplicação real.

### 🔽 Personalização do `<select>`

O elemento `<select>` possui estilos diferentes dependendo do navegador e do sistema operativo.

Para criar uma apresentação visual mais consistente, foi utilizada a propriedade:

```css
appearance: none;
```

A seta nativa é removida e substituída por um elemento visual personalizado através de uma imagem de fundo.

O seu posicionamento pode ser controlado através de:

```css
background-position: calc(100% - 10px) center;
```

Esta abordagem permite maior controlo sobre a aparência do componente.

### 📦 Box Model

Os elementos do formulário utilizam:

```css
box-sizing: border-box;
```

Com esta configuração, o `padding` e a `border` são contabilizados dentro das dimensões definidas para o elemento.

Em conjunto com `width: 100%`, isto ajuda a evitar que os campos ultrapassem os limites do container.

### ✨ Feedback Visual

O container do formulário utiliza um fundo semitransparente e efeitos de interação para criar maior destaque visual.

Através da pseudo-classe `:hover`, é possível alterar a sombra do componente quando o utilizador posiciona o cursor sobre a área.

Exemplo:

```css
.formContainer:hover {
   /* alterações visuais */
}
```

Este tipo de feedback ajuda a tornar a interface mais dinâmica e proporciona uma resposta visual durante a interação.

---

## 📐 Estrutura Visual e Semântica

A página está organizada em três áreas principais.

### Header

O `<header>` apresenta a proposta principal do evento e utiliza uma cor de destaque ciana (`#48c5ce`) para reforçar a identidade visual da página.

O título utiliza letras maiúsculas para criar maior impacto visual e facilitar a identificação imediata da mensagem principal.

### Section

A `<section>` contém a área principal da Landing Page.

Esta seção utiliza uma imagem de fundo adaptável através de:

```css
background-size: cover;
background-position: center;
```

O formulário de inscrição é integrado nesta área, concentrando a principal interação da página.

### Footer

O `<footer>` apresenta informações sobre o palestrante, incluindo fotografia e uma breve descrição.

A área utiliza um fundo escuro (`#202121`) para criar contraste com o restante conteúdo.

Elementos como `display: inline-block` são utilizados para organizar determinados componentes dentro desta seção.

---

## 📱 Responsividade

A estrutura da página foi desenvolvida considerando diferentes tamanhos de ecrã.

A utilização de dimensões relativas, containers e propriedades CSS flexíveis permite adaptar os elementos da interface para dispositivos com diferentes resoluções.

O formulário e os restantes conteúdos podem, assim, ocupar o espaço disponível de forma mais adequada em ecrãs menores.

---

## 💻 Como Executar o Projeto Localmente

Por ser uma aplicação web estática desenvolvida apenas com HTML e CSS, não é necessário instalar dependências ou configurar um ambiente de compilação.

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/projeto-workshop.git
```

### 2. Aceder ao diretório

```bash
cd projeto-workshop
```

### 3. Executar no navegador

Abra o ficheiro `index.html` diretamente num navegador moderno.

Como alternativa, pode utilizar a extensão **Live Server** no Visual Studio Code para executar o projeto através de um servidor local e visualizar as alterações em tempo real.

---

## 📁 Estrutura do Projeto

```text
projeto-workshop/
│
├── index.html
├── style.css
├── imagens/
│   └── ...
└── README.md
```

---

## 📚 Tecnologias e Conceitos Praticados

- **HTML5**
- **CSS3**
- **HTML5 Forms**
- **Validação nativa**
- **CSS Box Model**
- **CSS Pseudo-classes**
- **`appearance: none`**
- **CSS Backgrounds**
- **Responsive Design**
- **UI/UX**
- **Estrutura semântica**

---

## 👨‍💻 Autor

**Rafael Santana** 🚀

> Estudante de Engenharia da Computação, focado no desenvolvimento de interfaces web, organização estrutural e fundamentos de Engenharia de Software.

---

<p align="center">

Projeto desenvolvido para fins educacionais e para consolidação de conhecimentos em HTML5, CSS3 e desenvolvimento de interfaces web.

</p>
