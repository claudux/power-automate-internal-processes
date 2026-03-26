# Casos de automatización

## 1. Cometidos
Automatización del flujo interno de aprobaciones entre colaborador y jefatura. El proceso genera documentos PDF firmados digitalmente y envía correos automáticos a colaborador, jefatura y gestión de personas.

```mermaid
flowchart LR
    A[Colaborador solicita cometido] --> B[Jefatura aprueba]
    B --> C[Se genera PDF firmado digitalmente]
    C --> D[Se envia correo a Gestion de Personas]
    C --> E[Se envia correo a colaborador]
    E --> F[Colaborador informa cometido]
    F --> G[Jefatura aprueba cierre]
    G --> H[Se genera PDF firmado digitalmente]
    H --> I[Se envia correo a Gestion de Personas]
    H --> J[Se envia correo a colaborador]
```

## 2. Proyecto VAE
Automatización del flujo de información entre estudiantes, docentes y evaluadores. Permite gestionar los proyectos realizados por los estudiantes, generar documentos PDF digitales y distribuir correos de manera automática.

```mermaid
flowchart LR
    A[Estudiante crea VAE] --> B[Evaluadores revisan y aprueban]
    B --> C[Estudiante informa VAE]
    C --> D[Coordinador de sede finaliza]
    D --> E[Proceso aprobado]
```

## 3. Repactación Estudiantil
Automatización del flujo entre estudiantes y el área de finanzas. El proceso permite generar documentos digitales de repactación y enviar correos automáticos asociados al trámite.

```mermaid
flowchart LR
    A[Estudiante ingresa a la app] --> B[Configura pie y cuotas]
    B --> C[La app genera documento PDF]
    C --> D[Se informa al area de Finanzas]
    D --> E[Finanzas recibe correo]
    E --> F[Finanzas verifica pago del pie]
    F --> G[Autoriza matricula]
    G --> H[Se envia correo al estudiante]
```

## 4. Evaluación Docente
Automatización del flujo entre docentes y coordinadores. El proceso distribuye correos con documentos PDF de evaluación por docente, facilitando el seguimiento y la gestión documental.

```mermaid
flowchart LR
    A[Docente ingresa a la app] --> B[Revisa modulos, notas, comentarios y promedios]
    B --> C[Solicita detalle por correo]
    C --> D[Confirma su revision]
    D --> E[Coordinador recibe revision]
    E --> F[Sistema entrega metricas de revision]
```
