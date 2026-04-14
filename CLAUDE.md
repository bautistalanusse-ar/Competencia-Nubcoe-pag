# CLAUDE.md — Instrucciones para Claude Code

## Sobre este proyecto
Repositorio de inteligencia competitiva y herramientas de gestión estratégica para **Nubceo**
(plataforma de gestión financiera, conciliación y control de ingresos para PyMEs y empresas).

## Stack y arquitectura
- Frontend estático: HTML + CSS vanilla (sin frameworks, para máxima portabilidad)
- Sin dependencias de terceros salvo las explícitamente aprobadas
- Todo el contenido debe funcionar offline (no CDN externos en producción)

## Convenciones de código
- Indentación: 2 espacios
- Variables CSS: siempre usar custom properties (`:root { --var: value }`)
- Nombres de archivos: snake_case en español (`reporte_competencia.html`)
- Commits: prefijo convencional (`feat:`, `fix:`, `docs:`, `refactor:`)

## Seguridad
- NUNCA incluir credenciales, API keys ni datos sensibles en el código
- Todo reporte marcado como "Confidencial Interno" — no subir a repos públicos
- Usar `.gitignore` para excluir archivos con datos reales de clientes

## Lo que NO hacer
- No crear archivos de documentación extra salvo que se pida explícitamente
- No agregar dependencias npm/yarn sin aprobación
- No cambiar el esquema de colores de Nubceo sin consultar

## Personas del equipo
- Reportes van dirigidos a: equipo de ventas y dirección de Nubceo
- Nivel técnico del lector: no técnico — usar lenguaje claro y visual
