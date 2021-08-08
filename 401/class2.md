 ## Node Ecosystem, TDD, CI/CD

 ### Array.map() :
- The Map method in js basically its map all other the elments,or in other way its calling a specific function on each element present in the parent array.

![img](https://res.cloudinary.com/practicaldev/image/fetch/s--94BGHt73--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/7vncgvcjv659kt1itxoy.png)


## Array.reduce()
- The reduce method used to reduce the array to a single Value and exectes for each value(from left -to right ),and it will retrun a value of the function is stored in a accumulator.

![img](https://miro.medium.com/max/2000/1*dhTC_FFgiH3mKROrnDj12w.gif)


## superagent() 
- Its a light-weight progressive ajax API crafted for flexibility, readability ,its a HTTP client libraries. 
![img](https://files.speakerdeck.com/presentations/05e00950cd660131fa3126624a8aace7/slide_21.jpg)
![img](https://res.cloudinary.com/practicaldev/image/fetch/s--zX48DubG--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cx8kqbv035k5w9y64c9z.png)
 request
   .post('/api/pet')
   .send({ name: 'Manny', species: 'cat' })
   .set('X-API-Key', 'foobar')
   .set('Accept', 'application/json')
   .then(res => {
      alert('yay got ' + JSON.stringify(res.body));
   });


   ## explain promises in javascript :
   - It represent processes that are already happening ,and its been  used to handle asynchronous operations in JavaScript.

   ![img](https://www.freecodecamp.org/news/content/images/2020/11/consumer_executor.png)
   ![img](https://miro.medium.com/max/1024/1*yAFctUA8useVWRbC-nWhBA.png)


   ## all callback functions considered to be Asynchronous? 
   - Callback doesnt make a function asynchronous,so its only passing functions as arguments.

   ![img](https://miro.medium.com/max/1200/1*ZcAVLAfcH5gZcVppRykWmg.png)
   ![img](https://bs-uploads.toptal.io/blackfish-uploads/uploaded_file/file/190741/image-1582215000590-ffa807c19d5f6959de485fc66664e123.png)