# Table of Contents

- [Introduction](#introduction)
- [HTML](#html)
- [CSS](#css)
- [JavaScript](#javascript)
- [Conclusion](#React)

## html
<details>
  <summary><strong>1/ HTML কি?</strong></summary>
  <p>উত্তর : HTML এর পুর্ণরুপ হল HyperText Markup Language. এটি ওয়েব পেইজ তৈরি এবং গঠন করার জন্য ব্যবহৃত একটি মার্কআপ ভাষা। 
  HTML মুলত ওয়েবপেইজের বিষয়বস্তু যেমন পাঠ্য, চিত্র, লিঙ্ক, এবং অন্যান্য মিডিয়া উপাদানগুলি নির্ধারণ করতে ব্যবহৃত হয়। HTML কোডটি ট্যাগ এবং অ্যাট্রিবিউটের সমন্বয়ে গঠিত, যা ব্রাউজারকে বলে দেয় কীভাবে একটি ওয়েবপেইজ বিভিন্ন অংশ প্রদর্শন করতে হবে। HTML একটি স্ট্যাটিক ভাষা, অর্থাৎ এটি ওয়েবপেইজ স্থায়ী গঠন এবং বিষয়বস্তু নির্ধারণ করে। 
  </p>
</details>

<details>
  <summary><strong>2/HTML ডকুমেন্টের basic structure লিখ।</strong></summary>
  <p>উত্তর :  

                <!DOCTYPE html>
                <html lang="en">
                <head>
                    <meta charset="UTF-8">
                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                    <title>Document Title</title>
                </head>
                <body>
                    <h1>Welcome to HTML</h1>
                    <p>This is a basic HTML document structure.</p>
                </body>
                </html></p>
</details>


<details>
  <summary><strong>৩/ <!DOCTYPE html> ট্যাগটির কেন ব্যবহৃত হয়?</strong></summary>
  <p> উত্তর : <!DOCTYPE html> ট্যাগটি ব্রাউজারকে জানায় যে ডকুমেন্টটি HTML5 ভাষায় লেখা হয়েছে। এটি ব্রাউজারকে ডকুমেন্টটি সঠিকভাবে এবং স্ট্যান্ডার্ড মোডে রেন্ডার করতে সহায়তা করে।</p>
</details>

<details>
  <summary><strong>৪/ <head> ট্যাগের ভিতরে কী ধরনের তথ্য থাকে?</strong></summary>
  <p> উত্তর : <head> ট্যাগের ভিতরে থাকে মেটা-তথ্য যেমন চরসেট(charset), ভিউপোর্ট সেটিংস, শিরোনাম, এবং স্টাইলশিট এবং স্ক্রিপ্ট লিঙ্ক।</p>
</details>

<details>
  <summary><strong>৫/ <meta charset="UTF-8"> এর গুরুত্ব কী?</strong></summary>
  <p> উত্তর :<meta charset="UTF-8"> ডকুমেন্টের চরসেট(charset) নির্ধারণ করে যা ইউনিকোড ব্যবহার করে। এটি নিশ্চিত করে যে ডকুমেন্টে বিভিন্ন ভাষার বিশেষ অক্ষরগুলি সঠিকভাবে প্রদর্শিত হবে।</p>
</details>
<details>
  <summary><strong>6/ HTML ডকুমেন্টে lang অ্যাট্রিবিউটের গুরুত্ব কী?</strong></summary>
  <p> উত্তর :lang অ্যাট্রিবিউটটি ডকুমেন্টের ভাষা নির্ধারণ করে যা ব্রাউজার এবং স্ক্রিন রিডারগুলির জন্য উপকারী। এটি সার্চ ইঞ্জিন অপটিমাইজেশনেও সহায়ক।</p>
</details>
<details>
  <summary><strong>৭/ HTML ডকুমেন্টে কমেন্ট কিভাবে লেখা হয়?</strong></summary>
  <p> উত্তর : HTML ডকুমেন্টে কমেন্ট লেখার জন্য নিচের ফরম্যাট ব্যবহার করা হয়:
	                              <!-- এটি একটি কমেন্ট -->
HTML কমেন্ট শুরু হয় <!-- দিয়ে এবং শেষ হয় --> দিয়ে।এই দুটি চিহ্নের মধ্যে যা কিছু লেখা হয়, তা ব্রাউজার ব্যবহারকারীকে দেখানো হয় না।</p>
</details>
<details>
  <summary><strong>৮/<metaname="viewport" content="width=device-width, initial-scale=1.0"> এর কাজ কী?</strong></summary>
  <p> উত্তর : এই <meta> ট্যাগটি মোবাইল ডিভাইসে ডকুমেন্টের স্কেলিং এবং প্রস্থ নিয়ন্ত্রণ করে, যা রেস্পন্সিভ ডিজাইনের জন্য অত্যন্ত গুরুত্বপূর্ণ।</p>
</details>
<details>
  <summary><strong>৯/ HTML এ উপাদান (element) এবং অ্যাট্রিবিউট (attribute) এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>উত্তর : 

                        উপাদান (Element):
                        সংজ্ঞা: HTML ডকুমেন্টের বিল্ডিং ব্লক। এটি একটি শুরু ট্যাগ, বিষয়বস্তু, এবং একটি শেষ ট্যাগ নিয়ে গঠিত।
                        উদাহরণ: <p>এই একটি প্যারাগ্রাফ।</p>
                        এখানে <p> শুরু ট্যাগ, এই একটি প্যারাগ্রাফ। বিষয়বস্তু, এবং </p> শেষ ট্যাগ।
                        প্রকারভেদ:
                        ব্লক লেভেল উপাদান: <div>, <p>, <h1>, ইত্যাদি।
                        ইনলাইন উপাদান: <span>, <a>, <img>, ইত্যাদি।
                        অ্যাট্রিবিউট (Attribute):
                        সংজ্ঞা: HTML উপাদানগুলির অতিরিক্ত তথ্য প্রদান করে। এগুলি শুরু ট্যাগে নির্দিষ্ট করা হয় এবং সাধারণত নাম-মান জোড়া আকারে থাকে।
                        উদাহরণ: <a href="https://www.example.com" target="_blank">Visit Example</a>
                        এখানে href এবং target অ্যাট্রিবিউট, এবং তাদের মান যথাক্রমে "https://www.example.com" এবং "_blank"।</p>
</details>
<details>
  <summary><strong>১০/  HTML5 এর নতুন উপাদান গুলো কি কি?</strong></summary>
  <p>উত্তর : HTML5 এর নতুন উপাদানগুলোর নাম:
  <ul>
    <li><code>&lt;article&gt;</code></li>
    <li><code>&lt;section&gt;</code></li>
    <li><code>&lt;nav&gt;</code></li>
    <li><code>&lt;aside&gt;</code></li>
    <li><code>&lt;header&gt;</code></li>
    <li><code>&lt;footer&gt;</code></li>
    <li><code>&lt;main&gt;</code></li>
    <li><code>&lt;figure&gt;</code></li>
    <li><code>&lt;figcaption&gt;</code></li>
    <li><code>&lt;mark&gt;</code></li>
    <li><code>&lt;time&gt;</code></li>
    <li><code>&lt;progress&gt;</code></li>
    <li><code>&lt;meter&gt;</code></li>
    <li><code>&lt;summary&gt;</code></li>
    <li><code>&lt;details&gt;</code></li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>১১/ HTML5 এ স্থানাঙ্ক ভিত্তিক অবস্থান নির্ধারণের জন্য কোন API ব্যবহৃত হয়? </strong></summary>
  <p>উত্তর: জিওলোকেশন API।</p>
</details>
<details>
  <summary><strong>১২/ HTML এ ইনলাইন এবং ব্লক-লেভেল উপাদানগুলির মধ্যে পার্থক্য কী?</strong></summary>
  <p>উত্তর : 
  </p>
  <p><strong>ইনলাইন উপাদান (Inline Elements):</strong></p>
  <ul>
    <li>সংজ্ঞা: ইনলাইন উপাদানগুলি একটি লাইনের মধ্যে থাকে এবং শুধুমাত্র যতটুকু প্রয়োজন ততটুকু জায়গা নেয়।</li>
    <li>ডিসপ্লে প্রপার্টি: <code>display: inline;</code></li>
    <li>লাইনের পরিবর্তন: ইনলাইন উপাদানগুলি নতুন লাইন শুরু করে না।</li>
    <li>আনুষঙ্গিক উপাদান: ইনলাইন উপাদানগুলির মধ্যে শুধুমাত্র ইনলাইন বা টেক্সট উপাদান থাকতে পারে।</li>
    <li>উদাহরণ: <code>&lt;span&gt;</code>, <code>&lt;a&gt;</code>, <code>&lt;img&gt;</code>, <code>&lt;strong&gt;</code>, <code>&lt;em&gt;</code></li>
    <li>স্টাইলিং: ইনলাইন উপাদানগুলির প্রস্থ বা উচ্চতা পরিবর্তন করা যায় না।</li>
  </ul>
  <p><strong>ব্লক-লেভেল উপাদান (Block-level Elements):</strong></p>
  <ul>
    <li>সংজ্ঞা: ব্লক-লেভেল উপাদানগুলি একটি সম্পূর্ণ লাইনের জায়গা নেয় এবং নতুন লাইন শুরু করে।</li>
    <li>ডিসপ্লে প্রপার্টি: <code>display: block;</code></li>
    <li>লাইনের পরিবর্তন: প্রতিটি ব্লক-লেভেল উপাদান নতুন লাইন শুরু করে।</li>
    <li>আনুষঙ্গিক উপাদান: ব্লক-লেভেল উপাদানগুলির মধ্যে অন্যান্য ব্লক-লেভেল বা ইনলাইন উপাদান থাকতে পারে।</li>
    <li>উদাহরণ: <code>&lt;div&gt;</code>, <code>&lt;p&gt;</code>, <code>&lt;h1&gt;</code> - <code>&lt;h6&gt;</code>, <code>&lt;ul&gt;</code>, <code>&lt;ol&gt;</code>, <code>&lt;li&gt;</code></li>
    <li>স্টাইলিং: ব্লক-লেভেল উপাদানগুলির প্রস্থ এবং উচ্চতা পরিবর্তন করা যায়।</li>
  </ul>
</details>

<details>
  <summary><strong>১৩/ HTML এ একটি তালিকা কিভাবে তৈরি করা হয়?</strong></summary>
  <p>উত্তর: একটি আনঅর্ডারড তালিকার জন্য <code>&lt;ul&gt;</code> এবং <code>&lt;li&gt;</code>, এবং একটি অর্ডারড তালিকার জন্য <code>&lt;ol&gt;</code> এবং <code>&lt;li&gt;</code> ট্যাগ ব্যবহার করা হয়।</p>
</details>

<details>
  <summary><strong>১৪/ কোন অ্যাট্রিবিউটটি একটি ইমেজের বিকল্প টেক্সট প্রদান করে?</strong></summary>
  <p>উত্তর: <code>alt</code> অ্যাট্রিবিউট।</p>
</details>

<details>
  <summary><strong>১৫/ একটি টেবিল HTML এ কিভাবে তৈরি করা হয়?</strong></summary>
  <p>উত্তর: <code>&lt;table&gt;</code>, <code>&lt;tr&gt;</code>, <code>&lt;td&gt;</code>, <code>&lt;th&gt;</code> ট্যাগগুলি ব্যবহার করে।</p>
  <table>
    <tr>
      <th>নাম</th>
      <th>বয়স</th>
      <th>শহর</th>
    </tr>
    <tr>
      <td>আহমেদ</td>
      <td>২৫</td>
      <td>ঢাকা</td>
    </tr>
    <tr>
      <td>সারা</td>
      <td>২২</td>
      <td>চট্টগ্রাম</td>
    </tr>
  </table>
</details>
<details>
  <summary><strong>১৬/ HTML5 এ স্থানাঙ্ক ভিত্তিক অবস্থান নির্ধারণের জন্য কোন API ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: জিওলোকেশন API।</p>
</details>

<details>
  <summary><strong>১৭/ HTML5 এর ক্যানভাস উপাদান কী জন্য ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: 2D গ্রাফিক্স এবং অ্যানিমেশন আঁকতে।</p>
</details>

<details>
  <summary><strong>১৮/ কিভাবে সেম্যান্টিক ট্যাগগুলি ওয়েব অ্যাক্সেসিবিলিটি উন্নত করে?</strong></summary>
  <p>উত্তর: 
    সেম্যান্টিক ট্যাগগুলি ওয়েব অ্যাক্সেসিবিলিটি উন্নত করে বিভিন্ন উপায়ে, যার মধ্যে রয়েছে:
  </p>
  <ul>
    <li><strong>স্ক্রিন রিডারের জন্য ওয়েবসাইটের কাঠামো স্পষ্ট করা:</strong> সেম্যান্টিক ট্যাগগুলি স্ক্রিন রিডারকে বলে যে ওয়েবপৃষ্ঠার বিভিন্ন অংশ কী কাজ করে। উদাহরণস্বরূপ, একটি <code>&lt;h1&gt;</code> ট্যাগ স্ক্রিন রিডারকে বলে যে এটি একটি শিরোনাম, যখন একটি <code>&lt;p&gt;</code> ট্যাগ স্ক্রিন রিডারকে বলে যে এটি একটি অনুচ্ছেদ। এটি ব্যবহারকারীদের ওয়েবপৃষ্ঠার বিষয়বস্তু আরও সহজে বুঝতে এবং নেভিগেট করতে সাহায্য করে।</li>
    <li><strong>সার্চ ইঞ্জিন অপ্টিমাইজেশন (SEO) উন্নত করা:</strong> সেম্যান্টিক ট্যাগগুলি সার্চ ইঞ্জিনগুলিকে বুঝতে সাহায্য করে যে ওয়েবপৃষ্ঠাটি কিসের সম্পর্কে। এটি ওয়েবসাইটটিকে প্রাসঙ্গিক অনুসন্ধানের ফলাফলে বৃদ্ধি করতে সাহায্য করে।</li>
    <li><strong>সহজেই বোঝার জন্য ওয়েবসাইট তৈরি করা:</strong> সেম্যান্টিক ট্যাগগুলি ব্যবহার করার ফলে ওয়েবসাইটগুলি আরও সহজে বোঝা যায়, এমনকি যারা HTML বা CSS-এর সাথে পরিচিত নন। এটি বিভিন্ন দক্ষতা স্তরের ব্যবহারকারীদের জন্য ওয়েবসাইটগুলি আরও অ্যাক্সেসযোগ্য করে তোলে।</li>
  </ul>
  <p>সেম্যান্টিক ট্যাগগুলির কিছু নির্দিষ্ট উদাহরণ যা ওয়েব অ্যাক্সেসিবিলিটি উন্নত করতে ব্যবহার করা যেতে পারে তার মধ্যে রয়েছে:</p>
  <ul>
    <li><code>&lt;h1&gt;</code> থেকে <code>&lt;h6&gt;</code>: শিরোনামগুলি নির্দেশ করতে।</li>
    <li><code>&lt;p&gt;</code>: অনুচ্ছেদগুলি নির্দেশ করতে।</li>
    <li><code>&lt;a&gt;</code>: হাইপারলিঙ্কগুলি নির্দেশ করতে।</li>
    <li><code>&lt;img&gt;</code>: চিত্রগুলি নির্দেশ করতে।</li>
    <li><code>&lt;table&gt;</code>: সারণিগুলি নির্দেশ করতে।</li>
    <li><code>&lt;ul&gt;</code> এবং <code>&lt;ol&gt;</code>: তালিকাগুলি নির্দেশ করতে।</li>
  </ul>
  <p>সেম্যান্টিক ট্যাগগুলি ব্যবহার করা ওয়েব অ্যাক্সেসিবিলিটি উন্নত করার একটি সহজ উপায়। এগুলি ব্যবহারকারীদের জন্য ওয়েবসাইটগুলি আরও সহজে বোঝা এবং ব্যবহার করা যায় তা নিশ্চিত করতে সাহায্য করে।</p>
</details>


## css 
<details>
  <summary><strong>১/ CSS কী এবং এটি কেন ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: CSS (Cascading Style Sheets) একটি স্টাইল শীট ভাষা যা HTML বা XML (SVG, XHTML) এর মত মার্কআপ ভাষার সাথে ব্যবহৃত হয়। এটি ওয়েব পেইজের বিন্যাস নির্ধারণ করতে ব্যবহৃত হয়, যেমন রঙ, ফন্ট, এবং লেআউট।</p>
</details>

<details>
  <summary><strong>২/ CSS-এ Selectors কী এবং কত প্রকারের Selectors আছে?</strong></summary>
  <p>উত্তর: CSS-এ Selectors হল উপাদানগুলি নির্ধারণ করার উপায় যেগুলি আপনি স্টাইল করতে চান। Selectors-এর প্রকারভেদগুলি হল: Universal, Type, Class, ID, Attribute, Pseudo-class, এবং Pseudo-element।</p>
</details>

<details>
  <summary><strong>৩/ CSS-এ Inline, Internal এবং External stylesheet-এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>উত্তর: Inline CSS সরাসরি HTML ট্যাগের মধ্যে লেখা হয়, Internal CSS <code>&lt;style&gt;</code> ট্যাগের মধ্যে লেখা হয় যা HTML ডকুমেন্টের <code>&lt;head&gt;</code> সেকশনে থাকে, এবং External CSS আলাদা .css ফাইলে লেখা হয় এবং HTML ডকুমেন্টে <code>&lt;link&gt;</code> ট্যাগের মাধ্যমে যুক্ত করা হয়।</p>
</details>

<details>
  <summary><strong>৪/ CSS-এ Classes এবং IDs এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>উত্তর: CSS-এ Classes এবং IDs-এর মধ্যে পার্থক্য হল, Classes বহু HTML উপাদানে প্রয়োগ করা যায় এবং এগুলি ‘.’ সিম্বল দিয়ে শুরু হয়। অন্যদিকে, IDs একটি HTML উপাদানে অনন্য এবং ‘#’ সিম্বল দিয়ে শুরু হয়, যা সুনির্দিষ্টভাবে একটি উপাদানকে লক্ষ্য করতে ব্যবহৃত হয়।</p>
</details>

<details>
  <summary><strong>৫/ CSS Box Model কী এবং এর উপাদানগুলো কী কী?</strong></summary>
  <p>উত্তর: CSS Box Model হল একটি মডেল যা প্রতিটি HTML উপাদানকে একটি বক্স হিসেবে দেখায়। এর উপাদানগুলো হল: Content, Padding, Border, এবং Margin।</p>
</details>

<details>
  <summary><strong>৬/ Box Model-এর padding এবং margin এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>উত্তর: Padding হল উপাদানের ভিতরের অংশ এবং বর্ডারের মধ্যে ফাঁকা জায়গা, আর Margin হল উপাদানের বর্ডার এবং বাইরের অংশের মধ্যে ফাঁকা জায়গা।</p>
</details>

<details>
  <summary><strong>৭/ Border-box এবং content-box এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>উত্তর: Border-box এ, padding এবং border উপাদানের মোট প্রস্থ এবং উচ্চতায় অন্তর্ভুক্ত হয়। Content-box এ, প্রস্থ এবং উচ্চতা কেবলমাত্র উপাদানের বিষয়বস্তু পর্যন্ত সীমাবদ্ধ থাকে, padding এবং border অতিরিক্ত যোগ করা হয়।</p>
</details>

<details>
  <summary><strong>৮/ Box-sizing প্রোপার্টি কী এবং এটি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: Box-sizing প্রোপার্টি বক্স মডেল নির্ধারণ করে যে কিভাবে উপাদানের প্রস্থ এবং উচ্চতা গণনা করা হবে। এটি দুটি মান গ্রহণ করে: content-box এবং border-box।</p>
</details>

<details>
  <summary><strong>৯/ Margin collapsing কী এবং এটি কিভাবে কাজ করে?</strong></summary>
  <p>উত্তর: Margin collapsing হল দুটি বা ততোধিক খাড়া মার্জিন একসাথে মিলিত হওয়া এবং একক মার্জিন গঠন করা। সবচেয়ে বড় মার্জিনটি বজায় থাকে এবং ছোট মার্জিনগুলি মুছে যায়।</p>
</details>

<details>
  <summary><strong>১০/ Relative এবং Absolute পজিশনিং-এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>উত্তর: Relative পজিশনিং উপাদানটিকে তার স্বাভাবিক অবস্থান থেকে সরিয়ে দেয়, যেখানে Absolute পজিশনিং উপাদানটিকে তার পূর্বপুরুষের প্রথম পজিশন্ড উপাদান বা ডকুমেন্টের বডি থেকে সরিয়ে দেয়।</p>
</details>

<details>
  <summary><strong>১১/ CSS-এ Position প্রোপার্টি কী এবং এর প্রকারভেদ কী কী?</strong></summary>
  <p>উত্তর: CSS-এ Position প্রোপার্টি একটি উপাদানের অবস্থান নির্ধারণ করে। এর প্রকারভেদগুলো হল:
  <ul>
    <li>Static: ডিফল্ট পজিশনিং, উপাদান স্বাভাবিক অবস্থানে থাকে।</li>
    <li>Relative: উপাদান তার স্বাভাবিক অবস্থান থেকে স্থানান্তরিত হয়।</li>
    <li>Absolute: উপাদান তার প্রথম পজিশন্ড প্যারেন্ট থেকে স্থানান্তরিত হয়।</li>
    <li>Fixed: উপাদান ভিউপোর্টের আপেক্ষিকভাবে স্থির থাকে।</li>
    <li>Sticky: উপাদান স্ক্রল করার সময় নির্দিষ্ট অবস্থানে আটকানো থাকে।</li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>১২/ Fixed & Sticky কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: Fixed পজিশনিং উপাদানটিকে ভিউপোর্টের আপেক্ষিকভাবে স্থির করে। অর্থাৎ, যখন আপনি পৃষ্ঠাটি স্ক্রল করেন, তখন এটি একই স্থানে থাকে। এটি সাধারণত ইউজার ইন্টারফেস উপাদান, যেমন ন্যাভিগেশন বারে ব্যবহৃত হয়।
  <br>
  Sticky পজিশনিং উপাদানটিকে একটি নির্দিষ্ট অবস্থানে স্থির করে, কিন্তু এটি স্ক্রল করার সময় অন্যান্য উপাদানের সাথে চলাচল করে। যখন উপাদানটি নির্দিষ্ট স্ক্রল পজিশনে পৌঁছে যায়, তখন এটি স্থির হয়ে যায়। এটি সাধারণত হেডার বা সেকশন টাইটেল তৈরি করতে ব্যবহৃত হয়।</p>
</details>

<details>
  <summary><strong>১৩/ Z-index কী এবং এটি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: Z-index একটি CSS প্রোপার্টি যা উপাদানের স্ট্যাকিং অর্ডার নির্ধারণ করে। এটি শুধুমাত্র পজিশন্ড উপাদান (যেমন relative, absolute, fixed, বা sticky) এর জন্য প্রযোজ্য।
  <ul>
    <li>কিভাবে কাজ করে:</li>
    <li>Z-index এর মান যত বেশি হবে, উপাদানটি তত বেশি উপরে থাকবে।</li>
    <li>উদাহরণস্বরূপ, যদি একটি উপাদানের z-index 1 এবং অন্যটির 2 হয়, তবে দ্বিতীয়টি প্রথমটির উপরে প্রদর্শিত হবে।</li>
    <li>Z-index এর মান ইতিবাচক, নেতিবাচক বা শূন্য হতে পারে।</li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>১৪/ Flexbox কী এবং এটি কেন ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: Flexbox হল CSS3 এর একটি লেআউট মডেল যা সহজে এবং দক্ষভাবে কমপ্লেক্স লেআউট গঠন করতে ব্যবহৃত হয়। এটি কন্টেইনার এবং এর CHILD উপাদানগুলোর মধ্যে স্থান এবং আলাইনমেন্ট নিয়ন্ত্রণ করতে সাহায্য করে।</p>
</details>

<details>
  <summary><strong>১৫/ Flexbox-এ align-items প্রোপার্টির কাজ কী?</strong></summary>
  <p>উত্তর: align-items প্রোপার্টি ক্রস অ্যাক্স বরাবর ফ্লেক্স আইটেমগুলির সমতল নির্ধারণ করে। এর মানগুলি হল: flex-start, flex-end, center, baseline, এবং stretch।</p>
</details>

<details>
  <summary><strong>১৬/ Flex-grow এবং flex-shrink প্রোপার্টি কী এবং কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর:
  <ul>
    <li><strong>Flex-grow:</strong> Flex-grow প্রোপার্টি ফ্লেক্স কন্টেইনারের মধ্যে একটি ফ্লেক্স আইটেমের বৃদ্ধির হার নির্ধারণ করে। যদি কন্টেইনারে অতিরিক্ত স্থান থাকে, তবে flex-grow এর মানের ভিত্তিতে আইটেমগুলো সমানভাবে বা নির্দিষ্ট অনুপাতে স্থান গ্রহণ করে। উদাহরণস্বরূপ, যদি একটি আইটেমের flex-grow 2 এবং অন্যটির 1 হয়, তাহলে প্রথমটি দ্বিতীয়টির চেয়ে দ্বিগুণ স্থান নেবে।</li>
    <li><strong>Flex-shrink:</strong> Flex-shrink প্রোপার্টি ফ্লেক্স আইটেমের সংকোচনের হার নির্ধারণ করে যখন কন্টেইনারে স্থান কম থাকে। এটি কন্টেইনারের মোট প্রস্থ বা উচ্চতার তুলনায় আইটেমগুলোকে সংকোচন করতে সাহায্য করে। উদাহরণস্বরূপ, যদি একটি আইটেমের flex-shrink 1 এবং অন্যটির 2 হয়, তাহলে দ্বিতীয় আইটেমটি প্রথমটির তুলনায় দ্বিগুণ হারে সংকুচিত হবে।</li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>১৭/ CSS Grid Layout কী এবং এটি কেন ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: CSS Grid Layout হল একটি 2D লেআউট মডেল যা কমপ্লেক্স লেআউট তৈরি করতে ব্যবহৃত হয়। এটি কন্টেইনার এবং এর child উপাদানগুলির জন্য কলাম এবং সারি তৈরি করতে সাহায্য করে।</p>
</details>

<details>
  <summary><strong>১৮/ Grid container এবং Grid item কী?</strong></summary>
  <p>উত্তর: Grid container হল একটি উপাদান যা display: grid বা display: inline-grid প্রোপার্টি ব্যবহার করে। Grid items হল সেই উপাদানের সরাসরি সন্তান উপাদানগুলি।</p>
</details>

<details>
  <summary><strong>১৯/ Grid template-columns এবং grid template-rows প্রোপার্টি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: grid-template-columns এবং grid-template-rows প্রোপার্টি Grid কন্টেইনারের কলাম এবং সারির সংখ্যা এবং আকার নির্ধারণ করে।</p>
</details>

<details>
  <summary><strong>২০/ Grid-gap বা gap প্রোপার্টি কী?</strong></summary>
  <p>উত্তর: Grid-gap বা gap প্রোপার্টি Grid items এর মধ্যে ফাঁকা স্থান নির্ধারণ করে। এটি কলাম এবং সারির মধ্যে স্থান যোগ করতে ব্যবহৃত হয়।</p>
</details>

<details>
  <summary><strong>২১/ Grid item এর অবস্থান নির্ধারণ করতে কোন প্রোপার্টি ব্যবহার করা হয়?</strong></summary>
  <p>উত্তর: Grid item এর অবস্থান নির্ধারণ করতে grid-column এবং grid-row প্রোপার্টি ব্যবহার করা হয়। Grid-column প্রোপার্টি আইটেমটির কোন কলাম থেকে শুরু এবং কোন কলামে শেষ হবে তা নির্ধারণ করে। Grid-row প্রোপার্টি আইটেমটির কোন সারি থেকে শুরু এবং কোন সারিতে শেষ হবে তা নির্ধারণ করে।</p>
</details>

<details>
  <summary><strong>২২/ Typography কী?</strong></summary>
  <p>উত্তর: Typography হল টেক্সটের ডিজাইন এবং স্টাইলিংয়ের প্রক্রিয়া। এটি টেক্সটের ফন্ট, আকার, লাইন স্পেসিং, এবং অন্যান্য বৈশিষ্ট্য নির্ধারণ করে যা ওয়েব পৃষ্ঠায় টেক্সটের চেহারা ও পাঠযোগ্যতা প্রভাবিত করে।</p>
</details>

<details>
  <summary><strong>২৩/ CSS-এ font-family প্রোপার্টি কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: font-family প্রোপার্টি একটি টেক্সটের জন্য ব্যবহৃত ফন্ট নির্ধারণ করে। এটি ফন্টের নামের একটি তালিকা গ্রহণ করে, যেখানে প্রথম উপলব্ধ ফন্টটি প্রয়োগ করা হয়। উদাহরণ: <code>font-family: Arial, sans-serif;</code></p>
</details>

<details>
  <summary><strong>২৪/ CSS-এ font-size প্রোপার্টি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: font-size প্রোপার্টি টেক্সটের আকার নির্ধারণ করে। এটি বিভিন্ন ইউনিটে দেওয়া যেতে পারে, যেমন পিক্সেল(px), এম(em), রিম(rem), শতাংশ(%), বা পয়েন্ট(pt)। উদাহরণ: <code>font-size: 16px;</code></p>
</details>

<details>
  <summary><strong>২৫/ font-weight প্রোপার্টি কী এবং এটি কীভাবে ব্যবহার করা হয়?</strong></summary>
  <p>উত্তর: font-weight প্রোপার্টি টেক্সটের বোল্ডনেস নির্ধারণ করে। এটি বিভিন্ন মান নিতে পারে, যেমন normal, bold, বা নির্দিষ্ট সংখ্যাসূচক মান (100 থেকে 900 পর্যন্ত)। উদাহরণ: <code>font-weight: bold;</code></p>
</details>

<details>
  <summary><strong>২৬/ line-height প্রোপার্টি কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: line-height প্রোপার্টি লাইনের উচ্চতা নির্ধারণ করে, যা লাইনগুলির মধ্যে স্পেসিং নিয়ন্ত্রণ করে। এটি সাধারণত ফন্ট সাইজের একটি গুণক হিসাবে ব্যবহৃত হয়। উদাহরণ: <code>line-height: 1.5;</code></p>
</details>

<details>
  <summary><strong>২৭/ font-style প্রোপার্টি কী?</strong></summary>
  <p>উত্তর: font-style প্রোপার্টি টেক্সটের স্টাইল নির্ধারণ করে, যেমন normal, italic, এবং oblique। উদাহরণ: <code>font-style: italic;</code></p>
</details>

<details>
  <summary><strong>২৮/ text-transform প্রোপার্টি কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: text-transform প্রোপার্টি টেক্সটের অক্ষরের কেস পরিবর্তন করে। এর মানগুলি হল: capitalize, uppercase, lowercase, এবং none। উদাহরণ: <code>text-transform: uppercase;</code></p>
</details>

<details>
  <summary><strong>২৯/ letter-spacing প্রোপার্টি কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: letter-spacing প্রোপার্টি টেক্সটের অক্ষরগুলির মধ্যে ফাঁকা স্থান নির্ধারণ করে। এটি পজিটিভ বা নেগেটিভ মান নিতে পারে। উদাহরণ: <code>letter-spacing: 2px;</code></p>
</details>

<details>
  <summary><strong>৩০/ word-spacing প্রোপার্টি কী এবং এটি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: word-spacing প্রোপার্টি টেক্সটের শব্দগুলির মধ্যে ফাঁকা স্থান নির্ধারণ করে। এটি টেক্সটের পাঠযোগ্যতা উন্নত করতে ব্যবহৃত হয়। উদাহরণ: <code>word-spacing: 4px;</code></p>
</details>

## javascript

<details>
  <summary><strong>১/ JavaScript কী এবং এটি কেন ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: JavaScript একটি প্রোগ্রামিং ভাষা যা ওয়েবসাইটে ইন্টারঅ্যাকটিভ কনটেন্ট যুক্ত করতে ব্যবহৃত হয়। এটি HTML এবং CSS এর সাথে ব্যবহৃত হয়, ডাইনামিক ওয়েব পেজ তৈরি করতে এবং ব্যবহারকারীর সাথে ইন্টারঅ্যাকশন পরিচালনা করতে।</p>
</details>

<details>
  <summary><strong>২/ for লুপ কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: for লুপ একটি নির্দিষ্ট সংখ্যক বার কোড এক্সিকিউট করার জন্য ব্যবহৃত হয়। এটি সাধারণত পুনরাবৃত্তিমূলক কাজগুলির জন্য ব্যবহৃত হয়, যেখানে একটি কাউন্টার ভেরিয়েবল ব্যবহার করে লুপের প্রতিটি পুনরাবৃত্তি ট্র্যাক করা হয়।
  <pre>
  <code>
  for (initialization; condition; increment/decrement) {
      // কোড ব্লক যা এক্সিকিউট হবে
  }
  </code>
  </pre>
  কীভাবে কাজ করে:
  <ul>
    <li><strong>Initialization (শুরু):</strong> এটি লুপের কাউন্টার ভেরিয়েবল সেট আপ করে। এটি লুপের শুরুতে একবার এক্সিকিউট হয়।</li>
    <li><strong>Condition (শর্ত):</strong> প্রতিটি পুনরাবৃত্তির আগে এই শর্তটি চেক করা হয়। যদি শর্তটি সত্য হয়, তবে লুপটি চলতে থাকে। যদি শর্তটি মিথ্যা হয়, তবে লুপটি থেমে যায়।</li>
    <li><strong>Increment/Decrement (বৃদ্ধি/হ্রাস):</strong> প্রতিটি পুনরাবৃত্তির পরে কাউন্টার ভেরিয়েবলটি বৃদ্ধি বা হ্রাস করা হয়।</li>
    <li><strong>Code Block (কোড ব্লক):</strong> লুপের প্রতিটি পুনরাবৃত্তিতে এই কোড ব্লকটি এক্সিকিউট হয়।</li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>৩/ if...else স্টেটমেন্ট কী এবং এটি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>উত্তর: if...else স্টেটমেন্ট হল শর্তসাপেক্ষ লজিক্যাল স্টেটমেন্ট যা একটি শর্ত (condition) পরীক্ষা করে এবং সেই শর্তটি সত্য (true) হলে একটি কোড ব্লক এবং মিথ্যা (false) হলে অন্য একটি কোড ব্লক এক্সিকিউট করে। এটি প্রোগ্রামিংয়ে নির্দিষ্ট শর্ত অনুযায়ী বিভিন্ন ক্রিয়া সম্পাদনের জন্য ব্যবহৃত হয়।
  <pre>
  <code>
  if (condition) {
      // কোড ব্লক যা এক্সিকিউট হবে যদি condition সত্য হয়
  } else {
      // কোড ব্লক যা এক্সিকিউট হবে যদি condition মিথ্যা হয়
  }
  </code>
  </pre>
  কীভাবে কাজ করে:
  <ul>
    <li><strong>condition:</strong> এটি একটি এক্সপ্রেশন যা true বা false এ মূল্যায়ন করা হয়।</li>
    <li>যদি condition সত্য হয় (true), তবে if ব্লকের কোড এক্সিকিউট হয়।</li>
    <li>যদি condition মিথ্যা হয় (false), তবে else ব্লকের কোড এক্সিকিউট হয়।</li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>৪/ ফাংশন কী এবং এটি কীভাবে তৈরি করা হয়?</strong></summary>
  <p>উত্তর: ফাংশন হল কোডের একটি পুনর্ব্যবহারযোগ্য ব্লক যা একটি নির্দিষ্ট কাজ সম্পন্ন করে। এটি function কীওয়ার্ড ব্যবহার করে তৈরি করা হয়। উদাহরণ:
  <pre>
  <code>
  function greet(name) {
      return `Hello, ${name}!`;
  }
  </code>
  </pre>
  </p>
</details>

<details>
  <summary><strong>৫/ while লুপ কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: while লুপ একটি কন্ডিশনাল লুপ যা শর্ত (condition) সত্য (true) থাকলে কোড ব্লক বারবার এক্সিকিউট করে। এটি সাধারণত ব্যবহার করা হয় যখন লুপের পুনরাবৃত্তি সংখ্যা পূর্বনির্ধারিত নয়।
  <pre>
  <code>
  let i = 0;
  while (i < 5) {
      console.log(i);
      i++;
  }
  </code>
  </pre>
  কীভাবে কাজ করে:
  <ul>
    <li>condition পরীক্ষা করা হয়।</li>
    <li>যদি condition সত্য হয়, কোড ব্লক এক্সিকিউট হয়।</li>
    <li>এরপর পুনরায় condition পরীক্ষা করা হয়।</li>
    <li>শর্ত মিথ্যা হলে লুপটি থামে।</li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>৬/ Array methods (push, pop, shift, unshift, splice) মেথড কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর:
  <ul>
    <li><strong>push():</strong> মেথড একটি অ্যারের শেষে একটি বা একাধিক উপাদান যোগ করে এবং অ্যারের নতুন দৈর্ঘ্য ফেরত দেয়। উদাহরণ:
    <pre>
    <code>
    let fruits = ["apple", "banana"];
    fruits.push("orange");
    </code>
    </pre>
    </li>
    <li><strong>pop():</strong> মেথড একটি অ্যারের শেষ উপাদানটি সরিয়ে ফেলে এবং সেই উপাদানটি ফেরত দেয়। উদাহরণ:
    <pre>
    <code>
    let fruits = ["apple", "banana", "orange"];
    let lastFruit = fruits.pop();
    </code>
    </pre>
    </li>
    <li><strong>shift():</strong> মেথড একটি অ্যারের প্রথম উপাদানটি সরিয়ে ফেলে এবং সেই উপাদানটি ফেরত দেয়। উদাহরণ:
    <pre>
    <code>
    let fruits = ["apple", "banana", "orange"];
    let firstFruit = fruits.shift();
    </code>
    </pre>
    </li>
    <li><strong>unshift():</strong> মেথড একটি অ্যারের শুরুতে একটি বা একাধিক উপাদান যোগ করে এবং অ্যারের নতুন দৈর্ঘ্য ফেরত দেয়। উদাহরণ:
    <pre>
    <code>
    let fruits = ["banana", "orange"];
    fruits.unshift("apple");
    </code>
    </pre>
    </li>
    <li><strong>splice():</strong> মেথড একটি অ্যারের নির্দিষ্ট অবস্থানে উপাদান যোগ বা সরাতে ব্যবহৃত হয়। এটি উপাদান সরিয়ে ফেলে এবং নতুন উপাদান যোগ করতে পারে। উদাহরণ:
    <pre>
    <code>
    let fruits = ["apple", "banana", "orange"];
    fruits.splice(1, 1, "kiwi");
    </code>
    </pre>
    </li>
  </ul>
  </p>
</details>

<details>
  <summary><strong>7/ DOM কী এবং DOM ম্যানিপুলেশন কীভাবে কাজ করে?</strong></summary>
  <p>
    DOM (Document Object Model) হল একটি কাঠামোগত উপস্থাপন যা HTML বা XML ডকুমেন্টকে একটি অবজেক্ট হিসেবে বর্ণনা করে। DOM ব্যবহার করে JavaScript ডকুমেন্টের বিভিন্ন উপাদান (elements) এবং বৈশিষ্ট্য (attributes) পরিবর্তন, যোগ, অথবা মুছে ফেলতে পারে।
  </p>
  <p><strong>DOM ম্যানিপুলেশন কীভাবে কাজ করে:</strong></p>
  <ul>
    <li>
      <strong>DOM অ্যাক্সেস:</strong> JavaScript ডকুমেন্টের উপাদানগুলিতে অ্যাক্সেস করতে বিভিন্ন মেথড ব্যবহার করে, যেমন <code>getElementById()</code>, <code>getElementsByClassName()</code>, এবং <code>querySelector()</code>.
      <p><strong>উদাহরণ:</strong></p>
      <pre><code>document.getElementById("myElement").innerText = "New Text";</code></pre>
    </li>
    <li>
      <strong>উপাদান পরিবর্তন:</strong> একটি উপাদানের বিষয়বস্তু (content) পরিবর্তন করতে <code>innerHTML</code>, <code>innerText</code>, অথবা <code>textContent</code> ব্যবহার করা হয়।
      <p><strong>উদাহরণ:</strong></p>
      <pre><code>document.getElementById("myElement").innerText = "New Text";</code></pre>
    </li>
    <li>
      <strong>স্টাইল পরিবর্তন:</strong> CSS স্টাইল পরিবর্তন করতে <code>style</code> প্রোপার্টি ব্যবহার করা হয়।
      <p><strong>উদাহরণ:</strong></p>
      <pre><code>document.getElementById("myElement").style.color = "red";</code></pre>
    </li>
    <li>
      <strong>নতুন উপাদান যোগ করা:</strong> নতুন HTML উপাদান তৈরি করে এবং এটি DOM এ যুক্ত করতে <code>createElement()</code> এবং <code>appendChild()</code> ব্যবহার করা হয়।
      <p><strong>উদাহরণ:</strong></p>
      <pre><code>let newDiv = document.createElement("div");
newDiv.innerText = "This is a new div!";
document.body.appendChild(newDiv);</code></pre>
    </li>
    <li>
      <strong>ইভেন্ট হ্যান্ডলিং:</strong> DOM ম্যানিপুলেশন ব্যবহার করে ইভেন্ট লিসনার যোগ করা হয়, যেমন ক্লিক ইভেন্ট।
      <p><strong>উদাহরণ:</strong></p>
      <pre><code>document.getElementById("myButton").addEventListener("click", function() {
    alert("Button clicked!");
});</code></pre>
    </li>
  </ul>
</details>

<details>
  <summary><strong>8/ JavaScript-এ ইভেন্ট হ্যান্ডলিং কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>
    ইভেন্ট হ্যান্ডলিং হল একটি প্রক্রিয়া যা ব্যবহারকারীর কার্যকলাপ (যেমন ক্লিক, কীবোর্ড প্রেস, মাউস হভার ইত্যাদি) অনুযায়ী JavaScript কোড এক্সিকিউট করতে ব্যবহৃত হয়। এটি ওয়েব পেজের ইন্টারঅ্যাকটিভিটি এবং ব্যবহারকারীর অভিজ্ঞতা উন্নত করতে সাহায্য করে।
  </p>
  <p><strong>কীভাবে কাজ করে:</strong></p>
  <ul>
    <li>
      <strong>ইভেন্ট Listener যোগ করা:</strong> HTML উপাদানে একটি ইভেন্ট Listener যোগ করা হয় যা নির্দিষ্ট ইভেন্ট সংঘটিত হলে একটি ফাংশন কার্যকর করবে।
      <p><strong>উদাহরণ:</strong></p>
      <pre><code>document.getElementById("myButton").addEventListener("click", function() {
    alert("Button clicked!");
});</code></pre>
    </li>
    <li>
      <strong>ইভেন্ট টাইপ:</strong> বিভিন্ন ধরনের ইভেন্ট আছে, যেমন:
      <ul>
        <li><code>click</code>: একটি উপাদানে ক্লিক করলে।</li>
        <li><code>mouseover</code>: মাউস উপাদানের উপর এলে।</li>
        <li><code>keydown</code>: কীবোর্ডের কী প্রেস করলে।</li>
      </ul>
    </li>
    <li>
      <strong>ইভেন্ট অবজেক্ট:</strong> যখন একটি ইভেন্ট সংঘটিত হয়, একটি ইভেন্ট অবজেক্ট তৈরি হয় যা ইভেন্টের সম্পর্কে তথ্য ধারণ করে (যেমন কনটেক্সট, টার্গেট উপাদান ইত্যাদি)।
      <p><strong>উদাহরণ:</strong></p>
      <pre><code>document.getElementById("myButton").addEventListener("click", function(event) {
    console.log(event.target); // টার্গেট উপাদান প্রদর্শন করবে
});</code></pre>
    </li>
    <li>
      <strong>ফাংশন কার্যকর করা:</strong> যখন ইভেন্টটি সংঘটিত হয়, সংশ্লিষ্ট ফাংশনটি কার্যকর হয়, যা ব্যবহারকারীর ইন্টারঅ্যাকশনের ভিত্তিতে নির্দিষ্ট কার্যক্রম সম্পাদন করে।
    </li>
  </ul>
</details>

<details>
  <summary><strong>9/ getElementById() এবং querySelector() এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>
    <strong>getElementById()</strong>: শুধুমাত্র একটি নির্দিষ্ট ID-এর জন্য ব্যবহৃত হয় এবং একটি একক HTML উপাদান ফেরত দেয়।
    <br>
    <strong>querySelector()</strong>: CSS সিলেক্টর ব্যবহার করে, একটি উপাদান ফেরত দেয় এবং যদি একাধিক উপাদান থাকে তবে প্রথমটিকে নির্বাচন করে। <code>querySelectorAll()</code> সব মিলে উপাদান ফেরত দেয়।
  </p>
</details>

<details>
  <summary><strong>10/ innerHTML এবং innerText এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>
    <strong>innerHTML</strong>: HTML ট্যাগ সহ পূর্ণ HTML কনটেন্ট ফেরত দেয় এবং সেট করে।
    <br>
    <strong>innerText</strong>: শুধুমাত্র টেক্সট ফেরত দেয় এবং সেট করে, HTML ট্যাগ বাদ দিয়ে।
    <p><strong>উদাহরণ:</strong></p>
    <pre><code>let element = document.getElementById("myElement");
element.innerHTML = "<strong>Hello</strong>"; // HTML ট্যাগ অন্তর্ভুক্ত
element.innerText = "Hello"; // শুধুমাত্র টেক্সট
</code></pre>
  </p>
</details>
<details>
  <summary><strong>11/ addEventListener() এবং onclick এর মধ্যে পার্থক্য কী?</strong></summary>
  <p>
    <strong>addEventListener():</strong>
    <ul>
      <li>এটি একটি মেথড যা একাধিক ইভেন্ট লিসনার যোগ করতে দেয়। একাধিক ইভেন্ট একই উপাদানে যুক্ত করা সম্ভব।</li>
      <li>এটি বিভিন্ন ধরনের ইভেন্টের জন্য ব্যবহার করা যায় এবং কাস্টম ইভেন্টও সমর্থন করে।</li>
      <li>ইভেন্ট লিসনারগুলি মুছতে <code>removeEventListener()</code> ব্যবহার করা যায়। </li>
    </ul>
    <strong>onclick:</strong>
    <ul>
      <li>এটি একটি প্রোপার্টি যা শুধুমাত্র একটি ইভেন্ট লিসনার সংযুক্ত করে। পূর্ববর্তী লিসনার মুছে যাবে যদি নতুন একটি যুক্ত হয়।</li>
      <li>এটি শুধুমাত্র ক্লিক ইভেন্টের জন্য ব্যবহৃত হয়।</li>
    </ul>
  </p>
</details>

<details>
  <summary><strong>12/ let এবং const কী এবং এগুলি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>
    <strong>let</strong> এবং <strong>const</strong> হল ES6 এর নতুন কীওয়ার্ড। 
    <ul>
      <li><strong>let</strong> ব্লকের স্কোপে ভেরিয়েবল ডিক্লেয়ার করতে ব্যবহৃত হয়।</li>
      <li><strong>const</strong> কনস্ট্যান্ট ভেরিয়েবল ডিক্লেয়ার করতে ব্যবহৃত হয় যা পুনরায় নির্ধারণ করা যায় না।</li>
    </ul>
  </p>
</details>

<details>
  <summary><strong>13/ Arrow ফাংশন কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>
    <strong>Arrow ফাংশন</strong> হল ES6 এর একটি নতুন ফাংশন সিনট্যাক্স যা সংক্ষিপ্ত এবং আরও সংক্ষিপ্ত। উদাহরণ:
    <pre><code>const add = (a, b) => a + b;</code></pre>
  </p>
</details>

<details>
  <summary><strong>14/ Template literals কী এবং এটি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>
    <strong>Template literals</strong> হল ES6 এর একটি নতুন ফিচার যা ব্যাকটিক (<code>&grave;</code>) ব্যবহার করে স্ট্রিং ইন্টারপোলেশন এবং মাল্টি-লাইন স্ট্রিং তৈরি করতে ব্যবহৃত হয়। উদাহরণ:
    <pre><code>const name = "John";
const greeting = `Hello, ${name}!`;</code></pre>
  </p>
</details>

<details>
  <summary><strong>15/ Default parameters কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>
    <strong>Default parameters</strong> একটি ফাংশনের প্যারামিটারগুলির জন্য ডিফল্ট মান নির্ধারণ করে যদি কোনো মান পাস না করা হয়। উদাহরণ:
    <pre><code>function greet(name = "Guest") {
    return `Hello, ${name}!`;
}</code></pre>
  </p>
</details>

<details>
  <summary><strong>16/ Rest এবং Spread অপারেটর কী এবং এগুলি কীভাবে ব্যবহৃত হয়?</strong></summary>
  <p>
    <strong>Rest অপারেটর</strong> (<code>...</code>) ফাংশনে একটি অবশিষ্ট প্যারামিটার সংগ্রহ করতে ব্যবহৃত হয়। 
    <pre><code>function sum(...numbers) { // Rest অপারেটর
    return numbers.reduce((a, b) => a + b, 0);
}</code></pre>
    <strong>Spread অপারেটর</strong> (<code>...</code>) একটি অ্যারে বা অবজেক্টকে পৃথক উপাদানে বিস্তৃত করতে ব্যবহৃত হয়। 
    <pre><code>const arr = [1, 2, 3];
const newArr = [...arr, 4, 5]; // Spread অপারেটর</code></pre>
  </p>
</details>

<details>
  <summary><strong>17/ Array এবং Object Destructuring কী?</strong></summary>
  <p>
    <strong>Array Destructuring</strong> হল একটি সিনট্যাক্স যা JavaScript অ্যারেকে সহজে ভাঙার (extract) জন্য ব্যবহৃত হয়। এটি একটি অ্যারের উপাদানগুলোকে ভেরিয়েবল হিসাবে একসঙ্গে ঘোষণা করতে দেয়।
    <pre><code>const fruits = ["apple", "banana", "orange"];
const [first, second] = fruits;
console.log(first); // আউটপুট: apple
console.log(second); // আউটপুট: banana</code></pre>
    <strong>Object Destructuring</strong> হল একটি সিনট্যাক্স যা JavaScript অবজেক্টের প্রোপার্টিগুলোকে সহজে ভাঙার জন্য ব্যবহৃত হয়। এটি অবজেক্টের প্রোপার্টিগুলোকে ভেরিয়েবল হিসাবে একসঙ্গে ঘোষণা করতে দেয়।
    <pre><code>const person = { name: "John", age: 30 };
const { name, age } = person;
console.log(name); // আউটপুট: John
console.log(age); // আউটপুট: 30</code></pre>
  </p>
</details>

<details>
  <summary><strong>18/ Promises কী এবং এগুলি কীভাবে কাজ করে?</strong></summary>
  <p>
    <strong>Promises</strong> একটি অবজেক্ট যা ভবিষ্যতে ঘটতে পারে এমন একটি মানের প্রতিনিধিত্ব করে। এটি তিনটি অবস্থায় থাকতে পারে: Pending, Fulfilled, বা Rejected।
    <pre><code>let myPromise = new Promise((resolve, reject) => {
    // Async operation
    resolve("Success!");
});</code></pre>
  </p>
</details>

<details>
  <summary><strong>19/ ES6-এ Modules কীভাবে কাজ করে?</strong></summary>
  <p>
    <strong>ES6-এ modules</strong> কোডের পুনঃব্যবহারযোগ্য অংশ তৈরির জন্য ব্যবহৃত হয়। <code>export</code> এবং <code>import</code> কিওয়ার্ডের মাধ্যমে ফাংশন, অবজেক্ট, অথবা ভেরিয়েবল অন্য ফাইল থেকে আমদানি বা রপ্তানি করা যায়।
    <pre><code>// myModule.js
export const myFunction = () => {};

// main.js
import { myFunction } from './myModule.js';</code></pre>
  </p>
</details>

<details>
  <summary><strong>20/ Async/Await কী এবং এটি কীভাবে কাজ করে?</strong></summary>
  <p>
    <strong>Async/Await</strong> হল JavaScript-এ প্রতিশ্রুতি (Promises) এর উপর ভিত্তি করে অ্যাসিনক্রোনাস কোড লেখা সহজ করার একটি উপায়। <code>async</code> কিওয়ার্ড একটি ফাংশনকে অ্যাসিনক্রোনাস হিসেবে চিহ্নিত করে এবং <code>await</code> কিওয়ার্ড Promise-এর ফলাফল পাওয়ার জন্য ব্যবহৃত হয়, যা কোডকে সিঙ্ক্রোনাস মনে করায়।
    <pre><code>async function fetchData() {
    try {
        const response = await fetch('https://api.example.com/data');
        const data = await response.json();
        console.log(data);
    } catch (error) {
        console.error('Error fetching data:', error);
    }
}
fetchData()</code></pre>
  </p>
</details>

## React

# React Interview Questions

## Concept of Reconciliation

<details>
  <summary><strong>1/ Reconciliation কী?</strong></summary>
  <p>উত্তর: Reconciliation হল React-এর একটি প্রক্রিয়া যা উপাদানগুলির মধ্যে পার্থক্য নির্ধারণ করে এবং কেবলমাত্র পরিবর্তিত অংশগুলি DOM-এ আপডেট করে। এটি পারফরম্যান্স উন্নত করতে সাহায্য করে এবং দ্রুত UI রেন্ডারিং নিশ্চিত করে।</p>
</details>

<details>
  <summary><strong>2/ Reconciliation কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: React-এর Reconciliation প্রক্রিয়া Virtual DOM ব্যবহার করে। যখন একটি কম্পোনেন্ট আপডেট হয়, React প্রথমে Virtual DOM আপডেট করে এবং পরে মূল DOM-এ প্রয়োজনীয় পরিবর্তনগুলি প্রয়োগ করে।</p>
</details>

<details>
  <summary><strong>3/ Key prop কি এবং এটি Reconciliation-এ কীভাবে সাহায্য করে?</strong></summary>
  <p>উত্তর: Key prop একটি ইউনিক আইডেন্টিফায়ার যা React কে উপাদানগুলির মধ্যে পার্থক্য নির্ধারণ করতে সাহায্য করে। এটি তালিকা (list) উপাদানের মধ্যে দ্রুত এবং কার্যকরী আপডেট নিশ্চিত করে।</p>
</details>

<details>
  <summary><strong>4/ পুনরায় রেন্ডারিং কেন প্রয়োজন?</strong></summary>
  <p>উত্তর: পুনরায় রেন্ডারিং প্রয়োজন যখন কোন উপাদান বা কম্পোনেন্টের স্টেট বা প্রপস পরিবর্তিত হয়। এটি ব্যবহারকারীর পরিবর্তনগুলি UI তে প্রতিফলিত করতে সাহায্য করে।</p>
</details>

<details>
  <summary><strong>5/ Reconciliation-এর সময় কি DOM-এ পুরোপুরি পুনর্লিখন করা হয়?</strong></summary>
  <p>উত্তর: না, Reconciliation-এর সময় DOM সম্পূর্ণরূপে পুনর্লিখন করা হয় না। কেবলমাত্র পরিবর্তিত অংশগুলি আপডেট করা হয়।</p>
</details>

<details>
  <summary><strong>6/ Virtual DOM কিভাবে Reconciliation প্রক্রিয়া ত্বরান্বিত করে?</strong></summary>
  <p>উত্তর: Virtual DOM একটি মেমোরি-ভিত্তিক রিপ্রেজেন্টেশন যা মূল DOM-এ পরিবর্তন করার আগে সমস্ত পরিবর্তন যাচাই করতে সাহায্য করে। এটি পরিবর্তনগুলিকে একত্রিত করে এবং পরে একসাথে প্রয়োগ করে।</p>
</details>

<details>
  <summary><strong>7/ কিভাবে React কম্পোনেন্টের পারফরম্যান্স উন্নত করা যায়?</strong></summary>
  <p>উত্তর: React কম্পোনেন্টের পারফরম্যান্স উন্নত করতে React.memo, PureComponent, এবং shouldComponentUpdate() ব্যবহার করা যেতে পারে।</p>
</details>

<details>
  <summary><strong>8/ Functional কম্পোনেন্টে Reconciliation কীভাবে কাজ করে?</strong></summary>
  <p>উত্তর: Functional কম্পোনেন্টে Reconciliation সাধারণভাবে কাজ করে যেমন ক্লাস কম্পোনেন্টে। Virtual DOM এবং Key prop ব্যবহার করে শুধুমাত্র পরিবর্তিত অংশ আপডেট করা হয়।</p>
</details>

<details>
  <summary><strong>9/ Reconciliation প্রক্রিয়া কি সমানভাবে সকল ব্রাউজারে কাজ করে?</strong></summary>
  <p>উত্তর: হ্যাঁ, Reconciliation প্রক্রিয়া সকল আধুনিক ব্রাউজারে একীভূতভাবে কাজ করে, যেহেতু এটি JavaScript-এ ভিত্তি করে এবং ব্রাউজারের DOM API-র সাথে কাজ করে।</p>
</details>

<details>
  <summary><strong>10/ Reconciliation-এর সময় কোন ধরনের পদ্ধতি ব্যবহার করা হয়?</strong></summary>
  <p>উত্তর: Reconciliation-এর সময় React "diffing" পদ্ধতি ব্যবহার করে। এটি নতুন এবং পুরনো Virtual DOM-এর মধ্যে পার্থক্য চিহ্নিত করে এবং শুধুমাত্র প্রয়োজনীয় আপডেটগুলি করে।</p>
</details>
