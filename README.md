# AI Drone Builder

[English](#english) · [Русский](#русский) · [Қазақша](#қазақша)

AI Drone Builder is a web service that helps users choose compatible parts for a custom drone and plan its assembly. It turns a flight brief into a proposed configuration, a parts specification, and a step-by-step assembly guide. It is designed for hobbyists planning their first quadcopter, experienced builders comparing options, and instructors preparing training builds.

<img width="1280" height="720" alt="Moke_Specification" src="https://github.com/user-attachments/assets/c661f7b8-239d-4ac1-9669-70903f9d349d" />

### What you specify

| Input | What it tells the service |
| --- | --- |
| Aircraft type | The intended layout, such as a quadcopter. |
| Intended use | What the drone is for, such as training, recreational FPV flying, photography, or video. |
| Payload | The mass of any equipment the drone needs to carry in addition to its standard components. |
| Target flight time | How long the drone should fly on one battery under the specified conditions. |
| Maximum takeoff weight (MTOW) | The selected weight limit or class for the complete aircraft, including the battery and payload. |
| Assembly experience | The level of build complexity appropriate for the user. |
| Control mode | The flight behaviour required by the user, such as stabilised control. |

### How component selection works

1. **Set the requirements.** Choose the aircraft type and intended use, then enter the payload, target flight time, weight class, control mode, and assembly experience. Select **Build Drone** to start.
2. **Assess the configuration.** The service considers the requirements together. The payload and flight time affect the choice of propulsion and battery. Those parts also contribute to the total takeoff weight. The control mode guides the choice of flight controller and related equipment.
3. **Match and check the parts.** The service looks for models that meet the required specifications in selected manufacturers’ catalogues. It checks that the parts can be mounted together, that their electrical ratings are compatible, and that the configuration supports the requested control mode.
4. **Review the match.** The result shows the requested parameters alongside the estimated characteristics of the proposed build. If the requirements cannot all be met, the service identifies the limiting requirement. Where a close alternative is available, it shows which parameter would need to change so the user can decide whether to revise the request.

### What you get

- **Build summary.** The intended use, selected control mode, and estimated performance, including projected flight time and takeoff weight.
- **Parts specification.** Recommended models and quantities, relevant specifications, and any compatibility notes. The list covers the frame, motors, propellers, electronic speed controllers (ESCs), flight controller, battery, and other items required by the selected configuration.
- **Step-by-step assembly guide.** The sequence for mounting and connecting the selected parts, setting up the flight controller, and carrying out preflight checks. The guide uses the parts listed in the specification.
- **Downloadable PDF.** A copy of the specification that the user can save or share.

### Example request

A user wants a recreational FPV quadcopter with stabilised control, up to 250 g of payload, and a target flight time of 15 minutes. After the user sets the weight class and assembly experience, the service assesses whether a suitable configuration can meet those requirements together. The results show the selected parts and the estimated flight time for the specified payload. Actual flight time depends on the assembled aircraft, battery condition, and flight conditions.

[Back to languages](#ai-drone-builder)

AI Drone Builder — веб-сервис для подбора совместимых компонентов и планирования сборки дрона. Пользователь задаёт параметры полёта, а сервис предлагает конфигурацию, составляет спецификацию деталей и готовит пошаговую инструкцию по сборке. Сервис рассчитан на тех, кто собирает первый квадрокоптер, опытных сборщиков, сравнивающих варианты, и преподавателей, подбирающих комплектации для обучения.

<img width="1280" height="720" alt="Moke_Specification" src="https://github.com/user-attachments/assets/c661f7b8-239d-4ac1-9669-70903f9d349d" />

### Какие параметры задаёт пользователь

| Параметр | Что он определяет |
| --- | --- |
| Тип аппарата | Схему конструкции, например квадрокоптер. |
| Назначение | Задачу дрона, например обучение, любительские FPV-полёты, фото- или видеосъёмку. |
| Полезная нагрузка | Массу оборудования, которое дрон должен нести дополнительно к штатным компонентам. |
| Целевое время полёта | Сколько дрон должен летать на одном аккумуляторе при заданных условиях. |
| Максимальная взлётная масса (MTOW) | Выбранный предел или класс массы аппарата в сборе с аккумулятором и полезной нагрузкой. |
| Опыт сборки | Какой уровень сложности сборки подходит пользователю. |
| Режим управления | Требуемый режим полёта, например управление со стабилизацией. |

### Как подбираются компоненты

1. **Задайте требования.** Выберите тип и назначение аппарата, затем укажите полезную нагрузку, целевое время полёта, класс взлётной массы, режим управления и опыт сборки. Нажмите **Build Drone**, чтобы запустить подбор.
2. **Получите расчёт конфигурации.** Сервис оценивает требования в совокупности. Полезная нагрузка и время полёта влияют на выбор силовой установки и аккумулятора, а масса этих компонентов входит в общую взлётную массу. Режим управления определяет требования к полётному контроллеру и связанному оборудованию.
3. **Посмотрите, какие детали прошли проверку.** Сервис ищет модели с подходящими характеристиками в каталогах выбранных производителей. Он проверяет возможность совместной установки деталей, их электрическую совместимость и поддержку заданного режима управления.
4. **Сравните результат с запросом.** На экране указаны заданные параметры и расчётные характеристики предлагаемой сборки. Если выполнить все условия одновременно не удаётся, сервис указывает, какое требование ограничивает подбор. При наличии близкого варианта он показывает, какой параметр потребуется изменить.

### Что получает пользователь

- **Сводку по конфигурации.** Назначение аппарата, выбранный режим управления и расчётные характеристики, включая время полёта и взлётную массу.
- **Спецификацию компонентов.** Рекомендованные модели, количество деталей, существенные характеристики и замечания по совместимости. В перечень входят рама, двигатели, пропеллеры, регуляторы оборотов (ESC), полётный контроллер, аккумулятор и другие детали выбранной конфигурации.
- **Пошаговую инструкцию.** Порядок установки и подключения выбранных компонентов, настройки полётного контроллера и предполётных проверок. Инструкция составляется для моделей из спецификации.
- **Спецификацию в PDF.** Файл можно скачать, сохранить или передать другому участнику сборки.

### Пример запроса

Пользователь хочет собрать квадрокоптер для любительских FPV-полётов со стабилизацией, полезной нагрузкой до 250 г и целевым временем полёта 15 минут. После выбора класса взлётной массы и уровня опыта сервис оценивает, можно ли выполнить эти требования одновременно. На экране результатов отображаются подобранные детали и расчётное время полёта с указанной нагрузкой. Фактическое время зависит от собранного аппарата, состояния аккумулятора и условий полёта.

[К выбору языка](#ai-drone-builder)

AI Drone Builder — дронға өзара үйлесімді бөлшектерді таңдауға және оны құрастыруды жоспарлауға көмектесетін веб-сервис. Пайдаланушы ұшу параметрлерін енгізеді, ал сервис лайықты конфигурацияны ұсынып, бөлшектер спецификациясын және құрастыру бойынша қадамдық нұсқаулықты дайындайды. Сервис алғашқы квадрокоптерін құрастыратын әуесқойларға, түрлі нұсқаларды салыстыратын тәжірибелі құрастырушыларға және оқу үшін жинақ таңдайтын оқытушыларға арналған.

<img width="1280" height="720" alt="Moke_Specification" src="https://github.com/user-attachments/assets/c661f7b8-239d-4ac1-9669-70903f9d349d" />

### Пайдаланушы енгізетін параметрлер

| Параметр | Нені анықтайды |
| --- | --- |
| Аппарат түрі | Құрылым түрін, мысалы, квадрокоптер. |
| Қолдану мақсаты | Дронның міндетін, мысалы, оқыту, әуесқойлық FPV ұшулары, фото немесе бейне түсіру. |
| Пайдалы жүк | Дрон негізгі бөлшектерінен бөлек алып жүретін жабдықтың массасын. |
| Межелі ұшу ұзақтығы | Белгіленген жағдайда бір аккумулятормен қанша уақыт ұшу қажет екенін. |
| Ең жоғары ұшып көтерілу массасы (MTOW) | Аккумуляторы мен пайдалы жүгі бар аппараттың таңдалған масса шегін немесе санатын. |
| Құрастыру тәжірибесі | Пайдаланушыға сай құрастыру күрделілігін. |
| Басқару режимі | Қажетті ұшу режимін, мысалы, тұрақтандырылған басқаруды. |

### Бөлшектерді таңдау тәртібі

1. **Талаптарды енгізіңіз.** Аппараттың түрі мен қолдану мақсатын таңдаңыз. Одан кейін пайдалы жүкті, межелі ұшу ұзақтығын, масса санатын, басқару режимін және құрастыру тәжірибеңізді көрсетіңіз. Іріктеуді бастау үшін **Build Drone** түймесін басыңыз.
2. **Конфигурацияның есептік сипаттамаларын алыңыз.** Сервис талаптарды бірге қарастырады. Пайдалы жүк пен ұшу ұзақтығы күш қондырғысы мен аккумуляторды таңдауға әсер етеді. Бұл бөлшектердің массасы аппараттың ұшып көтерілу массасына кіреді. Басқару режимі ұшу контроллеріне және оған қатысты жабдыққа қойылатын талаптарды анықтайды.
3. **Үйлесімділігі тексерілген бөлшектерді қараңыз.** Сервис таңдалған өндірушілердің каталогтарынан сипаттамалары сәйкес модельдерді іздейді. Ол бөлшектерді бірге орнату мүмкіндігін, олардың электрлік үйлесімділігін және қажетті басқару режимін қолдайтынын тексереді.
4. **Нәтижені бастапқы талаптармен салыстырыңыз.** Нәтиже экранында енгізілген параметрлер мен ұсынылған конфигурацияның есептік сипаттамалары көрсетіледі. Барлық шартты бір мезгілде орындау мүмкін болмаса, сервис іріктеуді шектеген талапты көрсетеді. Жақын балама табылса, оны таңдау үшін қай параметрді өзгерту қажет екенін түсіндіреді.

### Пайдаланушы алатын нәтиже

- **Конфигурацияның қысқаша сипаттамасы.** Аппараттың мақсаты, таңдалған басқару режимі, есептік ұшу ұзақтығы мен ұшып көтерілу массасы көрсетіледі.
- **Бөлшектер спецификациясы.** Ұсынылған модельдер, бөлшектер саны, маңызды сипаттамалары және үйлесімділік туралы ескертпелер. Тізімге рама, қозғалтқыштар, пропеллерлер, айналым жиілігін реттегіштер (ESC), ұшу контроллері, аккумулятор және таңдалған конфигурацияға қажетті басқа бөлшектер кіреді.
- **Қадамдық нұсқаулық.** Бөлшектерді орнату мен жалғау, ұшу контроллерін баптау және ұшар алдындағы тексерулердің реті. Нұсқаулық спецификациядағы модельдерге арналып дайындалады.
- **PDF форматындағы спецификация.** Файлды жүктеп алуға, сақтауға немесе құрастыруға қатысатын басқа адамға жіберуге болады.

### Сұрау мысалы

Пайдаланушы әуесқойлық FPV ұшуларына арналған, тұрақтандыру режимі бар квадрокоптер құрастырғысы келеді. Пайдалы жүк 250 г-ға дейін, ал межелі ұшу ұзақтығы 15 минут. Пайдаланушы масса санаты мен тәжірибе деңгейін көрсеткеннен кейін, сервис осы талаптардың бәріне сай конфигурацияны іздейді. Нәтиже экранында таңдалған бөлшектер мен көрсетілген жүкпен ұшудың есептік ұзақтығы беріледі. Нақты ұшу ұзақтығы құрастырылған аппаратқа, аккумулятордың күйіне және ұшу жағдайына байланысты.

[Тіл таңдауға оралу](#ai-drone-builder)
