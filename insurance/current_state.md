## Ретроспектива

Страховые актуарии давно опирались на факторы, извлекаемые из данных, для оценок страховых рисков. Основной стат. метод: GLM (обобщённые страховые модели) [19], под это и приобретались инструменты для оценок: решения от SAS.

## Текущее состояние

Типовые бизнес-задачи:
- привлечение через хорошее предложение,
- урегулирование рисков,
- выявление мошенничества.

Бизнес-задачи сейчас решаются не столь точно, как кажется, могли бы, учитывая доступные массивы данных и современные DS-инструменты. Ключ к близкому успеху, вероятно, лежит через оптимизацию/замену имеющихся процедур оценок. 

## Перспективы

Публичной информации об эффекте применения ML в страховании - мало при первом рассмотрении (поиск по ключевым словам, просмотр статей, документов). Либо надо искать по другому, либо успехи пока не публикуются.

![The benefits of big data analytics (BDA) for insurers](https://miro.medium.com/max/1400/1*lEg2GcRBfa8bpitFusfeuw.png)

В России развитие практик DS в страховом бизнесе затруднено малым объёмом рынка страхования, что теоретически должно задавать высокую конкуренцию между участниками рынка и вынуждать их искать пути повышения эффективности.

Перспективные задачм:
- предотвращение рисков (подсказка как их избежать: своевременный визит к врачу, выбор дорожного маршрута, стиля вождения),
- автоматизация трудоёмких задач (обработка фото),
- паритетная интеграция с другими компаниями (например, с банками, медицинскими).

Форум [3] содержит в программе панельную дискуссию (одну из ~десяти) "Искусственный интеллект: что полезного могут взять себе страховщики и какие ограничители должны поставить". Интерес пока видится не столь ярко выраженным, как, например, у банков.

Форум [4] рассматривает добродетель цифровых технологий пока под вопросами:
- "Как изменятся роль и значение цифровых технологий для страхового рынка и для страховщиков в новых условиях."
- "Цифровые технологии в страховании - универсальный инструмент обеспечения стрессоустойчивости или источник и зона повышенных рисков?"

При этом (для медицины) использование даже простых алгоритмов машинного обучения показывает перспективные результаты [5].

В [8] есть статья, которая кажется не нашла выгод ML при его применении "в лоб" (стоит перечитать детальнее).

"We need a third generation of underwriting platforms…essentially an underwriting-tailored big data platform." [13]

"CLARA products utilise AI and advanced machine learning to deliver insights aimed at helping commercial insurers increase efficiency and make data-driven decisions that substantially improve operations as well as client service." [17]

"The new system is based on the AI smart claims credit model built with technologies such as image damage assessment, OCR (optical character recognition) bills identification, and biometrics, which help simplify claims procedures, Ping An said." [18]

![H2O, Insurance Use-Cases and Customers](https://h2o.ai/solutions/industry/insurance/_jcr_content/root/container/section_2045013565/par/image.coreimg.png/1653599716826/financial-services-15.png)

## Заключение

При хороших масштабах даже небольшой эффект может быть заметным. DS, как подход хорошо зарекомендовавший себя в других областях, интересен и в страховании. И, важнее того, будет накапливаться опыт применения DS для тех задач будущего, когда без него уже не получится обойтись.

Практика только формируется, по крайней мере, как это видно в публичном поле даже на мировом уровне. Вероятно, страховые компании здесь идут вслед за банками.

Большой потенциал видят в использовании IoT (машины, медицина), обмене данными. Отмечают, что использование AI может принести новые риски. [21]

## Ссылки

1. [Умный полис. Как машинное бучение изменит рынок страхования, 2017)](https://www.forbes.ru/biznes/355131-umnyy-polis-kak-mashinnoe-obuchenie-izmenit-rynok-strahovaniya])
2. [Искусственный интеллект в страховании: чем он может быть полезен, 2020](https://hightech.plus/2020/09/22/iskusstvennii-intellekt-v-strahovanii-chem-on-mozhet-bit-polezen)
3. [Форум лидеров страхового рынка, 2021](https://insfuture.ru/?rs=article_insfuture2019_asn_zetta-interview#programm).
4. [InnoIns-2022](https://www.insur-info.ru/InnoIns/).
5. [Машинное обучение для страховой компании: Исследуем алгоритмы, 2017](https://habr.com/ru/company/microsoft/blog/331484/)
6. [McKinsey, Insurance 2030](https://www.mckinsey.com/industries/financial-services/our-insights/insurance-2030-the-impact-of-ai-on-the-future-of-insurance)
7. [Eight use cases for machine learning in insurance](https://azure.microsoft.com/es-es/blog/eight-use-cases-for-machine-learning-in-insurance/)
8. [Machine Learning in Insurance, 2020](https://doi.org/10.3390/books978-3-03936-448-0)
9. [Google Scholar Search: "Machine Learning in Insurance"](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Machine+Learning+in+Insurance&btnG=)
10. [The Impact of Machine Learning on the Future of Insurance Industry, 2020](https://doi.org/10.18034/ajtp.v7i3.537)
11. [Machine Learning | Insurance Blog | Accenture](https://insuranceblog.accenture.com/tag/machine-learning)
12. [Accenture, Machine Learning in Insureance](https://www.accenture.com/_acnmedia/pdf-84/accenture-machine-leaning-insurance.pdf)
13. [5 predictions for the insurance industry in 2022](https://insuranceblog.accenture.com/5-predictions-insurance-industry-2022)
14. [H2O, Insurance](https://h2o.ai/solutions/industry/insurance/)
15. [Top 10 Insurance Companies by the Metrics](https://www.investopedia.com/articles/active-trading/111314/top-10-insurance-companies-metrics.asp)
16. [How Ping An, an insurer, became a fintech super-app, 2020](https://www.economist.com/finance-and-economics/2020/12/03/how-ping-an-an-insurer-became-a-fintech-super-app)
17. [Berkshire Hathaway unit looks to AI with CLARA analytics deal, 2020](https://www.reinsurancene.ws/berkshire-hathaway-unit-looks-to-ai-with-clara-analytics-deal/)
18. [China’s Ping An P&C Unveils Credit-Based Smart Auto Insurance Claim Solution](https://www.insurancejournal.com/news/international/2019/01/30/516134.htm)
19. [Application of Statistical Techniques in Group Insurance, 2016](https://actuaries.asn.au/Library/Events/FSF/2016/4cTiohEtAlInsurance.pdf)
20. [European insurance industry, Statistics](https://www.insuranceeurope.eu/statistics)
21. [European insurance industry, Annual Report 2021-2022](https://www.insuranceeurope.eu/mediaitem/dc5e32af-f76e-4b8d-bb6d-60ed929815cf/Annual%20Report%202021-2022.pdf)
22. [Machine Learning at Insurers, 2020](https://towardsdatascience.com/machine-learning-at-insurance-companies-2ac7ad109c65)
23. [Обзор страховщиков, использующих искусственный интеллект и машинное обучение, 2019](https://www.asn-news.ru/news/72013)