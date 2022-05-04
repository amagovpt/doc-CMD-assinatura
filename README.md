
# Documentação técnica relativa ao Serviço de Assinatura da Chave Móvel Digital


## Introdução
O Serviço de Assinatura da Chave Móvel Digital permite que as aplicações integrem a funcionalidade de assinatura digital de documentos com a chave móvel digital nos seus fluxos.

Mais informação sobre a assinatura digital em https://www.autenticacao.gov.pt/web/guest/assinatura-digital/assinatura-digital-qualificada.

Este repositório contêm a documentação técnica relativamente ao Serviço de Assinatura da Chave Móvel Digital.

## Estrutura da documentação

* Na pasta **wsdl** encontra-se a descrição do web service em formato xml.
* Na pasta **guidelines** disponibiliza-se um documento que elenca as guidelines de integração necessárias para certificação da aplicação.
* Na pasta **logotipos** estão disponíveis os logotipos para utilização mediante consulta prévia.
* Na pasta **certificado** encontra-se o certificado que contém a chave pública a utilizar no processo de cifra dos elementos **número de telemóvel**, **PIN** e **OTP** conforme indicado no documento de especificação.
* [Documento de especificação dos serviços de assinatura (download pdf)](https://amagovpt.github.io/doc-CMD-assinatura/AMA&#32;-&#32;CCMovel&#32;Especificação&#32;de&#32;Serviços&#32;Assinatura.pdf).


## Certificação
Para a certificação deverão ser fornecidas as seguintes evidências:
* Relatório assinado digitalmente (com LTV) com evidências de cumprimento das guidelines de integração.
* Vídeo demonstrativo da solução.
* Criar 5 exemplares de documentos assinados, no ambiente pré-produtivo da entidade aderente e sobre estes fornecer:
	* Documento original.
	* Documento assinado digitalmente.
	* Resumo criptográfico.
	* Resumo criptográfico assinado.
	* ProcessID.
* Código fonte da componente que integra com o serviço de assinatura.

Após a receção das evidências, a Agência para a Modernização Administrativa (AMA IP)  precederá à avaliação.
No processo de avaliação está previsto: 
 - Possibilidade de requisição de acesso ao sistema, para validação das evidências e esclarecimento de dúvidas.
 - Possibilidade de solicitar:
	 -  Novo relatório corrigido.
	 - Evidências adicionais ou substituição das fornecidas.

**NOTA:** A configuração em ambiente produtivo é precedida da formalização de protocolo e de certificação.

## Contactos
Para questões, sugestões ou comentários envie um e-mail para eid@ama.pt.
