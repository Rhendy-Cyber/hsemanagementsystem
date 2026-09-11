# HSE Management System

Versi ini mempertahankan konsep UI FULL sebelumnya dan menambahkan modul yang diminta tanpa data demo.

## Run
```bash
npm install
npm run dev
```

## Tambahan
- Register / Forgot Password / Reset Password tetap tersedia.
- Documents: upload, preview/download, delete.
- Reports: MCU, Health Findings, Follow-Up, COF; filter periode; CSV; print/PDF via browser.
- Pagination + detail pada tabel CRUD.
- Status MCU, Follow-Up, dan COF dihitung otomatis berdasarkan tanggal sistem.
- Reminder otomatis dibuat dari tanggal data dan konfigurasi reminder.
- Settings: company profile dan master data dasar.
- Tidak ada data karyawan, KPI, chart, notification, dokumen, akun demo, atau tanggal bisnis palsu.

Catatan: project ini masih client-side/localStorage. RBAC server-side, database server, API authorization, WebSocket, dan rate limiting memerlukan backend nyata.
