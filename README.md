# Diseños e Implementación de Red LAN Empresarial con Conectividad WAN/Internet

## Descripción del Proyecto
Este proyecto consiste en la planificación, diseño e implementación de una infraestructura de red local (LAN) empresarial con segmentos cableados e inalámbricos, interconectados hacia una salida a Internet simulada mediante **Cisco Packet Tracer**.

##  Tecnologías y Dispositivos Utilizados
- **Simulador:** Cisco Packet Tracer v8.x
- **Enrutamiento (Capa 3):** Router Cisco ISR 4331
- **Conmutación (Capa 2):** Switch Cisco Catalyst 2960-24TT
- **Acceso Inalámbrico:** Access Point (IEEE 802.11 Wi-Fi)
- **Dispositivos Finales:** 10 PCs, Impresora de red, Smartphones
- **Medios de Transmisión:** Cableado UTP Cat 5e/6 (Ethernet Directo) y ondas de Radiofrecuencia (Wi-Fi)

## Topología de Red (Diagrama Conceptual)
<img width="1920" height="1080" alt="Topologia de red" src="https://github.com/user-attachments/assets/c4550368-5ff6-498f-a71a-bdb588e51fc7" />


## Esquema de Direccionamiento IP
- **Red LAN:** `192.168.1.0/24`
- **Puerta de Enlace (Gateway):** `192.168.1.1`
- **Mascara de Subred:** `255.255.255.0`
- **Rango de Direcciones:**
  - PCs: `192.168.1.10` - `192.168.1.19`
  - Impresora de Red: `192.168.1.20`
  - Dispositivos Móviles: `192.168.1.30` - `192.168.1.31`
  - Enlace WAN / Router a Internet: `200.100.10.1/24`

##  Evidencia de Implementación en Cisco Packet Tracer
<img width="654" height="439" alt="RED" src="https://github.com/user-attachments/assets/0c8b7d56-be73-462c-854d-10f4de01bbc4" />


##  Funcionalidades y Configuración Realizada
1. Configuración de interfaces GigabitEthernet en Router mediante línea de comandos (CLI).
2. Asignación estática de direcciones IP y Gateway en todos los dispositivos finales.
3. Integración de dispositivos inalámbricos mediante Access Point (Wi-Fi).
4. Verificación de conectividad mediante pruebas PDU (ICMP Ping) entre segmentos LAN y WAN.
