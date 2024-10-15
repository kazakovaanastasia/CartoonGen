# Fine Tune StableDiffusion с Lora; ControlNet; StableDiffusionControlNetPipeline

## Описание
Этот проект направлен на создание эффективного пайплайна с использованием Lora и ControlNet для генерации изображений в определённом стиле на основе поз/карт глубин и текстового промпта.

#### Шаги

-  ✅Обучение модели StableDiffusion  с помощью Lora на [датасете в мультяшном стиле](https://huggingface.co/datasets/linoyts/Tuxemon)
- ✅Иннференс ControlNet  на датасете с позами / картами глубин
- ✅Инференс StableDiffusionControlNetPipeline  с загруженными lora_weights, полученными после fine tuning на [датасете в мультяшном стиле](https://huggingface.co/datasets/linoyts/Tuxemon) :

С помощью StableDiffusionControlNetPipeline сгенерировать картинку по карте глубин в определённой стилистике (Tuxemon style)