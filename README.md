# switch
learn switch func
If you find yourself repeating else if statements in your code, where each condition is based on the same value, then it might be time to use a switch statement.

var month = 3;

switch(month) {
  case 1:
  case 3:
  case 5:
  case 7:
  case 8:
  case 10:
  case 12:
    days = 31;
    break;
  case 4:
  case 6:
  case 9:
  case 11:
    days = 30;
    break;
  case 2:
    days = 28;
}
