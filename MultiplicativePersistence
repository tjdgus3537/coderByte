def MultiplicativePersistence(num)
  
  count = 0
  
  while(num >= 10)
    count = count + 1
    temp = num
    save = 1
    while(temp >= 10)
      save = save * (temp % 10)
      temp = temp / 10
    end
    save = save * temp
    num = save
  end
  
  return count
         
end
