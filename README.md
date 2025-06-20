# 🤟 Reconhecimento de Gestos em Libras com Visão Computacional

Projeto final da disciplina **Sistemas Multimídias**, desenvolvido por **José Henrique Lopes Motta**.  
Este sistema realiza o reconhecimento de gestos do alfabeto da Língua Brasileira de Sinais (LIBRAS) utilizando **OpenCV**, **MediaPipe** e um modelo de classificação treinado em **TensorFlow/Keras**.

---

## 📸 Demonstração

![Demonstração do sistema](CAMINHO_PARA_SUA_IMAGEM.gif)

---

## 🚀 Tecnologias Utilizadas

- **Python** 3.8.0
- **TensorFlow** 2.8.0
- **MediaPipe** 0.10.5
- **OpenCV-Python** 4.6.0.66
- **Protobuf** 3.19.4
- Modelo `.h5` treinado com [Teachable Machine](https://teachablemachine.withgoogle.com/)

---

## ⚙️ Requisitos

Certifique-se de estar utilizando **Python 3.8.0** ou compatível com TensorFlow 2.8.0.  
Use um ambiente virtual para isolar as dependências.

### Instalação das dependências:

```bash
pip install -r requirements.txt
```

### Conteúdo do `requirements.txt`

```txt
tensorflow==2.8.0
mediapipe==0.10.5
opencv-python==4.6.0.66
protobuf==3.19.4
```

> ⚠️ Atenção: Python 3.11 ou superior pode causar incompatibilidades com TensorFlow 2.8.0 e MediaPipe.

---

## ▶️ Como Rodar o Projeto

Clone o repositório:

```bash
git clone https://github.com/dev-josehenrique/ReconhecimentoLibras.git
cd ReconhecimentoLibras
```

Crie e ative o ambiente virtual:

```bash
python -m venv venv
venv\Scripts\activate    # Windows
source venv/bin/activate  # Linux / Mac
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute o programa:

```bash
python main.py
```

> Pressione **'q'** para encerrar a execução.

---

## 📂 Estrutura do Projeto

```
ReconhecimentoLibras/
│
├── main.py              # Código principal do sistema
├── keras_model.h5       # Modelo de reconhecimento treinado
├── requirements.txt     # Lista de dependências do projeto
└── README.md            # Documentação do projeto
```

---

## 📺 Vídeo e Imagens

Adicione aqui um vídeo ou imagens do sistema em funcionamento.

- [ ] Inserir link do vídeo demonstrativo
- [ ] Inserir capturas de tela (.png/.gif)

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 👨‍💻 Autor

**José Henrique Lopes Motta**  
GitHub: [@dev-josehenrique](https://github.com/dev-josehenrique)

---

## 🙏 Agradecimentos

- [Google Teachable Machine](https://teachablemachine.withgoogle.com/)
- [MediaPipe Hands API](https://google.github.io/mediapipe/solutions/hands.html)
- Comunidade Python e Visão Computacional
