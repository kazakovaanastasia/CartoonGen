# Fine Tune StableDiffusion с Lora; ControlNet; StableDiffusionControlNetPipeline 

## Описание
Этот проект направлен на создание эффективного пайплайна с использованием Lora и ControlNet для генерации изображений в определённом стиле на основе поз/карт глубин и текстового промпта.

#### Шаги

-  ✅Обучение модели с помощью Lora на [датасете в мультяшном стиле](https://huggingface.co/datasets/linoyts/Tuxemon)
- ✅Инференс модели с помощью ControlNet на датасете с позами / картами глубин
- ✅Обучение Lora и ControlNet в одном пайплайне
с помощью StableDiffusionControlNetPipeline сгенерировать картинку по карте глубин в определённой стилистике (Tuxemon style)