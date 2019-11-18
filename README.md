This is a sample Unity3D Project to Mjpg streaming it runs a server at given port.

<b>To use:<b>

1. Open "/Assets/Scenes/SampleScene.unity" in Unity3D.

2. Change the port in GameObject "StreamingServer". 

3. Play the scene and wait a few seconds. 

4. Access the mjpeg stream of the game at http://localhost:8080


<b>Instructions<b> 
1. Create sterming server instance in the Start()
2. Push the texture2d to as stream in the update method using  _server.WriteToStream(_jpgTexture);


You may also download StreamingServer.unitypackage and use it. 

Enjoy!
