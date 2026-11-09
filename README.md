# Projeto de Redes Industriais — Semana 9

## Conteúdo
- `rede.drawio`: diagrama editável da arquitetura proposta.
- `rede.pdf`: versão de leitura do diagrama.
- `enderecamento.xlsx`: nós, endereçamento, matriz de alternativas e casos de teste.
- `evidencias/`: roteiro e formulários de evidência para condição normal e falhas.

## Escopo da arquitetura
Projeto didático de uma rede de automação com três zonas:
1. **Zona A — Controle:** CLP-01 e IHM-01.
2. **Zona B — Supervisão e integração:** SCADA-01, switches industriais e GW-RTU.
3. **Zona C — Campo/legado:** LEG-01 e LEG-02 em Modbus RTU sobre RS-485.

A comunicação Ethernet utiliza Modbus TCP. A integração dos equipamentos legados ocorre pelo gateway Ethernet/RS-485. A proposta de disponibilidade acrescenta caminho Ethernet redundante com MRP, desde que os switches selecionados suportem esse protocolo e estejam configurados de forma compatível.

## Endereçamento proposto
A planilha contém os endereços de exemplo reservados para este projeto didático. Antes da implantação, confirme se as faixas não colidem com a rede real da instituição/empresa.

## Como abrir
- Abra `rede.drawio` em https://app.diagrams.net/ ou no diagrams.net para desktop.
- Consulte `rede.pdf` para leitura.
- Abra `enderecamento.xlsx` no Excel ou LibreOffice Calc.


