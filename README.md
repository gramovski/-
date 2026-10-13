# Метод Грамовски / Gramovski Method

**Автор на концепцията / Concept author: Христо Георгиев Грамовски — Hristo Georgiev Gramovski**  
**Начало на проекта / Project initiated: 2026**  
**Актуализация / Updated: 13 October 2026**

**Публична страница / Public research website:** [Български](https://gramovski-method.ochremoth32.chatgpt.site/) · [English](https://gramovski-method.ochremoth32.chatgpt.site/en/)

## Кратко представяне / Research overview

**Метод Грамовски (Gramovski Method), MMII — ORP/Eh, микробен метаболизъм и сеизмогеохимия.** Изследователски проект на **Христо Георгиев Грамовски / Hristo Georgiev Gramovski**, започнат през 2026 г. Целта е да се проверят възможни връзки между редокс динамиката и сеизмичните процеси чрез открити данни, контролни сравнения и възпроизводим анализ. Прогнозната способност не е установена.

**Gramovski Method, MMII — oxidation–reduction potential, microbial metabolism and seismogeochemistry.** A research project by **Hristo Georgiev Gramovski**, initiated in 2026, testing possible relationships between redox dynamics and seismic processes using open data, controls and reproducible analysis. Predictive capability has not been established.

### Научен интерес и сътрудничество / Research interest and collaboration

Приветстваме независими проверки, критични обсъждания и предложения за публични непрекъснати ORP/Eh серии със съпътстващи екологични измервания. Използвайте [Issues](https://github.com/gramovski/-/issues) за въпроси и предложения или pull request за конкретни промени. Прилагайте източник, период, място, единици и ограничения на данните. Публикувайте само информация, която желаете да бъде публична.

Independent validation, critical discussion and suggestions for public continuous ORP/Eh datasets with environmental controls are welcome. Use [Issues](https://github.com/gramovski/-/issues) for questions and proposals, or a pull request for specific changes. Include the source, dates, location, units and data limitations.

---

## Български

### Цел и работна хипотеза

„Метод Грамовски“ е изследователска концепция за проверка на възможна връзка между динамиката на редокс потенциала (ORP/Eh), микробния метаболизъм и сеизмогеохимичните процеси.

Промени в газовите потоци и химичните условия могат да променят микробния метаболизъм и измервания редокс потенциал. Изследват се редокс състояния, преходи, пикове, плато и следпиково поведение. Възможният сеизмичен произход на тези изменения подлежи на проверка.

### MMII

За измерваната редокс серия ε(t) е предложен Microbial Metabolic Instability Indicator:

`v = dε/dt`  
`a = d²ε/dt²`  
`MMII = v · a`

Размерността зависи от единиците на ε и времето. Ако ε е в mV и времето в дни, MMII е в mV²/ден³. Производните се изчисляват само в достатъчно непрекъснати участъци, с описана дискретизация и обработка на шума. Не се прескачат големи паузи в измерванията. ε тук означава редокс сигнал; не е независимо измерване на „ензимна памет“.

### Научен статус

**Прогнозната способност на метода не е установена.** Редокс аномалия или статистическа асоциация сама по себе си не доказва земетръсен предвестник. MMII и суровият ORP/Eh сигнал се оценяват поотделно.

Това хранилище съдържа описание на концепцията, протокол и исторически демонстрационен код. Засега тук няма публикувани сурови научни данни или възпроизводим числен отчет, потвърждаващ прогнозна способност. Старите твърдения за Svartsengi и праговете на Ip не са валидирани прогнози. Кодът Argus не изчислява MMII.

### Съдържание

- [Протокол за проверка / Validation protocol](docs/VALIDATION_PROTOCOL.md)
- [Научен статус и корекции / Scientific status and corrections](docs/SCIENTIFIC_STATUS.md)
- [Исторически Argus код / Historical Argus code](src/argus_legacy.py)
- [Указания за принос / Contributing](CONTRIBUTING.md)
- [Авторска атрибуция / Citation metadata](CITATION.cff)
- [Лиценз / License](LICENSE)

### Авторство

При описване на концепцията използвайте: **„Метод Грамовски — изследователска концепция на Христо Георгиев Грамовски, 2026.“** Атрибуцията не е твърдение за научно потвърждение или удостоверен патентен статут.

## English

### Purpose and working hypothesis

The Gramovski Method is a research concept investigating possible relationships between oxidation–reduction potential (ORP/Eh), microbial metabolism, and seismogeochemical processes.

Changes in gas fluxes and chemical conditions may alter microbial metabolism and measured redox potential. The proposed analysis examines redox states, transitions, peaks, plateaus, and post-peak behavior. A possible seismic origin remains a hypothesis to be tested.

### MMII

For the measured redox series ε(t), the proposed Microbial Metabolic Instability Indicator is:

`v = dε/dt`  
`a = d²ε/dt²`  
`MMII = v · a`

With ε in mV and time in days, MMII has units mV²/day³. Derivatives must be calculated within sufficiently continuous segments, with sampling and noise processing documented. Large measurement gaps must not be bridged. Here ε denotes a redox signal, not an independent measurement of “enzyme memory.”

### Scientific status

**Predictive capability has not been established.** A redox anomaly or statistical association alone does not demonstrate an earthquake precursor. MMII and the raw ORP/Eh signal must be evaluated separately.

This repository contains a concept description, a validation protocol, and historical demonstration code. It currently contains no published raw scientific datasets or reproducible numerical report establishing predictive capability. Historical Svartsengi claims and Ip thresholds are not validated forecasts. Argus does not calculate MMII.

See the linked documents above for the protocol, status, code, contribution guidance, and attribution.

### Author attribution

Use: **“Gramovski Method — a research concept by Hristo Georgiev Gramovski, 2026.”** Attribution does not assert scientific validation or verified patent status.

## Демонстрация / Demonstration

Requires Python 3; no external dependencies:

```bash
python3 src/argus_legacy.py
```

The output is an arbitrary historical score from synthetic inputs, not a probability, earthquake forecast, magnitude estimate, or operational alert.

## Лиценз / License

The MIT notice previously embedded in README is retained as a separate [LICENSE](LICENSE). Copyright and attribution must be preserved.
