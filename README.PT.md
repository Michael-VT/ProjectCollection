# ProjectCollection

**[English](README.md)** | **[Русский](README.RU.md)** | **[Українська](README.UA.md)** | **[Português](README.PT.md)** | **[Français](README.FR.md)** | **[Deutsch](README.DE.md)**

---

Planta de apartamento desenhada no FreeCAD, onde a fiação elétrica para tomadas, interruptores, luminárias e outros equipamentos foi traçada usando um script Python. A fiação foi então adquirida e instalada de acordo com este diagrama. A discrepância resultante entre a especificação e a instalação real foi inferior a 5%.

## FreeCAD — Fiação do Apartamento

<table>
<tr>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_0.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_0.jpg" width="200" alt="Modelo 3D"></a>
</td>
<td valign="middle">
<h4>Modelo 3D do Apartamento</h4>
Modelo tridimensional do apartamento com a fiação elétrica desenhada em marrom.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Vista Superior da Fiação</h4>
Vista em planta mostrando todos os percursos de fiação para tomadas, interruptores e luminárias.
</td>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_1.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_1.jpg" width="200" alt="Vista superior"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_2.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_2.jpg" width="200" alt="Vista em perspectiva"></a>
</td>
<td valign="middle">
<h4>Vista em Perspectiva da Fiação</h4>
Vista em perspectiva mostrando a disposição tridimensional de toda a fiação.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Tabela de Especificação dos Fios</h4>
O script gerou simultaneamente uma tabela completa de especificação de fios junto com o layout da fiação.
</td>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_3.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_3.jpg" width="200" alt="Tabela de especificação"></a>
</td>
</tr>
</table>

## Altium — Placas com ASIC

<table>
<tr>
<td align="center" width="220">
<a href="Past01.JPG"><img src="Past01.JPG" width="200" alt="Vista superior"></a>
</td>
<td valign="middle">
<h4>Placa ASIC — Vista Superior</h4>
PCI com chips de computação ASIC criada no Altium Designer, vista superior.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Placa ASIC — Vista em Perspectiva</h4>
PCI com chips de computação ASIC criada no Altium Designer, vista em perspectiva.
</td>
<td align="center" width="220">
<a href="Past02.JPG"><img src="Past02.JPG" width="200" alt="Perspectiva"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Past03.JPG"><img src="Past03.JPG" width="200" alt="Perspectiva 2"></a>
</td>
<td valign="middle">
<h4>Placa ASIC — Vista em Perspectiva (detalhe)</h4>
Vista em perspectiva detalhada da placa com chips de computação ASIC.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Placa ASIC — Vista Lateral com Dissipador</h4>
Vista lateral da PCI com dissipador de calor instalado.
</td>
<td align="center" width="220">
<a href="Past04.JPG"><img src="Past04.JPG" width="200" alt="Vista lateral dissipador"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Past05.JPG"><img src="Past05.JPG" width="200" alt="Vista do dissipador"></a>
</td>
<td valign="middle">
<h4>Placa ASIC — Lado do Dissipador</h4>
PCI vista pelo lado do dissipador de calor.
</td>
</tr>
</table>

## Altium — Esquemas e Diagramas

<table>
<tr>
<td align="center" width="220">
<a href="Sensor_Shema.png"><img src="Sensor_Shema.png" width="200" alt="Esquema interruptor touch"></a>
</td>
<td valign="middle">
<h4>Esquema do Interruptor Touch</h4>
Esquema elétrico do interruptor touch criado no Altium Designer.
</td>
</tr>
</table>

### Diagramas de Circuitos (PDF)

| Documento | Descrição |
|---|---|
| [REG-007a.pdf](REG-007a.pdf) | Diagrama do circuito do controlador de temperatura |
| [RelayExpan.PDF](RelayExpan.PDF) | Diagrama do circuito do expansor de controle de relés para conexão de cargas |
| [STM32F427ITx.pdf](STM32F427ITx.pdf) | Diagrama do circuito do controlador principal do apartamento com interface CAN |
| [USBHART2.pdf](USBHART2.pdf) | Diagrama do circuito do modem USB HART |
| [WoterMake_2019-02-11_16-03.PDF](WoterMake_2019-02-11_16-03.PDF) | Diagrama do circuito do controlador principal de tratamento de água com interfaces RS485, CAN e Ethernet |
| [XMC1404KEY4c_with_note.PDF](XMC1404KEY4c_with_note.PDF) | Esquema do interruptor inteligente com interface CAN |
