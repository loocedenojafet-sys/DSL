<!DOCTYPE html>

<html lang="es">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Informe Profesional - Examen Parcial 2</title>

    <!-- Carga del CDN de Tailwind CSS para un diseño limpio y moderno -->

    <script src="https://cdn.tailwindcss.com"></script>

    <style>

        /* Estilo base, usa la fuente Inter para un look profesional */

        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');

        body {

            font-family: 'Inter', sans-serif;

            background-color: #f4f7f9;

        }

        /* Barra lateral para resaltar títulos de sección */

        .section-header {

            border-left: 5px solid #007bff; /* Azul corporativo */

            padding-left: 1rem;

            margin-bottom: 1.5rem;

        }

        /* Bloque de código con fondo oscuro para visibilidad */

        .code-block {

            background-color: #1e1e1e;

            color: #d4d4d4;

            padding: 1rem;

            border-radius: 0.5rem;

            overflow-x: auto;

            white-space: pre;

        }

        /* Estilo para los marcadores de imagen */

        .image-placeholder {

            display: flex;

            justify-content: center;

            align-items: center;

            min-height: 250px;

            background-color: #e0e7ff; /* light blue for tech context */

            border: 2px dashed #4f46e5; /* indigo border */

            color: #1e3a8a; /* dark blue text */

            font-weight: 600;

            text-align: center;

            border-radius: 0.75rem;

            margin-top: 1rem;

            margin-bottom: 1rem;

            padding: 1rem;

            font-size: 1.1rem;

        }

    </style>

</head>

