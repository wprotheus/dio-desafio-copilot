# DIO - Trilha Java Básico

## Autor

🔸[wprotheus](https://github.com/wprotheus)

---

## Desafio - Criando seu primeiro Copiloto no Microsoft Copilot Studio  

Atividade executada conforme vídeos do [Desafio](https://web.dio.me/lab/criando-seu-primeiro-copiloto-no-microsoft-copilot-studio/learning/9eedcc64-8574-4bd7-a688-501124e14f67) e orientações abaixo.  
<small><sup>Obs.: O link acima somente é acessado através de uma conta na plataforma DIO.</sup></small>

### Descrição do Desafio

> O objetivo deste desafio é criar seu primeiro Copiloto no Microsoft Copilot Studio.

#### Em -> INFORMAÇÕES  
> Aprenda a criar um copiloto no Microsoft Copilot Studio, abordando a configuração de fluxos de conversa, integração com serviços externos e personalização de respostas. Ao final, você terá um assistente funcional capaz de interagir de forma inteligente e automatizar tarefas.

---  

# 📜 Criando um Copiloto no Microsoft Copilot Studio

Este tutorial guiará você através dos passos para criar um assistente funcional no Microsoft Copilot Studio, capaz de interagir de forma inteligente e automatizar tarefas.

## Passo 1: Configuração Inicial  

1. Acesso ao Microsoft Copilot Studio:
- Acesse o Microsoft Copilot Studio em copilot.microsoft.com.

2. Criar um Novo Projeto:  
- Clique em "Novo Projeto" e dê um nome ao seu projeto, por exemplo, "Meu Copiloto Inteligente".

## Passo 2: Configuração de Fluxos de Conversa  

1. Criar um Novo Fluxo de Conversa:  
- No menu do projeto, clique em "Fluxos de Conversa".
- Clique em "Novo Fluxo de Conversa" e defina um nome descritivo, como "Atendimento ao Cliente".

2. Definir Intenções e Diálogos:  
- Para cada fluxo de conversa, defina as intenções principais (por exemplo, "Perguntas Frequentes", "Suporte Técnico").
- Crie diálogos para cada intenção, especificando possíveis entradas do usuário e respostas correspondentes.

## Passo 3: Integração com Serviços Externos  

1. Configurar Conexões Externas:  
- No menu do projeto, clique em "Conexões".  
- Adicione conexões com serviços externos necessários, como APIs REST, bancos de dados ou sistemas CRM.    
- Configure as credenciais e parâmetros de autenticação conforme necessário.    
  
2. Chamar Serviços Externos nos Diálogos:  
- Em cada diálogo, utilize ações para chamar os serviços externos configurados.  
- Exemplo em Markdown:

```yaml
steps:
  - action: "action_name"
    parameters:
      key: "value"
```
  
## Passo 4: Personalização de Respostas  

1. Criar Respostas Dinâmicas:
- Utilize variáveis e lógica condicional para personalizar as respostas com base nas interações do usuário.  
- Exemplo em Markdown:

```yaml
responses:
  - response: "{{response}}"
```

2. Refinar a Lógica de Diálogo:  
- Ajuste a lógica dos diálogos com base no feedback e nos resultados obtidos durante os testes.

## Passo 5: Teste e Implantação  

1. Testar o Copiloto:
- Utilize o ambiente de teste integrado para simular interações com o copiloto.
- Verifique a correção das respostas e a integração com os serviços externos.

2. Implantar o Copiloto:
- Após os testes bem-sucedidos, implante o copiloto em produção para uso real.  
    
---  
  
## 📚 Documentação Recomendada    

- [Documentação do Microsoft Copilot Studio](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/)
