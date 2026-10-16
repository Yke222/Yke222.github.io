---
layout: default
lang: pt-BR
title: Política de privacidade
alternates:
  en: /roku-sleep-timer/en/privacy.html
  pt: /roku-sleep-timer/pt/privacy.html
  es: /roku-sleep-timer/es/privacy.html
---

# Política de privacidade

Vigente desde: {{ site.policy_effective_date }}

Esta política explica quais informações o aplicativo Roku Sleep Timer ("o app") trata no Android e no iOS. O app é feito por um desenvolvedor independente ("nós") e não tem relação com a Roku, Inc.

## Resumo

- Não temos servidores nem contas de usuário, e nunca recebemos suas informações pessoais.
- Os dados do seu Roku e suas configurações ficam no seu celular.
- O app exibe anúncios do Google AdMob. O Google pode coletar identificadores do dispositivo e dados de uso para exibir e medir anúncios, como descrito abaixo.
- O app usa o Google Firebase Analytics e o Crashlytics para entender como o app é usado e corrigir falhas. Esses serviços podem coletar dados do dispositivo e de uso, como descrito abaixo.

## Informações guardadas no seu celular

Para desligar seu Roku, o app guarda no seu celular:

- o endereço IP, o nome, o modelo e o número de série do Roku conectado;
- o idioma escolhido;
- o horário de término de um timer em andamento.

Essas informações ficam só no seu celular. Elas são enviadas apenas ao seu Roku, pela sua rede local, e nunca para nós. Tocar em **Trocar** nas configurações do app esquece o Roku, e desinstalar o app apaga tudo.

## Comunicação com o seu Roku

O app encontra aparelhos Roku na sua rede Wi-Fi e envia comandos como "desligar" usando o External Control Protocol da Roku (rede local, porta 8060). Esse tráfego fica dentro da sua rede local e, por definição da Roku, não é criptografado.

## Anúncios (Google AdMob)

O app exibe um anúncio em tela cheia ao ser aberto. Os anúncios são fornecidos pelo Google AdMob, que pode coletar e tratar:

- identificadores do dispositivo, como o ID de publicidade do Android ou o identificador de publicidade do iOS (IDFA, só se você permitir o rastreamento);
- seu endereço IP e a localização aproximada derivada dele;
- informações do aparelho e do app, como modelo, sistema operacional e versão do app;
- interações com anúncios, como visualizações e toques, além de dados de diagnóstico.

O Google usa esses dados para exibir anúncios, medir o desempenho deles, limitar a frequência com que você os vê e evitar fraudes. Onde a lei exige (por exemplo, no Espaço Econômico Europeu, no Reino Unido e na Suíça), o app pede seu consentimento antes de exibir anúncios, usando a ferramenta de consentimento do Google. Nesses casos, você pode mudar sua escolha a qualquer momento no app em **Configurações > Privacidade e anúncios**. No iOS, os anúncios só são personalizados se você permitir o rastreamento. Você também pode redefinir ou excluir seu ID de publicidade nas configurações do celular.

Saiba mais em [Como o Google usa informações de sites ou apps que usam os serviços dele](https://policies.google.com/technologies/partner-sites?hl=pt-BR) e na [Política de Privacidade do Google](https://policies.google.com/privacy?hl=pt-BR).


## Análise e relatórios de falha (Google Firebase)

O app usa o Google Firebase Analytics e o Firebase Crashlytics para vermos quais funções são usadas, onde a configuração falha e quando o app trava. O Firebase pode coletar e tratar:

- eventos do app, como abrir telas, conectar um Roku, iniciar ou cancelar um timer, e se o desligamento funcionou;
- dados de falha e diagnóstico, como stack traces, versão do app e modelo do aparelho;
- identificadores de dispositivo usados pelo Google Analytics for Firebase (por exemplo o app-instance id).

Esses relatórios não incluem o nome, o IP ou o número de série do seu Roku. Usamos esses dados só para melhorar o app e corrigir erros. Saiba mais na [Política de Privacidade do Google](https://policies.google.com/privacy?hl=pt-BR) e nas [informações de privacidade do Firebase](https://firebase.google.com/support/privacy?hl=pt-BR).

## Notificações

No iOS, o app pode agendar uma notificação local para lembrar você quando um timer terminar. Ela é criada no próprio celular e não passa por nenhum servidor.

## O que não fazemos

- Não vendemos suas informações pessoais.
- Não coletamos contatos, fotos, localização precisa ou arquivos.
- Não vendemos dados de análise. Relatórios de uso e falha vão só ao Google Firebase para os fins acima.

## Crianças

O app não é direcionado a menores de 13 anos e não coletamos intencionalmente informações deles.

## Seus direitos

Dependendo de onde você mora (por exemplo, pela LGPD no Brasil, pelo GDPR na União Europeia ou pelo CCPA na Califórnia), você pode ter direito de acessar, corrigir ou excluir dados pessoais e de se opor ao tratamento deles. Não guardamos dados pessoais sobre você em servidores próprios. Para os dados tratados pelo Google para anúncios, análise ou relatórios de falha, use os controles acima ou as [ferramentas de privacidade do Google](https://myaccount.google.com/data-and-privacy?hl=pt-BR).

## Alterações

Se esta política mudar, atualizaremos a data de vigência acima e publicaremos a nova versão nesta página.

## Contato

{% if site.contact_email != "" %}Envie um e-mail para [{{ site.contact_email }}](mailto:{{ site.contact_email }}) ou abra{% else %}Abra{% endif %} uma issue em [{{ site.issues_url }}]({{ site.issues_url }}).
