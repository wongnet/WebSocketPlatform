# WebSocketPlatform
<h2>WebSocketPlatform简介</h2>
<p>
WebsocketPlatform项目主要解决高并发场景下的Websocket业务支撑。<br>
传统的服务器与浏览器通信方式为AJAX轮询或长连接通信方式，HTML5新标准提供Websocket解决方案，可以实现服务器与浏览器的
双向异步通信。<br>
实现Websocket服务端的途径大致包括:<br>
<ul>J2EE实现</ul>
<ul>Pywebsocket等</ul>
本项目的大致形势类似于Pywebsocket，是独立于Web容器的一个web组件。<br>
本项目的优点也在于将Websocket与Web容器部分解耦合，方便其他脚本语言例如PHP来使用。<br>
该项目分为单机模式和分布式集群模式。<br>
正在开发的当前项目为单机模式版本，作为单台服务器的Websocket服务端来使用。<br>
分布式集群模式基于Zookeeper开发，可以用来支撑高并发场景下的Websocket通信业务。<br>
</p>
<h2>WebSocketPlatform业务场景与优点</h2>
<ul>将websocket业务单独抽取，实现websocket与web容器解耦合，实现web架构的组件化;</ul>
<ul>方便其他服务端脚本语言，例如：PHP,Python等使用;</ul>
<ul>保证websocket业务在面对大流量、高并发场景下的高可用，抽取websocket实现浏览器与Web服务端的双向异步通信，
可用于解决多种;</ul>
<ul>复杂业务场景，实现更加丰富的B/S功能，使互联网架构更加模块化;</ul>
<ul>提供可定制的编程接口和API，实现业务的高度自由化。</ul>
