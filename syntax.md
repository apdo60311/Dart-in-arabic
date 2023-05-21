## syntax

<br>

### 1. Identifiers in Dart
هي الأسماء التي يتم استخدامها لتمييز المتغيرات والوظائف والصفوف في البرنامج. ويجب أن تتبع المعرفات في دارت بعض القواعد والإرشادات لضمان أن تكون مفهومة وسهلة الفهم والصيانة.

<br>
<ul>
    <li>يجب أن تبدأ جميع المعرفات بحرف صغير.</li>
    <li>
    يمكن استخدام الحروف الصغيرة والكبيرة والأرقام والشرطات السفلية "_" في المعرفات.
    </li>
    <li>
    يجب أن تكون المعرفات واضحة وموضوعية، وتعبر عن المتغير أو الوظيفة بشكل جيد.
    </li>
    <li>
    يجب تجنب استخدام المعرفات التي تحتوي على أسماء محجوزة في لغة دارت مثل var وvoid وغيرها.
    </li>
</ul>

```dart
    // camel-case variable 
    var randomVariable = 100;
    // variable start with under score
    int _variable = 104.2;
    // illegal variable name
    String 1randomVariable = 'word';
```
<br>

### <strong>الأسماء المحجوزة في لغة دارت</strong>
<br>

<table style="text-align:center">
    <tbody>
        <tr>
            <td>abstract 1</td>
            <td>continue</td>
            <td>false</td>
            <td>new</td>
            <td>this</td>
        </tr>
        <tr>
            <td>as 1</td>
            <td>default</td>
            <td>final</td>
            <td>null</td>
            <td>throw</td>
        </tr>
        <tr>
            <td>assert</td>
            <td>deferred 1</td>
            <td>finally</td>
            <td>operator 1</td>
            <td>true</td>
        </tr>
        <tr>
            <td>async 2</td>
            <td>do</td>
            <td>for</td>
            <td>part 1</td>
            <td>try</td>
        </tr>
        <tr>
            <td>async* 2</td>
            <td>dynamic 1</td>
            <td>get 1</td>
            <td>rethrow</td>
            <td>typedef 1</td>
        </tr>
        <tr>
            <td>await 2</td>
            <td>else</td>
            <td>if</td>
            <td>return</td>
            <td>var</td>
        </tr>
        <tr>
            <td>break</td>
            <td>enum</td>
            <td>implements 1</td>
            <td>set 1</td>
            <td>void</td>
        </tr>
        <tr>
            <td>case</td>
            <td>export 1</td>
            <td>import 1</td>
            <td>static 1</td>
            <td>while</td>
        </tr>
        <tr>
            <td>catch</td>
            <td>external 1</td>
            <td>in</td>
            <td>super</td>
            <td>with</td>
        </tr>
        <tr>
            <td>class</td>
            <td>extends</td>
            <td>is</td>
            <td>switch</td>
            <td>yield 2</td>
        </tr>
        <tr>
            <td>const</td>
            <td>factory 1</td>
            <td>library 1</td>
            <td>sync* 2</td>
            <td>yield* 2</td>
        </tr>
    </tbody>
</table>

<br>

### 2. Comments
التعليقات في البرمجة هي عبارة عن نصوص أو جمل يتم إضافتها لشرح أو توضيح الأكواد المكتوبة، وتستخدم لتوضيح الأفكار والمفاهيم والتنبيه على الأمور المهمة في الأكواد. وتساعد التعليقات المبرمجين على فهم وصيانة الأكواد بشكل أسهل وتساهم في تحسين جودة البرمجة.

```dart
// single line comment

/*

    Multi-line comment

*/
```

<br>

### 3. Dart is Case-sensitive
دارت حساسة لحالة الحروف ، وهذا يعني أن الأحرف الكبيرة والصغيرة مختلفة. مما يعني أن المعرفات مثل name و Name يعتبران مختلفان.

أسماء ال classes في دارت تبدأ بحرف كبير بالاتفاق.

 المتغيرات والدوال والطرق عادة ما تسمى باستخدام حرف صغير.

 الثوابت عادة ما يتم تسميتها باستخدام حروف كبيرة تمامًا مع فواصل لفصل الكلمات.

```dart
class Person {} //اسم الكلاس يبدأ بحرف كبير

String name; //المتغير يبدأ بحرف صغير

void doSomething() {}  //الدالة تبدأ بحرف صغير   

const PI = 3.14; //الثابتة بالكامل بحروف كبيرة
```

<br>
