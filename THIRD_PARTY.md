# Сторонние компоненты

- `bgr.js` и `bgdata/` — [@imgly/background-removal](https://github.com/imgly/background-removal-js) 1.4.5 с моделью ISNet (medium), лицензия AGPL-3.0. Исходный код библиотеки: https://github.com/imgly/background-removal-js
- Внутри `bgr.js` также [onnxruntime-web](https://github.com/microsoft/onnxruntime) (MIT), lodash, ndarray, zod (MIT).
- HEIC на компьютере открывается через [heic2any](https://github.com/alexcorvi/heic2any) (MIT), загружается с jsDelivr только при необходимости.

Код страницы (`index.html`, `sw.js`) открыт в этом репозитории.

- `scenes/` — фоны-сцены, собранные из собственных фото владельца сайта.
