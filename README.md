<h1>Reference</h1>
<a href="https://www.traversymedia.com/">Brad Traversy's</a> excellent youtube <a href="https://www.youtube.com/watch?v=wqhNoDE6pb4">tutorial</a>

<br> <br>


<h1>Notes</h1>

<h2>Note 1</h2>

There was actually a minor issue with the tutorial that was causing the following error at the final minutes of the course:
<br>
<h6><em>Nest can't resolve dependencies of the ItemsService (?). Please make sure that the argument at index [0] is available in the AppModule context.</em></h6>
<br>

Now, I would like to acknowledge and express my sincere thanks to 
<a href="https://github.com/DanielFryy/NestJS-Crash-Course-TraversyMediaTutorial">Daniel Freire</a> who had successfully resolved the issue before, and I, just like 
<a href="https://stackoverflow.com/questions/56870498/nest-cant-resolve-dependencies-of-the-itemsservice-please-make-sure-that-t">many others</a> throughtout the world, benefited from his guidance.

<p>Please refer to his repository in order to fully grasp the issue.</p>

<br>

<h2>Note 2</h2>

My code differs from the original one in that, instead of an online MongoDB account with cloud services, I have used a local one on my machine (using ```mongosh```).
<p>
  That is, I have changed the ```keys.ts``` file as follows:

  ```typescript
export default {
  mongoURI:
    'mongodb://127.0.0.1:27017/?directConnection=true&serverSelectionTimeoutMS=2000&appName=mongosh+1.10.5',
};
```
</p>
