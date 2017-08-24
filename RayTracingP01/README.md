How to use <GL/glut.h> <GLUT/glut.h> in Xcode :

1. Create a new Xcode project in macOS, choose Application "Command Line Tool".
2. Click the project folder on the upper-left corner, then choose "Build Phase".
3. In "Link Binary with Libraries", add OpenGL.framework and GLUT.framework.
4. In your code, change <GL/glut.h> to <GLUT/glut.h>.

Now you are able to use the default glut in Mac.
