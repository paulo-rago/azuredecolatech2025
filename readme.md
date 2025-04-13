**Análise das Respostas do Azure Cognitive Services - Sentiment Analysis**


1ª Análise — Texto Objetivo e Equilibrado
"I am very happy today because I achieved all my goals. However, sometimes I feel a little anxious about the future. Life is full of challenges, but I am feeling positive and motivated to keep going."

Resultado do Azure:
Sentimento do Documento: Mixed (54% Positivo, 25% Neutro, 21% Negativo)

![Captura de tela 2025-04-12 233543](https://github.com/user-attachments/assets/6ae82209-634a-4c10-b516-0ed4662100ba)

Análise:
Neste caso, a IA do Azure conseguiu identificar corretamente que o texto apresenta sentimentos mistos, já que há expressões positivas (felicidade e motivação), mas também expressa certa ansiedade em relação ao futuro. O resultado foi coerente com o contexto do texto.

2ª Análise — Texto Irônico
"Wow, this is just perfect! Another meeting that could have been an email. I'm absolutely thrilled."

Resultado do Azure:
Sentimento do Documento: Positive (99% Positivo)

![Captura de tela 2025-04-12 233735](https://github.com/user-attachments/assets/6f4d5995-0474-4716-b850-0359901a947a)

Análise:
Aqui, apesar do contexto ser claramente irônico e negativo (crítica disfarçada de elogio), a IA do Azure interpretou o texto como totalmente positivo. Isso demonstra uma limitação do serviço em captar ironia e sarcasmo, já que a análise é baseada em palavras isoladas como perfect e thrilled, sem considerar o tom real da mensagem.

3ª Análise — Texto Ambíguo com Contraste de Emoções
"I'm so sad that I'm smiling right now because everything is finally falling apart exactly the way I hoped."

Resultado do Azure:
Sentimento do Documento: Negative (91% Negativo)

![Captura de tela 2025-04-12 233819](https://github.com/user-attachments/assets/b0e5adc1-fa2e-4051-abbd-2162d67e6e4f)

Análise:
Nesse exemplo, o texto foi propositalmente construído para gerar ambiguidade, unindo termos positivos e negativos em uma mesma frase. Apesar da confusão aparente, a IA do Azure classificou o sentimento como predominantemente negativo, muito provavelmente por causa de palavras-chave como sad e falling apart. No entanto, parte da essência irônica e do humor ácido do texto não foi compreendida.
