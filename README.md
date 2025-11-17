---
difficulty: 1
chapter: "Chapter 9: TypeScript"
training: true
tags: react
---

# Complete TypeScript Migration

## Challenge Description

Good news! The movies app has been partially migrated to TypeScript, but it looks like the previous developer left the job unfinished. Lucky for you, that means you get to complete the migration! 🔧 This challenge focuses on TypeScript type definitions, proper typing of functions, and ensuring type safety throughout the application.

Your task is to add proper TypeScript types and eliminate all TypeScript warnings. Your future self will thank you for it!

## Requirements

- Use TypeScript to type the data structure in `/src/data/movies.ts`
- Ensure all functions in `/src/services/movies-service.ts` are properly typed
- Fix TypeScript errors in `/src/pages/HomePage.tsx` and ensure all hooks, state variables, and function parameters are correctly typed
- Fix TypeScript errors in `/src/components/MovieItem.tsx` and ensure all component props are properly typed

> 💡 HINT: Remember that TypeScript can also infer types in many cases - you don't always need to explicitly declare every type if TypeScript can figure it out from context
>
> 💡 HINT: Run `npm run build` to check your progress. This command runs the TypeScript compiler (`tsc`) which will show you any remaining compile-time errors.

## Other Considerations

- TailwindCSS is preinstalled with the default config. It might be helpful for you, if you want to have some styles. (Not obligatory)
- 👀 Don't peek at the solution until you've solved the exercise yourself or exhausted your resources. Challenging yourself will best prepare you for the exam.

## Example of Finished App

This exercise focuses on TypeScript implementation. The visual result should maintain the same functionality while ensuring all TypeScript warnings are resolved and the code is type-safe.

![Screenshot of the finished app](https://api.certificates.dev/repositories/assets/UmVhY3QtQ2VydGlmaWNhdGlvbi9sMi10cmFpbmluZy1jb2RlLWNoYWxsZW5nZS1jaGFwdGVyLTkvc2NyZWVuc2hvdC5naWY=)
