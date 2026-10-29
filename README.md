# AMI Material Filing — Cloud（物料智能辨識建檔・雲端版）

登入保護的雲端建檔工具。程式只含操作邏輯，不含任何照片與物料資料：
照片存放在私有 Supabase Storage、建檔資料存放在 Supabase 資料庫，登入後才載入。

A sign-in protected cloud filing tool. This repository contains application code only —
no photos and no material data. Photos live in private Supabase Storage and filing
records in a Supabase database, loaded only after sign-in.

- App: https://gischeng37.github.io/ami-material-filing/
- Backend: Supabase project `ami-material-filing` (Postgres + Auth + private Storage, RLS enforced)
- Offline single-file builds (v1–v6) are kept locally and are not published here.
