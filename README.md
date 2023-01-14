# Frequently asked MEAN Stack Interview Questions

  ` Click ⭐if you like the project. Pull Request is highly appreciated. `

  Essentially, MEAN stack is an open-source technology that includes four JavaScript-based technologies including MongoDB, ExpressJS, Angular, Node.js (MEAN). By learning and mastering MEAN stack, you can enjoy the perks of a host of domains for developing web apps and dynamic websites.

## ![My Skills](https://skills.thijs.gg/icons?i=js,nodejs&theme=dark)  JS + Nodejs
   - Why? What?
	
   - EventLoop
	
   - How single threaded? 
   
   - threadpool? Libuv module

   - why express?  
        - middleware? example  
					
   - streams
   
   - event emitter
	
   - how to handle unhandledRejection, uncaughtException
   
   - module.exports vs export

   - higher order function
	 - callbacks
		- real use case  
		- error first callback
		- callback hell ? 1. example 2. how to remove the callback hell
					
	 - promises  
	   - real use case  
	   - chaining  
	   - promiseall vs race vs allSettled
			
	 - async/await  
	   - real use case   

  - Hoisting  
  	- let, var, const, normal funtion  
	- why function as expression not hoisted.  
	- "use strict"  

  - null undefined undeclared
		
  - call, apply, bind  / context switching
  
  - prototype
  
  - closure
  
  - classes in es5 & es6

  - array > filter, map, reduce, foreach, slice, splice  
	
  - functions > iffe, expression, normal function  

 - es6 features  
	 - fat arrow functions > significance and use  
	 - classes  
	 - literal string  
	 - destructuring object  
	 - rest and spread operator > significance and use  

  - Scope in JavaScript > global local lexical	
		
 - File system(fs)  
	 - asynchronous > methods  
	 - synchronous > methods  
	
  - settimeout, setimmediate, setInterval 
	
  - cron job
					
### Advance Question 
	web worker
	threads
	cluster,fork, process spwan
	cors issue > resolution & internal working
	virtual dom,real dom,real dom,shadow dom  
	scaling
	
## ![My Skills](https://skills.thijs.gg/icons?i=ts&theme=dark) TypeScript
	Will Add Soon

## ![My Skills](https://skills.thijs.gg/icons?i=angular&theme=dark) Angular

 - Angular start point  
	purpose index.html and main.ts
	
  - Decorators?  
  
  - Module? imports,declaration,providers
	
  - Service?  
	@injectable => providedin  
	how to make singleton service > 1. providedin="root" & 2.providedin="Module_Name"  
			
  - Components?  
	 - Lifecyclehooks?  
		- children method  
		- why ngOnchanges called first  			
		- parameters  
		- can we provide service directly in component? how? how many instances created?  
		
  - Pipes  
	 - Custom Pipes ? how to implement and real example  
	 - Pure pipes  
		
 - Directives 
	 - Types > why component is directive  
	 - Custom directive ? how to implement and real example  
	 
 - Can we use `*ngIf` and `*ngFor` on single line
	
 - Content projection
 
 - Elvis operator	
		
 - Observalables vs promises?  
	 - why observables are prefered  
	 - Subjects? Subjects vs BehaviorSubjects vs ReplaySubjects  	
	 - observables chaining  

 - Interceptor > how to use ? use cases
	
 - Purpose of below files and atleast rough idea of contents  
  	- package.json & package-lock.json  
	- angular.json  
	- tsconfig.json  

 - local storage, session storage and cookies

 - Karma & Jasmine? describe, it, Spyon, Spy, beforeEach, expect

 - Event binding & Property binding
	
 - Event bubbling 
  	- how to stop propagation vs prevent default  
	- event delegation  
		
 - Url/dom sanitization

 - Share data between component methods > total 5 method (state any 2-4)
	
 - ng-container vs ng-template
	
 - Security features in your application
	
 - Change detection  
	 - ngzone  
	 - which component lifecyclehook called

 - Routing  
	 - purpose of base href tag  
	 - lazy loading > what it is? how to implement  
	 - router outlet, router links, router state, routerLinkActive  
	 - Wildcard route  
	 - Route Guards > Methods and purpose (CanActivate, CanActivateChild, CanDeactivate,Resolve and CanLoad)

 - Just-in-Time (JIT) vs Ahead-of-Time (AOT)
 
 - rxjs, rxjs operators with example

## ![My Skills](https://skills.thijs.gg/icons?i=mongodb&theme=dark) Mongodb
	Why mongoose? > any other orm  
  		find  
  	aggregate > stages  
    	joins($loookup) > foreign key, left outer join only  
    	optimization  
  	replica  
  	sharding  
  	cluster  
	
### JWT 
	Why?  
   	   (rough idea) how it works  
	methods > use  
  	bcrypt vs jwt  
	drawbacks
	
### RestApi
	Why?  What?  

### Programs
	string reverse (using inbuilt methods and by loop) 1. simple 2. sentence( normal, word by word reverse)  
	string manipulation (using inbuilt methods and by loop)  
	fibonacci series (using recursion and loop) 1. simple 2. till n terms  
	palindrome(string and number)  
	factorial of number (small number and big number)  
	array (sort, find,remove duplicates, replace value, reverse, find 2nd highest number)  
	prime number( single number, range, next of given number)
	let var const  
	0.1+0.2==0.3 (reason why not equal)  
	console.log(3>2>1)	console.log(1<2<3)  
	console.log(1 ?? 3)  
	methods for creating object & object cloning(shallow & deep) with example

