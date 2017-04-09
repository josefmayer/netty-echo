## Netty 
Building a simple echo server with Netty framework. <br />
Clients sends message an prints out echo.



### Technologies
Netty, ByteBuf, Channels



### Steps
Compile: <br />
*mvn clean compile*

Run EchoServer: <br />
*mvn exec:java -Dexec.mainClass="io.netty.example.echo.EchoServer"*

Run EchoClient: <br />
*mvn exec:java -Dexec.mainClass="io.netty.example.echo.EchoClient"*



