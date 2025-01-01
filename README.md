# GO PROGRAMMING LANGUAGE

## গোল্যাং কি?
- __গোল্যাং বা গো হলো একটি ওপেন সোর্স প্রোগ্রামিং ল্যাঙ্গুয়েজ, যা গুগল ডেভেলপ করেছে। এটি দ্রুত, সহজ, এবং স্কেলেবল কোড লেখার জন্য ব্যবহার করা হয়।__
 
- __গোল্যাং-এর প্রধান বৈশিষ্ট্য:__
  - সহজ সিনট্যাক্স।
  - দ্রুত পারফরম্যান্স।
  - বিল্ট-ইন কনকারেন্সি (গরুটিন ব্যবহার করে)।
  - স্ট্যাটিক টাইপিং।
  - স্মৃতি ব্যবস্থাপনা সহজ (Garbage Collection)।<br><br><br>


## গোল্যাং (Go) প্রোগ্রামিং ল্যাঙ্গুয়েজের ইতিহাস
- গোল্যাং (Go) প্রোগ্রামিং ল্যাঙ্গুয়েজের ইতিহাস অত্যন্ত গুরুত্বপূর্ণ, কারণ এটি আধুনিক সফটওয়্যার ডেভেলপমেন্টের চাহিদা পূরণের লক্ষ্যে তৈরি করা হয়েছে। গোল্যাং-এর সৃষ্টি এবং এর বিবর্তনের পেছনের গল্পটি নিম্নরূপ:<br>
- __গোল্যাং-এর জন্ম: কীভাবে এবং কেন?__\
  উৎপত্তি: গোল্যাং-এর বিকাশ শুরু হয়েছিল ২০০৭ সালে গুগলের তিনজন প্রকৌশলী:রবার্ট গ্রিসেমার (Robert Griesemer), রব পাইক (Rob Pike), কেন থম্পসন (Ken Thompson)
  তারা লক্ষ্য করেছিলেন যে গুগলে ব্যবহৃত প্রোগ্রামিং ল্যাঙ্গুয়েজগুলো (যেমন C++, Java) বড় স্কেল অ্যাপ্লিকেশন তৈরির জন্য কার্যকর হলেও:
  - কম্পাইল টাইম দীর্ঘ।
  - জটিলতা বেশি।
  - কনকারেন্সি হ্যান্ডলিং দুর্বল।
  - কোড মেইনটেন করা কঠিন।
- __প্রধান উদ্দেশ্য:__
  তারা একটি নতুন ল্যাঙ্গুয়েজ তৈরি করতে চেয়েছিলেন যা:
  - দ্রুত হবে।
  - সহজ এবং সরাসরি।
  - কনকারেন্সি প্রোগ্রামিং সহজ করবে।
  - বড় স্কেল সিস্টেম তৈরির জন্য উপযোগী হবে।
- __উল্লেখযোগ্য সংস্করণ__
  - Go 1 (২০১২):
    প্রথম স্থিতিশীল সংস্করণ প্রকাশিত হয়। এটি এখন পর্যন্ত গোল্যাং-এর API এবং কোর ফিচারগুলোর ভিত্তি।
  - Go 1.5 (২০১৫):
    গারবেজ কালেক্টরের উন্নতি এবং পুরো ল্যাঙ্গুয়েজ সেলফ-হোস্টিং করা হয়েছিল (গোল্যাং নিজেই গোল্যাং ব্যবহার করে কম্পাইল হয়)।
  - Go 1.18 (২০২২):
    জেনেরিক (Generics) যোগ করা হয়, যা ডেভেলপারদের মধ্যে বহুল প্রতীক্ষিত একটি বৈশিষ্ট্য ছিল।


<br><br>
 ## গোল্যাং কেন বেছে নেওয়া উচিত?
 - এ প্রশ্নের উত্তর হলো, এটি অনেক সমস্যার জন্য একটি শক্তিশালী সমাধান, বিশেষত যখন আপনি দ্রুত, দক্ষ, এবং স্কেলেবল অ্যাপ্লিকেশন তৈরি করতে চান। নিচে গোল্যাং বেছে নেওয়ার প্রধান কারণগুলো তুলে ধরা হলো:
   - __উচ্চ পারফরম্যান্স__\
     গোল্যাং কম্পাইলড ল্যাঙ্গুয়েজ হওয়ায় এটি সরাসরি মেশিন কোডে অনুবাদ হয়, যা এর কর্মক্ষমতা অনেক দ্রুত করে তোলে। এটি সি এবং সি++ এর মতই দ্রুত কিন্তু তাদের চেয়ে বেশি সহজ।
     
   - __সহজ এবং পরিষ্কার সিনট্যাক্স__\
     গোল্যাং-এর সিনট্যাক্স খুবই সহজ এবং পড়তে সুবিধাজনক। নতুন প্রোগ্রামাররাও এটি সহজে শিখতে পারে। উদাহরণস্বরূপ, জাভা বা পাইথনের তুলনায় এটি কম কোডে কাজ সম্পন্ন করতে পারে।

   - __বিল্ট-ইন কনকারেন্সি__\
     গোল্যাং-এর গরুটিন (goroutines) এবং চ্যানেল (channels) ব্যবহারের মাধ্যমে সহজে কনকারেন্ট প্রোগ্রামিং করা যায়। আপনি অনেক কাজ একসাথে (multi-threading) করতে পারবেন, যা স্কেলেবল অ্যাপ্লিকেশন তৈরি করার জন্য অপরিহার্য।

   - __ক্রস-প্ল্যাটফর্ম সাপোর্ট__\
     একবার গোল্যাং কোড লিখলে আপনি সহজেই সেটিকে বিভিন্ন প্ল্যাটফর্মে (Windows, MacOS, Linux) রান করাতে পারেন। এটি ডকার (Docker) বা ক্লাউড-নেটিভ অ্যাপ্লিকেশনের জন্য আদর্শ।

   - __স্ট্যাটিক টাইপিং এবং সেফটি__\
     গোল্যাং একটি স্ট্যাটিক্যালি-টাইপড ল্যাঙ্গুয়েজ। ফলে কোড লেখা এবং রান করার সময় টাইপের সমস্যাগুলো কম হয়। এর ফলে কোড আরও সুরক্ষিত এবং নির্ভুল হয়।

   - __বিল্ট-ইন টুলস__\
     গোল্যাং ডেভেলপমেন্টের জন্য অনেক দরকারি টুলস বিল্ট-ইন দেয়:
     - go fmt: কোড ফরম্যাট করার জন্য।
     - go test: টেস্টিং সাপোর্ট।
     - go mod: ডিপেনডেন্সি ম্যানেজমেন্ট।
     - go build: কম্পাইল করার জন্য।

   - __বড় কোম্পানিগুলোর ব্যবহার__\
     গোল্যাং-এর স্কেলেবিলিটি এবং পারফরম্যান্সের জন্য বড় কোম্পানিগুলো এটি ব্যবহার করে। যেমন:
     - __Google:__ তাদের নিজস্ব ক্লাউড সার্ভিসে।
     - __Uber:__ রিয়েল-টাইম সার্ভিসের জন্য।
     - __Docker:__ কন্টেইনারাইজেশনের জন্য।
     - __Kubernetes:__ ক্লাস্টার ম্যানেজমেন্টে।
    
   - __ক্লাউড-নেটিভ এবং মাইক্রোসার্ভিস সমর্থ__\
     গোল্যাং মাইক্রোসার্ভিস এবং ক্লাউড-নেটিভ অ্যাপ্লিকেশনের জন্য চমৎকার। এটি ডকার এবং কুবারনেটিসের মত টুলের জন্য প্রধান ল্যাঙ্গুয়েজ।

   - __কমিউনিটি এবং সাপোর্ট__\
     গোল্যাং-এর একটি বিশাল এবং সক্রিয় কমিউনিটি আছে। ফলে আপনি সহজেই টিউটোরিয়াল, ফোরাম, এবং ডকুমেন্টেশন খুঁজে পাবেন।

   - __ভবিষ্যত-প্রস্তুত ল্যাঙ্গুয়েজ__\
    গোল্যাং ভবিষ্যতের অ্যাপ্লিকেশন, বিশেষত ডিস্ট্রিবিউটেড সিস্টেম এবং ক্লাউড বেসড সলিউশনগুলোর জন্য ডিজাইন করা হয়েছে। এটি একটি সময়োপযোগী ও টেকসই প্রযুক্তি।


