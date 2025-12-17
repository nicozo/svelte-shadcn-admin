# svelte-shadcn-admin

Svelte 5 と shadcn-svelte をベースにした、モダンで高速な管理画面テンプレートです。

## 🚀 技術スタック

本プロジェクトは最新のライブラリ群で構成されています。

### フレームワーク・コア
- **Framework:** Svelte 5 (Runes API)
- **Meta-framework:** SvelteKit 2
- **Language:** TypeScript
- **Build Tool:** Vite 7
- **Package Manager:** pnpm v10

### UI & デザイン
- **Styling:** Tailwind CSS v4
- **UI Components:** shadcn-svelte (bits-ui)
- **Icons:** Lucide Svelte / Tabler Icons
- **Charts:** LayerChart (D3-based)
- **Animations:** tw-animate-css / vaul-svelte (Drawer)

### データ・ユーティリティ
- **Table:** TanStack Table (v8)
- **Validation:** Zod
- **Drag & Drop:** dnd-kit-svelte
- **Toast:** Svelte Sonner

---

## 🛠 Docker での環境構築

Docker を使用して、依存関係のインストールから開発サーバーの起動までを自動化しています。

### 1. プロジェクトの準備
リポジトリをクローンし、ディレクトリに移動します。
```bash
git clone <your-repository-url>
cd svelte-shadcn-admin
```

### 2. コンテナのビルドと起動
以下のコマンドを実行すると、イメージの作成とコンテナの起動が行われます。
```bash
docker compose up --build
```

### 3. ブラウザで確認
起動後、以下のURLで開発サーバーにアクセスできます。
- Local: http://localhost:5173
