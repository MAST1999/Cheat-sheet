for fixing jslint use these on top of js : {

`/*jslint browser:true*/`

`/*jslint devel:true*/`

`/*global window */`

}

regular expressions {
    
for regular expressions : ^ in the beginning of regExpress means the start.

`$` in the end means the end of regExpress.

var regExper = `/[a-r]00/i;`

var regExper = `/[a-r]0[2-6]0[b-g]/i;`

for excluding var regExper = `/[^1abc]0[a-r]0/i;`

another way of making regular expressions : `regExper = new RegExper("E00"."i");`

\d - match any digit `(equal to [0-9]);`

\w - match any word character `(a-z,A-Z,0-9 & ...);`

\s - match whitespace character `(eg - spaces & tabs);`

\t - match a tab only;

use () for separating parts of the regExpress `(/^(a-z)(\d{2})$/);`

for . use : `\.`;

you can give range to character : `/^[a-z]{2,20}$/ or use /^[a-z]+$/` for
one or more;

you can use @ or . etc like this `/^([a-z]+)@(a-z).(\d)$/;`

to make a part optional use ? : `/^([a-z]+)@(a-z).(\d)?$/;`

}
