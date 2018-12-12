# First
## Second
### Third

_Emphasize_
==marked text==
~~Strike text~~
> Quoted text.
> 
- items
- [x] Complete Item
- [ ] Incomplete Item	
-------
[Canasu](canasu.org)
![Test image](https://www.hdwallpaper.nu/wp-content/uploads/2015/12/Joker_wallpaper_047.jpg =500x150)
-------
```javascript
var foo = 'bar';
$(document).ready(function(){
alert('hello world!');
});
```
```html
<html>
<head>
<body></body>
</head>
</html>
```
```css
.class
{
background-color:red;
}
#id
{
border:2px solid black;
}
```
```php
<?php
$hello;
echo "Hello World";
?>
```
```c++
#include<iostream.h>
void main()
{
int i;
for(i=0;i<10;i++)
cout<<i;
}
```
```c
#include<stdio.h>
void main()
{
printf("Hello again");
}

```
```java
import java.io.*
public class main
{
public static void main(String args[]) throws IOException
{
System.out.println("hello World!");
}
}
```
```python
print("Goodbye, World!")
```
```ruby
class HelloWorld
   def initialize(name)
      @name = name.capitalize
   end
   def sayHi
      puts "Hello #{@name}!"
   end
end

hello = HelloWorld.new("World")
hello.sayHi
```

|Item|Value|
------|-----
Computer|$1600
Phone|$100
Pencil|$1

-------
$\Gamma(n) = (n-1)!\quad\forall
n\in\mathbb N$
-------
$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$
### Emojis
:smile::grinning::smiling_imp::punch::-1::+1::v::skull:
### Gantt Charts
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
  ```
  
   ```mermaid
   gantt
      dateFormat  YYYY-MM-DD
       title Adding GANTT diagram functionality to mermaid

       section A section
       Completed task            :done,    des1, 2014-01-06,2014-01-08
       Active task               :active,  des2, 2014-01-09, 3d
       Future task               :         des3, after des2, 5d
       Future task2              :         des4, after des3, 5d

       section Critical tasks
       Completed task in the critical line :crit, done, 2014-01-06,24h
       Implement parser and jison          :crit, done, after des1, 2d
       Create tests for parser             :crit, active, 3d
       Future task in critical line        :crit, 5d
       Create tests for renderer           :2d
       Add to mermaid                      :1d

       section Documentation
       Describe gantt syntax               :active, a1, after des1, 3d
       Add gantt diagram to demo page      :after a1  , 20h
       Add another diagram to demo page    :doc1, after a1  , 48h

       section Last section
       Describe gantt syntax               :after doc1, 3d
       Add gantt diagram to demo page      :20h
       Add another diagram to demo page    :48h

```

```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
  ```
```abc
  X: 24
T:Clouds Thicken
C:Paul Rosen
S:Copyright 2005, Paul Rosen
M:6/8
L:1/8
Q:3/8=116
R:Creepy Jig
K:Em
|:"Em"EEE E2G|"C7"_B2A G2F|"Em"EEE E2G|\
"C7"_B2A "B7"=B3|"Em"EEE E2G|
"C7"_B2A G2F|"Em"GFE "D (Bm7)"F2D|\
1"Em"E3-E3:|2"Em"E3-E2B|:"Em"e2e gfe|
"G"g2ab3|"Em"gfeg2e|"D"fedB2A|"Em"e2e gfe|\
"G"g2ab3|"Em"gfe"D"f2d|"Em"e3-e3:|
```

 

   

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMjMzMjAyNzEsMTQ1MjcxNzg2NF19
-->