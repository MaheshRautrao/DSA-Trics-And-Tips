
You might think both the codes are working same but if you carefully see the second one is actually better performing as it compares left and right only once but in first 
left is checked twice;

      
       if(left && right) return root;
       else if(left) return left ;
       else return right;
       --------------------------------------
       if(!right) return left;
       else if(!left) return right;
       else return root;
      
