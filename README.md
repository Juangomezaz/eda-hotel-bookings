# 🏨 EDA — Hotel Bookings

Análisis exploratorio de datos sobre 119.390 reservas hoteleras · Python · Pandas · Seaborn

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)

---

## Descripción

Análisis exploratorio completo sobre un dataset de reservas hoteleras con 119.390 registros y 32 atributos. El objetivo fue identificar patrones de cancelación, comportamiento de clientes y factores que influyen en la tarifa diaria promedio (ADR).

---

## Hallazgos principales

- 📌 Los clientes con mayor historial de solicitudes especiales tienen menor tasa de cancelación — indicio de mayor compromiso con la reserva.
- 📌 El lead time (anticipación de reserva) tiene correlación positiva con cancelaciones — a mayor anticipación, mayor riesgo de cancelar.
- 📌 Clientes con reservas previas completadas exitosamente presentan perfil de bajo riesgo de cancelación.
- 📌 La tarifa ADR tiene baja correlación con variables numéricas — factores cualitativos como tipo de habitación y temporada explican mejor el precio.

---

## Stack técnico

`Python 3` `Pandas` `Seaborn` `Matplotlib` `NumPy` `Google Colab`

---

## Estructura

```
📁 eda-hotel-bookings/
├── ActividadEDA_HotelBookings.ipynb   # Notebook principal
└── hotel_bookings.csv                 # Dataset (119.390 registros)
```

---

*Proyecto académico · Ingeniería de Sistemas · Universidad Católica Luis Amigó · 2025*
