### 🔹 ¿Qué es una topología de red?

Es la **forma en que se organizan y conectan los dispositivos** (PCs, servidores, [[switches]], [[routers]], etc.) dentro de una red. Puede describirse en dos niveles:

- [[Física]]** → cómo están realmente los cables y dispositivos conectados.
    
- **[[Lógica]]** → cómo fluye la información entre los nodos.
    

---

### 🔹 Tipos principales de topologías

1. **Topología en Bus**
    
    - Todos los dispositivos comparten un único cable principal.
        
    - Ventaja: simple y barata.
        
    - Desventaja: si se corta el cable, toda la [[red]] cae.
        
2. **Topología en Estrella**
    
    - Todos los dispositivos se conectan a un dispositivo central (switch o hub).
        
    - Ventaja: fácil de instalar y administrar.
        
    - Desventaja: si falla el dispositivo central, se cae toda la red.
        
3. **Topología en Anillo**
    
    - Cada dispositivo se conecta con el siguiente formando un círculo.
        
    - Ventaja: el tráfico sigue un camino definido.
        
    - Desventaja: si se rompe un nodo, se corta el anillo (a menos que haya [[redundancia]]).
        
4. **Topología en Malla**
    
    - Cada dispositivo está conectado con varios otros.
        
    - Ventaja: muy tolerante a fallas.
        
    - Desventaja: costosa y compleja.
        
5. **Topología Árbol (Jerárquica)**
    
    - Combinación de estrella con bus: se organiza en niveles (ej. switches conectados a un switch principal).
        
    - Ventaja: escalable y ordenada.
        
    - Desventaja: si falla la raíz, se afecta la red entera.
        
6. **Topología Híbrida**
    
    - Mezcla de varias topologías (ej. malla + estrella).
        
    - Muy usada en redes modernas porque combina ventajas.
        

---

📌 En la práctica, la **estrella** y las **híbridas** son las más comunes en LAN modernas (con switches y routers).  
En grandes infraestructuras (datacenters, telecomunicaciones), se usan **malla y árbol** por redundancia.