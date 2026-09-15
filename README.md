# morocho.ai — Demo Ekoparty 2026

Simulación interactiva de [morocho.ai](https://morocho.ai) para el **Start-up Zone** de Ekoparty 2026.

## ¿Qué es?

Una versión estática de morocho.ai que reproduce 3 casos reales de pentest automatizado con IA.  
No hay backend — todo corre en el navegador. Ideal para que los visitantes del stand vean el sistema en acción sin riesgo.

## Cómo usarlo

1. Abrí la página: [https://inakiSarobe.github.io/morochogithub/](https://inakiSarobe.github.io/morochogithub/)
2. Logueate con:
   - **Email:** `cliente@empresa.com`
   - **Contraseña:** `supersegura`
3. Elegí uno de los 3 engagements
4. Escribí cualquier cosa y dale "Enviar"
5. Mirá el ataque en vivo 🚀

## Casos incluidos

| Engagement | Tipo | Hallazgos | Máx. Severidad |
|---|---|---|---|
| elcinelunar.com | Aplicación Web | 6 | 🔴 Crítico |
| regalosdigital.com | E-commerce / API | 6 | 🔴 Crítico |
| 185.62.33.47 | API / Infraestructura | 6 | 🟠 Alto |

Los datos están **anonimizados** — no se muestran URLs, IPs ni nombres reales de los objetivos originales.

## Características

- Playback animado con comandos reales (nmap, curl, nikto, Playwright, etc.)
- Fases del ataque (Recon → Escaneo → Explotación → Reporte)
- Hallazgos con evidencia, impacto y remediación
- Contador de costo y tiempo simulado
- Se resetea al cerrar la página o hacer logout (cada visitante empieza de cero)
- Responsive (funciona en laptop y celular)

## Stack

HTML + CSS + JavaScript vanilla. Cero dependencias. Una sola página.

---

**morocho.ai** — Red Team con Inteligencia Artificial  
Ekoparty 2026 · Start-up Zone
