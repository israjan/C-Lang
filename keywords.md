### Taken from [Programwiz](https://www.programiz.com)


<h3><a name="auto"></a>auto</h3>

<p>The auto keyword declares automatic variables. For example:</p>

<pre title="Keyword auto">auto int var1;</pre>

<p>This statement suggests that <var>var1</var> is a variable of storage class auto and type int.</p>

<p>Variables declared within function bodies are automatic by default. They are recreated each time a function is executed.</p>

<p>Since automatic variables are local to a function, they are also called local variables. To learn more visit <a href="https://www.programiz.com/c-programming/c-storage-class" title="C storage class">C storage class</a>.</p>

<hr><h3><a name="break_continue"></a>break and continue</h3>

<p>The break statement terminates the innermost loop immediately when it's encountered. It's also used to terminate the switch statement.</p>

<p>The continue statement skips the statements after it inside the loop for the iteration.</p>

<pre title="Keywords break and continue">for (i=1;i&lt;=10;++i){
   if (i==3)
   continue;
   if (i==7)
   break;
   printf("%d ",i);
} 
</pre>

<p></p><div id="block-inject-1" class="block-inject block-inject-1">
    
    
    
    <style>
    #div-gpt-ad-Programizcom37046 {display:none; width: 728px; height: 90px; }
    #div-gpt-ad-Programizcom36796 {display: block;}
    @media(min-width: 992px) { #div-gpt-ad-Programizcom37046 {display: block;} #div-gpt-ad-Programizcom36796 {display: none;}}
    </style><style class="darkreader darkreader--sync" media="screen"></style><div id="div-gpt-ad-Programizcom37046" style="margin: 32px 0;">
    </div>
    
    <div id="div-gpt-ad-Programizcom36796" style="margin: 32px 0; min-height: 250px;">
    </div>
    </div><div class="clearfix"></div><p><strong>Output</strong></p>

<pre><samp>1 2 4 5 6</samp></pre>

<p>When <var>i</var> is equal to 3, the continue statement comes into effect and skips 3. When <var>i</var> is equal to 7, the break statement comes into effect and terminates the for loop. To learn more, visit <a href="https://www.programiz.com/c-programming/c-break-continue-statement">C break and continue statement</a></p>

<hr><h3><a name="switch_case_default"></a>switch, case and default</h3>

<p>The switch and case statement is used when a block of statements has to be executed among many blocks. For example:</p>

<pre title="Keywords switch, case and default.">switch(expression)
{
    case '1':
    //some statements to execute when 1
    break;
    case '5':
    //some statements to execute when 5
    break;
    default:
    //some statements to execute when default;
}</pre>

<p>Visit <a href="https://www.programiz.com/c-programming/c-switch-case-statement" title="C switch statement">C switch statement</a> to learn more.</p>

<hr><h3><a name="char"></a>char</h3>

<p>The char keyword declares a character variable. For example:</p>

<pre title="Keyword char">char alphabet;
</pre>

<p>Here, <var>alphabet</var> is a character type variable.</p>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-data-types" title="C data types">C data types</a>.</p>

<hr><h3><a name="const"></a>const</h3>

<p>An identifier can be declared constant by using the const keyword.</p>

<pre>const int a = 5;</pre>

<p>To learn more, visit<a href="https://www.programiz.com/c-programming/c-variables-constants" title="C programming variables and constants"> C variables and constants</a>.</p>

<hr><h3><a name="do_while"></a>do...while</h3>

<pre>int i;
do 
{
   printf("%d ",i);
   i++;
}
while (i&lt;10)
</pre>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-do-while-loops" title="C do while loop">C do...while loop</a></p>

<hr><h3><a name="double_float"></a>double and float</h3>

<p>Keywords double and float are used for declaring floating type variables. For example:</p>

<pre title="Keywords double and float ">float number;
double longNumber;
</pre>

<p>Here, <var>number</var> is a single-precision floating type variable whereas, <var>longNumber</var> is a double-precision floating type variable.</p>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-data-types" title="C data types">C data types</a>.</p>

<hr><h3><a name="if_else"></a>if and else</h3>

<p>In C programming, if and else are used to make decisions.</p>

<pre>if (i == 1)
   printf("i is 1.")
else
   printf("i is not 1.")
</pre>

<p>If the value of <var>i</var> is other than 1, the output will be :</p>

<pre><samp>i is not 1</samp></pre>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-if-else-statement" title="C if else">C if...else statement</a>.</p>

<hr><h3><a name="enum"></a>enum</h3>

<p>Enumeration types are declared in C programming using keyword enum. For example:</p>

<pre title="Keyword enum">enum suit
{
    hearts;
    spades;
    clubs;
    diamonds;
};</pre>

<p>Here, an enumerated variable <var>suit</var> is created having tags: <var>hearts</var>, <var>spades</var>, <var>clubs,</var> and <var>diamonds</var>.</p>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-enumeration" title="C enum">C enum</a>.</p>

<hr><h3><a name="extern"></a>extern</h3>

<p>The extern keyword declares that a variable or a function has external linkage outside of the file it is declared.</p>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-storage-class" title="C storage type">C storage type</a>.</p>

<hr><h3><a name="for"></a>for</h3>

<p>There are three types of loops in C programming. The for loop is written in C programming using the keyword <code>for</code>. For example:</p>

<pre>for (i=0; i&lt; 9;++i){
  printf("%d ",i);
}
</pre>

<p><b>Output</b></p>

<pre><samp>0 1 2 3 4 5 6 7 8</samp></pre>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-for-loop" title="C for loop">C for loop</a>.</p>

<hr><h3><a name="goto"></a>goto</h3>

<p>The goto statement is used to transfer control of the program to the specified label. For example:</p>

<pre>for(i=1; i&lt;5; ++i)
{
    if (i==10)
    goto error;
}
printf("i is not 10");
error:
    printf("Error, count cannot be 10.");
</pre>

<p><b>Output</b></p>

<pre><samp>Error, count cannot be 10.</samp></pre>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-goto-statement" title="C goto">C goto</a>.</p>

<hr><h3><a name="int"></a>int</h3>

<p>The int keyword is used to declare integer type variables. For example:</p>

<pre>int count;</pre>

<p>Here, <var>count</var> is an integer variable.</p>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-data-types" title="C data types">C data types</a>.</p>

<hr><h3><a name="short_long_signed_unsigned"></a>short, long, signed and unsigned</h3>

<p>The short, long, signed and unsigned keywords are type modifiers that alter the meaning of a base data type to yield a new type.</p>

<pre>short int smallInteger;
long int bigInteger;
signed int normalInteger;
unsigned int positiveInteger;</pre>

<div class="table-responsive"><table summary="Range of data types when type modifiers are used in int types." border="0"><caption>Range of int type data types</caption>
	<thead><tr><th scope="col">Data types</th>
			<th scope="col">Range</th>
		</tr></thead><tbody><tr><td>short int</td>
			<td>-32768 to 32767</td>
		</tr><tr><td>long int</td>
			<td>-2147483648 to 214743648</td>
		</tr><tr><td>signed int</td>
			<td>-32768 to 32767</td>
		</tr><tr><td>unsigned int</td>
			<td>0 to 65535</td>
		</tr></tbody></table></div><h3><a name="return"></a>return</h3>

<p>The return keyword terminates the function and returns the value.</p>

<pre title="Keyword return">int func() {
    int b = 5;
    return b;
}
</pre>

<p>This function <code>func()</code> returns 5 to the calling function. To learn more, visit <a href="https://www.programiz.com/c-programming/c-user-defined-functions" title="C user defined functions">C user-defined functions</a>.</p>

<hr><h3><a name="sizeof"></a>sizeof</h3>

<p>The sizeof keyword evaluates the size of data (a variable or a constant).</p>

<pre>#include &lt;stdio.h&gt;
int main()
{
    printf("%u bytes.",sizeof(char));
}
</pre>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-operators" title="C operators">C operators</a>.</p>

<p><b>Output</b></p>

<pre><samp>1 bytes.</samp></pre>

<hr><h3><a name="Keyword%20register"></a>register</h3>

<p>The register keyword creates register variables which are much faster than normal variables.</p>

<pre title="Keyword register">register int var1;
</pre>

<hr><h3><a name="static"></a>static</h3>

<p>The <code>static</code> keyword creates a static variable. The value of the static variables persists until the end of the program. For example:</p>

<pre title="Keyword static">static int var;
</pre>

<hr><h3><a name="struct"></a>struct</h3>

<p>The struct keyword is used for declaring a structure. A structure can hold variables of different types under a single name.</p>

<pre title="Keyword struct">struct student{
    char name[80];
     float marks;
     int age;
}s1, s2;</pre>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-structures" title="C structures">C structures</a>.</p>

<hr><h3><a name="typedef"></a>typedef</h3>

<p>The typedef keyword is used to explicitly associate a type with an identifier.</p>

<pre title="Keyword typedef">typedef float kg;
kg bear, tiger;</pre>

<hr><h3><a name="union"></a>union</h3>

<p>A union is used for grouping different types of variables under a single name.</p>

<pre title="Keyword union">union student {
    char name[80];
    float marks;
    int age;
}</pre>

<p>To learn more, visit <a href="https://www.programiz.com/c-programming/c-unions" title="C unions">C unions</a>.</p>

<hr><h3><a name="void"></a>void</h3>

<p>The void keyword meaning nothing or no value.</p>

<pre title="Keyword void">void testFunction(int a) {
  .....
}</pre>

<p>Here, the <code>testFunction()</code> function cannot return a value because its return type is void.</p>

<hr><h3><a name="volatile"></a>volatile</h3>

<p>The volatile keyword is used for creating volatile objects. A volatile object can be modified in an unspecified way by the hardware.</p>

<pre>const volatile number</pre>

<p>Here, <var>number</var> is a volatile object.</p>

<p>Since<var> number</var> is a constant, the program cannot change it. However, hardware can change it since it is a volatile object.</p>
  </div>
