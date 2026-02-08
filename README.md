<a name="russian"></a>
[🇺🇸 Read in English](#english) | [🇷🇺 Читать на русском](#russian)

---


![Project Orbitus Banner](1770297254520.png)

# S.M.L.A.S. (Static Magnetic Lattice Array System)

**S.M.L.A.S.** — это концепция системы пассивной магнитной левитации, решающая фундаментальную проблему нестабильности через создание **дискретной силовой среды**. Проект доказывает возможность стабильного зависания (обход теоремы Ирншоу) без использования активной электроники.

---

## 1. Архитектура активного пола (The Stator Floor)
В основе лежит отказ от единого магнитного поля в пользу матрицы независимых «магнитных фонтанчиков».
*  **Изоляция зазорами:** Между шестигранными ячейками выдержан  зазор в **15 мм**(может достигать соотношения 1 к 1 по отношению к магниту!зависит от толщины т-стали! важно найти баланс). Это исключает слияние магнитных потоков в общую «горку», с которой платформа бы неизбежно соскальзывала.
* **Форм-фактор «Столб»:** Высота магнитов N52H рассчитана на компенсацию массы платформы, обеспечивая баланс сил 1:1.
* **Фокусировка Т-сталью:**
  ![Project Orbitus Banner](IMG_20260206_120714.png)
* Каждый столбик изолирован трансформаторной сталью 3408 по бокам. Она экранирует боковое рассеивание и направляет энергию вертикально, создавая эффект «магнитного луча».
* **Монолитизация:** Матрица зафиксирована в диэлектрическом основании (полимер/эпоксидная смола).

![Схема ячейки статора](1770367790967.png)


![Сравнение конфигураций поля](1770299361814.png)
*Справа (B) — реализованная система: сфокусированные лучи без паразитного взаимодействия.*

Важное дополнение!
​Активная поверхность пола представлена на схемах лишь частично, однако в реальности она может охватывать всё пространство большой комнаты. Проект является полностью масштабируемым. Стоит отметить, что в процессе разработки концепции Текущая итерация проекта включает использование Т-стали, однако её необходимость в основании платформы подлежит дальнейшей оптимизации!Для обеспечения ровномерности магнитного поля допускается применение финишного покрития например -​Лист стальной оцинкованный,тонкий!
## 2. Конструкция платформы (The Levitator)
Платформа представляет собой сверхлегкий каркас в форме звезды, несущий 6 магнитных узлов.

* **Взаимодействие полей:** 6 дисков («блинов») ориентированы полюсом S вниз. Поле диска вытянуто вдоль плоскости контакта, что позволяет ему эффективно опираться на «иглы» статора.
* **Стабилизирующий козырек:** Выступающий слой трансформаторной стали на дисках защищает от опрокидывания. Козырек перехватывает краевые фонтанчики пола, превращая попытку смещения в возвращающую силу.
* **Распределитель нагрузки:** Тончайшая сталь под диском «размазывает» давление тысяч силовых иголок пола, предотвращая деградацию магнитного поля левитатора.

![Векторная схема стабилизации](1770329216402.png)


![Принцип сжатия потока](IMG_20260206_114233.png)
*Визуализация Flux Compression: стабильность достигается за счет плотности магнитных линий в зоне контакта.*

---
## 2.5 платформа!
верхние диски (их 6 ) раставлены в пространстве над полом в форме 6-конечной звезды на расстоянии от 1.5 метров друг от друга и соеденены между собой каркасом из сверх прочного полимера! это так же предотврашает эффект опракидывания!
Конструкция предусматривает выносные медные пластины для стабилизации при необходимости!
так же для усиления отталкиваюшей сылы верхние магнитные диски можео экранировать с флангов (поле N) к- сталью для усиления эффекта отталкивания (опционально) это также предотвратит момент захвата поля N переферийными фантанчиками м- поля!
__
## 3. Техническая визуализация
Ниже представлены общие схемы сборки и расчетные модели системы.

![3D Модель системы](1770327862865.png)
*Общий вид платформы над гексагональной матрицей.*

![3D Модель системы](1770311098979.png)

![3D Модель системы](1770291745163.png)

![Геометрия матрицы](1770297648025.png)
*Топология расположения ячеек статора.*

---
![Процесс ](1770298045514.png)
## 4. Галерея разработки
![Процесс в лаборатории](1770297687785.png)
![Чертеж каркаса-звезды](1770314619770.png)
![Чертеж каркаса-звезды](1770313527640.png)

---
### Технические примечания:
* **Материалы:** NdFeB N52SH, Т-сталь 3408, немагнитные композиты.
* **Опции:** Предусмотрена установка медных пластин для демпфирования через вихревые токи.

---
*Для упорядочивания данных и финишного лоска и визуализации физических концепций использовался ИИ Gemini от компании Google.*


Данный проект представлен для открытого обсуждения фундаментальной возможности пассивной левитации. Основная задача — поиск условий, при которых система сохраняет устойчивость, независимо от наличия дрейфа платформы. Для достижения максимальной центровки в статичном положении допускается модификация поверхности пола в форме пологой «чаши», однако данный параметр требует точной юстировки для исключения заваливания системы.

### Послесловие автора и планы
Техническое замечание по трансформаторной стали: С этим материалом нужно быть осторожным. Важно понимать, что сталь не прерывает магнитное поле, а лишь направляет его (служит магнитопроводом). Она не является ключевым незаменимым элементом, а работает как «русло». Если переборщить с её количеством, можно «задушить» поле. При необходимости сталь можно заменить на другие материалы.

Репозиторий является инженерным стресс-тестом предложенной логики. Если концепция S.M.L.A.S. подтвердит свою жизнеспособность в ходе профессиональной критики, следующим этапом станет разработка магнитного двигателя, исследующего потенциал магнитного поля как энергетической среды.

## Послесловие автора 02: Обуздание хаоса и гибридная стабильность (Phase 02)
Несмотря на все примененные ухищрения с геометрией платформы, я продолжаю искать способы окончательной стабилизации системы. Пассивная левитация требует бескомпромиссной точности, и это обновление — ключевой шаг к решению проблемы устойчивости системы S.M.L.A.S.
1. Вызов: «Фланговая атака» магнитных лучей
Главное опасение в базовой модели — поведение краевых магнитных «фонтанчиков» статора. Существует риск, что лучи, проходящие мимо края левитирующего диска, могут «зайти во фланг» и вступить во взаимодействие с его верхним северным полюсом (N).
Проблема: Это создает паразитное притяжение сверху, резко увеличивая момент опрокидывания.
Решение: Внедрение системы гибридного экранирования, разделяющей роли двух типов стали.
2. Дуэт двух сталей: Т-сталь против К-стали
В обновленной концепции используются два принципиально разных материала:
Т-сталь (Анизотропная 3408): «Магнитный волновод» * На рабочей поверхности: Толщина минимальна (< 1 мм) для фокусировки «иглы» левитации.
На торцах: Здесь слой стали делается значительно шире. Её задача — полностью исключить расширение магнитного поля навстречу фонтанчикам статора. Мы прижимаем «крылья» магнитного поля к «туловищу» диска, упаковывая их так, чтобы поле N не выходило за габариты торца.
К-сталь (Компьютерная/Изотропная): «Магнитная ловушка» Из этого материала изготавливаются нижние перфорированные обручи. К-сталь работает как губка: она перехватывает «фонтанчики» статора на подлете и гасит их внутри своей структуры.
3. Конструктивные уточнения
Защитный перехват (Опционально): Обруч из К-стали может иметь внутренний диаметр чуть меньше диаметра магнитного диска. Это решение необязательно: такой «нахлест» позволяет прикрыть часть полезных «фонтанчиков» по периметру, создавая гарантированную зону отсечки и исключая возможность захода поля во фланг.
Отказ от меди: Данная схема позволяет отказаться от опциональных медных пластин. Обручи из К-стали работают как пассивные магнитные демпферы.
Крепление: Обручи крепятся по одному на каждый блин к несущему корпусу платформы. Они расположены ниже плоскости магнита, чтобы встречать поток от пола первыми.
Итог
Разделение сталей позволяет одновременно фокусировать полезную силу и фильтровать вредную. Мы сознательно предлагаем инструменты для достижения контролируемой стабильности, которая является фундаментом всей концепции левитации.

## P.S. Магнитная специализация: Почему именно эти материалы?
Для тех, кто хочет глубже понять физику процесса, я разделяю функции материалов по их принципиальному воздействию на поле:
Т-сталь (Трансформаторная) — это «РУСЛО»:
Благодаря своей анизотропности (способности проводить поле только в одном направлении), она выступает в роли навигатора. Её задача — не дать полю «растекаться». Она заставляет магнитные линии течь строго там, где нам нужно, формируя плотную и мощную «опору» под диском. Мы используем её для фокусировки и концентрации силы.
К-сталь (Компьютерная/Изотропная) — это «РАССЕИВАТЕЛЬ»:
Этот материал — полная противоположность. Он изотропен, то есть жадно впитывает магнитные линии со всех сторон сразу. В проекте он выполняет роль магнитного демпфера и ловушки. Она не направляет поле, а «съедает» его, превращая хаотичные краевые лучи в безопасный внутренний поток. Это наш главный инструмент защиты и фильтрации от паразитных помех.



---
<a name="english"></a>
# English Version
[🇷🇺 Back to Russian](#russian)

![Project Orbitus Banner](1770297254520.png)

## S.M.L.A.S. (Static Magnetic Lattice Array System)

**S.M.L.A.S.** is a concept for a passive magnetic levitation system that solves the fundamental problem of instability by creating a **discrete force environment**. The project demonstrates the possibility of stable hovering (**circumventing Earnshaw's Theorem**) without the use of active electronics.

---

## 1. The Stator Floor Architecture
The core concept is shifting from a single uniform magnetic field to a matrix of independent "magnetic fountains."
* **Gap Isolation:** A gap of **15mm** is maintained between hexagonal cells (this can reach a 1:1 ratio relative to the magnet, depending on the thickness of the T-steel; finding the right balance is key). This prevents magnetic fluxes from merging into a single "gradient hill" from which the platform would inevitably slide off.
* **"Pillar" Form Factor:** The height of N52H magnets is calculated to compensate for the platform's mass, ensuring a 1:1 force balance.
* **T-Steel Focusing:**
  ![Project Orbitus Banner](IMG_20260206_120714.png)
* Each pillar is isolated by 3408 transformer steel on the sides. It shields lateral dispersion and directs energy vertically, creating a "magnetic beam" effect.
* **Monolithization:** The matrix is fixed in a dielectric base (polymer/epoxy resin).

![Stator Cell Diagram](1770367790967.png)

![Field Configuration Comparison](1770299361814.png)
*On the right (B) — the implemented system: focused beams without parasitic interaction.*

**Important Note!** The active stator surface is only partially shown in the diagrams; in reality, it can scale to cover an entire room. The project is fully scalable. It is worth noting that while the current iteration uses T-steel, its necessity in the platform base is subject to further optimization! To ensure magnetic field uniformity, a finish coating such as a thin galvanized steel sheet may be used.

---

## 2. The Levitator (Platform) Design
The platform is an ultra-light star-shaped frame carrying 6 magnetic nodes.

* **Field Interaction:** 6 magnetic discs are oriented with the S-pole facing down. The disc's field is stretched along the contact plane, allowing it to "rest" effectively on the stator's magnetic needles.
* **Stabilizing Visor:** A protruding layer of transformer steel on the discs protects against tipping. The visor intercepts edge "fountains" from the floor, converting displacement attempts into a restoring force.
* **Load Distributor:** Ultra-thin steel under the disc spreads the pressure of thousands of force needles, preventing the degradation of the levitator's magnetic field.

![Stabilization Vector Scheme](1770329216402.png)

![Flux Compression Principle](IMG_20260206_114233.png)
*Flux Compression visualization: stability is achieved through the density of magnetic lines in the contact zone.*

---

## 2.5 The Platform!
The 6 upper discs are arranged in a 6-pointed star configuration at a distance of 1.5 meters from each other, connected by a high-strength polymer frame. This prevents the tipping effect.
The design allows for outrigger copper plates for stabilization if necessary.
Additionally, to enhance the repulsive force, the upper magnetic discs can be shielded from the flanks (N-pole field) with K-steel (optional). This also prevents the N-field from being captured by peripheral magnetic fountains.

---

## 3. Technical Visualization
Below are general assembly diagrams and calculation models of the system.

![3D System Model](1770327862865.png)
*General view of the platform over the hexagonal matrix.*

![3D System Model](1770311098979.png)
![3D System Model](1770291745163.png)
![Matrix Geometry](1770297648025.png)
*Stator cell topology.*

---

## 4. Development Gallery
![Process](1770298045514.png)
![Lab Process](1770297687785.png)
![Star-frame Blueprint](1770314619770.png)
![Star-frame Blueprint](1770313527640.png)

---

### Technical Notes:
* **Materials:** NdFeB N52SH, T-Steel 3408, non-magnetic composites.
* **Options:** Installation of copper plates for eddy current damping.

---
*Data organization, final polish, and physical concept visualization assisted by Google Gemini AI.*

This project is presented for open discussion on the fundamental possibility of passive levitation. The main task is to find conditions under which the system remains stable, regardless of platform drift. To achieve maximum centering in a static position, modifying the floor surface into a shallow "bowl" shape is permitted, though this parameter requires precise calibration to prevent the system from toppling.

### Author's Afterword and Plans
Technical note on transformer steel: Use this material with caution. It is important to understand that steel does not block the magnetic field, but merely directs it (acts as a magnetic circuit). It is not a key indispensable element but works as a "channel." If used excessively, it can "choke" the field. If necessary, steel can be replaced with other materials.

The repository serves as an engineering stress-test of the proposed logic. If the S.M.L.A.S. concept proves viable through professional critique, the next stage will be the development of a magnetic motor exploring the potential of the magnetic field as an energy medium.

---

## Author's Afterword 02: Taming Chaos & Hybrid Stability (Phase 02)
Despite all the geometric tricks applied to the platform, I continue to look for ways to fully stabilize the system. Passive levitation requires uncompromising precision, and this update is a key step toward solving the stability problem of S.M.L.A.S.

### 1. The Challenge: "Flank Attack" of Magnetic Rays
The main concern in the base model is the behavior of the edge magnetic "fountains" of the stator. There is a risk that rays passing the edge of the levitating disc might "attack the flank" and interact with its upper North (N) pole.
**Problem:** This creates parasitic attraction from above, sharply increasing the tipping moment.
**Solution:** Implementing a hybrid shielding system that separates the roles of two types of steel.

### 2. The Dual Steel Duo: T-Steel vs. K-Steel
In the updated concept, two fundamentally different materials are used:
* **T-Steel (Anisotropic 3408) — The "Magnetic Waveguide":**
    * On the working surface: Thickness is minimal (< 1 mm) to focus the levitation "needle."
    * On the ends: Here, the steel layer is significantly wider. Its task is to completely eliminate the expansion of the magnetic field toward the stator fountains. We "press" the magnetic field wings to the disc's body, packing them so that the N-field does not extend beyond the edge.
* **K-Steel (Computer/Isotropic) — The "Magnetic Trap":** This material is used to make the lower perforated rings. K-steel works like a sponge: it intercepts stator "fountains" on approach and neutralizes them within its structure.

### 3. Design Refinements
* **Protective Intercept (Optional):** The K-steel ring can have an inner diameter slightly smaller than the magnetic disc. This "overlap" covers some of the useful fountains around the perimeter, creating a guaranteed cutoff zone and excluding the possibility of the field entering the flank.
* **No Copper Required:** This scheme allows for the removal of optional copper plates. K-steel rings act as passive magnetic dampers.
* **Mounting:** One ring is attached to each magnetic disc on the platform's carrier body. They are positioned below the magnet plane to meet the floor's flux first.

### Summary
The separation of steels allows for the simultaneous focusing of useful force and the filtering of harmful interference. We are deliberately proposing tools to achieve controlled stability, which is the foundation of the entire levitation concept.

---

## P.S. Magnetic Specialization: Why these materials?
For those who want to dive deeper into the physics of the process, I separate the functions of the materials based on their fundamental impact on the field:
* **T-Steel (Transformer) — The "CHANNEL":** Due to its anisotropy (the ability to conduct a field in only one direction), it acts as a navigator. Its task is to prevent the field from "leaking." It forces magnetic lines to flow strictly where we need them, forming a dense and powerful "support" under the disc. We use it for focus and power concentration.
* **K-Steel (Computer/Isotropic) — The "DISSIPATOR":** This material is the exact opposite. It is isotropic, meaning it greedily absorbs magnetic lines from all directions at once. In the project, it serves as a magnetic damper and trap. It does not direct the field but "eats" it, transforming chaotic edge rays into a safe internal flow. This is our primary tool for protection and filtration against parasitic interference.
* 
