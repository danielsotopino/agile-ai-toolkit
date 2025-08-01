# Agile AI Toolkit

**Herramientas de IA para Desarrollo Ágil**

Un conjunto completo de herramientas que utilizan IA para generar historias de usuario y casos de prueba automáticamente, optimizando el proceso de desarrollo ágil de principio a fin.

## 🛠️ Herramientas Incluidas

### 📚 Generador de Historias de Usuario
- **Análisis inteligente** de requerimientos con preguntas de clarificación
- **Proceso híbrido**: Requerimiento → Análisis → Historias
- **Criterios INVEST**: Historias que siguen buenas prácticas
- **Edición completa**: Modifica títulos, roles, criterios y prioridades
- **Descomposición inteligente**: 1-8 historias según complejidad

### 🛡️ Generador de Casos de Prueba
- **Múltiples tipos**: Positivos, negativos, edge cases, regresión y no impacto
- **Generación iterativa**: Agrega más casos basándose en los existentes
- **Formato estándar**: Compatible con equipos de QA
- **Exportación múltiple**: Google Sheets y Markdown

## 🚀 Características Principales

- **Múltiples proveedores de IA**: OpenAI, Anthropic, Google Gemini, OpenRouter y configuración personalizada
- **Sin instalación**: Funciona completamente en el navegador
- **Privacidad total**: Tus datos no se almacenan, solo se envían a la IA que elijas
- **Exportación versátil**: JIRA, Azure DevOps, Google Sheets, Markdown
- **Diseño responsive**: Funciona en cualquier dispositivo

## 📖 Flujo de Trabajo Recomendado

```
1. Requerimiento → 2. Historias de Usuario → 3. Casos de Prueba → 4. Implementación
```

1. **Describe tu requerimiento** en lenguaje natural
2. **Genera historias estructuradas** siguiendo criterios INVEST
3. **Crea casos de prueba comprensivos** para validar la implementación
4. **Desarrolla con confianza** sabiendo qué y cómo probar

## 🔑 APIs Soportadas

- **OpenAI**: GPT-4, GPT-4o, GPT-4o Mini
- **Anthropic**: Claude 3 Opus, Sonnet, Haiku
- **Google**: Gemini 1.5 Pro, Gemini 1.5 Flash
- **OpenRouter**: Acceso a múltiples modelos con una sola API key
- **Personalizado**: Configura tu propio endpoint compatible con OpenAI

## 💰 Opciones de Costo

### Modelos Económicos (Recomendados)
- **GPT-4o Mini**: ~$0.15 por 1M tokens de entrada
- **Claude 3 Haiku**: ~$0.25 por 1M tokens de entrada  
- **Gemini 1.5 Flash**: ~$0.075 por 1M tokens de entrada
- **Llama 3.1 8B**: Gratis en OpenRouter

### Modelos Premium (Mayor Calidad)
- **GPT-4o**: Para resultados más sofisticados
- **Claude 3 Sonnet**: Equilibrio entre calidad y costo
- **Gemini 1.5 Pro**: Para análisis complejos

## 📝 Ejemplos de Uso

### Entrada: Requerimiento
```
Agregar campo tipos de sección en español para permitir a los usuarios 
seleccionar categorías en su idioma nativo en la interfaz de administración.
```

### Proceso: Análisis Automático
La IA genera preguntas como:
- ¿Qué tipos de sección específicos necesitas?
- ¿Cómo debe integrarse con el sistema existente?
- ¿Qué validaciones son necesarias?

### Salida: Historias de Usuario
```
Historia 1: Configuración de Tipos de Sección
Como administrador del sistema
Quiero configurar tipos de sección en español
Para que los usuarios puedan seleccionar categorías en su idioma nativo

Criterios de Aceptación:
- Debe mostrar una interfaz para agregar tipos de sección
- Debe permitir ingresar nombres en español
- Debe validar que no existan duplicados
```

### Resultado: Casos de Prueba
```
Caso 1: Validar creación exitosa de tipo de sección
Precondiciones: Usuario administrador logueado
Procedimiento: 
1. Acceder a configuración de tipos
2. Ingresar "Noticias Deportivas" 
3. Hacer clic en Guardar
Resultado esperado: Tipo creado correctamente con mensaje de confirmación
```

## 🌐 Acceso

### GitHub Pages
- **Página principal**: [https://tu-usuario.github.io/agile-ai-toolkit/](https://tu-usuario.github.io/agile-ai-toolkit/)
- **Historias de Usuario**: [generador-historias-usuario.html](https://tu-usuario.github.io/agile-ai-toolkit/generador-historias-usuario.html)
- **Casos de Prueba**: [generador-casos-prueba.html](https://tu-usuario.github.io/agile-ai-toolkit/generador-casos-prueba.html)

### Uso Local
1. Clona el repositorio: `git clone https://github.com/tu-usuario/agile-ai-toolkit.git`
2. Abre `index.html` en tu navegador
3. Configura tu API key y ¡comienza a usar!

## 🔒 Privacidad y Seguridad

- **Sin servidor**: Todo funciona en tu navegador
- **Sin almacenamiento**: No guardamos tus datos ni API keys
- **Comunicación directa**: Tus datos van directo a la IA que elijas
- **Control total**: Tú decides qué servicio usar y qué datos enviar

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Algunas ideas para mejoras:

- **Nuevos proveedores de IA**: Integrar más servicios
- **Plantillas personalizadas**: Templates para diferentes industrias
- **Integraciones**: Conectores directos con JIRA/Azure DevOps
- **Idiomas adicionales**: Soporte multiidioma
- **Métricas**: Analytics de calidad de historias/casos

## 📄 Licencia

MIT License - Libre para uso personal y comercial.

## 🛟 Soporte

¿Problemas o sugerencias? 
- Abre un [Issue](https://github.com/tu-usuario/agile-ai-toolkit/issues)
- Revisa la documentación en cada herramienta
- Verifica tu configuración de API key

---

**Desarrollado con ❤️ para equipos de desarrollo que buscan optimizar su proceso de trabajo ágil.**