# AI VISION - Visão computacional

Processo de utilização do Microsoft Azure AI Vision. Acesso via portal: [Azure AI Vision](https://portal.vision.cognitive.azure.com/)

Alguns insights importantes:

- Já existem vários módulos prontos para classificção e detecção de imagens, incluindo mas nao se limitando a reconhecimento facial, extração de textos de imagens, detecção de objetos comuns em imagens, etc.
- A parte de reconhecimento de OCR (extracao de textos de imagens) funciona muito bem com baixissima porcentagem de problema.
- Além do portal já existem SDKs e acesso via API para que se possa incluir em alguma aplicação desenvolvida externamente.
- O módulo de `Adicionar caption em imagens` traz a acessibilidade ao mundo real pois é possível entender do que se trata determinada imagem e incluir uma legenda para facilitar aos portadores de deficiencia.

Eis alguns exemplos de classificação de imagens com percentuais bastante altos de assertividade:
> Na pasta `inputs` voces encontram as imagens originais inclusive com nomes que não descrevem o que a imagem é para evitar algum direcionamento na identificação.

- **Avião entre prédios**
![Avião entre prédios](/output/buildings_and_plane.png)
- **Cidade e Ponte**
![Cidade e Ponte](/output/city_and_bridge.png)
- **Cidade à noite**
![Cidade à noite](/output/city_lights.png)
