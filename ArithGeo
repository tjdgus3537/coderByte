def ArithGeo(arr)

  count = 1
  start = arr[0]
  flag = 0
  
  arr.each do |x|
    if(x != start * count)
      flag = 1
      break
    end

    count = count + 1
  end
  
  if(flag == 0)
    return "Arithmetic"
  end
  
  ratio = arr[1]/arr[0]
  count = 0
  before = 0
  
  arr.each do |x|
    if(count == 0)
      count = count + 1
    else
      if(x != before * ratio)
        flag = 2
        break
      end
    end 
    
    before = x
  end
  
    if(flag == 1)
      return "Geometric"
    end
    
    return -1
      
end