<br><br>
## গোল্যাং সেটআপ এবং প্রথম প্রোগ্রাম
গোল্যাং শেখা শুরু করার আগে, এটি আপনার কম্পিউটারে ইনস্টল করা দরকার।

__গোল্যাং ডাউনলোড ও ইনস্টল__
- গোল্যাং অফিসিয়াল ওয়েবসাইট থেকে আপনার অপারেটিং সিস্টেম অনুযায়ী গল্যাং ডাউনলোড করুন।
- ডাউনলোড শেষ হলে সেটআপ ফাইল রান করুন এবং নির্দেশনা অনুযায়ী ইনস্টল করুন।
- ইনস্টলেশন শেষ হলে টার্মিনালে গিয়ে go version লিখে ইনস্টলেশন ঠিক আছে কিনা যাচাই করুন।
  <br><br>
  ~~~
  go version
  ~~~
  আপনার গোল্যাং সংস্করণ দেখালে ইনস্টলেশন সফল হয়েছে।

__প্রথম প্রোগ্রাম: "Hello, World!"__
- একটি প্রোজেক্ট তৈরি করুন "myproject"
- একটি ফাইল তৈরি করুন hello.go নামে।
-  প্রোজেক্টের জন্য mod তৈরি করুন
   ~~~
   go mod init myproject
   ~~~

- নিচের কোডটি লিখুন:
  ~~~
  package main

  import "fmt"

  func main() {
     fmt.Println("Hello, World!")
  }
  ~~~
- টার্মিনালে নিচের কমান্ড দিন:
  ~~~
  go run hello.go
  ~~~
- আপনার স্ক্রিনে Hello, World! দেখাবে।

<br><br><br>
## গোল্যাং- fmt প্যাকেজ প্রিন্টিং এবং ফরম্যাটিং
গোল্যাং-এ fmt প্যাকেজটি প্রিন্টিং এবং ফরম্যাটিং-এর জন্য সবচেয়ে বেশি ব্যবহৃত হয়। এটি টার্মিনালে আউটপুট দেখানোর জন্য বিভিন্ন ফাংশন প্রদান করে।

__fmt এর প্রধান ফাংশনগুলো__
- ### fmt.Println
  - এটি নতুন লাইনে (newline) শেষ করে প্রিন্ট করে।
  - একাধিক মান স্পেস দিয়ে পৃথক করে প্রিন্ট হয়।
    
    ~~~
    package main

    import "fmt"
  
    func main() {
       fmt.Println("Hello, World!")
       fmt.Println("Number:", 42, "Boolean:", true)
    }
    ~~~
    __আউটপুট:__
    ~~~
    Hello, World!
    Number: 42 Boolean: true
    ~~~
- ### fmt.Print
  - এটি লাইন শেষে কোনো নতুন লাইন যোগ করে না।
  - মানগুলো স্পেস দিয়ে পৃথক করে প্রিন্ট হয় না।
    
    ~~~
     package main

     import "fmt"

     func main() {
       fmt.Print("Hello, ")
       fmt.Print("World!")
     }
    ~~~
    __আউটপুট:__
    ~~~
    Hello, World!
    ~~~
