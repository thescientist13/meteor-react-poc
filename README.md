# meteor-react-poc

## Overview
This project is intended to evaluate technologies and tools related to cross-platform / device application development.  
It is mostly interested in understanding the effort to develop mobile apps leveraging web languages and technologies 
where possible.  As the project name implies, the principle tool being evaluated is [Meteor][], which is in and of 
itself a development platform for writing apps in JavaScript.  [React][] is used as the client-side view layer.

It follows this [guide][] from the Meteor docs.

[Meteor]: https://www.meteor.com/
[React]: https://facebook.github.io/react/
[guide]: https://www.meteor.com/tutorials/react/

## Installation
If you haven't, install the latest [Meteor](https://www.meteor.com/install) and [NodeJS](https://nodejs.org/en/download/)

1. Run `meteor npm install`

## Running

1. Run `npm run start`

## Building
Note: To build iOS application, you will need Xcode 7.2 or higher.  Follow the instructions [here][].

### Mobile
1. For iOS, run `meteor run ios`

TODO - android support

[here]: https://guide.meteor.com/mobile.html#installing-prerequisites

## Appendix

### TODO
1. Rest of the guide
2. Hosting

### Interacting with Mongo

1. Start the app - `npm run start`
2. Connect to Mongo - `meteor mongo`
3. Insert some data - `db.tasks.insert({ text: "Hello world!", createdAt: new Date() });`