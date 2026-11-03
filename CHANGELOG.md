# Changelog

Formulário de Relatório de Vistoria com Parecer de Fiscalização (antes: Termo de Aceite de Obra de Expansão) · SMOB/DIIP · Contrato nº 208/2025.

## 2.1 – 03/11/2026

### Removido
- Campos opcionais da versão 2.0 (ofício de aprovação do projeto, carta da concessionária, ART, data de conclusão, data de energização e placa de obra): dificultavam o preenchimento rotineiro.

## 2.0 – 01/11/2026

### Alterado
- O documento deixa de ser "Termo de Aceite de Obra de Expansão" e passa a ser **Relatório de Vistoria com Parecer de Fiscalização**. O Termo de Aceite é ato do Verificador Independente (Caderno de Encargos, item 16.1.12); a Prefeitura registra a vistoria e emite parecer, sem aceitar a obra.
- Decisão (aceitar / aceitar com ressalvas / não aceitar) substituída por parecer: conforme o projeto aprovado, com pendências ou em desconformidade.
- Disposições finais reescritas: o relatório não substitui o Termo de Aceite da OPUS, não exclui a responsabilidade da concessionária e é encaminhado por ofício à concessionária, com cópia ao Verificador Independente.
- "Vistoria de recebimento" passa a "Vistoria em campo"; arquivo gerado agora se chama `Relatorio_de_Vistoria_...pdf`.

### Adicionado
- Campos opcionais na identificação da obra, que só aparecem no PDF quando preenchidos: ofício de aprovação do projeto, carta da concessionária, ART de execução (CREA-PR), comunicação de conclusão da obra (Anexo 4, item 7.2.4), data da energização e placa de obra no padrão do Município.

### Removido
- Condicionamento da liberação de valores ao saneamento das pendências e a frase de que a obra aceita passa a integrar a rede municipal.

## 1.3 – 30/10/2026

### Adicionado
- Aviso em vermelho ao escolher uma obra com pontos a conferir. O aviso aparece só no formulário, não entra no PDF:
  - Bosque Guarani: 206 pontos no ofício, 234 no painel.
  - Playground Winkert: 1 ponto no ofício (1 poste com 3 luminárias), 3 no painel.
  - Fiorino Brol: 208 pontos no ofício, 209 no painel.
  - João Paulo II: verificar se os 44 pontos são adicionais (Cota Expansão) ou modernização.
  - Campo CRG14 e Campo/Três Bandeiras: os ofícios 7456 e 9201 só pediram estudo de viabilidade, sem aprovação de orçamento.

### Alterado
- Valor unitário da Av. Fiorino Brol preenchido: R$ 5.174,11, conforme a Carta 020/2026.

## 1.2 – 30/10/2026

### Adicionado
- Menu "Obras com orçamento aprovado", ao lado de "Carregar exemplo", com as 19 obras autorizadas (energizadas, em execução e autorizadas).
- Ao escolher uma obra, o termo é pré-preenchido com logradouro, bairro, serviços (cota, quantidade autorizada e valor unitário) e, quando conhecido, o responsável técnico. O que não consta nos ofícios fica em branco.
- Número, ano e data do termo são mantidos ao trocar de obra. Quantidades executadas, vistoria, pendências e decisão ficam para o fiscal.
- Dados dos ofícios SMOB/DIIP cruzados com o painel obras.ipfoz.com.br; onde há divergência, vale o ofício.

## 1.1 – 29/10/2026

### Alterado
- Identificação da obra no PDF reduzida a três linhas: obra/logradouro, bairro e responsável técnico do projeto executivo.
- Vistoria de recebimento reduzida de 14 para 9 itens; a numeração é refeita automaticamente.

### Adicionado
- Caixa de seleção para o Eng. Higor dos Santos Alves (CREA BA-3000150337/D) no campo de responsável técnico. Marcar preenche o campo; desmarcar limpa.

### Removido
- Campos de identificação: tipo de ponto/Cota Expansão, ofício de solicitação, carta da concessionária e data, ofício de aceite do orçamento e data, folha/data do projeto e data da vistoria.
- Itens da vistoria: iluminância e uniformidade (ABNT NBR 5101), pontos acendendo e apagando, pontos cadastrados e georreferenciados, local limpo e recomposto, segurança da execução e sinalização de obra.

## 1.0 – 28/10/2026

- Versão inicial: formulário em página única que preenche o termo e gera o PDF com o timbrado da Prefeitura, direto no navegador.
