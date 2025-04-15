### 💻 **Tecnologias Utilizadas**

#### **Frontend (Interface do site)**
- **HTML5 e CSS3**  
  Estrutura e estilização da página.
- **JavaScript (jQuery)**  
  Usado para interações, validações e funcionalidades dinâmicas.
- **Slick Slider**  
  Biblioteca de carrossel para exibir depoimentos e logos de clientes.
- **PhotoSwipe**  
  Para abrir imagens em lightbox com efeito de galeria.
- **Modernizr**  
  Verifica suporte a recursos modernos do navegador.
- **AOS (Animate on Scroll)**  
  Animações quando elementos entram na tela ao rolar.
- **Fontes Customizadas**  
  Montserrat e Lora (em `.woff`, `.ttf`, etc).
- **Icon fonts personalizados (icomoon)**  
  Conjunto de ícones definidos via CSS.

---

#### **Backend (Contato por formulário)**
- **PHP (`sendEmail.php`)**
  - Responsável por receber os dados do formulário de contato e enviar por email.
  - Validações básicas: nome, e-mail e mensagem.
  - Usa a função `mail()` do PHP.
  
---

### 🔧 **Funcionalidades do Projeto**

1. **Portfólio Pessoal** (aparência moderna com interações):
   - Página com animações suaves e design responsivo.
   - Seções como "Sobre", "Projetos", "Depoimentos", etc.
   - Efeitos de rolagem, carrossel de logos e projetos clicáveis com zoom (PhotoSwipe).

2. **Formulário de Contato**
   - Campos: nome, email, assunto e mensagem.
   - Validação em tempo real com jQuery Validate.
   - Envio assíncrono (AJAX) para `sendEmail.php`.
   - Feedback de sucesso ou erro sem recarregar a página.

3. **Integração com Mailchimp**
   - O script tem integração com o Mailchimp via AjaxChimp (lista de emails).
   - URL configurada para capturar emails (mas o domínio usado é exemplo do template original).

---

### 📝 Conclusão:

> Meu projeto é um **site de portfólio pessoal moderno**, com foco em design limpo e responsivo. Ele permite que visitantes:
