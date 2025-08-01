# Generador de Casos de Prueba

Un generador automático de casos de prueba que utiliza IA para crear casos detallados a partir de historias de usuario y criterios de aceptación.

## 🚀 Características

- **Múltiples proveedores de IA**: OpenAI, Anthropic, Google Gemini, OpenRouter y configuración personalizada
- **Tipos de casos**: Positivos, negativos, edge cases, no impacto y regresión
- **Generación iterativa**: Agrega más casos basándose en los existentes
- **Exportación fácil**: Google Sheets y Markdown
- **Sin instalación**: Funciona directamente en el navegador

## 📖 Cómo usar

1. Abre el archivo `generador-casos-prueba.html` en tu navegador
2. Configura tu proveedor de IA y API key
3. Pega el contenido completo (ID JIRA + Historia de Usuario + Criterios de Aceptación)
4. Selecciona los tipos de casos que quieres generar
5. ¡Genera y exporta tus casos de prueba!

## 🔑 APIs soportadas

- **OpenAI**: Requiere API key de OpenAI
- **Anthropic**: Requiere API key de Claude
- **Google**: Requiere API key de Google AI Studio
- **OpenRouter**: Una API key para múltiples modelos
- **Personalizado**: Configura tu propio endpoint

## 💰 Costos

La herramienta incluye modelos de bajo costo como:
- GPT-4o Mini
- Claude 3 Haiku  
- Gemini 1.5 Flash
- Llama 3.1 8B (gratis en OpenRouter)

## 📝 Ejemplo de uso

```
DRAC-1557

Como usuario registrado, quiero poder iniciar sesión en el sistema para acceder a mi perfil personal

Criterios de Aceptación:
- El usuario debe poder ingresar email y contraseña
- El sistema debe validar las credenciales
- Si las credenciales son correctas, redirigir al dashboard
- Si las credenciales son incorrectas, mostrar mensaje de error
```

## 🌐 Demo en vivo

[Ver demo aquí](https://danielsotopino.github.io/test-case-generator/)