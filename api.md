This comes directly from the Avaya website. 

**The one-X Agent API** (also known as the Event Notification API) enables developers to create custom clients that can register with one-X Agent and poll for event notifications, making it easy to provide custom screen-pops. The API also enables some basic call control operations to be performed by a custom client. The interface is an XML/HTTP based API where clients make HTTP requests to one-X Agent and receive XML/HTTP responses.

Some of the event notifcation operations enabled by the one-X Agent API include:

RegisterClient: registers a custom client with one-X Agent and creates a notification queue.
NextNotification: Enables the client to get the next notification from its notification queue.
WorkItemAdded: Notifies the client that a work item has been added to its notification queue.
VoiceItemAdded: Notifies the client that a voice item has been added to its notification queue.
IMInteractionCreated: Notifies the client that an instant message item has been added to its notification queue.
Call control operations include:

MakeCall: Enables a client to make an outgoing call, using one-X Agent.
AcceptVoiceInteraction: Enables a client to accept an incoming call, using one-X Agent.
For information about the full set of supported operations, see the Avaya one-X Agent API guide, available for download under Releases for the release of one-X Agent you are using.
