# Pré-requisitos Necessários para Começar


## Glossário

Sabemos que alguns termos são novos, então antes de começar dê uma olhada na tabela abaixo:

| Termo | Descrição |
| --- | --- |
| _Preferência (preference)_ | São as **informações do produto ou serviço que você quer oferecer.** Entre os atributos mais importantes de uma preferência são definidas as seguintes informações: a descrição, o valor e os itens. Ao gerá-lo, você obtém uma URL para iniciar o fluxo de pagamento. |
| _Credenciais (credentials)_ | Suas credenciais são as **chaves que te informamos para que você possa configurar suas integrações.**<br/>Existem dois tipos:<br/><br/>**Public key**: chave pública da aplicação para saber, por exemplo, os meios de pagamento e criptografar os dados do cartão. Você deve usá-las somente para as suas integrações.<br/>**Access token**: chave privada da aplicação para gerar pagamentos. Você deve usá-la somente para suas integrações.<br/><br/>Para poder encontrá-las, confira suas [credenciais]([FAKER][CREDENTIALS][URL]) e selecione as produtivas.<br/><br/> |
| _Ponto de inicio (init_point)_ | É a **URL obtida na hora de gerar a preferência** e que dá início ao fluxo de pagamento do Checkout Pro. |
| _Item (item)_ | Faz referência ao produto ou serviço que se quer oferecer, podendo ser um único produto/serviço ou uma lista. |
| _Aplicação (application)_ | As aplicações são usadas para processar os pagamentos do vendedor. **Cada aplicação identifica uma integração específica**, pois cada uma possui suas próprias [credenciais]([FAKER][CREDENTIALS][URL]).<br/><br/> Uma conta do Mercado Pago pode ter diversas aplicações e você pode encontrar as informações de cada uma na seção de **Credenciais**, clicando no menu **Recursos**. Ao entrar, uma aplicação será criada automaticamente ou você poderá [criá-la](https://applications.mercadopago.com) sempre que precisar. |

## Configurações

Observe o passo-a-passo a seguir antes de começar a integração:

### 1. Acesse uma conta:
Para poder começar a integração, é necessário **contar com uma conta do Mercado Pago ou do Mercado Livre.**

Você pode [entrar](https://www.mercadolibre.com/jms/[FAKER][GLOBALIZE][SITE_ID]/lgz/login?platform_id=mp&go=https://www.mercadopago[FAKER][URL][DOMAIN]/developers/pt/guides/online-payments/checkout-pro/previous-requirements) em uma conta existente ou [criar uma nova conta](https://www.mercadopago[FAKER][URL][DOMAIN]).

### 2. Instale o SDK do Mercado Pago:
**Instale o SDK oficial** para simplificar sua integração com as nossas APIs.

[[[
```php
===
[Instale o Composer](https://getcomposer.org/download) para usar o SDK e, em seguida, execute o seguinte código na linha de comandos:
===
php composer.phar require "mercadopago/dx-php"
```
```node
===
Para instalar o SDK, você deve executar o seguinte código na linha de comandos do seu terminal utilizando [npm](https://www.npmjs.com/get-npm):
===
npm install mercadopago
```
```java
===
Para instalar o SDK no seu projeto [Maven](http://maven.apache.org/install.html), adicione a seguinte dependência no seu arquivo ˜pom.xml˜ e execute o **maven install**.
===
<dependency>
            <groupId> com.mercadopago </groupId>
            <artifactId> sdk-java </artifactId>
            <version> 1.9.0 </version>
</dependency>
```
```ruby
===
O SDK do Mercado Pago está disponível como [gema](https://rubygems.org/gems/mercadopago-sdk).Para instalá-la, você deve executar o seguinte código na linha de comandos:
===
gem install mercadopago-sdk
```
```csharp
===
----[mlb]----
Utilize o [NuGet](https://docs.microsoft.com/pt-br/nuget/reference/nuget-exe-cli-reference) para instalar o **SDK .NET** do Mercado Pago.
------------
----[mla, mlm, mco, mlc, mlu]----
Use [NuGet](https://docs.microsoft.com/es-es/nuget/reference/nuget-exe-cli-reference) para instalar el SDK .NET de Mercado Pago.
------------
Execute o seguinte comando no seu terminal:
===
nuget install mercadopago-sdk
```
```python
===
O SDK do Mercado Pago está disponível como [pip](https://pypi.org/project/mercadopago/). Para instalá-la, você deve executar o seguinte código na linha de comandos:
===
pip3 install mercadopago
```
]]]

### 3. Obtenha suas credenciais:

As credenciais são as **chaves que te oferecemos para que possa configurar sua integração**.

Para poder encontrá-las, veja a [seção de Credenciais]([FAKER][CREDENTIALS][URL]).

> Tem dúvidas sobre credenciais? Leia a seção de [Credenciais](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/pt/guides/resources/credentials) para mais informações. 

---

### Próximos passos

> LEFT_BUTTON_REQUIRED_PT
>
> Integre o Checkout Pro
>
> Siga o passo-a-passo para começar a receber pagamentos no seu site.
>
> [Integre o Checkout Pro](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/pt/guides/online-payments/checkout-pro/integration)

> RIGHT_BUTTON_RECOMMENDED_PT
>
> Teste a sua Integração
>
> Confira se está tudo em ordem na sua integração com os usuários de teste.
>
> [Teste a sua integração](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/pt/guides/online-payments/checkout-pro/test-integration)
