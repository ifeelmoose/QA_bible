<img align="center" src="https://habrastorage.org/webt/un/ke/6d/unke6dmjxotrhtuqkkmppy88hqy.jpeg" />

Библия QA это 200++ страниц обновляемой смеси ответов на вопросы с реальных собеседований на QA, перевода интересного контента с зарубежных ресурсов и агрегации материала с отечественных. Уже на начальной стадии имеет несколько тысяч уникальных просмотров репозитория и огромный положительный фидбэк от коммьюнити, что даёт некоторые гарантии для сомневающихся, доверять ли этому материалу или контрибьютить ли сюда.
<cut />

<spoiler title="Disclaimer, очень важно прочитать!">
ВНИМАНИЕ! Для того, чтобы увидеть материал целиком, нужно открыть первую или вторую часть в файлах (Manual part 1 или 2). Пришлось их разбить ввиду ограничения на размер одного файла в 1 мб.<br>
В первую очередь хочу подчеркнуть, что в данный момент этот материал от джуна – джунам, от intermediate – таким же, но будет полезен всем грейдам, тем более что часть материала далеко не начального уровня. Качество материала (особенно перевода) будет улучшаться по мере вычитки и вклада сообщества. 
Что касается источников и ресурсов, то список не полный. В первоначальном конспекте для себя я не сохранял ссылки, так что, если увидели авторский контент, прошу не ругаться, напишите - добавлю в источники. Список полезных ресурсов я не пытался сделать всеобъемлющим, а лишь указал те, что пригодились лично мне, на самом деле их в разы больше.
Также отмечу, что и сам материал пока что далеко не всеобъемлющий. Предполагается, что это некий гибрид ответов на вопросы и базовой теории и здесь темы раскрыты в той мере, что требуется на собеседовании. То есть ориентир и какая-то база есть, но при необходимости копаете дальше уже сами. Каждый термин, каждая тема представляется мне как трехмерный объект и не всегда можно достичь понимания, глядя в лоб (один источник). Порой требуется посмотреть под разными углами (в разных источниках).<br>
Если есть что исправить или дополнить – пишите в tg @VA610/создавайте issue/форкайте и коммитьте! Любые замечания, любые запросы на недостающие темы постараюсь обработать как можно скорее! <br>
</spoiler>
<spoiler title="Оглавление">
<hr>
<h1 align="center">Оглавление</h1>
<hr>
<h2 align="center">Manual part 1 </h2>	
<hr>	
<h3 align="center">HR-часть</h3>
<ul>
		<li>Вопросы с реальных собеседований с этапа HR</li>
</ul>
<h3 align="center">Общее о тестировании</h3>
<ul>	
		<li>Что означает тестирование ПО?</li>
		<li>Почему требуется тестирование ПО?</li>
		<li>Что означает обеспечение качества (Quality Assurance - QA) при тестировании ПО?</li>
		<li>Что означает контроль качества (Quality Control - QC) при тестировании ПО?</li>
		<li>Что означает качество ПО? (Software Quality)</li>
		<li>Объясните отличия в QA, QC и тестировании</li>
		<li>Что означает Verification при тестировании ПО?</li>
		<li>Что означает Validation в тестировании ПО?</li>
		<li>Разница между Design Verification и Design Validation?</li>
		<li>Принципы тестирования?</li>
		<li>Критерии выбора тестов?</li>
		<li>Что подразумевается под тестовым покрытием? (Test Coverage)</li>
		<li>Что такое модель зрелости тестирования (TMM - Test Maturity Model)?</li>
		<li>Что такое CMM?</li>
		<li>Что такое тестирование со сдвигом влево? (Shift left testing)</li>
		<li>Что такое независимое тестирование? (Independent testing)</li>
		<li>В чем разница между превентивным и реактивным подходами в тестировании? (Preventative and Reactive approaches)</li>
		<li>Перечислите типичные возможные обязанности инженера по обеспечению качества?</li>
		<li>Что такое аудит качества?</li>
		<li>Почему тестирование делится на отдельные этапы?</li>
		<li>Почему невозможно полностью протестировать ПО?</li>
		<li>Как вы тестируете продукт, если требования еще не зафиксированы?</li>
		<li>Как вы узнаете, было ли создано достаточно тестов для тестирования продукта?</li>
		<li>Как вы понимаете инспекцию?</li>
		<li>Какие есть роли/должности в команде?</li>
		<li>Опишите жизненный цикл продукта по этапам - какие участники на каждом этапе, какие у них роли? Какие артефакты на каждом этапе?</li>
		<li>Кто такой SDET?</li>
		<li>Что такое тестирование как сервис? (TaaS – testing as a Service)</li>
		<li>Что подразумевается под тестовой средой? (Test Environment/Test Bed)</li>
		<li>Что подразумевается под тестовыми данными?</li>
		<li>Основные фазы тестирования?</li>
		<li>Подробнее про бета-тестирование?</li>
		<li>Что означает пилотное тестирование? (Pilot)</li>
		<li>В чем отличие build от release?</li>
		<li>Что такое бизнес – логика (domain)?</li>
		<li>Ты – единственный тестировщик на проекте. Что делать?</li>
		<li>Основные инструменты тестировщика?</li>
