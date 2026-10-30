# PAP2027HouseView
Projeto PAP
# HouseView

**PAP 2027 – TGPSI, Escola Secundária de Vergílio Ferreira**

Aluno: André Andrade · Turma 12.º 13.ª · N.º 3

Professor orientador: Jorge Silva

## Descrição

Este projeto é uma aplicação web que combina dois conceitos: um sistema de comparação de imóveis e um simulador 3D de design de interiores.
O “HouseView” permite navegar, pesquisar e comparar casas, ler análises, definir um orçamento e escolher as opções mais adequadas. Por outro
lado, oferece um projeto 3D da cozinha ou de outro espaço interior que pode ser editado, equipado com mobiliário e decorado, dando ao cliente uma
visão geral de todas as opções e do custo de uma remodelação.
Trata-se de encontrar uma abordagem mais consciente na hora de tomar decisões: o custo não se limita apenas à compra, mas também às possíveis
melhorias e personalizações depois da compra. A aplicação utiliza uma base de dados com informações categorizadas para um processamento
simplificado e uma interface intuitiva acessível a qualquer pessoa.

## Objetivos
   
- Desenvolver uma plataforma intuitiva e responsiva para pesquisar e consultar imóveis.
- Permitir a pesquisa e comparação de imóveis através das suas principais características.
- Criar um sistema de utilizadores e de gestão de imóveis favoritos.
- Desenvolver o VIEW, um simulador 3D de interiores com opções de personalização.
- Integrar uma base de dados para armazenar e gerir as informações da aplicação.
- Aplicar os conhecimentos adquiridos no curso de TGPSI no desenvolvimento de uma aplicação funcional.

## Funcionalidades(núcleo mínimo (o que vou desenvolver primeiro) e extras (o que pretendo acrescentar se tiver tempo)
### Núcleo mínimo (obrigatório)

- [ ] Apresentação dos imóveis disponíveis na plataforma.
- [ ] Pesquisa e filtragem de imóveis por critérios como localização, preço e tipologia.
- [ ] Visualização dos detalhes de cada imóvel.
- [ ] Comparação das principais características de diferentes imóveis.
- [ ] Registo e autenticação de utilizadores.
- [ ] Adição e remoção de imóveis favoritos.
- [ ] Base de dados para guardar as informações dos imóveis e dos utilizadores.
- [ ] Interface responsiva, adaptada a computadores, tablets e telemóveis.

### Extras (se houver tempo)

- [ ] VIEW: simulador 3D de varias divisões de uma casa ou varias divisões diferentes(ainda por decidir).
- [ ] Personalização do espaço através da alteração de cores, materiais e mobiliário.
- [ ] Estimativa dos custos de renovação com base nas opções selecionadas.
- [ ] Comparação de diferentes configurações do mesmo espaço.
- [ ] Área pessoal para gerir imóveis favoritos e preferências.
- [ ] Possibilidade de guardar configurações criadas no simulador.

## Tecnologias

| Camada | Tecnologia |
| --- | --- |
| Interface | HTML5, CSS3, JavaScript, React e Bootstrap |
| Servidor | Node.js e Express |
| Base de dados | MySQL |
| Simulação 3D | Three.js e React Three Fiber |
| Ferramentas | Visual Studio Code, Git e GitHub |
| Design responsivo | Bootstrap e CSS |

## Base de dados (tabelas previstas)

- `utilizadores` — guarda os dados dos utilizadores e as respetivas credenciais de acesso.
- `imoveis` — guarda as informações dos imóveis disponíveis na plataforma.
- `favoritos` — relaciona os utilizadores com os imóveis que guardaram como favoritos.
- `imagens_imoveis` — guarda os caminhos dos ficheiros de imagem associados aos imóveis.
- `configuracoes_view` — guarda as configurações dos espaços criadas pelos utilizadores no simulador VIEW.
- `elementos_view` — guarda informações sobre os elementos disponíveis no simulador, como móveis e materiais.

## Planeamento

| Fase | Período | Estado |

| Análise e modelação da base de dados | Novembro | Por fazer |
| Desenvolvimento do núcleo mínimo | Dezembro – Março | Por fazer |
| Desenvolvimento dos extras e do simulador VIEW | Março – Abril | Por fazer |
| Testes e correções | Abril | Por fazer |
| Relatório e apresentação | Maio – Junho | Por fazer |

## Registo de progresso

- 30/10/2026 – Criação do repositório e preparação do README.md.(feito)
