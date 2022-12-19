# Readings

## Intent Filters & Implicit vs. Explicit Intents

**Overview**

- An intent filter declares the capabilities of its parent component — what an activity or service can do and what types of broadcasts a receiver can handle. It opens the component to receiving intents of the advertised type, while filtering out those that are not meaningful for the component
- Implicit intent specifies an action that can be invoked by any app on the device which enables us to perform an action. It does not have exact knowledge about the landing component. It can open another app or its own app’s component and many other options exist.
Examples: Downloaded song, PDF, image, document, dial call, map location, etc. Explicit intent specifies the component in an app. It is one that we use to launch a specific app component, such as a particular activity or service in our application. Using this intent we can pass the data from one activity to another activity.
Examples: startActivity (know about which activity will start), start service to download the file.

## Things I want to know more about. 

- Everything.
