# TypeScript DOC

This repo contain TypeScript Doc Bangla.

## TypeScript কী?

TypeScript হলো Microsoft-এর তৈরি একটি superset প্রোগ্রামিং ল্যাঙ্গুয়েজ, যা JavaScript-এর উপর ভিত্তি করে তৈরি। এটি JavaScript-এর সব ফিচার সাপোর্ট করে এবং অতিরিক্ত কিছু সুবিধা যোগ করে, যেমন Static Typing, Interfaces, Enums ইত্যাদি।

## TypeScript কেন শিখবে?

- Static Typing: JavaScript-এ runtime-এ error ধরা পড়ে, কিন্তু TypeScript-এ আগে থেকেই type checking করে error বের করা যায়।
- Better Code Management: বড় প্রজেক্টে কোড মেইনটেইন করা সহজ হয়।
- Object-Oriented Features: TypeScript-এ OOP-এর কিছু উন্নত ফিচার রয়েছে, যেমন Interfaces, Abstract Classes ইত্যাদি।
- Better IDE Support: TypeScript ব্যবহার করলে VS Code-এর মতো IDE-তে ভালো IntelliSense এবং Autocomplete পাওয়া যায়।

## জাভাস্ক্রিপ্টে সমস্যা কী?

### 1. No Static Typing (ধরন নির্ধারণের সুবিধা নেই)

JavaScript-এ ভেরিয়েবলের ধরন (type) নির্ধারণ করা হয় না, তাই অনেক সময় ভুল টাইপের ডাটা ব্যবহার হলে runtime error দেখা দেয়।

### 2. Runtime Errors (বাগ খুঁজতে কষ্ট)

JavaScript হল একটি dynamically typed language, তাই অনেক বাগ runtime-এ ধরা পড়ে, যা debugging কঠিন করে তোলে।

### 3. Poor Code Maintainability (বড় প্রজেক্ট মেইনটেইন করা কঠিন)

JavaScript-এ বড় বড় প্রজেক্ট ম্যানেজ করা কঠিন হয়, কারণ সেখানে হাজার হাজার লাইন কোড থাকে এবং টাইপ বা স্ট্রাকচার না থাকায় ডেভেলপাররা বারবার ভুল করে।

TypeScript এই সমস্যার সমাধান করে interfaces, type definitions, এবং better tooling support দিয়ে।

### 4. Object-Oriented Features কম

JavaScript ES6 থেকে OOP (Object-Oriented Programming) সাপোর্ট করলেও এটি যথেষ্ট শক্তিশালী নয়। TypeScript-এ Interfaces, Enums, Abstract Classes ইত্যাদি রয়েছে, যা OOP পারদর্শীদের জন্য অনেক সুবিধাজনক।।

### 5. Lack of Modern Tooling Support

TypeScript ব্যবহার করলে IntelliSense, Autocomplete, এবং Code Refactoring অনেক উন্নত হয়। কারণ TypeScript কোডের টাইপ বুঝতে পারে এবং IDE-তে ভালো Suggestions দেয়।

## Images

![What is TypeScript](/assets/img-1.png)
![What's wrong with JS](/assets/img-2.png)
![Benefits of TypeScript](/assets/img-3.png)

## TypeScript সেটআপ করা

    npm install -g typescript
    or
    yarn global add typescript
