coloriq
=======

Goal: Reproduce the Color IQ Test so it works on mobile devices. http://xritephoto.com/ph_toolframe.aspx?action=coloriq
Specifics: 
1. Create an HTML page with a 4 row x 22 column grid. 
2. On every re/load, col 1 and col 22 for each row should always show the same color: 
[1][1] = 
[1][22] = 
[2][1] = 
[2][22] =
[3][1] = 
[3][22] = 
[4][1] = 
[4][22] =
3. Tile colors should be stored in a multidimensional array, but the "static tiles," those that are col 1 and col 22 for each row, should not be part of the array. 
4. Tile colors should display distinct (non-repeating) random colors between col 1 and col 22 for their row.
5. Users must be able to drag and drop tiles into any other tile holder in the same row. 
6. On submit, tiles will be tested against the correct tile arrangement in "correct" array.
7. For each incorrect tile placement (or "answer"), the user's IQ percentage will increase (n/40)*100 = x %
8. Research: is there an "official color iq" index? Why does % go up as IQ is worse? Should it be a number between 0-100, 100 being the top score you can receive? Address this. 