</ul>
<h3 align="center">Виды тестирования</h3>
<ul>	
		<li>Какие существуют основные виды тестирования ПО?</li>
		<li>Типы тестирования? (White/Black/Grey Box)</li>
		<li>Что означает тестирование черного ящика?</li>
		<li>Что означает тестирование белого ящика?</li>
		<li>Что означает тестирование серого ящика? (Grey box)</li>
		<li>Основные отличия White/grey/black box?</li>
		<li>Что такое деструктивное/разрушающее/негативное тестирование? (DT - Destructive testing)</li>
		<li>Что такое недеструктивное/неразрушающее/позитивное тестирование? (NDT – Non Destructive testing)</li>
		<li>Что такое пирамида/уровни тестирования? (Testing Levels)</li>
		<li>Что подразумевается под компонентным/модульным/юнит тестированием? (Component/Module/Unit testing)</li>
		<li>Что подразумевается под интеграционным тестированием? (Integration testing)</li>
		<li>Разница между Unit testing и Integration testing?</li>
		<li>Что такое системное интеграционное тестирование? (SIT - System Integration testing)</li>
		<li>Что подразумевается под инкрементальным подходом? (Incremental Approach)</li>
		<li>Что подразумевается под подходом снизу-вверх? (Bottom-Up Approach)</li>
		<li>Что подразумевается под подходом сверху-вниз? (Top-Down Approach)</li>
		<li>Что подразумевается под гибридным/сэндвич-подходом? (Sandwich Approach)</li>
		<li>Что подразумевается под подходом Большого взрыва?  (Big Bang Approach)</li>
		<li>В чем разница между тест-драйвером и тест-заглушкой? (Test Driver and Test Stub)</li>
		<li>Что подразумевается под системным тестированием?</li>
		<li>Можем ли мы провести системное тестирование на любом этапе?</li>
		<li>Что такое функциональное тестирование?</li>
		<li>Что такое тестирование совместимости/взаимодействия? (Compatibility/Interoperability testing)</li>
		<li>Что такое тестирование на соответствие? (Conformance/Compilance testing)</li>
		<li>Что такое нефункциональное тестирование?</li>
		<li>Основные понятия в тестировании производительности?</li>
		<li>Тестирование производительности клиентской части и серверной, в чем разница?</li>
		<li>В общем виде что такое тестирование производительности?</li>
		<li>Что такое тестирование емкости/способностей? (Capacity)</li>
		<li>Что означает тестирование масштабируемости? (Scalability)</li>
		<li>Разница между тестированием ёмкости/способностей и тестированием масштабируемости? (Capacity vs Scalability)</li>
		<li>Расскажите о стрессовом тестировании? (Stress testing)</li>
		<li>Расскажите о нагрузочном тестировании? (Load)</li>
		<li>Что такое объемное тестирование? (Volume testing)</li>
		<li>Тестирование выносливости/стабильности/надежности (Soak/Endurance/Stability/Reliability testing)</li>
		<li>Что такое спайк/шиповое тестирование? (Spike)</li>
		<li>Что такое тестирование устойчивости? (Resilence)</li>
		<li>Что такое тестирование времени отклика? (Response time testing)</li>
		<li>Что такое Ramp тестирование?</li>
		<li>Что такое тестирование хранилища? (Storage testing)</li>
		<li>Что такое тестирование на отказ и восстановление? (Failover and Recovery testing)</li>
		<li>Что вы знаете о Тестировании удобства пользования? (Usability testing)</li>
		<li>Отличия тестирование на удобство пользования и тестирования доступности? (Usability Vs. Accessibility testing)</li>
		<li>Что такое тестирование интерфейса? (UI testing)</li>
		<li>Что такое тестирование рабочего процесса/воркфлоу? (Workflow testing)</li>
		<li>Что вы знаете о пользовательском приемочном тестировании? (UAT – User Acceptance testing)</li>
		<li>Что такое эксплуатационное приемочное тестирование? (OAT - Operational Acceptance testing)</li>
		<li>Расскажите об инсталляционном тестировании?</li>
		<li>Что вы знаете о тестировании безопасности? (Security and Access Control testing)</li>
		<li>Что означает оценка уязвимости/защищенности? (Vulnerability Assessment)</li>
		<li>Расскажите подробнее о тестировании на проникновение? (Penetration testing)</li>
		<li>Отличия Vulnerability Assessment от Penetration testing?</li>
		<li>Что такое Fuzz тестирование?</li>
		<li>Можно ли отнести тестирование безопасности или нагрузочное тестирование к функциональным видам тестирования?</li>
		<li>Что вы знаете о конфигурационном тестировании? (Configuration testing)</li>
		<li>Что вы знаете про регрессионное тестирование? (Regression testing)</li>	
		<li>Типы регрессии по Канеру?</li>
		<li>Что подразумевается под проверкой дыма/дымовым тестированием? (Smoke testing)</li>
		<li>Что такое тестирование встряхиванием? (Shake out testing)</li>
		<li>Что подразумевается под санитарным тестированием/согласованности/исправности? (Sanity testing)</li>
		<li>Отличие санитарного тестирования от дымового? (Sanity vs Smoke testing)</li>
		<li>В чем разница между повторным и регрессионным тестированием?</li>
		<li>Объясните, что такое тестирование N+1?</li>
		<li>Что означает подтверждающее тестирование? (confirmation/re-testing)</li>	
		<li>Что вы знаете о тестировании сборки? (Build Verification Test)</li>
		<li>Что такое тестирование файлов cookie?</li>
		<li>Что такое тестирование потоков? (Thread testing)</li>
		<li>Что такое тестирование документации? (Documentation testing)</li>
		<li>Какие вы знаете уровни тестирования данных?</li>
		<li>Что такое подкожный тест? (Subcutaneous test)</li>
		<li>Расскажите о локализации, глобализации и интернационализации? (Localization/ globalization/internationalization testing)</li>
		<li>Что такое исследовательское тестирование? (Exploratory testing)</li>
		<li>Что вы знаете о турах Виттакера в исследовательском тестировании?</li>
		<li>Что такое Свободное или Интуитивное тестирование? (Adhoc)</li>
		<li>Что вы знаете о мутационном тестировании? (Mutation testing)</li>
		<li>Что означает механизм тестирования по ключевым словам? (Keyword Driven testing Framework)</li>
		<li>Что вы знаете о тестировании интерфейса прикладного программирования (API - Application Programming Interface)?</li>
		<li>Как протестировать API без документации/черным ящиком?</li>
		<li>А что такое endpoint?</li>
		<li>Frontend testing Vs. Backend testing?</li>
		<li>Что подразумевают под эталонным тестированием? (Baseline testing)</li>
		<li>В чем разница между Baseline и Benchmark testing?</li>
		<li>Что такое параллельное/многопользовательское тестирование? (Concurrency/Multi-user testing)</li>
		<li>Как вы думаете, что такое тестирование на переносимость?</li>
		<li>Что такое тестирование графического интерфейса/визуальное тестирование? (GUI - Graphical User Interface)</li>
		<li>Что такое A/B тестирование?</li>
		<li>Что означает сквозное тестирование? (E2E - End–to–End)</li>
		<li>В чем разница между E2E и системным тестированием?</li>
		<li>Что такое параллельное тестирование? (Parallel testing)</li>
