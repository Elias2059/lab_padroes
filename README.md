#Documentação do Modulo de conexão

##Descrição 
Este projeto implementa um padrão de conexão segura com banco de dados, utilizando **Design Patterns** para evitar *hardcoding*

## O que foi feito
- [X] Criação do repositorio
- [X] Implementação de conexão
- [X] Resolução de conflito de Merge
- [X] Separação de configuração

## Exemplo de Uso
Abaixo, o codigo padrão utilizado pelo Arquiteto:

'''python 
# Constante de configuração 
DB_HOST = "192.168.0.1"

def conectar_banco();
  """Conecta usando a constante definido
  return f"Conectando ao {HD_HOST}"
