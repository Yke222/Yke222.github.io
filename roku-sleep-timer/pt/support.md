---
layout: default
lang: pt-BR
title: Suporte
alternates:
  en: /roku-sleep-timer/en/support.html
  pt: /roku-sleep-timer/pt/support.html
  es: /roku-sleep-timer/es/support.html
---

# Suporte

## Primeiros passos

1. Conecte o celular à mesma rede Wi-Fi do Roku.
2. No Roku, abra **Configurações > Sistema > Configurações avançadas do sistema > Controle por apps móveis** e ajuste **Acesso à rede** para **Permissivo**.
3. Abra o app e escolha seu Roku na lista ou digite o IP dele (no Roku: **Configurações > Rede > Sobre**).
4. Escolha uma duração e toque em **Iniciar timer**. Depois é só assistir YouTube ou qualquer outro app na TV.

O modo desenvolvedor do Roku não é necessário.

## Dúvidas comuns

**O app diz que o Roku recusou o comando.** O Acesso à rede em **Controle por apps móveis** está em **Limitado** ou **Desativado**. Mude para **Permissivo**.

**Meu Roku não aparece na lista.** Alguns roteadores e iPhones bloqueiam a descoberta de aparelhos. Digite o IP do Roku.

**O Roku desligou, mas a TV continuou ligada.** Ative o HDMI-CEC na TV. Cada marca chama de um jeito, por exemplo Anynet+ (Samsung), SimpLink (LG), Bravia Sync (Sony) ou CEC (outras).

**No iPhone o timer não desligou o Roku.** O iOS não deixa apps enviarem comandos em segundo plano. Deixe o app aberto: ele mantém a tela ligada enquanto o timer corre. Se você sair dele, uma notificação lembra de voltar.

**No Android o timer não disparou.** Verifique se o app tem permissão de **Alarmes e lembretes** nas configurações do sistema e se a otimização de bateria não está restringindo o app.

## Contato

{% if site.contact_email != "" %}Envie um e-mail para [{{ site.contact_email }}](mailto:{{ site.contact_email }}) ou abra{% else %}Abra{% endif %} uma issue em [{{ site.issues_url }}]({{ site.issues_url }}).

[Política de privacidade](privacy.html) · [Termos de uso](terms.html)