<body class="p-4 sm:p-8">



    <div class="max-w-6xl mx-auto bg-white shadow-xl rounded-2xl p-6 sm:p-10">



        <!-- ENCABEZADO DEL INFORME -->

        <header class="mb-8 border-b pb-4">

            <h1 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mb-1">Examen Parcial 2 - Proyecto 7</h1>

            <h2 class="text-xl font-semibold text-gray-700">Sistema de Gestión para CHINOS CAFE</h2>

            <div class="mt-4 grid grid-cols-2 gap-4 text-sm text-gray-600">

                <div><span class="font-medium text-gray-800">Estudiante:</span> [Tu Nombre Completo Aquí]</div>

                <div><span class="font-medium text-gray-800">Profesor:</span> Napoleón Ibarra</div>

                <div><span class="font-medium text-gray-800">Asignatura:</span> Desarrollo Lógico y Algoritmo</div>

                <div><span class="font-medium text-gray-800">Cédula:</span> [Tu Número de Cédula Aquí]</div>

            </div>

        </header>



        <!-- RESUMEN EJECUTIVO / INTRODUCCIÓN -->

        <section class="mb-10">

            <h3 class="text-2xl font-bold text-gray-800 mb-4 section-header">Resumen Ejecutivo</h3>

            <p class="text-gray-700 leading-relaxed">

                Este informe presenta el desarrollo del Sistema de Información para CHINOS CAFE, un proyecto que abarca la configuración de infraestructura, el diseño de red, la lógica algorítmica y la implementación en Python. El objetivo es ofrecer una solución centralizada y robusta para la gestión de datos de los establecimientos.

            </p>

        </section>



        <!-- SECCIÓN 1: LABORATORIO DE SERVIDOR -->

        <section class="mb-10">

            <h3 id="servidor" class="text-2xl font-bold text-blue-700 mb-4 section-header">I. Laboratorio de Servidor (Linux + MySQL)</h3>

            <p class="text-gray-700 mb-4">

                La implementación del Servidor de Datos se realizó en una Máquina Virtual con Linux (elegir la distribución) y el gestor de bases de datos MySQL, como se solicitó para el almacenamiento centralizado de la información del negocio.

            </p>



            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">1.1. Configuración de la Máquina Virtual</h4>

            <p class="text-gray-700 mb-4">

                Pasos y especificaciones de hardware virtual asignado para la VM.

            </p>

            <!-- IMAGEN 1: Configuración de la Máquina Virtual -->
            <img src="https://github.com/user-attachments/assets/252b231c-39fd-4c88-b312-d04c71cee212" alt="Captura de pantalla del proceso de instalación del Sistema Operativo Linux en VirtualBox/VMware, mostrando la configuración de red y recursos." class="w-full h-auto">

            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">1.2. Instalación y Configuración de MySQL Server</h4>

            <p class="text-gray-700 mb-4">

                Comandos y resultados de la instalación del servidor de base de datos y la creación del esquema inicial (`chinos_cafe`).

            </p>

            <!-- IMAGEN 2: Instalación y Configuración de MySQL Server -->
            <img src="https://github.com/user-attachments/assets/7b00aacc-b9c7-44fb-b863-ba88fd027387" alt="Terminal o herramienta de gestión mostrando la base de datos `chinos_cafe` y sus tablas principales." class="w-full h-auto">

        </section>



        <!-- SECCIÓN 2: REDES -->

        <section class="mb-10">

            <h3 id="redes" class="text-2xl font-bold text-blue-700 mb-4 section-header">II. Redes</h3>

            <p class="text-gray-700 mb-4">

                Diseño de la topología de Red LAN en Cisco Packet Tracer para la interconexión de los dos establecimientos con el Servidor de Datos centralizado (VM).

            </p>



            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">2.1. Topología de Red LAN (Cisco Packet Tracer)</h4>

            <p class="text-gray-700 mb-4">

                Diagrama que muestra la disposición física y lógica de los dispositivos (Servidor, Router, Switch, Laptops/PCs) y el esquema de cableado.

            </p>

            <!-- IMAGEN 3: Topología de Red LAN -->
            <img src="https://github.com/user-attachments/assets/3d35328b-ad52-403b-8e3b-29a14f58cb89" alt="Esquema de la Red LAN implementado en el simulador." class="w-full h-auto">

            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">2.2. Pruebas de Conectividad</h4>

            <p class="text-gray-700 mb-4">

                Validación del direccionamiento IP y la accesibilidad del Servidor de Datos desde un equipo cliente.

            </p>

            <!-- IMAGEN 4: Pruebas de Conectividad -->
            <img src="https://github.com/user-attachments/assets/29e917ba-1fd3-40aa-be10-20d490e2fc49" alt="Captura de la prueba de conectividad (`ping`) confirmando el acceso al Servidor (192.168.x.x)." class="w-full h-auto">

        </section>



        <!-- SECCIÓN 3: LÓGICA Y PSEUDOCÓDIGO -->

        <section class="mb-10">

            <h3 id="logica" class="text-2xl font-bold text-blue-700 mb-4 section-header">III. Lógica y Pseudocódigo</h3>

            <p class="text-gray-700 mb-4">

                Desarrollo de la lógica del sistema mediante pseudocódigo, enfocándose en los procesos clave como el menú principal, la gestión de inventario y el carrito de ventas.

            </p>



            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">3.1. Pseudocódigo del Flujo Principal</h4>

            <p class="text-gray-700 mb-4">

                Estructura del algoritmo principal que gestiona el flujo de la aplicación.

            </p>

            <pre class="code-block"><code class="text-cyan-400">Algoritmo SistemaGestionChinosCafe



    // Variables de estado del sistema (Sucursal y usuario)

    Definir ESTABLECIMIENTO_ID Como Entero

    Definir opcion_menu Como Entero

    ESTABLECIMIENTO_ID &lt;- 1 



    Repetir

        // Mostrar Menú Principal

        Escribir "=== SISTEMA CHINOS CAFE ==="

        Escribir "Sucursal Actual: ", ESTABLECIMIENTO_ID

        Escribir "1. Iniciar Sesión"

        Escribir "2. Ver Inventario"

        Escribir "3. Carrito de Venta y Cobro"

        Escribir "4. Cambiar Sucursal"

        Escribir "0. Salir"

        Escribir "Seleccione una opción: "

        Leer opcion_menu



        Segun opcion_menu Hacer

            1: Subproceso_Login() 

            2: Subproceso_VerInventario()

            3: Subproceso_CarritoVenta()

            4: Subproceso_CambiarSucursal()

            0: Escribir "Saliendo del sistema..."

            De Otro Modo: Escribir "Opción inválida."

        FinSegun

        

        Si opcion_menu &lt;&gt; 0 Entonces

            Esperar Tecla

        FinSi

    Hasta Que opcion_menu = 0



