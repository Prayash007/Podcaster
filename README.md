````markdown
# 🎙️ Podcastr

A modern, full-stack podcast application built using Next.js, Clerk for authentication, and Convex for backend logic and data management.

---

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

### **Prerequisites**

Ensure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

---

### **Cloning the Repository**

```bash
git clone https://github.com/Prayash007/Podcaster.git
cd Podcaster
````

---

### **Installation**

Install dependencies using:

```bash
npm install
```

---

### **Set Up Environment Variables**

Create a `.env` file in the root and add the following:

```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
```

> Replace with your actual keys from [Convex](https://www.convex.dev/) and [Clerk](https://clerk.com/).

---

### **Running the Project**

```bash
npm run dev
```

Then open: [http://localhost:3000](http://localhost:3000)

---

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary>Example: Login Redirect</summary>

```tsx
import { useClerk } from "@clerk/nextjs";

const { signIn } = useClerk();
signIn.redirectToSignIn({ redirectUrl: "/dashboard" });
```

</details>

---

## 🛠️ Tech Stack

* Next.js 14+
* Clerk Auth
* Convex Backend
* Tailwind CSS
* TypeScript

---

## 🧠 Author

Made with 🎧 by [Prayash](https://github.com/Prayash007)

```
