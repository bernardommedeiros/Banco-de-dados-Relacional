# Normalização

**através da extração de modelos relacionais, permite a implementação em bancos relacionais**

## Dependências

### Funcional

Uma tabela com duas colunas, temos x determina y.

  pk       determina    
numero_pedido -> prazo_entrega_produto

Só há necessidade de verificar se há dependência caso haja duas ou mais chaves primárias estrangeiras(caso dependa de apenas uma será parcialmente dependente), pois caso haja apenas uma há dependência total

- dependencia transitiva