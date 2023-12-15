# Empresa

Crea un programa que permita gestionar una empresa

## Beans

### Empresa

Campos:
- Nombre
- CIF
- Departamentos

### Departamento

Campos:
- Nombre
- Presupuesto
- Empleados

### Empleado

Campos:
- NIF
- Nombre
- Apellidos
- Puesto (programador, jefe de proyecto...)

## Componentes

### Readers

Haz un reader por cada bean

### CompanyApp

Debe tener un método run() que haga:
- Pide los datos de la empresa
- Inicia un bucle de menú con las siguientes opciones:
  - Dado un nombre de departamento, mostrar todos sus datos. Si no existe el departamento mostrar "No se encuentra el departamento"
  - Mostrar los empleados de un departamento dado su nombre. Si no existe el departamento mostrar "No se encuentra el departamento"  
  - Dado un nif, muestra los datos del empleado. En caso de que el empleado no exista muestra el mensaje "NO se encuentra el empleado".
