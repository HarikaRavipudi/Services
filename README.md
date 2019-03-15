# Services
Serviecs are used for the long running tasks and it works on Main Thread.
These are running in the background even when you close the app.
It doesn't provide User Interface.
Take an example of Music Player uses Foreground Services and that is noticeable to the user.
A background service doesn't need user interaction and it is not directly noticed by the user
Here I am taking a simple player contains StartPlayer and StopPlayer.
When clicks on StartPlayer Player will start.
Even if we close the app the it runs in the background.
When click on StopPlayer the Player will be stopped.
