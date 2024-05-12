# LemonSort
```
function lemonSort(arr:number[]){
    let arr1 =new Array(arr.length)
    for(let i =0;i<arr.length;i++){
       if(arr1[arr[i]]!=null){
        arr1[arr[i]+1] = arr[i]
        continue
       }
        arr1[arr[i]] = arr[i]
      
    }
    console.log(arr1)
    let j =0
    for(let i = 0;i<arr1.length;i++){
        if(arr1[i] != null){
            arr[j] = arr1[i]
            j++
        }
    }
    
    return arr
}
```
