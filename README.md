# 🦋 BK Dashboard - Estadísticas en Redes Sociales

Dashboard completo con OAuth automático para:
- **Instagram** (Meta Graph API)
- **Facebook** (Meta Graph API)
- **TikTok** (TikTok Display API)
- **Google Analytics 4**
- **Google Business Profile**

## 📊 Features

✅ Dashboard interactivo en tiempo real
✅ OAuth automático - autorización en 1 clic
✅ Gráficos y métricas por plataforma
✅ Sincronización automática diaria
✅ Vercel KV para almacenamiento
✅ Diseño responsivo y moderno

## 🚀 Quick Start

### 1. Instalar Node.js
Descargar desde [nodejs.org](https://nodejs.org) (LTS)

### 2. Clonar repositorio
```bash
git clone https://github.com/MonarcaGastronomia/bk-dashboard-production.git
cd bk-dashboard-production
npm install
```

### 3. Variables de entorno
Crear archivo `.env.local` con:
```
VERCEL_KV_URL=
VERCEL_KV_REST_API_URL=
VERCEL_KV_REST_API_TOKEN=

META_APP_ID=
META_APP_SECRET=
META_REDIRECT_URI=http://localhost:3000/api/auth/meta/callback

TIKTOK_CLIENT_ID=
TIKTOK_CLIENT_SECRET=
TIKTOK_REDIRECT_URI=http://localhost:3000/api/auth/tiktok/callback

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_REDIRECT_URI=http://localhost:3000/api/auth/google/callback
```

### 4. Correr en desarrollo
```bash
npm run dev
```

### 5. Deploy en Vercel
```bash
npm i -g vercel
vercel
```

## 📚 Documentación

- [Meta Graph API](https://developers.facebook.com/docs/instagram-api)
- [TikTok Display API](https://developers.tiktok.com/doc/)
- [Google Analytics 4](https://developers.google.com/analytics/devguides/collection/ga4)
- [Google Business Profile API](https://developers.google.com/my-business)

## ⚙️ Setup en Vercel

1. Conectar repositorio GitHub
2. Agregar variables de entorno
3. Deploy automático en cada push

## 📝 Status

- ✅ OAuth flows implementados
- ✅ Dashboard UI
- ⏳ Google Business Profile (en espera de aprobación)
- ⏳ Alertas por email

## 📧 Support

Para problemas, abre un issue en este repositorio.
