# GuyHard - TPS Combat & Weapon System

> **Status:** Legacy Project (2020)
> **Tech Stack:** Unity 3D, C#, Advanced Animation States, Rigging

Este proyecto es un prototipo avanzado de un *Third Person Shooter* (TPS) centrado en la versatilidad de combate y movimiento táctico. Un controlador en tercera persona avanzado. Desarrollado para estudiar la gestión de inventarios complejos y máquinas de estados en Unity.

### 🎥 Demo de Combate

![alt text](Media/gif1.gif) ![alt text](Media/gif2.gif)
![alt text](Media/gif3.gif) ![alt text](Media/gif4.gif)


https://github.com/user-attachments/assets/560ff72e-896a-48f2-bccf-646e18c36464



### 🔫 Sistemas Implementados (C#)

* **Arsenal Dinámico:** Sistema de inventario que permite cambiar en tiempo real entre varios tipos de armas con comportamientos balísticos únicos:
    * **Ranged:** Pistola, M4 (Automática), Escopeta (Dispersión), Sniper (Zoom/Scope).
    * **Melee:** Bate de béisbol y combate a puños.
* **Tactical Movement:**
    * **Cover System:** Detección de muros y objetos para entrar en modo cobertura automáticamente.
    * **Parkour & Climbing:** Sistema de escalada mediante *Raycast detection* para interactuar con el entorno vertical.
* **Cámara TPS:** Control de cámara suave con "Aim Offset" (la cámara se acerca al hombro al apuntar).
