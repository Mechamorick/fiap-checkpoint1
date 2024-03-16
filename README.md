# fiap-checkpoint1

Aplicação Java com container para exemplo

Pré-requisitos
Java 17+
Docker
Acesso a internet
Acesso ao Docker Hub
Clone
git clone https://github.com/Mechamorick/fiap-checkpoint1
Instruções
Antes de executar esta aplicação, é preciso obter a imagem do Docker Hub. Para isso, utilize o comando a seguir:

docker pull jotamilanezi/fiap-checkpoint1


Isso fará com que a imagem necessária para a execução e aplicação seja aplicada em seu ambiente local


Para executar com perfil "dev", utilize o seguinte comando:

docker run -d -p 8080:8080 -e PROFILE=dev Mechamorick/fiap-checkpoint1

Para executar com perfil "stg", utilize o seguinte comando:

docker run -d -p 8080:8080 -e PROFILE=stg Mechamorick/fiap-checkpoint1

Para executar com perfil "prd", utilize o seguinte comando:

docker run -d -p 8080:8080 -e PROFILE=prd Mechamorick/fiap-checkpoint1
Navegação / Acesso a aplicação
Após o processo de duplicação e execução do mesmo você poderá acessa-lo utilizando o seguinte endereço

http://localhost:8080

e também é necessário se certificar de que você tenha o Docker instalado e em execução antes de executar os comandos

Contatos
João Pedro Bueno Milanezi rm88322 - jpbmila2@gmail.com
Henrique dos Santos Sousa Romero rm88273 - rick_romero25@hotmail.com
