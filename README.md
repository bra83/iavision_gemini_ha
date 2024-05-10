# 🚀 Leve sua casa para o futuro: Visão Computacional com API do Gemini!

Este projeto integra a API do Gemini com o Home Assistant para fornecer análises de imagens e notificações contextuais sobre detecção de movimento.

## Descrição
Ao detectar movimento, o sistema captura três fotos em rápida sucessão e as envia para a API do Gemini para análise. A resposta do Gemini, descrevendo a causa do movimento, é enviada como uma notificação para o dispositivo móvel do usuário através do Home Assistant.

Dê um upgrade na segurança da sua casa com a inteligência artificial! Este projeto integra a poderosa API do Gemini ao seu Home Assistant, levando o reconhecimento de movimento para outro nível. Você não apenas saberá quando algo está acontecendo, mas também entenderá a causa do movimento, recebendo notificações detalhadas diretamente no seu celular.

### Detecção com Contexto: Vá Além dos Alertas Genéricos!
Imagine a diferença: em vez de receber um simples "Movimento detectado na porta da frente!", você recebe "Um gato foi detectado brincando próximo à porta da frente 🐈". Este projeto torna isso possível, combinando a automação do Home Assistant com a análise de imagem de última geração da API do Gemini.

## Como Funciona?
* 1 - Movimento Detectado: Seu sensor de movimento, integrado ao Home Assistant, identifica uma atividade.
* 2 - Captura Instantânea: A câmera de segurança associada ao sensor entra em ação, tirando três fotos em sequência rápida para garantir uma boa representação do evento.<br>
<img src="https://github.com/bra83/iavision_gemini_ha/blob/main/img1.jpg" alt="Texto Alternativo">
* 3 - Análise Inteligente: As imagens são enviadas para a API do Gemini, que usa algoritmos avançados de visão computacional para analisar a cena.<br>
* 4 - Notificação Detalhada: Você recebe uma notificação no seu celular, informando o que realmente aconteceu: "Um entregador deixou um pacote na porta" ou "Folhas caindo foram detectadas no jardim".<br>

<img src="https://github.com/bra83/iavision_gemini_ha/blob/main/ss_notification.jpg" alt="Texto Alternativo">

### Segurança Personalizada e Tranquilidade Total
Este projeto não apenas aprimora a segurança, mas também oferece tranquilidade e personalização. Você pode ajustar a sensibilidade do sistema, personalizar as mensagens de notificação e integrar outras automações do Home Assistant.

## Pré-requisitos
* Home Assistant instalado e configurado.
* Câmera e sensor de movimento integrados ao Home Assistant.
* Acesso à API do Gemini com chave de API válida.
* Aplicativo móvel do Home Assistant configurado para receber notificações.

## Personalização
* Ajuste o tempo de espera na automação (delay) de acordo com o tempo de resposta da API do Gemini.
* Adapte o texto das notificações no arquivo automation.yaml às suas preferências.

## Exemplo de Notificação
Movimento detectado!
Um gato foi detectado próximo à porta da frente.

## Informações Adicionais
* A precisão da análise depende da qualidade da imagem e das capacidades da API do Gemini.
* Certifique-se de que o Home Assistant tenha permissão para acessar os arquivos de imagem temporários.
* Consulte a documentação da API do Gemini para obter informações detalhadas sobre seus recursos e funcionamento.

## Alguns exemplos de integração entre API Gemini e Home Assistant:
1. <b>Segurança proativa em caso de queda:</b><br>
<i>Cenário:</i> Uma pessoa idosa sozinha em casa.<br>
<i>Integração:</i> O Home Assistant, com a API Gemini, detecta uma queda através de uma câmera e envia uma notificação para um familiar ou responsável, além de acionar um sistema de comunicação para confirmar o estado da pessoa.
2. <b>Monitoramento de animais de estimação:</b><br>
<i>Cenário:</i> Você quer saber o que seu pet está aprontando enquanto está fora de casa.<br>
<i>Integração:</i> A API Gemini analisa as imagens da câmera e notifica você no celular com mensagens divertidas: "Seu cachorro está dormindo no sofá" ou "Seu gato está tentando abrir a geladeira!".
3. <b>Identificação de objetos para organização:</b><br>
<i>Cenário:</i> Organizar a garagem ou a despensa de forma inteligente.<br>
<i>Integração:</i> Ao apontar a câmera para um objeto, a API Gemini o identifica e o Home Assistant sugere um local de armazenamento ideal, além de criar um inventário automático.
4. <b>Detecção de intrusos com análise de comportamento:</b><br>
<i>Cenário:</i> Diferenciar um entregador de um possível invasor.<br>
<i>Integração:</i> A API Gemini analisa os movimentos e atitudes de uma pessoa na área externa da casa, e o Home Assistant dispara alertas mais precisos em caso de comportamento suspeito.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um Pull Request com melhorias ou correções.

# Considerção sobre o projeto
Apesar de funcionar perfeitamente em meu servidor com o Home Assistant todo configurado, este projeto visa apenas ilustrar a possibilidade de funcionamento para a Imersão de IA da Alura + Google.<br>
Para o projeto funcionar perfeitamente em seu computador, é necessário que o Home Assistant esteja instalado e configurado, assim como possuir câmeras de segurança e sensores de movimentos compatíveis com o Home Assistant.<br>

<b>Documentação do Home Assistant</br> - https://www.home-assistant.io/docs/
