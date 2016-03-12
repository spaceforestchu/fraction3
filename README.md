# fraction3

    function fraction3(num){
        if(num === 95){
      
            return 1/(num*(num+2));
      
        } else {
    
               return fraction3(num + 4 ) + 1/(num * (num + 2));
          
        }
    }
    
    fraction3(3);
