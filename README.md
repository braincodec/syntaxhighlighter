Syntax Highlighter

This repository contains all the code you need to have syntax coloring or highlighting in your blogger blog.

All you must to do is to open the blogger_code.txt and insert that code in the template of your blog html code,
before the "</head>" tag and then when you write a post with code the only thing you must to do is to enclose your
code between <pre> and </pre> tags like below:

<pre class="brush:cpp;">
int main()
{
	printf("This is a block of syntax colored code\n".);
}
</pre>