</ul>
<h3 align="center">Тест дизайн</h3>
<ul>
		<li>Тест дизайн? (Test Design)</li>
		<li>Перечислите известные техники тест-дизайна?</li>
		<li>Что такое статическое тестирование, когда оно начинается и что оно охватывает?</li>
		<li>Что такое динамическое тестирование, когда оно начинается и что оно охватывает?</li>
		<li>Какие виды Review вы знаете?</li>
		<li>Что вы знаете о Data Flow testing?</li>
		<li>Что вы знаете о Control Flow testing?</li>
		<li>Что такое Loop coverage?</li>
		<li>Что такое Race coverage?</li>
		<li>Тестирование пути и тестирование базового пути? (Path testing & Basis Path testing)</li>
		<li>Что вы знаете о Statement coverage?</li>
		<li>Что вы знаете о Decision coverage?</li>
		<li>Что вы знаете о Branch coverage?</li>
		<li>Что вы знаете о Condition coverage?</li>
		<li>Что вы знаете о FSM coverage?</li>
		<li>Что такое Function coverage?</li>
		<li>Что такое Call coverage?</li>
		<li>Что означает LCSAJ coverage?</li>
		<li>Сравнение некоторых метрик</li>
		<li>Что такое Equivalence Partitioning?</li>
		<li>Что такое Boundary Value Analysis?</li>
		<li>Что такое Error Guessing?</li>
		<li>Что такое Cause/Effect?</li>
		<li>Что такое Exhaustive testing?</li>
		<li>Какие вы знаете комбинаторные техники тест-дизайна?</li>
		<li>Что такое тестирование ортогональных массивов? (OAT - Orthogonal Array testing)</li>
		<li>Что такое Domain analysis/testing?</li>
		<li>Что такое Cyclomatic Complexity в тестировании ПО?</li>
		<li>Что такое State Transition testing?</li>
		<li>Что такое Scenario (use case) testing?</li>
		<li>Что такое Decision Table testing?</li>
		<li>Что такое Random testing?</li>
		<li>Что такое Syntax testing?</li>
		<li>Что вы знаете о Classification tree method?</li>
		<li>Как мы узнаем, что код соответствует спецификациям?</li>
		<li>Что включает в себя матрица отслеживания требований? (RTM - Requirement Traceability Matrix)</li>
		<li>В чем разница между Test matrix и Traceability matrix?</li>
		<li>Что такое анализ GAP?</li>
		<li>Что такое граф причинно-следственных связей? (Cause Effect Graph)</li>
		<li>В чем разница между предугадыванием ошибок и посевом? (Error guessing and error seeding)</li>
		<li>Стили тестов?</li>
		<li>Техники тестирования требований?</li>
		<li>Что такое эвристики?</li>
