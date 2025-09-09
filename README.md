linear search :-
   ```java
   class Main {
    public static void main(String[] args) {
    int[] arr ={1,2,3,4,5};
    int target=3;
    int l=arr.length;
    int flag=0;
        for(int i=0;i<l;i++){
            if(arr[i] == target){
                 System.out.println(i);
            }else{
                  flag++;
                continue;
              
            }
        }
        if(flag == l){
            System.out.println("-1");
        }
     }
}
```

input : 1 2 3 4 5
       target : 3

output : 2
        
  
