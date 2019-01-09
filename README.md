# AWS-Learning

Estudo da AWS

# Udemy AWS

Link do Curso: [AWS Essentials](https://www.udemy.com/aws-essentials)

Site de Suporte: [Projeto Omega](https://www.lucidchart.com/documents/view/703f6119-4838-4bbb-bc7e-be2fb75e89e5/0) 

## S3 (Simple Storange Service)

S3 (Simple Storange Service) é um storange com acesso a dado de alta escalabilidade, rápido, infraestrutura de armazenamento barato. Espaço para armazenamento praticamente ilimitado.

Ao criar um S3 é criado um *folder root* chamado  *Bucket* , subfolders criados dentro do bucket são considerados como folders.

![Components & Struture S3](_images/S3_Structure_Bucket.png "Estrutura do S3")

Os Buckets são criados em regiões específicas, como boa práticas sleecione a região fisica mais próxima para reduzir a latência ou em uma região perto do seu consumidor.

O Free Tier fornece 5GB, 20000 Get Request e 2000 Put Request e e 15GB de tranferência de dados para cada mes por um ano. Caso seja necessário comprar mais recurso acesse o link abaixo.

[Price S3 Bucket](https://aws.amazon.com/s3/pricing/)


## Navegando no Bucket S3

Nomeclatura dos Buckets segue um padrão
+ O nome do Bucket deve ser único por toda AWS;
+ O nome tem que ter entre 3 a 63 caractéres;
+ Os nomes dó podem conter letras minusculas, números e hífens;
+ Não pode ter um nome similar a endereço de ip ex.: 198.175.5.4.