</ul>
<h3 align="center">Тестовые артефакты и документация (Test Deliverables/TestWare/test artifacts)</h3>
<ul>
		<li>Виды тестовой документации?</li>
		<li>Отличия Test Suite от Test Scenario?</li>
		<li>Какие отличия у плана тестирования и стратегии тестирования?</li>
		<li>Виды тест планов?</li>
		<li>Что является основой для подготовки плана приемки? (PAP - Product Acceptance Plan)</li>
		<li>В чем разница между тест-кейсом и чек-листом?</li>
		<li>В чем разница между тест-кейсами высокого уровня и низкого уровня?</li>
		<li>Чем Test case отличается от сценария тестирования?</li>
		<li>Что такое тест-анализ/основа теста? (Test Analysis/Test Basis)</li>
		<li>Что такое документ бизнес-требований (BRD)?</li>
		<li>Что вы знаете о требованиях (уровни/виды и т. д.)?</li>
		<li>Рассажите, какие есть требования к самим требованиям?</li>
</ul>
<hr>
<h2 align="center">Manual part 2</h2>
<hr>
<h3 align="center">Дефекты и ошибки</h3>
<ul>
		<li>Что такое дефект?</li>
		<li>Классы дефектов?</li>
		<li>Какие есть категории дефектов?</li>
		<li>Error/Mistake/Defect/Bug/Failure/Fault?</li>
		<li>Каково содержание эффективного сообщения об ошибке?</li>
		<li>Несколько ключевых моментов, которые следует учитывать при написании отчета об ошибке?</li>
		<li>Серьезность и Приоритет Дефекта (Severity & Priority)</li>
		<li>Может ли быть высокий severity и низкий priority? А наоборот?</li>
		<li>Жизненный цикл дефекта?</li>
		<li>Пришёл баг из продакшена, что делаем?</li>
		<li>Что такое утечка дефектов и релиз бага? (Bug Leackage & Bug Release)</li>
		<li>Что означает плотность дефектов при тестировании ПО?</li>
		<li>Что означает процент обнаружения дефектов при тестировании ПО?</li>
		<li>Что означает эффективность устранения дефектов при тестировании ПО? (DRP)</li>
		<li>Что означает эффективность Test case в тестировании ПО? (TCE)</li>
		<li>Возраст дефекта в тестировании ПО?</li>
		<li>Что такое принцип Парето в тестировании ПО?</li>
		<li>Каковы различные способы применения принципа Парето в тестировании ПО?</li>
		<li>В чем основное отличие отладки от тестирования? (Debugging Vs. Testing)</li>
		<li>Почему в программном обеспечении есть ошибки?</li>
		<li>Что вы будете делать, если во время тестирования появится ошибка?</li>
		<li>Как вы справляетесь с невоспроизводимой ошибкой?</li>
		<li>Если продукт находится в производстве и один из его модулей обновляется, то необходимо ли провести повторную проверку?</li>
		<li>Что такое анализ рисков?</li>
		<li>В чем разница между coupling и cohesion?</li>
		<li>Что такое скрытый дефект? (Latent defect)</li>
		<li>Что такое маскировка ошибок, объясните примером?</li>
		<li>Категории отладки? (Debugging)</li>
		<li>Что такое Эффективность удаления дефектов? (DRE - Defect Removal Efficiency)</li>
		<li>Что такое сортировка дефектов? (Bug triage)</li>