FinAlgoritmo</code></pre>



            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">3.2. Diagrama de Flujo del Proceso de Venta</h4>

            <p class="text-gray-700 mb-4">

                Diagrama que representa la lógica detallada del proceso de venta, desde la selección de artículos hasta el cobro.

            </p>

            <!-- IMAGEN 5: Diagrama de Flujo del Proceso de Venta -->
            <img src="https://github.com/user-attachments/assets/3d073dd5-ffe0-47c4-8631-bd70a0bb0df1" alt="Diagrama de Flujo del subproceso `Subproceso_CarritoVenta()`." class="w-full h-auto">

        </section>



        <!-- SECCIÓN 4: PROGRAMACIÓN EN PYTHON -->

        <section class="mb-10">

            <h3 id="python" class="text-2xl font-bold text-blue-700 mb-4 section-header">IV. Programación en Python</h3>

            <p class="text-gray-700 mb-4">

                Implementación de la solución en el lenguaje Python. Se incluye el módulo principal con la configuración de la conexión a la base de datos MySQL.

            </p>



            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">4.1. Conexión a Base de Datos y Módulo Principal en Python</h4>

            <p class="text-gray-700 mb-4">

                Código fuente del archivo principal (`main.py`) con la función del menú y la configuración para la conexión remota a MySQL.

            </p>

            <pre class="code-block"><code class="text-green-400"># python:gestion_chinos_cafe:main.py

# Se asume que la librería 'mysql.connector' está instalada (pip install mysql-connector-python)

import mysql.connector



# --- CONFIGURACIÓN DE CONEXIÓN (Adaptar a tu VM) ---

DB_CONFIG = {

    'user': 'chinos_user',

    'password': 'password_segura',

    'host': '192.168.1.10', # <--- IP del Servidor Linux/VM

    'database': 'chinos_cafe'

}



# --- FUNCIÓN DE CONEXIÓN ---

def conectar_db():

    """Intenta establecer conexión con la base de datos MySQL."""

    try:

        conn = mysql.connector.connect(**DB_CONFIG)

        print("Conexión a MySQL exitosa.")

        return conn

    except mysql.connector.Error as err:

        print(f"Error al conectar a MySQL: {err}")

        return None



# --- FUNCIÓN DE MENÚ PRINCIPAL ---

def main_menu():

    # [Aquí va la implementación completa de la función main_menu,

    # siguiendo el pseudocódigo de la sección III]

    print("\n# Código Python para el Menú Principal (Función main_menu) #")



# --- PUNTO DE ENTRADA ---

if __name__ == "__main__":

    # Prueba de la conexión al inicio

    conn = conectar_db()

    if conn:

        conn.close()

    

    main_menu()

    

# EOF del archivo main.py</code></pre>



            <h4 class="text-xl font-semibold text-gray-800 mt-6 mb-3">4.2. Interfaz y Ejecución</h4>

            <p class="text-gray-700 mb-4">

                Captura de la ejecución del programa, mostrando la interfaz de consola o la ventana de Tkinter (si se utilizó para la GUI).

            </p>

            <!-- IMAGEN 6: Interfaz y Ejecución -->
            <img src="https://github.com/user-attachments/assets/930905eb-0f35-411a-a39f-ea6059557d73" alt="Prototipo de la Interfaz de Usuario de la aplicación Python en ejecución." class="w-full h-auto">

        </section>



        <!-- CONCLUSIÓN -->

        <footer class="mt-10 pt-6 border-t border-gray-200">

            <h3 class="text-2xl font-bold text-gray-800 mb-4 section-header">Conclusión</h3>

            <p class="text-gray-600 italic">

                El proyecto cumple con los objetivos de integrar la configuración de infraestructura, el diseño de red, la lógica algorítmica y la programación. La implementación garantiza un punto de partida sólido y escalable para el sistema de gestión de CHINOS CAFE.

            </p>

        </footer>



    </div>



</body>

</html>
