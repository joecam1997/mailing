
# Prueba Técnica Frontend - Mailing

## Descripción del Proyecto
Este proyecto consiste en la construcción desde cero de una **plantilla de mailing** para invitar a un evento institucional, utilizando **MJML** como framework principal.  
La plantilla está diseñada para ser:

- **Responsive** y compatible con Gmail, Yahoo, Outlook y Apple Mail (opcional).  
- **Escalable y reutilizable**, permitiendo agregar fácilmente nuevos idiomas y países.  
- **Coherente visualmente** con el Sistema de Diseño (SD) institucional, aplicando colores, tipografía, botones y bloques definidos en el SD.

---

## Contenido del Mailing

### Español
- **Título:** “Innovación Tecnológica 2025”  
- **Texto principal:** Te invitamos a participar en nuestro evento anual donde exploraremos las últimas tendencias en tecnología e innovación. Será una oportunidad única para conectar con expertos de la industria y descubrir nuevas herramientas para tu organización.  
- **Fecha y hora:** 25 de Octubre de 2025, 14h00  
- **CTA:** Regístrate ahora  
- **Footer Ecuador:** Av. Amazonas N34-232 y Av. Colón, Quito – Ecuador  
- **Footer Colombia:** Cra. 7 #32-16, Bogotá – Colombia  

### English
- **Title:** “Technology Innovation 2025”  
- **Main text:** Join us for our annual event where we will explore the latest trends in technology and innovation. It will be a unique opportunity to connect with industry experts and discover new tools for your organization.  
- **Date and time:** October 25th, 2025, 14h00  
- **CTA:** Register now  
- **Footer Ecuador:** Av. Amazonas N34-232 and Av. Colón, Quito – Ecuador  
- **Footer Colombia:** Cra. 7 #32-16, Bogotá – Colombia  

---

## Características Principales

- **Framework:** MJML (Mailjet Markup Language)  
- **Responsive:** Adaptable a dispositivos móviles y desktop.  
- **Compatibilidad:** Gmail, Yahoo, Outlook, Apple Mail (opcional).  
- **Escalabilidad:** Se pueden agregar nuevos idiomas y países fácilmente.  
- **Reutilización:** Componentes y bloques definidos con clases y variables CSS para mantener consistencia visual.  
- **Configuración de estilos:** Basada en el Sistema de Diseño institucional.

---

## Estructura del Proyecto

```

mailing/
├─ src/
│  ├─ templates/
│  │  ├─ es/
│  │  │  └─ evento.mjml
│  │  └─ en/
│  │     └─ evento.mjml
│  └─ partials/
│     ├─ header.mjml
│     ├─ footer-ec.mjml
│     └─ footer-co.mjml
├─ dist/
│  └─ evento.html
├─ package.json
└─ README.md

````

- `src/templates/` → Plantillas MJML separadas por idioma.  
- `src/partials/` → Bloques reutilizables (header, footer por país).  
- `dist/` → HTML compilado final listo para enviar por correo.  
- `package.json` → Configuración de proyecto y scripts de compilación.  

---

## Comandos para Uso y Desarrollo

### 1. Instalar dependencias
```bash
npm install
````

### 2. Compilar MJML a HTML

```bash
npm run build
```

> Genera los archivos HTML finales en la carpeta `dist/`.

### 3. Vista previa en navegador

```bash
npm run preview
```

> Permite abrir la plantilla en tu navegador antes de enviar el mailing.

### 4. Validación y testing

* Asegúrate de que la plantilla se vea correctamente en:

  * Gmail
  * Yahoo
  * Outlook
  * Apple Mail (opcional)

---

## Notas Adicionales

* Se recomienda mantener los archivos **.mjml** separados por idioma y país para facilitar escalabilidad.
* Se deben seguir los estilos definidos en el Sistema de Diseño institucional para mantener coherencia visual.
* Los botones CTA y bloques de contenido utilizan **clases reutilizables** para que sean fáciles de modificar o duplicar.

---

## Entrega

* **HTML final compilado:** Carpeta `dist/`
---

**Tecnologías utilizadas:**

* [MJML](https://mjml.io/)
* Node.js (para scripts de compilación)
* HTML/CSS (para personalización adicional)



¿Quieres que haga eso?
```