</ul>
<h3 align="center">SDLC и STLC</h3>
<ul>
		<li>Что вы знаете о жизненном цикле разработки ПО? (SDLC - Software Development Lifecycle)</li>
		<li>Что такое цикл/колесо Деминга? (Deming circle/cycle/wheel)</li>
		<li>Модели разработки ПО?</li>
		<li>Что такое Agile?</li>
		<li>Что такое Scrum?</li>
		<li>В чем отличие Canban от scrum?</li>
		<li>Что знаете о User stories в гибких подходах к разработке?</li>
		<li>Что значит жизненный цикл тестирования ПО? (STLC – Software Testing Lifecycle)</li>
		<li>Что вы знаете о техниках оценки теста? (Test Estimation)</li>
		<li>В чем разница между SDLC и STLC?</li>
		<li>Что такое быстрая разработка приложений? (RAD - Rapid Application Development)</li>
		<li>Что такое разработка через тестирование (TDD - Test Driven Development)?</li>
		<li>TDD в Agile Model Driven Development (AMDD)</li>
		<li>Тестирование на основе моделей (MDD - Model-driven Development)</li>
		<li>Тестирование на основе данных (DDT - Data Driven testing)</li>
		<li>Тестирование на основе риска (RBT - Risk Based Testing)</li>
		<li>Что вы знаете о потоковом тестировании? (BFT — BusinessFlowTesting)</li>
</ul>
<h3 align="center">Тестирование в разных сферах/областях (testing different domains)</h3>
<ul>
		<li>Что такое веб-тестирование и как его производить?</li>
		<li>Тестирование банковского ПО</li>
		<li>Тестирование электронной коммерции (eCommerce)</li>
		<li>Тестирование платежного шлюза (Payment Gateway)</li>
		<li>Тестирование систем розничной торговли (POS - Point Of Sale)</li>
		<li>Тестирование в сфере страхования (Insurance)</li>
		<li>Тестирование в сфере телекоммуникаций (Telecom)</li>
		<li>Тестирование протокола: L2 и L3 OSI</li>
		<li>Тестирование интернета вещей (IoT - Internet of Things)</li>
		<li>Что такое облачное тестирование? (Cloud testing)</li>
		<li>Что такое тестирование сервис-ориентированной архитектуры? (SOA - Service Oriented Architecture)</li>
		<li>Что такое тестирование планирования ресурсов предприятия? (ERP - Enterprise Resource Planning)</li>
		<li>Тестирование качества видеосвязи WebRTC-based сервиса видеоконференций</li>
		<li>Что такое тестирование ETL?</li>
</ul>
<h3 align="center">Мобильное тестирование</h3>
<ul>
		<li>Каковы особенности в тестировании мобильных приложений? В чем отличия тестирования мобильного приложения от десктопного?</li>
		<li>В чем отличия тестирования мобильного приложения от web?</li>
		<li>Что вы знаете о симуляторах и эмуляторах?</li>
		<li>Типы мобильных приложений?</li>
		<li>Что основное проверить при тестировании мобильного приложения?</li>
		<li>Последнее обновление Android/iOS, что нового?</li>
		<li>Основные различия iOS и Android?</li>
		<li>Виды жестов и т.п.?</li>
		<li>Как проверить использование процессора на мобильных устройствах?</li>
		<li>Объясните критические ошибки, с которыми вы сталкиваетесь при тестировании на мобильных устройствах или в приложениях?</li>
