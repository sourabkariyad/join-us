## About You.

1. 

My name is Sourab and I am from Kannur, Kerala.

Coming to my family we are seven members including me. Apart from my parents, I have grand father, grand mother, younger brother and younger sister, my father is a tea shop keeper and my mother is a housewife.

I have completed MCA from Pondicherry Central University. Now I am a Software Engineer at Zyntegra Solutions. Having 2 years of experience in PHP and its frameworks. Mainly handling Laravel and WordPress.

I am very interested to learn and work with new technologies.

My goal is to become one of the best Full Stack Developer.

My hobbies are listening to music, travelling, playing puzzle games etc.

That's all about me.

Thank you.


2.

OS: Windows 10
Editor: Sublime text & VS code
Database: MySQL
Local Server: Xampp


## Social Profile

1.
Github profile url: https://github.com/sourabkariyad

2.
LinkedIn profile: https://www.linkedin.com/in/sourab-k-a33567171/


## The real stuff.

2.

<?php
function numArray($num)
{
	return str_split($num);
}
print_r(numArray(524));
?>


3.

<?php
function pigLatin($text)
{
$arr = explode(' ',$text);
foreach($arr as $ar)
{
	$word = strrev($ar);
    $pig_latin_word = $word. 'ay ';
    $pig_latin .= $pig_latin_word;
}
return $pig_latin;
}
echo pigLatin("I am a professional prograammer");
?>


4.
<?php
function rotates($k)
{
$arr = array(1,2,3,4,5,6);
for($i=0; $i < $k; $i++)
{
array_push($arr, array_shift($arr));

}
return $arr;
}

print_r(rotates(3));

?>


5.

https://github.com/sourabkariyad/url-shortner



