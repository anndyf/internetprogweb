
# Aula 1 – Estruturação do Site com Menu de Navegação (com código)

🕒 Duração: 40 minutos  
🎯 Objetivo: Criar a estrutura completa em HTML de um site sobre Python, incluindo um menu de navegação funcional.

---

## 🧱 Etapa 1: Estrutura Base

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Python para Iniciantes</title>
</head>
<body>
  <!-- Conteúdo aqui -->
</body>
</html>
```

✅ **Explicação**:
- `<!DOCTYPE html>`: Informa que usamos HTML5.
- `<html lang="pt-br">`: Raiz do documento e define o idioma.
- `<head>`: Metadados da página.
- `<body>`: Tudo o que será exibido ao usuário.

---

## 🧱 Etapa 2: Cabeçalho e Menu de Navegação

```html
<header>
  <h1>Python para Iniciantes</h1>
  <nav>
    <ul class="menu">
      <li><a href="#inicio">Início</a></li>
      <li><a href="#vantagens">Vantagens</a></li>
      <li><a href="#recursos">Recursos</a></li>
      <li><a href="#sobre">Sobre</a></li>
    </ul>
  </nav>
</header>
```

✅ **Explicação**:
- `<header>`: Cabeçalho do site.
- `<nav>`: Área de navegação.
- `<ul>`: Lista não ordenada com links.
- `href="#id"`: Faz ligação com seções na mesma página.

---

## 🧱 Etapa 3: Seções do Conteúdo

```html
<main>
  <section id="inicio">
    <h2>Bem-vindo ao Guia de Python</h2>
    <p>Python é uma linguagem poderosa e simples.</p>
  </section>

  <section id="vantagens">
    <h2>Por que aprender Python?</h2>
    <ul>
      <li>Sintaxe simples</li>
      <li>Versátil e poderosa</li>
      <li>Ampla comunidade</li>
    </ul>
  </section>

  <section id="recursos">
    <h2>Recursos</h2>
    <ul>
      <li><a href="https://www.python.org">Site oficial</a></li>
    </ul>
  </section>

  <section id="sobre">
    <h2>Sobre o Projeto</h2>
    <p>Site criado para ensinar HTML e CSS com Python como tema.</p>
  </section>
</main>
```

---

## 🧱 Etapa 4: Rodapé

```html
<footer>
  <p>&copy; 2025 - Criado por estudantes.</p>
</footer>
```

---

✅ **Resultado esperado**: Um site dividido em seções, com navegação funcional.
