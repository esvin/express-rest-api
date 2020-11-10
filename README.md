# NodeJS
    Is a open source, cross-platform, Javascript Runtime environment that executes JavaScript code outside a web browser. Brings event-driven programming to web servers,  developmers can create scalable servers without using threading. 
    
    Nodejs operates on a single-thread event loop, using non-blocking I/O calls, allowing it to support ten of thousands of concurrent connections without incurring the cost of thread context switching.
    Node.js was built on top of the Google v8 JavaScript engine. Active LTS 14.x Fermium.
    The design of sharing a single thread among all requests that use observer patter is intended for building highly concurrent applications, where any function performing I/O must use a callback.
    A downside fo this single=threaded approach is that Node.js doesn't allow vertical scaling by increasing the number of CPU cores of the machinge.  Also long-lasting computations and other CPU-bound tasks freeze the entire event-loop until completion.
# Express 
    Is a minimal and flexible we application framework. Is the most popular choice when it comes to building web applications with Node.js. As Backend application, it is the glue between frontend application and potential database.

# Application Level Express Middleware
    A middleware is just a Javascript function which has access to three arguments: req, rest, next.
    Next should be called to notify that the middleware has finished its job.
# Modular Routing with Express Router
    Express offers the Rxpress router to creat such modular routes without mounting them directly to the Express application instance.