# Escopo do Projeto MESAFARTAI

## 1. Problema de negócio

O MESAFARTAI é um projeto que busca utilizar tecnologia e inteligência artificial para auxiliar na logística de doações de alimentos. A proposta é facilitar a comunicação entre doadores e organizações não governamentais (ONGs), ajudando a conectar a oferta de alimentos às organizações que precisam recebê-los e reduzindo dificuldades no processo de distribuição.

O projeto está alinhado à **ODS 2 da ONU — Fome Zero e Agricultura Sustentável**.

## 2. Público-alvo

O sistema possui dois públicos principais:

* **Doadores:** pessoas, supermercados, restaurantes e outros estabelecimentos que desejam disponibilizar alimentos para doação.
* **ONGs:** organizações que recebem doações de alimentos para atender pessoas em situação de vulnerabilidade alimentar.

## 3. Intenções tratadas pelo chat

O chat conversacional deverá reconhecer as seguintes intenções:

* `cadastrar_doacao`: identificar quando um doador deseja cadastrar uma doação de alimentos.
* `solicitar_alimentos`: identificar quando uma ONG deseja solicitar alimentos.
* `consultar_status`: identificar quando o usuário deseja consultar o status de uma doação ou solicitação.
* `fora_de_escopo`: identificar mensagens que não correspondem às funcionalidades previstas para o sistema.

O sistema também prevê um mecanismo de fallback para responder de forma amigável quando uma mensagem for ambígua ou não atingir o nível de confiança necessário para a classificação.

## 4. Dados coletados pelo chat

De acordo com as informações previstas no projeto, o sistema poderá trabalhar com os seguintes dados:

* **Dados do usuário:** nome, tipo de perfil (DOADOR ou ONG), CEP e telefone.
* **Dados de localização:** latitude e longitude, para auxiliar na identificação da proximidade entre doadores e ONGs.
* **Dados da doação:** descrição do alimento, quantidade em quilogramas e data de validade.
* **Dados do atendimento logístico:** identificação da doação, ONG relacionada, distância calculada e data do registro do match.

Esses dados serão utilizados para apoiar o cadastro, a consulta e a organização logística das doações de alimentos.

## 5. Prompt utilizado para criação do logotipo

[Inserir aqui o prompt exato utilizado para gerar o logotipo do MESAFARTAI.]

