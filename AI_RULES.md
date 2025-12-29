# AI Development Rules

## Tech Stack

• **Framework**: Next.js 15 with App Router
• **Language**: TypeScript
• **Styling**: Tailwind CSS with tailwindcss-animate
• **UI Components**: Radix UI primitives and shadcn/ui components
• **State Management**: React built-in hooks and context
• **Forms**: React Hook Form with Zod validation
• **Icons**: Lucide React
• **AI/ML**: Genkit with Google GenAI integration
• **Utilities**: Class Variance Authority, Tailwind Merge, clsx
• **Charts**: Recharts

## Library Usage Rules

### UI & Styling
• Use **shadcn/ui** components as the primary UI library
• Use **Radix UI** primitives only when shadcn/ui doesn't have the required component
• Style exclusively with **Tailwind CSS** classes
• Use **lucide-react** for all icons

### Forms & Validation
• Use **React Hook Form** for all form handling
• Use **Zod** for all validation schemas
• Use **@hookform/resolvers** to connect Zod with React Hook Form

### AI & Data
• Use **Genkit** with **@genkit-ai/google-genai** for all AI functionality
• Use **Firebase** for backend services if needed

### Utilities
• Use **clsx** or **tailwind-merge** for conditional class names
• Use **class-variance-authority** for component variants
• Use **date-fns** for date manipulation
• Use **recharts** for data visualization

### Component Structure
• Create new components in **src/components** directory
• Create pages in **src/app** directory with proper routing
• Keep components small and focused (under 100 lines)
• Use TypeScript for all new files
• Prefer client components unless server-side rendering is specifically required