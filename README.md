# Gestion-vaccins-enfants
Application de gestion des vaccins des enfants 0-5 ans (Laravel 13 + Flutter)
# Gestion des Vaccins des Enfants (0-5 ans)

## 🏥 Description
Application mobile et backend pour gérer les vaccins des enfants de 0 à 5 ans au Cameroun.  
- Suivi des vaccinations par enfant  
- Notifications / rappels pour les parents  
- Gestion des centres de santé et agents  
- Statistiques et tableau de bord

**Stack :**
- Backend : Laravel 13 + PHP 8.3 + PostgreSQL (Supabase)  
- Frontend : Flutter  
- Auth : Laravel Sanctum  
- Notifications : Firebase Cloud Messaging + SMS via Twilio / API locale  
- Tests : PHPUnit / Flutter Test  

---

## 📁 Structure du dépôt

```text
gestion-vaccins-enfants/
├─ backend/        # Laravel 13 API
│   ├─ app/
│   ├─ routes/
│   ├─ database/
│   └─ .env.example
├─ frontend/       # Flutter mobile app
│   ├─ lib/
│   ├─ pubspec.yaml
│   └─ ...
└─ README.md
