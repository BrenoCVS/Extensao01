---
marp: true
theme: default
paginate: true
backgroundColor: #fdf6e3
style: |
  section {
    font-size: 28px;
  }
  h1, h2, h3 {
    color: darkblue;
  }
  .code-asm {
    background-color: #2d2d2d;
    color: #f8f8f2;
    padding: 20px;
    border-radius: 10px;
    font-family: 'Fira Code', monospace;
    font-size: 22px;
    min-height: 320px;
    overflow:auto;
  }
  .code-python {
    background-color: #2d2d2d;
    color: #f8f8f2;
    padding: 15px;
    border-radius: 10px;
    font-family: 'Fira Code', monospace;
    font-size: 24px;
    min-height: 50px;
    overflow:auto;
  }


---
# Apresentação
Breno Silva  
19 anos  
Futuro Bacharel em Sistemas da Informação  
Corinthiano 🖤

---
<!-- _class: center -->
# Programação: A Linguagem do Futuro

---

# O que é Programar?
Programar é dar **instruções para o computador**.  
O computador não entende português, precisa de uma **linguagem de programação**.

É como seguir uma **receita de bolo**: passo a passo até o resultado final.

---

# Onde a Programação Está?
- **Celulares**: WhatsApp, TikTok, Instagram  
- **Jogos**: Minecraft, Roblox, Free Fire  
- **Sites**: YouTube, Google  
- **Robôs e carros inteligentes**  
- Até na **geladeira** e na **TV**  

---

# Linguagens de Programação
Existem várias linguagens diferentes:  
- **Python**  
- **Java**  
- **C++**  
- **JavaScript**  



---

# Alto Nível x Baixo Nível
As linguagens podem ser divididas em dois grupos:  

- **Baixo nível** → próximas da máquina (difíceis para humanos).  
- **Alto nível** → próximas da forma como pensamos (fáceis para humanos).  

👉 É como se fosse um idioma:  
- Baixo nível = falar a língua da máquina.  
- Alto nível = falar a nossa língua, com um tradutor para a máquina entender.


---
# Exemplo Assembly (baixo nível)
<div class="code-asm">
section .data<br>
&nbsp;&nbsp;&nbsp;&nbsp;msg db 'Hello, World!',0Ah<br><br>
section .text<br>
&nbsp;&nbsp;&nbsp;&nbsp;global _start<br><br>
_start:<br>
&nbsp;&nbsp;&nbsp;&nbsp;mov edx, 14<br>
&nbsp;&nbsp;&nbsp;&nbsp;mov ecx, msg<br>
&nbsp;&nbsp;&nbsp;&nbsp;mov ebx, 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;mov eax, 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;int 0x80<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;mov eax, 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;int 0x80
</div>

---

# Exemplo Python (alto nível)
<div class="code-python">
print("Hello, World!")
</div>




---

# Pensamento Lógico
Mais importante que a linguagem é a **lógica**.  
- Resolver problemas passo a passo.  
- Exemplo:  
  - Personagem anda 3 passos.  
  - Depois abre a porta.  
  - Depois entra na sala.  

Sem lógica, não existe programação.  


---

# Programação e o Futuro
Hoje tudo depende de código:  
- Carros autônomos  
- Inteligência Artificial  
- Bancos digitais  

Profissões do futuro vão precisar de programação.  
Programar é **criar** e também **entender como o mundo digital funciona**.  

---

# Segurança e Responsabilidade
- Com programação podemos criar coisas incríveis.  
- Mas também existem riscos (vírus, hackers).  
- Por isso, é preciso usar com **responsabilidade**.  
 

---

# Dúvidas / Perguntas?

---
 

### "Todo mundo deveria aprender a programar, porque isso ensina a pensar."  
— Steve Jobs