- ### fmt.Printf (Formatted Print)
  - এটি ফরম্যাট করা আউটপুট দেখানোর জন্য ব্যবহৃত হয়।
  - ফরম্যাট স্পেসিফায়ার ব্যবহার করে আউটপুট কাস্টমাইজ করা যায়।

    ~~~
    package main

    import "fmt"

    func main() {
      name := "Alice"
      age := 25
      height := 5.6
    
      fmt.Printf("Name: %s, Age: %d, Height: %.1f\n", name, age, height)
    }
    ~~~
    __আউটপুট:__
    ~~~
    Name: Alice, Age: 25, Height: 5.6
    ~~~
  - __ফরম্যাট স্পেসিফায়ার__
    - %d: পূর্ণসংখ্যা (Integer)
    - %f: দশমিক সংখ্যা (Float)
    - %.nf: দশমিকের পরে নির্দিষ্ট সংখ্যক ডিজিট প্রিন্ট করার জন্য (যেমন: %.2f).
    - %s: স্ট্রিং (String)
    - %t: বুলিয়ান (Boolean)
    - %v: ডিফল্ট ফরম্যাটে যেকোনো ডেটা টাইপ।
    - %T: ডেটা টাইপ প্রিন্ট করে।

    ~~~
    package main

    import "fmt"

    func main() {
       fmt.Printf("Integer: %d\n", 10)
       fmt.Printf("Float: %.2f\n", 3.14159)
       fmt.Printf("String: %s\n", "Golang")
       fmt.Printf("Boolean: %t\n", true)
       fmt.Printf("Default Format: %v\n", 42)
       fmt.Printf("Type: %T\n", 42)
    }
    ~~~
    __আউটপুট:__
    ~~~
    Integer: 10
    Float: 3.14
    String: Golang
    Boolean: true
    Default Format: 42
    Type: int
    ~~~
 - ### fmt.Errorf (Error Formatting)
    - এটি ফরম্যাট করা স্ট্রিং রিটার্ন করে এবং error টাইপে রূপান্তর করে।
     
      ~~~
      package main

      import (
        "fmt"
      )

      func main() {
        err := fmt.Errorf("an error occurred: %s", "file not found")
        fmt.Println(err)
      }
      ~~~
      __আউটপুট:__
      ~~~
      an error occurred: file not found
      ~~~

 - ### fmt.Sprintf (Formatted String)
    - এটি ফরম্যাট করা স্ট্রিং রিটার্ন করে (প্রিন্ট করে না)।
     
      ~~~
      package main

      import "fmt"
      
      func main() {
       	point := 1.23434
       	num := fmt.Sprintf("%.2f", point)
	       fmt.Println(num)
      }
      ~~~

      __আউটপুট:__
      ~~~
      1.23
      ~~~

## কীওয়ার্ডস (keywords), সিনট্যাক্স (syntax), এবং কমেন্টস (comments)
- ### কীওয়ার্ড (Keywords)
  গোল্যাং-এ মোট ২৫টি রিজার্ভড কীওয়ার্ড আছে, যেগুলি বিশেষ অর্থ বহন করে এবং ভেরিয়েবল বা ফাংশনের নামে ব্যবহার করা যায় না।\
  __গোল্যাং-এর রিজার্ভড কীওয়ার্ড তালিকা:__

  |            |               |          |             |          |
  |------------|---------------|----------|-------------|----------|
  | case       | defer         | go       | map         | struct   |
  | chan       | else          | goto     | package     | switch   |
  | const      | fallthrough   | if       | range       | type     |
  | continue   | for           | import   | return      | var      |

- ### সিনট্যাক্স (Syntax)
  গোল্যাং-এ কোড লেখার কিছু সাধারণ নিয়ম রয়েছে।
  
  __প্রাথমিক কোড কাঠামো:__
  
  ~~~
  package main

  import "fmt"

  func main() {
    fmt.Println("Hello, World!")
  }
  ~~~
  __বিবরণ:__
  - package main:\
	প্রতিটি প্রোগ্রামের একটি প্যাকেজ থাকে। main প্যাকেজ প্রোগ্রামের এন্ট্রি পয়েন্ট নির্দেশ করে।
  - import "fmt":\
	প্রয়োজনীয় প্যাকেজ ইমপোর্ট করতে ব্যবহার হয়। fmt প্যাকেজ প্রিন্টিং এবং ফরম্যাটিং-এর জন্য ব্যবহৃত হয়।
  - func main():\
	প্রোগ্রামের এক্সিকিউশন এই ফাংশন থেকে শুরু হয়।
  - fmt.Println():\
	এটি আউটপুট প্রদর্শনের জন্য ব্যবহৃত হয়।

  __ভেরিয়েবল ডিক্লেয়ারেশন:__
  
  ~~~
  var name string = "Golang"
  age := 10
  ~~~

  __লুপ:__
  
  ~~~
  for i := 0; i < 5; i++ {
    fmt.Println(i)
  }
  ~~~

  __কন্ডিশনাল স্টেটমেন্ট:__
  
  ~~~
  if age > 18 {
     fmt.Println("Adult")
  } else {
    fmt.Println("Not an adult")
  }
  ~~~

  __সুইচ স্টেটমেন্ট:__
  
  ~~~
  switch day {
   case "Monday":
      fmt.Println("Start of the week")
   case "Friday":
      fmt.Println("End of the work week")
   default:
      fmt.Println("Midweek")
  }
  ~~~

  __ফাংশন ডিক্লেয়ারেশন:__
  
  ~~~
  func add(a int, b int) int {
      return a + b
  }
  ~~~
- ### কমেন্টস (Comments)
  গোল্যাং-এ কোডে মন্তব্য যোগ করার জন্য দুটি ধরণ রয়েছে:<br><br>
  __সিঙ্গেল লাইন কমেন্ট__\
  সিঙ্গেল লাইন কমেন্ট যোগ করতে // ব্যবহার করা হয়।
  ~~~
  // This is a single line comment
  fmt.Println("Hello, World!")
  ~~~

  __মাল্টি-লাইন কমেন্ট:__\
  মাল্টি-লাইন কমেন্ট যোগ করতে /* ... */ ব্যবহার করা হয়।
 
  ~~~
  /*
  This is a multi-line comment.
  It can span multiple lines.
  */
  fmt.Println("Hello, World!")
  ~~~
  
## গোল্যাং-এ ভেরিয়েবল (Variable)
 গোল্যাং-এ ভেরিয়েবল (Variable) একটি স্টোরেজ ইউনিট যা কোনো ডেটা বা মান ধরে রাখে। এটি প্রোগ্রামের ভেতরে বিভিন্ন ডেটা পরিচালনা করতে ব্যবহৃত হয়। এখানে গোল্যাং-এ ভেরিয়েবল ব্যবহারের নিয়ম এবং উদাহরণগুলো দেওয়া 
