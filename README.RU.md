# ProjectCollection

**[English](README.md)** | **[Русский](README.RU.md)** | **[Українська](README.UA.md)** | **[Português](README.PT.md)** | **[Français](README.FR.md)** | **[Deutsch](README.DE.md)**

---

План квартиры, нарисованный в FreeCAD, на котором с помощью Python-скрипта была проложена электропроводка для розеток, выключателей, светильников и другого оборудования. По этой схеме была закуплена и проложена проводка; расхождение с расчётной спецификацией составило менее 5%.

## FreeCAD — Проводка в квартире

<table>
<tr>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_0.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_0.jpg" width="200" alt="3D модель"></a>
</td>
<td valign="middle">
<h4>3D-модель квартиры</h4>
Трёхмерная модель квартиры с электропроводкой, отрисованной коричневым цветом.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Вид сверху на проводку</h4>
План-вид с прокладкой всех линий проводки для розеток, выключателей и светильников.
</td>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_1.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_1.jpg" width="200" alt="Вид сверху"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_2.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_2.jpg" width="200" alt="Перспективный вид"></a>
</td>
<td valign="middle">
<h4>Перспективный вид проводки</h4>
Перспективный вид, показывающий трёхмерную раскладку всей проводки.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Таблица спецификации проводов</h4>
Скрипт одновременно с прокладкой проводки сгенерировал полную таблицу спецификации проводов.
</td>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_3.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_3.jpg" width="200" alt="Таблица спецификации"></a>
</td>
</tr>
</table>

## Altium — Платы с ASIC

<table>
<tr>
<td align="center" width="220">
<a href="Past01.JPG"><img src="Past01.JPG" width="200" alt="Вид сверху"></a>
</td>
<td valign="middle">
<h4>Плата с ASIC — вид сверху</h4>
Печатная плата с вычислительными чипами ASIC, созданная в Altium Designer, вид сверху.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Плата с ASIC — перспективный вид</h4>
Печатная плата с вычислительными чипами ASIC, созданная в Altium Designer, перспективный вид.
</td>
<td align="center" width="220">
<a href="Past02.JPG"><img src="Past02.JPG" width="200" alt="Перспектива"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Past03.JPG"><img src="Past03.JPG" width="200" alt="Перспектива 2"></a>
</td>
<td valign="middle">
<h4>Плата с ASIC — перспективный вид (детально)</h4>
Детальный перспективный вид платы с вычислительными чипами ASIC.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Плата с ASIC — вид сбоку с радиатором</h4>
Вид сбоку на печатную плату с установленным радиатором.
</td>
<td align="center" width="220">
<a href="Past04.JPG"><img src="Past04.JPG" width="200" alt="Вид сбоку радиатор"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Past05.JPG"><img src="Past05.JPG" width="200" alt="Вид с радиатора"></a>
</td>
<td valign="middle">
<h4>Плата с ASIC — сторона радиатора</h4>
Вид на печатную плату со стороны радиатора.
</td>
</tr>
</table>

## Altium — Принципиальные схемы

<table>
<tr>
<td align="center" width="220">
<a href="Sensor_Shema.png"><img src="Sensor_Shema.png" width="200" alt="Схема сенсорного выключателя"></a>
</td>
<td valign="middle">
<h4>Схема сенсорного выключателя</h4>
Принципиальная схема сенсорного выключателя, созданная в Altium Designer.
</td>
</tr>
</table>

### Принципиальные схемы (PDF)

| Документ | Описание |
|---|---|
| [REG-007a.pdf](REG-007a.pdf) | Принципиальная схема контроллера температуры |
| [RelayExpan.PDF](RelayExpan.PDF) | Принципиальная схема расширителя управления реле для подключения нагрузок |
| [STM32F427ITx.pdf](STM32F427ITx.pdf) | Принципиальная схема главного контроллера квартиры с интерфейсом CAN |
| [USBHART2.pdf](USBHART2.pdf) | Принципиальная схема USB HART-модема |
| [WoterMake_2019-02-11_16-03.PDF](WoterMake_2019-02-11_16-03.PDF) | Принципиальная схема главного контроллера водоподготовки с интерфейсами RS485, CAN и Ethernet |
| [XMC1404KEY4c_with_note.PDF](XMC1404KEY4c_with_note.PDF) | Принципиальная схема умного выключателя с интерфейсом CAN |
