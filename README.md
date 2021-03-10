# test_for_stl
The models is in the `/3dmodel`,what I want to do is show the models in my graph as node.

I have a test dataset in `datasets/test.json`,then set all the nodes to the model.

 `test3d.html` is testing the model , and it could show the model succeessfully.

But `testforstl.html` will return 

```
3d-force-graph:2 THREE.Object3D.add: object not an instance of THREE.Object3D. Promise
add @ 3d-force-graph:2
3d-force-graph:2 THREE.Object3D.add: object not an instance of THREE.Object3D. Promise
add @ 3d-force-graph:2
3d-force-graph:5 Uncaught TypeError: Cannot set property 'x' of undefined
    at 3d-force-graph:5
    at Array.forEach (<anonymous>)
    at 3d-force-graph:5
    at Function.tickFrame (3d-force-graph:5)
    at Function.Object.keys.forEach.i.<computed> [as tickFrame] (3d-force-graph:2)
    at i.Object.keys.forEach.r.<computed> [as tickFrame] (3d-force-graph:5)
    at Function._animationCycle (3d-force-graph:5)
    at Object.keys.forEach.i.<computed> (3d-force-graph:2)
2503d-force-graph:2 Uncaught TypeError: Cannot read property 'test' of undefined
    at xa (3d-force-graph:2)
    at ya.intersectObjects (3d-force-graph:2)
    at 3d-force-graph:2
    at HTMLCanvasElement.g (3d-force-graph:2)
```

I can not work out .Could you please tell how to do this ?Thank you very much.