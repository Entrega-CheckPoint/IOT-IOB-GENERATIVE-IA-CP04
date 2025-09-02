# $IOT-IOB-GENERATIVE-IA-CP04$

## Grupo

| NOME                        | RM     |
| --------------------------- | ------ |
| Francesco M Di Benedetto    | 557313 |
| Samuel Patrick Yariwake     | 556461 |
| Luiz Felipe Campos da Silva | 555591 |

---

## DATASET

Vamos trabalhar e manipular 2 datasets diferentes:

1. [Individual Household Electric Power Consumption](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)
2. [Appliances Energy Prediction](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)

## 1. **Individual Household Electric Power Consumption**

Este arquivo contém 2075259 medições coletadas em uma casa localizada em Sceaux (7 km de Paris, França) entre dezembro de 2006 e novembro de 2010 (47 meses).

### _Informações de variáveis_

1. date: Date in format dd/mm/yyyy
2. time: time in format hh:mm:ss
3. global_active_power: household global minute-averaged active power (in kilowatt)
4. global_reactive_power: household global minute-averaged reactive power (in kilowatt)
5. voltage: minute-averaged voltage (in volt)
6. global_intensity: household global minute-averaged current intensity (in ampere)
7. sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
8. sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
9. sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

---

## 2. **Appliances Energy Prediction**

O conjunto de dados cobre cerca de 4,5 meses com registros a cada 10 minutos:

- Temperatura e umidade da casa: monitoradas por uma rede de sensores sem fio ZigBee, transmitindo leituras a cada ~3,3 minutos, depois agregadas em médias de 10 minutos.
- Consumo de energia: registrado a cada 10 minutos por medidores de energia m-bus.
- Condições climáticas externas: obtidas da estação meteorológica do Aeroporto de Chievres (Bélgica) e integradas ao conjunto via coluna de data e hora.

### _Informações de variáveis_

1. date time year-month-day hour:minute:second
2. Appliances, energy use in Wh
3. lights, energy use of light fixtures in the house in Wh
4. T1, Temperature in kitchen area, in Celsius
5. RH_1, Humidity in kitchen area, in %
6. T2, Temperature in living room area, in Celsius
7. RH_2, Humidity in living room area, in %
8. T3, Temperature in laundry room area
9. RH_3, Humidity in laundry room area, in %
10. T4, Temperature in office room, in Celsius
11. RH_4, Humidity in office room, in %
12. T5, Temperature in bathroom, in Celsius
13. RH_5, Humidity in bathroom, in %
14. T6, Temperature outside the building (north side), in Celsius
15. RH_6, Humidity outside the building (north side), in %
16. T7, Temperature in ironing room , in Celsius
17. RH_7, Humidity in ironing room, in %
18. T8, Temperature in teenager room 2, in Celsius
19. RH_8, Humidity in teenager room 2, in %
20. T9, Temperature in parents room, in Celsius
21. RH_9, Humidity in parents room, in %
22. To, Temperature outside (from Chievres weather station), in Celsius
23. Pressure (from Chievres weather station), in mm Hg
24. RH_out, Humidity outside (from Chievres weather station), in %
25. Wind speed (from Chievres weather station), in m/s
26. Visibility (from Chievres weather station), in km
27. Tdewpoint (from Chievres weather station), Â°C
28. rv1, Random variable 1, nondimensional
29. rv2, Random variable 2, nondimensional
