# 🤖 @jadepicom_bot - Bot de Moderación para Telegram

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)
[![Telegram](https://img.shields.io/badge/Telegram-Bot_API-blue.svg)](https://core.telegram.org/bots/api)
[![GitHub Actions](https://img.shields.io/badge/Hosted-GitHub_Actions-success.svg)](https://github.com/features/actions)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Un bot de moderación completo y potente para grupos de Telegram, con más de 20 comandos de administración, implementado 100% en Python y ejecutándose gratuitamente en GitHub Actions.

## ✨ Características Destacadas

- 🛡️ **Sistema completo de moderación** con ban, kick, advertencias y más
- 🤖 **Funciona 24/7** usando GitHub Actions de forma gratuita
- ⚡ **Configuración fácil** en menos de 5 minutos
- 🔧 **Más de 20 comandos** para gestionar tu comunidad
- 📊 **Mensajes de bienvenida**, reglas personalizables y sistema de reportes

## 🚀 Comenzar

### 1. Crear tu bot con @BotFather
- Busca `@BotFather` en Telegram
- Usa `/newbot` y sigue las instrucciones
- **Guarda el token** que te proporcionará

### 2. Configurar el repositorio
1. **Haz fork** de este repositorio
2. Ve a **Settings → Secrets → Actions**
3. Añade el secreto: `TELEGRAM_TOKEN` con tu token

### 3. Activar el bot
1. Ve a la pestaña **Actions**
2. Activa workflows en tu repositorio
3. Ejecuta manualmente el workflow **"Run Moderator Bot"**

### 4. Añadir a tu grupo
1. Añade [@jadepicom_bot](https://t.me/jadepicom_bot) a tu grupo
2. Concede permisos de **administrador completo**
3. ¡Listo! Tu bot está funcionando 🎉

## 🎯 Comandos Disponibles

### 👮‍♂️ Moderación de Usuarios
| Comando | Función |
|---------|---------|
| `/ban` | Banear usuario permanentemente |
| `/kick` | Expulsar usuario del grupo |
| `/mute` | Silenciar usuario temporalmente |
| `/warn` | Advertir a usuario |
| `/unban` | Desbanear usuario |

### ⚙️ Gestión del Grupo
| Comando | Función |
|---------|---------|
| `/setrules` | Establecer reglas del grupo |
| `/setwelcome` | Configurar mensaje de bienvenida |
| `/lock` | Bloquear ciertos tipos de mensaje |
| `/pin` | Fijar mensaje importante |

### 📊 Información
| Comando | Función |
|---------|---------|
| `/info` | Ver información de usuario |
| `/id` | Obtener ID del chat/usuario |
| `/stats` | Ver estadísticas del grupo |
| `/admins` | Listar administradores |

## 🛠️ Tecnologías Utilizadas

- **Python 3.10+** - Lenguaje de programación principal
- **python-telegram-bot** - Biblioteca oficial de Telegram Bot API
- **GitHub Actions** - Ejecución y hosting gratuito
- **Telegram Bot API** - Plataforma de mensajería

## 📁 Estructura del Proyecto

```
bot-moderacion-telegram/
├── .github/workflows/
│   └── bot.yml              # Configuración de GitHub Actions
├── bot.py                   # Código principal del bot
├── requirements.txt         # Dependencias de Python
└── README.md               # Este archivo
```

## 🌟 Características Técnicas

- ✅ **Detección automática de spam**
- ✅ **Protección contra flood**
- ✅ **Sistema de advertencias escalable**
- ✅ **Registro de acciones de moderación**
- ✅ **Mensajes personalizables**
- ✅ **Compatibilidad con múltiples grupos**

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si quieres mejorar este bot:

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## ⚠️ Notas Importantes

- El bot necesita permisos de **administrador completo** para funcionar correctamente
- GitHub Actions tiene un límite de **6 horas por ejecución**
- Los datos se almacenan en memoria (se reinician cada 6 horas)
- Para uso production, considera un hosting 24/7

## 🆘 Soporte

Si tienes problemas o preguntas:
1. Revisa los [issues](https://github.com/tuusuario/bot-moderacion-telegram/issues)
2. Crea un nuevo issue describiendo tu problema
3. Contacta por Telegram: [@jadepicom_bot](https://t.me/jadepicom_bot)

---

**¿Te gusta el proyecto?** ¡Dale una ⭐ en GitHub y compártelo con otros administradores de grupos!

> **Nota**: Este bot está diseñado para ayudar a moderar comunidades de Telegram de forma efectiva y automática.
