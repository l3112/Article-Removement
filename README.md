# Article-Removement
https://runtcpip.blogspot.com
The replace() can take away articles for easier sorting. I wonder if there’s an option to take away vowels in words.

Many ways to make this thing;

return strip(a) > strip(b) ? 1 : -1
If all you’re doing in a function is returning something, you can use an implicit return;

const sortBands = bands.sort((a, b) =>  strip(a) > strip(b) ? 1 : -1);

(remove return and the } bracket) 

if(strip(a) > strip(b)){

const sortBands = bands.sort((a, b) => {

.join(‘’) makes one big string instead of a lot of little strings with commas you can see.
