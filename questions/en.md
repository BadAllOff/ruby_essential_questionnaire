1. [Demonstrate two ways to create an empty hash](#answer-1)
2. [Build a hash with two symbols as keys that each have different strings as values](#answer-2)
3. [Demonstrate how to pass a key into a hash](#answer-3)
4. [What is returned if you pass a key that doesnt exist into a hash?](#answer-4)
5. [Demonstrate how to change the value assoc with a key in a hash](#answer-5)
6. [Are hashes ordered? Does it matter order of Keys and Pairs?](#answer-6)
7. [How would you return all the keys in a hash?](#answer-7)
8. [These keys that are returned... what is their class?](#answer-8)
9. [How do you see if a key is in a hash?](#answer-9)
10. [How do you return all the values from a hash?](#answer-10)
11. [How would you merge one hash into another hash?](#answer-11)
12. [How would you add a key value pair to an existing hash?](#answer-12)
13. [Are these both strings "one" ... 'one'](#answer-13)
14. [Make a string with quotes inside the string... in a couple ways](#answer-14)
15. [Why would you use double or single quotes?](#answer-15)
16. [What are some common escape characters and how do you escape them?](#answer-16)
17. [How do you use flexible quotes to not have to worry about the above? i.e. this is a great way to create a string](#answer-17)
18. [flexible quotes with the delimiter can be used to handle newlines ... demonstrate...](#answer-18)
19. [What is a here document? describe and create one in ruby](#answer-19)
20. [What operator will concatenate 2 strings? Does it leave the strings in place?](#answer-20)
21. [Demonstrate how to concatenate to the end of a string](#answer-21)
22. [What is the shovel operator and what does it do for strings?](#answer-22)
23. [What is the difference between += and << ?](#answer-23)
24. [What is the output? "\n".size What is "\t"?](#answer-24)
25. [can you escape characters in a ' ' single quote?](#answer-25)
26. [How do you interpolate into a string?](#answer-26)
27. [Show two ways to get the 4th - 6th letters out of "One is less than two" *ruby1.9 see below question too](#answer-27)
28. [tell me about how this is different in 1.8 and 1.9 ... x = string\[1\] how do you get what you *usually* want here in 1.8](#answer-28)
29. [How would you split this string? "One two three" what do you get back when split?](#answer-29)
30. [Show how you would split with a reg expression](#answer-30)
31. [Use split and join on strings/array. Is join valid on strings? What does join do to an array? what does it do to a string?](#answer-31)
32. [a = "one" b = "one" .. does a == b? does a.object_id == b.object_id? What does == usually evalutate for](#answer-32)
33. [Is nil an object?](#answer-33)
34. [nil.nil? returns?](#answer-34)
35. [nil.to_s returns?](#answer-35)
36. [nil.inspect returns?](#answer-36)
37. [describe the is_a? function.](#answer-37)
38. [one = :symbol1 ... two = :symbol1 ... are one and two the same object?](#answer-38)
39. [Discuss method names and their relationship to symbols](#answer-39)
40. [Discuss Constants and their relationship to symbols](#answer-40)
41. [is :symb == :"symb"? or :name = :"name"](#answer-41)
42. [Ruby Symbols can never be garbage collected? is this true in 1.9?](#answer-42)
43. [How can you make a string into a symbol?](#answer-43)
44. [build a symbol that has spaces in it.](#answer-44)
45. [build a symbol with interpolation](#answer-45)
46. [What happens when you pass in a symbol to interpolated string?](#answer-46)
47. [What is the class of a Regular Expression?](#answer-47)
48. [Show two ways how you can match a string against a reg expression.. show...](#answer-48)
49. [What is returned when you get a match? no match?](#answer-49)
50. [What do the following do in Regexp?](#answer-50)

     \?
     
     \+
     
     \*
     
     \|
     
     \[\]
     
     \\d (say "backslash d")
     
     \\s (say "backslash s")
     
     \\w backslash w
     
     \.
     
     \\A backslash capital A
     
     \\Z backslash captial Z vs \z
     
     \^
     
     \$
51. [What is greedy matching?](#answer-51)
52. [If more than one match what gets returned?](#answer-52)
53. [What is this called /? ... what is this called \?](#answer-53)
54. [Demonstrate a range match in Regexp](#answer-54)
55. [Give an example of negating a character class](#answer-55)
56. [How do you get the negative of the characer classes?](#answer-56)
57. [How would you return a group of results in an array?](#answer-57)
58. [How can you take a string and return an array with all the words in it?](#answer-58)
59. [what does sub method do on a string?](#answer-59)
60. [gsub?](#answer-60)
61. [Talk about global methods](#answer-61)
62. [What kind of Runtime Error is called when you call a method with wrong number of arguments?](#answer-62)
63. [Demonstrate how to define a method with default argument values](#answer-63)
64. [Demonstrate how to define a method that takes a variable amount of arguments](#answer-64)
65. [if nothing is passed into a method with a variable arg, what is the value of that arg in the method?](#answer-65)
66. [How to you specify a return value in a method? what if you do not specify a return value?](#answer-66)
67. [Show two ways to call a method defined in the same class as the method you are in now.](#answer-67)
68. [define a private method in a class](#answer-68)
69. [talk about if you can call a private method from within another method of that class. How can you not call it?](#answer-69)
70. [How do you declare a top level constant? How can you reference it?](#answer-70)
71. [What about declaring constants in a class and referencing them?](#answer-71)
72. [Do Nested classes inherit constant values?](#answer-72)
73. [Do subclasses inherit constants from parent classes?](#answer-73)
74. [If in nested class ... and ...Constant declared in both the parent class and in the inherited class which would win?](#answer-74)
75. [Describe static(lexical) scoping and dynamic scoping.](#answer-75)
76. [What kind of statements return a value in Ruby?](#answer-76)
77. [Write an if then else in Ruby](#answer-77)
78. [Write an if then else in ruby that assigns a value to a variable. What if the result of a if then statement does not assign a value? What is returned?](#answer-78)
79. [Assign a value with a condition operator](#answer-79)
80. [assign a value with a statement modifier](#answer-80)
81. [write an unless statement](#answer-81)
82. [write a while statement](#answer-82)
83. [write a break statement in a loop, does it stop the whole loop?](#answer-83)
84. [write a next statement](#answer-84)
85. [write a for statement](#answer-85)

    85b.[ All of the above. do these change the current scope? do they pull in local variables? if you change these local vars do they change afger the while/unles/for stuff](#answer-85b)
86. [What are the things that evaluate to false when put into a conditon statement?](#answer-86)
87. [What does require do? demonstrate its call](#answer-87)
88. [What does the Class method ancestors do when called?](#answer-88)
89. [Talk about the exception class tree.](#answer-89)
90. [Write a rescue clause. Does a rescue have to be in a begin / end clause?](#answer-90)
91. [What does method .. fail ... do?](#answer-91)
92. [If an error is a RuntimeError is it also a StandardError?](#answer-92)
93. [What is a synonym for fail?](#answer-93)
94. [How could you define and raise your own exception you defined?](#answer-94)
95. [What class is all this assert_equal and assert_raise stuff in... what is it>](#answer-95)
96. [Can each method use do end and { } ?](#answer-96)
97. [What does map do on an array? what is a synonym for it?](#answer-97)
98. [What can you do to find all the matching elements in an array... how do you implement?](#answer-98)
99. [What is another name for this above method?](#answer-99)
100. [What method will get the first match in an array?](#answer-100)
101. [What does inject do? What "traditionally returns an array and what traditionally just returns a number?"](#answer-101)
102. [Is a range a collection that can be used with methods like map?](#answer-102)
103. [What does this do? File.open("example_file.txt") do |file|](#answer-103)
104. [Demonstrate how to pass a block into a method... describe what is going on](#answer-104)
105. [Can you call yield multiple times on a block?](#answer-105)
106. [How can you check if a method was called with a block?](#answer-106)
107. [Show how you can assign a block to a variable, can you pass in two lambdas to a method and never use a &?](#answer-107)
108. [Show another way to call a code block other than .. add_one.call(10)](#answer-108)
109. [How would you pass in a code block (lambda) to a method expecting a code block?](#answer-109)
110. [how would you define a method that explicitly takes a code block? what if you explicity define a code block and don't pass in a block?](#answer-110)
111. [Demonstrate 5 ways to do a loop from 1 .. 10 that prints the number.. not zero!](#answer-111)
112. [Describe the differences between using lambda and Proc.new? What is shorthand for Proc.new?
do some examples of the above.](#answer-112)
113. [Define a struct in ruby](#answer-113)
114. [Why might you use a Struct instead of a Hash?](#answer-114)
115. [What is a Binding object and how do you use it... how do you get a binding?](#answer-115)
116. [How do you comment out a line of code?](#answer-116)
117. [How do you comment out a block of code?](#answer-117)
118. [What is a bad way to ask for instance variable values in a class... show two ways?](#answer-118)
119. [Show how to create accessor methods to_return instance variables](#answer-119)
120. [What is the good way to get read access to a instance variable?](#answer-120)
121. [What is the good way to get read / write access to an instance variable?](#answer-121)
122. [What is a good way to initialize a lot of instance variables when creating an object?](#answer-122)
123. [if a method returned self what is it returning?](#answer-123)
124. [what method defined in all Ruby objects is called when you do string interpolation and in that have an object? e.g. "hello and #{object_name}"](#answer-124)
125. [What will inspect do on an object?](#answer-125)
126. [Can you re open an existing ruby class? How do you do it?](#answer-126)
127. [How would you check if a class had inherited from another class... ie the class has another class as a parent...?](#answer-127)
128. [What do all classes ultimately inherit from?](#answer-128)
129. [rand(6) returns values between x and y.. fill in x and y](#answer-129)
130. [Why can't you call method 'ancestors' on an object created by a call to Dog.new e.g. chico = Dog.new("Chico") .... you can not say chico.ancestors.include?(Dog) why?](#answer-130)
131. [if you try to call an undefined method on an object what Exception will be thrown?](#answer-131)
132. [Why do you do subclasses in general?](#answer-132)
133. [How can a subclass also get the functionality of the parent class when it overrides a method in the parent class?](#answer-133)
134. [can you call super 'cross method'? i.e. can you be in method "growl" in the subclass and call super.bark to try to get the functionality from the SuperClass method "bark"](#answer-134)
135. [What kind of Exception will you get from the above?](#answer-135)
136. [describe assert_raise and give an example](#answer-136)
137. [How do you define a module?](#answer-137)
138. [Can you instantiate a module?](#answer-138)
139. [How do you get a module's functionality into a class?](#answer-139)
140. [What is a good catchall in Unit::Test that will assert that no Exceptions thrown?](#answer-140)
141. [Can a module method affect an instance variable in the class that includes it?](#answer-141)
142. [if a class that includes a module adds a method that is also in the module which one wins?](#answer-142)
143. [Are class names really just constants?](#answer-143)
144. [How can you reference nested classes?](#answer-144)
145. [If you define a nested class called String does this have normal string methods with it?](#answer-145)
146. [When you say something like ::String what is going on?](#answer-146)
147. [which is right .... class dog ... Class dog ... class Dog ...or... Class Dog](#answer-147)
148. [is it True or true?](#answer-148)
149. [What effect does this have ... MyString = ::String](#answer-149)
150. [what does method const_get do? Where is const_get located?](#answer-150)
151. [How can you get a list of constants for a class?](#answer-151)
152. [How would you test if something is an Object?](#answer-152)
153. [Is something that is defined as a class an object? class Dog ... does this respond true to Dog.is_a?(Object)](#answer-153)
154. [How can you define a method on an individual object? What is this called? Show THREE ways to do it!!!](#answer-154)
155. [Are other objects of this class affected by these singleton methods?](#answer-155)
156. [Show 4 ways to define a class level method](#answer-156)
157. [Can you define two methods with the same name ... one an instance level method the other a class level method?](#answer-157)
158. [Do classes and instances share variables?](#answer-158)
159. [if you have a class statement what is returned? e.g. statement = class Dog ..... end](#answer-159)
160. [if you return self in a class statement what is returned?](#answer-160)
161. [If you have an instance of a class... \[say\] fido and want to call a class level method from this instance variable how can you do it?](#answer-161)
162. [Describe what this is doing ... class AboutMessagePassing < EdgeCase::Koan](#answer-162)
163. [So if you have an object and want to call one of its methods what are 2 ways to do it? Which one is used in something like metaprogramming?](#answer-163)
164. [Give some examples of dynamic ways to send an object a message](#answer-164)
165. [What is another way to call the send method and why could it be good?](#answer-165)
166. [How can you check if an object knows how to handle to a message?](#answer-166)
167. [show the two ways you can call an instance method passing in an array of args of unknown size](#answer-167)
168. [What is method_missing and how do you define it?](#answer-168)
169. [Describe the relationship between respond_to? and a class where method_missing is defined.](#answer-169)
170. [How can you make method_missing handle some messages and not handle other messages? talk about what you might do with respond_to? here also](#answer-170)
171. [talk about a forward proxy and reverse proxy](#answer-171)
172. [What is ⌘ ...and ... ⌥ ... and ... ⇆ .... and ⇧](#answer-172)
173. [What are some differences between blocks formed with { } and do ... end](#answer-173)
174. [When you have bark(arg1,arg2) do |x,y|
... code ...
end 
show an example of how you would call this...](#answer-174)
175. [Give an example of a Class method that is always created with every object](#answer-175)
176. [class File has a lot of class methods. What is an instance of class file though?](#answer-176)
177. [describe and implement the singleton pattern where you are creating a logging object and only one is ever created.](#answer-177)
178. [describe the pattern where you use class methods \[say\] to reopen the class and provide a new way to initialize it](#answer-178)
179. [If you pass in an object to another object of same class how can you access the passed in objects instance variables?](#answer-179)
180. [discuss obj.clone](#answer-180)
181. [What is the constant that gives you the ruby version you are using?](#answer-181)
182. [What is Ruby's top level self?](#answer-182)
183. [Are top level methods private? protected? or Public?](#answer-183)
184. [One of his main points was that in Ruby you are always sending a message to an object. If you don't explicitly say which object you want to send the message to, Ruby sends it to self. Is this true?](#answer-184)
185. [If a program wants to use a module how does it do that?](#answer-185)
186. [what is the . operator do?](#answer-186)
187. [Can you use . and :: interchangeabley when calling a method on an object instance?](#answer-187)
188. [What does p do?](#answer-188)
189. [Talk about how Modules define a namespace and how you use the scope operator to access things in the module.](#answer-189)
190. [How does ruby implememnt multiple inheritance?](#answer-190)
191. [how do you mixin a module to a class to make the module methods available as instance methods?](#answer-191)
192. [do you need to use require with include?](#answer-192)
193. [How do you use the Comparable mixin?](#answer-193)
194. [What is the Enumerable module?](#answer-194)
195. [write a class that includes Enumerable and Comparable](#answer-195)
196. [What is the operator that checks if something is defined and if it is returns it... otherwise it evaluates and returns the right side ... and remember it will create that variable because before it was undefined](#answer-196)
197. [how will ruby look up method names between, class, superclass, multiple modules?](#answer-197)
198. [what is the difference between load and require](#answer-198)
199. [Talk about the scope of variables and methods in a file that was loaded or required](#answer-199)
200. [Can you do an include Classname within another class?](#answer-200)
201. [What is this statement doing? x = Stuff::T.new](#answer-201)
202. [Can you define a method initialize in a module?](#answer-202)
203. [What is the difference between include, require, and load](#answer-203)
204. [Can you define two methods that accept different amount of args that Ruby will determine which one to use based on arg list?](#answer-204)
205. [can you say attr_accessor :purchases ... if purchases is a class level variable?](#answer-205)
206. [Can a subclass access a private method in the parent class?](#answer-206)
207. [Does x = [] x\[9999\] << "Hello" create a huge array?](#answer-207)
208. [Talk about 2 ways to do a deep copy of an object](#answer-208)
209. [What kind of objects can't be Marshaled](#answer-209)
210. [Show an example of parallel assignment in Ruby](#answer-210)
211. [Describe this parallel assignment](#answer-211)
212. [Describe and & , or ||, ! not, which has lower precedence of the pairs](#answer-212)
213. [How can you check if something has been defined in your program](#answer-213)
214. [What is the regular expression pattern match operator and negation of that? What does it return. What is difference between that and match method?](#answer-214)
215. [what is the difference between shape.eql?(obj) and shape.equal?(obj)](#answer-215)
216. [How do you define a global Ruby variable? Name 2 special ruby global variables](#answer-216)
217. [write an exception that saves the exception object to a variable, and handles two exception types](#answer-217)
218. [describe the === operator](#answer-218)
219. [describe else in a resuce clause](#answer-219)
220. [talk about all the pieces in a rescue clause... and then talk about a rescue statement modifier](#answer-220)
221. [talk about retry](#answer-221)
222. [Why would you put raise in a rescue clause?](#answer-222)
223. [if you just put a raise statement what happens?](#answer-223)
224. [What happens with a raise "Error message here"](#answer-224)
225. [What happens with raise ArgumentError, "Message", caller\[1..-1\]](#answer-225)
226. [Describe and write a catch / throw](#answer-226)
227. [use the ? : statement](#answer-227)
228. [Give 3 examples of classes and modules that are automatically built in](#answer-228)
229. [In Ruby syntax how are expressions and statements termintated?](#answer-229)
230. [How can you continue an expression on the next line?](#answer-230)
231. [What are BEGIN and END ? write some](#answer-231)
232. [Describe generalized delimited input](#answer-232)
233. [What are the basic types in Ruby?](#answer-233)
234. [can you make a here document anywhere?](#answer-234)
235. [Describe the convention of capitals in constants AND class names and modules](#answer-235)
236. [Talk about false and nil ... as in thier names. describe how to create a singleton class like these where only 1 object per class can be created](#answer-236)
237. [does FALSE = false? TRUE = true and NIL = nil?](#answer-237)
238. [What is the name of the current file constant? current line constant?](#answer-238)
239. [What responds true to object.nil?](#answer-239)
240. [Can you define a Constant in a method?](#answer-240)
241. [Do you have to initialize class variables before use?](#answer-241)
242. [Describe class variables defined at the top level](#answer-242)
243. [Are class variables shared by children of the class they are defined in?](#answer-243)
244. [Are instance variables available to class methods?](#answer-244)
245. [Does a block take on the set of local variables in existance when the block is created?](#answer-245)
246. [What are some examples of pre-defined r/o read only variables in ruby?](#answer-246)
247. [How can you define a shell command](#answer-247)
248. [can you use the scope operator to get a local variable or instance variable out of a class?](#answer-248)
249. [How are ruby's comparison methods implemented?](#answer-249)
250. [what can you use instead of the keyword "then"?](#answer-250)
251. [Describe the two case statements](#answer-251)
252. [Describe a definition (def) with an unadorned method name outside a class or module definition](#answer-252)
253. [Can a method argument list reference an argument that precedes it in the argument list?](#answer-253)
254. [Can you pass a block to any method?](#answer-254)
255. [Describe the order and things that can be passed into a method](#answer-255)
256. [What if you do not indicate a reciever for a message.. ie calling a method](#answer-256)
257. [What does calling super do? and talk about parameters with this call](#answer-257)
258. [if an operator is redefinable what does it look like method wise...](#answer-258)
259. [what does this def do?](#answer-259)
    ```ruby
    def attr=(val)
    ...
    end
    ```
260. [What is aliasing?](#answer-260)
261. [can you alias instance variables? local variables? class variables? constants?](#answer-261)
262. [what is done when you \[say\] include in a class definition? what happens when you write "include"](#answer-262)
263. [what happens if you overide new?](#answer-263)
264. [what does module_function :sin .... do when written in a module?](#answer-264)
265. [what is a closure?](#answer-265)
266. [what has higher precedence? do .. end or {}](#answer-266)
267. [describe the 3 places an exception can be handled](#answer-267)
268. [is the condition ? return value : other return value good for long if then / else things?](#answer-268)
269. [Can you have more than one method paramenter with a & .... explain](#answer-269)
270. [Can you pass in a &name and a code block to a method?](#answer-270)
271. [Can you pass in two code blocks to a method?](#answer-271)
272. [if you pass in a lambda that needs to be the "block" thus responding to block_given describe how you pass that in.](#answer-272)
273. [if you pass in a block of code without &'s' will that be a "block" of code ...responding to block_given?](#answer-273)
274. [Can you call Proc.new .... just like that... nothing else?](#answer-274)
275. [What is another way to say Proc.new](#answer-275)
276. [How do you execute a method on an object dynamically at runtime?](#answer-276)
277. [in each with index you pass in two parameters which is which?](#answer-277)
278. [What are the 4 evals? and what are the differences](#answer-278)
279. [How do you create Binding objects? Where is the binding function located?](#answer-279)
280. [What are binding objects?](#answer-280)
281. [Describe the two method objects you can create](#answer-281)
282. [what does unbind do?](#answer-282)
283. [how do you create a Method object and an UnboundMethod object?](#answer-283)
284. [What does class_eval do?](#answer-284)
285. [what does instance_eval do? x.instance_eval or Object.instance_eval { ..block..}](#answer-285)
286. [What has higher precedence? {} or do/end. What other differnces are there between the two?](#answer-286)
287. [What is prefered in Ruby generally Proc.new or proc or lambda? is proc = lambda?](#answer-287)
288. [how can you run an external process (it replaces the current process)](#answer-288)
289. [What is the best way to define a class method self.meth_name or ClassName.meth_name? why?](#answer-289)
290. [What does "inherited" method do... explain it.](#answer-290)
291. [What are the 3 types of conversion performed by the interpreter. Describe each.](#answer-291)
292. [Ruby objects have three components, name them.](#answer-292)
293. [What does this code do (x is a variable) class << x ... what is another way to do this?](#answer-293)
294. [When you do the above what happens as far as class structure?](#answer-294)
295. [String is an instance of what class?](#answer-295)
296. [talk about defining a singleton method on String....and how it is the same as a defining a singleton method variable x which is of class Person](#answer-296)
```ruby
    def String.say_hi; end
    
    def x.say_hi
    #..code.. ...code...
    end 
```
297. [Describe obj.extend(<mod.+)](#answer-297)
298. [When a class includes a module describe what happens as far as how they link together.](#answer-298)
299. [What is the difference between calling include ModuleName and extend ModuleName in a class definition?](#answer-299)
300. [When a class definition is executed ... talk about the value off self.class](#answer-300)
301. [When a class definitoin is executed... talk about the value of self.name](#answer-301)
302. [Can you define two methods with the same name... one a class method, the other an instance method?](#answer-302)
303. [While a class definition is being executed talk about the methods available to it](#answer-303)
304. [talk about how attr_accessor works](#answer-304)
305. [What does attr do in a class?](#answer-305)
306. [Talk about class instance variables and object instance variables.](#answer-306)
307. [How can you add functionality to when classes and modules are defined?](#answer-307)
308. [Can you use Ruby's keywords as variables? what about method names?](#answer-308)
309. [Can you include a class in another class?](#answer-309)
310. [If a class Dog < Animal ... and Animal has class methods... such as Animal.make_noise ... can you also say Dog.make_noise](#answer-310)
311. [When you execute a class method you are sending a message to the ____ object itself](#answer-311)
312. [What happens when you define methods at the top level](#answer-312)
313. [How can you change the visibility of a method in subclass from that of its parent class ie a_method is private in parent but public in subclasses](#answer-313)
314. [How can you iterate over all the objects in your program?... well not all... which objects are not in there?](#answer-314)
315. [How can you get a list of all superclasses of a class? how can you get a list of all the classes and modules?](#answer-315)
316. [when you have class Dog ... end and in your code you later say Dog.private_instance_methods(false) to get a list of the private instance methods... describe where this method is and how it was found](#answer-316)
317. [What are all the ruby keywords](#answer-317)
318. [Talk about the difference between alias and alias_method](#answer-318)
319. [In a Hash is the key :one the same as "one"?](#answer-319)
320. [When you have xx = String.new("Cat") yy = String.new("Cat") how is it that xx == yy ... they are different objects...](#answer-320)
321. [Give 3 examples of operators that can be overriden and 3 examples of operators that connot be... how is it that they can be overridden?](#answer-321)
322. [How can you erase all the keys and values in a hash?](#answer-322)
323. [how can you iterate over all the key/values in a hash and how can you iterate through each key.. or each value](#answer-323)
324. [Describe what is going on when a class definition is first encountered by the parser. What happens to @@vars ... what about the logic in the class statement that is not in "def's" is this stuff just executed once when the parser goes through?](#answer-324)
325. [Describe and diagram the ruby class / object model](#answer-325)
326. [Talk about the * operator and passing in variable args... most specifically the case when you pass in an array to a method that catches *args ... not args](#answer-326)
327. [Talk about what things are propogated into current scope in a required file](#answer-327)
328. [What does -cw do when you do ruby -cw prog.rb -v? --version? -e?](#answer-328)
329. [How would you get a line of input from the the keyboard? How would you read the lines of a file?](#answer-329)
330. [How can you get a lot of ruby config info? for example where is Ruby's executable files?](#answer-330)
331. [what is the standard library](#answer-331)
332. [Name a couple of files that have some standard library facilities that are in Config::CONFIG\["rubylibdir"\]... you may require these files to get some additional functionality](#answer-332)
333. [Talk about the terms library and extension](#answer-333)
334. [What is the global variable that has ruby's load path's stored?](#answer-334)
335. [How do you start an irb session? what if you have a file with all kinds of classes and stuff that you want in memory during your irb session?](#answer-335)
336. [What is RDoc and ri](#answer-336)
337. [What are # and :: in ri referencing?](#answer-337)
338. [Very simply what does rake do?](#answer-338)
339. [Write a loop statement](#answer-339)
340. [Use while and until as statement modifiers and use each at the begining and end of a loop construct.](#answer-340)
341. [talk about defining a namespace and a task in rake](#answer-341)
342. [what do you use to describe a namespace and task in Rake?](#answer-342)
343. [how can you see all the tasks defined in a Rakefile?](#answer-343)
344. [What is RubyGems?](#answer-344)
345. [What is the extension on gem files?](#answer-345)
346. [Describe where the 'gem' command will look for gems](#answer-346)
347. [what command line option can you give to gem to make it just look locally](#answer-347)
348. [does encountering a return in method halt the method?](#answer-348)
349. [What 2 ways can you get an object to call a private method?](#answer-349)
350. [How can you be sure you are only calling public methods on an object?](#answer-350)
351. [the *arg in a method definition is a sponge type argument... describe what this means and how vars in the parameters are assigned](#answer-351)
352. [do variables in Ruby hold values?](#answer-352)
353. [talk about clone and dup in relation to freeze method](#answer-353)
354. [What is the new method? is there a singleton new method and and instance new method?](#answer-354)
355. [if you have unassigned \[say\] local variables in a method definition will that be caught during the parse?](#answer-355)
356. [What can self be?](#answer-356)
357. [Describe the relationship between singleton methods and class methods](#answer-357)
358. [Show what it looks like to print out self for an instance of a class... what does it look like to print out the class object?](#answer-358)
359. [If you have a variable and a method named the same thing(not smart) and you write that variable / method in your code what wins? and Why?](#answer-359)
360. [name a case when you have to indicate self even when calling an instance method on an object.](#answer-360)
361. [What are the 3 types of variables?](#answer-361)
362. [How can you get the 'friendlier' version of global variables in use? instead of all the $: and $! stuff?](#answer-362)
363. [Do subclasses and parents share the same class variables?](#answer-363)
364. [What can not take an explicit reciever? what is the one exception?](#answer-364)
365. [What are top level methods?](#answer-365)
366. [Why can top level methods be called from anywhere?](#answer-366)
367. [talk about this code... notice x will never be assigned a value](#answer-367)

    ```ruby
    if false
    x = 99
    end
    
    puts x
    ```
368. [What comparison operator is used in the when part of case statements](#answer-368)
369. [How can you do a repeat until loop in ruby?](#answer-369)
370. [looping and an iterator are a bit different terms... what is an iterator?](#answer-370)
371. [when you create a block for a method call ... do you have access to the local variables created before the block was made?](#answer-371)
372. [when creating a block how can you make sure you have varibales that are local to the block scope and do not "pull" in variables from the outside, and possibly change them](#answer-372)
373. [if you create a local variable in the block will it be available outside the block?](#answer-373)
374. [can you use rescue without anything after it?](#answer-374)
375. [talk about using a resuce in a method or code block...](#answer-375)
376. [Is ensure clause run even if an exception is not raised?](#answer-376)
377. [What are the literal constructors for String.new ... Symbol.new ... Array .. Hash, Range, Regexp, Proc (lambda)](#answer-377)
378. [x = 1 + 2 is sytactic sugar ... how is it written verbosely?](#answer-378)
379. [How do you get modulus?](#answer-379)
380. [can your class define ! .... what does ! typically denote?](#answer-380)
381. [What is the splat operator? what does it do?](#answer-381)
382. [what happens with the following code?](#answer-382)

    ```ruby
    x = "We are number"
    y = 3
    puts x + y
    ```
383. [What is called when you try to do something like "Dog" + 9 ... does it work?](#answer-383)
384. [Describe evaluating a local variable that isnt initalized and an instance variable that isnt initialized](#answer-384)
385. [what happens if you try to access a nonexistnat element of a container or collection object?](#answer-385)
386. [list some valuble string methods](#answer-386)
387. [How do you find Ruby's encoding? what is the default?](#answer-387)
388. [Write a hash with symbols as keys without the => notation](#answer-388)
389. [what two libraries do you need to do date and time stuff?](#answer-389)
390. [show how to get a Date object from a string](#answer-390)
391. [What is different about hashes in Ruby 1.9?](#answer-391)
392. [Show how to iterate through a hash with an index](#answer-392)
393. [what are the Array and String methods?](#answer-393)
394. [What does passing in 2 arguments do within the array literal? e.g. array\[3,2\]](#answer-394)
395. [How do you add an element (or more) to the beginning of an array / take away first element? the end (add and take away)?](#answer-395)
396. [How can you get default values for a Hash when there is NO MATCH? talk about adding a block to the end of the call to new](#answer-396)
397. [Show two ways to create a range... also what is difference between 2 and 3 dots](#answer-397)
398. [What is the difference between #include and #cover for a range?](#answer-398)
399. [How do you use a set? What is it?](#answer-399)
400. [What are IO objects of IO class...?](#answer-400)
401. [What are the IO constants that are automatically set when a program starts?](#answer-401)
402. [What is the global var for the global input record seperator ?](#answer-402)
403. [Explain how you would change the standard output to say a file instead of the screen...](#answer-403)
404. [Every object has two classes... name them](#answer-404)
405. [How do you get inside the definition body of a singleton class?](#answer-405)
406. [Singleton classes of class objects sometimes called?](#answer-406)
407. [what is a special behavior of singleton methods of Class objects?](#answer-407)
408. [What does the tap method do? what objects is it available for?](#answer-408)
409. [How can you modify a method so that additional functionality is added to it... it is called a passthrough...](#answer-409)
410. [How can you open up the singleton of an object to add methods without the class << obj type of thing?](#answer-410)
411. [How do you create and call a new Proc object? 1.9](#answer-411)
412. [what does the proc method and lambda method do? 1.9](#answer-412)
413. [when you supply a code block to a method are you in fact sending a Proc object?](#answer-413)
414. [if you have a &block_var in your methods definition argument list and you pass in a block... does this create a Proc object?](#answer-414)
415. [if when calling a method you have a proc (Proc object) that you want to use as the code block ... how do you tell the method that you want this proc (Proc object) to be the methods code block?](#answer-415)
416. [Do code blocks preserve the variables that were in existence at the time they were created?](#answer-416)
417. [can you call a proc with the wrong number of arguments?](#answer-417)
418. [What is the difference between lambda and proc's creation of Proc objects?](#answer-418)
419. [How can you get a bound method? what is it?](#answer-419)
420. [How can you get an unbound method... and then how can you bind it?](#answer-420)
421. [If you have class B < A ... and .. you have an initialize method in A (the superclass) but not in B.. and you do a x = B.new ... does the superclass initialize method get run?](#answer-421)
422. [What is $SAFE](#answer-422)
423. [How can you pry open an instance and execute statements as if you were inside that instance?... thus you do change 'self'](#answer-423)
424. [What is the difference between instance_eval and instance_exec?](#answer-424)
425. [What will class_eval do?](#answer-425)
426. [what does define_method do? how is it useful](#answer-426)
427. [How do you implement a thread?](#answer-427)
428. [if your program terminates with a thread still running what happens to it? How can you make sure it keeps running?](#answer-428)
429. [What is a fiber?](#answer-429)
430. [How do you return from a fiber to the calling context?](#answer-430)
431. [How can you get a socket listening on a port?](#answer-431)
432. [Threads run using code blocks... if you change a local variable in the thread code block will it be changed when the code block exits?](#answer-432)
433. [the $1 $2 , ... $n are global reg ex match variables ... what about threads in respect to these?](#answer-433)
434. [Describe Thread keys /values](#answer-434)
435. [What is the difference between system("date") and `date` ?](#answer-435)
436. [List 7 callbacks, or hooks that are common to tie into during the execution of a Ruby program](#answer-436)
437. [How can you get a stacktrace of your execution?](#answer-437)
438. [What is the literal constructor for a regexp?](#answer-438)
439. [What responds to .match?](#answer-439)
440. [What is the difference between .match and =~ ?](#answer-440)
441. [What are the 3 possible components of a regexp?](#answer-441)
442. [How do you match a "special charactor" what are the special charactors?](#answer-442)
443. [Name some special escape secquences for common charactor classes](#answer-443)
444. [What is a regexp "capture"](#answer-444)
445. [How do you get a capture? talk about it a bit..](#answer-445)
446. [if you have a Matchdata object.... what does the matchdataobject.string method do? matchdataobject.captures meth? What are some useful Matchdata methods?](#answer-446)
447. [Can you use nested () in a regexp?](#answer-447)
448. [Describe some regular expression quantifiers, anchors, and modifiers](#answer-448)
449. [What can you do to a 'greedy' regualar expression to make it not greedy?](#answer-449)
450. [How can you match a specific number of repetitions within a regular expression? e.g. you have 239-9769 and want to match that it is a phone number with 3 digigts a '-' and then 4 digits](#answer-450)
451. [How can you specify a range for repetions in regexp matching?](#answer-451)
452. [How would you write a look ahead assertion? What is it?](#answer-452)
453. [How would you write a look behind assertion?](#answer-453)
454. [Show how to do interpolation on a Regexp](#answer-454)
455. [What if you are interpolating a string into a regular expression that has 'special' charactors e.g. a '.' the period takes on special significance in a regexp... how can you account for this?](#answer-455)
456. [Name some well know methods that take regular expressions as parameters](#answer-456)
457. [empty](#answer-457)
458. [What does grep do?](#answer-457)
459. [empty](#answer-459)
460. [Can you override the assignment operator in a class? as in just override = ?](#answer-460)
461. [How do you use Rdoc and ri together (simple example)](#answer-461)
462. [How can you see all the gems with thier documentation on your machine?](#answer-462)
463. [Describe two ways to implement a 2D array in Ruby.](#answer-463)
464. [What is a DNS server?](#answer-464)
465. [talk about the last argument passed into a method...](#answer-465)
466. [How do you change which ruby textmate uses?](#answer-466)
467. [Can you say x = Object.new then open up the singleton of x with class << x ... code .. end ?](#answer-467)
468. [How do you output a line but not do a \n?](#answer-468)
469. [Why would you def <(other) or def >(other)?](#answer-469)
470. [What have you decided is the best way to form strings given most use cases?](#answer-470)
471. [if you have a method defined like ... methname(&block) ... end .... what if you do not pass a block to it when you call it?](#answer-471)
472. [can you say something like ... return x,object,name,7,9 ... at the end of a method?](#answer-472)
473. [When you require a file do you need to put the .rb extension on it? e.g. require 'set.rb' do you even need the quotes?](#answer-473)
474. [In Ruby are arguments passed by value or passed by reference? ** double check this with some googeling to get whole story](#answer-474)
475. [Can you call a block that expects 4 arguments with zero arguments](#answer-475)
476. [REVIEW ALL SCOPE RULES IN PARTICULAR ABOUT BLOCKS AND SUCH if you pass in a variable reference to a block... change that reference to a new object withing the block.. exit block ... what is the value of the reference after you leave the block?](#answer-476)
477. [What would you use extra () within a method definition parameters list for?](#answer-477)
478. [Is this true? You can pass in the wrong number of arguments to a method... but you MUST pass in the correct number to a block...](#answer-478)
479. [How can you get the last element of an array?](#answer-479)
480. [What does !! operator do in Ruby?](#answer-480)
481. [If you are in an each loop and and exception is raised that causes the program to terminate how can you execute the rest of the each loop?](#answer-481)
482. [Describe the scope of variables and the use of while, until and for loops](#answer-482)
483. [Talk about ruby being pass by value or pass by reference](#answer-483)
484. [What does partition method do for a string?](#answer-484)
485. [List all the % delimeters](#answer-485)
486. [How can you iterate over numbers from 5 to 1 (backwards)](#answer-486)
487. [What is the difference between using a statement like .. for i in (1..8) .... end and (1..8).each do |i| ... end ....](#answer-487)
488. [In Ruby you actually can change constants... but how can you really make a CONSTANT a CONSTANT?](#answer-488)
489. [What does Object mix in to get all its power? :)](#answer-489)
490. [What is an enemerator?](#answer-490)
491. [THE CODE BLOCK GETS THE CURRENT SCOPE AND CAN CHANGE THE CURRENT SCOPE!!! you only change the scope when you go into a def, a class definition, or a module definition](#answer-491)
492. [What does defined? return? ... is it a keyword or a method?](#answer-492)
493. [empty](#answer-493)
494. [How can you find the position of an element in an array?](#answer-494)
495. [what is difference between p and pp](#answer-495)
496. [Describe {instance|module|class}_{eval|exec} family of methods](#answer-496)
497. [When you create a class what is the default behavior of ==](#answer-497)
498. [What is the difference between instance_of? and kind_of?](#answer-498)
499. [What class === only defined for? what if === is not defined for a class?](#answer-499)
500. [What method does Hash use to compare a key passed in with the already stored keys? i.e. you can change the lookup behavior of a hash by overriding this method...](#answer-500)
501. [Name two classes that you cannot declare singleton methods on instances of objects...](#answer-501)
502. [If you have a bunch of ways to create an instance of a class that all differ a bit how should you do this?](#answer-502)
503. [class Parent; def self.who_am_i; puts self; end; end; class Child < Parent; end; if you say Child.who_am_i what is printed?](#answer-503)
504. [If you have a module and want to store a useful method in there that you can access without instanciating any object how would you do it?](#answer-504)
505. [Do code blocks return a value? i.e. you pass a code block into a method...](#answer-505)
506. [Describe the term "Execute Around" and how it pertains to blocks](#answer-506)
507. [Describe a danger when creating a block that you hold onto for a while... pass it around maybe...](#answer-507)
508. [Describe lazy initialization with code blocks](#answer-508)
509. [How do you make "new" method private for a class? i.e. x = Person.new](#answer-509)
510. [Describe the at_exit hook.](answer-510)
511. [Describe set_trace_func and its use](answer-511)
512. [Describe the pattern where you are mixing in a module where you have some methods that should be mixed in as instance methods and some methods that should be class methods](answer-512)
513. [Describe what you get when you use SimpleDelegator ... after you have required 'delegate'... how to use...](answer-513)
514. [Describe the PathName class](answer-514)
515. [What is the difference between is_a? and kind_of?](answer-515)
516. [How can you dynamically define instance methods in a class?](answer-516)
517. [how do you get a charactor in a string at position 2 in 1.8 and 1.9?](answer-517)
518. [Talk about how Rails can use methods that are added to the script on the fly.](answer-518)
519. [talk about providing a block to an object being created with a call to new.. eg. jim = Person.new do |person| .... end](answer-519)
520. [When you define a method dynamically for a class using define_method(method_name) how do you get this newly defined method to have parameters?](#answer-520)
521. [How can you end the execution of a block during its execution?](#answer-521)
522. [Talk about some clever ways to create "singleton" type objects in ruby... as in only one instance of each](#answer-522)
523. [What are the 3 scope gates? Where scope changes?](#answer-523)
524. [describe a top level instance variable?](#answer-524)
525. [Talk about rescuing from Exception ie ... in code .... rescue Exception => er](#answer-525)
526. [What are the differences between new method and initialize method?](#answer-526)
527. [What is self?](#answer-527)



## Answers

###### answer 1
> Demonstrate two ways to create an empty hash

{} and Hash.new
###### answer 2
> Build a hash with two symbols as keys that each have different strings as values

newhash = { :one => "uno", :two "dos"}
###### answer 3
> Demonstrate how to pass a key into a hash

newhash[:one] .... you build a hash with {} you call with []
###### answer 4
> What is returned if you pass a key that doesnt exist into a hash?

nil
###### answer 5
> Demonstrate how to change the value assoc with a key in a hash

newhash[:one] = "fixed"
###### answer 6
> Are hashes ordered? Does it matter order of Keys and Pairs?

They are ordered in 1.9. two hashes with the exact same key and value pairs will eval the same
###### answer 7
> How would you return all the keys in a hash?

newhash.keys
###### answer 8
> These keys that are returned... what is their class?

Array ... when you call the above you are returned an array
###### answer 9
> How do you see if a key is in a hash?

newhash.keys.include?("value")
###### answer 10
> How do you return all the values from a hash?

newhash.values
###### answer 11
> How would you merge one hash into another hash? 

newhash.merge!({:newvalue => 7, :another => 8})
###### answer 12
> How would you add a key value pair to an existing hash?

newhash[:key] = value ... or (worse) newhash.merge!({:newvalue => 7}) ... without ! to not change original
###### answer 13
> Are these both strings "one" ... 'one'

yes
###### answer 14
> Make a string with quotes inside the string... in a couple ways

"He said \"hi\" to me" .. the \ escapes the " ..or use single quote 'He said "hi" to me' .. even better! OR!! %(this is "Quote" here!)
###### answer 15
> Why would you use double or single quotes?

Example 'He said "hi" to me' and "I don't do that" ...double quotes to get single quote.. single to get double within
###### answer 16
> What are some common escape charactors and how do you escape them?

\" ... \' ... \n ... \\ .... you escape with the \ (backslash)
###### answer 17
> How do you use flexible quotes to not have to worry about the above? i.e. this is a great way to create a string

%(this is the string) the "%" is what creates the string after % can be ( ... ! ... { this is the delimiter
###### answer 18
> flexible quotes with the delimiter can be used to handle newlines ... demonstrate... 

```ruby
newstring = %{It was the best of times
it was the worst of times
}
```
this is equal to "it was the best of times\nit was the worst of times\n"
###### answer 19
> What is a here document? describe and create one in ruby

It is a string literal that preserves whitespace linebreaks and such.
<<delimiter (on its own line)
..
..
delimiter
you have to say newstring = <<delimiter
....
delimiter ..... notice the = up there
###### answer 20
> What operator will concatinate 2 strings? Does it leave the strings in place?

\+ ... yes it will leave the original strings in place
###### answer 21
> Demonstrate how to concatinate to the end of a string

string1 += string2 ... will add string2 to the end of string1
###### answer 22
> What is the shovel operator and what does it do for strings?

22. << it will concatinate .. same as += string1 << string2
###### answer 23
> What is the difference between += and << ?

23 The main deal with += is that it re-assigns to the variable. << will modify that variable. if that variable was tied to another re-assign will lose that tie... << will not re-assign
+= will not modify the origional string it RE-ASSIGNS the origional string. << will modify the origional string
x = "one"
x2 = x ... x2 and x will have the same object_id
y = "two"
x2 << y .. this will concat y onto x2 ... and modify x2 in place ... x is tied to x2 so it changes ... when you += it does not modify in place... it re-assigns so the concection is lost
<< for IN-PLACE .... += to re-asssign
###### answer 24
> What is the output? "\n".size What is "\t"?

24. 1 \t "slash t" is tabbed space
###### answer 25
> can you escape charactors in a ' ' single quote? 

25. Sort of ... this will work '\\\'' ... it will escape the '
###### answer 26
> How do you interpolate into a string?

26. Use double quotes and #{ } within it ... "xxxx #{var}"
###### answer 27
> Show two ways to get the 4th - 6th letters out of "One is less than two" *ruby1.9 see below question too

27. substring = string1[3,3] ... or .. substring = string1[3..5]
###### answer 28
> tell me about how this is different in 1.8 and 1.9 ... x = string[1] how do you get what you *usually* want here in 1.8

28. In 1.8 it will return the integer representation. In 1.9 it will return the character ... **** .chr converts an integer to a charactor
###### answer 29
> How would you split this string? "One two three" what do you get back when split?

29 newstringarray = string1.split ... it returns an array split with no args will split on blank spaces
###### answer 30
> Show how you would split with a reg expression

30. newstringarray = string1.split(/:/) the : is the matching reg expression
###### answer 31
> Use split and join on strings/array. Is join valid on strings? What does join do to an array? what does it do to a string?

31. newstringarray = sting1.split ... newstring = array1.join(" ") ... that will build a string with " " between each element... it will call to_s on each element and create a string with whatever you pass into join inserted between each elelment.. returns a string. You can't call join on a string.. NOT DEFINED!! ha
###### answer 32
> a = "one" b = "one" .. does a == b? does a.object_id == b.object_id? What does == usually evalutate for

32. yes ... a == b .... but they are different objects ... == defined for strings this way in the class definition obviously
###### answer 33
> Is nil an object?

33. Yes nil is an object
###### answer 34
> nil.nil? returns?

34. true
###### answer 35
> nil.to_s returns?

35. ""
###### answer 36
> nil.inspect returns?

36. "nil"
###### answer 37
> describe the is_a? function.

37. is_a? will verify class of the object. e.g. :test.is_a?(Symbol) ... returns true .. it checks the superclasses too AND MODULES .. a mixed in module will make is_a? evaluate to true
###### answer 38
> one = :symbol1 ... two = :symbol1 ... are one and two the same object?

38. Yes. both one and two have the same object_id ...
###### answer 39
> Discuss method names and their relationship to symbols

39. Well.. all method names will become symbols. (maybe something to do with making sure there is only one.... you can define it again / add to it... but there is just one)
###### answer 40
> Discuss Constants and their relationship to symbols

40. Well.. all Constants will become symbols
RubyConstant = "Hello there"
###### answer 41
> is :symb == :"symb"? or :name == :"name"

41. yes, Ruby turns the quote into a symbol
###### answer 42
> Ruby Symbols can never be garbage collected? is this true in 1.9?

42. true
###### answer 43
> How can you make a string into a symbol?

43. "Stringthing".to_sym
###### answer 44
> build a symbol that has spaces in it.

44. x = :"this has spaces"
###### answer 45
> build a symbol with interpoation

45 x = :"This has #{interpolation} in it"
###### answer 46
> What happens when you pass in a symbol to interpolated string?

46. The symbol is converted to a string
###### answer 47
> What is the class of a Regular Expression?

47. Regexp
###### answer 48
> Show two ways how you can match a string against a reg expression.. show...

48. 1. "this is string"[/is/] or if a variable x[/is/] 2. x =~ /aaba/ ... [/ /] ... this returns a string NOT MATCHDATA ... to get matchdata use .match
###### answer 49
> What is returned when you get a match? no match?

49. 1. The matching string is returned.... no match nil is returned .... 2. the position(integer) of the match is returned
###### answer 50
> What do the following do in Regexp?  
 ?  
 \+   
 \*  
 \|  
 \[]  
 \\d (say "backslash d")  
 \\s (say "backslash s")  
 \\w backslash w  
 \. (dot)   
 \\A backslash capital A  
 \\Z backslash captial Z vs \z  
 \^  
 \$  

50. ? letter before it is optional /ab?/ will return ab or a .... b is fine but optional
+ must match a least one, then unlimited /ab+/ matches ab or abbb... but not a ... must be a b
* matches zero or more. /ab*/ matches a ... ab ... abbbb.... /b*/ matches b...bbb and "" (the match must be at begining.. is this an "anchor typish"? thingy in the Regexp you are doing?)
[] this will match any charactor in there. /[cbr]at/ matches cat, bat, rat, not zat . the [] is within a [] that starts the regexp ... this is a charactor class
| ... or
\d ... backslash d will match any digit
\s ... backslash s will match any whitespace
\w This is a word charactor definded by [/[a-zA-Z0-9_]+/] ( use \w+ to get words ... just w is JUST a word character)
. any character at all except a \n newline
\A matches begining of a string
\Z matches end of a string but wont include newline ... \z includes the newline
^ matches the start of a line (anchor) e.g. /^\d/ finds a number if it starts a line good for matching after \n 's ** note this and the one below also match when the start of a string (or end as below) a newline does not need to be embeded
$ matches the end of a line (anchor) e.g. /\d$/ finds a number if it ends a line good for matching after \n 's
###### answer 51
> What is greedy matching?

51. The Regexp will match as much as it can .. repetition operators are greedy
###### answer 52
> If more than one match what gets returned? 

52. The first match encountered will be returned
###### answer 53
> What is this called /? ... what is this called \?

53. That is a / slash...forward slash and a \ backslash ...
###### answer 54
> Demonstrate a range match in Regexp

54. "this is a number 46"[/[0-9]+/] [0-9] is a range in Regexp
###### answer 55
> Give an example of negating a character class

55. "new match 78"[/[^0-9]+/]
###### answer 56
> How do you get the negative of the characer classes?

56. Capitalize it .. e.g. \W
###### answer 57
> How would you return a group of results in an array?

57. ([a-f].+) as an example this will return all the matches
###### answer 58
> How can you take a string and return an array with all the words in it?

58. scan will take a regualr expression as an parameter and return an array with all matches
wordarray = "one two-three".scan(/\w+/)
###### answer 59
> what does sub method do on a string?

59. Substites...find and replace .. pass in two parameters find,replace_with
###### answer 60
> gsub?

60. find and replace all pass in two parameters find, replace_with g-(global)sub
###### answer 61
> Talk about global methods

61. Global methods exist in the program outside of a class defintion. () are optional for params list
sometimes lack of parenthesis leads to ambiguity.
having wrong number of arguaments is not a sytax error. It is a runtime error
global methods e.g. puts are defined on Kernal... Kernal is mixed into all objects and kernal
###### answer 62
> What kind of Runtime Error is called when you call a method with wrong number of arguments?

62. ArgumentError, is a type of Runtime Error
###### answer 63
> Demonstrate how to define a method with default argument values

63. def newmethod(a, b = :default)
###### answer 64
> Demonstrate how to define a method that takes a variable amount of arguments

64. def varargmethod(*args) if the * sponge operator is in the middle values are assigned left to right then right to left, the * sponges up the others
###### answer 65
>  if nothing is passed into a method with a variable arg, what is the value of that arg in the method?


65. []
###### answer 66
>How to you specify a return value in a method? what if you do not specify a return value?

66. return :returnvalue, if you do not specify the last statement executed is returned ... once a return is encountered the method passes back control
###### answer 67
>Show two ways to call a method defined in the same class as the method you are in now. 

67. x = method_defined_in_class(3,4) or x = self.method_defined_in_class(3,4) ... the self is implied
###### answer 68
>define a private method in a class

68. def private_method(a,b)
a*b
end
private :private_method
you can also define methods underneath the word private in the class
###### answer 69
>talk about if you can call a private method from within another method of that class. How can you not call it?

69. You can call the private method within the class, but it will not work if you use self.private_mothod
You will get a NoMethodError
###### answer 70
>How do you declare a top level constant? How can you reference it?

70. CaptialLetter = "value" you can reference it with ::Capitalletter
###### answer 71
>What about declaring constants in a class and referenceing them? 

71. Declare it the same way. You can reference it with ClassName::CapitalLetter or even ::ClassName::CapitalLetter
###### answer 72
>Do Nested classes inheret constant values?

72. yes
###### answer 73
>Do subclasses inheret constants from parent classes?

73. yes
###### answer 74
>If in nested class ... and ...Constant declared in both the parent class and in the inherited class which would win?

(WRONG ANSWER)
74. If you have a nested class that inherets from another class and is also nested in a class the lexical scope would win (nested would take from parent (outside the nest), not from the < inhereted)
the definition of the variable would be searched first locally then searched through the inheritance hiearchy
###### answer 75
>Describe static(lexical) scoping and dynamic scoping.

75. These examples show how ruby does lexical static scoping. static scoping variables are bound locally... dynamicaly scoped variables will pop on and off the stack based on environment
Ruby searches for Constants in this order
1 The enclosing scope
2 Any outer scopes (repeat until top level is reached)
3 Included modules
4 Superclass(es)
5 Object
6 Kernel
###### answer 76
>What kind of statements return a value in Ruby?

76. Every statement will return a value in Ruby
###### answer 77
>Write an if then else in Ruby

77. if condition == true
:returnval
else
:otherval
end
###### answer 78
>Write an if then else in ruby that assigns a value to a variable. What if the result of a if then statement does not assign a value? What is returned?

78. value = if condition == 8
:returnvalue
elsif condition == 9
:othervalue
else
:finalthing
end
You can say this ... assign a value because... EVERY STATEMENT IN RUBY returns a value
If you do this and nothing matches... nil is returned.
###### answer 79
>Assign a value with a condition operator

79. value = (x == 4 ? "true_value" : "false_value")
###### answer 80
>assign a value with a statement modifier

80. value = 17 if x == 7
###### answer 81
>write an unless statement

81 unless x == 5
puts "here"
end
###### answer 82
>write a while statement

82. while x < 5
z + 1
stuff = stuff - 1
end
###### answer 83
>write a break statement in a loop, does it stop the whole loop?

83. while x < 5 # And yes it stops the whole loop
z + 1
break if interupt_recieved == true
end
###### answer 84
>write a next statement

84. while x < 5
z + 1
next if interupt_recived == true // next advances the loop
cc + 1
end
###### answer 85
>write a for statement 

85 for x in arraylist
put x // for is an iterator that will pass in each element of arraylist
end
###### answer 85b
>All of the above. do these change the current scope? do they pull in local variables? if you change these local vars do they change after the while/unless/for stuff

85b. All of these will pull in the local environment. any changes to vars will be reflected. Scope does not change.

###### answer 86
>What are the things that evaluate to false when put into a conditon statement?

86. false and nil ... note 0 does not evalute to false
###### answer 87
>What does require do? demonstrate its call

87. It will load the file at runtime. require 'filename.rb' ** note it will execute that file... not just load the classes and stuff... it will run it
###### answer 88
>What does the Class method `ancestors` do when called?

88. returns an array of all the classes and modules that a given class inherits from
###### answer 89
>Talk about the exception class tree.

89. Object is at top... of course.  
Exception inherets from Object ...  
then StandardError ....  
RuntimeError
###### answer 90
>Write a rescue clause. Does a rescue have to be in a begin / end clause?

90. begin
do stuff
if bad stuff happens
fail "error in this code block"
end
rescue StandardError => ex
stuff to do after the rescue
ensure
stuff to DEFINATLY DO
end
... um well you can do the statement rescue "stufff to say" ... but yes if you want the structure above it seems you must be in a begin end block...
###### answer 91
>What does method .. fail ... do?

91. same as raise .. I guess it causes an RuntimeError to be raised always or if in a rescue clause will raise the same exception
###### answer 92
>If an error is a RuntimeError is it also a StandardError?

92. Yes StandardError is higher up the inheritance hierachy so if it is a RuntimeError of course it is also a StandardError
###### answer 93
>What is a synonym for fail?

93. raise
###### answer 94
>How could you define and raise your own exception you defined?

94. Well you could have class MySpecialException < Exception
end
Then you could ... raise MySpecialException "message"
###### answer 95
>What class is all this assert_equal and assert_raise stuff in... what is it>

95. assert_equal and assert_raise are methods in... Test::Unit ... Test::Unit provides a rich set of assertions for ruby testing
###### answer 96
>Can each method use `do end `and `{}`?

96. Yes
###### answer 97
>What does map do on an array? what is a synonym for it?

97. map transforms each element of the array according to what is returned by block. Synonym is "collect"
or better said... map transforms a list by applying a function to each of its elements. map! does this in place
###### answer 98
>What can you do to find all the matching elements in an array... how do you implement?

98. When you call an_array.select { |item| (item % 2) == 0 } ... will iterate over the array... passing into the block each item... it will return the items that match the condition in there
###### answer 99
>What is another name for this above method?

99. find_all
###### answer 100
>What method will get the first match in an array?

100. Find will find the first element that matches a criteria an_array.find { |item| item.size > 4 }
###### answer 101
>What does inject do? What "traditionally" returns an array and what traditionally just returns a number?"

101. Inject takes an inital value as an argument and passes that into the first param of block, second param in block is the collection being passed in to be iterated over
This is basically an accumulator enum.inject(initial) {| memo, obj | block } => obj
The 'memo' is first set by 'initial' from then on out, the memo is whatever is returned by the block. this will iterate over each item that is part of the enum... you can use the memo as part of calculations as you go through the list of stuff... you can only call inject on an enum object like an array or a range
*** map and collect will change each value in the array and return an array... inject just returns last thing evaluated.. unless of course you are returning an array or something on purpose
###### answer 102
>Is a range a collection that can be used with methods like map?

102. Sure you can do this x = (1..3).map { [item] item + 1} this will add 1 to each element of the array... return that array
###### answer 103
>What does this do? File.open("example_file.txt") do |file|

103. That will open a file and pass each line of the file into a block
###### answer 104
> Demonstrate how to pass a block into a method... describe what is going on 

104. 
```ruby
def new_method
    result = yield
    result
end
```


`value = new_method { 1 + 2 }` ... or you could do a ... do ... end

... or with variables
```ruby
def new_method(arg1, arg2)
if arg1 == 7
yield "OK","Pass"
else
yield "NO","Fail"
end
end

new_method(7,"TEST") do |ok_var, pass_var |
puts ok_var, pass_var
end
```
You are executing a method and passing some code in.... the method may be able to use this code... if it wants to execute the code (block) passed in it does so with yield argument, arguments....
###### answer 105
>Can you call yield multiple times on a block?

105. Yes... you can call yield tons and it will keep executing the block you have passed in
###### answer 106
>How can you check if a method was called with a block?

106. if block_given?
###### answer 107
>Show how you can assign a block to a variable, can you pass in two lambdas to a method and never use a &?

107. code_block = lambda do |argument|
x = 4
puts argument
end

code_block.call("called")
YES ... you do NOT need & just define 2 lambdas and then pass them in... the & is to designate the yield
###### answer 108
>Show another way to call a code block other than .. add_one.call(10)

108.another way to write e.g. code_block_name.call(10) is code_block_name[10]
###### answer 109
>How would you pass in a code block (lambda) to a method expecting a code block? 

109.you would call the method with .... meth_name(&code_block) ... I think the "&" here kinda splats out the variable into a code block, then the "&" in the method parameter list grabs this code block because it is now in correct block form and not a var referencing a lambda.
###### answer 110
>how would you define a method that explicitly takes a code block? what if you explicity define a code block and don't pass in a block?

110 def method_with_block(&block) .... ** you do not HAVE to pass in a block just because it explicitly takes one
block.call(10)
end
###### answer 111
>Demonstrate 5 ways to do a loop from 1 .. 10 that prints the number.. not zero!

111. 10.times { |index| puts index+1 }

for x in 1..10 do
puts x
end

###### answer 112
>Describe the differences between using lambda and Proc.new? What is shorthand for Proc.new?
 do some examples of the above.

112. lambda will withing the scope of a function return a value then... if another return is in that function ... it will return that... flow continues...  
Proc.new will return that value and not another return value in the function ** cant say return in Proc... but it will return a value and then stop the flow **.  
proc is shorthand for Proc.new...  
proc does not have to have correct arguments passed in... will be assigned to nil...  
lambda must have correct argument list
###### answer 113
>Define a struct in ruby

113.
```ruby
Video = Struct.new(:title, :video_id, :id) do
    def to_s
      "http://youtube.com/get_video.php?t=#{id}&video_id=#{video_id}&fmt=18"
    end
    
    def empty?
      @title.nil? and @video_id.nil? and @id.nil?
    end
end
```
then .... new_movie = Video.new("Gone w the Wind", 99, 5.99) to create it
.... note of course that you do not have to have the block here ....you can just have the parameters
###### answer 114
>Why might you use a Struct instead of a Hash? 

114. A Struct is a convenient way to bundle a number of attributes together using accessor methods without having to write an explicit class
A Struct has the feature that you can get at its elements by index as well as by name:
###### answer 115
>What is a Binding object and how do you use it... how do you get a binding?

115. binding method is in module Kernel.. to get a binding call the method `binding` which is available everywhere as it is in Kernal. A Binding Object encapsulate the execution context at some particular place in the code and retain this context for future use. The variables, methods, value of self, and possibly an iterator block that can be accessed in this context are all retained.
often you will pass a Binding object into eval to get the context for which eval is being executed .. eval("puts r",the_bind) ... before maybe did ... the_bind = binding somewhere ... or binding is returne somewhere... binding is a function that can be called anywhere returning a binding
###### answer 116
>How do you comment out a line of code?

116. \#
###### answer 117
>How do you comment out a block of code?

117. =begin =end but there can be no spaces or tabs or anything before these =begin and =end
###### answer 118
>What is a bad way to ask for instance variable values in a class... show two ways?

118. fido.instance_variable_get("@name") this is if you didnt use attr asscr stuff I guess
fido.instance_eval("@name") # string version
fido.instance_eval { @name } # block version
###### answer 119
>Show how to create accessor methods to_return instance variables

119.
```ruby
Class dog
    def set_name
      @name = "Fido"
    end
    
    def name
      @name
    end
end
``` 
###### answer 120
>What is the good way to get read access to a instance variable?

120. you would put after the Class dog .... attr_reader :name
###### answer 121
>What is the good way to get read / write access to an instance variable?

121. you would put after the Class dog ---- attr_accessor :name
###### answer 122
>What is a good way to initialize a lot of instance variables when creating an object?

122. you define a method initialize(arg1 = :default, arg2 = :default) ... important that the call to obj_name.new("one","two") matches up param wise with the initializer
###### answer 123
>if a method returned self what is it returning?

123 it is returning the object currently defined... not a copy ... a new variable assignment to this returned self will be equal to the orgional object
###### answer 124
>what method definded in all Ruby objects is called when you do string interpolation and in that have an object? e.g. "hello and #{object_name}" 

124 to_s will be called on that ... to_s is defined for all Ruby objects
###### answer 125
>What will inspect do on an object?

125 It will return a more complete string version of the object e.g. an Array.to_s will return "123" whereas Array.inspect will return "[1,2,3]" just a bit more complete
###### answer 126
>Can you re open an existing ruby class? How do you do it?

126. Of course you can... you open it back up the same way you would define it to begin with
###### answer 127
>How would you check if a class had inherited from another class... ie the class has another class as a parent...?

127. You would call this method on the Class Dog.ancestors.include?(ClassName) dog.ancestors returns an array... instance_of? will just tell you what it is an instance of x.instance_of?(Object) will be FALSE .... is different than x.is_a?(Object) which will be TRUE... is_a? will be true for all superclasses and modules
###### answer 128
>What do all classes ulitmatly inheret from?

128. Object BasicObject in 1.9
###### answer 129
>rand(6) returns values between x and y.. fill in x and y

129 0 and 5 ... integers, not float... 6 values possible
###### answer 130
>! Why can't you call method 'ancestors' on an object created by a call to Dog.new e.g. chico = Dog.new("Chico") .... you can not say chico.ancestors.include?(Dog) why?

130. ! 'ancestors' is an instance method... you need an object of class Class to use that method... ancestors method is located in class Module class Class < Module .... Module is a Class ... remember a class is a Module really... just a subclass of Module
###### answer 131
>if you try to call an undefined method on an object what Exception will be thrown?

131. NoMethodError
###### answer 132
>Why do you do subclasses in general?

132. You create subclasses to extend or modify the behavior of a class... you can redefine the methods of the parent class... you can add new methods...etc
###### answer 133
>How can a subclass also get the functionality of the parent class when it overrides a method in the parent class?

133. You call super in the method and this invokes the method in the parent (super) class.
###### answer 134
>can you call super 'cross method'? i.e. can you be in method "growl" in the subclass and call super.bark to try to get the functionality from the SuperClass method "bark"

134 No you can only call super from within the overridden method "bark" and that will call on the Super method "bark" you cannot cross over to a new method
###### answer 135
>What kind of Exception will you get from the above?

135. NoMethodError
###### answer 136
>describe assert_raise and give an example

136. assert_raise is part of Test::Unit (??) and it takes an argument and a block. It will verify that an Exception was raised in the block that matches the argument passed in
assert_raise(NoMethodError) do
code ...
end
###### answer 137
>How do you define a module?

137. You define a module much like a class... module Nameable
```ruby
module Nameable
    def set_name(new_name)
      @name = new_name
    end
    
    def here
      :in_module
    end
end
```

###### answer 138
>Can you instantiate a module?

138. No you cannot instantite a module
###### answer 139
>How do you get a module's functionality into a class?

139. At the top of the class you would do a include Nameable
###### answer 140
>What is a good catchall in Unit::Test that will assert that no Exceptions thrown?

140. You can call method assert_nothing_raised(Exception) with a block of code passed in. Exception will catch all exceptions thrown
assert_nothing_raised(Exception) do
fido.set_name("Rover")
end
###### answer 141
>Can a module method affect an instance variable in the class that includes it? 

141. Yes you can set instance variables in the module
###### answer 142
>if a class that includes a module adds a method that is also in the module which one wins?

142. The class definition will override the module definition. Class method wins
###### answer 143
>Are class names really just constants?

143. Yes
###### answer 144
>How can you reference nested classes?

144. Use the scope operator :: e.g. fido = Jims::Dog.new
###### answer 145
>If you define a nested class called String does this have normal string methods with it?

145. No ... in the current scope it would be its own class ... to access the string class it would need to inheret < from ::String
###### answer 146
>When you say something like ::String what is going on?

146. the :: is a prefix global scope operator forcing global scope... you now are accessing the global class String
###### answer 147
>which is right .... class dog ... Class dog ... class Dog ...or... Class Dog

147. class Dog ... remember a class name is just a Constant
###### answer 148
>is it True or true?

148. true
###### answer 149
>What effect does this have ... MyString = ::String

149. MyString now is a constant that references the globally scoped ::String... you can now say x = MyString.new("hi")
###### answer 150
>what does method const_get do? Where is const_get located?

150. it will return a reference to a constant e.g. Dog.const_get("Name") will get a reference to the Constant Name defined in class Dog. It is defined in Class Module. Class < Module
###### answer 151
>How can you get a list of constants for a class?

151. Dog.constants .... I think this is a class class instance method ... it will return an array
###### answer 152
>How would you test if something is an Object?

152. fido.is_a?(Object)
###### answer 153
>Is something that is defined as a class an object? class Dog ... does this respond true to Dog.is_a?(Object) 

153. Yes a Class is an object
###### answer 154
>How can you define a method on an individual object? What is this called? Show THREE ways to do it!!!

154. 
```ruby
fido = Dog.new
#******
def fido.wag
  :wag_tail
end
#******
fido.instance_eval {
    def wag
      :wag_tail
    end
}
#******
class << jim
    def wag
      :wag_tail
    end
end
#******
```
This is called a singleton method
###### answer 155
>Are other objects of this class affected by these singleton methods?

155. Of course not
###### answer 156
>Show 4 ways to define a class level method 

156. outside of the class ...
```ruby
def Dog.make_wag
  :wag_tail
end
# and inside the class
class Dog
    def Dog.make_wag
      :wag_tail
    end
end
# or inside the class
class Dog
    def self.make_wag
      :wag_tail
    end
end
# or inside the class
class Dog
    def instance_method
      :instance_meth_return
    end
    class << self
        def class_method
          :a_return
        end
    end
end
```

###### answer 157
>Can you define two methods with the same name ... one an instance level method the other a class level method?

157. Yes
###### answer 158
>Do classes and instances share variables?

158. No... not really except of course you can define a @@classvariable and this variable is accessible by all instances. shared by the instances
###### answer 159
>if you have a class statement what is returned? e.g. statement = class Dog ..... end

159. It will return the last thing evaluated
###### answer 160
>if you return self in a class statement what is returned?

160. you get a class object, not an instance object ... this would create 2 ways to instansiate an object e.g. dog = class Dog .... self end *note self at end... this way dog.new and Dog.new both make Dog objects .. silly of course
###### answer 161
>If you have an instance of a class... \[say\] fido and want to call a class level method from this instance variable how can you do it?

161. You would call the instance level method ... class ... which returns the class... then you can call the method
x = fido.class.class_level_method ... the .class part returns the class ... now we can call class level methods
###### answer 162
>Describe what this is doing ... class AboutMessagePassing < EdgeCase::Koan

162. This is defining a class that inherits from another class... and from that parent class it is inheriting specifically from a nested class in there .... or maybe it is inheriting from a module that has this class defined... yes it is last one
###### answer 163
>So if you have an object and want to call one of its methods what are 2 ways to do it? Which one is used in something like metaprogramming?

163. you can call it with fido.bark ... or fido.send(:bark) or fido.__send__(:bark) .. all objects in Ruby respond to send
###### answer 164
>Give some examples of dynamic ways to send an object a message

164. fido.send("bark" + "_{x}") ... where x is a string that will identify what kind of bark [for instance]
fido.send("BARK".downcase) ... will adjust the message sent to the object
###### answer 165
>What is another way to call the send method and why could it be good?

165. fido.__send__(:message) ... because in a project send might get defined... this is a way to ensure you are getting the send you want
###### answer 166
>How can you check if an object knows how to handle to a message?

166. fido.respond_to?(:message) ... will check if :message is defined
###### answer 167
>show the two ways you can call an instance method passing in an array of args of unknown size

167.  *** Note with send you can pass the message in as a :symbol then the args comma seperated
```ruby
class Dog
    def bark(*args)
      args
    end
end
fido = Dog.new
fido.bark("pat","tom","dave")
fido.__send__(:bark, "pat", "tom")
```
###### answer 168
>What is method_missing and how do you define it?

168. method_missing is a method in a class that you can define that will be called anytime an object receives a message that it doesn't 'understand' i.e. it is undefined in the class
```ruby
class Dog
    def initialize(arg)
        @name = arg
    end

    def method_missing(m, *args, &block)
        puts "Could not find #{m}"
    end
end
```
###### answer 169
>Describe the relationship between respond_to? and a class where method_missing is defined

169. When you define method_missing on a class you can pass it any message and it will 'handle' it because it will invoke method missing... but the method really isn't defined so it will \[say\] false to respond_to? even though it does respond to it
###### answer 170
>How can you make method_missing handle some messages and not handle other messages? talk about what you might do with respond_to? here also

170. Well you can do an if / else where you handle /matches/ on certain messages and if no match you call super(m,*args,&block) and just pass the message up to the 'usual' message handler
You can then also specifically define respond_to? so that it knows what kind of messages the object can handle... calling super on objects it does not respond to
###### answer 171
>talk about a forward proxy and reverse proxy

171. a forwarding proxy takes requests from client \[processes\] and forwards them to the internet. A reverse proxy takes requests from the internet and forwards to internal web servers \[Internet \] --> ** \[Reverse Proxy\]--\[Web Server\] ** ....vs.... ** \[user\] -- \[forward proxy\] ** ----> \[Internet\]
###### answer 172
>What is ⌘ ...and ... ⌥ ... and ... ⇆ .... and ⇧

172. Command , Option, Tab, Shift
###### answer 173
>What are some differences between blocks formed with { } and do ... end

173. do end is for multiline ...
###### answer 174
>When you have bark(arg1,arg2) do |x,y|
 ... code ...
 end show an example of how you would call this... 

174. 
```ruby
def bark(arg1, arg2)
  #... code ...
  yield(x,y) #this will then execute the code block
end
```
###### answer 175
>Give an example of a Class method that is always created with every object

175. new ... all classes must have a new object and this must be a Class method ... this is how you get an instance
###### answer 175
>class File has a lot of class methods. What is an instance of class file though? 

176. and instance of class File represents an open file. class methods can operate on files without opening them
###### answer 177
>describe and implement the singleton pattern where you are creating a logging object and only one is ever created. 

177. 
```ruby
class Mylogger
    private_class_method :new
    @@logger = nil
    def create
        @@logger = new unless @@logger
        @@logger
    end
end
```
###### answer 178
>describe the pattern where you use class methods \[say\] to reopen the class and provide a new way to initialize it

178. say you have initialize defined... now you revisit and you want other ways to create objects... you could create a class method that calls new with the new interface
```ruby
class Shape
    def initialize(arg1, arg2)
      @sides = arg1
      #...
    end

    def Shape.triangle(size)# or self.triangle(size) this give a new way to initialzie the object
      Shape.new(3,size)
    end
end
```

###### answer 179
>If you pass in an object to another object of same class how can you access the passed in objects instance variables?

179. the message is of type >obj< and the receiver is also of type >obj< ... so protected methods in the receiver object can be called by the message object....
but to answer the question in general you can get object instance variables with obj.instance_variable_get("@sides")

###### answer 180
>discuss obj.clone

180. x = obj.clone will produce a shallow copy of the object... variables and such will be copied and the object will have a new object_id ... it is a different object now, ...BUT yes a new object and the instance variables are copied BUT not the objects they reference... so changing the object that is referenced by the instance variable will affect both! You have to do a new assignment on the instance variable to really change that particular  instances state.
###### answer 181
>What is the constant that gives you the ruby version you are using?

181. RUBY_VERSION
###### answer 182
>What is Ruby's top level self?

182. puts self at the top level will return >> main ... this has a class of Object
###### answer 183
>Are top level methods private? protected? or Public?

183. They are private
###### answer 184
>One of his main points was that in Ruby you are always sending a message to an object. If you don't explicitly say which object you want to send the message to, Ruby sends it to self. Is this true?

184. Yes, true
###### answer 185
> If a program wants to use a module how does it do that?

185. include it... might has to require a file that contains the module ...require 'name'
###### answer 186
>what is the . operator do?

186. it is for sending an message to a receiver
###### answer 187
>Can you use . and :: interchangeably when calling a method on an object instance?

187. Yes using a . or a :: works the same for calling a method on an object... I guess the :: just uses the scope of the constant in front of it Shape::add will use the Shape scope and then call the method add ... IF the method name is capitalized(BAD) then :: will first look for a constant in that namespace
###### answer 188
>What does p do?

188. It writes obj.inspect p()
###### answer 189
>Talk about how Modules define a namespace and how you use the scope operator to access things in the module. 

189. When you define a module it encapsulates all the variables and constants used in that module... you access those variables and constants with the scope :: operator
###### answer 190
>How does ruby implement multiple inheritance?

190. Ruby uses a mixin... which is a module. A module defines 'instance methods'... though you can not get an instance of a module. but these 'instance methods' are 'mixed in' to the class that includes them
###### answer 191
>how do you mixin a module to a class to make the module methods available as instance methods?

191. you say "include Modname" to include / mixin ... require in global scope will make methods available.
###### answer 192
>do you need to use require with include?

192. you must require first if the module is in another file... this drags that file in and include will create a reference to it ... otherwise just use include
###### answer 193
>How do you use the Comparable mixin?

193. You need to include the module Comparable then you define the 'comparison operator' <=> with
def <=>(other)
self.duration <=> other.duration
end .... this will give you the < <= == > >= operators with just this. <=> works for integers and floats... otherwise you need to do an if than else for > .. < ... else .. returning -1, 1, or 0
###### answer 194
>What is the Enumerable module?

194. the Enumerable module is a mixin that can support things like traversing a collection, sorting, map, include?, find_all. You must define JUST the 'each' method and '<=>'(in Comparable) to get lots of functionality
The main thing about defining "each" is that you need to have a loop where you keep yielding a value... this value is sent to the block where each is called... fido.each { |x| ...code ...} ... silly to have an enumerator for fido but you could and each needs to yield things to that block
```ruby
def each
    @string.scan(/[aeiou]/) do |vowel|
      yield vowel
    end
end
```
###### answer 195
>write a class that includes Enumerable and Comparable

195.
###### answer 196
>What is the operator that checks if something is defined and if it is returns it... otherwise it evaluates and returns the right side ... and remember it will create that variable because before it was undefined

196. ||=
###### answer 197
>how will ruby look up method names between, class, superclass, multiple modules?

197. It will first look in the current class,  
then mixed in modules (last one included looked at first),  
then superclasses  
and there mixins
###### answer 198
>what is the difference between load and require

198. You can use load to 'force' a load.. in the case of files changing... require only loads things once
###### answer 199
>Talk about the scope of variables and methods in a file that was loaded or required

199. the variables and methods that are 'required' or 'loaded' are NOT propagated to the current scope... Global variables ARE propagated....the file will 'execute' and classes can be included... but variables defined there are not in the scope where 'require' or 'load' is called
###### answer 200
>Can you do an include Classname within another class?

200. NO include is for modules even though a class is a module
###### answer 201
>What is this statement doing? x = Stuff::T.new 

201. it is using the Stuff namespace(a module or a class) and then creating a new T object which is either a class defined in that module or a nested class within Stuff class, :: creates scope
###### answer 202
>Can you define a method initialize in a module?

202. Sure... remember the methods in a module will be 'mixed in' to a class, so that could become the way to initialize an object
###### answer 203
>What is the difference between include, require, and load

203. include is for including a module in a class, require and load will drag a file into the current file, load 'forces' a load, require brings it in once. You can not include something unless it is defined in the current file or required
###### answer 204
>Can you define two methods that accept different amount of args that Ruby will determine which one to use based on arg list?

204. No, you cannot do operator overloading... you just have to be able to accept multiple args and then deal with them
###### answer 205
>can you say attr_accessor :purchases ... if purchases is a class level variable?

205. No... attr_accessor is for instance level vars... you can open up the singleton and define an attr_accessor there though
###### answer 206
>Can a subclass access a private method in the parent class?

206. Yes...
###### answer 207
>Does x = [] x[9999] << "Hello" create a huge array?

207. It will create the whole array... huge... populated with nil and the one value
###### answer 208
>Talk about 2 ways to do a deep copy of an object

208. You can use the Marshal module ... x = Marshal::load(Marshal.dump(obj)) ... or you can override the clone method in your class
###### answer 209
>What kind of objects can't be Marshaled 

209. You can't dump objects that have bindings or have procedure or method objects or instances of Class IO or singleton objects... marshaled data loading must match up ruby versions with the data writting
###### answer 210
>Show an example of parallel assignment in Ruby

210 a,b = b, a
###### answer 211
>Describe this parallel assignment

211. the values on the right are determined in a left to right order then assigned to the left side an array is formed of the rvalues and then the lvalues are populated by each of the rvalues
###### answer 212
>Describe and & , or ||, ! not, which has lower precedence of the pairs?

212. They are the same thing except and, or, not have lower precedence... also it is shortcircuit evaluation... if one of the `and` expressions is `false`, it halts evaluation of other stuff... returned is the value of the first expression that halts the comparisons
###### answer 213
>How can you check if something has been defined in your program

213. use defined? x it will return nil if undefined or something like "method" or "constant" ** note defined? nil will return "nil" ** ...  
defined? is an operator! like + - not .... it is not a method
###### answer 214
>What is the regular expression pattern match operator and negation of that? What does it return. What is difference between that and match method?

214 =~ !~ ... it returns the start position of the match or nil if no match... match method will return the part of the string that matches ... or array depending on stuff
###### answer 215
>what is the difference between shape.eql?(obj) and shape.equal?(obj)

215. eql? will check that the receiver and the argument have the same type and value 17 != 17.0 because of type eql? and == are usually the same ... usually you override these in classes to get behavior needed.... equal? tests that they have the same object_id
###### answer 216
>How do you define a global Ruby variable? Name 2 special ruby global variables

216. $ couple others are $! is the last error message, $& is last reg expression matched $0 name of the ruby script file
###### answer 217
>write an exception that saves the exception object to a variable, and handles two exception types
```ruby
begin
    # code...
    # code ....
    rescue SyntaxError, NameError => error_1
      puts error_1
    rescue ArgumentError => error_2
      puts error_2
    else
      puts "No Errors"
    ensure
    # code ...
    # code ...
end
```

###### answer 218
>describe the === operator

this is the case subsumption operator... a === b means If a described a set, would b be a member of that set?" ... this is usually defined by the author of the class of 'a' ... case operations use this
###### answer 219
>describe else in a resuce clause

else is executed if NO Exceptions are raised it is after all rescue's and before ensure
###### answer 220
>talk about all the pieces in a rescue clause... and then talk about a rescue statement modifier

220. begin... end rescue's, else, ensure, retry, raise .... you can say ... bad_non_existent_method rescue do_this ... do this can be a string that is just returned... it can be a begin end where you have ...code... in between you cant use all the ensure and stuff that you do with a normal rescue clause
###### answer 221
>talk about retry 

221. retry must go in a rescue clause... it will repeat the begin / end block
###### answer 222
>Why would you put raise in a rescue clause?

222. this will allow you to filter the exception... storing the exception in \[say\] $! or whatever var you want... and it will pass the exception up where it can be better handled
###### answer 223
>if you just put a raise statement what happens?

223. it will re-raise the current exception, if there is none it will raise a RuntimeError. This is used in exception handlers rescue clauses that need to deal with an exception before passing it on up the stack ... thus the re-raising of same one... it is not completely handled yet
###### answer 224
>What happens with a raise "Error message here"

224. it will create a new RuntimeError with it's message as the string
###### answer 225
>What happens with raise ArgumentError, "Message", caller\[1..-1\]

225. it will raise a RuntimeError, with the message, with the stacktrace (minus a couple routines) ... the stacktrace is put in the last ar
###### answer 226
>Describe and write a catch / throw

226. This is designed to jump out of processing during normal processing. Ruby will zip through the calling stack to find the matching catch to the throw... An exception is not necessarily raised. This is kinda a exception type construct for normal processing where you have to jump out of a nested construct.
```ruby
catch (:done) do
    while line = gets
        if line == "!"
          throw :done
        else
          puts line + " ** "
        end
    end
end
```

###### answer 227
>use the ? : statement

227. x == :done ? done_object.new : continue_object.new
###### answer 228
>Give 3 examples of classes and modules that are automatically built in

228. TONS are ..but... classes Array, File, Integer, Object ..... Modules Comparable, Enumerable, Math, Kernal
###### answer 229
>In Ruby syntax how are expressions and statements terminated? 

229. The end of the line terminates the statement or expression, you can also put in a ; to put multiple statements on one line
###### answer 230
>How can you continue an expression on the next line?

230. If the parser can tell that it is an incomplete statement it will continue on next line, e.g. if ends with an operator +,-, etc.. or a comma , ... you can also put a \ backslash in to make it continue on next line
x = 5 + 6 \
+ 10
###### answer 231
>What are BEGIN and END ? write some

231. BEGIN {} and END {} are BLOCKS that are executed when a file is loaded and when a program has finished executing END{} ... BEGIN blocks are executed as they are encountered, END blocks are executed in reverse order LIFO
###### answer 232
>Describe generalized delimited input

232. besides "" or '' you can form strings with a % followed by the literal type then a delimiting character which is non-alphabetic and non-multibyte. if (,{,[,< are used.. the delimiter is the closing bracket
%q single quoted string ** note all these 'specialized' %'s have a delimiter after the letter e.g. %q* where * will be the decimeter you don't need a literal after the % ... the literal just makes it more specific... in fact just using % is a great way to make a string with ' and " in it
%Q double quoted string
%w, %W array of strings
%r regular expression
%x Shell command
###### answer 233
>What are the basic types in Ruby?

233. numbers, strings, arrays, hashes, ranges, symbols and regular expressions
###### answer 234
>can you make a here document anywhere?

234. Whenever ruby parses <<identifier or <<"quoted string" it replaces in with a string literal built from successive logical input lines ... it ends when it encounters identifier ... the ending has to be on its own line unless you put in a <<-EOM (-) before the delimiter
###### answer 235
>Describe the convention of capitals in constants AND class names and modules

235. Constants object references are all caps with underscore X_DIVISOR = 4.5 class names and modules are CamelCase
###### answer 236
>Talk about false and nil ... as in their names. describe how to create a singleton class like these where only 1 object per class can be created

236. false is a singleton instance of FalseClass(there can be only one), nil is a singleton instance of NilClass(there can be only one) and the value of uninitialized instance and global variables... to get a singleton instance Ruby must do some stuff? I know you can def self.new in a class and set a class var to false so new instances can not be created... call super if there is no instances yet... better yet... require 'singleton' .... include Singleton
require 'singleton'; include Singleton in a class... this makes "new" private
create the (one and only instance) with "instance" method x = Person.instance if you do a y = Person.instance ... both are referencing the same object ... that's it! just include Singleton then get it with "instance"
###### answer 237
>does FALSE = false? TRUE = true and NIL = nil?

237. they are synonyms... yes they are the same
###### answer 238
>What is the name of the current file constant? current line constant?

238. __FILE__ , __LINE__
###### answer 239
>What responds true to object.nil?

239. only an instance of nil object will respond true to nil?
###### answer 240
>Can you define a Constant in a method?

240. Nope, I guess because you would be re-assigning everytime the method is called... which is counter-intuitive
###### answer 241
>Do you have to initialize class variables before use?

241. Yup
###### answer 242
>Describe class variables defined at the top level

242. class variables defined at the top level are defined in Object and behave like global variables (put this in your diagram :) )
###### answer 243
>Are class variables shared by children of the class they are defined in?

243. Yes.
###### answer 244
>Are instance variables available to class methods?

244. No
###### answer 245
>Does a block take on the set of local variables in existence when the block is created?

245. Yes, this is part of the blocks binding
###### answer 246
>What are some examples of pre-defined r/o read only variables in ruby?

246. $& is the string matched following a patter match, this is local to current scope. $$ the process number of program being executed
###### answer 247
>How can you define a shell command

247. back quotes `backquotes ` or the %x{} ...delimiter
###### answer 248
>can you use the scope operator to get a local variable or instance variable out of a class?

248. Dont think so... you use the scope operator followed by a Constant... you could call a method within that Constant defined namespace and that could return \[say\] a instance variable
###### answer 249
>How are ruby's comparison methods implemented?

249. comparison operators are implemented as methods.
###### answer 250
>what can you use instead of the keyword "then"?

250. : and NO YOU DO NOT HAVE to use THEN OR : if the body starts on a new line
###### answer 251
>!! Describe the two case statements

251. case starts with case statement then you either have or do not have a target
case case target
when condition when comparison, other_comparison, YET_ANOTHER // comparison === target ... case (with) or (without) target
.... ...
when condition when comparison
... ...
else else
... ...
end end
###### answer 252
>Describe a definition (def) with an unadorned method name outside a class or module definition 

252. This will be added as a private method in class Object and may be called in any context without an explicit receiver (put this in your diagram)
###### answer 253
>Can a method argument list reference an argument that precedes it in the argument list?

253. Yes it can
###### answer 254
>Can you pass a block to any method?

254. Sure you can pass a block to any method... it will only get executed if there is a yield
###### answer 255
>Describe the order and things that can be passed into a method

255. reciever.name[parameters][block] params ... [param,...][,hashlist (=>)][*array][&a_proc] ... pass in params, then a hash, then an array, then a block... couple ways to pass in the block HASH IS BEFORE ARRAY
###### answer 256
>What if you do not indicate a receiver for a message.. ie calling a method

256. self will be assumed
###### answer 257
>What does calling super do? and talk about parameters with this call

257. calling super acts just like calling the original method except the search for the method body starts in the parent. if no params are passed the original method calls parameters are used
###### answer 258
>if an operator is redefineble what does it look like method wise...

258. (expr1).operator(expression2)
###### answer 259
>what does this def do?  
 def attr=(val)
 end

259. it is called when you say something like obj.attr = "Hello" .... really obj.attr=("hello")
###### answer 260
>What is aliasing?

260. it creates a new name that refers to an existing method, operator, global ref, or reg expression back-reference. it makes a copy so if you redefine the method... the alias will still invoke the old method
alias $prematch $` ** NOTE alias does not have to be in a method definition... you can do it anywhere ... cant do to local vars.. only methods global refs, reg expressions
alias plus +
###### answer 261
>can you alias instance variables? local variables? class variables? constants?

261. No you cant.. you can alias the getter and setter methods if you said something like attr_accessor :name ... you could then alias :fullname= :name=
###### answer 262
>what is done when you \[say\] include in a class definition? what happens when you write "include"

262. Module#include is a method in Module which is automatically in all Ruby programs. it will add the named modules as anonymous superclasses of the class being defined
###### answer 263
>what happens if you override new? 

263. new is a class method and if you override it you need to call super or else no objects will be created and will return nil
###### answer 264
>what does module_function :sin .... do when written in a module?

264. It creates kinda makes class method out of an instance method.. but in a module... you can access by scope operator ModuleName::funcname or of course you can access within the module ...
###### answer 265
>what is a closure?

265. (a structure) that remembers the context in which it was defined and uses THAT context whenever it is called... or an anonymous function that preserves the local variable bindings that are in effect when the proc is created
###### answer 266
>what has higher precedence? do .. end or {}

266. {} have higher precedence than do end
###### answer 267
>describe the 3 places an exception can be handled

267. within the scope of a begin/end block...  
withing the body of a method (add rescue at end) ...or after a single statement ...    
statement rescue r_statement  
http://www.robertsosinski.com/2008/12/21/understanding-ruby-blocks-procs-and-lambdas/ go here and practice with procs, lambdas, methods, and blocks
###### answer 268
>is the condition ? return value : other return value good for long if then / else things?

268. No this is for simple conditional assignments though you can do a begin/end to make more robust... but this is dumb
###### answer 269
>Can you have more than one method parameter with a & .... explain

269. No. the & is really so you can re-use code blocks and pass them in to a method. e.g. you cant pass a block in this way { } and re-use something... you have to write it out... the &proc_name is just so you can pass in something that has already been done.
###### answer 270
>Can you pass in a &name and a code block to a method?

270. No. the { code block } would want to go into the &name, but so would the other thing you passed in. You would get a 'wrong number of arguments 1 for 0" error
###### answer 271
>Can you pass in two code blocks to a method?

271. Sure. just pass them in like everything else you pass in... no & before it... the & is just for yield .... pass them in then do >> name.call to call the code block you passed in. ... yield will call the &codeblock or the { code block }
###### answer 272
>if you pass in a lambda that needs to be the "block" thus responding to block_given describe how you pass that in.

272. if it is going to be the code block you have to pass it in with &name and it must be received as &name or it will not be the "block" ... the first & splats out the lambda into a block
###### answer 272b
>if you pass in a block of code without &'s' will that be a "block" of code ...responding to block_given?
# TODO 272 is written 2 times 
273. no just a block of code will not be considered a "block" of code for that method
###### answer 274
>Can you call Proc.new .... just like that... nothing else?

273. no. it is just a block of code.
###### answer 274
>

275. It would have to be in a method definitition that had a block passed into it. Proc.new would take the block as its value.... otherwise... for the most part you would never call Proc.new without a block
###### answer 275
>What is another way to say Proc.new

275. proc
###### answer 276
>How do you execute a method on an object dynamically at runtime?

276. You could just call the send method "send".... this sends the object the method and parameters
obj.send(:getinfo,"param1", :param2)
###### answer 277
> in each with index you pass in two parameters which is which?

277. The first one is the each/item the second is the count/index
###### answer 278
>What are the 4 evals? and what are the differences

278. eval, class_eval, module_eval, instance_eval ...  
class eval only works on objects of class Class ...  
ClassName.class_eval will open the class for defining instance methods ....  
ClassName.instance_eval would open up the singleton of ClassName ... here any def's would define class methods
###### answer 279
>How do you create Binding objects? Where is the binding function located?

280. you just call binding ... no parameters.... returns a binding This method is located in Kernal thus avail everywhere...
###### answer 280
>What are binding objects?

280. A binding object encapsulates the execution context
###### answer 281
>Describe the two method objects you can create

281. You can create a bound Method object or an UnboundMethod object... method objects are bound (have a binding) whereas unbounded don't.. Method objects can get a binding or be unbound.. to execute a method object it needs to be bound.
###### answer 282
>what does unbind do?

282. it will disassociate a method from its current receiver.
###### answer 283
>how do you create a Method object and an UnboundMethod object?

283. A bound method object is created by calling "method" on a receiver(an instance of a class) with the name of the method as a parameter.... an UnboadMethod is created by calling instance_method on the Class of the object you want to create the unbound method on. e.g. ub = String.instance_method(:length) ... you would then need to bind the method before you can call it ... bind it with an instance of the class
###### answer 284
>What does class_eval do?

284. Essentially it re-opens a class. You pass it a block or a string(to eval)
###### answer 285
>what does instance_eval do?
 x.instance_eval or Object.instance_eval { ..block..}

285. It will open up an instance of the class, not the class... if you define something you are defining on the singleton...You can pass it a block or a string(to eval)
###### answer 286
>What has higher precedence? {} or do/end. What other differences are there between the two?

286. {} have higher precedence. There are no differences except the precedence
###### answer 287
>What is preferred in Ruby generally Proc.new or proc or lambda? is proc = lambda?

287. Reading suggests lambda is favored. proc = Proc.new in Ruby 1.9 and proc = lambda in 1.8 ... in general try to use lambda
###### answer 288
>how can you run an external process (it replaces the current process)

288. exec(command <,args>)
###### answer 289
>What is the best way to define a class method self.meth_name or ClassName.meth_name? why?

289. self.meth_name ... because it is DRY... what if you change the class name? you would have to change all those class methods too
###### answer 290
>What does "inherited" method do... explain it.

290. inherited is a class method of class Class. classes are instances of Class. inherited is called whenever a subclass of current class is created. You override inherited to \[do something\] whenever a class is subclassed. def self.inherited(klass_name) .... code .. end
###### answer 291
>What are the 3 types of conversion performed by the interpreter. Describe each.

291. loose, strict and numeric coercion. loose is to_i and to_s ...(and more) if an object has any kind of decent representation as a string to_s will convert it. to_str is much more strict, with to_str you only implement it if EVERYWEHERE you could use a string you can use this object. the method coerce implements Ruby's coercion protocol. coerce guarantees the two objects will have the same class. You must implement coerce.
###### answer 292
>Ruby objects have three components, name them.

292. a set of flags, some instance variables, and an associated class.... objects reference classes, and classes reference zero or more superclasses
###### answer 293
>What does this code do (x is a variable) class << x ... what is another way to do this?

293. This is used to define a singleton method for the x object. another way to do this is say def x.meth_name ...code ... end .. or even x.instance_eval { .. code w/ def..}
###### answer 294
>When you do the above what happens as far as class structure?

294. The Ruby interpreter will insert an anonymous class inbetween the object and the objects real class. This is the singleton class. this class is searched first for methods on that object.
###### answer 295
>String is an instance of what class? 

295. Class. classes are objects themselves... String is an instance of class Class
###### answer 296
>talk about defining a singleton method on String.... and how it is the same as a defining a singleton method variable x which is of class Person  
 def String.say_hi 
 ..code.. 
 end  
def x.say_hi
...code...
 end

296. both of these are defining a singleton method... the singleton on String will be a string class method
###### answer 297
>Describe obj.extend(<mod.+)

297. extend will add the methods in module passed in as parameters to the obj ... if needed it will create the virtual class and add these methods as part of this virtual class. Extend adds the methods... if you call extend in a class it adds those methods to the class as class methods because self is assumed
###### answer 298
>When a class includes a module describe what happens as far as how they link together.

298. When you include a module Ruby creates an anonymous proxy class that is the direct superclass of the class that does the including.
###### answer 299
>What is the difference between calling include ModuleName and extend ModuleName in a class definition?

299. When you include.. the methods in the module are mixed in to the class as instance stuff... when you extend it is same as self.extend which will create class methods.
###### answer 300
>When a class definition is executed ... talk about the value off self.class

300. When the class definition is executed you are creating a Class object named \[say\] Dog ... the class of self is thus Class while executing the code to create a class
###### answer 301
> When a class definition is executed... talk about the value of self.name

301. when you do self.name you are executing the name method (which is in Module)... Module is a ancestor of Class and thus its instance methods can be called without an explicit receiver within a class definition

###### answer 302
>Can you define two methods with the same name... one a class method, the other an instance method?

302. Yes... one is avail for instance methods the other self.meth_name is inserted into the singleton class.

###### answer 303
>While a class definition is being executed talk about the methods available to it

303. While a class method is executing it can access Class instance methods ie Dog.name because name is defined in Class's superclass .. of course it has access to Object methods and those mixed in with Kernel and stuff
Dog = Class.new{}

###### answer 304
>talk about how attr_accessor works

304. attr_accessor is an instance method in class Module. when you are defining a class you have an object named ClassName which is an instance of Class... Module is in the chain of superclasses for Class so you can call the instance method attr_accessor when defining a class

###### answer 305
>What does attr do in a class?

305. makes a attr_reader out of the symbol passed in, if you say attr :name, true it makes it an attr_accessor

###### answer 306
>Talk about class instance variables and object instance variables.

306. if you \[say\] @var_name in a class definition that is not in a method definition that @var_name is an instance variable of the class ... not the object... to get an object instance variable you have to define it in something like def initialize where the object is being created

```ruby
class Dog
@cls_var = 9 # self here is Dog which is a Class object
    def initialize
      @inst_var = 9 # self here is a variable that is about to 
                    # be a Dog object (an instance of a Dog)
    end
end

```
###### answer 307
>How can you add functionality to when classes and modules are defined?

307. open up class Module and define some methods there. the methods you define there can be called during Dog = Class.new {} or the syntactic sugar class Dog ... end ... attr_accessor is defined there for instance
###### answer 308
>Can you use Ruby's keywords as variables? what about method names?

308. You can't use any of Ruby's keywords as variable names, You could use them as method names though... prob a bad idea though
###### answer 309
>Can you include a class in another class?

309. Nope.. a class can inherit from another class but it cant include it
###### answer 310
>If a class Dog < Animal ... and Animal has class methods... such as Animal.make_noise ... can you also say Dog.make_noise

310. Yes... the class methods in the superclass will also be class methods on the child class accessible with the child class name
###### answer 311
>When you execute a class method you are sending a message to the ____ object itself

311. Class... Dog = Class.new or class Dog ..... Dog is now a Class object.. when you say Dog.class_meth ... you are sending a message to the class object (which is Dog) ... class methods are singleton methods on the ClassName
###### answer 312
>What happens when you define methods at the top level

312. You are creating private instance methods of class Object... these are available everywhere; as they are in class object
###### answer 313
>How can you change the visibility of a method in subclass from that of its parent class ie a_method is private in parent but public in subclasses

313. You would just say public :a_method ... this will insert a hidden proxy method in the subclass that invokes the original method using super
###### answer 314
>How can you iterate over all the objects in your program?... well not all... which objects are not in there?

314. `ObjectSpace.each_object { |x| p x}` will not return FixNum, Symbol, true, false and nil objects

###### answer 315
>How can you get a list of all superclasses of a class? how can you get a list of all the classes and modules?

You just call Classname.superclass ... then assign a var to this parent class and call it again... this will build a list of all superclasses... Module::ancestors Module is mixed in so you dont need the scope operator.. so ClassName.ancestors will return all the modules and classes
###### answer 316
>when you have class Dog ... end and in your code you later say Dog.private_instance_methods(false) to get a list of the private instance methods... describe where this method is and how it was found

316. Dog is a object of class Class... Class inherits from Module so all the instance methods of Module are available to the Dog object which is of class Class. One of those methods available to Dog is private_instance_method. false keeps the method from recursing up into superclasses and returning those instance methods
###### answer 317
>What are all the ruby keywords

317. `BEGIN END __ENCODING__ __END__ __FILE__ __LINE__ alias and begin break case class def defined? do else elsif end ensure false for if in module next nil not or redo rescue retry return self super then true undef unless until when while yield`
###### answer 318
>Talk about the difference between alias and alias_method

318. First off alias is a keyword and takes two (no comma ,) arguments new_name copy_of_this_name.... alias method is in Module as a Private instance method... takes two arguments( with a comma ,) both make new copies of METHODS!! not vars or stuff like that alias_method :new_name, :copy_of_this_name seems preferred because it can be overridden
###### answer 319
>In a Hash is the key :one the same as "one"?

319. No. you will not be able to access the value for :one with "one" ... I think rails changes this behavior
###### answer 320
>When you have xx = String.new("Cat") yy = String.new("Cat") how is it that xx == yy ... they are different objects...

320. It is because of how the == operator is defined for xx ... which is a String... you could override this ... == is defined differently for Objects ... *but String overrides ==*
###### answer 321
>Give 3 examples of operators that can be overridden and 3 examples of operators that cannot be... how is it that they can be overridden?

321. overridden `== , +, !` ... NOT overridden `&&, not, and` ... they can be overridden because they are implemented as methods in the class
###### answer 322
>How can you erase all the keys and values in a hash?

322. clear method `hashname.clear` returns `{}`
###### answer 323
>how can you iterate over all the key/values in a hash and how can you iterate through each key.. or each value

323. `each { |key, value| } each_key {|key|} each_value {|value|}`
###### answer 324
>Describe what is going on when a class definition is first encountered by the parser. What happens to @@vars ... what about the logic in the class statement that is not in "def's" is this stuff just executed once when the parser goes through?

324. .... yes code not in def's will be executed as it is encountered during parsing
###### answer 325
>Describe and diagram the ruby class / object model

325. answer please
###### answer 326
>Talk about the * operator and passing in variable args... most specifically the case when you pass in an array to a method that catches *args ... not args

326. When you pass in an array to *args that whole array will become the first arg[0] ... if I put the * in front of the array you pass in.. it breaks it up then passes it in which means the broken up array could get sponged up by *args...
```ruby
def init(*args)
  args
end
init(an_array) # [[1, 2, 3, 4, 5, 6, 7, 8]]
init(*an_array) # [1, 2, 3, 4, 5, 6, 7, 8]
```

this will put an_array as [0] element This works... it breaks up the array and passes in each element
(an array within the array)
###### answer 327
>Talk about what things are propagated into current scope in a required file

327. constants, global variables, instance variables and class variables ... methods defined at the top level are available also ...defined in the top level scope in a required file will all be available in the scope of the requiring file
###### answer 328
>What does -cw do when you do ruby -cw prog.rb -v? --version? -e?

328. -c check for syntax errors (wont run prog) -w allow higher level of warnings -v verbose mode --version show version info -e execute code in quotations
###### answer 329
>How would you get a line of input from the the keyboard? How would you read the lines of a file?

329. 
```ruby
value = gets
file = File.new("filename.dat", "w")
file.puts "hey there"
file.close # you can of course have a block here passing in |file| ... this will close it automatically
```
###### answer 330
>How can you get a lot of ruby config info? for example where is Ruby's executable files?

330. require 'rbconfig' include Config Config::CONFIG["bindir"] This is a hash with keys and values that have all the config info Config::CONFIG.keys returns all the settings
###### answer 331
>what is the standard library

331. It is a collection of files in a directory that is shipped with ruby. you use these with the require command
###### answer 332
>Name a couple of files that have some standard library facilities that are in Config::CONFIG["rubylibdir"]... you may require these files to get some additional functionality

332. cgi.rb , fileutils.rb, set.rb
###### answer 333
>Talk about the terms library and extension

333. Library is usually means ruby code that can be loaded or required... extensions are usually thought to be written in C
###### answer 334
>What is the global variable that has ruby's load path's stored?

334. `$:` this is the set of paths ruby searches when you do a require or load
###### answer 335
>How do you start an irb session? what if you have a file with all kinds of classes and stuff that you want in memory during your irb session?

335. type in `irb` ... `irb --simple-prompt --noecho` are common additions ... `exit` exits irb .... in irb you can do something like ... `require 'filenam.rb'` ... this will do what you think it does ... then you could use classes and such in there
###### answer 336
>What is RDoc and ri

336. RDoc and ri go hand in hand. *Ruby Documentation*, *Ruby Index*...RDoc uses Simplemarkup to format your comments in Ruby code... both are command line tools ... ri String#upcase will display info on the instance method string
###### answer 337
>What are # and :: in ri referencing?

337. \# is instance methods and :: is class methods
###### answer 338
>Very simply what does rake do?

338. rake is a command line tool that reads and executes tasks in a file (Rakefile) .... it is a mini language built in ruby and you just write normal ruby code within it to define tasks. Rake is really an automation tool - its a way of putting all those tasks that you perform in a project into one place
###### answer 339
>Write a loop statement 

339. 
```ruby
loop do 
    # ...code... 
    break if x < 8 
end 

loop {
    # ... code ....
    break if x < 9
}
```

###### answer 340
>Use while and until as statement modifiers and use each at the beginning and end of a loop construct.

340. 
```ruby
puts(x = x+1) while x < 10 
x+=1 until x ==14
while x > 10 do 
# ...
end 
until x > 10 do 
  # ... .... *until* .... ...
end

x = 0
begin
  x += 1
  p x
end while x <10
p  x  # prints 10

x = 0
begin
  x += 1
  p x
end until x <10
p  x  # prints 1
```
###### answer 341
>talk about defining a namespace and a task in rake

341. to make a namespace you just \[say\] `namespace :admin do .... end` within that you can have more `namespace :db do ... end` `namespace :function do .... end` ... within each of these namespaces you define a task `:clean do .... end` ... you do not have to have tasks in namespaces
```ruby
namespace :admin do
    namespace :db do
        task :clean do
          #....code....
        end
        task :other do
          #...code...
        end
    end
    namespace :files do
        task :check do
          #...code...
        end
    end
end
```
###### answer 342
>what do you use to describe a namespace and task in Rake?

desc "write something here" (this goes right before the task you are defining)
###### answer 343
>how can you see all the tasks defined in a Rakefile?

rake --tasks
###### answer 345
>What is RubyGems?

RubyGems is a library of utilities that helps with installing Ruby libraries, Ruby applications, and helps package these things. With 1.9 RubyGems is baked in. RubyGems makes sure all dependencies are downloaded and met. The command line tool for this system is 'gem' on unix use sudo gem install because *by default local gems are installed into shared directories*
###### answer 346
>What is the extension on gem files?

.gem
###### answer 347
>Describe where the 'gem' command will look for gems

first it will look first in the current directory  
then in the local cache maintained by RubyGems system.  
then it will look at RubyForge.org
###### answer 348
>what command line option can you give to gem to make it just look locally

`-l`
###### answer 
>does encountering a return in method halt the method?

348. Yes... you can have many returns... e.g. in if than else .... but when a return hits... that is returned and program stops
###### answer 
>What 2 ways can you get an object to call a private method?

349. you cannot call the private method with the `.` operator but `send` or `__send__` will get it done... you can also do e.g. `x.instance_eval("private_meth_name")`
###### answer 350
>How can you be sure you are only calling public methods on an object?

350. `public_send` will make sure you are only calling public methods... of course the `.` dot operator will only allow this also
###### answer 351
>the *arg in a method definition is a sponge type argument... describe what this means and how vars in the parameters are assigned

351. all other args in the definition will try to be filled from left to right and right to left... whatever is left will get sponged up into *arg.. if nothing left [] is that args value... think this is Ruby 1.9
###### answer 352
>do variables in Ruby hold values?

352. No not really...variables hold references to objects .... except for say something like an integer or symbol or true/false/nil... these are not referenced... they are 'immediate values'
###### answer 353
>talk about clone and dup in relation to freeze method 

353. in a frozen object a 'clone'd' object is also frozen... in a frozen object a "dup" of it is not frozen
###### answer 354
>What is the new method? is there a singleton new method and and instance new method?

354. Dog = Class.new {... } (calling new on Class this is a class method of Class) or fido = Dog.new (calling new on Dog which is an instance of class Class) it is an instance method of class Class... yes there are both... Class.new calls the singleton method and something like \[say\] Ticket.new will call the instance one ... ie in class Class you have the class method new for something like Dog = Class.new(or the syntactic sugar class Dog ... end) and in class Class you have an instance method new for when you say fido = Dog.new
###### answer 355
>if you have unassigned \[say\] local variables in a method definition will that be caught during the parse?

355. No... caught at runtime
###### answer 356
>What can self be?

356. -main- top level default object -class object Person- -module object PersonHelper- -an instance of Person- -an individual object executing a singleton method-
###### answer 357
>Describe the relationship between singleton methods and class methods

357. A "class" method is really just a singleton method on the class object. e.g. class Person ... def Person.some_method ... this is just creating a singleton method on Person....
###### answer 358
>Show what it looks like to print out self for an instance of a class... what does it look like to print out the class object?

358. <Person:0x4402a0> .... and ... Person
###### answer 359
>If you have a variable and a method named the same thing(not smart) and you write that variable / method in your code what wins? and Why?

359. The variable will win ... you need a . operator to show it is a method self.var_name or you can also use () to establish it is a method
###### answer 360
>name a case when you have to indicate self even when calling an instance method on an object.

360. when you do 'setter' methods make sure you put the self and . operator... e.g. when calling name= "Shawn" you need to indicate self ... self.name= "Shawn" because ruby will think this is a local variable assignment firstly
###### answer 361
>What are the 3 types of variables?

361. Global, local, and instance... what about class variables??
###### answer 362
>! How can you get the 'friendlier' version of global variables in use? instead of all the $: and $! stuff?

362. require english.rb
###### answer 363
>Do subclasses and parents share the same class variables?

363. Yes. if you define @@var_name in the parent class... then re-assign it in the child ... it is changed in both!
###### answer 364
>What can not take an explicit receiver? what is the one exception?

364. a call to a private method. A private method can only be called by implicit `self` (no `.` ) ... the exception is setter methods ... you can use `self.age = 7` ... because otherwise if you just use `age` .. it will think you are defining a local variable
###### answer 365
>What are top level methods?

365. They are private methods in class Object .... thus anything descending from Object can call them ... of course because they are private you cannot call with a `.` operator
###### answer 366
>Why can top level methods be called from anywhere? 

366. They can be called from anywhere because they are private methods in Object. Object sits at the top.. it is in the method lookup path of every class (except BasicObject) ... they are private because imagine if they were public... you could then send any object the method name as a message
###### answer 367
>talk about this code... notice x will never be assigned a value
 if false
 x = 99
 end
 puts x

367. It will print nil ... even though x is never assigned.... ruby parses the code ... and will set aside space for x.... it is never given a value... but it's defalut value is nil ... this is because Ruby needs to know if local variables are local vars or they are method calls
###### answer 368
>What comparison operator is used in the when part of case statements

368. case statements use === for the whens... you need to define the === for a class if you want it to work in case statements
###### answer 369
>How can you do a repeat until loop in ruby?

369. use begin begin
...code... .... code ....
end until x > 10 end while x < 10
###### answer 370
>looping and an iterator are a bit different terms... what is an iterator?

370. An iterator expects a code block... an iterator yields something to code block....an iterator is an object that enables a programmer to traverse a container ....
###### answer 371
>when you create a block for a method call ... do you have access to the local variables created before the block was made? 

371. Yes the local variables are available in the block.... if you pass in a var of same name of course that has precedence and is in fact a NEW VARIABLE
###### answer 372
>when creating a block how can you make sure you have varibales that are local to the block scope and do not "pull" in variables from the outside, and possibly change them

372. in the parameter list put a ; followed by the variables you want to be local to this block scope |index,var;local_var1,local_var2| ... now these variables will not effect the ones that are in scope outsie this block
###### answer 373
>if you create a local variable in the block will it be available outside the block?

373. No.... the block will pull in the variables in existance but if you make a local variable and assign it in a block it will not be available outside the block
###### answer 374
>can you use rescue without anything after it?

374. Yes, it will just catch any exception and execute what is below it until it encounters an end
###### answer 375
>talk about using a resuce in a method or code block...

375. it is special because the begining of a method or code block serves as an implicit begin/end context ... you dont need to say begin... as long as you want rescue to govern the whole code block
###### answer 376
>Is ensure clause run even if an exception is not raised?

376. YES .. ensure is part of the begin/end structure ... it is run no matter what... you don't need resucues to have an ensure... it is part of the begin end... you can have begin ... ensure ...code... end no resuces
###### answer 377
>What are the literal constructors for String.new ... Symbol.new ... Array .. Hash, Range, Regexp, Proc (lambda)

377. "" : [] {} .. ... / / ->() {}
###### answer 378
>x = 1 + 2 is sytactic sugar ... how is it written verbosely?

378. x = 1.+(2)
###### answer 379
>How do you get modulus?

379. %
###### answer 380
>can your class define ! .... what does ! typically denote

380. sure... you can make the 'bang' operator do whatever you want ... typically will permanently change the reciever.... by custom only define a method with a ! if there is a similar method without a ! ...note 1.8.7 cannot define ! as a method
###### answer 381
>What is the splat operator? what does it do?

381. it is kinda an "un-array" operator... it turns an array into a bare list e.g. names = ["david","john"]; method_name(*names) // this will break out the names into a list to send
###### answer 382
>what happens with the following code?
 x = "We are number"
 y = 3
 puts x + y

382. type error. you must convert the string to a number... ruby will not automatically convert strings to numbers. you can override to_str in Fixnum class to get this to work
###### answer 383
> What is called when you try to do something like "Dog" + 9 ... does it work? 

383. This requires a string (strictly) so ruby calls to_str .... if it is defined ... it is not here... you will get a "TypeError" .. it will work if you define to_str in Integer
###### answer 384
>Describe evaluating a local variable that isnt initalized and an instance variable that isnt initialized

384. local var will produce an error puts x >> error ... puts @x >> nil
###### answer 385
>what happens if you try to access a nonexistnat element of a container or collection object?

385. nil returned asking for an_arry[7] when you defined 3 spots
###### answer 386
>list some valuble string methods 

386. capitalize upcase downcase
rjust(20) ljust(20) center(20,"*")
strip lstrip rstrip
chomp chop clear
replace delete("a") count("a")
crypt succ scan(//)
###### answer 387
>How do you find Ruby's encoding? what is the default?

387. __ENCODING__ USASCII
###### answer 388
>Write a hash with symbols as keys without the => notation

388. { name: "David", age: 29 } ... 1.9 only I think
###### answer 389
>what two libraries do you need to do date and time stuff?

389. require 'date' require 'time'
###### answer 390
>show how to get a Date object from a string

390. x = Date.parse("Jan 2 2009") the parse commmand will make sense of lots of different strings e.g."January 2 2009" is fine... so are lots of others parse returns a Date object
###### answer 391
>What is different about hashes in Ruby 1.9?

391. They are ordered... the hash remembers what order items were inserted.
###### answer 392
>Show how to iterate through a hash with an index

392. hash.each_with_index { |(key,value), index| puts "pair #{index} is #{key} >> #{value}"}
###### answer 393
>what are the Array and String methods?

393. They are built in methods that take an argument and create a String or Array from that. e.g. x = Array("under the sun") ... it will use the to_ary method to determine how to make it if not avail it will use to-a
###### answer 394
>What does passing in 2 arguments do within the array literal? e.g. array[3,2]

394. accesses the array at posiion 3 and returns two things... in an array of course.. you can use this to get, set , whatever

###### answer 395
>How do you add an element (or more) to the beginning of an array / take away first element? the end (add and take away)?

395. add >> a.unshift("dog") remove a.shift..... add >> a.push("dog","cat") remove >> a.pop
###### answer 396
>How can you get default values for a Hash when there is NO MATCH? talk about adding a block to the end of the call to new

396. Hash.new("Default_Value") an argument to Hash.new....this does not make the key/value come into existance ... though you can do this by supplying a block to Hash.new.. if you supply block you can set return value at end and do other stuff before that in the block ..this will execute when a nonexistant key is referenced
###### answer 397
>Show two ways to create a range... also what is difference between 2 and 3 dots

397. r = Range.new(1,100,false) false is inclusive .... r = 1..100 .... 2 dots is INCLUSIVE 3 dots EXCLUSIVE
###### answer 398
>What is the difference between #include and #cover for a range?

398. include will check if it is IN there... cover will check for < > e.g. r = "a".."z" include?("c") yes ...cover?("abc") yes but "abc" is not included .. cover is for alphebiting checking stuff
###### answer 399
>How do you use a set? What is it?

399. require 'set' as it is not in Ruby core... a set is a collection... everything in Set is unique... you can merge .... get the union + ... difference - .... intersection & of sets
###### answer 400
>What are IO objects of IO class...?

400. IO objects represent readable and/or writable connections to disk files , keyboards, screens and other devices. An IO object is just like any other object... you send it messages and it returns results
###### answer 401
>What are the IO constants that are automatically set when a program starts?

401 STDIN, STDOUT, STDERR ... these are IO objects that can be written to and read from where appororiate
###### answer 402
>What is the global var for the global input record seperator ?

402. $/ ... this is what each responds to for the IO object ... is initally set to "\n"
###### answer 403
>Explain how you would change the standard output to say a file instead of the screen...

403. you would redefine the global var $stdout like so ... record = File.open("/tmp/record.txt", w); $stdout = record; .... this will now write all STDOUT to that file... you should not change a constant i.e. STDOUT ... just modify the global var
###### answer 404
>Every object has two classes... name them

404. The class of which it is an instance and .. it's singleton class
###### answer 405
>How do you get inside the definition body of a singleton class?

405. class << obj ... the << obj nototion means 'the anonymous singleton class of obj' ... this prys open the singleton class of obj
###### answer 406
>Singleton classes of class objects sometimes called?

406. Metaclasses
###### answer 407
>what is a special behavior of singleton methods of Class objects? 

407. The singleton methods of a class object are also available to subclasses of that class. B < A A's singleton methods (class methods) are available to B
###### answer 408
>What does the tap method do? what objects is it available for?

408. tap will yield the reciever to the code block ... then returns the reciever "hello".tap {|string| puts string.upcase }.reverse HELLO >> "olleH"
###### answer 409
>How can you modify a method so that additional functionality is added to it... it is called a passthrough...

409. You alias the old method alias __old_reverse__ reverse ... then you def reverse ... and add what you want to... then within that... call __old_reverse__
###### answer 410
>How can you open up the singleton of an object to add methods without the class << obj type of thing? 

410. obj.extend(Module_to_add) .... and you can mix in modules ... or def obj.method .... end
###### answer 411
>How do you create and call a new Proc object? 1.9

411. pr = Proc.new { puts "Inside a Proc's block"} pr.call
lambdas must have correct number of arguments
###### answer 412
>what does the proc method and lambda method do? 1.9 

412. proc produces a Proc object .. lambda produces a slightly different varient of Proc object ... both create Proc objects ... lambdas that include a return will not exit surrounding method... 
###### answer 413
>when you supply a code block to a method are you in fact sending a Proc object?

413. No.. the code block is part of the syntax ...of the method call. blocks are not method arguents either... they are code blocks ad that is a thing unto intself sytactically
###### answer 414
>if you have a &block_var in your methods definition argument list and you pass in a block... does this create a Proc object?

414. Yes... this will create a new Proc object ... that you will call with block_var.call
###### answer 415
>if when calling a method you have a proc (Proc object) that you want to use as the code block ... how do you tell the method that you want this proc (Proc object) to be the methods code block? 

415. when you call the method you put a & in front of the proc (Proc object) this triggers Ruby into knowing your intentions... this will tell the reciever that this is supposed to be the code block.... of course you can't do capture_block(&p) { puts "this is the code block"} .. because &p is indcated as the code block... AND you have supplied a { code block} ... cant do this
###### answer 416
>Do code blocks preserve the variables that were in existence at the time they were created?

416. Yes.. they stay in scope and remain in scope no matter where or when you call it
###### answer 417
>can you call a proc with the wrong number of arguments

417. Yes... unlike methods they can be called with wrong number of args... you can use a *an_array to sponge up all arguments too ... a lambda must have the correct number of args
###### answer 418
>What is the difference between lambda and proc's creation of Proc objects?

418. 2 things... lambdas must have correct # of arguments...procs do not .... ALSO ...A return statement in a lambda triggers and exit from the body of the lambda... a return in a proc tiggers a return from the method that contains the lambda ... NOTE if a proc has a 'return' in it you MUST be in a method or this will be an error.
###### answer 419
>How can you get a bound method? what is it?

419. jim = Person.new; meth = jim.method(:say_hi); meth.call ... this is a bound method
###### answer 420
>How can you get an unbound method... and then how can you bind it?

420. meth = Person.instance_method(:talk) you can then bind it to an object of that class though meth.bind(jim) where jim is an instance of person
###### answer 421
>If you have class B < A ... and .. you have an initialize method in A (the superclass) but not in B.. and you do a x = B.new ... does the superclass initialize method get run?

421. Yes, the initialize of the superclass will get run.. unless you have a initialize in B then that will override
###### answer 422
>What is $SAFE

422. it is a number you can set from 0 to 4 to gain protection from dangers like rouge file writing requests.
###### answer 423
>How can you pry open an instance and execute statements as if you were inside that instance?... thus you do change 'self'

423. x = Person.new; x.instance_eval("puts @x") ...(or a code block { puts @x} ) this will open up the instance and let you get the instance variables... even if no accessor was defined... you can still get into it
###### answer 424
>What is the difference between instance_eval and instance_exec?

424. they are the same but instnace_exec takes arguments and then a code block... the arguments it takes will be passed to the code block x.instance_exec("s",obj) {|str,obj| self.split(str); puts obj ... etc}
###### answer 425
>What will class_eval do?

425. puts you inside a class definition body. Person.class_eval do def a_method; puts "hi"; end; end this opens up person... and you still have access to local variables unlike when you use a class Person to open it up... of course if you do a 'def' in here you go out of scope for the local vars though
###### answer 426
>what does define_method do? how is it useful

426. you pass define_method a string or a sybmol and it will define a method in that class.. you also pass it a code block this will be the methods body.... this lets you use local variables that would not be available when using def method_name construct (as this creates new scope)
###### answer 427
>How do you implement a thread? 

427. t = Thread.new do \\ you assign t = if you want to be able to wakeup / join / stop / alive? the thread from outside the code block
...code ...
rescue Exception
puts "message"
Thread.exit \\ optional of course .. thread can terminate normally
end
###### answer 428
>if your program terminates with a thread still running what happens to it? How can you make sure it keeps running?

428. The thread will stop when the program terminates... you can call the instance method 'join' on the thread to keep it going...
###### answer 429
>What is a fiber?

429. It is like a thread but it does not start until you tell it to with 'resume' .... create with f = Fiber.new do ... code ... end
###### answer 430
>How do you return from a fiber to the calling context?

430. call the class method Fiber.yield .. you can resume with f.resume
###### answer 431
>How can you get a socket listening on a port?

431. require 'socket'
s = TCPServer.new(3000)
conn = s.accept
conn.puts `date` \\ backticks `` are for a system command
conn.close
###### answer 432
>Threads run using code blocks... if you change a local variable in the thread code block will it be changed when the code block exits?

432. Yes... just like all code blocks... the code block gets the current scope and can change the current scope
###### answer 433
>the $1 $2 , ... $n are global reg ex match variables ... what about threads in respect to these?

433. They will output matches based on what thread you are in.
###### answer 434
>Describe Thread keys /values 

434. these are a storage hash for threads... you can get at the current thread with Thread.current ... Thread.current[:message] = "message here" will store this key/value pair
###### answer 435
>What is the difference between system("date") and `date` ?

435. the backticks ... the return value is the output of the program you run...
###### answer 436
>List 7 callbacks, or hooks that are common to tie into during the execution of a Ruby program

436.   
    1. A nonexistent method being called on an object -- ** implement method missing
    2. A module being mixed into a class or another module -- ** def self.included(c) for the class or module... this is called automaticly by interpreter when including
    3. An object being extended with a module -- ** def self.extended(obj) in the MODULE (you cant extend a class)
    4. A class being subclassed (inhereted from) -- ** def self.inherited(subclass) in the class you want to moniter for subclassing
    5. A reference being made to a non-existant constant -- ** def self.const_missing(const) within you could use const_set(const,1) to set the constant
    6. A instance method being added to a class -- ** def self.method_added(m)
    7. A singleton method being added to an object ** def self.singleton_method_added(m)
###### answer 437
>How can you get a stacktrace of your execution? 

437. The top level method caller
###### answer 438
>What is the literal constructor for a regexp?

438. //
###### answer 439
>What responds to .match?

439. Both Regualarexpressions and Strings respond to .match
###### answer 440
>What is the difference between .match and =~ ?

440. match returns an instance of MatchData =~ returnds the index where the match started ... both are equally useful for yes / no answers to if there is a match
###### answer 441
>What are the 3 possible components of a regexp?

441. 1. Literal characters (match this charactor) 2. the dot wildchard character (.) (match any charactor) 3. Character classes (match one of these charactrs)
###### answer 442
>How do you match a "special charactor" what are the special charactors?

442. escape it the a backslash \ .. e.g. /a\?/ matches a? .. must escape the ? .... ^ $ ? . / \ [ ] { } ( ) + *
###### answer 443
>Name some special escape secquences for common charactor classes

443. \d for any digit ... \w any "word" charactor .... \s ... any whitespace .....
###### answer 444
>What is a regexp "capture"

444. when you isolate and save substrings of the string that match particular subpatterns
###### answer 445
>How do you get a capture? talk about it a bit..

445. you capture parts of the regexp with ( ) around parts of the regexp. each ( ) will save its matches into $1 .. $2 ...up to n ... where n is the number of ( ) in the regexp match .... these globals only save the last regexp done... to save it you would need to assign the Matchdata object returned to a variable
###### answer 446
>if you have a Matchdata object.... what does the matchdataobject.string method do? matchdataobject.captures meth? What are some useful Matchdata methods?

446. matchdataobject.string returns the origional string matched against ... matchdataobject.captures[1] returns the first capture ...[0] gives the origional string too .. .pre_match gives part of string before match .post_match gives the part after ... .prematch .postmatch .captures
###### answer 447
>Can you use nested () in a regexp?

447. Yes, each ( left parenth is how you count the capture e.g. first ( encountered matches [1] ...
###### answer 448
>Describe some regular expression quantifiers, anchors, and modifiers

448. Quantifiers let you specify HOW MANY times in a row you want to match something
? ... 0 or 1 matches
* ... 0 or more matches
+ ... 1 or more matches
Anchors do not 'consume' charactors they express a constraint: a condition the must be met before the matching of charactors is allowed to proceed
^ ... anchors the beginning of a line
$ ... anchors the end of a line
\A .. anchors the beginning of a string
\z .. anchors the end of a string
\Z .. anchors the end of a string (except for a final newline)
\b .. anchors a word boundary
Modifiers -- a modifier is a letter placed after the final closing forward slash of a regexp literal
//i ... makes the match operations be case insensitive.
//m ... makes the '.' wildcard charactor match ANY charactor including newlines
//x ... makes the regexp ignore whitespace


###### answer 449
>What can you do to a 'greedy' regualar expression to make it not greedy?

449. Add a ? after the + or * e.g. abc!def!hij!.match(/.+!/) will match the whole string ... change the reg to /.+?!/ will return to first part of the match. This makes the regex match 0 or 1 or that part... not the whole thing
###### answer 450
>How can you match a specific number of repetitions within a regular expression? e.g. you have 239-9769 and want to match that it is a phone number with 3 digigts a '-' and then 4 digits

450. {} braces specify how many repetions in a greedy match. so the phone number reg expression would be /\d{3}-\d{4}/
###### answer 451
>How can you specify a range for repetions in regexp matching?

451. {1,10} will match betwen 1 and 10 ... {3, } will match at least 3
###### answer 452
>How would you write a look ahead assertion? What is it?

452. A look ahead assertion will verify that the match continues but WILL NOT CONSUME it.... (?= ) ...e.g. /\d+(?=\.)/ will match any number of digits that have a period at the end 456 678. 999 matches 678 but NOT the . and it is not consumed so be careful about how the pattern continues
###### answer 453
>How would you write a look behind assertion?

453. (?<=) ... add the < ... each with its negative are (?=) (?!) and (?<=) (?<!)
###### answer 454
>Show how to do interpolation on a Regexp

454. str = "def"; /abc#{str}/;
###### answer 455
>What if you are interpolating a string into a regular expression that has 'special' charactors e.g. a '.' the period takes on special significance in a regexp... how can you account for this?

455. re = /#{Regexp.escape(str)}/
###### answer 456
>Name some well know methods that take regular expressions as parameters

456. .scan .split .sub .gsub
"This is a string 55 that looks for numbers 88 and returnds them all in an array".scan(/\d/) do |var| ... end will pass each sucessful match into the block
"first=david;last=black;".split(/=|;/) ... will split and return and array splitting on = and ;
"ooooohhhhh".sub(/i/,"a") ... will just replace FIRST match
"oooooohhhh".gsub(/i/,"a") ... will replace ALL GLOBAL sub
###### answer 457
> empty

457.
###### answer 458
>What does grep do?

458. grep checks an enumerable for matches. you pass in what you want to match against. for an enumerable object grep does a filtering operation on each element based on === ["USA", "UK", "France", "Germany"].grep(/[a-z]/) {|country| country.upcase} ...will match France and Germany and then do a map operation on each match... the block is optional... the block is to map/transform the results array
###### answer 459
> empty

459.
###### answer 460
>Can you override the assignment operator in a class? as in just override = ? 

460. No you cannot override the = e.g. def =(rvalue) ... you can override an assignment though as in def name=(rvalue)
###### answer 461
>How do you use Rdoc and ri together (simple example)

461. from the command line run rdoc filename.rb -r this will parse the file the -r will format for ri ... then you can run ri ClassName and it will give you the Roc about that class.
#:title:ClassName
#Author:: Shawn
#Stuff about the class below // this is the basic format for Rdoc and ri which displays Rdocs
class Classname

end
###### answer 462
>How can you see all the gems with thier documentation on your machine?

462. gem server ... then go to localhost:8808
###### answer 463
>Describe two ways to implement a 2D array in Ruby.

463. a= Hash.new a = Array.new(5) {Array.new(5,"default")}
a[[1,2]]= 23
a[[5,6]]= 42
###### answer 464
>What is a DNS server?

464. It maintains a database of human readable names and the matching machine readable IP address. It is a hierachy. e.g. your ISP will maintain a table... if it does not have an item in its database it will query higher up server. there are 13 main servers. 10 in USA. Lower level ones get info from the higher ones.
###### answer 465
>talk about the last argument passed into a method...

465. Well... this spot is where you would pass the block in if you were going to name it. &block. ... it is also where you can pass in a hash and omit the curly braces.
###### answer 466
>How do you change which ruby textmate uses?

466. In texmate... open up preferences... advanced and add the path to the ruby you want to use... put it first as I think it looks up PATHS until a success is found... so put it first.. to find out which ruby you are using at terminal say 'which ruby'
###### answer 467
>Can you say x = Ojbect.new then open up the singleton of x with class << x ... code .. end ?

467. Yes
###### answer 468
>How do you output a line but not do a \n?

468. print "hello"
###### answer 469
>Why would you def <(other) or def >(other)?

469. If you include comparable and you need to implement less than and greater than
###### answer 470
>What have you decided is the best way to form strings given most use cases?

470. <<END For multiline
I use this
END
%q[When I need " or ' in a string I will use %q or %Q]
"I will use double quotes for string interpolation #{variable} stuff"
'Single quotes for normal stuff'
###### answer 471
>if you have a method defined like ... methname(&block) ... end .... what if you do not pass a block to it when you call it?

471. Nothing... there is no block_given ... nothing assigned to &block ... you would only get a problem if you tried to block.call ... cause nothing was passed in
###### answer 472
>can you say something like ... return x,object,name,7,9 ... at the end of a method?

472. Yes. It will return an array made up of the comma sepereated values
###### answer 473
>When you require a file do you need to put the .rb extension on it? e.g. require 'set.rb' do you even need the quotes?

473. No you do not need to add the .rb extension (I think)... yes you do need quotes though
###### answer 474
>In Ruby are arguments passed by value or passed by reference? ** double check this with some googeling to get whole story

474. Arguements variables reference objects, then those objects are passed to the method. You can do what you want with those objects after they are passed. The parameter in the method will name the object while the method is in scope... The variable is translated into an object and the object is then passed
###### answer 475
>Can you call a block that expects 4 arguments with zero arguments

475. Yes, it appears so... I think the parser will see these as local variables and set them to nil... if you use them in the block they will be nil, because nothing was passed in. you cant do this with method calls... you get a wrong number of arguments error
###### answer 476
>REVIEW ALL SCOPE RULES IN PARTICULAR ABOUT BLOCKS AND SUCH if you pass in a variable reference to a block... change that reference to a new object withing the block.. exit block ... what is the value of the reference after you leave the block?

476. Be careful here as I was confused... when you pass in a value to a method e.g.
x = [1,2,3]
def test(x)
...code
x = [99,99,99]
end
test(x)
... you are NOT changing the same x that was passed in... when you exit... x is not changed... you have created a new local variable x in the method and assigned it (naming it x) to the object being passed in... if you want to change x... then do something like x.replace([99,99,99]) mutate it... you are passing an object... the variable is just its name
###### answer 477
>What would you use extra () within a method definition parameters list for?

477. These could be used to group an array. def meth((x,y),z) ... end call with ... meth(array_with_two_elements,8) ... the array is passed intp the () grouping and then broken out into those vars
###### answer 478
>Is this true? You can pass in the wrong number of arguments to a method... but you MUST pass in the correct number to a block...

478. NO... think about all the Wrong number of arguments errors you get.. this is for METHODS.. blocks however or procs do not require the exact right argument list .. will be set to nil ... LAMBDAS and METHODS need the right argument matching
###### answer 479
>How can you get the last element of an array?

479. array.last array[-1] array.pop will modify array
###### answer 480
>What does !! operator do in Ruby?

480. It converts a value into true or false
###### answer 481
>If you are in an each loop and and exception is raised that causes the program to terminate how can you execute the rest of the each loop?

481. Just handle the exception. it is that simple :)
###### answer 482
>Describe the scope of variables and the use of while, until and for loops

482. local variables in scope will be available within the while, until and for loops. variables created in these loops are availle outside of the loop as well
###### answer 483
>Talk about ruby being pass by value or pass by reference

483. When you pass a variable into a method you are passing an actual object. The parameter is a local variable to that method... if you change! the value the variable references then it will be reflected after the method ends because this object is mutable and you have just mutated it...if you just assign that paremeter a new value.. that old value (object) still exists and outside of that method there may still be things pointing to it that come back into scope.
###### answer 484
>What does partition method do for a string?

484. partition takes a regexp and returns an array with the part [0] before the match, [1] the match, [2] after the match
###### answer 485
>List all the % delimeters

485. Modifier Meaning
%q[ ] Non-interpolated String (except for \\ \[ and \])
%Q[ ] Interpolated String (default)
%r[ ] Interpolated Regexp (flags can appear after the closing delimiter)
%s[ ] Non-interpolated Symbol
%w[ ] Non-interpolated Array of words, separated by whitespace
%W[ ] Interpolated Array of words, separated by whitespace
%x[ ] Interpolated shell command
###### answer 486
>How can you iterate over numbers from 5 to 1 (backwards)

486. 5.down_to(1)
###### answer 487
>What is the difference between using a statement like .. for i in (1..8) .... end and (1..8).each do |i| ... end .... 

487. The for loop is part of the current scope... anything done in the loop is available outside the loop.... the each loop sets up a block
###### answer 488
>In Ruby you actually can change constants... but how can you really make a CONSTANT a CONSTANT?

488. freezeing might be an answer... but not as simple as Const = 9 Const.freeze ... this doesnt work... **left as note*** the previous... you dummby of course it doesnt work.. you are RE-ASSIGNING to CONST ... if you try to modify CONST in place it will work because it is frozen, but of course you can just say ='s ... freeze works ... but not if you re-assign
###### answer 489
>What does Object mix in to get all its power? :)

489. Most of Objects instance methods are mixed in by Kernal
###### answer 490
>What is an enemerator? 

490. An enum has state. An Enumerator wraps an interation. Most methods come in 2 forms.. one with a block, and another without a block. A call to an_array.each with a block just passes each element into the block. A call to an_array WITHOUT a block will return an Enumerator which wraps this iteration. A class which allows both internal and external iteration. Most methods have two forms: a block form where the contents are evaluated for each item in the enumeration, and a non-block form which returns a new Enumerator wrapping the iteration.
ary = [1,2,3,4,5] # I think Enumerator is only supported in Ruby 1.9
enum = ary.each # Just made an Enumerator object... this has state, instance variables...etc
enum.next # this will advance through the enum I guess that there is an instance variable that saves the position in the enum
###### answer 491
>THE CODE BLOCK GETS THE CURRENT SCOPE AND CAN CHANGE THE CURRENT SCOPE!!! you only change the scope when you go into a def, a class definition, or a module definition 

491. True. New local variables created in the block though will be lost
###### answer 492
>What does defined? return? ... is it a keyword or a method?

492. defined? is a KEYWORD. defined returns a STRING, or NIL
###### answer 493
>

493. if the first item in the right expression is true it returns that, otherwise it returns the second... if neither was true it would return false. this can be written ... @name ||= ''
###### answer 494
>How can you find the postion of an element in an array?

494. an_array.find_index("word") ... you can also use block form of course like most stuff
###### answer 495
>what is difference between p and pp

495. p calls obj.inspect and prints ( p foo = puts foo.inspect ) pp does "pretty_inspect"... they are very similiar you have to require 'pp' ... p uses inspect... pp uses pretty_inspect... puts uses to_s ...the pp library adds #pretty_inspect methods to many classes such as String, Array or Struct
###### answer 496
>Describe {instance|module|class}_{eval|exec} family of methods

496. All variations of {instance|module|class}\_{eval|exec} change the current context, i.e. the value for self: obj.instance_{eval|exec} opens the singleton class of obj, while ClassName.{class|module}\_{eval|exec} opens the class definition body itself.
Of course, instance_{eval|exec} are available on any Ruby object (including modules), while {class|module}\_* are only available on Module (and thus Classes) module_{eval|exec} is the same as the corresponding class_{eval|exec}
###### answer 497
>When you create a class what is the default behavior of ==

497. It is the same as equal? ... thus it checks that the two objects have the same object_id
###### answer 498
>What is the difference between instance_of? and kind_of?

498. instance_of? must be an instance of that exact class... kind_of? is true for specified class and all of it's subclasses
###### answer 499
>What class === only defined for? what if === is not defined for a class?

499. It is defined for Regex .... === defaults to == .... it is mainly for case statements. location = "area 51" case location; when /area.*/ .... the === definition in Regex allows this because case operations use === (which usually default to ==)
###### answer 500
>What method does Hash use to compare a key passed in with the already stored keys? i.e. you can change the lookup behavior of a hash by overriding this method...

500. eql? ... eql? is mainly used for Hash ... otherwise just use ==
###### answer 501
>Name two classes that you cannot declare singleton methods on instances of objects...

501. Well any Numeric classs e.g. Integer... you cant declare a singleton method ... 1.do_this ... also Symbols.. can't declare singleton methods
###### answer 502
>If you have a bunch of ways to create an instance of a class that all differ a bit how should you do this?

502. You should create class methods that make the instances instead of complicated parameters supplied to Person.new ...i.e. Person.supervisor Person.cook each create people but the class methods create different versions... supervisor and cook each will call new
###### answer 503
>class Parent; def self.who_am_i; puts self; end; end; class Child < Parent; end; if you say Child.who_am_i what is printed?

503. Child. The class methods of Parent are inherited by Child .. SELF THOUGH IS THE OBJECT TO THE LEFT OF THE METHOD CALL
###### answer 504
>If you have a module and want to store a useful method in there that you can access without instanciating any object how would you do it?

504. in the module def self.method_name ... you can access this with ModuleName.method_name or ModuleName::method_name .. if you do not do the self it can only be used when mixed into a class because it would have to be instciated.. when you add the 'self' you are making it a module-level method
###### answer 505
>Do code blocks return a value? i.e. you pass a code block into a method... 

505. Yes, Like almost everything in Ruby a codeblock will return the last expression that the code block executes.
###### answer 506
>Describe the term "Execute Around" and how it pertains to blocks

506. When you have some common functionality where things need to be executed before and after ... and these "before" and "after" evemts never change you can define these events in a method with a `yield` sandwiched between ... you pass in code blocks which have things executed around them
###### answer 507
>Describe a danger when creating a block that you hold onto for a while... pass it around maybe...

507. if you create say big_array = Array.new(1000000) and in the same scope declare that block that block will keep the array in memory! the block holds onto local variables that were in existance when the block was created
###### answer 508
>Describe lazy initialization with code blocks

508. if say you have a Document class and instead of reading all the content into a vairable when a Document object is created you save that part of reading the content till you need it. you pass a code block to the initialization and this block gets run when you actually call on the content... by using a code block you also can change how you get the content... maybe read a file... maybe over http...etc
###### answer 509
>How do you make "new" method private for a class? i.e. x = Person.new

509. You would have to say private_class_method :new .. to get new objects you will need to make a 'create' class method that calls new... make sure there is not a reciver in front of 'new' you can call new from within the 'create' method as 'self' (the class) is assumed as the reciever
###### answer 510
>Describe the at_exit hook.

510. at_exit takes a block and will execute this when the Ruby program is terminating... at_exit's are executed in a LIFO order
###### answer 511
>Describe set_trace_func and its use

511. This method you supply a block to ... it gets called whenever a method is executed, returned, class opened exectption called or LINE of CODE EXECUTED... everywhere :) e.g. proc_object = proc { |event, file,line,id,binding,klass| puts "#{event} in #{file}/#{line} -- #{id} #{klass}" } ... set_trace_func(proc_obj)
###### answer 512
>Describe the pattern where you are mixing in a module where you have some methods that should be mixed in as instance methods and some methods that should be class methods 

512. You would achive this by creating a module that will be `included` in the class... within that included module you will def self.included(klass) klass.extend(nested_module) end .. within your module you nest a module that will be used to extend the class where this is all getting mixed in.
###### answer 513
>Describe what you get when you use SimpleDelegator ... after you have required 'delegate'... how to use...

513. this creates a wrapper around a class... you do a class DocumentWrapper < SimpleDelegator; def initialize (real_doc); super(real_doc);end;end when you create an instance of DocumentWrapper.new(doc) where doc is a Document.new ... the wrapper effectivly implements method missing forwarding all messages to document
###### answer 514
>Describe the PathName class

514. This is a class that can do lots of file system programming tasks
###### answer 515
>What is the difference between is_a? and kind_of?

515. Nothing. They are the same. They check if klass is_a?(klass) is in the inheritance hiearchy ancestors also checks modules mixed in
###### answer 516
>How can you dynamically define instance methods in a class?

516. Of course you can always monkeypatch... reopen and redefine. You can also add logic within the class definition to create methods based on certain conditions. ... another example.... def self.enable_encryption( enable); if enabled def encrypt_str; ... end else def encrypt_str; ... end; .. this allows you to (through a class method) change the def of the encrypt instance method
###### answer 517
>how do you get a charactor in a string at position 2 in 1.8 and 1.9?

517. 1.9 str[2] 1.8 str[2].chr
###### answer 518
>Talk about how Rails can use methods that are added to the script on the fly.

518. It must reload the __FILE__ ? it must also remove all the instance methods first with .. instnace_methods(false).each do |method| remove_method(method) end
###### answer 519
>talk about providing a block to an object being created with a call to new.. eg. jim = Person.new do |person| .... end

519. In the class definition you must have within the initialize method ... def initialize ... yield(self) if block_given? ... this will pass the new object into the block for more initialization.... YIELDING SELF AT THE END OF INITIALIZE IS NICE ... YOU CAN NOW SUPPLY A BLOCK TO THE ".new" mehtod
###### answer 520
>When you define a method dynamically for a class using define_method(method_name) how do you get this newly defined method to have parameters?

520. You just put the parameters in the block to define_method(method_name) do |var1,var2,var3| ...code .... end these var1's will become the paramters to the new method defined in the class
###### answer 521
>How can you end the execution of a block during its execution? 

521. break
###### answer 522
>Talk about some clever ways to create "singleton" type objects in ruby... as in only one instance of each 

522. You can include Singleton ... you can use the Module approach (you can't get lots of BigBoss's ... just this one because it is module not class)
module BigBoss
@index = -1 *** instance variables here are just like class instance variables
@locations = %w{office floor home}
def self.move
@locations[@index = (@index + 1) % @locations.size}]
end
end

Or just create a generic object and add methods to it!
MySingleton = Object.new
MySingleton.instance_eval do
@count = 0
def next
@count += 1
end
end
###### answer 523
>What are the 3 scope gates? Where scope changes?

523. Class definitions, Module definitions, Methods.... ie these three keywords class , module, def ... these change scope ...
###### answer 524
>describe a top level instance variable? 

524. A top level @instance variable is accessible whenever 'main' takes the role of self. This might be better than a global variable
###### answer 525
>Talk about rescuing from Exception ie ... in code .... rescue Exception => er

525. You should never do this. This will catch too much... at WORST case rescue StandardError ... catching Exception will rescue you from things lke Interupt ... cntl-c or SyntaxError
###### answer 526
>What are the differences between new method and initialize method?

526. New is an instance method of Class ... it is used by [say] Person to create a new person object. Initialize is an instance method of the Person object. Class also has a class method "new" j = Class.new { def meth1 .. end def meth2 ... end } this is an anoymnous class that you could assign to a constant
###### answer 527
>What is self?

527. Self ... simply... is the object to the left of the method call. at the top level... self is main... of course... it is -kinda- to the left of the method call