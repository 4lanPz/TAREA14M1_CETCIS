# TAREA14M1_CETCIS

** Problema 1: Cola Básica

Se implementó una cola utilizando una lista enlazada.
Cada nodo contiene:
- un dato
- una referencia al siguiente nodo

Métodos implementados:
- enqueue: agrega elementos al final
- dequeue: elimina el elemento del frente
- front: muestra el primer elemento sin eliminarlo
- is_empty: verifica si la cola está vacía
- size: retorna el número de elementos

** Problema 2: Cola Circular (Round Robin)

Se implementó una cola circular para simular la ejecución de procesos.
Cada proceso tiene:
- nombre
- tiempo de ejecución

Se utilizó el algoritmo Round Robin con un quantum de 3 unidades, donde:
- Cada proceso se ejecuta por un tiempo fijo
- Si no termina, vuelve al final de la cola
- Si termina, se elimina

** Problema 3: Cola de Prioridad (Emergencias)

Se implementó una cola de prioridad usando 5 colas simples, una para cada nivel de urgencia (1 a 5).
- Los pacientes se agregan según su nivel de urgencia
- Se atienden primero los de mayor prioridad (nivel 1)
- Si tienen la misma prioridad, se respeta el orden de llegada

Incluye un menú interactivo para:
- Atender pacientes
- Visualizar la lista de espera

** Problema 4: Aplicación Real (Banco)

Se desarrolló un sistema de atención en un banco utilizando:
- Colas de prioridad
- Colas simples por tipo de servicio

Servicios:
- Caja
- Préstamos
- Consultas

Los clientes pueden ser normales o con prioridad:
-Se atiende primero a los clientes con prioridad
- Se respeta el orden de llegada dentro de cada grupo

Se implementó un menú interactivo que permite:
- Registrar clientes
- Atender clientes por área
- Visualizar el estado de las colas