হলো:\
গোল্যাং-এ ভেরিয়েবল ঘোষণা করার তিনটি প্রধান উপায় রয়েছে:

- __১. var কিওয়ার্ড দিয়ে ডিক্লেয়ার করা__\
  গোল্যাং-এ var কিওয়ার্ড ব্যবহার করে ভেরিয়েবল ডিক্লেয়ার করা হয়। আপনি চাইলে টাইপ নির্ধারণ করতে পারেন বা গোল্যাং-কে ইনফারেন্স করতে দিতে পারেন।

  ~~~
  package main

  import "fmt"

  func main() {
      var name string = "Golang" // টাইপ নির্ধারণ করে ডিক্লেয়ারেশন
      var age = 10              // টাইপ ইনফারেন্স
      var isCool bool           // ডিফল্ট ভ্যালু (false)

      fmt.Println(name, age, isCool)
  }
  ~~~
- __২. শর্টহ্যান্ড (:=) ব্যবহার করে ডিক্লেয়ার করা__\
  শুধুমাত্র ফাংশনের ভেতরে ব্যবহার করা যায়। টাইপ ইনফারেন্স স্বয়ংক্রিয়ভাবে ঘটে।

  ~~~
  package main

  import "fmt"

  func main() {
      name := "Golang"
      age := 10
      isCool := true

      fmt.Println(name, age, isCool)
  }
  ~~~
- __৩. মাল্টিপল ভেরিয়েবল ডিক্লেয়ারেশন__\
  একই সাথে একাধিক ভেরিয়েবল ডিক্লেয়ার করা যায়।
  
  ~~~
  package main

  import "fmt"

  func main() {
      var x, y, z int = 1, 2, 3 // একই টাইপের ভেরিয়েবল
      a, b := "Hello", true     // শর্টহ্যান্ডে বিভিন্ন টাইপ

      fmt.Println(x, y, z)
      fmt.Println(a, b)
  }
  ~~~

<br><br>  
### ডেটা টাইপস
গোল্যাং-এ ভেরিয়েবল বিভিন্ন ডেটা টাইপ ধারণ করতে পারে। সাধারণ ডেটা টাইপগুলো নিচে দেওয়া হলো:
    
   - __প্রিমিটিভ ডেটা টাইপস__

     |    টাইপ       |      বর্ণনা       |   উদাহরণ    |
     |---------------|------------------|--------------|
     | string     | টেক্সট ডেটা	     | "Hello"         | 
     | int        | পূর্ণসংখ্যা             | 42           |
     | float32    | ভাসমান বিন্দু সংখ্য     | 3.14         |
     | bool       | বুলিয়ান (সত্য/মিথ্যা)   | true, false  |
     | byte       | ৮-বিট সংখ্যা	     | 'a' (ASCII)     | 


### গোল্যাং-এ পাবলিক এবং প্রাইভেট ভেরিয়েবলের নিয়ম:
  - __বড় হাতের অক্ষর দিয়ে শুরু হওয়া ভেরিয়েবল:__
      - এগুলি পাবলিক (Public) হয়।
      - এগুলি প্যাকেজের বাইরে থেকেও অ্যাক্সেস করা যায়।
        
  - __ছোট হাতের অক্ষর দিয়ে শুরু হওয়া ভেরিয়েবল:__
      - এগুলি প্রাইভেট (Private) হয়।
      - এগুলি প্যাকেজের বাইরে থেকে অ্যাক্সেসযোগ্য নয়, শুধুমাত্র একই প্যাকেজের ভেতরে ব্যবহৃত হয়।
      - 
    __public vaiable__
    ~~~
    package main

    import (
        "fmt"
        "mypackage"
    )

    func main() {
        // প্যাকেজের পাবলিক ভেরিয়েবল অ্যাক্সেস
        fmt.Println("Public Variable:", mypackage.PublicVar)
    }
    ~~~

    ~~~
    // mypackage/mypackage.go
    package mypackage

    // Public Variable (বড় হাতের অক্ষর দিয়ে শুরু হওয়ায় এটি পাবলিক)
    var PublicVar = "I am Public"
    ~~~

    __Private Variable__
    ~~~
    package main

    import (
        "fmt"
        "mypackage"
    )

    func main() {
        // প্যাকেজের প্রাইভেট ভেরিয়েবল অ্যাক্সেস করার চেষ্টা
        // fmt.Println("Private Variable:", mypackage.privateVar) // কম্পাইল টাইম এরর
        fmt.Println("Use Public Function:", mypackage.GetPrivateVar())
    }
    ~~~

    ~~~
    // mypackage/mypackage.go
    package mypackage

    // Private Variable (ছোট হাতের অক্ষর দিয়ে শুরু হওয়ায় এটি প্রাইভেট)
    var privateVar = "I am Private"

    // Function to access the private variable
    func GetPrivateVar() string {
        return privateVar
    }
    ~~~
 <br>
    
### গোল্যাং-এ ভেরিয়েবল লেখার নিয়ম:
  - __নাম শুরু করতে হবে একটি অক্ষর বা _ (আন্ডারস্কোর) দিয়ে।__
      - সংখ্যা দিয়ে ভেরিয়েবলের নাম শুরু করা যাবে না।
      - বৈধ: name, _id, age2
      - অবৈধ: 2name, -temp
  - __নাম শুধুমাত্র অক্ষর, সংখ্যা এবং _ থাকতে পারে।__
      - বৈধ: userName, data_2023
      - অবৈধ: user-name, data#id
  - __গোল্যাং-এ কেস সেনসিটিভ।__
      - Name এবং name আলাদা ভেরিয়েবল হিসেবে বিবেচিত হবে।
  - __কিওয়ার্ড বা রিজার্ভড শব্দ ভেরিয়েবলের নাম হিসেবে ব্যবহার করা যাবে না।__
      - অবৈধ: var, func, if (কারণ এগুলি কীওয়ার্ড)
 - __ভেরিয়েবলের নাম সংক্ষিপ্ত কিন্তু অর্থপূর্ণ হওয়া উচিত।__
      - ভালো: counter, userName
      - খারাপ: c, x
 <br>
 
