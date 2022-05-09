# Projeto Final - Automação e Orquestração Pucminas

## Alunos

- Fábio Gomes
- Ricardo Ferraz
- Marciano Souza

## Sonar Cloud

Links para o ambiente do [Sonar Cloud](https://sonarcloud.io/project/configuration?id=ffabiosantosgcm_devops-F-R-M)

### Requisitos

```

1. Devem ser implementados pelo menos os seguintes jobs: build e deploy. 

2. O job ‘deploy’ deve contemplar steps para publicação em um provedor de serviço em nuvem com o serviço escolhido pelo grupo, por exemplo, Amazon S3 e/ou Amazon EC2.

3. Deverá ser implementado pelo menos um exemplo de execução de jobs em paralelo.

4. Deverá ser implementado pelo menos um exemplo de uso dos recursos cache e/ou artefato.

5. Deverá ser implementado pelo menos um exemplo de custom action, ou seja, criada e utilizada especificamente no projeto.

6. As credenciais deverão ser obtidas por meio de mecanismos providos pela solução de pipeline (ex.: secrets).

7. Os componentes da infraestrutura do servidor em nuvem deverão ser provisionados por meio do uso de soluções de automação (ex.: Ansible, Terraform, CloudFormation etc.)

8. O pipeline deverá ser executado a partir de um push com a mensagem de commit contendo o texto [pipeline], ou seja, um trigger condicional.

9. O deploy em produção deverá ser configurado para ser feito apenas com aprovação manual. A implementação pode ser feita por meio do mecanismo ‘environment’ do GitHub.
```
![diagrama](https://github.com/ffabiosantosgcm/devops-F-R-M/blob/6ce763c226c92dff531cf52f24722161db4d03f5/pipeline.PNG)
