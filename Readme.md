## Прогноз пролонгации полиса автострахования 


### [EDA и генерация новых признаков](https://github.com/YaninaK/car-insurance-renewal/blob/main/notebooks/01_Car_insurance_renewal_EDA.ipynb)
* Генерация новых признаков была сделана с учетом требований к интерпретируемости результатов моделирования: инструментарий был ограничен линейными моделями и их обобщениями, а также простыми деревьями.

### [Benchmark: AutoML (PyCaret)](https://github.com/YaninaK/car-insurance-renewal/blob/main/notebooks/02_Car_insurance_renewal_AutoML.ipynb)
* Результаты, сгенерированные с помощью AutoML (PyCaret) использовались в качестве отправной точки.

### [Модели](https://github.com/YaninaK/car-insurance-renewal/blob/main/notebooks/03_Car_insurance_renewal_Models.ipynb)
* Прогнозы сделаны на основе ансамбля Logit-моделей, Generalized linear models, объединенных в последовательную композицию с Random Forest или LightGBM.
* Финальные результаты представлены в виде score для ранжирования по каждой из моделей, для всего ансамбля точка отсечения была определена исходя из максимизации F1-score. Возможны и другие бизнес-критерии выбора точки отсечения, свзанные со стоимостью обработки ложно-положительных и ложно-отрицательных ответов модели.
* [Результаты моделирования](https://drive.google.com/file/d/1-uSIAfjknozaIZ1uL4XAuK_r1pOuhTT4/view?usp=sharing)
