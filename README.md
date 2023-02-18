জাভাস্ক্রিপ্ট নামটাই তার অর্ধেক পরিচয় ফাঁস করে দেয়। লেজের দিকে তাকালেই দেখা যায় ‘স্ক্রিপ্ট’। এই শব্দটিই বলে দেয় এটা একটা স্ক্রিপ্টিং ল্যাঙ্গুয়েজ।
বেশ, ভালো। তো স্ক্রিপ্টিং ল্যাঙ্গুয়েজ আবার কি?
স্ক্রিপ্টিং ল্যাঙ্গুয়েজ হলো এমন প্রোগ্রামিং ল্যাঙ্গুয়েজ যা কম্পাইলার দিয়ে নয় বরং ইন্টাপ্রেটার দিয়ে লাইন বাই লাইন ‘রান’ হয়। মানে সে শুধু ইন্টাপ্রেটারের! 🙂
তার মানে জাভাস্ক্রিপ্ট ইন্টাপ্রেটেড ল্যাঙ্গুয়েজ। একটু গুছিয়ে বললে,
“জাভাস্ক্রিপ্ট একটি ইন্টাপ্রেটেড প্রোগ্রামিং ল্যাঙ্গুয়েজ ।“
নোটঃ নামের শুরুর দিকে দেখে আবার 'জাভা' প্রোগ্রামিং ল্যাঙ্গুয়েজের সাথে মিল খুঁজতে হবে না! জাভার সাথে এর কোন সম্পর্ক নেই।
যাক! কিছু টা ধারণা পাওয়া গেল। এবার…
/ *
বেটার রিডিং এক্সপেরিয়েন্স এর জন্য ভিজিট করুনঃ  https://medium.com/@mahfuzswaron/জাভাস্ক্রিপ্ট-আবার-কী-c72b903bfe05
*/
একটু ইতিহাস
আদিম কালের কথা। তখন মানুষ ওয়েবসাইটে ভিজিট করতো জাস্ট অনেকগুলো টেক্সট আর ইমেজ দেখার জন্য। মানে অনেকটা খবরের কাগজ পড়ার মতো! ওয়েবসাইট ইউজারের সাথে কোনো ইন্টারেকশন করতে পারতো না।
তো এই আধমরা ওয়েবসাইটে সম্পূর্ণ প্রাণ দেওয়ার জন্য আবির্ভাব হলো “JavaScript” the “JS” এর! Document Object Model (DOM) manipulation করার মাধ্যমে সে ওয়েব পেইজে সকল ধরণের ইন্টারেকশন দিতে সক্ষম।
এই যে ফেসবুকে পোস্ট, লাইক, কমেন্ট, শেয়ার এসব করতেছেন সবই জাভাস্ক্রিপ্টের কারিশমা 😉
তাকে বানানোর মূল উদ্দেশ্য ওয়েব অ্যাপ্লিকেশনের client-side ডেভেলপ করা এবং ওয়েব সাইটকে ডায়নামিক করা।

কিন্তু না
সে কবি নজরুলের তালে তালে বলে উঠলো — “থাকবো না কো ক্লায়েন্ট সাইডে, দেখবো এবার ব্যাক-এন্ড টাকে”। মানে? মানে কিছুই না, ক্লায়েন্ট সাইডে তো সার্ভার থেকে আসা ডাটা ডায়নামিকভাবে ডিসপ্লে করা ও ইন্টারেকটিভিটি দেওয়া এসব কাজ হয়। সে এতে সীমাবদ্ধ থাকবে না। বরং সার্ভার সাইড ল্যাঙ্গুয়েজ হিসেবে ডাটাবেজ ম্যানেজমেন্ট, লজিক বিল্ড, API তৈরি এসব কাজ ও করবে। ক্লায়েন্ট সাইড ল্যাঙ্গুয়েজ হিসেবে সে শুধুমাত্র ব্রাউজারেই রান হতে পারে। তো তাকে মেশিনে রান করানোর জন্য দ্যা লিজেন্ড প্রোগ্রামার — “Ryan Dahl” ডেভেলপ করে ফেললেন “Node.js”। এই Node.js এর অবদানে এটি সার্ভার-সাইড ল্যাঙ্গুয়েজ হিসেবে ও ব্যাপক হারে ব্যবহৃত হচ্ছে।
সের্প ইয়ে হি নেহি , আভি অর সুনিয়ে… বর্তমানে প্রোগ্রামিং এর সব সেক্টরে জাভাস্ক্রিপ্টের ব্যবহার রয়েছে। আই মিন… Ananta-Script (🐸) এর কাছে সবই সম্ভব 😉
তবে তা সম্ভব হয়েছে বিভিন্ন ফ্রেমওয়ার্ক ও লাইব্রেরীর এর সাহায্যে। যেমনঃ
# React Native — মোবাইল এপ্লিকেশন
# Electron — ডেস্কটপ এপ্লিকেশন
# TensorFlow.js (টেনসরফ্লো ), Brain.js, ML.js — মেশিন লার্নিং

