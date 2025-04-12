# DASIO-Model 0.25

## Описание
Данный проект представляет собой модель для оценки потока приходящей солнечной радиации на основе анализа облачности с использованием набора данных DASIO.

## Итоговая модель
Итоговая модель для короткой волны: **CatBoost Regressor**
Итоговая модель для длинной волны: **XBG Regressor**
## Метрики (оценка коротковолновой)
- **MSE**: 25.8 W/m^2
- **RMSE**: 51.7 W/m^2
- **R2-score**: 0.96
- **Средняя скорость прогноза**: между 10^-6 и 10^-5 секунд на изображение

## Метрики (оценка длинноволновой)
- **MSE**: 8.8 W/m^2
- **RMSE**: 12.9 W/m^2
- **R2-score**: 0.86
- **Средняя скорость прогноза**: между 10^-6 и 10^-5 секунд на изображение

## Доступные модели
- **long**: Модель для оценки длинноволновой радиации
- **short**: Модель для оценки коротковолновой радиации

Вы можете найти предварительно обученные модели в соответствующих файлах. Также предоставляются файлы с кодом для обучения данных моделей.

## Участники проекта

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: center; margin-top: 20px;">

  <div style="text-align: center; padding: 15px; background: #f5f5f5; border-radius: 10px; transition: transform 0.3s;">
    <a href="https://github.com/voldisoriginal" style="text-decoration: none; color: #333;">
      <img src="https://avatars.githubusercontent.com/u/159686633?v=4" width="100" style="border-radius: 50%; border: 3px solid #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
      <br>
      <span style="display: block; margin-top: 10px; font-weight: 600;">Voldisoriginal</span>
    </a>
  </div>

  <div style="text-align: center; padding: 15px; background: #f5f5f5; border-radius: 10px; transition: transform 0.3s;">
    <a href="https://github.com/Kartel7" style="text-decoration: none; color: #333;">
      <img src="https://avatars.githubusercontent.com/u/39780240?v=4" width="100" style="border-radius: 50%; border: 3px solid #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
      <br>
      <span style="display: block; margin-top: 10px; font-weight: 600;">Kartel7</span>
    </a>
  </div>

</div>