### কনভেনশন (Conventions)

গোল্যাং-এ কোডিং কনভেনশন অনুযায়ী ভেরিয়েবল লেখার কিছু ভালো প্রথা রয়েছে:

 - __ক্যামেল কেস (Camel Case):__
     - লোকাল ভেরিয়েবল এবং ফাংশনের জন্য ক্যামেল কেস ব্যবহার করা হয়।
     - উদাহরণ: userName, maxValue, isActive
 - __বড় হাতের অক্ষর (Pascal Case):__
     - প্যাকেজের বাইরে অ্যাক্সেসযোগ্য ভেরিয়েবল বা ফাংশনের জন্য বড় হাতের প্রথম অক্ষর ব্যবহার করা হয়।
     - উদাহরণ: UserName, MaxValue, IsActive
 - __সংক্ষিপ্ত নাম ব্যবহার করা:__
     - ছোট ভেরিয়েবল নাম ব্যবহার করা হয়, বিশেষত লুপ বা অস্থায়ী মানের জন্য।
     - উদাহরণ: i, j, temp
 - __দিয়ে অব্যবহৃত ভেরিয়েবল নির্দেশ করা:__
     - _ ব্যবহার করে এমন ভেরিয়েবল নির্দেশ করা যায় যা পরবর্তীতে ব্যবহার করা হবে না।
     - উদাহরণ:
        ~~~
        result, _ := someFunction() // দ্বিতীয় মানটি অগ্রাহ্য করা হয়েছে
        ~~~
       
## গোল্যাং-এ সকল টাইপ কাস্টিং
  ~~~
  package main

  import (
      "fmt"
      "strconv"
  )

  func main() {
      // Integer to Float
      var intVal int = 42
      var floatVal float64 = float64(intVal)
      fmt.Println("Integer to Float:", floatVal)

      // Float to Integer
      var newIntVal int = int(floatVal)
      fmt.Println("Float to Integer:", newIntVal)

      // Integer to String
      var strVal string = strconv.Itoa(intVal)
      fmt.Println("Integer to String:", strVal)

      // String to Integer
      strToInt, _ := strconv.Atoi(strVal)
      fmt.Println("String to Integer:", strToInt)

      // String to Float
      strToFloat, _ := strconv.ParseFloat("42.56", 64)
      fmt.Println("String to Float:", strToFloat)

      // Float to String
      strFloat := strconv.FormatFloat(floatVal, 'f', 2, 64)
      fmt.Println("Float to String:", strFloat)

      // String to Byte Slice
      byteVal := []byte(strVal)
      fmt.Println("String to Byte Slice:", byteVal)

      // Byte Slice to String
      newStrVal := string(byteVal)
      fmt.Println("Byte Slice to String:", newStrVal)

      // Rune to String
      var runeVal rune = 'A'
      strRune := string(runeVal)
      fmt.Println("Rune to String:", strRune)

      // String to Rune
      newRuneVal := []rune(strRune)[0]
      fmt.Println("String to Rune:", newRuneVal)

      // Signed to Unsigned
      var signedVal int = -10
      var unsignedVal uint = uint(signedVal)
      fmt.Println("Signed to Unsigned:", unsignedVal)

      // Unsigned to Signed
      var newSignedVal int = int(unsignedVal)
      fmt.Println("Unsigned to Signed:", newSignedVal)
  }
  ~~~
## গোল্যাং-এ অপারেটর
   - __Arithmetic Operators__

     |    Operator       |      Description       |   Example    |
     |---------------|------------------|--------------|
     | +	| Addition	| a + b |
     | -	| Subtraction	| a - b |
     | *	| Multiplication | 	a * b| 
     | /	| Division	| a / b |
     | %	| Modulus (Remainder)	| a % b  |

   - __Relational (Comparison) Operators__

     |    Operator       |      Description       |   Example    |
     |---------------|------------------|--------------|
     | ==	| Equal to	| a == b |
     | !=	| Not equal to	| a != b |
     | >	| Greater than	 | a > b |
     | <	| Less than	| a < b |
     | >=	| Greater than or equal to | a >= b| 
     | <=    |  Less than or equal to | a <= b | 


   - __Logical Operators__

     |    Operator       |      Description       |   Example    |
     |---------------|------------------|--------------|
     | &&	| Logical AND	| (a > b) && (b < c) |
     | !	| Logical NOT	| !(a > b) |


## Array (স্থির দৈর্ঘ্যের তালিকা)
  - একটি নির্দিষ্ট দৈর্ঘ্যের ডেটা স্ট্রাকচার।
  - সবগুলো উপাদান একই টাইপের হয়।
  - একবার তৈরি হলে এর দৈর্ঘ্য পরিবর্তন করা যায় না।
  ~~~
  package main

  import "fmt"

  func main() {
      var arr [5]int // একটি ৫ উপাদানের array তৈরি
      arr[0] = 10
      arr[1] = 20
      arr[2] = 30

      fmt.Println("Array:", arr)
      fmt.Println("Length:", len(arr))    // দৈর্ঘ্য
      fmt.Println("Element at index 1:", arr[1])
  }
  ~~~