কেন কেন কেন ?
একটা ক্লায়েন্ট সাইড ল্যাঙ্গুয়েজ হিসেবে জন্ম নেওয়া জাভাস্ক্রিপ্ট কেন এত বেশি জনপ্রিয়তা পেল যা তাকে এখন এত উচ্চ পর্যায়ে নিয়ে গিয়েছে?
১। Multi-paradigm programming : paradigm (প্যারাডাইম ) মানে প্রোগ্রামিং করার পদ্ধতি । একেক ল্যাঙ্গুয়েজ একেক paradigm এর হয়ে থাকে। কিন্তু জাভাস্ক্রিপ্ট কোনো নির্দিষ্ট paradigm এ সীমাবদ্ধ না। জাভাস্ক্রিপ্ট দিয়ে Object Oriented Programming, Functional Programming, Event Driven Programming সহ বিভিন্ন ধরণের paradigm এ প্রোগ্রামিং করা যায়।
২। Dynamic and weak typing : জাভাস্ক্রিপ্টে ভ্যারিয়েবল লিখতে তার ডাটা টাইপ বলে দিতে হয় না। এটি নিজে নিজে বুঝে নেয়। এটাই Dynamic Typing।
আর Weak Typing এর ফলে ডাটাকে বিভিন্ন টাইপে কনভার্ট করা যায়। কখনো প্রয়োজন হলে এটি নিজেই Type Coercion ( টাইপ কোআর্শন — এক টাইপ হয়ে অন্য টাইপে রূপান্তর) করে থাকে।
৩। Asynchronous (অ্যাসিনক্রোনাস ) programming : কোনো statement প্রোসেস হতে যদি সময় বেশি লাগে, তাহলে তার জন্য অপেক্ষা না করে, তাকে Background Processing এ রেখে পরবর্তী statement এর কাজ করে ফেলে।
৪। Interoperability with Browser ( ব্রাউজারের সাথে ইন্টারঅপারেবলিটি ): সকল ব্রাউজারে জাভাস্ক্রিপ্ট ইঞ্জিন রয়েছে। তাই টেকনিক্যালি ব্রাউজারের সাথে জাভাস্ক্রিপ্ট খুবই ঘনিষ্ঠ।
JavaScript এর বহুল ব্যবহারের পেছনে আরো অনেক কারণ আছে। কিন্তু এগুলো হচ্ছে জাভাস্ক্রিপ্টের মৌলিক গুন যা অন্যান্য ল্যাঙ্গুয়েজ থেকে তাকে আলাদা করে রেখেছে।
এই ব্লগে যা দিতে পেরেছি তা খুবই নগণ্য। তবে বিগিনারদের জন্য আশা করি কিছুটা উপকার হয়েছে। এটাই আমার জীবনের প্রথম সম্পূর্ণ ব্লগ। ইন শা আল্লাহ নিয়মিত লিখার ইচ্ছা আছে। আপনাদের গঠনমূলক সমালোচনা ও পরামর্শ আশা করছি।
ধন্যবাদ
