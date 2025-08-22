git config --global user.name "foisal-hossen"
git config --global user.email "farjana01811389904@gmail.com"

Personal Access Token (PAT) তৈরি করবেন:
ধাপ ১: আপনার GitHub অ্যাকাউন্টে লগইন করুন এবং এই লিঙ্কে যান: https://github.com/settings/tokens
ধাপ ২: "Generate new token" বাটনে ক্লিক করুন এবং "Generate new token (classic)" অপশনটি সিলেক্ট করুন।
ধাপ ৩:
Note: টোকেনের একটি নাম দিন, যেমন my-kali-terminal বা আপনার ইচ্ছামত কিছু।
Expiration: টোকেনটি কতদিন থাকবে তা সিলেক্ট করুন (যেমন: 30 days বা 90 days)।
Select scopes: এখানে আপনাকে পারমিশন দিতে হবে। কোড পুশ করার জন্য, repo লেখা অপশনটির পাশের চেকবক্সে টিক চিহ্ন দিন। এটিই যথেষ্ট।
ধাপ ৪: একদম নিচে গিয়ে "Generate token" বাটনে ক্লিক করুন।
ধাপ ৫: খুব গুরুত্বপূর্ণ!
GitHub আপনাকে একটি টোকেন দেখাবে (এটি ghp_ দিয়ে শুরু হবে)।
এই টোকেনটি একবারই দেখানো হবে। এখনই এটি কপি করে একটি নিরাপদ জায়গায় (যেমন একটি নোটপ্যাড ফাইলে) সেভ করে রাখুন। যদি পেজটি রিফ্রেশ করেন, টোকেনটি আর দেখতে পারবেন না।

# ১. ফাইলটি আবার অ্যাড করুন (যদি কোনো পরিবর্তন করে থাকেন)
git add README.md
git add .

# ২. এখন কমিট করুন (এইবার এটি কাজ করবে)
git commit -m "first commit"

# ৩. ব্রাঞ্চের নাম main রাখুন (এটি একটি ভালো অভ্যাস)
git branch -M main

# ৪. রিমোট রিপোজিটরিটি আগে থেকেই অ্যাড করা আছে, তাই এটি আবার চালানোর দরকার নেই।
# কিন্তু যদি কোনো কারণে মুছে গিয়ে থাকে, তবে আবার চালাতে পারেন:
# git remote add origin https://github.com/foisal-hossen/web-scanner-cpp.git

# ৫. সবশেষে, এখন GitHub এ পুশ করুন
git push -u origin main

