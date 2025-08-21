# 📄 Gerador de Arquivo TXT para SIMPROQUI - PF

Este projeto tem como objetivo **gerar arquivos TXT** no formato exigido pelo **SIMPROQUI da Polícia Federal**, a partir de uma planilha Excel (`GERARTXT.xlsx`).  
A ferramenta foi desenvolvida em **Python (Jupyter Notebook)** e automatiza o processo de conversão, garantindo conformidade e reduzindo erros manuais.

---

## 🚀 Funcionalidades
- Leitura da planilha de entrada (`GERARTXT.xlsx`).
- Validação dos dados conforme regras do SIMPROQUI.
- Geração automática do arquivo `.txt` formatado.
- Exportação rápida e segura.

---

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Jupyter Notebook
- Pandas
- OpenPyXL

---

## 📂 Estrutura do Projeto

📦 Gerador-de-Arquivo-TXT-para-SIMPROQUI-PF
┣ 📜 GERARTXT.xlsx # Modelo de entrada (planilha base)
┣ 📜 Geração de TXT.ipynb # Notebook principal
┣ 📜 README.md # Documentação do projeto


---

## ⚙️ Pré-requisitos
Antes de rodar o projeto, você precisa ter instalado:
- [Python 3.x](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)
- Bibliotecas listadas no `requirements.txt` (ou instale manualmente com pip)

### Instalação das dependências:
```bash
pip install pandas openpyxl

▶️ Como Usar

Clone o repositório:

git clone https://github.com/AlandersonBatista/Gerador-de-Arquivo-TXT-para-SIMPROQUI-PF.git


Abra o Jupyter Notebook:

jupyter notebook


Execute o arquivo Geração de TXT.ipynb.

Carregue a planilha GERARTXT.xlsx com seus dados.

O sistema irá gerar o arquivo .txt pronto para envio ao SIMPROQUI.

📌 Exemplo de Entrada (Excel)
<img width="1919" height="546" alt="image" src="https://github.com/user-attachments/assets/7127a4e3-a28f-4b1e-b8c6-1b60ac00fb1b" />



📌 Exemplo de Saída (TXT)

<img width="937" height="588" alt="image" src="https://github.com/user-attachments/assets/38c6222d-2c67-413f-83e5-67d9e83e4d21" />


🤝 Contribuição

Contribuições são bem-vindas!
Para sugerir melhorias:

Faça um fork do projeto

Crie uma branch (git checkout -b minha-feature)

Commit suas alterações (git commit -m 'Adicionei nova feature')

Faça um push (git push origin minha-feature)

Abra um Pull Request

📜 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar e modificar conforme necessário.

✍️ Desenvolvido por Alanderson Batista


👉 Esse modelo já deixa seu repositório bem organizado e profissional.  

Quer que eu já monte também um **requirements.txt** com as bibliotecas básicas (`pandas`, `openpyxl`) para deixar o setup automático?
