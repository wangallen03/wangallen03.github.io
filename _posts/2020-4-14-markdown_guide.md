---
layout: default
title: yes
---

# markdown

### why markdown?
---
tl;dr: html is a pain
basically, your only other option if you want c*O*o**L** formatting online is html. but html is kinda unintuitive and has tags out the wazoo. look at this table i made in markdown. pretty cool, huh?
| this | list | is   |
| ---- | ---- | ---- |
| a    | list | --   |
it took me more time to think of what to put in the table than it did to actually create it: 
~~~
| this | list | is |
|  -   |  -   |  - | 
| a    | list | -- |
~~~
now look at what that code would look like in HTML:
~~~
<table>
   <thead>
      <tr>
         <th>this</th>
         <th>list</th>
         <th>is</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>a</td>
         <td>list</td>
         <td>--</td>
      </tr>
   </tbody>
</table>
~~~
big difference, huh? sure, the second example is readable, but it definitely takes a lot more effort to parse. although markdown doesn't offer the flexibility that HTML or a word processor like Google Docs does, it's a lot more easy to learn and use because of its simplicity. also you can use it on forums and stuff if you want to talk to your friends (yay!) or get into endless arguments (no!) more fancily.



### why it exist?
---
two cool people called john gruber and aaron swartz saw how much of a pain it was to format things in html and thought "hey, what if we made html more simple. so people can post things without needing to learn html. that would be pretty cool if we did it." they did it. it was, indeed, pretty cool. swartz would later go on to found reddit and rss, which was pretty cool, and then try to download documents on jstor to make them freely available, which was also pretty cool, and then get arrested for that and commit suicide, which was very decidedly not cool. 

### features n stuff!
---
##### headers
this is how you a headers:
~~~
# biggest header
### smaller header
###### smallest header
~~~
and this is what it looks like:
# biggest header
### smaller header
###### smallest header

##### fancy text!
---
same deal
~~~
**BOLD** 
__ALSO BOLD__

*italics*
_this works too_

~~strikethrough~~
~~~
and this is what it looks like:
**BOLD** 
__ALSO BOLD__

*italics*
_this works too_

~~strikethrough~~

##### numeric and bulleted lists
---
~~~
1. this is the first entry
this is a very cool description of it! or maybe it's something else, who knows? certainly not me
2. this is the second entry
5. this is the third entry, even though i wrote 5! now ain't that neat

* this is a bullet point
- this is also a bullet point
+ you don't get a choice, everything is a bullet point
~~~
1. this is the first entry
this is a very cool description of it! or maybe it's something else, who knows? certainly not me
2. this is the second entry
5. this is the third entry, even though i wrote 5! now ain't that neat

* this is a bullet point
- this is also a bullet point
+ you don't get a choice, everything is a bullet point 

##### numeric and bulleted lists 2! sublist boogaloo!
---
~~~
* a bullet
  1. a number!
      * and another bullet!
       3. oh no, this is part of the same list :(
~~~
note: you have to indent each new sublist by at least 2 spaces for it to show up as a sublist
* a bullet
  1. a number!
      * and another bullet!      
       3. oh no, this is part of the same list :(

##### links and images
---
~~~
[link](https://google.com/ "optional mouseover description!")
![image](https://cdn.arstechnica.net/wp-content/uploads/2012/05/astley.jpg "another optional description!")
~~~

[link](https://google.com/ "optional mouseover description!")
![image](https://cdn.arstechnica.net/wp-content/uploads/2012/05/astley.jpg "another optional description!")

##### links and images, but more fancily
---
~~~
[you can write text here][1]
[1]: https://google.com/ "and insert the link and description here in the footnotes"
[same with images][image]
[image]: https://cdn.arstechnica.net/wp-content/uploads/2012/05/astley.jpg "another optional description!"
~~~

[you can write text here][1]

[1]: https://google.com/ "and insert the link and description here in the footnotes"
[same with images][image]

[image]: https://cdn.arstechnica.net/wp-content/uploads/2012/05/astley.jpg "another optional description!"

##### tables!

---

~~~
| these | are | the | headers |
|  -   | 
| the | "| - |" | is | necessary | ignored text cause the headers determine how many rows will show up|

|  |   |  |
|:-|:-:|-:|
|left aligned text|center aligned text|right aligned text|
~~~

| these | are       | the  | headers   |
| ----- | --------- | ---- | --------- |
| the   | "\| - \|" | is   | necessary |

|                   |                     |                    |
| :---------------- | :-----------------: | -----------------: |
| left aligned text | center aligned text | right aligned text |

##### miscellaneous things

~~~
​~~~
this is how i did the cool multiline code you see
​~~~
```
this should work too
```
    
and this is how you `embed` code
---
3 dashes make a horizontal line

***
3 asterisks make a horizontal line too

if you want to use markdown characters like *this*, markdown will interpret them as formatting markers
put a backslash before your \* and markdown will render them as regular characters instead
~~~

~~~
this is how i did the cool multiline code you see
~~~
```
this should work too
```

and this is how you `embed` code

---
3 dashes make a horizontal line

***

3 asterisks make a horizontal line too

if you want to use markdown characters like *this*, markdown will interpret them as formatting markers.
put a backslash before your \* and markdown will render them as regular characters instead

