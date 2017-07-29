### PRPL - An experimental pattern by Google
###### PRPL is the web development architecture revealed by Google.

We all know now internet users are consuming more time on smart phones.Most of the users won't tolerate applications that take too much time to load. So building applications with more performance and native capabilities is a challenge.Things like service workers perform an important role in app development and enhance the functionalities of any web application.
###### Let's discuss some best web practices with modern web development.
PRPL is an advanced web development pattern which is used to design and optimize the serving of progressive web apps.The term PRPL stands for Push, Render, Precache, Lazyload.
##### Push
 Necessary web components for the initial URL route.This is achieved through the `<link preload>` and http/2.
According to wiki HTTP/2 (originally named HTTP/2.0) is a major revision of the HTTP network protocol used by the World Wide Web. It was derived from the earlier experimental SPDY protocol, originally developed by Google.
##### Render
This part renders the initial route of the web application.
##### Precache 
Different types of networking strategies can be implemented using service worker. The routes can be pre cached.
##### Lazyload
Loads web components according to demand.

This main objective of this pattern is to optimize caching, improve performance and also to make applications more maintainable.Flipkart is currently doing some experiments with this pattern.PRPL should work if the application follows single page structure.

##### PRPL based applications
- [Google polymer shop](https://shop.polymer-project.org/)
- [Polymer HN](https://hnpwa.com/)
##### Resources
- [PRPL by google](https://developers.google.com/web/fundamentals/performance/prpl-pattern/)
- [Planning for perfomance Google I/O](https://youtu.be/RWLzUnESylc?list=PLNYkxOF6rcIBTs2KPy1E6tIYaWoFcG3uj)
- [The PRPL pattern](https://www.google.co.in/url?sa=t&rct=j&q=&esrc=s&source=web&cd=5&cad=rja&uact=8&ved=0ahUKEwiC-vTYnq_VAhVIKo8KHZjxDV8QFghDMAQ&url=https%3A%2F%2Fnews.ycombinator.com%2Fitem%3Fid%3D13751466&usg=AFQjCNFPtSnfiYvYJKuaglGxoGFoS7mPnw)
