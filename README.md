# Operators - Arithmetic Operators
هناك عدد من العمليات المختلفة التي يمكنك استخدامها أثناء البرمجة مثل العمليات الرياضية وعمليات المقارنة والعمليات المنطقية وغيرها من العمليات المُختلفة، وسنتحدث في هذا الجزء عن مجموعة من أهم العمليات التي توفرها لغة Dart.

- Arithmetic Operators || العمليات الحسابية 
- Assignment Operator || عوامل الإسناد
- Relational Operators || العمليات العلاقية
- Logical Operators || العمليات المنطقية
## المعاملات الحسابية Arithmetic Operators
| العلامات | الاسم                |
| -------- | -------------------- |
| +        | الجمع                |
| –        | الطرح                |
| *        | الضرب                |
| /        | القسمه               |
| ~/       | باقي القسمه عدد صحيح |
| %        | باقي القسمه          |

    
    void main() {
    
        int a = 2;
        int b = 3;
     
        // Adding a and b
        var c = a + b;
        print("Sum of a and b is $c");
     
        // Subtracting a and b
        var d = a - b;
        print("The difference between a and b is $d");
     
        // Multiplication of a and b
        var f = a * b;
        print("The product of a and b is $f");
     
        // Division of a and b
        var g = b / a;
        print("The quotient of a and b is $g");
     
        // Using ~/ to divide a and b
        var h = b ~/ a;
        print("The quotient of a and b is $h");
     
        // Remainder of a and b
        var i = b % a;
        print("The remainder of a and b is $i");
    
    }


المخرجات :

    Sum of a and b is 5
    The difference between a and b is -1
    The product of a and b is 6
    The quotient of a and b is 1.5
    The quotient of a and b is 1
    The remainder of a and b is 1



