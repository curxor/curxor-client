.
├── public                              # Static files
├── src                                 # Next.js source directory
│   ├── app                             # Next.js App Router
│   │   ├── (auth)                      # (Group) Private routes
│   │   │   ├── layout.tsx              # Authenticated layout
│   │   │   └── profile                # (Module) Profile page
│   │   │       └── page.tsx
│   │   ├── (unauth)                    # (Group) Public routes
│   │   │   ├── layout.tsx              # Unauthenticated layout
│   │   │   ├── page.tsx                # Unauthenticated index page
│   │   │   └── products              # (Module) Product page
│   │   │       ├── components         # Components for the product page
│   │   │       │   └── ProductCard.tsx
│   │   │       ├── layout.tsx
│   │   │       └── page.tsx
│   │   ├── layout.tsx                  # App layout
│   │   ├── not-found.tsx               
│   │   ├── loading.tsx
│   │   └── error.tsx
![image](https://github.com/user-attachments/assets/34e1dbf8-4577-479d-a5ab-f6b4e5a8abf3)

│   ├── components                      # Global components
│   │   ├── Footer.tsx
│   │   ├── Header.tsx
│   │   └── ui                        # Atomic design components
│   │       ├── Button.tsx
│   │       └── Tag.tsx
│   ├── api                             # Global API route handlers
│   │   ├── auth
│   │---global.css                  # Global styles
│   ├── types                           # Global types
│   │   └── global.ts
│   ├── libs                            # 3rd-party libraries
│   │   └── auth.ts
│   └── utils                           # Global utility functions
│       └── helpers.ts
├── tailwind.config.ts                  # TailwindCSS configuration
├── .eslintrc.json                      # ESLint configuration
├── .prettierrc                         # Prettier configuration
├── LICENSE
├── README.md
├── commitlint.config.ts                # Commitlint configuration
├── lint-staged.config.js               # Lint-staged configuration
├── next-env.d.ts
├── next.config.mjs
├── package-lock.json
├── package.json
├── postcss.config.mjs                  # PostCSS configuration
└── tsconfig.json                       # Typescript configuration
