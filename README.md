# 📈 Crypto Price Alert Bot - Руководство пользователя

<div style="text-align: center; margin-bottom: 30px;">
  <img src="https://example.com/banner.png" alt="Баннер бота" style="max-width: 100%; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
  <p style="font-style: italic; color: #666; font-size: 0.9em;">Мощный инструмент для отслеживания крипторынка</p>
</div>

## 🌟 О боте

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #4285f4; margin: 15px 0;">
Crypto Price Alert Bot — это умный помощник для отслеживания резких изменений цен криптовалют на бирже Binance. Бот уведомляет вас, когда цена выбранной пары изменяется на заданный процент за указанный период.
</div>

## 🚀 Основные возможности

<div style="display: flex; flex-wrap: wrap; gap: 15px; margin: 20px 0;">
  <div style="flex: 1; min-width: 200px; background: #e3f2fd; padding: 12px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #1976d2;">🔔 Уведомления</h3>
    <p>Мгновенные алерты при достижении пороговых значений</p>
  </div>
  <div style="flex: 1; min-width: 200px; background: #e8f5e9; padding: 12px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #388e3c;">📊 Аналитика</h3>
    <p>Графики с ключевыми метриками волатильности</p>
  </div>
  <div style="flex: 1; min-width: 200px; background: #fff8e1; padding: 12px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #ffa000;">⚙ Управление</h3>
    <p>Гибкие настройки отслеживания</p>
  </div>
</div>

## 📋 Команды бота

<div style="overflow-x: auto;">
<table style="width: 100%; border-collapse: collapse; margin: 20px 0;">
  <thead>
    <tr style="background-color: #4285f4; color: white;">
      <th style="padding: 12px; text-align: left;">Команда</th>
      <th style="padding: 12px; text-align: left;">Описание</th>
      <th style="padding: 12px; text-align: left;">Пример</th>
    </tr>
  </thead>
  <tbody>
    <tr style="border-bottom: 1px solid #ddd;">
      <td style="padding: 12px;"><code>/start</code></td>
      <td style="padding: 12px;">Запустить бота</td>
      <td style="padding: 12px;"><code>/start</code></td>
    </tr>
    <tr style="border-bottom: 1px solid #ddd; background-color: #f9f9f9;">
      <td style="padding: 12px;"><code>/set</code></td>
      <td style="padding: 12px;">Установить условие</td>
      <td style="padding: 12px;"><code>/set</code> → <code>BTCUSDT 5</code></td>
    </tr>
    <tr style="border-bottom: 1px solid #ddd;">
      <td style="padding: 12px;"><code>/plot</code></td>
      <td style="padding: 12px;">Построить график</td>
      <td style="padding: 12px;"><code>/plot ETHUSDT</code></td>
    </tr>
  </tbody>
</table>
</div>

## 🛠 Настройка отслеживания

<div style="background: #f5f5f5; padding: 20px; border-radius: 8px; margin: 20px 0;">
  <h3 style="margin-top: 0; color: #4285f4;">Шаг 1: Установка условия</h3>
  <p>Используйте команду <code>/set</code> с параметрами:</p>
  <div style="background: white; padding: 10px; border-radius: 5px; border-left: 3px solid #4285f4; margin: 10px 0;">
    <code>/set BTCUSDT 5</code>
  </div>
  
  <h3 style="color: #4285f4;">Шаг 2: Получение уведомлений</h3>
  <div style="background: #e8f5e9; padding: 12px; border-radius: 5px; font-family: monospace;">
    📢 <strong>BTCUSDT</strong>: изменение на <strong>5.23%</strong><br>
    🕒 Время: 14:30 UTC<br>
    📉 Было: $51,200.00<br>
    📈 Стало: $53,850.00
  </div>
  
  <h3 style="color: #4285f4;">Шаг 3: Анализ графика</h3>
  <p>Пример графика за последний час:</p>
  <div style="text-align: center;">
    <img src="https://example.com/chart.png" alt="Пример графика" style="max-width: 100%; border: 1px solid #ddd; border-radius: 5px;"/>
  </div>
</div>

## ⚠️ Ограничения

<div style="background: #fff3e0; padding: 15px; border-radius: 8px; border-left: 4px solid #fb8c00; margin: 20px 0;">
  <ul style="margin: 0; padding-left: 20px;">
    <li>Максимум <strong>10 пар</strong> на пользователя</li>
    <li>Минимальный процент: <strong>0.01%</strong></li>
    <li>Данные только с <strong>Binance</strong></li>
    <li>Настройки сбрасываются при перезапуске</li>
  </ul>
</div>

## 🤖 Технические детали

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; margin: 20px 0;">
  <div style="background: white; padding: 15px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h4 style="margin-top: 0; color: #4285f4;">📡 Источник данных</h4>
    <p>Binance Public API</p>
  </div>
  <div style="background: white; padding: 15px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h4 style="margin-top: 0; color: #4285f4;">⏱ Частота</h4>
    <p>Проверка каждые 10 сек</p>
  </div>
  <div style="background: white; padding: 15px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h4 style="margin-top: 0; color: #4285f4;">🛠 Технологии</h4>
    <p>Python, aiogram, Binance API</p>
  </div>
</div>

## 💡 Советы

<div style="background: #e8eaf6; padding: 15px; border-radius: 8px; margin: 20px 0;">
  <div style="display: flex; align-items: center; margin: 10px 0;">
    <span style="background: #3f51b5; color: white; width: 25px; height: 25px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin-right: 10px;">1</span>
    <span>Для волатильных пар (например, SHIB) устанавливайте больший процент</span>
  </div>
  <div style="display: flex; align-items: center; margin: 10px 0;">
    <span style="background: #3f51b5; color: white; width: 25px; height: 25px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin-right: 10px;">2</span>
    <span>Используйте <code>/plot</code> перед установкой условий</span>
  </div>
  <div style="display: flex; align-items: center; margin: 10px 0;">
    <span style="background: #3f51b5; color: white; width: 25px; height: 25px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin-right: 10px;">3</span>
    <span>Удаляйте неактуальные пары для оптимизации</span>
  </div>
</div>

## 📞 Поддержка

<div style="text-align: center; background: #4285f4; color: white; padding: 20px; border-radius: 8px; margin-top: 30px;">
  <h2 style="margin-top: 0;">Нужна помощь?</h2>
  <p>Свяжитесь с разработчиком: <a href="https://t.me/your_username" style="color: white; text-decoration: underline;">@your_username</a></p>
  <p>или оставьте issue на <a href="https://github.com/yourrepo" style="color: white; text-decoration: underline;">GitHub</a></p>
</div>

<div style="text-align: center; margin-top: 40px; color: #666; font-size: 0.9em;">
  <p>Последнее обновление: 8 июня 2025 | Версия бота: 1.0</p>
  <p style="font-size: 1.2em;">🚀 <strong>Happy trading!</strong> 🚀</p>
</div>
