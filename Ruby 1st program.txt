print "What's your first name?" 
first_name = gets.chomp
print "What's your last name?"
last_name = gets.chomp
print "What city are you from?"
city = gets.chomp
print "What state are you from? (please abbreviate for example NY)"
state = gets.chomp

puts "Your name is #{first_name.capitalize!}, your last name is #{last_name.capitalize!}, you're from #{city.capitalize!}, and you're state is #{state.upcase!}"


