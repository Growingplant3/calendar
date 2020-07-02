# calendar
閏年のルール<br>
西暦が4で割り切れる年は閏年である。<br>
year % 4 == 0 が true<br>
ただし、100で割り切れる年は閏年ではない。<br>
year % 100 == 0 が false<br>
ただし、400で割り切れる年は閏年である。<br>
year % 400 == 0 が true