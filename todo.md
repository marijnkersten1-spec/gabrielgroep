# Gabriël Groep Platform — TODO

## Phase 2: Database Schema & Design System
- [x] Extended database schema (members, events, news, photos, documents, attendance, equipment)
- [x] Design system: navy/gold color palette, typography, global CSS
- [x] Google Fonts integration (Inter + Playfair Display)

## Phase 3: Public Website
- [x] Navigation bar (responsive, mobile hamburger)
- [x] Home page: hero, features, speltakken, CTA
- [x] About Us page
- [x] Join / Lid Worden page with registration form
- [x] News page with article cards
- [x] Contact page with Google Maps

## Phase 4: Public Agenda & Gallery
- [x] Public event calendar / agenda page
- [x] Photo gallery page with lightbox
- [x] Footer component

## Phase 5: Member Portal
- [x] Login / auth flow (Manus OAuth)
- [x] Member dashboard landing
- [x] Age-group specific calendars (Dolfijnen, Verkenners, Wilde Vaart)
- [x] Camp registration / event registration
- [x] Document downloads section
- [x] Internal news feed
- [x] GDPR consent fields on user table

## Phase 6: Staff Dashboard
- [x] Staff layout with sidebar (PortaalLayout)
- [x] Member management (list, filter, edit speltak/role)
- [x] Activity / event creation and management
- [x] Boat & equipment inventory management
- [x] Staff dashboard with overview stats

## Phase 7: Admin Dashboard
- [x] Admin dashboard with system stats
- [x] User role management (promote to staff/admin)
- [x] News publishing (create, publish/unpublish, delete)
- [x] User administration with speltak assignment

## Phase 8: Polish & Tests
- [x] Mobile-first responsive design throughout
- [x] Vitest unit tests (16 tests passing)
- [x] SpeltakBadge reusable component
- [x] All routes wired in App.tsx
- [x] Checkpoint & delivery


## Bugs & Fixes
- [x] Add Navbar component to all public pages (Home, OverOns, LidWorden, Nieuws, Contact, Agenda, Fotos)
- [x] Add new pages to App.tsx routes
- [x] Add new pages to Navbar navigation


## Phase 9: New Features & Admin Enhancements
- [x] Verhuur (Rental) page: event calendar + 2 room photo galleries
- [x] Admin submissions view: see all join form and contact form submissions
- [x] De Vloot (Fleet) page: boat inventory showcase with photos and specs
- [x] Mookse Zeilweek (Event Showcase) page: camp/event details and photos
- [x] Navigation links updated for all new pages


## Phase 10: Member Approval Workflow
- [x] Build Staff member approval page (/portaal/staf/aanmeldingen)
- [x] Display pending join requests with child/parent details
- [x] Approve/reject functionality with status updates
- [x] Email notifications to parents on approval/rejection (via backend)
- [x] Add link to approval page in Staff dashboard


## Critical Bugs to Fix
- [x] Photo upload system for staff (Fotos, Vloot, Verhuur galerijen) — StafFotos page built
- [x] Join form submission working — LidWorden form is functional
- [x] Aanmeldingen/submissions visible — AdminInzendingen page shows all submissions
- [x] Multi-day events supported in agenda — Agenda now handles multi-day events
- [ ] Event creation UI for Verhuur agenda
- [ ] Event creation UI for Vloot page


## Phase 11: Admin Features & Notifications
- [x] Admin photo album management section on AdminDashboard (/portaal/admin/fotos)
- [x] Email notifications when member signup form is submitted (via notifyOwner)


## Phase 12: Email Verification & Testing
- [x] Verify email notifications are sent on join form submission (via notifyOwner)
- [x] Test confirmation screen after signup (green checkmark screen visible)
- [x] Ensure notifyOwner sends email to admin/owner (Manus Notification Service)


## Phase 13: Admin Photo Upload on Public Pages
- [x] Add admin-only photo upload to Verhuur page (Ruimte 1 & 2)
- [x] Add admin-only photo upload to Fotos page
- [x] Add admin-only photo upload to De Vloot page
- [x] Display uploaded photos in galleries

## Phase 14: De Vloot Page Rebuild
- [x] Add all 6 boat descriptions (Sextant, Klipkruiper, Thor, Kontiki, Celsius, Boeibonker II)
- [x] Add technical specifications for each boat
- [x] Add expandable accordion for each boat
- [x] Add photo gallery for each boat with admin upload
- [x] Match Gabriel Groep website content and layout


## Phase 15: Home Page & Registration Fixes
- [x] Add hero image to Home page beginning
- [x] Debug and fix registration/join form submission
- [x] Verify form data is saved to database
- [x] Test confirmation screen after submission

## Bug Fixes: Join Form & Admin Submissions
- [x] Fix: join form completely rewritten with clear confirmation screen
- [x] Fix: infinite loop on Home page (unstable date reference)
- [x] Fix: sidebar now includes Aanmeldingen, Foto's Beheer, Inzendingen, Foto Albums links
- [x] Fix: AdminInzendingen accessible via /portaal/admin/inzendingen

## Phase 16: Photo Gallery & Admin Panel Overhaul
- [ ] Photo gallery: full CRUD (create/rename/delete albums, upload/rename/delete photos)
- [ ] Photo gallery: backend procedures for delete photo, rename photo, rename album, delete album
- [ ] AdminFotos: complete management UI with all CRUD operations
- [ ] AdminDashboard: audit and fix all stats and quick links
- [ ] AdminNieuws: audit create/edit/delete/publish flow
- [ ] AdminGebruikers: audit role management and user list
- [ ] AdminInzendingen: audit join + contact submissions view
- [ ] StafFotos: audit upload and gallery management

## Phase 17: Verhuur Agenda Admin
- [x] Admin page for managing Verhuur events (create, edit, delete)
- [x] Add route and sidebar link for Verhuur Agenda admin
- [x] Added rental type to event schema and database

## Phase 18: Verhuur Agenda Koppeling
- [x] Connect public Verhuur page agenda to rental events from database (filter on type=rental)

## Phase 19: Calendar & Admin Fixes
- [ ] Show dot on calendar days that have rental events
- [ ] Multi-day events: show dot on ALL days between start and end date
- [ ] Fix text input bug in admin activity creation (only 1 letter allowed)
