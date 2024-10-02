
# O que é *Phishing*?

De acordo com a Cybersecurity and Infrastructure Security Agency (CISA):
> "Phishing é um tipo de ataque de engenharia social frequentemente usado para roubar dados de usuário, incluindo credenciais de login e números de cartão de crédito. Isso ocorre quando um atacante, se passando por uma entidade confiável, engana a vítima para abrir um email, mensagem instantânea ou mensagem de texto mal-intencionada que parece legítima. O objetivo é enganar a vítima para revelar informações sensíveis ou clicar em um link mal-intencionado que instala malware ou a direciona para um site fraudulento."


## Spear Phishing

De acordo com a Kaspersky:
> "Enquanto phishing é um termo geral para ataques cibernéticos realizados por e-mail, SMS ou chamadas telefônicas, alguns podem se perguntar como são chamados ataques de phishing direcionados. A resposta é spear phishing. Em termos mais simples, trata-se de ataques cibernéticos altamente personalizados que visam indivíduos ou empresas específicas. Normalmente, esses ataques são realizados por meio de e-mails de spear phishing que parecem legítimos para o destinatário e os incentivam a compartilhar detalhes confidenciais com o invasor. Embora o objetivo dos ataques de spear phishing geralmente seja roubar informações como credenciais de login ou informações de cartão de crédito, alguns são projetados para infectar dispositivos com malware. Frequentemente, hackers e hacktivistas patrocinados pelo governo são os perpetradores de golpes de spear phishing. No entanto, criminosos cibernéticos individuais também realizam esses ataques com a intenção de perpetrar roubo de identidade ou fraude financeira, manipulando preços de ações, cometendo espionagem ou roubando dados confidenciais para revendê-los a governos, empresas privadas ou outros indivíduos interessados."

## Ferramentas para Testes de Phishing

Para testes em escala, vale ressaltar que existem ferramentas mais apropriadas como o *Gophish*, *Evilginx2*, *HiddenEye*, *King Phisher*, etc. Mas para propósitos conceituais, iremos usar a ferramenta SET (Social-Engineer Toolkit) que já vem disponível em distros como o Kali Linux.

Vale ressaltar que a eficácia de phishings e engenharia social está ligada à quantidade de informações disponíveis, então também podemos associar a OSINT (Open Source Intelligence).

### Ferramentas Utilizadas

- **Kali Linux**
- **SET (Social-Engineer Toolkit)**


### Configurando o Phishing no Kali

- Inicie um terminal
- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Insira o ip local, onde serão recebidas as informações.
- Insira a URL para clone, neste exemplo estarei usando o github.

## Fontes
[Kaspersky - Spear Phishing](https://www.kaspersky.com.br/resource-center/definitions/spear-phishing)
[CISA - Avoiding Social Engineering and Phishing Attacks](https://www.cisa.gov/news-events/news/avoiding-social-engineering-and-phishing-attacks)
