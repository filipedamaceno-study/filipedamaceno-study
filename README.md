# Olá, este é meu github de estudos!

- ☕: Estudante de Análise e Desenvolvimento de Sistemas no CEUB-DF
- 💻: Estou buscando estágio enquanto me aprimoro com diversos cursos de programação além da faculdade.
- 🔗: https://www.linkedin.com/in/filipedamaceno/


```python
class Persona:
    # Construtor da classe
    def __init__(self, nome, idade, languages, areas, hobbies):
        self.nome = nome
        self.idade = idade
        self.languages = languages
        self.areas = areas
        self.hobbies = hobbies
        
    def informacoes(self) -> object:
        print("Nome:", self.nome)
        print("Idade:", self.idade)
        print("Languages:", self.languages)
        print("Hobbies:", self.hobbies)
    
eu = Persona("Filipe Augusto",
             "29",
             ["Java","Python", "Javascript"],
             ["Backend","Análise de dados",],
             ["Videogame", "Anime", "Mangá", "Tokusatsu", "Música"])


```
  
