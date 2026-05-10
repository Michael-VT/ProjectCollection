# ProjectCollection

**[English](README.md)** | **[Русский](README.RU.md)** | **[Українська](README.UA.md)** | **[Português](README.PT.md)** | **[Français](README.FR.md)** | **[Deutsch](README.DE.md)**

---

Plan d'appartement dessiné dans FreeCAD, sur lequel le câblage électrique des prises, interrupteurs, luminaires et autres équipements a été tracé à l'aide d'un script Python. Le câblage a ensuite été acheté et installé selon ce schéma. L'écart entre la spécification et l'installation réelle était inférieur à 5%.

## FreeCAD — Câblage de l'appartement

<table>
<tr>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_0.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_0.jpg" width="200" alt="Modèle 3D"></a>
</td>
<td valign="middle">
<h4>Modèle 3D de l'appartement</h4>
Modèle tridimensionnel de l'appartement avec le câblage électrique dessiné en marron.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Vue de dessus du câblage</h4>
Vue en plan montrant tous les tracés de câblage pour les prises, interrupteurs et luminaires.
</td>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_1.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_1.jpg" width="200" alt="Vue de dessus"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_2.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_2.jpg" width="200" alt="Vue en perspective"></a>
</td>
<td valign="middle">
<h4>Vue en perspective du câblage</h4>
Vue en perspective montrant la disposition tridimensionnelle de l'ensemble du câblage.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Tableau de spécification des fils</h4>
Le script a simultanément généré un tableau complet de spécification des fils en même temps que le tracé du câblage.
</td>
<td align="center" width="220">
<a href="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_3.jpg"><img src="Laying_wiring_in_an_apartment_using_a_script_in_FreeCad_3.jpg" width="200" alt="Tableau de spécification"></a>
</td>
</tr>
</table>

## Altium — Cartes ASIC

<table>
<tr>
<td align="center" width="220">
<a href="Past01.JPG"><img src="Past01.JPG" width="200" alt="Vue de dessus"></a>
</td>
<td valign="middle">
<h4>Carte ASIC — Vue de dessus</h4>
Carte PCB avec puces de calcul ASIC créée dans Altium Designer, vue de dessus.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Carte ASIC — Vue en perspective</h4>
Carte PCB avec puces de calcul ASIC créée dans Altium Designer, vue en perspective.
</td>
<td align="center" width="220">
<a href="Past02.JPG"><img src="Past02.JPG" width="200" alt="Perspective"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Past03.JPG"><img src="Past03.JPG" width="200" alt="Perspective 2"></a>
</td>
<td valign="middle">
<h4>Carte ASIC — Vue en perspective (détail)</h4>
Vue en perspective détaillée de la carte avec les puces de calcul ASIC.
</td>
</tr>
<tr>
<td valign="middle">
<h4>Carte ASIC — Vue latérale avec dissipateur</h4>
Vue latérale du PCB avec dissipateur thermique installé.
</td>
<td align="center" width="220">
<a href="Past04.JPG"><img src="Past04.JPG" width="200" alt="Vue latérale dissipateur"></a>
</td>
</tr>
<tr>
<td align="center" width="220">
<a href="Past05.JPG"><img src="Past05.JPG" width="200" alt="Vue du dissipateur"></a>
</td>
<td valign="middle">
<h4>Carte ASIC — Côté dissipateur</h4>
Carte PCB vue du côté du dissipateur thermique.
</td>
</tr>
</table>

## Altium — Schémas et Diagrammes

<table>
<tr>
<td align="center" width="220">
<a href="Sensor_Shema.png"><img src="Sensor_Shema.png" width="200" alt="Schéma interrupteur tactile"></a>
</td>
<td valign="middle">
<h4>Schéma de l'interrupteur tactile</h4>
Schéma électrique de l'interrupteur tactile créé dans Altium Designer.
</td>
</tr>
</table>

### Schémas de circuits (PDF)

| Document | Description |
|---|---|
| [REG-007a.pdf](REG-007a.pdf) | Schéma du circuit du régulateur de température |
| [RelayExpan.PDF](RelayExpan.PDF) | Schéma du circuit de l'expandeur de commande de relais pour le raccordement de charges |
| [STM32F427ITx.pdf](STM32F427ITx.pdf) | Schéma du circuit du contrôleur principal de l'appartement avec interface CAN |
| [USBHART2.pdf](USBHART2.pdf) | Schéma du circuit du modem USB HART |
| [WoterMake_2019-02-11_16-03.PDF](WoterMake_2019-02-11_16-03.PDF) | Schéma du circuit du contrôleur principal de traitement d'eau avec interfaces RS485, CAN et Ethernet |
| [XMC1404KEY4c_with_note.PDF](XMC1404KEY4c_with_note.PDF) | Schéma de l'interrupteur intelligent avec interface CAN |
