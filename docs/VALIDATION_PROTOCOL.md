# Протокол за проверка / Validation protocol

Автор на концепцията / Concept author: Христо Георгиев Грамовски / Hristo Georgiev Gramovski.

## Български

1. Запазвайте оригиналните данни и ZIP архиви, източника, условията за използване, метаданните и калибрацията.
2. Проверявайте часовите зони, честотата, пропуските, дублираните времена, смяната на датчици и единиците. ORP и Eh не се приемат за взаимозаменяеми без информация за референтния електрод.
3. Анализирайте суровия сигнал преди филтриране. Описвайте филтъра, параметрите и всички варианти. При прогнозен тест обработката не трябва да използва бъдещи измервания.
4. Определяйте допустимия интервал между измерванията преди анализа; прекъсвайте серията при по-големи паузи. Не изчислявайте производни през тях.
5. Контролирайте температура, pH, проводимост, кислород, водно ниво, сезонност, обслужване и технически артефакти, когато са налични данни. Липсващ контрол се отбелязва.
6. Предварително определяйте събитията, магнитудния праг, пространствения обхват, времевия прозорец, аномалията и посоката на ефекта. Отчитайте разстоянието и геологията.
7. Сравнявайте с контролни дати и процедури, запазващи времевата зависимост. Отчитайте множествените сравнения и настройването на параметри.
8. Проверявайте върху независими периоди и станции. Разграничавайте предсеизмични и следсеизмични изменения.
9. Публикувайте отрицателните и неубедителните резултати, отменените анализи и неизпълнените проверки.
10. За прогнозна оценка отчитайте попадения, пропуснати събития, фалшиви тревоги, време под тревога и преднина. Статистическата асоциация не замества тази оценка.

За всеки тест запишете: идентификатор, източници и версии, период, станции, единици, покритие, обработка, фиксирани критерии, контрол, брой събития, размер на ефекта, неопределеност, всички проверени варианти, код и ограничения.

## English

Preserve original data and archives, provenance, reuse terms, metadata, and calibration. Audit time zones, sampling, gaps, duplicate times, instrument changes, units, and reference electrodes. Do not equate ORP and Eh without reference information.

Inspect raw signals first. Document all filters and parameter variants; predictive processing must not use future samples. Fix a maximum sampling gap before analysis and split the series at longer gaps. Never differentiate across those gaps.

Use available environmental and instrument controls and report missing controls. Fix event selection, spatial scope, magnitude threshold, anomaly criteria, and lead windows in advance. Consider source distance and geology.

Use controls accounting for temporal dependence and multiple testing. Validate on independent periods and stations. Report negative, inconclusive, withdrawn, and unperformed tests. Forecast evaluation must include hits, missed events, false alarms, time under alarm, and lead time.

Each report must include data versions, coverage, units, methods, fixed criteria, controls, event counts, effect sizes, uncertainty, all tested variants, executable code, and limitations.
