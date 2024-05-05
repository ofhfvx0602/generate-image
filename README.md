<h1 align=center>画像生成サイト</h1>

![genera](https://github.com/ofhfvx0602/generate-image/assets/95751619/2f023ba2-c5e8-4655-8bb9-8d8a21e14707)

## メイン機能
- 技術スタック: Next.js 14, Typescript, React, Stripe, Tailwind, MongoDB, Clerk, Cloudinary, Shadcn, vercel
- 新規登録、ログインが可能です。
- 画像検索できます。
- 画像を修復することができます。
- 画像の色を変えることができます。
- 画像を塗りつぶすことが可能です。
- 指定したオブジェクトを正確に除去することができます。
- 背景を削除することができます。
- AI変換された画像を保存して共有することができます。
- 変換した画像を削除することもできます。
- 無課金の場合10回まで画像を生成できます。
- 課金することで画像をさらに生成できます。
- レスポンシブUI/UX  


### Setup .env file
```bash
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...

# Clerk URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=...
NEXT_PUBLIC_CLERK_SIGN_UP_URL=...
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=...
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=...

# Clerk Webhook Secret
WEBHOOK_SECRET=...

# MongoDB
MONGODB_URL=...

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

# Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=...
STRIPE_SECRET_KEY=...
STRIPE_WEBHOOK_SECRET=...

# NEXT
NEXT_PUBLIC_SERVER_URL=...
```














