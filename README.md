# class_02_assignment

1. Manually main.dart file a কোড করে
2. বডিতে একটা এসেট ইমেজ এড করতে হবে ।
3. এ্যাপবার এড করতে হবে সাথে নেইম থাকবে.
4. ভ্যারিয়েবল, ক্লাস, ফাংশন সম্পর্কে অনলাইনের ডকুমেন্টস পড়তে হবে ।

## Home Work Start

1.  [x] Manually main.dart file a কোড করে

> এখানে AppBar টেক্সট যুক্ত করছি..

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
