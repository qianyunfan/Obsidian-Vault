# Comments

This is a book from [Learning Modern 3D Graphics Programming (nicolbolas.github.io)](https://nicolbolas.github.io/oldtut/index.html), which consolidates the foundation of computer graphics. I am a noob and i read two chapter of it, it is very clear for me.

# Basic
- Image is made up of 2D pixels(picture element).
- 3D world into a 2D image of that world is called _rendering_.
- Rasterization is a step to render. A rendering system that uses rasterization is called a _rasterizer._ Raterizer use triangle to render everything. Such series of triangle is often called _mesh_ _geometry_ or _model_.
   It is suitable for hardware accelerate because the process of rasterizer is a pipeline, which gets the vertex of triangle and finally outputs image we want. There are 