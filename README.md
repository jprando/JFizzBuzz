# JFizzBuzz
Fizz Buzz teste em C#

<pre>
Enumerable.Range(1,100)
    .Select(i => $"{i:00} {(i%3==0?"Fizz":"")}{(i%5==0?"Buzz":"")}")
    .ToList().ForEach(Console.WriteLine)
</pre>

<i>dá pra melhorar?</i>

<img src="https://github.com/jprando/JFizzBuzz/raw/master/execJFizzBuzz.png">
