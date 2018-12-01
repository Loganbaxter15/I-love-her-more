print "Sweetie, write a sentence please:"
sentence = gets.chomp
sentence.downcase!

if sentence.include? "i love logan"
  sentence.gsub!(/i love logan/, "Logan Loves me more!")
else
 puts "Logan loves me more!"
end

puts "#{sentence}"
