# data-sense-vacancy

## Подготовка к собеседованию (live coding в Вашей среде)

- Установить **[Qlik Sense Desktop](https://github.com/qlik-download/qlik-sense-desktop/releases/tag/v14.139.4)**;
- Скопировать **Qlik_Sense_Desktop.unlock.json** в папку `C:\Users\User\Documents\Qlik\Sense\trial` (папку trial нужно создать, подробнее читай инструкцию по ссылке выше)
- Скопировать **Whats New App - August 2023.qvf** файл в `C:\Users\User\Documents\Qlik\Sense\Apps`
- Подготовить своё окружение: IDE, node, npm и т.д.
- После установки Qlik Sense Desktop, если unlock файл корректно размещен, то будет доступа кнопка запуска (Launch)
- После запуска в браузере перейдите по ссылке `localhost:4848/hub` (она должна открыться)

## Дополнительно

- При отрисовке отчёта используется client.html (C:\Users\User\AppData\Local\Programs\Qlik\Sense\Client)
- При отрисовке хаба используется hub.html (C:\Users\User\AppData\Local\Programs\Qlik\Sense\Client)
- [Connecting to the Qlik Engine JSON API](https://help.qlik.com/en-US/sense-developer/August2023/Subsystems/EngineAPI/Content/Sense_EngineAPI/GettingStarted/connecting-to-engine-api.htm)
- [Engine API](https://qlik.dev/apis/json-rpc/qix/global#%23%2Fentries%2FGlobal)
- [enigma.js](https://github.com/qlik-oss/enigma.js/blob/master/README.md)

`global -> openDoc -> grtAllInfos -> getObject`
