# 🤖 Samio AI - Intelligent Chatbot Interface

<div align="center">

![Samio AI Banner](https://img.shields.io/badge/Samio_AI-Powered_by_OpenRouter-blueviolet?style=for-the-badge&logo=openai&logoColor=white)

**A modern, powerful AI chatbot built with Next.js and powered by OpenRouter**

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![OpenRouter](https://img.shields.io/badge/OpenRouter-API-green?style=flat-square)](https://openrouter.ai/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

[Features](#✨-features) • [Demo](#🚀-demo) • [Installation](#📦-installation) • [Usage](#💡-usage) • [Contributing](#🤝-contributing)

</div>

---

## 📖 About

**Samio AI** is a sophisticated chatbot interface that leverages the power of OpenRouter to provide intelligent, context-aware conversations. Built with modern web technologies, it offers a seamless and responsive user experience for interacting with advanced language models.

### Why Samio AI?

- 🎯 **Multi-Model Support**: Access various AI models through OpenRouter's unified API
- ⚡ **Lightning Fast**: Built on Next.js for optimal performance and speed
- 🎨 **Beautiful UI**: Modern, intuitive interface with smooth animations
- 🔒 **Secure**: Environment-based configuration for API key management
- 📱 **Responsive**: Perfect experience across all devices

---

## ✨ Features

- 💬 **Real-time Chat**: Instant responses with streaming support
- 🧠 **Smart Context**: Maintains conversation history for coherent dialogues
- 🎨 **Custom Themes**: Light and dark mode support
- 📝 **Markdown Support**: Rich text formatting in responses
- 🔄 **Model Switching**: Easy switching between different AI models
- 💾 **Conversation History**: Save and load previous conversations
- 🎯 **Code Highlighting**: Syntax highlighting for code snippets
- 🌐 **Multi-language**: Support for conversations in multiple languages

---

## 🚀 Demo

Experience Samio AI in action! Check out our live demo:

🔗 ** https://samio-ai-client.vercel.app

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/) - React framework with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/) - Type-safe development
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- **AI Provider**: [OpenRouter](https://openrouter.ai/) - Unified LLM API
- **Font**: [Geist](https://vercel.com/font) - Modern font family by Vercel

---

## 📦 Installation

### Prerequisites

- Node.js 18.17 or later
- npm, yarn, pnpm, or bun package manager
- OpenRouter API key ([Get one here](https://openrouter.ai/))

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/samio11/Samio_AI_Client.git
   cd Samio_AI_Client
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory:
   ```env
   OPENROUTER_API_KEY=your_api_key_here
   NEXT_PUBLIC_APP_URL=http://localhost:3000
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

5. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

---

## 💡 Usage

### Basic Chat

Start a conversation by typing your message in the input field and pressing Enter or clicking Send.

### Selecting AI Models

Choose from various AI models available through OpenRouter:
- GPT-4
- Claude
- Llama
- And many more!

### Keyboard Shortcuts

- `Enter` - Send message
- `Shift + Enter` - New line
- `Ctrl/Cmd + K` - Clear conversation
- `Ctrl/Cmd + /` - Toggle theme

---

## 📁 Project Structure

```
Samio_AI_Client/
├── app/                    # Next.js app directory
│   ├── api/               # API routes
│   ├── components/        # React components
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── public/                # Static assets
├── styles/                # Global styles
├── lib/                   # Utility functions
├── .env.local            # Environment variables
├── next.config.js        # Next.js configuration
├── tailwind.config.js    # Tailwind configuration
└── package.json          # Dependencies
```

---

## 🔧 Configuration

### OpenRouter Setup

1. Sign up at [OpenRouter](https://openrouter.ai/)
2. Generate an API key from your dashboard
3. Add the key to your `.env.local` file

### Customization

Edit `app/page.tsx` to customize the main interface. The application uses Next.js App Router for routing and layout management.

---

## 🚀 Deployment

### Deploy to Vercel

The easiest way to deploy your Samio AI chatbot is using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/samio11/Samio_AI_Client)

1. Push your code to GitHub
2. Import your repository to Vercel
3. Add your environment variables
4. Deploy!

For detailed deployment instructions, check the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

---

## 🤝 Contributing

Contributions are always welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React Framework
- [OpenRouter](https://openrouter.ai/) - Unified LLM API
- [Vercel](https://vercel.com/) - Deployment platform
- All contributors who help improve this project

---

## 📧 Contact

**Samio** - [@samio11](https://github.com/samio11)

Project Link: [https://github.com/samio11/Samio_AI_Client](https://github.com/samio11/Samio_AI_Client)

---

## 🌟 Star History

If you find this project useful, please consider giving it a star! ⭐

---

<div align="center">

**Made with ❤️ by Samio**

[⬆ Back to Top](#🤖-samio-ai---intelligent-chatbot-interface)

</div>
