# Dinosaur World – Escape

Prototipo jugable en navegador de exploración 3D, construido con Three.js y geometría 3D generada en tiempo de ejecución. No utiliza escenas 2D ni imágenes planas para sustituir los personajes.

## Ejecutar

Abre `index.html` en un navegador moderno con conexión a internet. Three.js se carga desde jsDelivr como módulo ES. Si el navegador bloquea módulos desde `file://`, sirve la carpeta con cualquier servidor estático, por ejemplo:

```bash
python -m http.server 8000
```

Luego visita `http://localhost:8000`.

## Controles

- **WASD**: movimiento
- **Ratón**: cámara en tercera persona (clic para capturar el cursor)
- **E**: interactuar, entrar/salir del laboratorio, recoger componentes y recuperar al dinosaurio
- **Shift**: correr
- **Esc**: liberar el cursor

## Incluye esta primera versión

- Escenario 3D explorable con carreteras, aceras, barrio, casas y bosque generado proceduralmente.
- Casa del protagonista con mobiliario, habitaciones y acceso interactivo al búnker subterráneo.
- Laboratorio con bancos de trabajo, pantallas, estanterías y robot humanoide 3D.
- Compsognathus 3D con movimiento y exploración procedural; al acercarse puede morder y activar un efecto visual temporal.
- Recogida de componentes y una interacción sencilla para mejorar el robot.
- Objetivo de misión actualizado al recuperar al dinosaurio.

## Alcance

Es un prototipo funcional con modelos procedurales y materiales/iluminación 3D, no una producción AAA ni una recreación fotorrealista: los modelos y animaciones aún requieren arte, texturas PBR y animación de calidad profesional. Las funciones se limitan a las implementadas aquí; no se simula un mundo persistente, IA avanzada, captura física ni exportación del dinosaurio a la isla.
