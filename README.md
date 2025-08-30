# Desafio de Projeto: Documentando a Criação de um Banco de Dados no Azure

Este é o meu projeto para o desafio da DIO, onde o objetivo era criar um Banco de Dados SQL no Azure.

### Nota Importante:
Eu não consegui criar o banco de dados na prática. Minha conta do Azure é antiga e os créditos de teste já tinham acabado. Tentei criar uma conta nova, mas deu erro. Por isso, este documento é um resumo de como o processo *deveria ser feito*, com base no que aprendi nas aulas e na documentação da Microsoft.

---

### Passo a Passo (Teórico) para Criar o Banco de Dados

1.  **Achar o Serviço:** Primeiro, eu entraria no Portal do Azure e procuraria por "Instância Gerenciada de SQL".

2.  **Preencher os Dados:** Depois, eu preencheria as informações básicas que o Azure pede, como o nome do banco de dados, o usuário/senha do administrador e em qual região do mundo eu quero que ele fique.

3.  **Configurar a Rede:** Esta parte é para definir como o banco de dados vai se conectar com a internet e outras coisas de segurança.

4.  **Revisar e Criar:** No final, o Azure mostra um resumo de tudo que foi escolhido. Se estivesse tudo OK, era só clicar em "Criar".

---

### O que Eu Aprendi com Isso

Mesmo sendo um exercício teórico, deu pra conectar com as aulas:

* **Tipos de Serviço em Nuvem (IaaS, PaaS, SaaS):**
    No começo do curso, eu aprendi a criar **Máquinas Virtuais**, que são **IaaS** (você gerencia quase tudo). Já este Banco de Dados SQL é um serviço **PaaS**, onde a Microsoft cuida da parte chata (servidor, sistema operacional) e eu só me preocupo em usar o banco. É um modelo bem mais prático para quem desenvolve.

* **Responsabilidade de Cada Um:**
    Com um serviço PaaS, a Microsoft garante que o banco de dados fique no ar e seguro (responsabilidade dela). A minha responsabilidade seria cuidar dos dados que eu coloco lá e definir quem pode acessá-los.

* **Custos (CapEx vs. OpEx):**
    Usar um serviço desses é um exemplo de **OpEx** (gasto operacional), porque eu pagaria uma "mensalidade" pelo uso. É diferente de **CapEx**, que seria o gasto gigante de comprar um servidor físico.

### Conclusão

Apesar de não conseguir fazer na prática, o desafio me ajudou a entender o processo e a conectar a teoria com um caso de uso real.
