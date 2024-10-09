==============================================================
Sonarqube
==============================================================
1) Iniciando com Sonarqube
https://www.sonarsource.com/products/sonarqube/
2) Conceitos principais
3) Instalando primeiro projeto 

token criado
goproject: sqp_a13318f7e4d36d3770a1d6cf228436e8a4b7ec55

executando o sonar-scanner
sonar-scanner \
  -Dsonar.projectKey=go-project \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_a13318f7e4d36d3770a1d6cf228436e8a4b7ec55
  
4) Trabalhando com cobertura de código
5) Cobrindo código Javascript
6) Preparando ambiente para SonarCloud
[sonarcloud.io](https://www.sonarsource.com/products/sonarcloud/)

7) Executando SonarCloud
8) Trocando de Quality Gate
