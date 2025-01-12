## Autor
Fernando Aquize
# Conversor de Monedas

Este es un proyecto de Java que permite realizar conversiones de monedas en tiempo real utilizando la API de ExchangeRate. Además, guarda los resultados de las conversiones en archivos JSON para su consulta posterior.

## Características

- Conversión de monedas entre múltiples divisas.
- Validación de entradas para evitar errores, como números negativos o entradas no válidas.
- Integración con la API de ExchangeRate para obtener las tasas de conversión actualizadas.
- Guardado de los resultados de las conversiones en archivos JSON con formato legible.
- Soporte para manejo de excepciones en caso de errores en la entrada del usuario o en la conexión con la API.

## Tecnologías Utilizadas

- **Java 11 o superior**
- Librerías externas:
  - [Gson](https://github.com/google/gson): Para la conversión de objetos Java a JSON y viceversa.
- API de ExchangeRate: Para obtener datos de tasas de conversión actualizados.

## Requisitos Previos

- Tener instalado Java Development Kit (JDK) 11 o superior.
- Configurar el archivo `pom.xml` o descargar manualmente la librería `Gson`.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/conversor-de-monedas.git
   cd conversor-de-monedas
