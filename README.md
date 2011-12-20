# MHDirectoryWatcher
MHDirectoryWatcher monitors a given path for changes, polling file sizes every second to make sure that file transfers are complete.

### Basic usage
Just copy the files into your project, start the watcher using +startWatchingFolderWithPath.
Add an observer for the notification name MHDirectoryDidChangeNotification. 

Call -stopWatching/-startWatching to pause/resume.
