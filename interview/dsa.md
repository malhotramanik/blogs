1. Design a Data structure with insert delete and getRandom().
Time complexity for all funs should be O(1)

**Its not the answer though**
```
class Operations{
    val map:HashMap<Int,Int> = HashMap()
    
    val arr:ArrayList<Int> = ArrayList()
    
    fun insert(value:Int){
        arr.add(value)
        val index=arr.size-1
        map.put(value, index)
    }
    
    fun delete(value:Int)
    {
        val index:Int=map.get(value)!!
        
        val temp=arr[arr.size-1]
        arr[arr.size-1]=arr[index]
        arr[index]=temp
        
        val tempMap =  
        
        map.remove(value)
        arr.removeAt(index)
        
    }
    
    fun random(){
        var index= random() 0 to arr.size
        return arr.get(index)
    }
}

// insert(10)
//insert(20)
//insert(30)

//delete(20)

// getRandom() => 10
// getRandom() => 10/30
```
