
## Varibles

المتغيرات في دارت تُستخدم لتخزين القيم التي يمكن أن تتغير أثناء تنفيذ البرنامج.

<br>

1. Dynamic types

المتغيرات الديناميكية في دارت هي التي يمكن تغيير نوعها أثناء التشغيل.

تتيح لك المتغيرات الديناميكية مرونة أكبر في البرمجة، حيث يمكنك تغيير نوع المتغير أثناء تشغيل البرنامج.


<br>

```dart
    var variable1 = 'string';
    Object variable2 = 'string';
    dynamic variable3 = 1313; 
    variable4 = false;
```

<br>

2. Static types

المتغيرات الثابته في دارت هي التي لا يمكن تغيير نوعها أثناء التشغيل.


```dart
    String variable1 = 'string';
    double variable2 = 12.3;
    int variable3 = 1313; 
    bool variable4 = false;
```

### dynamic vs  var vs final

*  Dynamic <br>
    نستطيع تغير نوع المتغير وايضا قيمه المتغير فيما بعد

```dart
    // type is String value is "word"  
    dynamic variable1 = 'word'; 
    // type is String value is "name"  
    variable1 = 'name';
    // type is int value is 1313  
    variable1 = 1313; 
    // type is bool value is false  
    variable1 = false;
```

*  var <br>
 نستطيع تغير قيمه المتغير ولاكن لا نستطيع نوع المتغير فيما بعد

```dart
    // type is String value is "word"  
    var variable1 = 'word'; 
    // type is String value is "name"  
    variable1 = 'name';
    // type cannot be changed  
    variable1 = 1313; // wrong
    // type cannot be changed  
    variable1 = false; // wrong
```

*  final <br>
لا نستطيع تغير قيمه المتغير ولا نستطيع  تغيرنوع المتغير فيما بعد

```dart
    // type is String value is "word"  
    final variable1 = 'word'; 
    // value cannot be changed
    variable1 = 'name'; // wrong
    // type cannot be changed  
    variable1 = 1313; // wrong
    // type cannot be changed  
    variable1 = false; // wrong
```
<br>

### final vs const    

الفرق الوحيد بينهم هو ان final يمكن تغير ال fields ولاكن ال const لا يمكن .

```dart
    final final_list = [1, 2, 4];
    final_list.add(5); // final_list = [1,2,4,5]
    
    const const_list = [1, 2 ,3];
    const_list.add(); // const cannot be modified 
```

