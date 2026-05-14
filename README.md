# BloomShop - Free Next.js Tailwind CSS E-Commerce Template

2. Install Dependencies
```
npm i
```
3. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Folder Structure

```text
shoes-ecom/
├── app/
│   ├── cart/
│   │   └── page.tsx
│   ├── contact/
│   │   └── page.tsx
│   ├── product/
│   │   └── [productId]/
│   │       └── page.tsx
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── cart/
│   │   ├── CartItem.tsx
│   │   ├── CartItemList.tsx
│   │   ├── EmptyCart.tsx
│   │   ├── OrderSummary.tsx
│   │   └── Recommendations.tsx
│   ├── home/
│   │   ├── ProductCard.tsx
│   │   └── ProductList.tsx
│   ├── layout/
│   │   ├── Footer.tsx
│   │   └── Header.tsx
│   ├── product/
│   │   ├── Features.tsx
│   │   ├── ProductBreadcrumb.tsx
│   │   ├── ProductNotFound.tsx
│   │   └── RelatedProducts.tsx
│   └── ui/
│       ├── badge.tsx
│       ├── button.tsx
│       ├── card.tsx
│       ├── input.tsx
│       ├── select.tsx
│       ├── separator.tsx
│       └── textarea.tsx
├── context/
│   └── CartContext.tsx
├── data/
│   └── products.json
├── lib/
│   └── utils.ts
├── public/
│   └── images/
│       └── NoImage.jpg
├── types/
│   └── product.ts
├── components.json
├── eslint.config.mjs
├── next.config.ts
├── package.json
├── postcss.config.mjs
├── tailwind.config.js
└── tsconfig.json
```

## Author 
```
Design and code is completely written by Bloomtpl and development team. 
```

## License

 - Design and Code is Copyright &copy; <a href="https://github.com/bloomtpl" target="_blank">Bloomtpl</a>
 - Licensed cover under [MIT]
 - Distributed by <a href="https://themewagon.com" target="_blank">ThemeWagon</a>
