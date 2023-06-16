---
template: overrides/main.html
title: Pagina
---

# A

## Pagina

## Sistema

### TISS <small>recomendado</small> { #tiss data-toc-label="TESTE" }

Material utilizado para absorver a documentação sobre teste:

=== "Observação"

    ``` sh
    exemplo
    ```

=== "Observação 2 <small>detalhes</small>"

    ``` sh
    Exemplos do que pode ser inserido =="8.*" #(1)!
    ```

    1.  Aqui por exemplo podemos colocar formas de uso[^1] ou outras dicas de consumo ou links tb: 
        
        
        ```
        teste pra copiar
        ```

        Podemos colocar um link pra copiar também:

        ```
        https://podemoscolocarumlinkaqui.com.br
        ```

  [^1]:
    Lembra que colocamos como "Formas de uso", um topico que podemos colocar aqui na parte inferior pra descrever outro ponto.


### Guias de Internação

Guia de [`Solicitação de Internação`][Solicitacaodelink] - É o formulário padrão a ser utilizado para a solicitação, autorização ou negativa...

  [Solicitacaodelink]: #whith-Solicitacaodelink



Podemos tambem inserir listas para outras paginas:

- [Item-lista-1]
- [Item-lista-2]

  
  [item-lista-1]: https://beacons.ai/wuldson
  [item-lista-2]: https://github.com/wuldson-franco/Mkdocs_Markdown

??? question "podemos elencar topicos ou questões levantadas por cor, por exemplo:"

    Esse topico pode ser distinguido dos outros dando uma maior ênfase ou algum tipo de alerta para uso de calculo especifico:

    ``` Dockerfile
    FROM Tarefa 02 - Dropar os Índices da Tabela Traders_Warehouse - D_Produto_SCD_Mixed
    IF EXISTS (SELECT * FROM dbo.sysindexes WHERE NAME = 'IX_PRODUTO_KEY')
      DROP INDEX D_PRODUTO_SCD_MIXED.IX_PRODUTO_KEY
    IF EXISTS (SELECT * FROM dbo.sysindexes WHERE NAME = 'IX_PRODUTO_ID')
    RUN pip install ...
    ```
    

!!! info ":material-apple: Ou Alertas com icones :fontawesome-brands-raspberry-pi: "

    Criação de alerta para o usuário não deixar passar nada despercebido no momento do consumo.

 
  [third-party image]: https://github.com/afritzler/mkdocs-material



