# [Hacks  Markdown Guide](https://www.markdownguide.org/hacks/) 

20220827 1626
<details open>
<summary> <sup><sub><mark>--note--</mark></summary>
<p> <sub>I went down a rabbit hole. </sub><br> So...
I learned 

      [ how to create a collapsible code ]

Went back to it: 17:05
<br>
</details>



<details open>
<summary><mark>(1)</mark> underline </summary>

    Some of these words will <ins>be underlined.<ins> 

結果：
- Some of these words will <ins> be underlined.<ins> 

</details>

<details open>
<summary>(2) Indent</summary>

    &nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.


結果：
- &nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.

</details>




<details open>
<summary>(3) Center</summary>

    <center>This text is centered.</center>


結果：
- <center>This text is centered.</center>

<sub>INFO: Do note that `<center>` tag is:
- <sub>technically supported BUT
- <sub>officially deprecated

    what is 
    <details>
    <summary>deprecated</summary>
    
    ![image](https://user-images.githubusercontent.com/111704606/187030022-91150393-e5e3-4391-972a-92412c29d88b.png)
</details>


<details open>
<summary>(4) Color</summary>
*markdown doesn't allow text color change, but if it supports HTML

    <font>

is usable.

Would have to use either
- color name
- hexadecimal #RRGGBB code


        <font color="green"> **GREEN TEXT SAMPLE** </font>


結果：
-   <font color="green"> **GREEN TEXT SAMPLE** </font>
    <details open>
    <summary> NOTE </summary>
    > also deprecated. <br>

    >"The <font> HTML tag is technically supported but officially deprecated, which means it works for now but you’re not supposed to be using it. Unfortunately, there’s not another pure HTML alternative. You could try using one of the CSS alternatives. Not all Markdown applications provide CSS support, but if the one you’re using does, here’s an alternative to the <font> tag:" </br>
    
    ![image](https://user-images.githubusercontent.com/111704606/187030549-8a1294ac-623b-473f-901f-89056bd26562.png)

        
</details>

---



<details open>
<summary>(5) Comments</summary>

    This is not a hidden paragraph.

    [While this one is a comment that will be hidden. ]: #

    This is another unhidden sentence.


    Here's a paragraph that will be visible.

    [This is a comment that will be hidden.]: # 

    And here's another paragraph that's visible.

結果：

This is not a hidden paragraph/sentence.

[ While this one is a comment that will be hidden. ]: #
This is another unhidden sentence.

Here's a paragraph that will be visible.

[ This is a hidden comment]: #

This is another paragraph that's visible.

</details>





<details open>
<summary>(6) Admonitions</summary>

.
> <sub>Admonitions are frequently used in documentation to call attention to warnings, notes, and tips. Markdown doesn’t provide special syntax for admonitions, and most Markdown applications don’t provide support for admonitions (one exception is MkDocs).

> <sub><sub> However, if you need to add admonitions, you might be able to use blockquotes with emoji and emphasis to create something that looks similar to the admonitions you see on other websites. </sub>


    > :warning: **Warning:** Do not push the big red button.

    > :memo: **Note:** Sunrises are beautiful.

    > :bulb: **Tip:** Remember to appreciate the little things in life.





結果：
- 
> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.

![image](https://user-images.githubusercontent.com/111704606/187030952-43dc8e15-8c0a-4a41-8bd5-999111196955.png)



</details>





<details open>
<summary>()</summary>

結果：
- 
</details>










<details open>
<summary>()</summary>

結果：
- 
</details>