🚀 CRM Dashboard

Dashboard profesional de gestión de clientes construido con React, TypeScript y TanStack Query. Diseñado para demostrar arquitectura limpia, patrones modernos y UX profesional.

![CRM Dashboard](https://via.placeholder.com/800x400/1a1a1a/c17f3e?text=CRM+Dashboard+Preview)

## ✨ Características

### 🎯 Funcionalidades Core
- ✅ **Autenticación** - Sistema de login con validación
- ✅ **CRUD Completo** - Crear, leer, actualizar y eliminar clientes
- ✅ **Búsqueda en tiempo real** - Con debounce optimizado
- ✅ **Filtros avanzados** - Por estado (activo, pendiente, inactivo)
- ✅ **Paginación** - Navegación eficiente de grandes datasets
- ✅ **Exportar a CSV** - Descarga de datos para análisis externo
- ✅ **Dashboard con métricas** - Estadísticas y gráficos interactivos

### 🎨 UX/UI
- ✅ **Tema oscuro profesional** - Inspirado en Claude AI
- ✅ **Validación de formularios** - Con Zod y mensajes descriptivos
- ✅ **Notificaciones toast** - Feedback visual para todas las acciones
- ✅ **Skeleton loaders** - Estados de carga elegantes
- ✅ **Animaciones suaves** - Transiciones y micro-interacciones
- ✅ **Atajos de teclado** - `N` para nuevo cliente, `/` para buscar
- ✅ **Responsive design** - Adaptado a todos los dispositivos

### 🏗️ Arquitectura Técnica
- ✅ **TypeScript** - Tipado estático completo
- ✅ **React Query** - Gestión de estado del servidor con caché
- ✅ **Custom hooks** - Lógica reutilizable y separación de concerns
- ✅ **Error boundaries** - Manejo robusto de errores
- ✅ **Optimistic updates** - UX instantáneo
- ✅ **Clean architecture** - Separación por features

## 🛠️ Stack Tecnológico

### Frontend
- **React 18** - Biblioteca UI
- **TypeScript** - Tipado estático
- **Vite** - Build tool ultrarrápido
- **TanStack Query** - Gestión de estado servidor
- **React Router** - Enrutamiento
- **React Hook Form** - Gestión de formularios
- **Zod** - Validación de esquemas

### Styling
- **Tailwind CSS** - Utility-first CSS
- **Lucide React** - Iconos modernos
- **Recharts** - Gráficos y visualizaciones

### Otros
- **Axios** - Cliente HTTP
- **React Hot Toast** - Notificaciones
- **ESLint** - Linter

## 📦 Instalación
```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/crm-dashboard.git
cd crm-dashboard

# Instalar dependencias
npm install

# Configurar variables de entorno
echo "VITE_MOCK_API=true" > .env

# Iniciar servidor de desarrollo
npm run dev
```

## 🎮 Uso

### Credenciales de Demo
- **Email:** admin@crm.com
- **Password:** admin123

### Atajos de Teclado
- `N` - Crear nuevo cliente
- `/` - Focus en buscador
- `ESC` - Cerrar modales

## 📁 Estructura del Proyecto
```
crm-dashboard/
├── src/
│   ├── api/              # Lógica de API y datos mock
│   ├── components/       # Componentes compartidos
│   ├── features/         # Features organizadas por dominio
│   │   ├── auth/
│   │   └── customers/
│   ├── hooks/            # Custom hooks globales
│   ├── pages/            # Páginas de la aplicación
│   ├── routes/           # Configuración de rutas
│   ├── schemas/          # Esquemas de validación Zod
│   ├── types/            # Tipos TypeScript
│   └── utils/            # Utilidades
├── public/               # Assets estáticos
└── ...configs           # Configuraciones (vite, ts, tailwind)
```

## 🚀 Scripts
```bash
npm run dev        # Servidor de desarrollo
npm run build      # Build de producción
npm run preview    # Preview del build
npm run lint       # Ejecutar linter
```

## 🎯 Roadmap Futuro

- [ ] Tests unitarios con Vitest
- [ ] Tests E2E con Playwright
- [ ] Backend real con Node.js/Express
- [ ] Base de datos PostgreSQL
- [ ] JWT authentication real
- [ ] Subida de avatares de clientes
- [ ] Timeline de actividad por cliente
- [ ] Exportar a PDF/Excel
- [ ] Dark/Light theme toggle

## 📄 Licencia

MIT License - Siéntete libre de usar este proyecto para tu portfolio.

## 👤 Autor

**Pau Ventura**
- Portfolio: https://portfolio-pau-ventura.netlify.app/
- LinkedIn: https://www.linkedin.com/in/pau-ventura-612450250/
- GitHub: https://github.com/PauVentura30

---

⭐ Si este proyecto te ha sido útil, considera darle una estrella en GitHub!