## Slice (পরিবর্তনযোগ্য দৈর্ঘ্যের তালিকা)
   - ডাইনামিক ডেটা স্ট্রাকচার (দৈর্ঘ্য পরিবর্তনযোগ্য)।
   - একটি array-এর উপর ভিত্তি করে কাজ করে।
   - খুবই ফ্লেক্সিবল এবং সাধারণত list-এর জন্য slice ব্যবহৃত হয়।
    
   ~~~
   package main

   import "fmt"

   func main() {
       // Slice তৈরি
       slice := []int{10, 20, 30}

       // Slice-এর দৈর্ঘ্য ও ক্যাপাসিটি
       fmt.Println("Slice:", slice)
       fmt.Println("Length:", len(slice))     // দৈর্ঘ্য
       fmt.Println("Capacity:", cap(slice))   // ক্যাপাসিটি

       // নতুন উপাদান যোগ করা
       slice = append(slice, 40, 50)
       fmt.Println("After Append:", slice)

       // সাব-স্লাইস তৈরি
       subSlice := slice[1:4]
       fmt.Println("Sub-slice:", subSlice)
   }
   ~~~
 - __Common Operations on Slices__
     
   | Operation | Example |
   |-----------|---------|
   |Create Slice	| slice := []int{1, 2, 3} |
   | Length	| len(slice) |
   | Capacity	| cap(slice) |
   | Append Element(s)	| slice = append(slice, 4, 5) | 
   | Copy Slice	| copy(newSlice, slice) |
   | Sub-slice	| subSlice := slice[1:3] |
   | Iterate with Range | 	for i, v := range slice { fmt.Println(v) } |



## গোল্যাং-এ if-else
   গোল্যাং-এ if-else স্টেটমেন্ট ব্যবহার করে শর্ত ভিত্তিক কোড এক্সিকিউশন করা যায়। এখানে এর বিস্তারিত আলোচনা এবং উদাহরণ দেওয়া হলো:

   - __if-else স্টেটমেন্ট__
    
     ~~~
     package main

     import "fmt"

     func main() {
        num := 3
        if num%2 == 0 {
          fmt.Println("Number is even")
        } else {
        fmt.Println("Number is odd")
        }
     }
     ~~~

   - __if-else else if স্টেটমেন্ট__
    
     ~~~
      package main

      import "fmt"

      func main() {
        score := 85

        if score >= 90 {
            fmt.Println("Grade: A")
        } else if score >= 75 {
            fmt.Println("Grade: B")
        } else if score >= 50 {
            fmt.Println("Grade: C")
        } else {
            fmt.Println("Grade: F")
        }
      }

     ~~~


   - __Nested if-else স্টেটমেন্ট__
    
     ~~~
     package main

     import "fmt"

     func main() {
        num := 15

        if num > 10 {
            if num%3 == 0 {
                fmt.Println("Number is greater than 10 and divisible by 3")
            } else {
            fmt.Println("Number is greater than 10 but not divisible by 3")
            }
       } else {
          fmt.Println("Number is 10 or less")
       }
     }
     ~~~


## গোল্যাং-এ switch স্টেটমেন্ট
   গোল্যাং-এ switch স্টেটমেন্ট একটি শক্তিশালী কন্ট্রোল স্ট্রাকচার যা একাধিক শর্ত যাচাই করতে ব্যবহৃত হয়। এটি if-else if-else এর সহজ ও পরিষ্কার বিকল্প।

   - ডিফল্ট break: প্রতিটি case ব্লক শেষে স্বয়ংক্রিয়ভাবে break থাকে, যা অন্য ভাষার switch এর মতো আচরণ করে।
   - fallthrough: এটি ব্যবহার করলে একটি case ব্লকের পরবর্তী case ও এক্সিকিউট হয়।
   - মাল্টিপল case: একাধিক মানের জন্য একটি case ব্যবহার করা যায়।
   - টাইপ সুইচ: ইন্টারফেসের মধ্যে টাইপ চেক করতে type ব্যবহার করা হয়।
   - ডিফল্ট: কোনো case মেলে না এমন অবস্থায় default ব্লক এক্সিকিউট হয়।
    
  ~~~
  package main

  import "fmt"
 
  func main() {
      day := "Monday"

      switch day {
      case "Monday":
          fmt.Println("Start of the work week")
      case "Friday":
          fmt.Println("Last working day")
      default:
          fmt.Println("It's a regular day")
      }
  }
  ~~~

  ~~~
  package main

  import "fmt"

  func main() {
      num := 15

      switch {
      case num < 10:
          fmt.Println("Number is less than 10")
      case num >= 10 && num <= 20:
          fmt.Println("Number is between 10 and 20")
      default:
          fmt.Println("Number is greater than 20")
      }
  }
  ~~~


## গোল্যাং-এ for loop
   গোল্যাং-এ for loop হল একমাত্র লুপ স্ট্রাকচার, যা সাধারণ for, while, এবং do-while লুপের বিকল্প হিসেবে কাজ করে। এখানে for loop এর বিস্তারিত আলোচনা এবং উদাহরণ দেওয়া হলো:

   - ইনফিনিট লুপ: for {} ব্যবহার করে ইনফিনিট লুপ তৈরি করা যায়।
   - break: লুপ থেকে বের হতে break ব্যবহার করা হয়।
   - continue: পরবর্তী ইটারেশনে যেতে continue ব্যবহার করা হয়।
   - range: range ব্যবহার করে slice, map, বা string এর উপাদানগুলোর উপর সহজে ইটারেট করা যায়।
   - নেস্টেড লুপ: নেস্টেড লুপ ব্যবহার করে জটিল লজিক প্রয়োগ করা যায়।
   
   __সাধারণ for লুপ__
   
   ~~~
   package main

   import "fmt"

   func main() {
       for i := 0; i < 5; i++ {
           fmt.Println("Value of i:", i)
       }
   }
   ~~~

   __লুপ কাউন্টার ছাড়া (While Loop স্টাইল)__
   
   ~~~
   package main

   import "fmt"

   func main() {
       count := 0
       for count < 5 {
           fmt.Println("Count:", count)
           count++
       }
   }
   ~~~

   ### for লুপ এবং range ব্যবহার

   __Array/Slice এর জন্য:__
   
   ~~~
   package main

   import "fmt"

   func main() {
       nums := []int{10, 20, 30, 40, 50}
       for i, v := range nums {
           fmt.Printf("Index: %d, Value: %d\n", i, v)
       }
   }
   ~~~  


   __Map এর জন্য:__
   
   ~~~
   package main

   import "fmt"

   func main() {
       myMap := map[string]int{"Alice": 25, "Bob": 30}
       for key, value := range myMap {
           fmt.Printf("Key: %s, Value: %d\n", key, value)
       }
   }
   ~~~  


