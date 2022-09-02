# oscs-all-the-way-down

 A saw tooth, but each partial is a saw tooth and so on, each saw tooth has 8 partials. I did 5 layers of this, Pd's clone object breaks on the 5th layer. I also tried increasing the number of partials in each layers, but Pd also breaks.

 On the main file you will encouter:

 osc -                    1 partial
 saw tooth -          8 ^ 1 partials
 sawsaw tooth -       8 ^ 2 partials
 sawsawsaw tooth -    8 ^ 3 partials
 sawsawsawsaw tooth - 8 ^ 4 partials

 sawsawsawsawsaw tooth is in the main-osc-layer5 file and doesn't play correctly