# Pre- Entrega Proyecto de Automatización QA - Sauce Demo - Carolina Moreno

## Descripcion

El respectivo repositorio contiene un framework de automatización para ejecutar pruebas funcionales sobre el sitio web Sauce Demo, su objetivo principal es validar los flujos de inicio de sesión y la gestión del carrito de compras.

## Tecnologias usadas

El stack tecnológico seleccionado es el siguiente: 

- Lenguaje: Python
- Automatización de Navegador Web: Selenium WebDriver
- Framework: Pytest
- Reportes: Pytest HTML
- Control de versiones: Git

## Instalacion y Configuración

## Clonar Repositorio: 

`git clone https://github.com/Jdmonte4269AP/pre-entrega.git`


## Instalacion dependencias

`pip install -r requirements.txt`

## Ejecucion de todas las  Pruebas:

python -m pytest

## Ejecucion de Pruebas especificas:

py -m pytest -v test\test_inventory.py

## Funcionamiento de las prubeas

- Test cart: Realiza el flujo completo de agregar productos al carrito, verifica el contador, valida el nombre del primer producto y de que el producto seleccionado coincida con el que aparece.

- Test login: Valida el ingreso al sitio web Sauce Demo con credenciales válidas

- Test inventory: 

## Generar Reporte HTML:

python -m pytest --html=report.html

