# FCC-code
This is to keep track of my Free Code Camp exercices.


===== This is the counting cards exercice ==== 

function cc(card) {

  // Only change code below this line
  
  switch(card) {
  
    case 2:
    
    case 3:
    
    case 4:
    
    case 5:
    
    case 6:
    
     count ++;
     
      break;
      
    case 7:
    
    case 8:
    
    case 9:
    
      count = count;
      
      break;
      
    default:
    
      count --;
      
  }
  
  return count + (count > 0 ? " Bet" : " Hold");
