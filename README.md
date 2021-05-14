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
6. flex-grow, flex-shrink
   1. flex-shrink
      1. 여분의 공간이 없을 때 적용됨
      2. flex-shrink: 1; <- default
   2. flex-grow
      1. 여분의 공간이 있을 때 적용됨
      2. flex-grow: 0; <- default
7. flex-basis
8. Flexbox Froggy 1-13
9. Flexbox Froggy 14-24

# GRID