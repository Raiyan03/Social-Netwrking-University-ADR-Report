# ADR report on social networking app

# Adoption of Native App Development

## Status

Accepted

## Context

Our project mandates a framework that assures the application will fully integrate into the underlying hardware to provide quality user experience on both platforms: `iOS` and `Android`. For this application, the features that demand high performance, access to device hardware, and look and feel should be native.

## Decision

This is a decision we have resolved to go with. What begs this decision, really, is the question of the high-performing interactions, which will enable seamless integrations of the several device-specific features and always produce a good user experience, platform-bound.

## Consequences

This approach would help maximize the specific features of the platform, leading to better app performance and user interaction. The policy aligns with providing powerful features like advanced graphics, fluid animations, and immediate access to hardware like GPS and the camera. This would involve parallel development tracks for iOS and Android, potentially with different resource needs and a longer development time. However, we believe this decision best aligns with our goal of creating an effective, responsive, and high-quality mobile application.


# Adoption of React Native for Mobile Development

## Status 

Accepted

## Context:

In developing our university social networking. It's out goal to provide a seamless and consistent user experience for both `IOS` and and `Android` users. So it's essential for us to choose a development framework that supports cross platform capabilities to serve our diverse user base.

## Decision

We had seriously considered the merits of several frameworks, and React Native stood out. This was because it supported the cross-platform capabilities in a strong way, hence fitting to our need of targeting the `iOS` and `Android` platforms efficiently. Also, this will be supported by the team's JavaScript knowledge. It will, in general, reduce the learning curve and amount of time for development. React Native has a pretty good ecosystem of libraries that will make it possible to build things like push notifications and data synchronization. In addition, the framework is also supported by offline capabilities: very key to ensuring that the application can remain operational even in cases of network absence, and it is critical in meeting one of the very critical user needs within varying campus connectivity conditions.

## Consequences

This choice will enable our team to capitalise both on the existing knowledge of the team and the available resources in the React Native community for more efficient development and maintenance activity. However, we are open to the mandate of managing sophisticated native functionalities and are fine to accommodate the integration of native modules wherever required. Overall, this approach is in line with our aims of quickly developing cross-platform support and high user engagement.

# Adoption of Node.js for backend services

## Status

Accepted

## Context

A robust, scalable, and efficient backend is crucial for handling the dynamic data exchange and operational demands of our social networking app, including user interactions, data storage, and authentication.

## Decision

The chosen technology for its I/O model is asynchronous, non-blocking, as it can befit the expected high concurrency of the app and real-time data processing needs. It will easily connect the front end to the back end and support the JSON and JavaScript compatibility, thus justifying our choice for React Native. The npm ecosystem is very rich in hosting many libraries and tools that Node.js allows us to use in order to accelerate the development of scalable network applications. What's more, its event-driven architecture suits the real-time features required in our social networking app.

## Consequences

These are the reasons that gave a room for application being done in Node.js: scalability, rapid development, enhanced performance. We, however, still remain committed to ensuring best practices in error handling and security to reduce the potential risk that may arise because JavaScript is an asynchronous language and the environment hosted by Node.js is open.

# Adoption of MongoDB for data storage

## Context

Our application will require an infinitely scalable and adaptive database that can store many kinds of data fields, such as user profiles, posts, and academic resources, and be efficiently queried and accessed to retrieve records.

## Decision

By schema-less nature of MongoDB, we imply that the diversity and dynamism of the data type associated with social networking—those like user profiles, posts, comments, among others—are flexible to accommodate. They are highly scalable and are able to give high performance for large volumes of data, which befits a dynamic environment of a university social network. Easy integration with Node.js makes development Easy. Further, MongoDB offers strong data management features required for real-time data synchronization and capabilities for offline access.

## Consequences

The use of MongoDB for unstructured data will help us well manage the data and be able to scale up as users increase. In doing so, we shall apply the best practices in database designs and security to make sure we guarantee the data's integrity and protection, bearing in mind that this is sensitive educational data.