## গোল্যাং-এ map 
   
   গোল্যাং-এ map হল একটি ডেটা স্ট্রাকচার যা key-value জোড়ার মাধ্যমে ডেটা সংরক্ষণ করে। এটি সাধারণত দ্রুত অনুসন্ধান এবং মান ব্যবহারের জন্য ব্যবহৃত হয়।

   - Key-এর ধরন: Map-এর key কোনো comparable type হতে হবে, যেমন string, int, ইত্যাদি। তবে, slice, map, বা function key হতে পারে না।
   - মানের ধরন: Map-এর value যেকোনো টাইপ হতে পারে।
   - Default value: যদি কোনো key না থাকে, তবে তার value ডিফল্ট (zero value) হবে।
   - Concurrency: Map একাধিক গোরুটিন থেকে সুরক্ষিত নয়। কনকারেন্ট অ্যাক্সেসের জন্য sync.Map ব্যবহার করুন।
    
  - __ডিরেক্ট ইনিশিয়ালাইজেশন__

   ~~~
   package main

   import "fmt"

   func main() {
       myMap := map[string]int{
           "Alice": 25,
           "Bob":   30,
       }
       fmt.Println("Initialized map:", myMap)
   }
   ~~~ 

  - __মান যোগ করা__

   ~~~
   package main

   import "fmt"

   func main() {
       myMap := make(map[string]int)
       myMap["Alice"] = 25
       myMap["Bob"] = 30

       fmt.Println("After adding values:", myMap)
   }
   ~~~ 

   
  - __মান আপডেট করা__

   ~~~
   package main

   import "fmt"

   func main() {
       myMap := map[string]int{"Alice": 25}
       myMap["Alice"] = 26 // Update value
       fmt.Println("Updated map:", myMap)
   }
   ~~~ 

  - __Map থেকে মান পড়া__

   ~~~
   package main

   import "fmt"

   func main() {
       myMap := map[string]int{"Alice": 25, "Bob": 30}
       age := myMap["Alice"] // Key এর value পড়া
       fmt.Println("Alice's age:", age)
   }
   ~~~ 

  - __Map থেকে মান মুছে ফেলা__

   ~~~
   package main

   import "fmt"

   func main() {
       myMap := map[string]int{"Alice": 25, "Bob": 30}
       delete(myMap, "Bob") // "Bob" key মুছে ফেলা
       fmt.Println("After deletion:", myMap)
   }
   ~~~ 


  - __Nested Map__

   ~~~
   package main

   import "fmt"

   func main() {
       nestedMap := map[string]map[string]int{
           "Alice": {"Math": 90, "Science": 85},
           "Bob":   {"Math": 80, "Science": 88},
       }

       fmt.Println("Alice's Math score:", nestedMap["Alice"]["Math"])
   }
   ~~~

## গোল্যাং-এ struct
   গোল্যাং-এ struct হল একটি ইউজার-ডিফাইন্ড ডেটা টাইপ যা এক বা একাধিক ফিল্ড (প্রপার্টি) ধারণ করে। এটি জটিল ডেটা মডেল তৈরি করতে সহায়ক। struct ব্যবহার করে একটি অবজেক্ট বা রেকর্ড তৈরি করা যায়, যেখানে 
   বিভিন্ন টাইপের ডেটা রাখা সম্ভব।

   - Struct ডিফল্ট মান: Struct এর প্রতিটি ফিল্ডের ডিফল্ট মান zero value হয়।
   - মেথড: Struct-এ মেথড যুক্ত করে অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং-এর মতো আচরণ তৈরি করা যায়।
   - পয়েন্টার: Struct-এর পয়েন্টার ব্যবহার করে ডেটা সরাসরি মডিফাই করা যায়।
   - Nested Struct: Struct-এর মধ্যে আরেকটি Struct ব্যবহার করে জটিল ডেটা মডেল তৈরি করা যায়।

  ~~~
  package main

  import "fmt"

  // Struct ডিফাইন করা
  type Person struct {
      Name string
      Age  int
  }

  func main() {
      // Struct এর একটি অবজেক্ট তৈরি
      person1 := Person{Name: "Alice", Age: 25}
      fmt.Println("Person:", person1)
      fmt.Println("Name:", person1.Name)
      fmt.Println("Age:", person1.Age)
  }
  ~~~

   - __Nested Struct__

   ~~~
   package main

   import "fmt"

   type Address struct {
       City    string
       ZipCode int
   }

   type Person struct {
       Name    string
       Age     int
       Address Address
   }

   func main() {
       person := Person{
           Name: "David",
           Age:  35,
           Address: Address{
               City:    "New York",
               ZipCode: 10001,
           },
       }

       fmt.Println("Person:", person)
       fmt.Println("City:", person.Address.City)
   }
   ~~~

## গোল্যাং-এ পয়েন্টার (Pointers)
   গোল্যাং-এ পয়েন্টার (Pointers) হল একটি ভেরিয়েবলের মেমোরি অ্যাড্রেস। পয়েন্টার ব্যবহার করে আমরা ভেরিয়েবলের মান সরাসরি মেমোরি থেকে পড়তে এবং পরিবর্তন করতে পারি। এটি মেমোরি ম্যানেজমেন্ট এবং ডেটা হ্যান্ডলিং আরও কার্যকর করে তোলে।\
   
   __পয়েন্টার ডিক্লারেশন ও ব্যবহারের মূল কাঠামো__
   - \* : পয়েন্টার ডিক্লারেশন এবং ডেরেফারেন্সিং-এর জন্য ব্যবহৃত হয়।
   - & : কোনো ভেরিয়েবলের মেমোরি অ্যাড্রেস পাওয়ার জন্য ব্যবহৃত হয়।
   - Nil Pointer: পয়েন্টার ব্যবহারের আগে এটি nil কিনা তা পরীক্ষা করা উচিত।
   - Garbage Collection: গোল্যাং স্বয়ংক্রিয়ভাবে মেমোরি পরিচালনা করে, তাই পয়েন্টার ফ্রি করার দরকার হয় না।
   - Unsafe Operations: পয়েন্টার ব্যবহারে সাবধান থাকতে হবে, কারণ এটি ভুল ব্যবহার করলে প্রোগ্রাম ক্র্যাশ করতে পারে।

  ~~~
  package main

  /// pointers stors memory address

  import "fmt"

  func main() {

	num := 23
	var pointers *int = &num
	fmt.Println(pointers)

	name := "nahid"
	pit := &name
	fmt.Println(pit)

	var pnt *int // deafult value of pointers nil
	fmt.Println(pnt)

	///modifyValueByRefarence
	value := 10
	modifyValueByRefarence(&value) //func
	fmt.Println(value)
  }

  func modifyValueByRefarence(value *int) {
	*value = *value + 20
  }
  ~~~

