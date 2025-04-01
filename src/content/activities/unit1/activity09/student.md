Implementando un ciclo simple

```
@0        
D=A       
@12      
M=D       

@1        
D=A       
@13       
M=D       

(LOOP)    
@13       
D=M       
@6       
D-A       
@END      
D;JEQ     

@12       
M=M+D     

@13       
M=M+1     

@LOOP     
0;JMP    

(END)     
@END      
0;JMP    

```

