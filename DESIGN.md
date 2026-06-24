# Rapi Laundry — Design Guidelines

## Design Principles
- Clean, practical, trustworthy. Calm and efficient — operational tool, not a consumer toy.
- Information-dense but legible: the owner dashboard must surface branch status at a glance.
- Mobile-first for branch managers (photo upload, checklists on the go); comfortable on desktop for the owner dashboard.

## Color
- **Primary**: Fresh, trustworthy blue — `#2563EB` (used for primary actions, active states).
- **Surface / Background**: Neutral light `#F8FAFC` with white cards `#FFFFFF`.
- **Text**: Slate `#0F172A` primary, `#64748B` secondary.
- **Status accents**:
  - Success / complete: `#16A34A`
  - Warning / pending: `#F59E0B`
  - Problem / alert: `#DC2626`
  - Info / in-progress (laundry status): `#0EA5E9`
- Use status colors consistently for laundry batch states and checklist completion.

## Typography
- Sans-serif system stack (Inter / system-ui). Clean and highly legible.
- Clear hierarchy: bold section headers, medium card titles, regular body. Numbers (counts, branch totals) emphasized on the dashboard.

## Elevation & Shape
- Soft rounded corners (8–12px) on cards and buttons.
- Subtle shadows for cards; avoid heavy drop shadows. Flat, calm surfaces.

## Components
- **Dashboard cards** per branch: completion %, open problem badge, laundry batch summary.
- **Checklist**: clear checkboxes, item labels, optional photo attach per item.
- **Status chips**: color-coded laundry batch states (masuk / dicuci / dikeringkan / siap diambil).
- **Problem report list**: severity-aware, with thumbnail photos and timestamps.
- **Photo upload**: thumbnail previews, easy capture on mobile.

## Tone in UI Copy
- Bahasa Indonesia, concise and direct. Operational, not playful.
- Examples: "Laporan Harian", "Checklist Selesai", "Status Cucian", "Laporan Masalah", "Dashboard Cabang".