# FullCycle | Teste para Tutor DevOps

## Tecnologias e requisitos
- Docker e Docker-compose
- Ambiente Cloud
- TerraForm
- Kubernetes
- Ferramentas de monitoramento

# O desafio

O projeto é dividido em etapas que você poderá escolher ir até o final ou até onde desejar. Através disso poderemos medir em que momento você está tecnicamente. O minimo necessário que esperamos é que a etapa 1 e 2 sejam entregues.

# O prazo

Você terá o prazo de uma semana a partir do momento em que o desafio é enviado. 

## Etapa 01

- Analisar a aplicação disponível neste repositório, verificar quais componentes você precisará provisionar;
- Criar um Dockerfile para esse projeto para conseguirmos subí-la localmente, dividindo em ambientes: DEV, TEST, PROD;
- Utilizar um docker-compose que sobe a API + banco de dados localmente, dividindo em ambientes: DEV, TEST, PROD;
- Uma pipeline de integração contínua para essa API utilizando tecnologias como Azure DevOps, TravisCI, Github Actions ou algum outro de sua preferência;
- Subir a aplicação em um cloud provider (provavelmente você terá que assinar uma conta free tier ou se aproveitar de limites gratuitos oferecidos por cloud providers);

## Etapa 2

- Utilizar Kubernetes, criando os manifestos para deploy do projeto;
- Criar um cluster de Kubernetes em algum cloud provider;
- Adaptar os comandos do seu Makefile para subir a aplicação na cloud e para ser testada localmente utilizando K8S (Minikube, Microk8s);

## Etapa 3

- Utilizando alguma solução de IaC, como Terraform para provisionar em um cloud provider;
- Adaptar a pipeline de CD para deployar no seu novo cluster;
- Realizar monitoramento do cluster Kubernetes, avaliando e definindo alertas que você julga importante;
- Criar rotina de monitoramento para a aplicação dentro do cluster de Kubernetes;
- Criar dashboard para apresentar o estado da aplicação e do cluster Kubernetes;
- Pensar em uma estratégia de deploy que fizesse rollout da aplicação de forma a diminuir a quantidade de possíveis erros de uma nova release;
