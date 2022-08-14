## Class 2:

> Topics: Class, Data type, OOP, @Override, MaterialApp, Scaffold, AppBar, Image + pubspec.yaml

## flutter_class_02_assignment

1. [x] Manually main.dart file a কোড করে
2. [x] বডিতে একটা এসেট ইমেজ এড করতে হবে ।
3. [x] এ্যাপবার এড করতে হবে সাথে নেইম থাকবে.
4. [x] ভ্যারিয়েবল, ক্লাস, ফাংশন সম্পর্কে অনলাইনের ডকুমেন্টস পড়তে হবে ।

## Flutter_Class-02_Assignment

## Getting Started

A new Flutter project.

Then...

# class_02_assignment

## Home Work Start

1.  [x] Manually main.dart file a কোড করে

> 3. এখানে AppBar টেক্সট যুক্ত করছি..

```dart
 AppBar(
        title: const Text("Class-02 Assignment"),
      )

```

> এখানে class তৈরি করছি + StatelessWidget নিয়েছি, Scaffold উইজেট নিয়েছি সেখানে AppBar নিয়ে টেক্সত উইজেট নিয়েছি

‌‌

```dart
class MyHomePage extends StatelessWidget {
  const MyHomePage({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text("Class-02 Assignment"),
      ),
      body: Container(
        child: Center(child: Text("Class-02 Assignment")),
      ),
    );
  }
}
```

> 2. বডিতে একটা এসেট ইমেজ এড করলাম।

```dart
 Image(image: AssetImage('assets/images/rabbi.jpg')),
```

## Result

![Class-02_Assignment_01](https://user-images.githubusercontent.com/86506002/184548811-647d7f26-3826-4bd9-968c-2b6cac41b17c.jpg)

