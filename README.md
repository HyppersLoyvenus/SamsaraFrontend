# Gerenciamento Escolar Infantil

O sistema tem como objetivo principal automatizar e otimizar o controle de pagamentos, presenças e atividades dos alunos, substituindo o método manual atual baseado em cadernos.

## Objetivos Desta Etapa 

Dar continuidade ao projeto do semestre passando, realizando a criação do front-end em React + TypeScript consumindo as API REST desenvolvidas anteriormente.

Membros:
- Antuane Felipe - RA: 3124596
- Gabrielle Palma - RA: 6324589
- Karolina Mendes - RA: 6324304
- Vitória Nascimento - RA: 6324549

---

## Sumário

1. [Instalação & Execução](#instalacao-execucao)
2. [Pré-Compilador Vite](#compilador-vite)

## Instalação & Execução <a name="instalacao-execucao"></a>

1. Clonar o repositório & acessa-lo:
    
    ```sh
    git clone https://github.com/HyppersLoyvenus/SamsaraFrontend.git
    cd SamsaraFrontend
    ```

2. Subir a aplicação com Docker Compose:

   ```sh
   docker-compose up --build -d
   ```

- URLs:
  - **Frontend React:** http://localhost:5173
  - **Backend API:** http://localhost:3000/api
  - **View EJS Alunos:** http://localhost:3000/view/alunos
  - **View EJS Professores:** http://localhost:3000/view/professores

## Pré-Compilador Vite <a name="compilador-vite"></a>

```bash
cd FRONTEND
npm run build    # Gera build otimizado na pasta dist/
npm run preview  # Preview do build de produção
```
