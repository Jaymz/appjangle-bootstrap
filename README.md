appjangle-bootstrap
===================

Template for creating [appjangle](http://appjangle.com) JavaScript Applications.

For news and announcements, see [@appjangle](https://twitter.com/appjangle) or the [appjangle blog](http://appjangle.blogspot.com).

## Usage

- Create a new HTML page anywhere on your local system using the template `app.html` (you can change the name of the file, if you like).
- Download the textsync.jar and save somewhere on your local system
- Head to [appjangle.com/signup](http://appjangle.com/signup) and get a free appjangle account.
- Launch textsync.jar and enter your appjangle account details.
- Open the app.html and edit it with any editor/IDE of your choice.
 - Add JS code and HTML code at the appropriate location.
 - You can change the layout etc of the HTML page, but you should keep the external dependencies and embed statements.
- 'Drag and Drop' the `app.html` file  onto the running textsync instance.
- Start a textsync synchronization
- Reload your `app.html` file. It should now have a statement in the beginning such as `<-- one.upload [YOUR URL] -->`.
- Copy the URL given at `YOUR URL` and paste it into a browser window. 
- **Important**: Add to the end of the URL `.value.html` and change `https` to `http` at the beginning of the URL. 
