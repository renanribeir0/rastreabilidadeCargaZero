# Teste de Rastreabilidade de Carga Zero - Página Web

## Descrição
Este documento descreve o procedimento para realizar um teste de rastreabilidade de carga zero em uma página da web hospedada em http://localhost:3001/iniciativas usando o Postman. O objetivo deste teste é verificar o acesso à página sem carga adicional e garantir que ela funcione corretamente em condições normais.

### Pré-condições
1. O Postman está instalado no sistema.
2. O servidor da página web está em execução em http://localhost:3001/iniciativas.

### Procedimento de Teste
1. Abra o Postman.
2. Crie uma nova coleção de testes (se necessário).
3. Crie uma nova solicitação dentro da coleção e nomeie-a "Acesso à Página Web".
4. Configure a solicitação para usar o método GET.
5. Configure a URL da solicitação para http://localhost:3001/iniciativas.
6. Execute a solicitação.

#### Captura de Tela
<img width="638" alt="image" src="https://github.com/renanribeir0/rastreabilidadeCargaZero/assets/110369271/90e31881-3a7e-402e-8718-7f8021bbc30e">


#### Tempo de Execução
O tempo total de execução da solicitação foi de 150 ms.

### Pós-condição
1. Verifique o resultado da solicitação.

### Resultados Esperados
- Status HTTP 200 (OK).
- A página web é carregada sem erros visíveis.

### Resultados Obtidos
- **Status HTTP:** 200
- **Observações:** A página foi carregada corretamente sem erros visíveis. Nenhuma anomalia foi encontrada durante o teste.

## Conclusão
O teste de rastreabilidade de carga zero foi concluído com sucesso. A página web em http://localhost:3001/iniciativas foi acessada com êxito, com um tempo de execução de 1561 ms, e nenhum erro visível foi encontrado.
