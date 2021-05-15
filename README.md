# SCSS MASTERCLASS

# INTRODUCTION

# FLEXBOX
0. Life Before Flexbox
   1. block
   2. inline-block
      1. 가로로 배치가 가능한 block(=box)
      2. 픽셀단위로 간격조정해야함
   3. inline
      1. box가 아님 -> 유동적인 거라서 너비와 높이가 없음
      2. ex) text
1. First Rule of Flexbox
   1. 바로 붙어있는 부모에 flex container 적용
   2. display: flex;
      1. inline-block 과 동일한 결과
2. Main Axis and Cross Axis
   1. Main Axis : row(수평)
      1. flex-direction: row; <- default
      2. justify-content <- flex container에 설정 
   2. Cross Axis : column(수직)
      1. flex-direction: column;
         1. main axis - column, cross axis - row 
      2. align-items <- flex container에 설정
3. Column and Row
4. align-self and order
   1. align-self <- align-items 와 유사
   2. order
      1. order: 0; <- default
5. wrap, nowrap, reverse, align-content
   1. wrap
      1. flex-wrap: nowrap; <- default
      2. flex-wrap: wrap;
         1. child의 크기 유지
   2. reverse
      1. flex-direction: row-reverse;
      2. flex-direction: column-reverse;
      3. flex-wrap: wrap-reverse;
   3. align-content
      1. justfy-content와 유사하지만 line(cross-axis)에 관한 것
      2. 줄사이 간격 지정
6. flex-grow, flex-shrink
   1. flex-shrink
      1. 여분의 공간이 없을 때 적용됨
      2. flex-shrink: 1; <- default
   2. flex-grow
      1. 여분의 공간이 있을 때 적용됨
      2. flex-grow: 0; <- default
7. flex-basis
   1. child에 적용되는 property
   2. initial size
   3. flex-direction에 따라 달라짐 -> main-axis에 적용됨
8. Flexbox Froggy 1-13
9. Flexbox Froggy 14-24

# GRID
1. Life Before Grid
2. CSS Grid Basic Concepts
   1. 바로 붙어있는 부모에 grid container 적용
   2. display: grid;
      1. grid-template-columns
      2. grid-template-rows
      3. column-gap
      4. row-gap
      5. gap
3. Grid Template Areas
   1. repeat(4, 200px)
   2. auto 200px
   3. grid-template-areas
      1. grid-area: "name";
4. Rows and Columns
   1. grid-column-start
   2. grid-column-end
   3. grid-row-start
   4. grid-row-end
5. Shortcuts
   1. grid-column: 1 / 5; = grid-column: 1 / -1; = grid-column: span 4;
   2. grid-row: 2 / 4;
6. Line Naming
7. Grid Template
   1. 1fr(=fraction) : 사용가능한 공간
8. Place Items
   1. justify-items
9.  Place Content
10. Auto Columns and Rows
11. minmax
12. auto-fit auto-fill
13. min-content max-content
14. Grid Garden part ONE
15. Grid Garden part TWO