# 💱 Conversor de Monedas

Aplicación de consola desarrollada en Java que permite convertir entre distintas monedas en tiempo real, consumiendo la API de [ExchangeRate-API](https://www.exchangerate-api.com/).

---

## 🚀 Funcionalidades

- Menú interactivo en consola con 6 opciones de conversión
- Conversión en tiempo real usando la API de ExchangeRate
- El programa sigue corriendo hasta que el usuario decida salir
- Manejo básico de errores de conexión o API key inválida

---

## 💰 Conversiones disponibles

| # | Conversión |
|---|-----------|
| 1 | Dólar → Peso Argentino |
| 2 | Peso Argentino → Dólar |
| 3 | Dólar → Real Brasileño |
| 4 | Real Brasileño → Dólar |
| 5 | Dólar → Peso Colombiano |
| 6 | Peso Colombiano → Dólar |
| 7 | Salir |

---

## 🖥️ Ejemplo de uso

```
*************************************
   Bienvenido al Conversor de Monedas
*************************************

Elija una opcion:
1) Dolar => Peso Argentino
2) Peso Argentino => Dolar
3) Dolar => Real Brasileno
4) Real Brasileno => Dolar
5) Dolar => Peso Colombiano
6) Peso Colombiano => Dolar
7) Salir
Opcion: 1

Ingresa el valor que deseas convertir: 25

El valor de 25.0 [USD] corresponde al valor final de =>>> 20293.75 [ARS]
```

---

## ⚙️ Tecnologías utilizadas

- Java 11+
- `java.net.http.HttpClient` (cliente HTTP nativo de Java)
- API REST: [ExchangeRate-API](https://www.exchangerate-api.com/)

---

## 🔧 Cómo ejecutar el proyecto

**1. Clona el repositorio**
```bash
git clone https://github.com/tu-usuario/conversor-monedas.git
cd conversor-monedas
```

**2. Consigue tu API Key gratis**

Regístrate en [exchangerate-api.com](https://www.exchangerate-api.com/) y copia tu clave.

**3. Configura tu API Key**

En el archivo `ConversorMonedas.java`, reemplaza:
```java
static String apiKey = "TU_API_KEY_AQUI";
```
por tu clave real.

**4. Compila y ejecuta**
```bash
javac ConversorMonedas.java
java ConversorMonedas
```

---

## 📁 Estructura del proyecto

```
conversor-monedas/
│
└── ConversorMonedas.java
```

---

## 👩‍💻 Desarrollado por

Cristhian Ordano — Challenge ONE Backend Java — Alura Latam 🚀
