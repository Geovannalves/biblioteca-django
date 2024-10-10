# Exercício - Unidade 6 da Trilha de Backend
**Dupla**: Geovanna Alves dos Santos e Edenilson Fabiano da Silva Souza

---

## Observação:

Na URL `/livros/`, já é possível realizar tanto a requisição **POST** para criar um livro quanto a **GET** para listar os livros, utilizando a view `LivroList`, que é uma **ListCreateAPIView**. 

Portanto, não há necessidade de criar uma nova rota como `/livros/create/`, visto que a view `LivroList` já implementa as funcionalidades de listagem e criação de livros em uma única URL.

A mesma lógica aplica-se para as URLs `/categoria/` e `/autor/`, onde as views `CategoriaList` e `AutorList`, ambas sendo **ListCreateAPIView**, também suportam as requisições **GET** e **POST** nas respectivas rotas.
