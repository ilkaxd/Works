<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
  </head>
  <body>
    <table>
      <caption>
        Рабочие и не очень проекты:
      </caption>
      <thead>
        <tr>
          <th>№</th>
          <th>Компания</th>
          <th>Проект</th>
          <th>Описание</th>
          <th>Связанный проект</th>
          <th>Описание связанного проекта</th>
          <th>Стек</th>
          <th>Дата начала</th>
          <th>Статус</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>RUSAL</td>
          <td><a href="https://github.com/ilkaxd/ReportGenerator" target="_blank">ReportGenerator</a></td>
          <td>Генератор унифицированных отчётов в Word</td>
          <td></td>
          <td></td>
          <td>Django[Python]</td>
          <td>05.2024</td>
          <td>Остановлен</td>
        </tr>
        <tr>
          <td>2</td>
          <td>RUSAL</td>
          <td><a href="https://github.com/ilkaxd/DBReader" target="_blank">DBReader</a></td>
          <td>Сервис работы с заводской БД MS SQL в рамках системы PrecipExpert</td>
          <td></td>
          <td></td>
          <td>WPF[C#]</td>
          <td>06.2024</td>
          <td>В эксплуатации</td>
        </tr>
        <tr>
          <td rowspan="4">3</td>
          <td rowspan="4">PET</td>
          <td rowspan="4"><a href="https://github.com/ilkaxd/CalibrationStand" target="_blank">CalibrationStand</a></td>
          <td rowspan="4">Калибровочный стенд</td>
          <td><a href="https://github.com/ilkaxd/CalibrationStandServer" target="_blank">CalibrationStandServer</a></td>
          <td>Сервер блока управления для Linux</td>
          <td>React[TypeScript], Django[Python]</td>
          <td rowspan="4">12.2023</td>
          <td rowspan="4">В эксплуатации</td>
        </tr>
        <tr>
          <td><a href="https://github.com/ilkaxd/CalibrationStandDesktop" target="_blank">CalibrationStandDesktop</a></td>
          <td>Приложение для Windows для управления</td>
          <td>WPF[C#]</td>
        </tr>
        <tr>
          <td><a href="https://github.com/ilkaxd/CalibrationStandAndroid" target="_blank">CalibrationStandAndroid</a></td>
          <td>Приложение для Android для управления</td>
          <td>Kotlin</td>
        </tr>
        <tr>
          <td><a href="https://github.com/ilkaxd/CalibrationStandAndroid" target="_blank">CalibrationStandPLC</a></td>
          <td>Код для ПЛК ОВЕН ПР205</td>
          <td>FBD + ST</td>
        </tr>
        <tr>
          <td>4</td>
          <td>RUSAL</td>
          <td><a href="https://github.com/ilkaxd/MillExpert" target="_blank">MillExpert</a></td>
          <td>Система оценки загрузки мельницы</td>
          <td></td>
          <td></td>
          <td>React[TypeScript], Django[Python]</td>
          <td>05.2024</td>
          <td>В эксплуатации с поддержкой</td>
        </tr>
        <tr>
          <td rowspan="3">5</td>
          <td rowspan="3">RUSAL</td>
          <td rowspan="3"><a href="https://github.com/ilkaxd/Balancer" target="_blank">Balancer</a></td>
          <td rowspan="3">Система согласованных измерений</td>
          <td><a href="https://github.com/ilkaxd/BalanceServer" target="_blank">BalanceServer</a></td>
          <td>Веб-сервис системы согласованных измерений</td>
          <td>React[TypeScript], Django[Python]</td>
          <td rowspan="3">01.2025</td>
          <td rowspan="3">В эксплуатации с поддержкой</td>
        </tr>
        <tr>
          <td><a href="https://github.com/ilkaxd/LimsServer">LimsServer</a></td>
          <td>Сервис для интеграции с системой химических анализов</td>
          <td>Django[Python]</td>
        </tr>
        <tr>
          <td><a href="https://github.com/ilkaxd/BalanceServerApi">BalanceServerApi</a></td>
          <td>Обёртка на C# для работы с веб-сервисом</td>
          <td>C#</td>
        </tr>
        <tr>
          <td>6</td>
          <td>PET</td>
          <td><a href="https://github.com/ilkaxd/VK-ORD" target="_blank">VK-ORD</a></td>
          <td>Автоматизированная работа с рекламой через VK ОРД</td>
          <td></td>
          <td></td>
          <td>Python</td>
          <td>06.2025</td>
          <td>В разработке</td>
        </tr>
        <tr>
          <td rowspan="3">7</td>
          <td rowspan="3">PET</td>
          <td rowspan="3"><a href="https://github.com/ilkaxd/plus_size_shopping_bot" target="_blank">plus_size_shopping_bot</a></td>
          <td rowspan="3">Сервис для работы с ботами</td>
          <td><a href="https://github.com/ilkaxd/plus_size_shopping_bot_telegram">plus_size_shopping_bot_telegram</a></td>
          <td>Бот для телеграм по продаже гайдов</td>
          <td>aiogram[Python],FastApi[Python]</td>
          <td rowspan="3">02.2025</td>
          <td rowspan="3">В эксплуатации с поддержкой</td>
        </tr>
        <tr>
          <td><a href="https://github.com/ilkaxd/plus_size_shopping_bot_max">plus_size_shopping_bot_max</a></td>
          <td>Бот для MAX по продаже гайдов</td>
          <td>maxapi[Python],FastApi[Python]</td>
        </tr>
        <tr>
          <td><a href="https://github.com/ilkaxd/shopping_bot_payment_gateway">shopping_bot_payment_gateway</a></td>
          <td>Шлюз для распредлеления платежей из различных источников в соответствующие системы</td>
          <td>FastApi[Python]</td>
        </tr>
        <tr>
          <td>8</td>
          <td>PET</td>
          <td><a href="https://github.com/ilkaxd/PlantControllerPLC" target="_blank">PlantControllerPLC</a></td>
          <td>Система управления растениями на базе ПЛК ОВЕН ПР205</td>
          <td></td>
          <td></td>
          <td>FBD</td>
          <td>08.2025</td>
          <td>В разработке</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
