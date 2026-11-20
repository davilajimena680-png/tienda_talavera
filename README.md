# Tienda Talavera

Módulo de comercio de **Super Dolores** enfocado en la tienda **Talavera del Centro** (Dolores Hidalgo), desarrollado siguiendo el ciclo de pruebas **ROJO / VERDE** en Flutter.

---

## 1. Dominio y reglas base

Rojo: las pruebas de dominio fallan antes de completar las reglas y modelos base.

![Dominio rojo](assets/01_flutter_test_dominio_ROJO.png)

Verde: pasan las pruebas de dominio (monedero, eventos, permisos y reglas base).

![Dominio verde](assets/01_flutter_test_dominio_VERDE.png)

---

## 2. Servicios de comercio (Talavera del Centro)

Rojo: las pruebas de servicios fallan antes de implementar el catálogo, existencias, comisión e idempotencia de la tienda.

![Servicios rojo](assets/02_flutter_test_servicios_ROJO.png)

Verde: pasan las pruebas de servicios con **Talavera del Centro** (`Taza de Talavera` y `Jarrón azul`), control de inventario, comisión de plataforma e idempotencia.

![Servicios verde](assets/02_flutter_test_servicios_VERDE.png)

---

## 3. ViewModels de presentación

Rojo: las pruebas de ViewModels fallan antes de conectar el estado de la tienda y el carrito con la interfaz.

![ViewModels rojo](assets/03_flutter_test_viewmodels_ROJO.png)

Verde: pasan las pruebas de ViewModels con el flujo completo de selección, carrito y compra.

![ViewModels verde](assets/03_flutter_test_viewmodels_VERDE.png)

###Pantallas funcionando

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c49a27b9-ef40-4859-b5eb-be217bdc291b" width="180">
      <p><strong>Pantalla 1</strong></p>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/896d96c9-7b50-4757-b478-022133be2566" width="180">
      <p><strong>Pantalla 2</strong></p>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1c4624c0-fd51-499f-8fb9-7bcd10cad2dc" width="180">
      <p><strong>Pantalla 3</strong></p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/21daa2e7-e66f-4e10-8e84-beb6dbb620e5" width="180">
      <p><strong>Pantalla 4</strong></p>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/2f216f7e-f828-4bfc-8517-fcda9474e360" width="180">
      <p><strong>Pantalla 5</strong></p>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/58f934a9-8fb6-4f9b-bd84-6f3660889d9e" width="180">
      <p><strong>Pantalla 6</strong></p>
    </td>
  </tr>
</table>

