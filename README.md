# React Iranian Bank Logos — لوگو بانک های ایرانی

[![npm](https://img.shields.io/npm/v/react-iranian-bank-logo)](https://www.npmjs.com/package/react-iranian-bank-logo)
![React](https://img.shields.io/badge/React-18%2B-61DAFB.svg)
![Next.js](https://img.shields.io/badge/Next.js-Compatible-000000.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-Supported-3178C6.svg)
[![Releases](https://img.shields.io/github/v/release/cyberhuginn/react-iranian-bank-logo)](https://github.com/cyberhuginn/react-iranian-bank-logo/releases)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

**Iranian bank logos and bank icons as React components for React and Next.js applications.**

یک مجموعه از **لوگو بانک های ایرانی** به صورت کامپوننت‌های React، مناسب برای استفاده در پروژه‌های **React** و **Next.js**.

---

## Demo

See all available Iranian bank logos:

https://cyberhuginn.github.io/react-iranian-bank-logo/

---

## Features

- Iranian bank logos and icons
- Ready-to-use React component
- Compatible with React and Next.js
- Supports customizable logo size
- SVG-based bank icons
- TypeScript declaration included
- Simple API with minimal dependencies
- Suitable for dashboards, banking applications, fintech projects and financial websites

---

## Supported Iranian Banks

This package provides logos for popular Iranian banks, including:

- بانک ملت — Mellat Bank
- بانک پاسارگاد — Pasargad Bank
- بانک ملی ایران — Bank Melli Iran
- بانک صادرات ایران — Bank Saderat Iran
- بانک تجارت — Tejarat Bank
- بانک سامان — Saman Bank
- بانک پارسیان — Parsian Bank
- بانک رفاه کارگران — Refah Bank
- بانک آینده — Ayandeh Bank
- بانک شهر — Shahr Bank
- بانک اقتصاد نوین — Eghtesad Novin Bank
- بانک دی — Dey Bank
- بانک گردشگری — Tourism Bank
- بانک کارآفرین — Karafarin Bank
- بانک سینا — Sina Bank
- بانک ایران زمین — Iran Zamin Bank

> The list of available banks may change as new logos are added to the package.

---

## Installation

Install the package with npm:

```bash
npm install react-iranian-bank-logo
```

Or with Yarn:

```bash
yarn add react-iranian-bank-logo
```

Or with pnpm:

```bash
pnpm add react-iranian-bank-logo
```

---

## Usage

Import the `IranianBank` component:

```jsx
import { IranianBank } from "react-iranian-bank-logo";

export default function App() {
    return (
        <div>
            <IranianBank name="ir-mellat" size={40} />
            <IranianBank name="ir-pasargad" size={30} />
        </div>
    );
}
```

### Next.js

The component can be used in Next.js applications.

```tsx
"use client";

import { IranianBank } from "react-iranian-bank-logo";

export default function BankLogo() {
    return (
        <IranianBank
            name="ir-mellat"
            size={40}
        />
    );
}
```

---

## API

### `IranianBank`

Render an Iranian bank logo by its name.

| Prop | Type | Default | Description |
| --- | --- | --- | --- |
| `name` | `string` | — | Bank logo identifier |
| `size` | `number` | `20` | Logo width and height in pixels |
| `...rest` | `img` attributes | — | Additional HTML `<img>` attributes |

Example:

```jsx
<IranianBank
    name="ir-mellat"
    size={48}
    alt="Mellat Bank"
/>
```

All bank logos are designed to use a square aspect ratio.

---

## Bank Logo Names

Bank logos use simple identifiers such as:

```text
ir-mellat
ir-pasargad
```

For the complete list of available logos, see the `icons` directory or the online demo.

---

## TypeScript

TypeScript declarations are included with the package.

```tsx
import { IranianBank } from "react-iranian-bank-logo";

export default function Example() {
    return (
        <IranianBank
            name="ir-mellat"
            size={40}
        />
    );
}
```

---

## Use Cases

`react-iranian-bank-logo` can be useful for:

- Iranian banking applications
- Fintech applications
- Payment platforms
- Financial dashboards
- Wallet applications
- E-commerce websites
- Iranian payment forms
- Bank account selection
- Card and banking interfaces
- React admin dashboards
- Next.js applications

---

## Adding New Bank Logos

To add a new Iranian bank logo during development:

1. Add the SVG file to the `src/icons/` directory.
2. Generate the icon definitions:

```bash
node scripts/build-icons.js
```

3. Build the package:

```bash
npm run build
```

---

## Development

Clone the repository:

```bash
git clone https://github.com/cyberhuginn/react-iranian-bank-logo.git
cd react-iranian-bank-logo
```

Install dependencies:

```bash
npm install
```

Build the package:

```bash
npm run build
```

Start development/watch mode:

```bash
npm run dev
```

The build process automatically copies the bank SVG icons into the `dist` directory.

---

## Open Source

Contributions, bug reports and suggestions are welcome.

If you find a missing Iranian bank logo or have an issue with an existing icon, feel free to open an issue or submit a pull request.

---

## Links

- **npm:** https://www.npmjs.com/package/react-iranian-bank-logo
- **GitHub:** https://github.com/cyberhuginn/react-iranian-bank-logo
- **Demo:** https://cyberhuginn.github.io/react-iranian-bank-logo/

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Keywords

Iranian bank logos, Iranian bank icons, Iran bank logos, Iran banks, Iranian banks, bank logo React, React bank icons, React bank logos, Next.js bank logos, Iranian banking, Persian banking, fintech React, Iranian fintech, SVG bank logos, لوگو بانک ایرانی, لوگو بانک های ایران, آیکون بانک, بانک های ایران