# 1. Modelo Conceptual - Caso Práctico 1

## Identificación de Entidades y Atributos

### Entidad: Empleado
- id_empleado (PK)
- nombre
- apellido
- dni
- fecha_nacimiento
- telefono
- direccion
- Fecha_Ingreso
- salario
- Estado_Empleado
- id_departamento (FK)
- id_puesto (FK)

### Entidad: Departamento
- id_departamento (PK)
- nombre
- descripcion
- ubicacion

### Entidad: Puesto
- id_puesto (PK)
- Título_Puesto
- Descripción
- Salario_Base
- Nivel
- id_departamento (FK)

---

## Relaciones entre Entidades

- Un empleado pertenece a un departamento (N:1)
- Un empleado ocupa un puesto (N:1)
- Un departamento tiene varios puestos (1:N)
