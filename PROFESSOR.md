Instruções para o Professor
===========================

Para utilizar esse projeto:

1. Crie um novo repositório a partir do template.
2. Faça um clone local do repositório.
3. Edite o arquivo `.exercicio_zero/project` com os dados do exercício.
4. Execute o _script_ de configuração `.exercicio_zero/config`.
5. Remova os arquivos de exemplo.
    ```nohl
    git rm features/listas.feature features/steps/listas.py src/zero.py
    ```
5. Salve as alterações no repositório e envie de volta ao Github.
    * Sugestão de mensagem: "Configuração do exercício"
        ```nohl
        git add -u
        git commit -m "Configuração do exercício."
        git push origin main
        ```
6. Altere os arquivos do projeto de acordo com o seu exercício.
7. Adicione as alterações ao repositório e envie o trabalho para o Github.
8. Em `Settings > Rules > Rulesets` abra o menu `New ruleset` e selecione
   `Import a ruleset`, selecione o arquivo
   `.exercicio_zero/rulesets/auto_eval.json`, revise as regras e clique em
   `Create`.

Com esses passos, quando um aluno criar um _pull request_ contra o
repositório, a avaliação automática será executada.

No primeiro _pull request_ de cadaaluno, é necessário que o _workflow_
seja autorizado a executar.
