<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>
## Welcome to My HomePage!
Hello! This is Chao Zhang, a master student in Columbia University. I am currently proceeding to the degree in Mechanical Engineering.

## What is this Page About?
A project review of the course I recently took. It is **EVOLUTIONARY COMPUTATION&DESIGN AUTOMATION**, a wonderful course and an exciting challenge.

## EA Project Review
### Phase A -> Physical Simulator Creation
Developed By Python & OpenGL. The simulator object is a group of masses and springs. The ground is simply defined as a spring covering the whole ground.
![Image of a cube](/EA1.png)

### Phase B -> Evolving a Robot with a fixed Morphology
In this work a four-leg robot is Created. Each leg is made up of two tetrahedrons. In addition, the main body of the robot is also a  tetrahedron, of which the bottom face is a square instead of  a triangle.  To sum up, there are 13 masses and 34 springs in the robot.
For each spring, its rest length follows the formula $ L=\ L_0\ast(1+a\ast sin(wt+c))$
The parameters k, a, w, c are evolved in the algorithm to achieve a faster motion.
![Image of a series of Robots](/EA2.png)

### Phase C -> Evolving a Robot with variable Morphology
In this part, tree stucture is used as the representation. For each robot, its shape, number of springs and spring parameters are all design to be evolvable in the algorithm.
<iframe width="560" height="315" src="https://www.youtube.com/embed/YRgx3EmoSDY?controls=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Josepher-Echo/Josepher-Echo.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.




