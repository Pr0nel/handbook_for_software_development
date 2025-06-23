```mermaid
graph TD

subgraph Paradigmas_de_Programación

A[Imperativo] --> A1(Procedural)

A --> A2(Orientado a Objetos - POO)

B[Declarativo] --> B1(Funcional)

B --> B2(Lógico)

B --> B3(Bases de Datos - SQL)

end

subgraph Estructuras_de_Datos

C[Lineales] --> C1(Arreglos/Arrays)

C --> C2(Listas Enlazadas)

C --> C3(Pilas - Stack)

C --> C4(Colas - Queue)

D[No Lineales] --> D1(Árboles)

D --> D2(Grafos)

D --> D3(Tablas Hash/Mapas)

end

subgraph Algoritmos

E[Ordenamiento] --> E1(Bubble Sort, Quick Sort, Merge Sort)

F[Búsqueda] --> F1(Lineal, Binaria)

G[Recorrido de Grafos] --> G1(DFS: Búsqueda en Profundidad, BFS: Búsqueda en Amplitud)

H[Optimización] --> H1(Programación Dinámica, Greedy: Codiciosa o Voraz)

I[Manipulación de Estructuras] --> I5(Inserción, Eliminación, Recorrido)

end

subgraph Conceptualización del Problema

P[Problema del Mundo Real] --> S{Solución}

end

S -->|Define la Lógica con| Algoritmos

Algoritmos -->|Implementados según un| Paradigmas_de_Programación
Algoritmos -->|Operan sobre| Estructuras_de_Datos

Paradigmas_de_Programación -->|Influyen en la Implementación de| Estructuras_de_Datos
Paradigmas_de_Programación -->|Influyen en el Diseño de| Algoritmos

Estructuras_de_Datos -->|Modeladas según un| Paradigmas_de_Programación
Estructuras_de_Datos -->|Optimizan y Habilitan| Algoritmos
```

<!-- end list -->

## Licencia

Este contenido (incluyendo los diagramas) está bajo la licencia [Creative Commons Atribución-NoComercial 4.0 Internacional](https://creativecommons.org/licenses/by-nc/4.0/).
