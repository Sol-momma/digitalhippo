# ReuseMate

A bulletin board application for university students to facilitate reusing items.  
Instead of **throwing away** clothing, furniture, or textbooks you no longer need, you can **pass them on to someone who needs them**. Through this process, we aim to contribute to **SDGs Goal 12**: Responsible Consumption and Production.

---

## Table of Contents
- [Project Overview](#project-overview)
- [SDGs Alignment](#sdgs-alignment)
- [Key Features](#key-features)
- [Technologies](#technologies)
- [Progress Management and Schedule](#progress-management-and-schedule)
  - [Weekly Schedule](#weekly-schedule)
- [Current Development Status](#current-development-status)
- [Task List](#task-list)
- [Presentation Materials](#presentation-materials)
- [Final Submission Requirements](#final-submission-requirements)
- [Reference Links](#reference-links)
- [License](#license)

---

## Project Overview

### Concept
**ReuseMate** is an app where university students can **post photos** of items they no longer need (clothes, furniture, textbooks, etc.) and **exchange or give them away** for free or at a low price.  
Users can communicate directly with each other to easily arrange when and where to pick up items. We start with a **small-scale** university community and strive to promote reuse culture on a **global** scale.

### Goals
1. Reduce waste by giving new life to items that can still be used.  
2. Support **multilingual communication** among international students (Japanese, English, Chinese), removing language barriers.  
3. Enable **university students** to lead sustainable initiatives, aligning with SDGs for a more sustainable society.

---

## SDGs Alignment

**ReuseMate** strongly aligns with **SDGs Goal 12: Responsible Consumption and Production**.

- **Target 12.5**: By 2030, substantially reduce waste generation through prevention, reduction, recycling, and reuse  
  - Our platform makes it easy to **reuse** items instead of throwing them away.  
- **Target 12.8**: By 2030, ensure that people everywhere have the relevant information and awareness for sustainable development and lifestyles  
  - By providing **multilingual support**, diverse groups of students can access information more easily and engage in sustainable actions.

---

## Key Features

1. **User Authentication**
   - Sign up / login with university email address  
   - Secure sessions via NextAuth.js

2. **Item Posting**
   - Upload photos (1–3 images)
   - Provide item name, description, condition (new/used)
   - Categories (clothing, furniture, textbooks, etc.)
   - Hashtag-based search

3. **Search & Filtering**
   - Search by category
   - Filter by condition or price range

4. **Comments & Messaging**
   - Users can leave comments under each post
   - Direct communication between users to arrange pick-up

5. **Notification System** (Optional)
   - Push notifications for new comments or messages

6. **Favorite Items** (Optional)
   - Save interesting posts for future reference

7. **Admin Features**
   - Remove inappropriate posts/comments
   - Admin dashboard for moderators

---

## Technologies

- **Frontend**:  
  - [Next.js](https://nextjs.org/) (React-based)  
  - [TypeScript](https://www.typescriptlang.org/)

- **Backend**:  
  - Next.js API Routes  
  - [Supabase](https://supabase.com/) (authentication & database)

- **Image Storage**:  
  - Supabase or [Cloudinary](https://cloudinary.com/)

- **Authentication**:  
  - [NextAuth.js](https://next-auth.js.org/)

- **Design**:  
  - [Canva](https://www.canva.com/) or [Figma](https://www.figma.com/)

---

## Progress Management and Schedule

### Weekly Schedule

<details>
<summary>Week 1 (2024/11/22 - 2024/11/28)</summary>

- **2024/11/22**  
  - Finalize project concept, define key features, and confirm tech stack  
  - (In charge: So Momma, Tomoka Iwase)

- **2024/11/25**  
  - Design database schema and set up backend structure (Supabase)

- **2024/11/27**  
  - Create wireframes and mockups (UI/UX)  
  - (Design team / Canva, Figma, etc.)

- **2024/11/28**  
  - Submit progress report slides (all members)

</details>

<details>
<summary>Week 2 (2024/11/29 - 2024/12/05)</summary>

- **2024/11/29**  
  - Begin implementing authentication (signup/login via NextAuth.js)

- **2024/12/01**  
  - Implement item posting (photo upload, categories, details)

- **2024/12/03**  
  - Begin development of search & filter functionality

- **2024/12/05**  
  - Review and test authentication & posting features (all members)

</details>

<details>
<summary>Week 3 (2024/12/06 - 2024/12/12)</summary>

- **2024/12/06**  
  - Build item detail page (comments section, contact options)

- **2024/12/08**  
  - Implement notification system (leveraging Supabase real-time)

- **2024/12/10**  
  - Code review (all members)

- **2024/12/12**  
  - Begin admin features (inappropriate post/comment removal)

</details>

<details>
<summary>Week 4 (2024/12/13 - 2024/12/19)</summary>

- **2024/12/13**  
  - Continue developing admin features

- **2024/12/15**  
  - Perform integration testing on all features (QA team)

- **2024/12/18**  
  - Deploy to production (e.g., Vercel)

- **2024/12/19**  
  - Create user documentation / FAQs

</details>

<details>
<summary>Week 5 (2024/12/20 - 2024/12/26)</summary>

- **2024/12/20**  
  - Finalize presentation materials

- **2024/12/23**  
  - Internal (campus) demo for feedback (all members)

- **2024/12/25**  
  - Final feature testing (QA team)

</details>

<details>
<summary>Week 6 (2024/12/27 - 2025/01/03)</summary>

- **2024/12/27**  
  - Final review and preparations for submission

- **2024/12/29**  
  - Record demo video (at least 3 minutes)

- **2025/01/02**  
  - Final check of all deliverables (slides, docs, video, web link)

- **2025/01/03**  
  - Project submission (deadline: 23:59)

</details>

---

## Current Development Status

- **Completion Rate**: (Example) **60%**  
  - Most basic features for design, frontend, and backend are done  
  - Currently in testing phase & adding extra features (notifications, favorites)

- **Resolved Issues**:
  1. **CSRF protection for authentication**: Improved security with NextAuth.js  
  2. **Image upload optimization**: Using Cloudinary for faster transfer  
  3. **Database schema adjustments**: Supabase provides flexible, scalable design  

- **Future Challenges and Risks**:
  1. Load balancing for real-time notifications  
  2. Network speed for image uploads on campus  
  3. Avoiding UI clutter when implementing multilingual support  

---

## Task List

1. **User Authentication**  
   - [ ] University email registration  
   - [ ] NextAuth.js integration  
   - [ ] Password reset (optional)

2. **Item Posting**  
   - [ ] Photo upload  
   - [ ] Save post data to DB (Supabase)

3. **Search & Filter**  
   - [ ] Filter by category, condition, price range  
   - [ ] Search results page UI

4. **Item Detail Page**  
   - [ ] Comments feature  
   - [ ] Messaging between users  
   - [ ] Favorites feature (optional)

5. **Notification System**  
   - [ ] New comment/message alerts  
   - [ ] Notification settings (enable/disable)

6. **Admin Features**  
   - [ ] Remove inappropriate posts/comments  
   - [ ] Admin dashboard (moderator panel)

7. **Design/UX**  
   - [ ] Unified color scheme and fonts  
   - [ ] Responsive design (PC/Mobile)

8. **Testing and Deployment**  
   - [ ] Unit tests  
   - [ ] Integration tests  
   - [ ] Deploy on Vercel (or similar)

9. **Documentation/Presentation**  
   - [ ] User manual  
   - [ ] Presentation slides / demo video  
   - [ ] Final project report  

---

## Presentation Materials

- **Slides for 2024/11/28 Submission**  
  - [Canva Link 1](https://www.canva.com/design/DAGXK0_ldvc/rbmkVS3KtDNnD0XS1TAdPg/edit?utm_content=DAGXK0_ldvc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

- **Additional Slide Deck (Design Mockups)**  
  - [Canva Link 2](https://www.canva.com/design/DAGT4wc15xQ/qePNsISburgscY0mI-3nmQ/edit)

---

## Final Submission Requirements

1. **Final Project Proposal (due 2024/10/25 23:59)**
   - Present your project idea and plan
   - Must relate to SDGs (Sustainable Development)
   - 5–10 minutes presentation + slides
   - **1 day late = -20 points**

2. **Final Project Progress Report (due 2024/11/29 23:59)**
   - Present your current progress
   - 5–10 minutes presentation + slides
   - Explain SDGs alignment again
   - **1 day late = -20 points**

3. **Final Project (due 2025/1/10 23:59)**
   - 5–10 minutes final demo
   - Required submissions:
     1. Link to your website
     2. A video overview of at least 3 minutes
     3. Documentation (technologies used, team roles, project breakdown, etc.)
   - **1 day late = -20 points**

---

## Reference Links

- **SDGs**
  - [United Nations Information Centre - 17 Goals](https://www.unic.or.jp/activities/economic_social_development/2030agenda/17goals/)
  - [Goal 12: Responsible Consumption and Production - The Global Goals](https://www.globalgoals.org/goals/12-responsible-consumption-and-production/)
- **Supabase**  
  - [https://supabase.com/](https://supabase.com/)
- **Next.js**  
  - [https://nextjs.org/](https://nextjs.org/)
- **NextAuth.js**  
  - [https://next-auth.js.org/](https://next-auth.js.org/)

---

## License

This project respects the licenses of all dependent libraries.  
For any custom source code, please add the appropriate license as needed.

---

If you have any questions or feedback, feel free to reach out via [Issues](../../issues) or submit a pull request.  
**Happy Reuse!**
















# ReuseMate

大学生向けのリユース掲示板アプリケーションです。  
不要になった洋服・家具・教科書などを **“捨てる”** のではなく、**“必要としている人”** へ譲渡や交換しやすくすることで、**SDGs Goal 12**（つくる責任・つかう責任）に貢献します。

---

## 目次
- [プロジェクト概要](#プロジェクト概要)
- [SDGsとの関連](#sdgsとの関連)
- [主な機能](#主な機能)
- [使用技術](#使用技術)
- [進捗管理とスケジュール](#進捗管理とスケジュール)
  - [ウィークリースケジュール](#ウィークリースケジュール)
- [開発状況](#開発状況)
- [タスク一覧](#タスク一覧)
- [プレゼン資料](#プレゼン資料)
- [最終提出に関して](#最終提出に関して)
- [参考リンク](#参考リンク)
- [ライセンス](#ライセンス)

---

## プロジェクト概要

### コンセプト
**ReuseMate** は、大学内で不要になったアイテム（洋服、家具、教科書など）を **写真付き** で投稿し、**無料** または低価格で譲渡・交換できるアプリです。  
ユーザー間で直接コミュニケーションし、受け渡し場所や方法を気軽に相談できます。学内コミュニティというスモールスケールから始め、**地球規模** でのリユース文化を促進することを目指しています。

### 目的
1. まだ使える物を捨てずに再活用することで、**廃棄物を削減** する。  
2. 語学の壁を取り払うことで、**多国籍な学生同士が気軽にやり取り** できるようサポート（日本語・英語・中国語対応を想定）。  
3. **大学生** が主体となって、SDGsの目標である持続可能な社会の実現に貢献する。

---

## SDGsとの関連

ReuseMate は、特に **SDGs Goal 12**「つくる責任・つかう責任」と密接に関わっています。

- **Target 12.5**: 2030年までに廃棄物の発生を予防・削減・再利用およびリサイクルを通じて大幅に削減する  
  - 不要品を捨てずに「譲渡」や「交換」するプラットフォームを提供  
- **Target 12.8**: 2030年までに、すべての人々が持続可能な開発とライフスタイルについての情報と意識を持つ  
  - 多言語対応により、多様な学生が情報にアクセスしやすくし、SDGsに取り組むきっかけを提供  

---

## 主な機能

1. **ユーザー認証**
   - 大学メールアドレスでのサインアップ／ログイン  
   - (NextAuth.js による安全なセッション管理)

2. **アイテム投稿**
   - 写真アップロード（1〜3枚）
   - アイテム名／説明／状態（新品・中古など）
   - カテゴリ（洋服・家具・教科書など）
   - ハッシュタグ検索機能

3. **検索・フィルター**
   - カテゴリ別検索
   - 状態や価格帯などでの絞り込み

4. **コメント・メッセージ機能**
   - 投稿にコメントを付けられる
   - ユーザー間で直接連絡を取り合い、受け渡し方法などを相談可能

5. **通知機能** (オプション)
   - コメントが付いた、メッセージが届いた等のプッシュ通知

6. **お気に入り登録機能** (オプション)
   - 気になる投稿を後で見返せるように保存

7. **管理者機能**
   - 不適切な投稿やコメントを削除
   - 管理者ダッシュボード（モデレータ用）

---

## 使用技術

- **フロントエンド**:  
  - [Next.js](https://nextjs.org/) (Reactベース)  
  - [TypeScript](https://www.typescriptlang.org/)  

- **バックエンド**:
  - Next.js の API Routes  
  - [Supabase](https://supabase.com/) (認証・データベース)

- **画像ストレージ**:
  - Supabase ストレージ or [Cloudinary](https://cloudinary.com/)

- **認証**:
  - [NextAuth.js](https://next-auth.js.org/)

- **デザイン**:
  - [Canva](https://www.canva.com/) または [Figma](https://www.figma.com/)

---

## 進捗管理とスケジュール

### ウィークリースケジュール

<details>
<summary>Week 1 (2024/11/22 - 2024/11/28)</summary>

- **2024/11/22**  
  - プロジェクトコンセプトの最終決定、主要機能の定義、技術スタックの確認  
  - (担当: So Momma, Tomoka Iwase)

- **2024/11/25**  
  - データベーススキーマの設計、バックエンド構造のセットアップ (Supabase)

- **2024/11/27**  
  - ワイヤーフレーム・モックアップの作成 (UI/UX)  
  - (Designチーム / Canva, Figmaなど)

- **2024/11/28**  
  - 進捗報告用スライドの提出 (全メンバー)

</details>

<details>
<summary>Week 2 (2024/11/29 - 2024/12/05)</summary>

- **2024/11/29**  
  - 認証機能（サインアップ／ログイン）の実装開始 (NextAuth.js)

- **2024/12/01**  
  - アイテム投稿機能（写真アップロード、カテゴリー、詳細入力）の実装

- **2024/12/03**  
  - 検索・フィルター機能の開発開始

- **2024/12/05**  
  - 認証／投稿機能のテスト・レビュー (全メンバー)

</details>

<details>
<summary>Week 3 (2024/12/06 - 2024/12/12)</summary>

- **2024/12/06**  
  - アイテム詳細ページの作成（コメント欄、連絡手段）

- **2024/12/08**  
  - 通知システムの実装 (Supabaseのリアルタイム機能など)

- **2024/12/10**  
  - コードレビュー (全メンバー)

- **2024/12/12**  
  - 管理者機能の実装開始 (不適切な投稿の削除など)

</details>

<details>
<summary>Week 4 (2024/12/13 - 2024/12/19)</summary>

- **2024/12/13**  
  - 管理者機能の継続開発

- **2024/12/15**  
  - 全機能の統合テスト (QAチーム)

- **2024/12/18**  
  - 本番環境へのデプロイ (Vercelなど)

- **2024/12/19**  
  - ユーザー向けドキュメント／FAQ作成

</details>

<details>
<summary>Week 5 (2024/12/20 - 2024/12/26)</summary>

- **2024/12/20**  
  - プレゼン資料の最終化

- **2024/12/23**  
  - 社内（学内）デモでフィードバック収集 (全メンバー)

- **2024/12/25**  
  - 最終機能テスト (QAチーム)

</details>

<details>
<summary>Week 6 (2024/12/27 - 2025/01/03)</summary>

- **2024/12/27**  
  - 最終レビュー、提出準備

- **2024/12/29**  
  - プロジェクトデモ動画の作成 (3分以上)

- **2025/01/02**  
  - 成果物（スライド、ドキュメント、動画、Webリンク）の最終チェック

- **2025/01/03**  
  - プロジェクト提出（期限: 23:59）

</details>

---

## 開発状況

- **進捗率**: （例）**60%完了**  
  - デザイン・フロントエンド・バックエンドの基本機能は概ね実装済み  
  - 現在テストフェーズと追加機能（通知機能、お気に入り機能）を開発中

- **解決済み課題**:
  1. **認証周りでのCSRF対策**: NextAuth.jsの採用によりセキュリティ向上  
  2. **画像アップロードの最適化**: Cloudinary活用で転送速度改善  
  3. **DBスキーマ調整**: Supabaseで柔軟かつ拡張性のある設計が可能に  

- **今後の技術的課題・リスク**:
  1. リアルタイム通知機能の負荷対策  
  2. 学内ネットワークでの画像アップロード速度  
  3. 多言語対応におけるUIの煩雑化  

---

## タスク一覧

1. **ユーザー認証**  
   - [ ] 大学メールアドレスでの新規登録  
   - [ ] NextAuth.js連携  
   - [ ] パスワードリセット（オプション）

2. **アイテム投稿**  
   - [ ] 写真アップロード機能  
   - [ ] 投稿データのDB保存 (Supabase)

3. **検索・フィルター**  
   - [ ] カテゴリ・状態・価格帯などの絞り込み  
   - [ ] 検索結果ページのUI

4. **アイテム詳細ページ**  
   - [ ] コメント機能  
   - [ ] ユーザー間メッセージ機能  
   - [ ] お気に入り機能（オプション）

5. **通知システム**  
   - [ ] 新規コメント・メッセージ通知  
   - [ ] 通知設定 (ON/OFF)

6. **管理者機能**  
   - [ ] 不適切な投稿・コメントの削除  
   - [ ] 管理画面の実装（モデレータ用）

7. **デザイン/UX**  
   - [ ] カラー・フォントの統一  
   - [ ] レスポンシブ対応 (PC / モバイル)

8. **テストとデプロイ**  
   - [ ] ユニットテスト  
   - [ ] 結合テスト  
   - [ ] Vercelデプロイ

9. **ドキュメント/発表**  
   - [ ] ユーザー向けマニュアル  
   - [ ] プレゼン用スライド／デモ動画の作成  
   - [ ] 最終レポート作成  

---

## プレゼン資料

- **2024/11/28 提出用スライド**  
  - [Canva Link 1](https://www.canva.com/design/DAGXK0_ldvc/rbmkVS3KtDNnD0XS1TAdPg/edit?utm_content=DAGXK0_ldvc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)  

- **その他参考スライド（デザイン案）**  
  - [Canva Link 2](https://www.canva.com/design/DAGT4wc15xQ/qePNsISburgscY0mI-3nmQ/edit)

---

## 最終提出に関して

1. **最終プロジェクト提案書 (2024/10/25 23:59)**
   - プロジェクトのアイデアと計画
   - SDGs（永續發展）との関連
   - 5〜10分の発表＋スライド提出
   - **1日遅れ = -20点**

2. **最終プロジェクト進捗報告 (2024/11/29 23:59)**
   - 進捗状況の発表
   - 5〜10分の発表＋スライド提出
   - SDGsとの関係を再度説明
   - **1日遅れ = -20点**

3. **最終プロジェクト (2025/1/10 23:59)**
   - デモ（5〜10分）
   - 下記の提出物：
     1. ウェブサイトのリンク
     2. 3分以上の紹介動画
     3. ドキュメント（使用技術、担当箇所、作業内容 など）
   - **1日遅れ = -20点**

---

## 参考リンク

- **SDGs全般**
  - [国連広報センター - SDGs 17の目標](https://www.unic.or.jp/activities/economic_social_development/2030agenda/17goals/)
  - [Goal 12: Responsible consumption and production - The Global Goals](https://www.globalgoals.org/goals/12-responsible-consumption-and-production/)
- **Supabase**  
  - [https://supabase.com/](https://supabase.com/)
- **Next.js**  
  - [https://nextjs.org/](https://nextjs.org/)
- **NextAuth.js**  
  - [https://next-auth.js.org/](https://next-auth.js.org/)

---

## ライセンス

本プロジェクトは各種依存ライブラリのライセンスを遵守します。  
独自のコード部分については、必要に応じてライセンス表記を追加してください。

---

ご意見やご要望がございましたら、[Issues](../../issues) またはプルリクエストでお知らせください。  
**Happy Reuse!**
