# README
...or don't readme. It's your choice!

## UPCOMING
* Do the homework
* Next class is Tuesday @ 4pm

## ACTIVITY LOG

### Wednesday, April 10
Class @ 4pm

#### Class Notes
Course Overview
	first 4 weeks > learn ruby (vs rails) language, methods, classes
	weeks 5-10 rails framework
	weeks 10-15 personal rails projects
	week 16 - present personal project to ec mgmt
	week 17-23 customer drf
	week 24 - present to customer mgmt
You must put in the time > homework
ask lots of questions
read the docs
ruby is an open source language focused on simplicity and productivity
everything is an object (and as such has methods and properties)
docs at http://www.ruby-lang.org/en/
stack overflow is a thing
ruby is o-o
a hash is a key/value pair
=> is called a "hash rocket"
is ruby case sensitive? yes
if else
	if condition a
		#do something
	elsif condition b
		#do something else
	else
		#do this thing
	end

one-liner
	condition ? true : false
	rand(100).even? ? puts "it's even" : "it's odd" 
	^ syntax error lol
case statements
	case capacity
		when 0
			'you ran out of gas'
		when 1..20
			'tank almost empty'
		...
iterators
	users = ['User1','User2']
	users.each do |user|
		user.downcase
	end

	users.each_with_index do |index, user|
		...
operators
	% 	modulus
	** 	exponent
	<=>	???	
	...
variables
	globals
		$global_variable = 10 (not recommended)
	instance
		class Customer
			def i_am_a_method
				@customer_id = 1
			end
			def i_can_access_instance_vars
				puts @cust_id
			end
		end
	class variables
		similar to global
		class Customer
			@@ i_am_a_class_variable
			def a_method
			end
			...
	constant variables
		class Example
			VAR1 = 100
			VAR2 = 100
?? question: properties are stored using which variable type from above?
	answer: 
	follow-up question: how do you define get/set methods?
methods
	def method_name_1
		#do something
	end
	def method_name_2 (var1, var2)
		#do something
	end
	def method_name_3 (var1 = 'default value')
		#do something
	end
classes and methods
	class Customer
		def self.welcome_message
			"hi from the class method"
			# called via Customer.welcome_message
		end
		def welcome_message
			"hello from the instance message"
			# called via... 
			# customer = Customer.new
			# customer.welcome_message
		end
	end
exercism
	is an online platform designed to help you improve your coding skills through practice and mentorship
	url: https://exercism.io/tracks/ruby	
homework
	4 easy level exercises? exercisms?
?? questions
	what is a mixin
		answer: 
	what is a block
		answer: 
	which 4 are our homework
		answer: 
	where are slides available to review
		answer: 
testing and ruby go hand-in-hand

### Tuesday, April 9
Made it three pages into https://www.ruby-lang.org/en/documentation/quickstart/ 

### Monday April 8
1. Installed VirtualBox
2. Created an Ubuntu 18.10 VirtualBox Appliance (see :Rails Install Notes section below)
3. Installed Ruby On Rails using these instructions https://gorails.com/setup/ubuntu/18.10 

#### Rails Install Notes
* when using the gorails instructions, copy and paste each line and watch carefully for errors.  resolve them before you go onto copying and pasting the next line
* install locked up on rbenv, so I went with the rvm instructions
* don't remember how I resolved the "you must use bundler 2 or greater with this lockfile" issue (when creating myapp)
* created app using command rails new myapp -d postgresql

## MISCELLANEOUS

### Git
* https://kbroman.org/github_tutorial/pages/init.html

### Linux
	commands
		touch	
			creates a file
		example
			touch a_file.rb
			(creates empty file a_file.rb)

## Do Not Read This Section
* you didn't listen

