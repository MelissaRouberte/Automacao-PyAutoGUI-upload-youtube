# 🎥 YouTube Upload Automation

Automação desenvolvida em Python utilizando a biblioteca **PyAutoGUI** para realizar o processo de upload de vídeos no YouTube através da interface gráfica do navegador.

> ⚠️ Este projeto foi desenvolvido **exclusivamente para fins educacionais**, com o objetivo de estudar automação de interfaces utilizando Python e PyAutoGUI.

---

## 🚀 Funcionalidades

O programa apresenta um menu simples no terminal:

```
1 - Fazer upload de vídeo
2 - Encerrar programa
```

Ao selecionar a opção **1**, o usuário informa:

- 📹 Nome do arquivo do vídeo
- 📝 Se deseja adicionar uma descrição
- 🖼️ Se deseja adicionar uma thumbnail

Dependendo das respostas, a automação realiza todo o processo de upload de forma automática.

---

## 📌 Fluxo da automação

1. Abre o YouTube Studio
2. Seleciona o vídeo informado
3. Adiciona a descrição (caso desejado)
4. Adiciona a thumbnail (caso desejada)
5. Configura o vídeo como:
   - ✅ Público
   - ✅ Não é conteúdo infantil
   - ✅ Comentários habilitados
6. Finaliza o upload automaticamente.

---

## ⚠️ Limitações

Atualmente o projeto foi desenvolvido apenas para uploads com as seguintes configurações:

- Vídeos Públicos
- Conteúdo não infantil
- Comentários habilitados

Não possui suporte para:

- Vídeos privados
- Vídeos não listados
- Agendamento de publicação
- Alteração de configurações avançadas

---

## 🛠 Tecnologias

- Python 3
- PyAutoGUI
- Time
- OS

---

## ⚠️ Aviso

Este projeto foi criado **exclusivamente para fins de estudo** sobre automação de interfaces.

O YouTube pode alterar sua interface a qualquer momento, o que pode fazer a automação deixar de funcionar.

Além disso, automações podem estar sujeitas aos **Termos de Serviço do YouTube**. Utilize este projeto com responsabilidade e apenas para aprendizado.

---

## 📚 Objetivo

Este projeto teve como objetivo praticar:

- Automação de interface gráfica
- Manipulação de teclado e mouse
- Organização de código em Python
- Estruturas condicionais
- Loops
- Tratamento de entrada do usuário

---

## 📷 Exemplo

```
1 - Fazer Upload

Nome do vídeo:
video.mp4

Deseja adicionar descrição? (S/N)
S

Digite a descrição:
Meu primeiro vídeo

Deseja adicionar thumbnail? (S/N)
S

Digite o nome da thumbnail:
thumb.png

Iniciando automação...
```

---

## 👩‍💻 Desenvolvido por

Melissa Rouberte
