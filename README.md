
seekverse-ai/
├── app/
│   ├── page.tsx            <-- UI Home Page
│   └── layout.tsx          <-- Layout Wrapper
├── public/
│   └── assets/             <-- Logos, Graphics
├── styles/
│   └── globals.css
├── tailwind.config.ts
├── tsconfig.json
├── package.json
├── README.md
export default function Home() {
  return (
    <main className="flex min-h-screen flex-col items-center justify-center bg-gray-100 px-4 py-8">
      <div className="max-w-2xl text-center">
        <h1 className="text-4xl font-extrabold text-blue-700 mb-4">
          SeekVerse AI
        </h1>
        <p className="text-gray-700 text-lg mb-6">
          Discover the secrets of the universe, explore divine and scientific realities with AI-powered research.
        </p>
        <button className="bg-blue-700 hover:bg-blue-800 text-white px-6 py-2 rounded-lg shadow-md">
          Start Exploring
        </button>
      </div>
    </main>
  );
}
export const metadata = {
  title: 'SeekVerse AI',
  description: 'AI-powered universal research engine',
};

export default function RootLayout({ children }) {
  return (
    <html lang="en">
      <body>{children}</body>
    </html>
  );
}
@tailwind base;
@tailwind components;
@tailwind utilities;

body {
  font-family: 'Inter', sans-serif;
}
