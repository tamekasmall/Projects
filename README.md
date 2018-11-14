# Projects
bottle = 99

new_bottle = bottle

  while new_bottle.to_i != 0

  puts new_bottle.to_s + " bottles of beer on the wall"
  
  new_bottle = new_bottle - 1
  
  puts "take one away " + new_bottle.to_s + " bottles of beer on the wall."

end
