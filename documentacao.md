# Documentação - Arquivos HTML para Etapas de E-mails Personalizados

## Visão Geral
Este pacote contém arquivos HTML para representar diferentes etapas de um fluxo de demandas em e-mails personalizados. Os arquivos foram projetados para manter um fluxo linear, deixando claro cada etapa do processo.

## Arquivos Incluídos
1. **template_base.html** - Template base com a estrutura comum para todos os e-mails
2. **em_analise.html** - E-mail para a etapa "Em Análise"
3. **em_desenvolvimento.html** - E-mail para a etapa "Em Desenvolvimento"
4. **em_revisao.html** - E-mail para a etapa "Em Revisão"
5. **concluido.html** - E-mail para a etapa "Concluído"

## Como Usar
Cada arquivo HTML representa uma etapa específica do processo de demanda. Você pode personalizar os seguintes elementos em cada arquivo:

### Elementos Personalizáveis
- Logo da empresa (substitua a URL do placeholder)
- Nome da empresa (substitua [NOME_EMPRESA] no rodapé)
- Informações da demanda:
  - Número da demanda (substitua #DEM-2025-0001)
  - Data de atualização
  - Nome do solicitante (substitua [NOME_SOLICITANTE])
  - Departamento (substitua [DEPARTAMENTO])
  - Prioridade (substitua [PRIORIDADE])
  - Descrição da demanda (substitua [DESCRIÇÃO_DEMANDA])
- URLs para links (Portal de Demandas, botões de ação, etc.)

### Personalização do Design
- Os estilos CSS estão incorporados em cada arquivo HTML
- Você pode modificar as cores, fontes e outros elementos visuais editando a seção `<style>` em cada arquivo
- Cores principais utilizadas:
  - Azul principal: #3498db
  - Verde (concluído): #2ecc71
  - Cinza (inativo): #e0e0e0
  - Texto escuro: #2c3e50
  - Texto claro: #7f8c8d

## Recursos
- **Design Responsivo**: Os e-mails se adaptam a diferentes tamanhos de tela
- **Indicadores Visuais**: Barra de progresso e ícones coloridos para indicar o status atual
- **Estrutura Consistente**: Layout padronizado em todas as etapas para facilitar a compreensão

## Compatibilidade
Os arquivos HTML foram testados e são compatíveis com os principais clientes de e-mail e navegadores web modernos.

## Personalização Avançada
Para personalização avançada, você pode:
1. Modificar o número de etapas na barra de progresso
2. Alterar as cores e estilos para corresponder à identidade visual da sua empresa
3. Adicionar ou remover seções de conteúdo conforme necessário

## Suporte
Para dúvidas ou suporte adicional, entre em contato com a equipe de desenvolvimento.
