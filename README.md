git config --global user.name "foisal-hossen" <br>
git config --global user.email "farjana01811389904@gmail.com"

<h5>Personal Access Token (PAT) তৈরি করবেন:<br></h5>
ধাপ ১: আপনার GitHub অ্যাকাউন্টে লগইন করুন এবং এই লিঙ্কে যান: https://github.com/settings/tokens<br>
ধাপ ২: "Generate new token" বাটনে ক্লিক করুন এবং "Generate new token (classic)" অপশনটি সিলেক্ট করুন।<br>
ধাপ ৩:<br>
Note: টোকেনের একটি নাম দিন, যেমন my-kali-terminal বা আপনার ইচ্ছামত কিছু।<br>
Expiration: টোকেনটি কতদিন থাকবে তা সিলেক্ট করুন (যেমন: 30 days বা 90 days)।<br>
Select scopes: এখানে আপনাকে পারমিশন দিতে হবে। কোড পুশ করার জন্য, repo লেখা অপশনটির পাশের চেকবক্সে টিক চিহ্ন দিন। এটিই যথেষ্ট।<br>
ধাপ ৪: একদম নিচে গিয়ে "Generate token" বাটনে ক্লিক করুন।<br>
ধাপ ৫: খুব গুরুত্বপূর্ণ!<br>
GitHub আপনাকে একটি টোকেন দেখাবে (এটি ghp_ দিয়ে শুরু হবে)।<br>
এই টোকেনটি একবারই দেখানো হবে। এখনই এটি কপি করে একটি নিরাপদ জায়গায় (যেমন একটি নোটপ্যাড ফাইলে) সেভ করে রাখুন। যদি পেজটি রিফ্রেশ করেন, টোকেনটি আর দেখতে পারবেন না।<br>

<h6># ১. ফাইলটি আবার অ্যাড করুন (যদি কোনো পরিবর্তন করে থাকেন)</h6>
git add README.md
git add .

<h6># ২. এখন কমিট করুন (এইবার এটি কাজ করবে)</h6>
git commit -m "first commit"

<h6># ৩. ব্রাঞ্চের নাম main রাখুন (এটি একটি ভালো অভ্যাস)</h6>
git branch -M main

<h6># ৪. রিমোট রিপোজিটরিটি আগে থেকেই অ্যাড করা আছে, তাই এটি আবার চালানোর দরকার নেই।
# কিন্তু যদি কোনো কারণে মুছে গিয়ে থাকে, তবে আবার চালাতে পারেন:</h6>
# git remote add origin https://github.com/foisal-hossen/web-scanner-cpp.git

<h6># ৫. সবশেষে, এখন GitHub এ পুশ করুন</h6>
git push -u origin main