</ul>
<h3 align="center">Сети и около них</h3>
<ul>
		<li>Что такое http?</li>
		<li>Компоненты HTTP?</li>
		<li>Методы HTTP-запроса?</li>
		<li>Что такое ресурс?</li>
		<li>Что такое веб-сервис? (WS - Web service)</li>
		<li>Отличие сервиса от сервера?</li>
		<li>Отличие сервиса от веб-сайта?</li>
		<li>Что такое REST, SOAP? В чем отличия?</li>
		<li>Что такое JSON, XML?</li>
		<li>Коды ответов/состояния сервера с примерами? (HTTP status code)</li>
		<li>Почему ошибка 404 относится к 4** - клиентской, если по идее должна быть 5**?</li>
		<li>Какие еще бывают протоколы?</li>
		<li>TCP/IP это?</li>
		<li>Что такое куки (cookies)?</li>
		<li>Разница между cookie и сессией/сеансом?</li>
		<li>Отличие stateless и stateful?</li>
		<li>Различия методов GET и POST?</li>
		<li>Клиент - серверная архитектура?</li>
		<li>Уровни OSI?</li>
		<li>Что вы подразумеваете под потоковыми медиа? (Streaming media)</li>
		<li>Основные команды Linux?</li>
		<li>Почему важно тестировать в разных браузерах?</li>
		<li>Адаптивный веб-дизайн vs. Отзывчивый веб-дизайн, в чем разница? (Adaptive Vs. Responsive)</li>
		<li>Как сервер узнаёт, с какого типа устройства/браузера/ОС/языка вы открываете веб-сайт? (Например, для Adaptive design)</li>
		<li>Чем отличается авторизация от аутентификации?</li>
		<li>Как работает авторизация/аутентификация? Как сайт понимает, что ты залогинен?</li>
		<li>Почему важно делать подтверждение e-mail при регистрации?</li>
		<li>Что такое кэш и зачем его очищать при тестировании?</li>
		<li>Что такое AJAX в вебе?</li>
		<li>Как работает браузер (коротко)?</li>
		<li>Как работает сотовая связь?</li>
		<li>Как работает подключение к Wi-Fi?</li>
</ul>
<h3 align="center">Базы данных</h3>
<ul>
		<li>Может ли у ПО быть сразу несколько баз данных?</li>
		<li>Что такое SQL?</li>
		<li>Что вы знаете о NoSQL?</li>
		<li>Что такое нормальные формы?</li>
		<li>Понятие хранимой процедуры?</li>
		<li>Понятие триггера?</li>
		<li>Что такое индексы? (Indexes)</li>
		<li>Какие шаги выполняет тестер при тестировании хранимых процедур?</li>
		<li>Как бы вы узнали для тестирования базы данных, сработал триггер или нет?</li>
		<li>Как тестировать загрузку данных при тестировании базы данных?</li>
		<li>Основные команды SQL?</li>
		<li>Подробнее о джойнах? (Join)</li>
		<li>Типы данных в SQL?</li>
</ul>
<h3 align="center">ПРАКТИКА</h3>
<ul>
		<li>Дана форма для регистрации. Протестируйте.</li>
		<li>Определение серьезности и приоритета</li>
		<li>Определение граничных значений и классов эквивалентности</li>
		<li>Логические задачи</li>
		<li>Еще примеры</li>
		<li>Набор небольших задач по SQL</li>
		<li>Тестирование чашки для кофе</li>
		<li>HR: Как вы будете решать конфликты между членами вашей команды?</li>
		<li>HR: Что делать, если разработчик утверждает, что найденный дефект таковым не является?</li>
		<li>Вот тебе комп и работающий сайт. Сделай мне 401-ю ошибку.</li>
</ul>
<h3 align="center">С чего начать абсолютному новичку?</h3>
<ul>
		<li>Путь</li>
		<li>CV</li>
		<li>Собеседование</li>
		<li>Ошибки в работе у начинающих тестировщиков</li>
</ul>
<h3 align="center">Полезное</h3>
<ul>
		<li>Youtube-каналы</li>
		<li>Telegram</li>
		<li>Web</li>
		<li>Книги</li>
		<li>Курсы</li>
</ul>
<h3 align="center">Источники</h3>
</spoiler>