## গোল্যাং-এ string 
   গোল্যাং-এ string হল একটি ইমিউটেবল সিকোয়েন্স যা ইউনিকোড ক্যারেক্টার সংরক্ষণ করে। এটি টেক্সট ম্যানিপুলেশনের জন্য ব্যবহার করা হয়। স্ট্রিং ব্যবহার করার জন্য গোল্যাং অনেক বিল্ট-ইন ফাংশন এবং প্যাকেজ সরবরাহ করে, যেমন strings এবং strconv।
   
   - ইমিউটেবল স্ট্রিং: একবার স্ট্রিং তৈরি হলে তা পরিবর্তন করা যায় না।
   - ইন্টারনাল বাইটস: স্ট্রিংয়ের দৈর্ঘ্য বাইটের ওপর ভিত্তি করে নির্ধারিত হয়, না যে ক্যারেক্টারের সংখ্যা।
   - বিল্ট-ইন লাইব্রেরি: স্ট্রিং ম্যানিপুলেশনের জন্য strings এবং strconv খুবই উপযোগী।
     
  ~~~
  package main

  import (
	"fmt"
	"strings"
  )

  func main() {

	//শূন্য স্ট্রিং
	var emptyString string
	fmt.Println("Empty String:", emptyString)

	//ক্যারেক্টার অ্যাক্সেস
	str := "Hello"
	fmt.Println("First Character:", string(str[0]))
	fmt.Println("Second Character:", string(str[1]))

	//স্ট্রিং স্লিট
	name := "nahid nafiz"
	namelist := strings.Split(name, " ")
	fmt.Println(namelist[0])
	fmt.Println(namelist)

	//start end space remove
	data := "   nahid hossen  "
	trimmed := strings.TrimSpace(data)
	fmt.Println(trimmed)

	//string join
	st1 := "nahid"
	st2 := "hossen"
	st3 := "abdullah"
	sjoin := strings.Join([]string{"MD", st1, st2, st3}, " ")
	fmt.Println(sjoin)
  }
  ~~~

## গোল্যাং-এ ফাংশন
   গোল্যাং-এ ফাংশন হল একটি কোড ব্লক যা নির্দিষ্ট কাজ সম্পাদন করতে ব্যবহৃত হয়। ফাংশন ব্যবহার করে কোড পুনঃব্যবহারযোগ্য, পরিষ্কার এবং সহজবোধ্য করা যায়।

   - প্যারামিটার পাসিং: গোল্যাং-এ প্যারামিটার পাসিং ডিফল্টভাবে পাস বাই ভ্যালু।
   - পয়েন্টার ব্যবহার: পয়েন্টার দিয়ে পাস করলে পাস বাই রেফারেন্স-এর মতো আচরণ করে।
   - Variadic Function: যেকোনো সংখ্যক আর্গুমেন্ট পাস করার জন্য ব্যবহার করা যায়।
   - Defer: ফাংশন শেষে কোনো নির্দিষ্ট কাজ করতে কার্যকর।

  ~~~
  package main

  import "fmt"

  func greet(name string) {
      fmt.Println("Hello,", name)
  }

  func main() {
      greet("Alice")
  }
  ~~~

  ~~~
  package main

  import "fmt"

  func add(a int, b int) int {
      return a + b
  }

  func main() {
      result := add(5, 3)
      fmt.Println("Sum:", result)
  }
  ~~~


  ~~~
  //একাধিক রিটার্ন ভ্যালু সহ
  package main

  import "fmt"

  func divide(a int, b int) (int, int) {
      quotient := a / b
      remainder := a % b
      return quotient, remainder
  }

  func main() {
      q, r := divide(10, 3)
      fmt.Println("Quotient:", q)
      fmt.Println("Remainder:", r)
  }
  ~~~

  ~~~
  //পয়েন্টার প্যারামিটার সহ ফাংশন
  package main

  import "fmt"

  func increment(num *int) {
      *num = *num + 1
  }

  func main() {
      value := 10
      increment(&value)
      fmt.Println("Incremented Value:", value)
  }
  ~~~


  
  ~~~
  //ল্যাম্বডা বা অ্যানোনিমাস ফাংশন
  package main

  import "fmt"

  func main() {
      add := func(a, b int) int {
          return a + b
      }

      fmt.Println("Sum:", add(3, 7))
  }
  ~~~
   
## গোল্যাং প্যাকেজ
   প্যাকেজ হলো সম্পর্কিত কোড ফাইলগুলোর একটি সংগ্রহ যা একসঙ্গে একটি নির্দিষ্ট কার্য সম্পাদন করে। প্রতিটি গোল্যাং প্রোগ্রাম অন্তত একটি প্যাকেজ ধারণ করে, যেমন main।

   - __প্যাকেজ তৈরি__
      - একটি নতুন ফোল্ডার তৈরি করুন।
      - ফোল্ডারের প্রতিটি .go ফাইলের শুরুতে package <package_name> ডিক্লারেশন দিন।
       
  - __ফাইল: mathutil/mathutil.go__
  ~~~
  package mathutil

  func Add(a, b int) int {
      return a + b
  }

  func Multiply(a, b int) int {
      return a * b
  }
  ~~~
  - __ফাইল: main.go__
  ~~~
  package main

  import (
      "fmt"
      "yourmodule/mathutil" // প্যাকেজ ইমপোর্ট
  )

  func main() {
      fmt.Println("Sum:", mathutil.Add(5, 3))
      fmt.Println("Product:", mathutil.Multiply(4, 2))
  }
  ~~~
