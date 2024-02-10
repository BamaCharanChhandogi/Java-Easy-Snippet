# Java Easy Snippet

## Description

Boost your Java development productivity with the **Java Boilerplate Generator** extension for Visual Studio Code. Say goodbye to repetitive code setup and hello to streamlined project initialization. This extension provides essential Java boilerplate code snippets and templates, helping you kickstart your projects swiftly and efficiently.

## How to Use

**Step 1:** Install Java Easy Snippet  
**Step 2:** Not Downloaded Yet? [Download Now](https://marketplace.visualstudio.com/items?itemName=BamaCharanChhandogi.JavaSnippet)  
**Step 3:** Find all snippets below and use as per need.  
**Step 4:** Happy Coding

## Demo Screenshot

![hello](https://github.com/BamaCharanChhandogi/Java-Easy-Snippet/blob/master/images/screen.png?raw=true)

## Example Java Snippet

| No  | Java Snippet Short Code | Description                         |
| :-- | :----------------------- | :---------------------------------- |
| 1   | java                    | Basic Java Class with Main Method   |
| 2   | jscan                   | Java Class with Scanner             |
| 3   | jarraylist              | Java Class with ArrayList           |
| 4   | jhashmap                | Java Class with HashMap             |
| 5   | jlinkedlist             | Java Class with LinkedList          |
| 6   | jqueue                  | Java Class with Queue                |
| 7   | jstack                  | Java Class with Stack                |
| 8   | jset                    | Java Class with HashSet              |
| 9   | jtreemap                | Java Class with TreeMap              |
| 10  | jpqueue                 | Java Class with PriorityQueue        |
| 11  | jhashset                | Java Class with HashSet              |
| 12  | jtreeset                | Java Class with TreeSet              |
| 13  | jlinkedhashset          | Java Class with LinkedHashSet        |
| 14  | jarraylistiter          | Java Class with ArrayList Iteration  |
| 15  | jhashmapiter            | Java Class with HashMap Iteration    |
| 16  | jlinkedlistiter         | Java Class with LinkedList Iteration |
| 17  | jqueueiter              | Java Class with Queue Iteration      |
| 18  | jstackiter              | Java Class with Stack Iteration      |
| 19  | jsetiter                | Java Class with Set Iteration        |
| 20  | jtreemapiter            | Java Class with TreeMap Iteration    |
| 21  | jpqueueiter             | Java Class with PriorityQueue Iteration  |
| 21  | jout                    | Java Class with output                |



<!-- ## View Demo Codes  -->

<!-- ![java-easy-snippet](#) -->

## View Snippet Codes

### 1. java = Basic Java Class with Main Method

```java
public class Main {
    public static void main(String[] args) {
        $0
    }
}
```
### 2. jscan = Java Class with Scanner
```java
Scanner scanner = new Scanner(System.in);
```
<!-- Input section -->
## 3. jscanint = Creates a Java class with a Scanner object for user input Integer
```java
int ${1:variable} = scanner.nextInt();
```

## 4. jscanstr = Creates a Java class with a Scanner object for user input String
```java 
String ${1:variable} = scanner.nextLine();
```

## 5. jscandouble = Creates a Java class with a Scanner object for user input Double
```java
double ${1:variable} = scanner.nextDouble();
```
## 6. jscandfloat = Creates a Java class with a Scanner object for user input Float
```java
float ${1:variable} = scanner.nextFloat();
```
## 7. jscanlong = Creates a Java class with a Scanner object for user input Long
```java
float ${1:variable} = scanner.nextLong();
```
## 8. jscanbool = Creates a Java class with a Scanner object for user input Boolean
```java
boolean ${1:variable} = scanner.nextBoolean();
```
## 9. jscanbyte =  Creates a Java class with a Scanner object for user input Byte.
```java
byte ${1:variable} = scanner.nextByte();
```
## 10. jscanshort = Creates a Java class with a Scanner object for user input Short
```java
short ${1:variable} = scanner.nextShort();
```
## 11. jscanchr =  Creates a Java class with a Scanner object for user input Char
```java
char ${1:variable} = scanner.next().charAt(0);
```

## 12. jscanbiginteger = Creates a Java class with a Scanner object for user input BigInteger
```java
BigInteger ${1:variable} = scanner.nextBigInteger();
```

## 13. jscanbigdecimal = Creates a Java class with a Scanner object for user input BigDecimal
```java
BigDecimal ${1:variable} = scanner.nextBigDecimal();
```
## 14. jscannextline = Creates a Java class with a Scanner object for user input Line
```java
scanner.nextLine();
```
## 15. jscanintarray = Creates a Java class with a Scanner object for user input Integer Array.
```java
Scanner scanner = new Scanner(System.in);
int[] arr = new int[scanner.nextInt()];

for (int i = 0; i < arr.length; i++) {
    arr[i] = scanner.nextInt();
}
```
## 16. jscanstrarray = Creates a Java class with a Scanner object for user input String Array
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
scanner.nextLine(); // Consume the newline character

String[] arr = new String[n];
for (int i = 0; i <arr.length; i++) {
    arr[i] = scanner.nextLine();
}
```
## 17. jscanintarraylist = Creates a Java class with a Scan scanner object for user input Integer Array list
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();

ArrayList<Integer> list = new ArrayList<>();
for (int i = 0; i < n; i++) {
    list.add(scanner.nextInt());
}
```
## 18. jscanstrarraylist = Creates a Java class with a Scan scanner object for user input String Array list
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
scanner.nextLine(); // Consume the newline character

ArrayList<String> list = new ArrayList<>();
for (int i = 0; i < n; i++) {
    list.add(scanner.nextLine());
}
```
## 19. jscanintlinkedlist = Creates a Java class with a Scan scanner object for user input Integer LinkedList
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();

LinkedList<Integer> list = new LinkedList<>();
for (int i = 0; i < n; i++) {
    list.add(scanner.nextInt());
}
```
## 20. jscanstrlinkedlist = Creates a Java class with a Scan scanner object for user input String LinkedList
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
scanner.nextLine(); // Consume the newline character

LinkedList<String> list = new LinkedList<>();
for (int i = 0; i < n; i++) {
    list.add(scanner.nextLine());
}
```
## 21. jscanintqueue = Creates a Java class with a Scan scanner object for user input Integer Queue
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();

Queue<Integer> queue = new LinkedList<>();
for (int i = 0; i < n; i++) {
    queue.offer(scanner.nextInt());
}
```
## 22. jscanstrqueue = Creates a Java class with a Scan scanner object for user input String Queue
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
scanner.nextLine(); // Consume the newline character

Queue<String> queue = new LinkedList<>();
for (int i = 0; i < n; i++) {
    queue.offer(scanner.nextLine());
}
```
## 23. jscanintstack = Creates a Java class with a Scan scanner object for user input Integer Stack
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();

Stack<Integer> stack = new Stack<>();
for (int i = 0; i < n; i++) {
    stack.push(scanner.nextInt());
}
```
## 24. jscanstrstack = Creates a Java class with a Scan scanner object for user input String Stack
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
scanner.nextLine(); // Consume the newline character

Stack<String> stack = new Stack<>();
for (int i = 0; i < n; i++) {
    stack.push(scanner.nextLine());
}
```
## 25. jscanintset = Creates a Java class with a Scan scanner object for user input Integer Set
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();

Set<Integer> set = new HashSet<>();,
for (int i = 0; i < n; i++) {
    set.add(scanner.nextInt());
}
```
## 26. jscanstrset = Creates a Java class with a Scan scanner object for user input String Set
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
scanner.nextLine(); // Consume the newline character

Set<String> set = new HashSet<>();,
for (int i = 0; i < n; i++) {
    set.add(scanner.nextLine());
}
```

## 27. jscaninttreemap = Creates a Java class with a Scan scanner object for user input Integer TreeMap
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();

Map<Integer, Integer> map = new TreeMap<>();
for (int i = 0; i < n; i++) {
    set.add(scanner.nextInt());
}
```
## 28. jscansrset = Creates a Java class with a Scan scanner object for user input String TreeMap
```java
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
scanner.nextLine(); // Consume the newline character

Map<String, Integer> map = new TreeMap<>();
for (int i = 0; i < n; i++) {
    map.put(scanner.nextLine(), scanner.nextInt());
}
```




### 1. jarraylist = Java Class with ArrayList
```java
ArrayList<Integer> list = new ArrayList<>();
```
### 2. jhashmap = Java Class with HashMap
```java
HashMap<String, Integer> map = new HashMap<>();
```
### 3. jlinkedlist = Java Class with LinkedList
```java
LinkedList<Integer> list = new LinkedList<>();
```
### 4. jqueue = Java Class with Queue
```java
Queue<Integer> queue = new LinkedList<>();
```
### 5. jstack = Java Class with Stack
```java
Stack<Integer> stack = new Stack<>();
```
### 6. jset = Java Class with HashSet
```java
HashSet<Integer> set = new HashSet<>();
```
### 7. jtreemap = Java Class with TreeMap
```java
TreeMap<String, Integer> map = new TreeMap<>();
```

### 8. jpqueue = Java Class with PriorityQueue
```java
PriorityQueue<Integer> pq = new PriorityQueue<>();
```

## 9. jhashset = Java Class with HashSet
```java
HashSet<Integer> set = new HashSet<>();
```

## 10. jtreeset = Java Class with TreeSet
```java
TreeSet<Integer> set = new TreeSet<>();
```
## 11. jlinkedhashset = Java Class with LinkedHashSet
```java
LinkedHashSet<Integer> set = new LinkedHashSet<>();
```
