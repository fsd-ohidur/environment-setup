# Learn Markdown syntax
### Heading: #  (use Hash)  
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
  
### Italic: _ (use Underscore)  
```
Sample of _Italic Text_
```
**Output:** Sample of _Italic Text_  
  
### Bold: ** (use double asteric)  
```
Sample of **Bold Text**
```
**Output:** Sample of **Bold Text**

### Paragraph
Simple text, Just use double space for soft line break
```
Line one [two space]
Line two
```
Line one  
Line two

### Hyperlink:
* Single Link  
```
[Link Text](url)
Want to visit [my git home page](https://github.com/fsd-ohidur)?
[More markdown guide](https://www.markdownguide.org/extended-syntax/)
```
**Output:**  
Want to visit [my git home page](https://github.com/fsd-ohidur)?  
[More markdown guide](https://www.markdownguide.org/extended-syntax/)  

* Multiple Link  
  - Create Label  
  [label name]: url  
  - Use Label   
  And now back to [Link text][label name]    
```
[Google]:https://www.google.com
[Youtube]:https://www.youtube.com

1. want to visit [google][Google]
2. want to visit [youtube][Youtube]
3. Search text to [google][Google]
4. Watch video to [youtube][Youtube]
```
[Google]:www.google.com
[Youtube]:www.youtube.com

1. want to visit [google][Google]  
2. want to visit [youtube][Youtube]  
3. Search text on [google][Google]  
4. Watch video on [youtube][Youtube]  

### Image
Image and hyperlink is same, for image just use a ! symbol at beginging
```
My ![Avator](https://avatars.githubusercontent.com/u/98311745?s=40&v=4)
```
**Output**
My Avator ![Avator](https://avatars.githubusercontent.com/u/98311745?s=40&v=4)

### List
* Order List
```
1. a
2. b
3. c
```
**Output**
1. a
2. b
3. c

* Un-Order List
```
* a
* b
* c
  * c1
  * c2
```
**Output**
* a
* b
* c
  * c1
  * c2
  
 ### Code block
 use ``` at begining and end
 
 ### Quote block
 use > at begining for single quote  
 use > at begining of each quote and blank line for group of quote
 
 
