# AVA - Assistente-Virtual-Academica
AVA e um projeto de assistente virtual em Python voltado para auxiliar os calouros da faculdade com informaçoes sobre seus cursos, como PPCs (Projetos Pedagogicos de Cursos), Matrizes curriculares, Disciplinas, Cargas horarias, entre outras perguntas.
## 🎯 Objetivo

Fornecer uma ferramenta acessível e inteligente que responda perguntas sobre a estrutura dos cursos da faculdade.

## 📚 Funcionalidades previstas

- Leitura de PPCs e matrizes curriculares
- Respostas para perguntas como:
  - "Qual a duração do curso?"
  - "Quantas horas de estágio obrigatório tem?"
  - "Quais disciplinas do 1º semestre?"
- Interface simples de uso (inicialmente no terminal)
- Estrutura para evolução futura com NLP e interface web

## 📁 Estrutura inicial

ava-assistente-virtual/ ├── README.md ├── requirements.txt ├── docs/ ← Documentos (PPCs, matrizes) ├── data/ ← Dados processados ├── src/ ← Código-fonte da AVA │ └── main.py └── tests/ ← Testes futuros

## 🚀 Como rodar

```bash
python3 src/main.py


---

### ✅ `src/main.py`

```python
def iniciar_ava():
    print("Olá! Eu sou a AVA - sua Assistente Virtual Acadêmica 🤖")
    print("Ainda estou em treinamento, mas em breve poderei te ajudar com dúvidas sobre seu curso!")

if __name__ == "__main__":
    iniciar_ava()
